This is an attempt to test vforwater django project. Some lines of the codes have been modified and changed to able to run the project in local host. 

- Files to fill PostGRESQL database (db_schema_dump.sql and  db_data_dump.sql) has not been provided in the repository. 
- Some of the divs are removed from html's due to missing templates error (quick_files.html, map_model.html)
- Geoserver setting are modified with random local geoserver information so that, no error raised in related functions. 


![image](https://user-images.githubusercontent.com/15700676/173160127-29e6f8d6-f4ea-41de-be96-17d38f10a7cc.png)



# V-FOR-WaTer portal

Vforwater-portal is an open source virtual research environment written in django for common and systematic management of data obtained from water and environmental research.

![Dev status](https://img.shields.io/badge/development%20status-2%20--%20Pre--alpha-orange)
 [![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)



# Installation notes

For installation instructions please look at [`install_notes.txt`](install_notes.txt).
There are no special dependencies on the LINUX distribution. We tested the installation on Fedora 29, 30, Centos 7, and RHEL 7.
Code is still under development and comes with no guarantees.

# Dependencies

vforwater-portal is a Django project (we testet Django 3.2, python 3.7)
The following components are needed:
* PostGIS (we testet postgresql 9.6, 10.6, 11.2 + postgis 2.4, 2.5)
* Geoserver (we testet 2.12.2 and 2.14.1, Oracle Java + tomcat or OpenJDK)

# License

Vforwater-portal is licensed under the MIT license.
