# DES-Trojan insertion

## Summary
Implemented a cryptography algorithm and inserted a trojan using VHDL. The cryptography algorithm implemented is Data Encryption Standard (DES) algorithm. The trojan inserted is a sequentially triggered synchronous trojan which is triggered after 2^12 encryption and decryption cycles are performed.
Payload- Random bits of the output corrupted and the correct output is leaked through a covert channel.
This project is implemented in Xilinx Vivado using VHDL.

## DES circuit
![image](https://github.com/KaavyaVarshitha/DES-Trojan/assets/143062029/0749d492-f6d2-4273-8bcf-5fc0983447c8)

![image](https://github.com/KaavyaVarshitha/DES-Trojan/assets/143062029/26e32e5d-58a1-4bc3-8507-c7cc87fa7bdc)


## DES circuit with trojan
![image](https://github.com/KaavyaVarshitha/DES-Trojan/assets/143062029/344f7502-708e-4fc8-b3f1-fd2e63246f9a)

![image](https://github.com/KaavyaVarshitha/DES-Trojan/assets/143062029/e8da73e5-fd7e-49cd-940e-3f302cf40b8d)

 
 ## Authors

Solution|Author(s)
--------|---------
DES Trojan | [Kaavya Varshitha Raman Shantha](https://github.com/KaavyaVarshitha) 
DES Trojan | [Ashwin Koshy John](https://www.linkedin.com/in/ashwinjohn02/) 
DES Trojan | [Vangumalla Sowmya Reddy](https://www.linkedin.com/in/reddy-sowmya-vangumalla/) 

## Version history

Version|Date|Comments
-------|----|--------
1.0|Dec 2023|Final 







