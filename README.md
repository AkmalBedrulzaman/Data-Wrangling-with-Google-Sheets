# Data Wrangling with Google Sheets by using Netflix Shows Dataset


## 1) Loading Data into Google Sheets

#### Upload Dataset
open google sheets - file - import - upload - rename the google sheets to Nextflix Shows Raw Data
#### Save the Dataset at Google Drive 
file - move - new folder - give title - move here
#### Make a Copy of Raw Data to Use as Data Wrangling
file - make a copy - select folder - make a copy - rename the google sheet to Netflix Shows Data Wrangling
#### Clear Any Formatting in Dataset
format - clear formatting
#### Resize the Column Header
select whole dataset - double click betweeen any columns
#### Lock Header 
drag down thing at the top of row 1 - put at bottom of row 1 
#### Format Header by Giving Cell and Text Colour
select header row - fill colour - text colour
#### Change Header Wording 
change manually by capitalized the first character and put some space between other word 

---

## 2) Inspecting Data

#### Make an Action List for Data Cleaning
press add sheet at the bottom left - rename it to Cleaning Actions - list all outstanding data cleaning here
#### How to Select Whole Dataset Shortcut
shift - ctrl - right arrow - down arrow
#### Highlight Missing Values
select whole data - format - conditional formatting - is empty - choose colour - done
#### Highlight Text is NA
format - conditional formatting - add another rule - text exactly - give values NA - choose colour - done
#### Use Transpose Function to change header column to row
type =TRANSPOSE(A1:G1) - it will change from column to row position
#### Use Countblank Function to Calculate Blank Cell
type =COUNTBLANK(A2:A1001) - it will calculate total blank cell
#### Use Countif Function to Calculate Missing Value Denoted by NA 
type =COUNTIF(F2:F1001, "NA") - it will calculate total NA
#### Check Data Type Format Manually
choose one column - more formats - change manually if needed
#### Check Column Stats 
column - data - column stats
#### Check Spelling Errors
select whole data - tools - spelling - spell check

---

## 3) Data Cleaning

#### Remove Duplicates






