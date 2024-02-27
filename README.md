These are files for upload to App Script in google sheet
Step to upload:
1. goto google drive
2. create new google sheet file
3. goto extension tab and select App Script
4. clear content in the Code.gs
5. copy code from gsheet_Temperature for storing temperature data,
   copy code from gsheet_Counter for storing counter data.
   change sheetID to your sheet ID.
7. click save and click deploy button
8. select new deployment
9. select App on the left side and select authorize for anyone, then click deploy
10. copy deployment ID and save in your keeping folder.

How to save deployment iD into microcontroller (IOT Box)
1. connect miniusb cable to microcontroller(esp32) and computer usb port
2. open serial monitor software (S/P) or Arduino IDE or other USB serial reader.
3. key in to send command to IOT Box
   - for gsheetT SheetT --- Temperature
   *gsheetT=[deployment ID]     
   - or for gsheet SheetC --- Counter
   *gsheet=[deploment ID]
    then press send or enter
...end
   - *gsheetC=[deploymentID]
   - 
