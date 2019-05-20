# django_sqltools
根据model生成sql，或者根据sql生成model


# 打包
python setup.py sdist

# 安装
pip install --user dist/*

# 使用
1 给项目指定一个新的测试数据库
2 清理所有migration目录
3 运行 python manange.py allmigrations
4 运行 python manage.py makesql
