# NetBeans IDE

Project website: https://netbeans.org/

Bug fix: This code was not actually downloading NetBeans to the VM. This issue was fixed by changing the download commands so that the turbo.me script properly downloads NetBeans. Unneccessary code in the downloads/install section was deleted. 

To build: 

    turbo build /path/to/turbo.me
