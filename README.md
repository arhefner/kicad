# KiCad Project Templates

This is a collection of KiCad project templates for various boards.

## Description

KiCad allows you to create a new PCB project from a template project. This can jump-start a project by creating a schematic pre-populated with components unique to a particular project type, as well as a board outline with pre-placed footprints for common headers, mounting holes, and the like.

## Getting Started

In the main KiCad application, select File -> New -> Project from Template... (or press Ctrl-T). Select the User Templates tab, and all of the installed templates will appear. Click on a specific template to see a description of the project and a preview of the board that will be created. Select a template and press OK. KiCad will prompt for a project location and create a new project for the selected board type.

### Dependencies

* KiCad v. 5.0 or greater

### Installing

Download the templates or check them out from the repository. Then copy the desired template folders to the KiCad user template folder. This folder can be found under Preferences -> Configure Paths... and is set by the KICAD_USER_TEMPLATE_DIR environment variable.

## Authors

Tony Hefner

## License

This project is licensed under the MIT License - see the LICENSE.md file for details

## Acknowledgments

The templates for expansion cards for the 1802/Mini computer are based on the excellent work of David Madole (https://github.com/dmadole). The 1802/Mini is a modular, expandable computer based on the RCA CDP1802 microprocessor.