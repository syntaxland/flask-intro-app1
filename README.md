(myapp) PS C:\Users\jb\dev\flask_projects\flask-intro> py
Python 3.9.2 (tags/v3.9.2:1a79785, Feb 19 2021, 13:44:55) [MSC v.1928 64 bit (AMD64)] on win32
Type "help", "copyright", "credits" or "license" for more information.
>>> from app import db
C:\Users\jb\Envs\myapp\lib\site-packages\flask_sqlalchemy\__init__.py:851: UserWarning: Nei: Neither SQLALCHEMY_DATABASE_URI nor SQLALCHEMY_BINDS is set. Defaulting SQLALCHEMY_DSE_URATABASE_URI to "sqlite:///:memory:".
  warnings.warn(
C:\Users\jb\Envs\myapp\lib\site-packages\flask_sqlalchemy\__init__.py:872: FSADeprecationWaionWarning: SQLALCHEMY_TRACK_MODIFICATIONS adds significant overhead and will be disaby defled by default in the future.  Set it to True or False to suppress this warning.      
  warnings.warn(FSADeprecationWarning(
>>> db.create_all()
