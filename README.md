# omnifocus-plugin-reschedule-objects
Reschedule the selected tasks/projects to Morning, Noon, Afternoon, Evening, Daytime or Whole Day of the chosen date, or clear the existing schedules.

## Quick Start Guide

### Dependencies

This plugin depends on the [omnifocus-plugin-libdev](https://github.com/xbot/omnifocus-plugin-libdev) library.

### Installation

Clone the repo and link it in the Automation Configuration dialog in OmniFocus, or add it as a git submodule to the default plugin folder of OmniFocus. I recommend the latter for an easier synchronization with other devices.

```shell
cd ~/Library/Mobile Documents/iCloud~com~omnigroup~OmniFocus/Documents/Plug-Ins

git init

# Install the dependent library, ignore this if you have already installed it.
git submodule add https://github.com/xbot/omnifocus-plugin-libdev.git libdev

git submodule add https://github.com/xbot/omnifocus-plugin-reschedule-objects.git reschedule-objects

# For updating:
git submodule update --remote --recursive
```

### Usage

The timescales are fixed at present:

| Name          | Timescale          |
| ------------- | -------------      |
| Morning       | 9:00 AM - 12:00 PM |
| Noon          | 12:00 PM - 14:00   |
| Afternoon     | 14:00 - 18:30      |
| Evening       | 18:30 - 23:00      |
| Daytime       | 9:00 AM - 18:30    |
| Whole Day     | 9:00 AM - 23:00    |
