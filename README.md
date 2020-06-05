The TA data collectors are split into smaller pieces because of the size restriction for GITHUB uploads. 
Generally we have this as a last resort if all other methods of sending the data collector are blocked by a companies firewall. 


Linux
---
To split files you run the command:  

`split -b 50m transformationadvisor-Linux.tgz transformationadvisor-Linux.tgz.`
  
To combine the files run the command:  

`cat transformationadvisor-Linux.tgz.* > transformationadvisor-Linux.tgz`


Windows
---

To split files you run the command:  

`split -b 50m transformationadvisor-Windows.zip transformationadvisor-Windows.zip.`
  
To combine the files run the command:

`cat transformationadvisor-Windows.zip.* > transformationadvisor-Windows.zip`


AIX
---
To split files you run the command:  

`split -b 50m transformationadvisor-AIX.tgz transformationadvisor-AIX.tgz.`
  
To combine the files run the command:  

`cat transformationadvisor-AIX.tgz.* > transformationadvisor-AIX.tgz`


Solaris
---
To split files you run the command:  

`split -b 50m transformationadvisor-Solaris.tgz transformationadvisor-Solaris.tgz.`
  
To combine the files run the command:

`cat transformationadvisor-Solaris.tgz.* > transformationadvisor-Solaris.tgz`
