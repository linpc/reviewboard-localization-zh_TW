reviewboard-localization-zh_TW
=======================

* The Traditional Chinese Localization file for ReviewBoard.
* [Review Board] (http://www.reviewboard.org) 的繁體中文化。

Install
-----------------------
1. Edit `settings.py` under `ReviewBoard-1.x.x-py2.x.egg/reviewboard` directory.
    Change the language / timezone setting:

	    TIME_ZONE = 'Asia/Taipei'
	    LANGUAGE_CODE = 'zh-tw'
	    USE_I18N = True
	    LANGUAGES = (
	        ('en', _('English')),
		('zh-tw', _('Chinese')),
	    )

2. Go to your reviewboard installed directory.
    Simply just copy the `.mo` file I made.

	    # cd reviewboard
	    # mkdir -p locale/zh_TW/LC_MESSAGES
	    # cp django.mo locale/zh_TW/LC_MESSAGES/

    Or, you can also generate django.mo by youself.

	    # cd reviewboard
	    # cp django.po locale/zh_TW/LC_MESSAGES/
	    # django-admin.py compilemessages

2. Restart your web server.

