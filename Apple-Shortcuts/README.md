# Apple Shortcuts Collection

## Overview

Welcome to the Apple Shortcuts Collection! This repository contains a set of useful and time-saving Apple Shortcuts that you can easily integrate into your iOS devices.

## Table of Contents

- [Getting Started](#getting-started)
- [Automations](#automations)
- [Shortcuts](#shortcuts)
- [License](#license)

## Getting Started

### Prerequisites

Before you begin, make sure you have the following:

- An iOS device running iOS 13 or later.
- The Shortcuts app installed on your iOS device.
   
## Automations

> [!NOTE]  
> Automations cannot be shared via an iCloud link; users must manually create them on their devices. I will share screenshots of the listed automations for you to replicate.

Here is a list of available **Automations**:

1. **Create an Alarm for Flight Check-in** [:book:](https://github.com/hdonapati/missing-link/blob/main/Apple-Shortcuts/Automations/Flight-CheckIn-Alarm/Setup.md "Read More")
   - Description: Generates alarms for Flight Check-in (24 hours before) based on your Flight Schedules.
   - Usage: The automation runs daily, a minute after midnight, fetching Flight Schedules for the next day and creating alarms as needed.
   - Author: [hdonapati](https://github.com/hdonapati)

2. **Toggling Work Alarms based on Work Schedule** [:book:](https://github.com/hdonapati/missing-link/blob/main/Apple-Shortcuts/Automations/Work-Alarms/Setup.md "Read More")
   - Description: Toggles Work Alarms based on your Work Schedule - Vacation Day or Work Holiday.
   - Usage: The automation runs on set days at `22:00`(configurable), fetching Work Schedules for the next day and toggling alarms as needed.
   - Author: [hdonapati](https://github.com/hdonapati)
  
3. **Toggling Work Focus mode based on Work Schedule** [:book:](https://github.com/hdonapati/missing-link/blob/main/Apple-Shortcuts/Automations/Work-Focus-Mode/Setup.md "Read More")
   - Description: Toggles Work Focus Mode based on your Work Schedule - Vacation Day or Work Holiday.
   - Usage: The automation runs on set days at `09:01`(a minute after Work Time starts, configurable), fetching Work Schedules for the current day and turning off Work Focus mode if required.
   - Author: [hdonapati](https://github.com/hdonapati)
     
## Shortcuts

Here is a list of available **Shortcuts**:

1. **Get Flights** [:book:](https://github.com/hdonapati/missing-link/blob/main/Apple-Shortcuts/Shortcuts/GetFlights/Setup.md "Read More") <a href="https://www.icloud.com/shortcuts/5d7e5572e3264586af7ade590a38c3af" title="Apple Shortcut Link" alt="GetFlights-Shortcut-Link"><img src="https://raw.githubusercontent.com/hdonapati/missing-link/main/Apple-Shortcuts/ShortcutsIcon.png" style="width:20px;height:20px;" /></a>
   - Description: Will show/return the flights for a given date by looking up in the calendar.
   - Usage: Can be used within another shortcut/automation to return the data or standalone to display a notification.
   - Author: [hdonapati](https://github.com/hdonapati)
  
2. **Holiday or Vacation Check** [:book:](https://github.com/hdonapati/missing-link/blob/main/Apple-Shortcuts/Shortcuts/HolidayorVacationCheck/Setup.md "Read More") <a href="https://www.icloud.com/shortcuts/e9f9e20cb0bc4cb7b3a0c44d3173e9c8" title="Apple Shortcut Link" alt="GetFlights-Shortcut-Link"><img src="https://raw.githubusercontent.com/hdonapati/missing-link/main/Apple-Shortcuts/ShortcutsIcon.png" style="width:20px;height:20px;" /></a>
   - Description: For a given date, if it's Work vacation day or Holiday, will return the event name.
   - Usage: Can be utilized within another shortcut/automation to retrieve the event name – helpful for disabling work-related alarms or enabling Work Focus mode for the current or upcoming day.
   - Author: [hdonapati](https://github.com/hdonapati)


<!-- Add more shortcuts as needed -->


## License

This project is licensed under the [MIT License](LICENSE) - see the [LICENSE](LICENSE) file for details.

Happy Shortcuttin'! 🚀
