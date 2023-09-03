# 24hrs-Digital-Clock
This project implements a 24-hour digital clock on the Nexys A7 board using the Verilog language. The time is displayed on six seven-segment displays. The first two displays show the hours in 24-hour format, the second two displays show the minutes, and the third two displays show the seconds.
We converted time (seconds, minutes, hours) into bcd format such that we can increment one's place of seconds, minutes and hours from 0 to 9 and ten's place of seconds, minutes from 0 t0 5, and ten's place of hours is set to 0 to 2
We set a reset condition for seconds, minutes at 59 and hours at 23
Therefore, seconds,minutes display shows the value between 0 to 59 whereas hours display shows the value between 0 to 23
