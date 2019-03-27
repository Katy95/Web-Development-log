Check python version
---
	python --version
	Python 2.7.10
	
Installing with get-pip.py
---
	curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
	python get-pip.py
if shows error errors:
	Could not install packages due to an EnvironmentError: [Errno 13] Permission denied: '/Library/Python/2.7/site-packages/pip' 	Consider using the `--user` option or check the permissions.
	
	sudo python get-pip.py
	
Install pymysql
---
	sudo pip install pymysql

Check
--
	python
	>>>import pymysql
	>>>

Done!
