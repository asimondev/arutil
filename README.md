# ARUTIL
Andrej's RAC Utility

## Description

ARUTIL is a command line tool for working with Oracle RAC. It helps you to display and prepare some often used *SRVCTL CONFIG* and *SRVCTL STATUS* commands.

## Using ARUTIL

ARUTIL is developed in Go. You should download the latest ARUTIL release and transfer the corresponding file to your Linux database server. After setting Oracle environment, unpacking ARUTIL and adding execute permissions with `chmod +x ./arutil_ol7` you can start ARUTIL.


![Start ARUTIL](https://github.com/asimondev/arutil/blob/main/screenshots/arutil_start.png)

You can display the available *list* and *service* subcommands using the `-h` option.

![ARUTIL list help](https://github.com/asimondev/arutil/blob/main/screenshots/arutil_list_help.png)

![ARUTIL service help](https://github.com/asimondev/arutil/blob/main/screenshots/arutil_service_help.png)


## See Also

[ARUTIL Documentation](https://asimondev.github.io/docs/arutil/)


***

This tool is developed by *Andrej Simon*, Oracle ACS Germany in my free time. If you have any 
questions or comments, please contact me directly (*andrej.simon@oracle.com*).

***

**Freeware disclaimer**: The author, Andrej Simon, of this freeware accepts no responsibility for damages resulting from the use of this product and makes no warranty or representation, either express or implied, including but not limited to, any implied warranty of merchantability or fitness for a particular purpose. This software is provided "AS IS", and you, its user, 
assume all risks when using it.
