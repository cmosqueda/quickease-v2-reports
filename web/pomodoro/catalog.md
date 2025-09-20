This master catalog lists all test cases for `POMODORO TIMER -> PTxxx` module.

---

## In list format:

- **PT001: Customize time intervals**

  - Description: The user should be able to customize the durations for study sessions, long breaks, and short breaks, and save the changes.
  - Steps to perform:
    1. On the drawer navigation, click on the pomodoro button.
    2. Customize and set your desired study time duration or break time duration.
    3. Once set, click on the save button.

- **PT002: Enabling/disabling Pomodoro popup floating timer options**

  - Description: The user should be able to enable or disable the Pomodoro popup floating timer options.
  - Steps to perform:
    1. On the drawer navigation, click on the pomodoro button.
    2. Toggle **popup pomodoro timer options** option

- **PT003: Enabling/disabling Pomodoro persistent full timer display**

  - Description: The user should be able to enable or disable persistent full timer display options by toggling the study options always on top.
  - Steps to perform:
    1. Make sure the popup timer is enabled.
    2. Click on the start study session popup.
    3. Toggle the study options always on top

- **PT004: Timer operation**

  - Description: When pomodoro is used/started, the timer should properly and accurately operate. The counts should be consistent and intervals/delays must be stable.
  - Steps to perform:
    1. On the full timer display, click on pause/play timer.
    2. Select on any of the timer's mode (study, short break, long break)

---

## In tabular format:

| FEAT_CODE | Feature Name                                              | Description                                                                                                                                           |
| --------- | --------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------- |
| PT001     | Customize time intervals                                  | The user should be able to customize the durations for study sessions, long breaks, and short breaks, and save the changes.                           |
| PT002     | Enabling/disabling Pomodoro popup floating timer options  | The user should be able to enable or disable the Pomodoro popup floating timer options.                                                               |
| PT003     | Enabling/disabling Pomodoro persistent full timer display | The user should be able to enable or disable persistent full timer display options by toggling the study options always on top.                       |
| PT004     | Timer operation                                           | When pomodoro is used/started, the timer should properly and accurately operate. The counts should be consistent and intervals/delays must be stable. |
