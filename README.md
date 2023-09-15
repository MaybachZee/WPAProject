# Time Management Application

This is a desktop time management application for managing your semester's study hours.

## Prerequisites

- Windows Operating System
- [.NET Framework](https://dotnet.microsoft.com/download/dotnet-framework) (typically pre-installed on Windows)

## How to Compile and Run

1. Clone this repository to your local machine:


2. Open the solution file `MaybachZee.sln` in Visual Studio.

3. Build the solution by pressing `Ctrl + Shift + B` or selecting "Build" from the Visual Studio menu.

4. Start the application by pressing `F5` or selecting "Start Debugging" from the Visual Studio menu.

5. The application's main window should now appear.

## Usage Instructions

1. Adding Modules:
- Enter module details (code, name, credits, class hours per week) and click "Add Module."

2. Setting Semester Parameters:
- Enter the number of weeks in the semester.
- Select the start date of the semester using the date picker.
- Click "Calculate" to update module self-study hours.

3. Recording Hours:
- Select a module from the dropdown.
- Choose a date using the date picker.
- Enter the number of hours worked.
- Click "Record Hours."

4. Viewing Remaining Self-Study Hours:
- The remaining self-study hours for each module will be displayed in the list.

5. Adding More Modules:
- You can continue adding more modules by entering their details and clicking "Add Module."

## Notes

- Data is not persisted between runs; it's stored in memory while the application is open.
- Ensure valid inputs and dates are provided to avoid errors.
- Modules with duplicate codes or names cannot be added.

## Credits

This application was developed by [Your Name].

