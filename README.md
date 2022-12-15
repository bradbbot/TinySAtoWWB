# TinySAtoWWB

TinySAtoWWB Convertor
By Brad Baisley

--

This is a Windows Powershell script which converts CSV files generated by TinySA-App into a CSV format useable in the coordination tab of Shure Wireless Workbench


Instructions:
-Open TinytoWWBfix.ps1 in a text editor like Notepad, Notepad++ or Powershell ISE
-Edit the input file path to the CSV generated by TinySA-APP one spot at the top of the script C:\PATHTOYOUR\INPUTFILELOCATION.csv
-Edit the output file path to wherever you would like the new file be deposited.  4 places at the bottom of the script need your path replaced C:\PATHTOYOUR\OUTPUTFILELOCATION.csv 

-Save TinytoWWBfix.ps1 

-Open tinytowwb.bat in a text editor
-change the path to whereyour TinytoWWBfix.ps1 is located C:\PATHTOYOUR\TinytoWWBfix.ps1
-Save

-Double click tinytowwb.bat and the file you have pointed it to should be processed and outputted to the file location and name you specified.

-Alternativly you can just right click on your updated TinytoWWBfix.ps1 and select Run with PowerShell.
