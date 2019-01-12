# Read carefully before using this project


##Steps to download the content of EEPROM into a file:

1. First, make **download_rom()** function only active and flash the sketch into your arduino.
2. Configure **serial port** and **baud rate** in **download_rom.py** according to your arduino sketch.
3. Run **download_rom.py** by entering '**python2.7 download_rom.py**' in your terminal/cmd window.
4. Press **reset** button in your arduino.
5. Now press '**d**' and hit enter in the prompt in your terminal/cmd window and wait for finish.


##Steps to upload a file from computer to the EEPROM:

1. First, make **upload_rom()** function only active and flash the sketch into your arduino.
2. Configure **serial port** and **baud rate** in **upload_rom.py** according to your arduino sketch.
3. Run **upload_rom.py** by entering '**python2.7 upload_rom.py**' in your terminal/cmd window.
4. Press **reset** button in your arduino.
5. Enter the file path i.e. '**/path/to/the/file.rom**' and hit enter and wait for finish.