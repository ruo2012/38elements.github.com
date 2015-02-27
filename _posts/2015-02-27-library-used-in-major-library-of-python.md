---
layout: posts
title: Pythonの主要なライブラリで使用されているライブラリは何か調べました。
---
この[ランキング](/2015/02/11/python-repository-github-star-ranking.html)にあるrepositoryのsetup.py、requirements.txt、requirements/default.txt、requirements/default.txt       
から使用されているライブラリを取得して集計しました。プログラムで自動化して集計しました。そのプログラムで使用した       
正規表現のパターンが十分ではないので集計漏れがあると思います。     
<pre style="background-color: white;border: none;">
requests            84
six                 74
django              64
flask               50
jinja2              46
numpy               39
nose                35
pillow              33
mock                33
lxml                31
argparse            31
pyyaml              31
python-dateutil     30
simplejson          29
sqlalchemy          28
sphinx              28
pygments            27
pytz                26
redis               25
coverage            25
wsgiref             23
tornado             22
werkzeug            21
markupsafe          20
beautifulsoup4      19
psutil              18
boto                17
setuptools          17
pymongo             16
docutils            15
gunicorn            15
scipy               14
flask-sqlalchemy    14
gevent              14
click               13
unidecode           13
decorator           13
south               13
twisted             13
itsdangerous        13
flake8              13
docopt              13
pytest              12
httplib2            12
pycrypto            12
cssselect           11
markdown            11
greenlet            10
pyopenssl           10
paramiko            10
zope.interface      9
psycopg2            9
chardet             9
html5lib            9
pep8                9
alembic             9
pandas              9
cython              8
tox                 8
babel               8
pyparsing           8
celery              8
mako                8
dnspython           8
webob               8
beautifulsoup       7
matplotlib          7
flask-login         7
nltk                7
flask-wtf           7
mysql-python        7
whoosh              7
jsonschema          7
pastedeploy         7
wtforms             7
selenium            7
bottle              7
distribute          7
fabric              7
flask-mail          7
prettytable         6
eventlet            6
sqlparse            6
djangorestframework 6
flask-script        6
python-openid       6
pyserial            6
unittest2           6
blinker             6
ipython             6
raven               6
paste               6
feedparser          5
pbr                 5
msgpack-python      5
pytest-cov          5
pylint              5
requests-oauthlib   5
py                  5
pyflakes            5
enum34              5
virtualenv          5
amqp                5
passlib             5
</pre>