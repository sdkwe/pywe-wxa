========
pywe-wxa
========

Wechat Module for Python for MiniProgram.

Installation
============

::

    pip install pywe-wxa


Usage
=====

::

    from pywe_wxa import get_session_key, get_userinfo, get_phone_number


Method
======

::

    def get_session_key(self, appid=None, secret=None, code=None, grant_type='authorization_code', storage=None):

    def get_userinfo(self, appid=None, secret=None, code=None, grant_type='authorization_code', session_key=None, encryptedData=None, iv=None, storage=None):

    def get_phone_number(self, appid=None, secret=None, code=None, grant_type='authorization_code', session_key=None, encryptedData=None, iv=None, storage=None):

