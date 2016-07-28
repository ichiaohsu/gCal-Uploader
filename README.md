# gCal-Uploader

gCal-Uploader is a small website project, designed to enable a little group of users
 to visit this webpage, drag and drop a excel file written in special format. This
 page would parse the content of the spreadsheet, let user choose google account,
 choose whose shift he/she wants to upload, and insert the shifts to google Calendar
 as events.

# URL

http://ichiaohsu.github.io/gCal-Uploader/

# Compatibility

Because I use fileAPI in HTML5, this page definitely does not support IE9 or below.

Google Chrome is recommended.

For Chrome user, I recommend you use version 45 or later.
For firefox user, it might be better to use ver. 46 or later.

For more information about browser support on fileAPI, please check:
http://caniuse.com/#feat=fileapi

# Dependencies

- bootstrap 3.3.6
- jQuery 2.2.3
- fileAPI
- [SheetJS](https://github.com/SheetJS/js-xlsx)

# Usage

To use this page is quite simple. You can follow the steps as below:

1. Select an excel file written in special format in your explorer
2. Drag it to the drop zone and drop it.
3. A month selector and a member selector would show up. Select the month and member you want to upload
4. Press Insert button
5. During the insertion of Google Calendar events, you could press the cancel button to abort the insertion.(Events already inserted would not be deleted)
