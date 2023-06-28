# Comparing `tmp/pywa-0.0.1rc11-py3-none-any.whl.zip` & `tmp/pywa-0.0.1rc12-py3-none-any.whl.zip`

## zipinfo {}

```diff
@@ -1,17 +1,17 @@
-Zip file size: 23369 bytes, number of entries: 15
+Zip file size: 24356 bytes, number of entries: 15
 -rw-rw-r--  2.0 unx      117 b- defN 23-Jun-27 07:52 pywa/__init__.py
--rw-rw-r--  2.0 unx       26 b- defN 23-Jun-27 08:15 pywa/__version__.py
--rw-rw-r--  2.0 unx    15077 b- defN 23-Jun-26 17:13 pywa/api.py
--rw-rw-r--  2.0 unx    26563 b- defN 23-Jun-27 08:15 pywa/client.py
--rw-rw-r--  2.0 unx      989 b- defN 23-Jun-19 21:14 pywa/errors.py
--rw-rw-r--  2.0 unx    11047 b- defN 23-Jun-26 16:59 pywa/filters.py
--rw-rw-r--  2.0 unx     1464 b- defN 23-Jun-22 18:21 pywa/handlers.py
--rw-rw-r--  2.0 unx    32457 b- defN 23-Jun-26 17:29 pywa/types.py
+-rw-rw-r--  2.0 unx       26 b- defN 23-Jun-28 10:05 pywa/__version__.py
+-rw-rw-r--  2.0 unx    15070 b- defN 23-Jun-28 09:01 pywa/api.py
+-rw-rw-r--  2.0 unx    26900 b- defN 23-Jun-28 10:04 pywa/client.py
+-rw-rw-r--  2.0 unx     2183 b- defN 23-Jun-28 09:56 pywa/errors.py
+-rw-rw-r--  2.0 unx    14258 b- defN 23-Jun-28 09:56 pywa/filters.py
+-rw-rw-r--  2.0 unx     1630 b- defN 23-Jun-28 09:26 pywa/handlers.py
+-rw-rw-r--  2.0 unx    34313 b- defN 23-Jun-28 09:56 pywa/types.py
 -rw-rw-r--  2.0 unx      991 b- defN 23-Jun-20 16:58 pywa/utils.py
--rw-rw-r--  2.0 unx     4391 b- defN 23-Jun-27 08:09 pywa/webhook.py
--rw-rw-r--  2.0 unx     1066 b- defN 23-Jun-27 08:17 pywa-0.0.1rc11.dist-info/LICENSE
--rw-rw-r--  2.0 unx     4493 b- defN 23-Jun-27 08:17 pywa-0.0.1rc11.dist-info/METADATA
--rw-rw-r--  2.0 unx       92 b- defN 23-Jun-27 08:17 pywa-0.0.1rc11.dist-info/WHEEL
--rw-rw-r--  2.0 unx        5 b- defN 23-Jun-27 08:17 pywa-0.0.1rc11.dist-info/top_level.txt
-?rw-rw-r--  2.0 unx     1105 b- defN 23-Jun-27 08:17 pywa-0.0.1rc11.dist-info/RECORD
-15 files, 99883 bytes uncompressed, 21587 bytes compressed:  78.4%
+-rw-rw-r--  2.0 unx     4391 b- defN 23-Jun-28 10:01 pywa/webhook.py
+-rw-rw-r--  2.0 unx     1066 b- defN 23-Jun-28 10:06 pywa-0.0.1rc12.dist-info/LICENSE
+-rw-rw-r--  2.0 unx     4389 b- defN 23-Jun-28 10:06 pywa-0.0.1rc12.dist-info/METADATA
+-rw-rw-r--  2.0 unx       92 b- defN 23-Jun-28 10:06 pywa-0.0.1rc12.dist-info/WHEEL
+-rw-rw-r--  2.0 unx        5 b- defN 23-Jun-28 10:06 pywa-0.0.1rc12.dist-info/top_level.txt
+?rw-rw-r--  2.0 unx     1106 b- defN 23-Jun-28 10:06 pywa-0.0.1rc12.dist-info/RECORD
+15 files, 106537 bytes uncompressed, 22574 bytes compressed:  78.8%
```

## zipnote {}

```diff
@@ -24,23 +24,23 @@
 
 Filename: pywa/utils.py
 Comment: 
 
 Filename: pywa/webhook.py
 Comment: 
 
-Filename: pywa-0.0.1rc11.dist-info/LICENSE
+Filename: pywa-0.0.1rc12.dist-info/LICENSE
 Comment: 
 
-Filename: pywa-0.0.1rc11.dist-info/METADATA
+Filename: pywa-0.0.1rc12.dist-info/METADATA
 Comment: 
 
-Filename: pywa-0.0.1rc11.dist-info/WHEEL
+Filename: pywa-0.0.1rc12.dist-info/WHEEL
 Comment: 
 
-Filename: pywa-0.0.1rc11.dist-info/top_level.txt
+Filename: pywa-0.0.1rc12.dist-info/top_level.txt
 Comment: 
 
-Filename: pywa-0.0.1rc11.dist-info/RECORD
+Filename: pywa-0.0.1rc12.dist-info/RECORD
 Comment: 
 
 Zip file comment:
```

## pywa/__version__.py

```diff
@@ -1 +1 @@
-__version__ = "0.0.1rc11"
+__version__ = "0.0.1rc12"
```

