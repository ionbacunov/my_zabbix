This is a modified zabbix Template for Monitoring Mikrotik Switch CRS-326-24G-2S+RM
This template is created and tested on zabbix 7 !  
Added :
1) SNMP walk SFP interface optical tx/rx power ( if your modules support DDM)
2) Display Graphs in graphs menu
3) Added Triggers for alarming if TX/RX are too bad/low ( you can adjust yourself any cifers) 
     Removed :
 1) Discovery/Walk Cap'sMAN/WLAN interfaces
 2) Discovery/Walk LTE interfaces

How to use :
1) make a backup of your original template ( export it ) (for reverting if something doesn't work )
2) delete original template after export
3) Import my template.
4) Enjoy !
