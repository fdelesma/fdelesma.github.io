# How to install QBlade in MacOs

by F. Delesma (Tested in Catalina)

## Preparations 

* Get the source code

https://qblade.org/downloads/#Source_Code

* Get Macports

https://www.macports.org/install.php 

Select the corresponding installer depending on your MacOS version

* Get qt5 from macports

* Check if GL path is included

Sometimes the GL path is missing add the appropiate path in the `Makefile`

E.g. I/opt/local/include/GL

* Check if cmath is included

For some reason the cmath file was installed elsewhere. To find it run

`find /opt/ -name cmath`

add one of the paths in the `Makefile`

In my particular case it was lookin for `tr1/cmath`in the following file

` `

-fopen (not supported)


