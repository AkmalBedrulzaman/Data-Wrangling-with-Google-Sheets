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
    type function =TRANSPOSE(A1:G1) - it will change from column to row position
#### Use CountBlank Function to Calculate Blank Cell
    type function =COUNTBLANK(A2:A1001) - it will calculate total blank cell
#### Use CountIF Function to Calculate Missing Value Denoted by NA 
    type function =COUNTIF(F2:F1001, "NA") - it will calculate total NA
#### Check Data Type Format Manually
    choose one column - more formats - change manually if needed
#### Check Column Stats 
    column - data - column stats
#### Check Spelling Errors
    select whole data - tools - spelling - spell check

---

## 3) Data Cleaning

#### Remove Duplicates
    data - data cleanup - remove duplicates - select all - remove - then delete rows that empty due to duplicates
#### Filter the Missing Value
    create filter - select column that has missing value - select blanks only 
#### Handle Missing Value by Drop Technique
    create filter - select column that has missing value - select blanks only - delete all rows - data - remove filter
#### Handle Missing Value NA using IF Function by Flag Technique
    add new column - rename it as missing in user rating score - type function =IF(F2="NA", "Missing", "Not Missing")
#### Handle Missing Value NA and Blank using IFOR Function by Flag Technique
    type function =IF(OR(F2="NA", F2=" "), "Missing", "Not Missing")
#### Handle Missing Value with Fill in 0 using IFOR Function by Impute Technique 
    type function =IF(OR(F2="NA", F2=" "), 0, F2)
#### Handle Missing Value with Fill in Average using IFOR Function by Impute Technique
    type function =IF(OR(F2="NA", F2=" "), AVERAGE(F:F), F2) 
#### Data Cleaning using CLeanup Suggestion
    data - data cleanup - cleanup suggestion - handle all suggestion
    
    
#### 
#### 
####
#### 
####






