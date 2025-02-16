# DIY-WiFi-Backup
Wi-Fi backup using power bank & Decoy Module.

February-2025

https://github.com/user-attachments/assets/5bec8f8c-7398-422c-9678-f69734743a51

<b><h3>Some Back Story :</h3></b> 
After the college graduation I moved to Bengaluru for studies and Job hunt, I'm living with 2 of my friends. We're all studying some professional courses, so as a part of this we all have online exams once in a while. One day my friend was in the middle of an exam the power supply was gone, Wi-Fi turned off and the exam got interrupted in the middle and couldn't complete it. Also the cell reception in our building is also poor , so pairing with hotspot is not an option. So i thought about doing something to prevent it. 

<b><h3>Solution :</h3></b>

Buying a Wi-Fi UPS from online cost more than 1500 RS and due to budget constraint that was also not an option. As i was thinking, i happened to look into the power bank and saw it's capable of providing 9/12/20 volts ( it supports fast charging ).  But if we directly plug the USB cable and check the voltage it's only gonna provide 5v only.
So after searching in the internet, i found this decoy module, It's less than 150 Rs (including shipping charge ) from robu.in

![image alt](https://github.com/Anandhu-Sudha/DIY-WiFi-Backup/blob/832a50703499d6fb19bcd921dcfc691af6dd1c33/pictures/site.jpg)

![image alt](https://github.com/Anandhu-Sudha/DIY-WiFi-Backup/blob/0b3912b422a9740fa3481b37b190802ee2d77c23/pictures/Untitled-1.jpg)

<b><h3>What it does :</b></h3>

It's capable of extracting the maximum voltage from the power source acting like it needs it ( now the word 'decoy' makes sense ). 
So i ordered it & received the decoy module, i needed to check the output voltage and make sure it's not pushing more than 12 Volts, otherwise the Wi-Fi router gets damaged for sure.  The module contains 3 toggle switches by changing the position of these switches, different voltage is obtained, After checking the voltage levels with a digital meter, it was working as it promised to be, it was able to give 5,9,12 and 20 Volts at different modes. The modes and their voltage output is mentioned below. I adjusted the mode to set output voltage as 12 Volts and now it's working perfectly. 

in this mode it will give 5v 👇
![image alt](https://github.com/Anandhu-Sudha/DIY-WiFi-Backup/blob/832a50703499d6fb19bcd921dcfc691af6dd1c33/pictures/3.jpg)

15v 👇
![image alt](https://github.com/Anandhu-Sudha/DIY-WiFi-Backup/blob/832a50703499d6fb19bcd921dcfc691af6dd1c33/pictures/4.jpg)

21v 👇
![image alt](https://github.com/Anandhu-Sudha/DIY-WiFi-Backup/blob/832a50703499d6fb19bcd921dcfc691af6dd1c33/pictures/5.jpg)

12v ( i'm using this for the Wi-Fi router) 👇
![image alt](https://github.com/Anandhu-Sudha/DIY-WiFi-Backup/blob/832a50703499d6fb19bcd921dcfc691af6dd1c33/pictures/6.jpg)

9v 👇
![image alt](https://github.com/Anandhu-Sudha/DIY-WiFi-Backup/blob/832a50703499d6fb19bcd921dcfc691af6dd1c33/pictures/7.jpg)

<b><h3>Cons : </b></h3>

Even though it works as expected, <h3>it cannot be used as UPS.</h3> When the power bank is plugged for charging and if it's also powering the decoy module, when the charging goes off (due to: unplug/power-cut...) the power bank will reset and due to this the Wi-Fi router also gets reset. So this can be only used for " Preventing the Failure " or can use while the power supply is out. To use it as a UPS, So kind of additional circuitry is needed. Once i found out, it will be appended here.
