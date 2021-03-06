# txt-dayone-import
Assists in merging and formatting `.txt` files to prepare for importing in DayOne. Built for version 2.6.1.

## When is this script useful?
- You have a bunch of `.txt` files that you would want to import into DayOne
- The `.txt` files do not have the proper date formatting (specified [here](http://help.dayoneapp.com/day-one-2-0/importing-data-to-day-one)), and you would like to add it automatically to all `.txt` files

## Usage

1) Clone the repo with the command `git clone git@github.com:micahcarroll/txt-dayone-import.git`
2) Place all your `.txt` files in the `txt-dayone-import`
3) Run the script using the command `sh dayone_format_txt.sh`
4) Go to the DayOne dropdown menu: `File -> Import` and select the file `diary_log.txt` that was generated by the script in the same folder

Hopefully it should all work smoothly. Feel free to email me for any issues.

**Note: the `Last Modified Date` of the files will be the date associated with each entry in the final log**
