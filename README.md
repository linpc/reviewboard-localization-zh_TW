reviewboard-localization-zh_TW
=======================

* The Traditional Chinese Localization file for ReviewBoard.
* [Review Board] (http://www.reviewboard.org) 的繁體中文化。

Install
-----------------------
1. Go to your reviewboard installed directory.

	    # cd reviewboard
	    # mkdir -p locale/zh_TW/LC_MESSAGES
	    # cp django.mo locale/zh_TW/LC_MESSAGES/

2. Restart your web server.

You can also generate django.mo by youself.

    # cd reviewboard
    # cp django.po locale/zh_TW/LC_MESSAGES/
    # django-admin.py compilemessages

