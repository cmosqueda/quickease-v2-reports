This master catalog lists all test cases for `POMODORO TIMER -> PTxxx` module.

---

## In list format:

- **PT001: Customize time intervals**

  - Description: The user should be able to customize the durations for study sessions, long breaks, and short breaks, and save the changes.
  - Steps to perform:
    1. On the drawer navigation, click on the timer button. This should display the full timer bottomsheet options.
    2. Click on the settings icon.
    3. Customize and set your desired study time duration or break time duration.
    4. Once set, click on the save button.

- **PT002: Enabling/disabling Pomodoro drawer display**

  - Description: The user should be able to enable or disable the Pomodoro drawer display.
  - Steps to perform:
    1. On the drawer navigation, click on the settings button.
    2. Toggle **enable pomodoro timer in drawer** option

- **PT003: Full timer display**

  - Description: The user should be able to display full Pomodoro timer options by clicking the Pomodoro button option located at the bottom of the drawer.
  - Steps to perform:
    1. On the drawer navigation, click on the timer button. This should display the full timer bottomsheet options.

- **PT004: Timer operation**

  - Description: When pomodoro is used/started, the timer should properly and accurately operate. The counts should be consistent and intervals/delays must be stable.
  - Steps to perform:
    1. On the drawer navigation, pause/play the timer on its compact display (if pomodoro drawer display is enabled)
    2. On the full timer bottomsheet display, click on the start/stop buttons.

---

## In tabular format:

| FEAT_CODE | Feature Name                               | Description                                                                                                                                           |
| --------- | ------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------- |
| PT001     | Customize time intervals                   | The user should be able to customize the durations for study sessions, long breaks, and short breaks, and save the changes.                           |
| PT002     | Enabling/disabling Pomodoro drawer display | The user should be able to enable or disable the Pomodoro drawer display.                                                                             |
| PT003     | Full timer display                         | The user should be able to display full Pomodoro timer options by clicking the Pomodoro button option located at the bottom of the drawer.            |
| PT004     | Timer operation                            | When pomodoro is used/started, the timer should properly and accurately operate. The counts should be consistent and intervals/delays must be stable. |
