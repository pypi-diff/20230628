# Comparing `tmp/neon-skill-alerts-1.5.2a4.tar.gz` & `tmp/neon-skill-alerts-1.5.2a5.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "neon-skill-alerts-1.5.2a4.tar", last modified: Mon Jun 26 17:10:04 2023, max compression
+gzip compressed data, was "neon-skill-alerts-1.5.2a5.tar", last modified: Wed Jun 28 00:04:00 2023, max compression
```

## Comparing `neon-skill-alerts-1.5.2a4.tar` & `neon-skill-alerts-1.5.2a5.tar`

### file list

```diff
@@ -1,134 +1,138 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 17:10:04.149191 neon-skill-alerts-1.5.2a4/
--rw-r--r--   0 runner    (1001) docker     (123)     1635 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/LICENSE.md
--rw-r--r--   0 runner    (1001) docker     (123)     2532 2023-06-26 17:10:04.149191 neon-skill-alerts-1.5.2a4/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     2274 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/README.md
--rw-r--r--   0 runner    (1001) docker     (123)    62733 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 17:10:04.133191 neon-skill-alerts-1.5.2a4/locale/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 17:10:04.137191 neon-skill-alerts-1.5.2a4/locale/en-us/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 17:10:04.141191 neon-skill-alerts-1.5.2a4/locale/en-us/dialog/
--rw-r--r--   0 runner    (1001) docker     (123)       68 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/dialog/confirm_alert_playback.dialog
--rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/dialog/confirm_alert_recurring.dialog
--rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/dialog/confirm_alert_recurring_playback.dialog
--rw-r--r--   0 runner    (1001) docker     (123)       61 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/dialog/confirm_alert_recurring_script.dialog
--rw-r--r--   0 runner    (1001) docker     (123)       67 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/dialog/confirm_alert_script.dialog
--rw-r--r--   0 runner    (1001) docker     (123)       51 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/dialog/confirm_alert_set.dialog
--rw-r--r--   0 runner    (1001) docker     (123)       29 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/dialog/confirm_cancel_alert.dialog
--rw-r--r--   0 runner    (1001) docker     (123)       30 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/dialog/confirm_cancel_all.dialog
--rw-r--r--   0 runner    (1001) docker     (123)       19 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/dialog/confirm_dismiss_alert.dialog
--rw-r--r--   0 runner    (1001) docker     (123)       35 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/dialog/confirm_snooze_alert.dialog
--rw-r--r--   0 runner    (1001) docker     (123)       37 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/dialog/confirm_timer_started.dialog
--rw-r--r--   0 runner    (1001) docker     (123)       97 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/dialog/error_audio_reminder_too_far.dialog
--rw-r--r--   0 runner    (1001) docker     (123)       41 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/dialog/error_no_duration.dialog
--rw-r--r--   0 runner    (1001) docker     (123)       31 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/dialog/error_no_scheduled_kind_to_cancel.dialog
--rw-r--r--   0 runner    (1001) docker     (123)       64 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/dialog/error_no_time.dialog
--rw-r--r--   0 runner    (1001) docker     (123)       44 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/dialog/error_nothing_to_cancel.dialog
--rw-r--r--   0 runner    (1001) docker     (123)       20 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/dialog/expired_alert.dialog
--rw-r--r--   0 runner    (1001) docker     (123)       27 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/dialog/expired_audio_alert_intro.dialog
--rw-r--r--   0 runner    (1001) docker     (123)       32 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/dialog/expired_reminder.dialog
--rw-r--r--   0 runner    (1001) docker     (123)       23 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/dialog/list_alert.dialog
--rw-r--r--   0 runner    (1001) docker     (123)       33 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/dialog/list_alert_intro.dialog
--rw-r--r--   0 runner    (1001) docker     (123)       23 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/dialog/list_alert_missed_intro.dialog
--rw-r--r--   0 runner    (1001) docker     (123)       30 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/dialog/list_alert_none_missed.dialog
--rw-r--r--   0 runner    (1001) docker     (123)       31 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/dialog/list_alert_none_upcoming.dialog
--rw-r--r--   0 runner    (1001) docker     (123)       40 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/dialog/list_alert_repeating.dialog
--rw-r--r--   0 runner    (1001) docker     (123)       55 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/dialog/next_alert_named.dialog
--rw-r--r--   0 runner    (1001) docker     (123)       45 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/dialog/next_alert_unnamed.dialog
--rw-r--r--   0 runner    (1001) docker     (123)       22 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/dialog/quiet_hours_end.dialog
--rw-r--r--   0 runner    (1001) docker     (123)       85 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/dialog/quiet_hours_start.dialog
--rw-r--r--   0 runner    (1001) docker     (123)       41 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/dialog/timer_status.dialog
--rw-r--r--   0 runner    (1001) docker     (123)       27 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/dialog/timer_status_none_active.dialog
--rw-r--r--   0 runner    (1001) docker     (123)        5 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/dialog/word_alarm.dialog
--rw-r--r--   0 runner    (1001) docker     (123)        5 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/dialog/word_alert.dialog
--rw-r--r--   0 runner    (1001) docker     (123)        3 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/dialog/word_day.dialog
--rw-r--r--   0 runner    (1001) docker     (123)        8 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/dialog/word_reminder.dialog
--rw-r--r--   0 runner    (1001) docker     (123)        5 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/dialog/word_timer.dialog
--rw-r--r--   0 runner    (1001) docker     (123)       21 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/dialog/word_weekday.dialog
--rw-r--r--   0 runner    (1001) docker     (123)        6 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/dialog/word_weekday_friday.dialog
--rw-r--r--   0 runner    (1001) docker     (123)        6 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/dialog/word_weekday_monday.dialog
--rw-r--r--   0 runner    (1001) docker     (123)        8 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/dialog/word_weekday_saturday.dialog
--rw-r--r--   0 runner    (1001) docker     (123)        6 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/dialog/word_weekday_sunday.dialog
--rw-r--r--   0 runner    (1001) docker     (123)        8 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/dialog/word_weekday_thursday.dialog
--rw-r--r--   0 runner    (1001) docker     (123)        7 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/dialog/word_weekday_tuesday.dialog
--rw-r--r--   0 runner    (1001) docker     (123)        9 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/dialog/word_weekday_wednesday.dialog
--rw-r--r--   0 runner    (1001) docker     (123)       19 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/dialog/word_weekend.dialog
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 17:10:04.141191 neon-skill-alerts-1.5.2a4/locale/en-us/intent/
--rw-r--r--   0 runner    (1001) docker     (123)      163 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/intent/list_alerts.intent
--rw-r--r--   0 runner    (1001) docker     (123)      133 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/intent/quiet_hours_end.intent
--rw-r--r--   0 runner    (1001) docker     (123)      199 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/intent/quiet_hours_start.intent
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 17:10:04.145191 neon-skill-alerts-1.5.2a4/locale/en-us/vocab/
--rw-r--r--   0 runner    (1001) docker     (123)       23 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/vocab/alarm.voc
--rw-r--r--   0 runner    (1001) docker     (123)       12 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/vocab/alert.voc
--rw-r--r--   0 runner    (1001) docker     (123)       20 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/vocab/all.voc
--rw-r--r--   0 runner    (1001) docker     (123)       32 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/vocab/articles.voc
--rw-r--r--   0 runner    (1001) docker     (123)       39 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/vocab/cancel.voc
--rw-r--r--   0 runner    (1001) docker     (123)       68 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/vocab/dismiss.voc
--rw-r--r--   0 runner    (1001) docker     (123)       37 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/vocab/event.voc
--rw-r--r--   0 runner    (1001) docker     (123)       88 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/vocab/everyday.voc
--rw-r--r--   0 runner    (1001) docker     (123)        4 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/vocab/next.voc
--rw-r--r--   0 runner    (1001) docker     (123)       73 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/vocab/playable.voc
--rw-r--r--   0 runner    (1001) docker     (123)       24 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/vocab/priority.voc
--rw-r--r--   0 runner    (1001) docker     (123)       32 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/vocab/query.voc
--rw-r--r--   0 runner    (1001) docker     (123)       20 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/vocab/remind_me.voc
--rw-r--r--   0 runner    (1001) docker     (123)       18 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/vocab/reminder.voc
--rw-r--r--   0 runner    (1001) docker     (123)       15 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/vocab/repeat.voc
--rw-r--r--   0 runner    (1001) docker     (123)       22 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/vocab/script.voc
--rw-r--r--   0 runner    (1001) docker     (123)       32 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/vocab/set.voc
--rw-r--r--   0 runner    (1001) docker     (123)       16 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/vocab/snooze.voc
--rw-r--r--   0 runner    (1001) docker     (123)       17 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/vocab/timer.voc
--rw-r--r--   0 runner    (1001) docker     (123)       43 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/vocab/timer_time_remaining.voc
--rw-r--r--   0 runner    (1001) docker     (123)       23 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/vocab/until.voc
--rw-r--r--   0 runner    (1001) docker     (123)       35 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/vocab/weekdays.voc
--rw-r--r--   0 runner    (1001) docker     (123)       35 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/locale/en-us/vocab/weekends.voc
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 17:10:04.145191 neon-skill-alerts-1.5.2a4/neon_skill_alerts.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     2532 2023-06-26 17:10:04.000000 neon-skill-alerts-1.5.2a4/neon_skill_alerts.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     4231 2023-06-26 17:10:04.000000 neon-skill-alerts-1.5.2a4/neon_skill_alerts.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-26 17:10:04.000000 neon-skill-alerts-1.5.2a4/neon_skill_alerts.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       72 2023-06-26 17:10:04.000000 neon-skill-alerts-1.5.2a4/neon_skill_alerts.egg-info/entry_points.txt
--rw-r--r--   0 runner    (1001) docker     (123)       93 2023-06-26 17:10:04.000000 neon-skill-alerts-1.5.2a4/neon_skill_alerts.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       13 2023-06-26 17:10:04.000000 neon-skill-alerts-1.5.2a4/neon_skill_alerts.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-26 17:10:04.149191 neon-skill-alerts-1.5.2a4/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     4454 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/setup.py
--rw-r--r--   0 runner    (1001) docker     (123)     2561 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/skill.json
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 17:10:04.145191 neon-skill-alerts-1.5.2a4/test/
--rw-r--r--   0 runner    (1001) docker     (123)   114134 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/test/test_skill.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 17:10:04.145191 neon-skill-alerts-1.5.2a4/ui/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 17:10:04.145191 neon-skill-alerts-1.5.2a4/ui/+mediacenter/
--rw-r--r--   0 runner    (1001) docker     (123)     3546 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/ui/+mediacenter/RoundProgress.qml
--rw-r--r--   0 runner    (1001) docker     (123)     2234 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/ui/+mediacenter/Timer.qml
--rw-r--r--   0 runner    (1001) docker     (123)     3896 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/ui/+mediacenter/TimerCard.qml
--rw-r--r--   0 runner    (1001) docker     (123)     1153 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/ui/AlarmBoxControl.qml
--rw-r--r--   0 runner    (1001) docker     (123)     3437 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/ui/AlarmBoxView.qml
--rw-r--r--   0 runner    (1001) docker     (123)     4930 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/ui/AlarmButtonView.qml
--rw-r--r--   0 runner    (1001) docker     (123)     4468 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/ui/AlarmCard.qml
--rw-r--r--   0 runner    (1001) docker     (123)     3073 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/ui/AlarmsOverviewCard.qml
--rw-r--r--   0 runner    (1001) docker     (123)     2427 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/ui/AlarmsOverviewDelegate.qml
--rw-r--r--   0 runner    (1001) docker     (123)     3546 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/ui/RoundProgress.qml
--rw-r--r--   0 runner    (1001) docker     (123)     2557 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/ui/Timer.qml
--rw-r--r--   0 runner    (1001) docker     (123)     3469 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/ui/TimerCard.qml
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 17:10:04.145191 neon-skill-alerts-1.5.2a4/ui/icons/
--rw-r--r--   0 runner    (1001) docker     (123)      550 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/ui/icons/close.svg
--rw-r--r--   0 runner    (1001) docker     (123)      275 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/ui/icons/continue.svg
--rw-r--r--   0 runner    (1001) docker     (123)      352 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/ui/icons/pause.svg
--rw-r--r--   0 runner    (1001) docker     (123)      272 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/ui/qmldir
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 17:10:04.145191 neon-skill-alerts-1.5.2a4/ui/sounds/
--rw-r--r--   0 runner    (1001) docker     (123)    15240 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/ui/sounds/clicked.wav
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 17:10:04.149191 neon-skill-alerts-1.5.2a4/ui/translations/
--rw-r--r--   0 runner    (1001) docker     (123)       90 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/ui/translations/TimerCard_de.ts
--rw-r--r--   0 runner    (1001) docker     (123)       90 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/ui/translations/TimerCard_es.ts
--rw-r--r--   0 runner    (1001) docker     (123)       90 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/ui/translations/TimerCard_fr.ts
--rw-r--r--   0 runner    (1001) docker     (123)       90 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/ui/translations/TimerCard_it.ts
--rw-r--r--   0 runner    (1001) docker     (123)       90 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/ui/translations/TimerCard_nl.ts
--rw-r--r--   0 runner    (1001) docker     (123)       90 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/ui/translations/TimerCard_pt.ts
--rw-r--r--   0 runner    (1001) docker     (123)       33 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/ui/translations/skill-ovos-timer.openvoiceos_de.qm
--rw-r--r--   0 runner    (1001) docker     (123)       33 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/ui/translations/skill-ovos-timer.openvoiceos_es.qm
--rw-r--r--   0 runner    (1001) docker     (123)       33 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/ui/translations/skill-ovos-timer.openvoiceos_fr.qm
--rw-r--r--   0 runner    (1001) docker     (123)       33 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/ui/translations/skill-ovos-timer.openvoiceos_it.qm
--rw-r--r--   0 runner    (1001) docker     (123)       33 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/ui/translations/skill-ovos-timer.openvoiceos_nl.qm
--rw-r--r--   0 runner    (1001) docker     (123)       33 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/ui/translations/skill-ovos-timer.openvoiceos_pt.qm
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 17:10:04.149191 neon-skill-alerts-1.5.2a4/util/
--rw-r--r--   0 runner    (1001) docker     (123)     2573 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/util/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    10166 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/util/alert.py
--rw-r--r--   0 runner    (1001) docker     (123)    16625 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/util/alert_manager.py
--rw-r--r--   0 runner    (1001) docker     (123)    22330 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/util/parse_utils.py
--rw-r--r--   0 runner    (1001) docker     (123)     4503 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/util/ui_models.py
--rw-r--r--   0 runner    (1001) docker     (123)     1856 2023-06-26 17:09:59.000000 neon-skill-alerts-1.5.2a4/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 00:04:00.800868 neon-skill-alerts-1.5.2a5/
+-rw-r--r--   0 runner    (1001) docker     (123)     1635 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/LICENSE.md
+-rw-r--r--   0 runner    (1001) docker     (123)     2532 2023-06-28 00:04:00.800868 neon-skill-alerts-1.5.2a5/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     2274 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)    63722 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 00:04:00.784867 neon-skill-alerts-1.5.2a5/locale/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 00:04:00.784867 neon-skill-alerts-1.5.2a5/locale/en-us/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 00:04:00.792868 neon-skill-alerts-1.5.2a5/locale/en-us/dialog/
+-rw-r--r--   0 runner    (1001) docker     (123)       68 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/dialog/confirm_alert_playback.dialog
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/dialog/confirm_alert_recurring.dialog
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/dialog/confirm_alert_recurring_playback.dialog
+-rw-r--r--   0 runner    (1001) docker     (123)       61 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/dialog/confirm_alert_recurring_script.dialog
+-rw-r--r--   0 runner    (1001) docker     (123)       67 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/dialog/confirm_alert_script.dialog
+-rw-r--r--   0 runner    (1001) docker     (123)       51 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/dialog/confirm_alert_set.dialog
+-rw-r--r--   0 runner    (1001) docker     (123)       29 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/dialog/confirm_cancel_alert.dialog
+-rw-r--r--   0 runner    (1001) docker     (123)       30 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/dialog/confirm_cancel_all.dialog
+-rw-r--r--   0 runner    (1001) docker     (123)       19 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/dialog/confirm_dismiss_alert.dialog
+-rw-r--r--   0 runner    (1001) docker     (123)       35 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/dialog/confirm_snooze_alert.dialog
+-rw-r--r--   0 runner    (1001) docker     (123)       37 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/dialog/confirm_timer_started.dialog
+-rw-r--r--   0 runner    (1001) docker     (123)       97 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/dialog/error_audio_reminder_too_far.dialog
+-rw-r--r--   0 runner    (1001) docker     (123)       41 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/dialog/error_no_duration.dialog
+-rw-r--r--   0 runner    (1001) docker     (123)       31 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/dialog/error_no_scheduled_kind_to_cancel.dialog
+-rw-r--r--   0 runner    (1001) docker     (123)       64 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/dialog/error_no_time.dialog
+-rw-r--r--   0 runner    (1001) docker     (123)       44 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/dialog/error_nothing_to_cancel.dialog
+-rw-r--r--   0 runner    (1001) docker     (123)       20 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/dialog/expired_alert.dialog
+-rw-r--r--   0 runner    (1001) docker     (123)       27 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/dialog/expired_audio_alert_intro.dialog
+-rw-r--r--   0 runner    (1001) docker     (123)       32 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/dialog/expired_reminder.dialog
+-rw-r--r--   0 runner    (1001) docker     (123)       23 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/dialog/list_alert.dialog
+-rw-r--r--   0 runner    (1001) docker     (123)       33 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/dialog/list_alert_intro.dialog
+-rw-r--r--   0 runner    (1001) docker     (123)       23 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/dialog/list_alert_missed_intro.dialog
+-rw-r--r--   0 runner    (1001) docker     (123)       30 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/dialog/list_alert_none_missed.dialog
+-rw-r--r--   0 runner    (1001) docker     (123)       31 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/dialog/list_alert_none_upcoming.dialog
+-rw-r--r--   0 runner    (1001) docker     (123)       40 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/dialog/list_alert_repeating.dialog
+-rw-r--r--   0 runner    (1001) docker     (123)       55 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/dialog/next_alert_named.dialog
+-rw-r--r--   0 runner    (1001) docker     (123)       45 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/dialog/next_alert_unnamed.dialog
+-rw-r--r--   0 runner    (1001) docker     (123)       22 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/dialog/quiet_hours_end.dialog
+-rw-r--r--   0 runner    (1001) docker     (123)       85 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/dialog/quiet_hours_start.dialog
+-rw-r--r--   0 runner    (1001) docker     (123)       41 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/dialog/timer_status.dialog
+-rw-r--r--   0 runner    (1001) docker     (123)       27 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/dialog/timer_status_none_active.dialog
+-rw-r--r--   0 runner    (1001) docker     (123)        5 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/dialog/word_alarm.dialog
+-rw-r--r--   0 runner    (1001) docker     (123)        5 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/dialog/word_alert.dialog
+-rw-r--r--   0 runner    (1001) docker     (123)        3 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/dialog/word_day.dialog
+-rw-r--r--   0 runner    (1001) docker     (123)        8 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/dialog/word_reminder.dialog
+-rw-r--r--   0 runner    (1001) docker     (123)        5 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/dialog/word_timer.dialog
+-rw-r--r--   0 runner    (1001) docker     (123)       21 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/dialog/word_weekday.dialog
+-rw-r--r--   0 runner    (1001) docker     (123)        6 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/dialog/word_weekday_friday.dialog
+-rw-r--r--   0 runner    (1001) docker     (123)        6 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/dialog/word_weekday_monday.dialog
+-rw-r--r--   0 runner    (1001) docker     (123)        8 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/dialog/word_weekday_saturday.dialog
+-rw-r--r--   0 runner    (1001) docker     (123)        6 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/dialog/word_weekday_sunday.dialog
+-rw-r--r--   0 runner    (1001) docker     (123)        8 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/dialog/word_weekday_thursday.dialog
+-rw-r--r--   0 runner    (1001) docker     (123)        7 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/dialog/word_weekday_tuesday.dialog
+-rw-r--r--   0 runner    (1001) docker     (123)        9 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/dialog/word_weekday_wednesday.dialog
+-rw-r--r--   0 runner    (1001) docker     (123)       19 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/dialog/word_weekend.dialog
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 00:04:00.792868 neon-skill-alerts-1.5.2a5/locale/en-us/intent/
+-rw-r--r--   0 runner    (1001) docker     (123)      163 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/intent/list_alerts.intent
+-rw-r--r--   0 runner    (1001) docker     (123)      133 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/intent/quiet_hours_end.intent
+-rw-r--r--   0 runner    (1001) docker     (123)      199 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/intent/quiet_hours_start.intent
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 00:04:00.792868 neon-skill-alerts-1.5.2a5/locale/en-us/vocab/
+-rw-r--r--   0 runner    (1001) docker     (123)       23 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/vocab/alarm.voc
+-rw-r--r--   0 runner    (1001) docker     (123)       12 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/vocab/alert.voc
+-rw-r--r--   0 runner    (1001) docker     (123)       20 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/vocab/all.voc
+-rw-r--r--   0 runner    (1001) docker     (123)       32 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/vocab/articles.voc
+-rw-r--r--   0 runner    (1001) docker     (123)       39 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/vocab/cancel.voc
+-rw-r--r--   0 runner    (1001) docker     (123)       68 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/vocab/dismiss.voc
+-rw-r--r--   0 runner    (1001) docker     (123)       37 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/vocab/event.voc
+-rw-r--r--   0 runner    (1001) docker     (123)       88 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/vocab/everyday.voc
+-rw-r--r--   0 runner    (1001) docker     (123)        4 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/vocab/next.voc
+-rw-r--r--   0 runner    (1001) docker     (123)       73 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/vocab/playable.voc
+-rw-r--r--   0 runner    (1001) docker     (123)       24 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/vocab/priority.voc
+-rw-r--r--   0 runner    (1001) docker     (123)       32 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/vocab/query.voc
+-rw-r--r--   0 runner    (1001) docker     (123)       20 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/vocab/remind_me.voc
+-rw-r--r--   0 runner    (1001) docker     (123)       18 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/vocab/reminder.voc
+-rw-r--r--   0 runner    (1001) docker     (123)       15 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/vocab/repeat.voc
+-rw-r--r--   0 runner    (1001) docker     (123)       22 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/vocab/script.voc
+-rw-r--r--   0 runner    (1001) docker     (123)       32 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/vocab/set.voc
+-rw-r--r--   0 runner    (1001) docker     (123)       16 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/vocab/snooze.voc
+-rw-r--r--   0 runner    (1001) docker     (123)       17 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/vocab/timer.voc
+-rw-r--r--   0 runner    (1001) docker     (123)       43 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/vocab/timer_time_remaining.voc
+-rw-r--r--   0 runner    (1001) docker     (123)       23 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/vocab/until.voc
+-rw-r--r--   0 runner    (1001) docker     (123)       35 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/vocab/weekdays.voc
+-rw-r--r--   0 runner    (1001) docker     (123)       35 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/locale/en-us/vocab/weekends.voc
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 00:04:00.792868 neon-skill-alerts-1.5.2a5/neon_skill_alerts.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     2532 2023-06-28 00:04:00.000000 neon-skill-alerts-1.5.2a5/neon_skill_alerts.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     4283 2023-06-28 00:04:00.000000 neon-skill-alerts-1.5.2a5/neon_skill_alerts.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 00:04:00.000000 neon-skill-alerts-1.5.2a5/neon_skill_alerts.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       72 2023-06-28 00:04:00.000000 neon-skill-alerts-1.5.2a5/neon_skill_alerts.egg-info/entry_points.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       93 2023-06-28 00:04:00.000000 neon-skill-alerts-1.5.2a5/neon_skill_alerts.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       13 2023-06-28 00:04:00.000000 neon-skill-alerts-1.5.2a5/neon_skill_alerts.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 00:04:00.784867 neon-skill-alerts-1.5.2a5/res/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 00:04:00.796867 neon-skill-alerts-1.5.2a5/res/snd/
+-rw-r--r--   0 runner    (1001) docker     (123)   496586 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/res/snd/default-alarm.wav
+-rw-r--r--   0 runner    (1001) docker     (123)   143564 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/res/snd/default-timer.wav
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 00:04:00.800868 neon-skill-alerts-1.5.2a5/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     4461 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/setup.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2561 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/skill.json
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 00:04:00.796867 neon-skill-alerts-1.5.2a5/test/
+-rw-r--r--   0 runner    (1001) docker     (123)   114134 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/test/test_skill.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 00:04:00.796867 neon-skill-alerts-1.5.2a5/ui/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 00:04:00.796867 neon-skill-alerts-1.5.2a5/ui/+mediacenter/
+-rw-r--r--   0 runner    (1001) docker     (123)     3546 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/ui/+mediacenter/RoundProgress.qml
+-rw-r--r--   0 runner    (1001) docker     (123)     2234 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/ui/+mediacenter/Timer.qml
+-rw-r--r--   0 runner    (1001) docker     (123)     3896 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/ui/+mediacenter/TimerCard.qml
+-rw-r--r--   0 runner    (1001) docker     (123)     1153 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/ui/AlarmBoxControl.qml
+-rw-r--r--   0 runner    (1001) docker     (123)     3437 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/ui/AlarmBoxView.qml
+-rw-r--r--   0 runner    (1001) docker     (123)     4930 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/ui/AlarmButtonView.qml
+-rw-r--r--   0 runner    (1001) docker     (123)     4468 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/ui/AlarmCard.qml
+-rw-r--r--   0 runner    (1001) docker     (123)     3073 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/ui/AlarmsOverviewCard.qml
+-rw-r--r--   0 runner    (1001) docker     (123)     2427 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/ui/AlarmsOverviewDelegate.qml
+-rw-r--r--   0 runner    (1001) docker     (123)     3546 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/ui/RoundProgress.qml
+-rw-r--r--   0 runner    (1001) docker     (123)     2557 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/ui/Timer.qml
+-rw-r--r--   0 runner    (1001) docker     (123)     3469 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/ui/TimerCard.qml
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 00:04:00.796867 neon-skill-alerts-1.5.2a5/ui/icons/
+-rw-r--r--   0 runner    (1001) docker     (123)      550 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/ui/icons/close.svg
+-rw-r--r--   0 runner    (1001) docker     (123)      275 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/ui/icons/continue.svg
+-rw-r--r--   0 runner    (1001) docker     (123)      352 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/ui/icons/pause.svg
+-rw-r--r--   0 runner    (1001) docker     (123)      272 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/ui/qmldir
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 00:04:00.796867 neon-skill-alerts-1.5.2a5/ui/sounds/
+-rw-r--r--   0 runner    (1001) docker     (123)    15240 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/ui/sounds/clicked.wav
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 00:04:00.796867 neon-skill-alerts-1.5.2a5/ui/translations/
+-rw-r--r--   0 runner    (1001) docker     (123)       90 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/ui/translations/TimerCard_de.ts
+-rw-r--r--   0 runner    (1001) docker     (123)       90 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/ui/translations/TimerCard_es.ts
+-rw-r--r--   0 runner    (1001) docker     (123)       90 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/ui/translations/TimerCard_fr.ts
+-rw-r--r--   0 runner    (1001) docker     (123)       90 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/ui/translations/TimerCard_it.ts
+-rw-r--r--   0 runner    (1001) docker     (123)       90 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/ui/translations/TimerCard_nl.ts
+-rw-r--r--   0 runner    (1001) docker     (123)       90 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/ui/translations/TimerCard_pt.ts
+-rw-r--r--   0 runner    (1001) docker     (123)       33 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/ui/translations/skill-ovos-timer.openvoiceos_de.qm
+-rw-r--r--   0 runner    (1001) docker     (123)       33 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/ui/translations/skill-ovos-timer.openvoiceos_es.qm
+-rw-r--r--   0 runner    (1001) docker     (123)       33 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/ui/translations/skill-ovos-timer.openvoiceos_fr.qm
+-rw-r--r--   0 runner    (1001) docker     (123)       33 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/ui/translations/skill-ovos-timer.openvoiceos_it.qm
+-rw-r--r--   0 runner    (1001) docker     (123)       33 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/ui/translations/skill-ovos-timer.openvoiceos_nl.qm
+-rw-r--r--   0 runner    (1001) docker     (123)       33 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/ui/translations/skill-ovos-timer.openvoiceos_pt.qm
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 00:04:00.800868 neon-skill-alerts-1.5.2a5/util/
+-rw-r--r--   0 runner    (1001) docker     (123)     2573 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/util/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10166 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/util/alert.py
+-rw-r--r--   0 runner    (1001) docker     (123)    16625 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/util/alert_manager.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22330 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/util/parse_utils.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4503 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/util/ui_models.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1856 2023-06-28 00:03:56.000000 neon-skill-alerts-1.5.2a5/version.py
```

### Comparing `neon-skill-alerts-1.5.2a4/LICENSE.md` & `neon-skill-alerts-1.5.2a5/LICENSE.md`

 * *Files identical despite different names*

### Comparing `neon-skill-alerts-1.5.2a4/PKG-INFO` & `neon-skill-alerts-1.5.2a5/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: neon-skill-alerts
-Version: 1.5.2a4
+Version: 1.5.2a5
 Home-page: https://github.com/NeonGeckoCom/skill-alerts
 Author: Neongecko
 Author-email: developers@neon.ai
 License: BSD-3-Clause
 Description-Content-Type: text/markdown
 License-File: LICENSE.md
