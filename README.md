# homeassistant-pending-notifications
Home Assistant scripts and automations to postpone mobile phone notifications and deliver them when the recipient returns home. Also create advanced (e.g. actionable) notifications within the visual editor.

## Features
- [ ] Create mobile app notifications in scripts and automations using the visual editor (without yaml):
  - [x] Basic notifications with `title`, `message` and `data`.
  - [x] [Actionable notifications](https://companion.home-assistant.io/docs/notifications/actionable-notifications):
    - [x] With two customizable actions and up to two automatic postponement options.
    - [x] Allow parallel notifications without [blocking behavior](https://companion.home-assistant.io/docs/notifications/actionable-notifications#blocking-behaviour).
    - [x] Time out script instances waiting for user interaction.
    - [x] Clear notifications after corresponding scipt instance timed out.
    - [x] Stop waiting script instances when notification is replaced.
    - [ ] [uri values](https://companion.home-assistant.io/docs/notifications/actionable-notifications#uri-values).
    - [ ] [iOS specific options](https://companion.home-assistant.io/docs/notifications/actionable-notifications#ios-specific-options).
  - [ ] [Attatchments](https://companion.home-assistant.io/docs/notifications/notification-attachments).
  - [x] [Clearing](https://companion.home-assistant.io/docs/notifications/notifications-basic#clearing).
    - [ ] [Android specific Notification Cleared](https://companion.home-assistant.io/docs/notifications/notification-cleared).
  - [ ] [Critical Notifications](https://companion.home-assistant.io/docs/notifications/critical-notifications).
  - [ ] [Notification Commands](https://companion.home-assistant.io/docs/notifications/notification-commands):
    - [x] request_location_update
    - [x] clear_notification
    - [ ] iOS specific Notification Commands.
    - [ ] Android specific Notification Commands.
  - [x] [Grouping](https://companion.home-assistant.io/docs/notifications/notifications-basic#grouping).
  - [x] [Opening a URL](https://companion.home-assistant.io/docs/notifications/notifications-basic#opening-a-url).
    - [ ] [Android specific uri values](https://companion.home-assistant.io/docs/notifications/actionable-notifications#blocking-behaviour).
  - [x] [Replacing](https://companion.home-assistant.io/docs/notifications/notifications-basic#replacing).
  - [ ] [Sounds](https://companion.home-assistant.io/docs/notifications/notification-sounds).
  - [x] [Subtitle/ Subject](https://companion.home-assistant.io/docs/notifications/notifications-basic#subtitle--subject).
- [x] Automatically add `Remind me at home` button to notifications delivered when recipient is not home (❗not fully tested).
- [x] Automatically add `Remind me later` and `Remind me tomorrow` button to notifications delivered when recipient is home (❗not fully tested).
- [x] Queue postponed notifications for later delivery.
- [x] Deliver queued notifications when recipient returns home.
- [x] Deliver notifications after user queued them for later delivery.


## Credits
This project was inspired by [Simon42](https://www.simon42.com/home-assistant-zu-hause-benachrichtigen/). The scripts and ideas are heavily based on [Pending / Postponed notifications](https://community.home-assistant.io/t/pending-postponed-notifications/363234) by [RoboMagus](https://gist.github.com/RoboMagus/).

Thank you to the Home Assistant Developers and Community! ❤️