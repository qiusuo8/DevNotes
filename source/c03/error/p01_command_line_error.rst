===============================
命令行
===============================

brew install python3
----------------------

::

	Error: /usr/local/Cellar is not writable. You should change the
	ownership and permissions of /usr/local/Cellar back to your
	user account:
  	  sudo chown -R $(whoami) /usr/local/Cellar
	Error: Cannot write to /usr/local/Cellar

解决办法 ``sudo chown -R $USER /usr/local``
