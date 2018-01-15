===============================
1.4 cocoapods
===============================

常用命令
-------------

::

	pod install --verbose --no-repo-update
	pod update --verbose --no-repo-update
	pod lib lint --verbose
	pod trunk push AppInfoTracker.podspec
	pod search AppInfoTracker
	pod trunk me
	pod setup
	ls -al ~/.cocoapods/repos/
	pod trunk push
	pod repo update --verbose


常见问题
-------------

pod install 失败原因
~~~~~~~~~~~~~~~~~~~~

- 可能是网络问题，重启teminal