## pywa/api.py

```diff
@@ -48,15 +48,15 @@
             The response JSON.
 
         Raises:
             WhatsAppApiError: If the request failed.
         """
         res = self._session.request(method=method, url=f"{self._base_url}{endpoint}", **kwargs)
         if res.status_code != 200:
-            raise WhatsAppApiError(status_code=res.status_code, error=res.json()["error"])
+            raise WhatsAppApiError.from_response(status_code=res.status_code, error=res.json()["error"])
         return res.json()
 
     def send_text_message(
             self,
             to: str | int,
             text: str,
             preview_url: bool = False,
@@ -346,15 +346,15 @@
             }
         }
 
         return self._make_request(
             method="POST",
             endpoint=f"/{self.phone_id}/messages",
             json=data
-        )['messages'][0]['id']
+        )
 
     def send_raw_json(
             self,
             data: dict
     ) -> dict:
         """
         Send a raw JSON message to a WhatsApp Cloud API.
```

## pywa/client.py

```diff
@@ -142,24 +142,31 @@
                 WhatsApp client and the incoming callback selection and return a boolean).
         """
         def decorator(func: Callable[["WhatsApp", CallbackSelection], Any]):
             self.add_handler(SelectionCallbackHandler(func, *filters))
             return func
         return decorator
 
-    def on_message_status_change(self, *filters: Callable[["WhatsApp", MessageStatus], bool]):
+    def on_message_status(self, *filters: Callable[["WhatsApp", MessageStatus], bool]):
         """
         Decorator to register a function as a handler for incoming message status changes.
 
+        **DO NOT USE THIS HANDLER TO SEND MESSAGES, IT WILL CAUSE AN INFINITE LOOP!**
+
         Example:
 
-            >>> @wa.on_message_status_change(MessageStatusFilter.READ)
+            >>> @wa.on_message_status(MessageStatusFilter.READ)
             ... def delivered_handler(wa: WhatsApp, status: MessageStatus):
             ...     print(f"Message {status.id} was read by {status.from_user.wa_id}")
 
+            >>> @wa.on_message_status(MessageStatusFilter.FAILED)
+            ... def delivered_handler(wa: WhatsApp, status: MessageStatus):
+            ...     print(f"Message {status.id} failed to send to {status.to_user.wa_id}. error: {status.error.message}
+
+
         Args:
             filters: Filters to apply to the incoming message status changes (filters are function that take the
                 WhatsApp client and the incoming message status change and return a boolean).
         """
         def decorator(func: Callable[["WhatsApp", MessageStatus], Any]):
             self.add_handler(MessageStatusHandler(func, *filters))
             return func
```

## pywa/errors.py

```diff
@@ -1,28 +1,68 @@
 
 
 class WhatsAppApiError(Exception):
     """
-    Represents an error that happened while making a request to the WhatsApp Cloud API.
+    Represents an error that happened while making a request to the WhatsApp Cloud API or incoming error from the webhook.
 
     - See more: https://developers.facebook.com/docs/whatsapp/cloud-api/support/error-codes
 
     Attributes:
-        status_code (int): The status code of the response.
-        error_code (int): The error code.
-        message (str): The error message.
-        details (str): The error details (optional).
-        fbtrace_id (str): The Facebook trace ID.
+        status_code: The status code (in case of response, else None).
+        error_code: The error code.
+        message: The error message.
+        details: The error details (optional).
+        fbtrace_id: The Facebook trace ID (optional).
+        href: The href to the documentation (optional).
     """
     def __init__(
             self,
-            status_code: int,
-            error: dict
+            status_code: int | None,
+            error_code: int,
+            message: str,
+            details: str | None,
+            fbtrace_id: str | None,
+            href: str | None
     ) -> None:
         self.status_code = status_code
-        self.error_code = error["code"]
-        self.message = error["message"]
-        self.details = error.get("error_data", {}).get("details", None)
-        self.fbtrace_id = error["fbtrace_id"]
+        self.error_code = error_code
+        self.message = message
+        self.details = details
+        self.fbtrace_id = fbtrace_id
+        self.href = href
+
+    @classmethod
+    def from_response(
+            cls,
+            status_code: int,
+            error: dict
+    ) -> "WhatsAppApiError":
+        """Create an error from a response."""
+        return cls(
+            status_code=status_code,
+            error_code=error["code"],
+            message=error["message"],
+            details=error.get("error_data", {}).get("details", None),
+            fbtrace_id=error.get("fbtrace_id"),
+            href=error.get('href')
+        )
+
+    @classmethod
+    def from_incoming_error(
+            cls,
+            error: dict
+    ) -> "WhatsAppApiError":
+        """Create an error from an incoming error."""
+        return cls(
+            status_code=None,
+            error_code=error["code"],
+            message=error["message"],
+            details=error.get("error_data", {}).get("details", None),
+            fbtrace_id=error.get("fbtrace_id"),
+            href=error.get('href')
+        )
 
     def __str__(self) -> str:
         return f"WhatsAppApiError(status_code={self.status_code}, message={self.message!r}, details={self.details!r})"
+
+    def __repr__(self) -> str:
+        return self.__str__()
```

## pywa/filters.py

