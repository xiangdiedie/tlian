I change the code in main.aadl
1. I split Controller and Sender/receiver module from DEVICE_COMTROLLER_MONITOR.
2. Because sender and receiver have similar functions, and they have common functions like parsing data. So I make an encapsulation as S_R.