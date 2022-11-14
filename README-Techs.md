## Updating Python Application
When building Python, make sure to get the offline files. They should end up in the 'Files' folder with the installer.

### Download Python command:
.\python-3.11.0-amd64.exe /layout .\

Make sure to edit the unattend.xml in the Files folder with the correct path for the version of Python you are creating


This install has also been customized to install the 'truststore' package by trusting the python servers, and copies pip.ini with configuration set to use the truststore package.

This should avoid certificate issues when installing Python modules.

https://pip.pypa.io/en/stable/topics/https-certificates/

https://pip.pypa.io/en/stable/topics/configuration/

https://packaging.python.org/en/latest/tutorials/installing-packages/
