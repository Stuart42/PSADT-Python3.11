When building Python, make sure to get the offline files. They should end up in the 'Files' folder with the installer.

Similar to this command:
.\python-3.11.0-amd64.exe /layout .\

This install has also been customized with the 'truststore' package pre-installed, and the pip configuration set to use it.
This should avoid certificate issues when installing Python modules.

https://pip.pypa.io/en/stable/topics/https-certificates/

https://pip.pypa.io/en/stable/topics/configuration/

https://packaging.python.org/en/latest/tutorials/installing-packages/
