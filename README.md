# TestStand Layout Loader

![Warning](https://raw.githubusercontent.com/425J/LayoutLoader/main/Documentation/w0.svg)

## Description

This tool automatically loads the TestStand layout (`layout_*.bin`) assigned to the user. The layout file is specified _indirectly_ in the user attribute. User attribute specifies UI configuration XML file path (using `%EnvTestStandAppData%`), which specifies layout file to load at startup. This solution requires SeqEdit.exe restart.

## Requirements

To use the tool:
- TestStand 2021 (ni-teststand-2021-x86)

## Installation

Run `.\Installer\Install.seq`. Select menu **View»Output** to see installation details. After successful installation, Layout Loader is automatically launch after login.

NOTE: You must also run `.\Installer\SetEnvironmentVariables.bat` (run as administrator) to create environment variables.
