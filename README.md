# Set-Time-DS3231-RTC
Set the time the first time you fire up a DS3231 RTC

This code should be used the first time you use an RTC or after you have installed a new battery (assuming you are using a watch battery as the backup power source).  After you run this the first time, you can then upload the code you want to run on the MCU and the time should be set.  

NOTE: This code sets the time to be the time the code is compiled, and so the RTC time will be a little behind the the time on the computer where the code was compiled.