```diff
@@ -31,32 +31,64 @@
 class TextFilter:
     """Useful filters for text messages."""
 
     ANY: Callable[[Wa, Msg], bool] = lambda wa, m: m.type == Mt.TEXT
     """Filter for all text messages."""
 
     @staticmethod
-    def equals(*matches: str) -> Callable[[Wa, Msg], bool]:
-        """Filter for text messages that equal the given text/s."""
-        return lambda wa, m: m.type == Mt.TEXT and any((t == m.text for t in matches))
+    def equals(*matches: str, ignore_case: bool = False) -> Callable[[Wa, Msg], bool]:
+        """
+        Filter for text messages that equal the given text/s.
+
+        Args:
+            matches: The text/s to filter for.
+            ignore_case: Whether to ignore case when matching (default: ``False``).
+        """
+        return lambda wa, m: m.type == Mt.TEXT and any(
+            (m.text.lower() == t.lower() if ignore_case else m.text == t for t in matches)
+        )
 
     @staticmethod
-    def contains(*matches: str) -> Callable[[Wa, Msg], bool]:
-        """Filter for text messages that contain the given text/s."""
-        return lambda wa, m: m.type == Mt.TEXT and any((t in m.text for t in matches))
+    def contains(*matches: str, ignore_case: bool = False) -> Callable[[Wa, Msg], bool]:
+        """
+        Filter for text messages that contain the given text/s.
+
+        Args:
+            matches: The text/s to filter for.
+            ignore_case: Whether to ignore case when matching. (default: ``False``).
+        """
+        return lambda wa, m: m.type == Mt.TEXT and any(
+            (t.lower() in m.text.lower() if ignore_case else t in m.text for t in matches)
+        )
 
     @staticmethod
-    def startswith(*matches: str) -> Callable[[Wa, Msg], bool]:
-        """Filter for text messages that start with the given text/s."""
-        return lambda wa, m: m.type == Mt.TEXT and any((m.text.startswith(t) for t in matches))
+    def startswith(*matches: str, ignore_case: bool = False) -> Callable[[Wa, Msg], bool]:
+        """
+        Filter for text messages that start with the given text/s.
+
+        Args:
+            matches: The text/s to filter for.
+            ignore_case: Whether to ignore case when matching (default: ``False``).
+        """
+        return lambda wa, m: m.type == Mt.TEXT and any(
+            (m.text.lower().startswith(t.lower()) if ignore_case else m.text.startswith(t) for t in matches)
+        )
 
     @staticmethod
-    def endswith(*matches: str) -> Callable[[Wa, Msg], bool]:
-        """Filter for text messages that end with the given text/s."""
-        return lambda wa, m: m.type == Mt.TEXT and any((m.text.endswith(t) for t in matches))
+    def endswith(*matches: str, ignore_case: bool = False) -> Callable[[Wa, Msg], bool]:
+        """
+        Filter for text messages that end with the given text/s.
+
+        Args:
+            matches: The text/s to filter for.
+            ignore_case: Whether to ignore case when matching (default: ``False``).
+        """
+        return lambda wa, m: m.type == Mt.TEXT and any(
+            (m.text.lower().endswith(t.lower()) if ignore_case else m.text.endswith(t) for t in matches)
+        )
 
     @staticmethod
     def regex(*patterns: str | re.Pattern, flags: int = 0) -> Callable[[Wa, Msg], bool]:
         """
         Filter for text messages that match the given regex/regexes.
             * It's recommended to pass compiled regexes to save time (``re.compile(your_pattern)``)
         """
@@ -69,23 +101,28 @@
 
         Args:
             lengths: The length range/s to filter for (e.g. (1, 10), (50, 100)).
         """
         return lambda wa, m: m.type == Mt.TEXT and any((i[0] <= len(m.text) <= i[1] for i in lengths))
 
     @staticmethod
-    def command(*cmds: str, prefixes: str | Iterable[str] = "!") -> Callable[[Wa, Msg], bool]:
+    def command(*cmds: str, prefixes: str | Iterable[str] = "!", ignore_case: bool = False) -> Callable[
+        [Wa, Msg], bool]:
         """
         Filter for text messages that are commands.
 
         Args:
             cmds: The command/s to filter for (e.g. "start", "hello").
             prefixes: The prefix/s to filter for (default: "!", i.e. "!start").
+            ignore_case: Whether to ignore case when matching (default: ``False``).
         """
-        return lambda wa, m: m.type == Mt.TEXT and any(m.text[0] in prefixes and m.text[1:].startswith(c) for c in cmds)
+        return lambda wa, m: m.type == Mt.TEXT and any(
+            m.text[0] in prefixes and (m.text[1:] if not ignore_case else m.text[1:].lower())
+            .startswith((c if not ignore_case else c.lower()) for c in cmds)
+        )
 
 
 class ImageFilter:
     """Useful filters for image messages."""
 
     ANY: Callable[[Wa, Msg], bool] = lambda wa, m: m.type == Mt.IMAGE
     """Filter for all image messages."""
@@ -195,21 +232,25 @@
         return _in_radius
 
 
 class ReactionFilter:
     """Useful filters for reaction messages."""
 
     ANY: Callable[[Wa, Msg], bool] = lambda wa, m: m.type == Mt.REACTION
-    """Filter for all reaction messages."""
+    """Filter for all reaction updates (added or removed)."""
+
+    ADDED: Callable[[Wa, Msg], bool] = lambda wa, m: m.type == Mt.REACTION and m.reaction.emoji is not None
+    """Filter for reaction messages that were added."""
+
+    REMOVED: Callable[[Wa, Msg], bool] = lambda wa, m: m.type == Mt.REACTION and m.reaction.emoji is None
+    """Filter for reaction messages that were removed."""
 
     @staticmethod
     def emoji(*emojis: str) -> Callable[[Wa, Msg], bool]:
-        """
-        Filter for custom reaction messages. pass emojis as strings.
-        """
+        """Filter for custom reaction messages. pass emojis as strings."""
         return lambda wa, m: m.type == Mt.REACTION and m.reaction.emoji in emojis
 
 
 class ContactsFilter:
     """Useful filters for contact messages."""
 
     ANY: Callable[[Wa, Msg], bool] = lambda wa, m: m.type == Mt.CONTACTS
@@ -242,33 +283,65 @@
     ANY: Callable[[Wa, Msg], bool] = lambda wa, m: m.type == Mt.UNSUPPORTED
     """Filter for all unsupported messages."""
 
 
 class CallbackFilter:
     """Useful filters for callback queries."""
 
+    ANY: Callable[[Wa, CallbackButton | CallbackSelection], bool] = lambda wa, c: True
+    """Filter for all callback queries (the default)."""
+
     @staticmethod
-    def data_equals(*matches: str) -> Callable[[Wa, CallbackButton | CallbackSelection], bool]:
-        """Filter for callbacks their data equals the given string/s."""
-        return lambda wa, c: any((c.data == m for m in matches))
+    def data_equals(*matches: str, ignore_case: bool = False) -> Callable[
+        [Wa, CallbackButton | CallbackSelection], bool]:
+        """
+        Filter for callbacks their data equals the given string/s.
+
+        Args:
+            matches: The string/s to match.
+            ignore_case: Whether to ignore case when matching (default: False).
+        """
+        return lambda wa, c: any((c.data.lower() == m.lower() if ignore_case else c.data == m for m in matches))
 
     @staticmethod
-    def data_startswith(*matches: str) -> Callable[[Wa, CallbackButton | CallbackSelection], bool]:
-        """Filter for callbacks their data starts with the given string/s."""
-        return lambda wa, c: any((c.data.startswith(m) for m in matches))
+    def data_startswith(*matches: str, ignore_case: bool = False) -> Callable[[Wa, CallbackButton | CallbackSelection], bool]:
+        """
+        Filter for callbacks their data starts with the given string/s.
+
+        Args:
+            matches: The string/s to match.
+            ignore_case: Whether to ignore case when matching (default: False).
+        """
+        return lambda wa, c: any(
+            (c.data.lower().startswith(m.lower()) if ignore_case else c.data.startswith(m) for m in matches)
+        )
 
     @staticmethod
-    def data_endswith(*matches: str) -> Callable[[Wa, CallbackButton | CallbackSelection], bool]:
-        """Filter for callbacks their data ends with the given string/s."""
-        return lambda wa, c: any((c.data.endswith(m) for m in matches))
+    def data_endswith(*matches: str, ignore_case: bool = False) -> Callable[[Wa, CallbackButton | CallbackSelection], bool]:
+        """
+        Filter for callbacks their data ends with the given string/s.
+
+        Args:
+            matches: The string/s to match.
+            ignore_case: Whether to ignore case when matching (default: False).
+        """
+        return lambda wa, c: any(
+            (c.data.lower().endswith(m.lower()) if ignore_case else c.data.endswith(m) for m in matches)
+        )
 
     @staticmethod
-    def data_contains(*matches: str) -> Callable[[Wa, CallbackButton | CallbackSelection], bool]:
-        """Filter for callbacks their data contains the given string/s."""
-        return lambda wa, c: any((m in c.data for m in matches))
+    def data_contains(*matches: str, ignore_case: bool = False) -> Callable[[Wa, CallbackButton | CallbackSelection], bool]:
+        """
+        Filter for callbacks their data contains the given string/s.
+
+        Args:
+            matches: The string/s to match.
+            ignore_case: Whether to ignore case when matching (default: False).
+        """
+        return lambda wa, c: any((m in c.data.lower() if ignore_case else m in c.data for m in matches))
 
     @staticmethod
     def data_regex(*patterns: str | re.Pattern) -> Callable[[Wa, CallbackButton | CallbackSelection], bool]:
         """
         Filter for callbacks their data matches the given regex/regexes.
             * It's recommended to pass compiled regexes to save time (``re.compile(your_pattern)``)
         """
@@ -282,7 +355,15 @@
     """Filter for messages that have been sent."""
 
     DELIVERED: Callable[[Wa, Ms], bool] = lambda wa, data: data.status == Mst.DELIVERED
     """Filter for messages that have been delivered."""
 
     READ: Callable[[Wa, Ms], bool] = lambda wa, data: data.status == Mst.READ
     """Filter for messages that have been read."""
+
+    FAILED: Callable[[Wa, Ms], bool] = lambda wa, data: data.status == Mst.FAILED
+    """Filter for messages that have failed to send (than you can access to the ``error`` attribute)."""
+
+    @staticmethod
+    def failed_on_error_code(*codes: int) -> Callable[[Wa, Ms], bool]:
+        """Filter for messages that have failed to send with the given error code/s."""
+        return lambda wa, s: s.status == Mst.FAILED and s.error.error_code in codes
```

