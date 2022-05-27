# CRAPLOG
A tool to create statistics from Apache2 log files 

<br/>

## OFFICIAL VERSIONS

| Version | Repository | Description | Coded with |
| :-: | :-- | :-- | :-: |
| 5.0 | [full GUI](https://github.com/elB4RTO/craplog-fullGUI) | Fully graphical version, improved with more functionalities | ![Java](https://img.shields.io/badge/%20-Java-b07219) |
| 3.1 | [GUI aided CLI](https://github.com/elB4RTO/craplog-GUIaidedCLI) | Command line version with a graphical launcher | ![Python](https://img.shields.io/badge/%20-Python-3572A5) |
| 3.0 | [full CLI](https://github.com/elB4RTO/craplog-fullCLI) | Command line version | ![Bash](https://img.shields.io/badge/%20-Bash-89e051) ![Python](https://img.shields.io/badge/%20-Python-3572A5) |

*NOTE: All of the **official versions** are up-to-date, the version number is just indicative for the development progress*

*IMPORTANT NOTE: significant changes, which affect the way statistics are made and handled, has been made from version **3.\*** to version **5.\***:*
- *version **3** only uses "yesterday's" logs (\*.log.1 files), it will store statistics by date of execution and is therefore meant to be ran daily*
- *version **5** can instead use every log file (archived logs included), it will store statistics depending on the date in every single log line and can therefore be used at anytime (once a week, a month, etc), with any number of log files (all in once)*

<br/><br/>

### ARCHIVED VERSIONS
*older versions, published to keep track of the developement progress*

| Version | Repository | Description | Coded with |
| :-: | :-- | :-- | :-: |
| 4.0 | [py GUI](https://github.com/elB4RTO/craplog-pyGUI) | Fully graphical version, achieved with Tkinter | ![Python](https://img.shields.io/badge/%20-Python-3572A5) |
| 2.0 | [origin enhanced](https://github.com/elB4RTO/craplog-originEnhanced) | Original version, enhanced with C++ | ![Bash](https://img.shields.io/badge/%20-Bash-89e051) ![C++](https://img.shields.io/badge/%20-C++-f34b7d) |
| 1.0 | [origin](https://github.com/elB4RTO/craplog-origin) | Original version | ![Bash](https://img.shields.io/badge/%20-Bash-89e051) |

*NOTE: The **archived versions** may be un-complete, or un-updated. The code still works, but has not been enhanced from the day they was archived*
