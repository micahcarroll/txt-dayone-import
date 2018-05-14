# DayOne-txt-import
Assists in merging and formatting txt files to prepare for importing in DayOne. Built for version 2.6.1.

## When is this script useful?
- You have a bunch of `.txt` files that you would want to import into DayOne
- The `.txt` files do not have the proper date formatting (specified [here](http://help.dayoneapp.com/day-one-2-0/importing-data-to-day-one)), and you would like to add it automatically to all `.txt` files

## Usage

1) Place all your `.txt` files in the DayOne-txt-import folder
2) Run the script using `sh dayone_format_txt.sh`
3) Go to `DayOne -> File -> Import` and select the file `diary_log.txt` that was generated by the script

Hopefully it should all work smoothly.

**Note: the `Last Modified Date` of the files will be the date associated with each entry in the final log**