## pywa/handlers.py

```diff
@@ -27,29 +27,34 @@
 
     def __call__(self, wa: "WhatsApp", data: Any):
         if all([f(wa, data) for f in self.filters]):
             self.handler(wa, data)
 
 
 class MessageHandler(Handler):
-    __handler_type__ = "message"
     """A message handler (e.g. text, image, video, audio, etc.)."""
+    __handler_type__ = "message"
 
 
 class ButtonCallbackHandler(Handler):
-    __handler_type__ = "button"
     """A button handler."""
+    __handler_type__ = "button"
 
 
 class SelectionCallbackHandler(Handler):
-    __handler_type__ = "selection"
     """A section handler."""
+    __handler_type__ = "selection"
 
 
 class RawUpdateHandler(Handler):
-    __handler_type__ = "raw_update"
     """A raw update handler."""
+    __handler_type__ = "raw_update"
 
 
 class MessageStatusHandler(Handler):
+    """
+    A message status handler (e.g. delivered, read, failed, etc.).
+
+    **DO NOT USE THIS HANDLER TO SEND MESSAGES, IT WILL CAUSE AN INFINITE LOOP!**
+    """
     __handler_type__ = "message_status"
     """A message status handler (e.g. delivered, read, etc.)."""
```

## pywa/types.py

