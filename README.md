
# Smart-Trolley-with-Recommendation-System
This Project is a blend of IoT and Machine Learning to make shopping hassle-free with a recommendation of products to customers as the icing on the cake! 
Working:
First, the customer is supposed to scan to products which he/she wants to buy. These entries are instantaneously updated in an excel sheet and displayed on the LCD screen. Furthermore, the excel sheet is used as a dataset to perform recommendations for the buyer using Apriori Algorithm.

Hardware Requirements:
Arduino Uno
RFID Reader
RDIF Tags
Buzzer
LED
LCD Display
Jumper Cables
Bread Board

Software Requirements:
Arduino IDE, 
Jupyter Notebook, 
Mysql, 
Xampp.

Programming Languages:

Python, 
C Programming, 
Sql.

Libraries Used:

Arduino IDE:
MFRC522.h --> For RFID, 
LiquidCrystal_I2C.h --> For LCD Display.

Jupyter NB:

tkinter, 
pymysql, 
pandas, 
smtplib, 
mlxtend.

# How to run the code: 
Do the Required H/W Connections.


Open the 'Only_Read_UID' Arduino file, install the mentioned Libraries. Futhermore, change the RFID Tags in the code according to your Tags.


Open the XAMPP control panel and start Apache and Mysql.


Run the Sql queries in MySql DB from the 'App' file. Add more enties in DB if needed.


Open the 'PLX-DAQ-v2-AutoGrapher-RandomValue' excel file and connect the IDE in it to port 3.


Open and Run the 'Python_Code' file after installing the Libraries. 


Scan the RFID tags!!











# Snaps
![connection_ss](https://user-images.githubusercontent.com/67335951/117673729-a97c4000-b1c8-11eb-8eba-47bcd2137c47.jpg)
![excel_ss](https://user-images.githubusercontent.com/67335951/117674082-fe1fbb00-b1c8-11eb-9231-673bf22debed.PNG)
![image](https://user-images.githubusercontent.com/67335951/117674567-653d6f80-b1c9-11eb-8b9e-1b75e19e113f.png)
