# Disable Fields Example

Contains a Form that demonstrates how to disable and enable the different kinds of Fields available in a Form.

## Project Details

#### Built Using:
Aras 11.0 SP15

#### Versions Tested:
Aras 11.0 SP15

#### Browsers Tested:
Chrome 71

## Installation

#### Important!
**Always back up your code tree and database before applying an import package or code tree patch!**

### Pre-requisites

1. Aras Innovator installed (version 11.0 SP15 preferred)
2. Aras Package Import tool
3. DisableFieldsExample import package

### Install Steps

#### Database Installation

1.  Backup your database and store the BAK file in a safe place
2.  Open the Aras Package Import tool
3.  Enter your login credentials and click **Login**
    * _Note: You must login as root for the package import tool to succeed!_
4. Enter the package name in the TargetRelease field
    * Optional: Enter a description in the Description field
5. Enter the path to your local `..\DisableFieldsExample\Import\imports.mf` file in the Manifest File field
6. Select **aras.labs.disableFieldsExample** in the Available for Import field
7. Select Type = **Merge** and Mode = **Thorough Mode**
8. Click **Import** in the top left corner
9. Close the Aras Package Import tool

You are now ready to login to Aras and try out the example!

## Usage

1. Log in to Aras as admin
2. From the main window run **Actions > Open Disable Field Example**
3. You should see a dialog with a few different fields and a **Toggle** button next to each one
4. Pressing the toggle button will switch whether the field next to them is enabled or disabled

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

## Credits

Original Aras community project written by Christopher Gillis at Aras Corp.

Documented and published by Christopher Gillis for Labs. @cgillis-aras

## License

Aras Labs projects are published to Github under the MIT license. See the LICENSE file for license rights and limitations.