```diff
@@ -15,16 +15,16 @@
     "MediaUrlResponse"
 )
 
 from datetime import datetime
 from dataclasses import dataclass, field, asdict
 from enum import Enum
 from typing import TYPE_CHECKING, Iterable
-
 from pywa import utils
+from pywa.errors import WhatsAppApiError
 
 if TYPE_CHECKING:
     from pywa.client import WhatsApp
 
 
 @dataclass(frozen=True, slots=True)
 class InlineButton:
@@ -130,14 +130,15 @@
     IMAGE = "image"
     STICKER = "sticker"
     VIDEO = "video"
     REACTION = "reaction"
     LOCATION = "location"
     CONTACTS = "contacts"
     INTERACTIVE = "interactive"
+    MESSAGE_STATUS = "message_status"  # Not a real message type, used for MessageStatus
     UNSUPPORTED = "unsupported"
 
     # SYSTEM = "system"
     # ORDER = "order"
 
     @classmethod
     def _missing_(cls, value):
@@ -262,18 +263,18 @@
 @dataclass(frozen=True, slots=True)
 class Reaction:
     """
     Represents a reaction to a message.
 
     Attributes:
         message_id: The ID of the message that was reacted to.
-        emoji: The emoji that was used to react to the message.
+        emoji: The emoji that was used to react to the message (optional, ``None`` if removed).
     """
     message_id: str
-    emoji: str
+    emoji: str | None = None
 
     @classmethod
     def from_dict(cls, data: dict | None):
         return cls(**data) if data else None
 
 
 @dataclass(frozen=True, slots=True)
@@ -373,18 +374,18 @@
     org: Org | None = None
 
     @classmethod
     def from_dict(cls, data: dict | None):
         return cls(
             name=cls.Name(**data["name"]),
             birthday=data.get("birthday"),
-            phones=[cls.Phone.from_dict(phone) for phone in data.get("phones", [])],
-            emails=[cls.Email.from_dict(email) for email in data.get("emails", [])],
-            urls=[cls.Url.from_dict(url) for url in data.get("urls", [])],
-            addresses=[cls.Address.from_dict(address) for address in data.get("addresses", [])],
+            phones=[cls.Phone.from_dict(phone) for phone in data.get("phones", ())],
+            emails=[cls.Email.from_dict(email) for email in data.get("emails", ())],
+            urls=[cls.Url.from_dict(url) for url in data.get("urls", ())],
+            addresses=[cls.Address.from_dict(address) for address in data.get("addresses", ())],
             org=cls.Org.from_dict(data.get("org")),
         ) if data else None
 
     def to_dict(self) -> dict:
         return {
             "name": asdict(self.name),
             "birthday": self.birthday,
@@ -546,22 +547,28 @@
 
 
 @dataclass(frozen=True, slots=True)
 class BaseUpdate:
     """Base class for all update types."""
     _client: WhatsApp = field(repr=False, hash=False, compare=False)
     id: str
+    type: MessageType
     metadata: Metadata
     from_user: User
     timestamp: datetime
 
     @property
     def sender(self) -> str:
         return self.from_user.wa_id
 
+    @property
+    def message_id_to_reply(self) -> str:
+        """The ID of the message to reply to."""
+        return self.id
+
     def reply_text(
             self,
             text: str,
             preview_url: bool = False,
             quote: bool = False,
             keyboard: list[InlineButton] | SectionList | None = None,
             header: str | None = None,
@@ -581,15 +588,15 @@
         Returns:
             The ID of the sent message.
         """
         return self._client.send_message(
             to=self.sender,
             text=text,
             preview_url=preview_url,
-            reply_to_message_id=self.id if quote else None,
+            reply_to_message_id=self.message_id_to_reply if quote else None,
             keyboard=keyboard,
             header=header,
             footer=footer
         )
 
     def reply_image(
             self,
@@ -614,15 +621,15 @@
         Returns:
             The ID of the sent message.
         """
         return self._client.send_image(
             to=self.sender,
             image=image,
             caption=caption,
-            reply_to_message_id=self.id if quote else None,
+            reply_to_message_id=self.message_id_to_reply if quote else None,
             buttons=buttons,
             body=body,
             footer=footer
         )
 
     def reply_video(
             self,
@@ -647,15 +654,15 @@
         Returns:
             The ID of the sent message.
         """
         return self._client.send_video(
             to=self.sender,
             video=video,
             caption=caption,
-            reply_to_message_id=self.id if quote else None,
+            reply_to_message_id=self.message_id_to_reply if quote else None,
             buttons=buttons,
             body=body,
             footer=footer
         )
 
     def reply_document(
             self,
@@ -683,15 +690,15 @@
             The ID of the sent message.
         """
         return self._client.send_document(
             to=self.sender,
             document=document,
             filename=filename,
             caption=caption,
-            reply_to_message_id=self.id if quote else None,
+            reply_to_message_id=self.message_id_to_reply if quote else None,
             buttons=buttons,
             body=body,
             footer=footer
         )
 
     def reply_audio(
             self,
@@ -707,15 +714,15 @@
 
         Returns:
             The ID of the sent message.
         """
         return self._client.send_audio(
             to=self.sender,
             audio=audio,
-            reply_to_message_id=self.id if quote else None
+            reply_to_message_id=self.message_id_to_reply if quote else None
         )
 
     def reply_sticker(
             self,
             sticker: str | bytes,
             animated: bool = False,
             quote: bool = False,
@@ -731,15 +738,15 @@
         Returns:
             The ID of the sent message.
         """
         return self._client.send_sticker(
             to=self.sender,
             sticker=sticker,
             animated=animated,
-            reply_to_message_id=self.id if quote else None
+            reply_to_message_id=self.message_id_to_reply if quote else None
         )
 
     def reply_location(
             self,
             latitude: float,
             longitude: float,
             name: str | None = None,
@@ -779,15 +786,15 @@
 
         Returns:
             The ID of the sent message.
         """
         return self._client.send_contact(
             to=self.sender,
             contact=contact,
-            reply_to_message_id=self.id if quote else None
+            reply_to_message_id=self.message_id_to_reply if quote else None
         )
 
     def react(
             self,
             emoji: str,
     ) -> str:
         """
@@ -798,42 +805,42 @@
 
         Returns:
             The ID of the sent message.
         """
         return self._client.send_reaction(
             to=self.sender,
             emoji=emoji,
-            message_id=self.id
+            message_id=self.message_id_to_reply
         )
 
     def unreact(
             self,
     ) -> str:
         """
         Remove the reaction from the message.
 
         Returns:
             The ID of the sent message.
         """
         return self._client.remove_reaction(
             to=self.sender,
-            message_id=self.id
+            message_id=self.message_id_to_reply
         )
 
     def mark_as_read(
             self
     ) -> bool:
         """
         Mark the message as read.
 
         Returns:
             Whether it was successful.
         """
         return self._client.mark_message_as_read(
-            message_id=self.id
+            message_id=self.message_id_to_reply
         )
 
 
 @dataclass(frozen=True, slots=True)
 class Message(BaseUpdate):
     """
     A message received from a user.
@@ -854,49 +861,52 @@
         sticker: The sticker of the message (if the message type is sticker). (optional)
         document: The document of the message (if the message type is document). (optional)
         audio: The audio of the message (if the message type is audio). (optional)
         reaction: The reaction of the message (if the message type is reaction). (optional)
         location: The location of the message (if the message type is location). (optional)
         contacts: The contacts of the message (if the message type is contacts). (optional)
     """
-    type: MessageType
     reply_to_message: ReplyToMessage | None
     forwarded: bool
     text: str | None
     image: Image | None
     video: Video | None
     sticker: Sticker | None
     document: Document | None
     audio: Audio | None
     reaction: Reaction | None
     location: Location | None
     contacts: list[Contact] | None
 
+    @property
+    def message_id_to_reply(self) -> str:
+        """The ID of the message"""
+        return self.id if self.type != MessageType.REACTION else self.reaction.message_id
+
     @classmethod
     def from_dict(cls, client: WhatsApp, value: dict):
         message = value['messages'][0]
-        msg_type = MessageType(message['type'])
         return cls(
             _client=client,
             id=message['id'],
-            type=msg_type,
+            type=MessageType(message['type']),
             from_user=User.from_dict(value['contacts'][0]),
             timestamp=datetime.fromtimestamp(int(message['timestamp'])),
             metadata=Metadata(**value['metadata']),
             forwarded=message.get('context', {}).get('forwarded', False),
             reply_to_message=ReplyToMessage.from_dict(message.get('context')),
             text=message['text']['body'] if 'text' in message else None,
             image=Image.from_dict(client=client, data=message.get('image')),
             video=Video.from_dict(client=client, data=message.get('video')),
             sticker=Sticker.from_dict(client=client, data=message.get('sticker')),
             document=Document.from_dict(client=client, data=message.get('document')),
             audio=Audio.from_dict(client=client, data=message.get('audio')),
             reaction=Reaction.from_dict(message.get('reaction')),
             location=Location.from_dict(message.get('location')),
-            contacts=[Contact.from_dict(contact) for contact in message.get('contacts', [])] or None
+            contacts=[Contact.from_dict(contact) for contact in message.get('contacts', ())] or None
         )
 
     def download_media(
             self,
             filepath: str | None = None,
             filename: str | None = None,
             in_memory: bool = False,
@@ -925,75 +935,95 @@
 class CallbackButton(BaseUpdate):
     """
     Represents a callback button.
 
     Attributes:
         id: The ID of the message.
         metadata: The metadata of the message (to which phone number it was sent).
+        type: The message type (always ``interactive``).
         from_user: The user who sent the message.
         timestamp: The timestamp when the message was sent.
+        reply_to_message: The message to which this callback button is a reply to.
         data: The data of the button.
         title: The title of the button.
     """
+    reply_to_message: ReplyToMessage
     data: str
     title: str
 
+    @property
+    def message_id_to_reply(self) -> str:
+        """The ID of the message to reply to"""
+        return self.reply_to_message.message_id
+
     @classmethod
     def from_dict(cls, client: WhatsApp, value: dict):
         message = value['messages'][0]
         return cls(
             _client=client,
             id=message['id'],
             metadata=Metadata(**value['metadata']),
+            type=MessageType(message['type']),
             from_user=User.from_dict(value['contacts'][0]),
             timestamp=datetime.fromtimestamp(int(message['timestamp'])),
+            reply_to_message=ReplyToMessage.from_dict(message['context']),
             data=message['interactive']['button_reply']['id'],
             title=message['interactive']['button_reply']['title']
         )
 
 
 @dataclass(frozen=True, slots=True)
 class CallbackSelection(BaseUpdate):
     """
     Represents a callback selection.
 
     Attributes:
         id: The ID of the message.
         metadata: The metadata of the message (to which phone number it was sent).
+        type: The message type (always ``interactive``).
         from_user: The user who sent the message.
         timestamp: The timestamp when the message was sent.
+        reply_to_message: The message to which this callback selection is a reply to.
         data: The data of the selection.
         title: The title of the selection.
         description: The description of the selection (optional).
     """
+    reply_to_message: ReplyToMessage
     data: str
     title: str
     description: str | None
 
+    @property
+    def message_id_to_reply(self) -> str:
+        """The ID of the message to reply to"""
+        return self.reply_to_message.message_id
+
     @classmethod
     def from_dict(cls, client: WhatsApp, value: dict):
         message = value['messages'][0]
         return cls(
             _client=client,
             id=message['id'],
             metadata=Metadata(**value['metadata']),
+            type=MessageType(message['type']),
             from_user=User.from_dict(value['contacts'][0]),
             timestamp=datetime.fromtimestamp(int(message['timestamp'])),
+            reply_to_message=ReplyToMessage.from_dict(message['context']),
             data=message['interactive']['list_reply']['id'],
             title=message['interactive']['list_reply']['title'],
             description=message['interactive']['list_reply'].get('description')
         )
 
 
 class MessageStatusType(Enum):
     """Message status type."""
     SENT = 'sent'
     DELIVERED = 'delivered'
     READ = 'read'
-    timestamp: datetime
+    FAILED = 'failed'
 
 
 @dataclass(frozen=True, slots=True)
 class MessageStatus(BaseUpdate):
     """
     Represents the status of a message.
 
@@ -1001,21 +1031,27 @@
 
     Attributes:
         id: The ID of the message that the status is for.
         metadata: The metadata of the message (to which phone number it was sent).
         status: The status of the message.
         timestamp: The timestamp when the status was updated.
         from_user: The user who the message was sent to.
+        error: The error that occurred (if status is ``failed``).
     """
     status: MessageStatusType
+    error: WhatsAppApiError | None
 
     @classmethod
     def from_dict(cls, client: WhatsApp, value: dict):
         status = value['statuses'][0]
+        status_type = MessageStatusType(status['status'])
         return cls(
             _client=client,
             id=status['id'],
             metadata=Metadata(**value['metadata']),
-            status=MessageStatusType(status['status']),
+            type=MessageType.MESSAGE_STATUS,
+            status=status_type,
             timestamp=datetime.fromtimestamp(int(status['timestamp'])),
-            from_user=User(wa_id=status['recipient_id'], name=None)
+            from_user=User(wa_id=status['recipient_id'], name=None),
+            error=WhatsAppApiError.from_incoming_error(status['errors'][0])
+            if status_type == MessageStatusType.FAILED else None
         )
```