```

### Comparing `neon-skill-alerts-1.5.2a4/README.md` & `neon-skill-alerts-1.5.2a5/README.md`

 * *Files identical despite different names*

### Comparing `neon-skill-alerts-1.5.2a4/__init__.py` & `neon-skill-alerts-1.5.2a5/__init__.py`

 * *Files 0% similar despite different names*

```diff
@@ -31,19 +31,19 @@
 from datetime import datetime, timedelta, timezone
 from threading import RLock, Thread
 from typing import Tuple, List, Optional
 from dateutil.tz import gettz
 
 from ovos_utils import classproperty
 from ovos_utils import create_daemon
+from ovos_utils.file_utils import resolve_resource_file
 from ovos_utils.process_utils import RuntimeRequirements
 from ovos_utils.log import LOG
 from ovos_utils.sound import play_audio
 from adapt.intent import IntentBuilder
-
 from lingua_franca.format import nice_duration, nice_time, nice_date_time
 from lingua_franca.parse import extract_duration, extract_datetime
 from lingua_franca.time import default_timezone
 from ovos_bus_client.message import Message
 from neon_utils.message_utils import request_from_mobile, dig_for_message
 from neon_utils.skills.neon_skill import NeonSkill
 from neon_utils.user_utils import get_user_prefs, get_message_user
