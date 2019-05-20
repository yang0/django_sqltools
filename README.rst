=====
django-sqltools
=====

django-sqltools可以将数据库的注释字段解析出来，生成model的verbose字段和help字段

同时支持反向操作，将model的verbose字段导成带注释的sql语句

Quick start
-----------

1. Add "django_sqltools" to your INSTALLED_APPS setting like this::

    INSTALLED_APPS = [
        ...
        'django_sqltools',
    ]

2. 将mysql数据库ENGINE改为：django_sqltools.mysql::

    'ENGINE': 'django_sqltools.mysql',