## Comparing `pywa-0.0.1rc11.dist-info/LICENSE` & `pywa-0.0.1rc12.dist-info/LICENSE`

 * *Files identical despite different names*

## Comparing `pywa-0.0.1rc11.dist-info/METADATA` & `pywa-0.0.1rc12.dist-info/METADATA`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pywa
-Version: 0.0.1rc11
+Version: 0.0.1rc12
 Summary: Python wrapper for the WhatsApp Cloud API
 Download-URL: https://pypi.org/project/pywa/
 Author: David Lev
 Author-email: davidlev@telegmail.com
 License: MIT
 Project-URL: Documentation, https://github.com/david-lev/pywa#readme
 Project-URL: Issue Tracker, https://github.com/david-lev/pywa/issues
@@ -30,18 +30,18 @@
 Requires-Dist: flask ; extra == 'flask'
 
 .. image:: https://i.imgur.com/hbGP0rW.png
   :width: 200
   :alt: PyWa Logo
 .. end-logo
 
-`pywa <https://github.com/david-lev/pywa>`_: Python wrapper for the WhatsApp Cloud API
-######################################################################################
+`PyWa <https://github.com/david-lev/pywa>`_ • Python wrapper for the WhatsApp Cloud API
+########################################################################################
 
-THIS IS A WORK IN PROGRESS. DO NOT USE IN PRODUCTION.
+**THIS IS A WORK IN PROGRESS. DO NOT USE IN PRODUCTION.**
 
 
 .. image:: https://img.shields.io/pypi/dm/pywa?style=flat-square
     :alt: PyPI Downloads
     :target: https://pypi.org/project/pywa/
 
 .. image:: https://badge.fury.io/py/pywa.svg
