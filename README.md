# ACC Tools

ACC Tools is a suite of tools to compliment Assetto Corsa Competizione the official GT racing simulator

## Release History

### v1.0.0-beta-8- 2023-02-24

- Added logging of database operation
- Database Log Viewer

#### Changed
- Completed side panel of Lap Analyser for lap selection

#### Fixed
- Threading issue with DbContext

### v1.0.0-beta-7- 2023-02-20

#### Added
- Telemetry logs to Log Viewer

#### Changed
- Optimised layout of Lap Times Viewer for 1080p screens

### v1.0.0-beta-6- 2023-02-19

#### Added
- Initial live telemerty view
- Live telemetry monitor

The monitor is disabled for now

### v1.0.0-beta-5- 2023-02-17

#### Fixed
- Trying to disconnect from unconnected telemetry connectioin disabled in last quick fix

### v1.0.0-beta-4- 2023-02-17

#### Changed
- Disable feature that is work in progress and should have been disabled in last release

### v1.0.0-beta-3- 2023-02-17

#### Changed
- Moved Enable Diagnostics Mode checkox to settings panel to avoid temptation to enable it without being asked by support

### v1.0.0-beta-2- 2023-02-15

#### Added
- Option to automatically start Lap Time Recorder on startup
- Export Fastest Laps to Excel or CSV

### v1.0.0-beta.1 - 2023-02-14

#### Added
- Delete session from lap recorder
- Delete own lap from lap recorder primary driver table

#### Fixed
- User settings not saving property due to dumb developer error
- Driver laps lists not updating on driver selection
- Stats not updating correctly at end of session

### v1.0.0-alpha.8- 2023-02-12

#### Fixed
- Issue where car id is different when online to offline

### v1.0.0-alpha.7- 2023-02-12

#### Changed
- Switched to tabs for dashboard analysis section

### v1.0.0-alpha.6 - 2023-02-12

#### Fixed
- Dashboard layout for 1080p screen resolution

### v1.0.0-alpha.5 - 2023-02-12

#### Added
- Dashboard
- Fastest Laps table on Dashboard
- Track Time Distribution chart on Dashboard
- Car Time Distribution chart on Dashboard

#### Fixed
- Issue where settings could end up empty
- Issue where changes to app settings were not picked up on deployment

### v1.0.0-alpha.4 - 2023-02-11

#### Added
- New Log Viewer under Help menu
- Log cleanup on exit

#### Changed
- Separate application and broadcast logging

#### Fixed
- Lap recording process to account for lack of some expected events

### v1.0.0-alpha.3 - 2023-01-31

#### Added
- New Lap Recorder tool with support for side by side comparison of drivers

### v1.0.0-alpha.2 - 2023-01-31
Small change to test revised automatic update

#### Added
- UI for automatic update with progress indicator

#### Changed
- Renamed Track Maps to Track Map Builder

#### Fixed
- Automatic update

### v1.0.0-alpha.1 - 2023-01-28
Initial release of the tools with the following completed features

#### Added
- Setup Manager
- Track Map
- Result File Tracker

Dashboard and Lap Analyser featues are still being worked on