@@ -101,44 +101,57 @@
         return self.preference_skill().get('speak_timer', True)
 
     @property
     def alarm_sound_file(self) -> str:
         """
         Return the path to a valid alarm sound resource file
         """
-        filename = self.preference_skill().get('sound_alarm') or 'default-alarm.wav'
+        filename = self.preference_skill().get('sound_alarm') or \
+            'default-alarm.wav'
         if os.path.isfile(filename):
             return filename
-        file = self.find_resource(filename)
+        file = resolve_resource_file(filename,
+                                     os.path.join(self.root_dir, "res"),
+                                     self.config_core)
         if not file:
             LOG.warning(f'Could not resolve requested file: {filename}')
-            file = os.path.join(os.path.dirname(__file__), 'res', 'snd',
+            file = os.path.join(self.root_dir, 'res', 'snd',
                                 'default-alarm.wav')
         if not file:
             raise FileNotFoundError(f"Could not resolve sound: {filename}")
         return file
 
     @property
     def timer_sound_file(self) -> str:
         """
         Return the path to a valid timer sound resource file
         """
-        filename = self.preference_skill().get('sound_timer') or 'default-timer.wav'
+        filename = self.preference_skill().get('sound_timer') or \
+            'default-timer.wav'
         if os.path.isfile(filename):
             return filename
-        file = self.find_resource(filename)
+        file = resolve_resource_file(filename,
+                                     os.path.join(self.root_dir, "res"),
+                                     self.config_core)
         if not file:
             LOG.warning(f'Could not resolve requested file: {filename}')
-            file = os.path.join(os.path.dirname(__file__), 'res', 'snd',
+            file = os.path.join(self.root_dir, 'res', 'snd',
                                 'default-timer.wav')
         if not file:
             raise FileNotFoundError(f"Could not resolve sound: {filename}")
         return file
 
     @property
+    def escalate_volume(self) -> bool:
+        """
+        If true, increase volume while alert expiration is playing
+        """
+        return self.preference_skill().get("escalate_volume", False)
+
+    @property
     def quiet_hours(self) -> bool:
         """
         Return true if the user has requested not to be disturbed
         """
         return self.preference_skill().get('quiet_hours', False)
 
     @property
@@ -1017,25 +1030,37 @@
 
         if not to_play:
             self._speak_notify_expired(alert)
             return
 
         timeout = time.time() + self.alert_timeout_seconds
         alert_id = get_alert_id(alert)
+        volume_message = Message("mycroft.volume.get")
+        resp = self.bus.wait_for_response(volume_message)
+        if resp:
+            volume = resp.data.get('percent')
+        else:
+            volume = None
         while self.alert_manager.get_alert_status(alert_id) == \
                 AlertState.ACTIVE and time.time() < timeout:
             if alert_message.context.get("klat_data"):
                 self.send_with_audio(self.dialog_renderer.render(
                     "expired_alert", {'name': alert.alert_name}),
                     to_play, alert_message, private=True)
             else:
                 # TODO: refactor to `self.play_audio`
+                LOG.debug(f"Playing file: {to_play}")
                 play_audio(to_play).wait(60)
             time.sleep(1)
-            # TODO: If ramp volume setting, do that
+            if self.escalate_volume:
+                self.bus.emit(Message("mycroft.volume.increase"))
+
+        if volume:
+            # Reset initial volume
+            self.bus.emit(Message("mycroft.volume.set", {"percent": volume}))
         if self.alert_manager.get_alert_status(alert_id) == AlertState.ACTIVE:
             self._missed_alert(alert_id)
 
     def _speak_notify_expired(self, alert: Alert):
         LOG.debug(f"notify alert expired: {get_alert_id(alert)}")
         alert_message = Message("neon.alert", alert.data, alert.context)
```

### Comparing `neon-skill-alerts-1.5.2a4/neon_skill_alerts.egg-info/PKG-INFO` & `neon-skill-alerts-1.5.2a5/neon_skill_alerts.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: neon-skill-alerts
-Version: 1.5.2a4
+Version: 1.5.2a5
 Home-page: https://github.com/NeonGeckoCom/skill-alerts
 Author: Neongecko
 Author-email: developers@neon.ai
 License: BSD-3-Clause
 Description-Content-Type: text/markdown
 License-File: LICENSE.md
```

### Comparing `neon-skill-alerts-1.5.2a4/neon_skill_alerts.egg-info/SOURCES.txt` & `neon-skill-alerts-1.5.2a5/neon_skill_alerts.egg-info/SOURCES.txt`

 * *Files 8% similar despite different names*

```diff
@@ -77,14 +77,16 @@
 locale/en-us/vocab/weekends.voc
 neon_skill_alerts.egg-info/PKG-INFO
 neon_skill_alerts.egg-info/SOURCES.txt
 neon_skill_alerts.egg-info/dependency_links.txt
 neon_skill_alerts.egg-info/entry_points.txt
 neon_skill_alerts.egg-info/requires.txt
 neon_skill_alerts.egg-info/top_level.txt
+res/snd/default-alarm.wav
+res/snd/default-timer.wav
 test/test_skill.py
 ui/AlarmBoxControl.qml
 ui/AlarmBoxView.qml
 ui/AlarmButtonView.qml
 ui/AlarmCard.qml
 ui/AlarmsOverviewCard.qml
 ui/AlarmsOverviewDelegate.qml
```

### Comparing `neon-skill-alerts-1.5.2a4/setup.py` & `neon-skill-alerts-1.5.2a5/setup.py`

 * *Files 0% similar despite different names*

```diff
@@ -54,15 +54,15 @@
                 requirements[i] = \
                     r.replace("github.com",
                               f"{getenv('GITHUB_TOKEN')}@github.com")
     return requirements
 
 
 def find_resource_files():
-    resource_base_dirs = ("locale", "ui", "vocab", "dialog", "regex")
+    resource_base_dirs = ("locale", "ui", "vocab", "dialog", "regex", "res")
     base_dir = BASE_PATH
     package_data = ["skill.json"]
     for res in resource_base_dirs:
         if path.isdir(path.join(base_dir, res)):
             for (directory, _, files) in walk(path.join(base_dir, res)):
                 if files:
                     package_data.append(
```

### Comparing `neon-skill-alerts-1.5.2a4/skill.json` & `neon-skill-alerts-1.5.2a5/skill.json`

 * *Files identical despite different names*

### Comparing `neon-skill-alerts-1.5.2a4/test/test_skill.py` & `neon-skill-alerts-1.5.2a5/test/test_skill.py`

 * *Files identical despite different names*

### Comparing `neon-skill-alerts-1.5.2a4/ui/+mediacenter/RoundProgress.qml` & `neon-skill-alerts-1.5.2a5/ui/+mediacenter/RoundProgress.qml`

 * *Files identical despite different names*

### Comparing `neon-skill-alerts-1.5.2a4/ui/+mediacenter/Timer.qml` & `neon-skill-alerts-1.5.2a5/ui/+mediacenter/Timer.qml`

 * *Files identical despite different names*

### Comparing `neon-skill-alerts-1.5.2a4/ui/+mediacenter/TimerCard.qml` & `neon-skill-alerts-1.5.2a5/ui/+mediacenter/TimerCard.qml`

 * *Files identical despite different names*

### Comparing `neon-skill-alerts-1.5.2a4/ui/AlarmBoxControl.qml` & `neon-skill-alerts-1.5.2a5/ui/AlarmBoxControl.qml`

 * *Files identical despite different names*

### Comparing `neon-skill-alerts-1.5.2a4/ui/AlarmBoxView.qml` & `neon-skill-alerts-1.5.2a5/ui/AlarmBoxView.qml`

 * *Files identical despite different names*

### Comparing `neon-skill-alerts-1.5.2a4/ui/AlarmButtonView.qml` & `neon-skill-alerts-1.5.2a5/ui/AlarmButtonView.qml`

 * *Files identical despite different names*

### Comparing `neon-skill-alerts-1.5.2a4/ui/AlarmCard.qml` & `neon-skill-alerts-1.5.2a5/ui/AlarmCard.qml`

 * *Files identical despite different names*

### Comparing `neon-skill-alerts-1.5.2a4/ui/AlarmsOverviewCard.qml` & `neon-skill-alerts-1.5.2a5/ui/AlarmsOverviewCard.qml`

 * *Files identical despite different names*

### Comparing `neon-skill-alerts-1.5.2a4/ui/AlarmsOverviewDelegate.qml` & `neon-skill-alerts-1.5.2a5/ui/AlarmsOverviewDelegate.qml`

 * *Files identical despite different names*

### Comparing `neon-skill-alerts-1.5.2a4/ui/RoundProgress.qml` & `neon-skill-alerts-1.5.2a5/ui/RoundProgress.qml`

 * *Files identical despite different names*

### Comparing `neon-skill-alerts-1.5.2a4/ui/Timer.qml` & `neon-skill-alerts-1.5.2a5/ui/Timer.qml`

 * *Files identical despite different names*

### Comparing `neon-skill-alerts-1.5.2a4/ui/TimerCard.qml` & `neon-skill-alerts-1.5.2a5/ui/TimerCard.qml`

 * *Files identical despite different names*

### Comparing `neon-skill-alerts-1.5.2a4/ui/icons/close.svg` & `neon-skill-alerts-1.5.2a5/ui/icons/close.svg`

 * *Files identical despite different names*

### Comparing `neon-skill-alerts-1.5.2a4/ui/sounds/clicked.wav` & `neon-skill-alerts-1.5.2a5/ui/sounds/clicked.wav`

 * *Files identical despite different names*

### Comparing `neon-skill-alerts-1.5.2a4/util/__init__.py` & `neon-skill-alerts-1.5.2a5/util/__init__.py`

 * *Files identical despite different names*

### Comparing `neon-skill-alerts-1.5.2a4/util/alert.py` & `neon-skill-alerts-1.5.2a5/util/alert.py`

 * *Files identical despite different names*

### Comparing `neon-skill-alerts-1.5.2a4/util/alert_manager.py` & `neon-skill-alerts-1.5.2a5/util/alert_manager.py`

 * *Files identical despite different names*

### Comparing `neon-skill-alerts-1.5.2a4/util/parse_utils.py` & `neon-skill-alerts-1.5.2a5/util/parse_utils.py`

 * *Files identical despite different names*

### Comparing `neon-skill-alerts-1.5.2a4/util/ui_models.py` & `neon-skill-alerts-1.5.2a5/util/ui_models.py`

 * *Files identical despite different names*

### Comparing `neon-skill-alerts-1.5.2a4/version.py` & `neon-skill-alerts-1.5.2a5/version.py`

 * *Files 1% similar despite different names*

```diff
@@ -22,8 +22,8 @@
 # EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO,
 # PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA,
 # OR PROFITS;  OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF
 # LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING
 # NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS
 # SOFTWARE,  EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
 
-__version__ = "1.5.2a4"
+__version__ = "1.5.2a5"
```