@@ -59,15 +59,14 @@
 .. image:: https://badges.aleen42.com/src/telegram.svg
    :target: https://t.me/py_wa
    :alt: Telegram
 
 ________________________
 
 
-
 🎛 Installation
 --------------
 .. installation
 
 - **Install using pip3:**
 
 .. code-block:: bash
@@ -79,23 +78,20 @@
     # or:
     pip3 install -U pywa[fastapi]
 
 - **Install from source:**
 
 .. code-block:: bash
 
-    git clone https://github.com/david-lev/pywa.git
-    cd pywa && python3 setup.py install
+    pip3 install -U git+https://github.com/david-lev/pywa.git
 
 .. end-installation
 
 ----------------------------------------
 
-**DOCUMENTATION WILL BE AVAILABLE SOON**
-----------------------------------------
 
 👨‍💻 **Usage**
 ----------------
 
 - Create a WhatsApp client and send a message
```

## Comparing `pywa-0.0.1rc11.dist-info/RECORD` & `pywa-0.0.1rc12.dist-info/RECORD`

 * *Files 22% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 pywa/__init__.py,sha256=u98CpT0wYk8-XDPUGB_hW-a_23agBkzTSzfwmoqnsE0,117
-pywa/__version__.py,sha256=GVsyXElC308caK4I6LjYEqfIc3Uw7LhtajV62yNE0xM,26
-pywa/api.py,sha256=zW7zrkDcWB7df5B0FW2GM6an5wn1cMXxuMCD19krOLU,15077
-pywa/client.py,sha256=7s-7J9Pb-WLGwD6eizYnZj_pzCwODVH4ssHBwldkR9E,26563
-pywa/errors.py,sha256=Vs5SJehEt5PhUrJBbia710gpusoxmTPQmlgDBBnYpWM,989
-pywa/filters.py,sha256=9t2ckte1_gRaKNF6LlISgNY2up3CN7Gnx7IQ1cSEue8,11047
-pywa/handlers.py,sha256=Z4j2jiEwQ0_mzlcybHFDmRg7OR8agakXXkzU85eQyGk,1464
-pywa/types.py,sha256=ooFguLLhqx6Y25zyuqQ9O1knwXkWsx-at0RMJhD1Z6g,32457
+pywa/__version__.py,sha256=Q4681157_dITDwXmPcLXHmK1bppz7txCwBG3wi2LLhA,26
+pywa/api.py,sha256=CHh9VAI0Wa-4_2gDxT0aThCm-whIhCM4JZVUGrx7rUw,15070
+pywa/client.py,sha256=dN3l8DJmlXHmVQPfDa8bt-HFB-ub9HKJvfeiqNd7CmA,26900
+pywa/errors.py,sha256=VdM4q6XtWY5sR_b1j2a1F6oq2ctmqm2nLTmN6acfpBI,2183
+pywa/filters.py,sha256=jOfzDR9TIlFJvlCCqAFVeQxgEbpDX4dLqj5bdDPOtsk,14258
+pywa/handlers.py,sha256=fb6CKJ7A_EhLdIynR5ilHeZ5VnfnvRcT6JpxNnzTVXk,1630
+pywa/types.py,sha256=IXPH8C5-Fu0Rpwy3KwsyZSXXdfxoFgeJlgUWMwFnxUI,34313
 pywa/utils.py,sha256=GRTfSvmsuOBd1_Yw2c90XoALqVPuy6HzyvJuqg3xjtI,991
 pywa/webhook.py,sha256=ZRqfm8b0-_U-Bx7dw_ATfuyU1EcyWCbz3UFdo4LHdSU,4391
-pywa-0.0.1rc11.dist-info/LICENSE,sha256=RwljuP8WgWttLkSivccHoHEFSDhOY8aLM_vg6Ix48yQ,1066
-pywa-0.0.1rc11.dist-info/METADATA,sha256=kRs8Za6MRJctDTJbvX6xc2fiN9RMoLEV9GWfonRcLKQ,4493
-pywa-0.0.1rc11.dist-info/WHEEL,sha256=2wepM1nk4DS4eFpYrW1TTqPcoGNfHhhO_i5m4cOimbo,92
-pywa-0.0.1rc11.dist-info/top_level.txt,sha256=Cl24ggXVvxvOUnQfKRASer1LzHxpYCPZd5ZcVyS98Oo,5
-pywa-0.0.1rc11.dist-info/RECORD,,
+pywa-0.0.1rc12.dist-info/LICENSE,sha256=RwljuP8WgWttLkSivccHoHEFSDhOY8aLM_vg6Ix48yQ,1066
+pywa-0.0.1rc12.dist-info/METADATA,sha256=AEOyFofu73lJielRbiOg0IO7bg_d2iGAohkZH-n2AdI,4389
+pywa-0.0.1rc12.dist-info/WHEEL,sha256=2wepM1nk4DS4eFpYrW1TTqPcoGNfHhhO_i5m4cOimbo,92
+pywa-0.0.1rc12.dist-info/top_level.txt,sha256=Cl24ggXVvxvOUnQfKRASer1LzHxpYCPZd5ZcVyS98Oo,5
+pywa-0.0.1rc12.dist-info/RECORD,,
```

