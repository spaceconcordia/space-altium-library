# Title Blocks

When working on an official design for Space Concordia, the use of a Space Concordia title block is required. It allows for the proper documentation and traceability of the design. For a design to be considered complete, all fields must be filled out.

The fields can be filled out in Document Properties > Parameters.

## Importing a Title Block

To import a title block template, go to Design > Templates > General Templates > Choose Another File > [location of the desired template].

## Title Block Fields

The following list uses the following format: "Field name" (Parameter ID): "explanation".

* Title (Title): The title of the sheet. This should reflect the contents of the page.
* Project (Project): The name of the board currently being designed.
* Reference Number (RefNum): The internal ID assigned to the board.
* Used In (UsedIn): Name of the project or assembly the board in for.
* Drawn By (DrawnBy): The name of the main person who designed the circuit (and therefore drew the schematic).
* Approved By (ApprovedBy): The name of the person who checked the schematic and approved it (normally the subdivision lead).
* Size (<no ID; static text>): The size of the sheet.
* Date (Date): The date of completion of a version. This should be manually set once a schematic has been approved.
* Version (Version): The version of the board. It follows the <Major version>.<Minor version> format. Major versions deal with new elements being added or removed to the board. Minor versions deal with fixes and small changes.
* Sheet Number (SheetNumber, SheetTotal): The page number of the sheet, out of the total number of sheets. These two fields can also be edited going to Tools > Annotations > Number Schematic Sheets.

To edit fields globally, go to Project > Project Options > Parameters. Name the parameters using their ID, and they should apply globally to all sheets within the project.