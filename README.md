һ.��Ŀ���
1.����Ŀ��һ��С�͵���̳ϵͳ�����õ���python + flask ��Ŀ��ܽ��п���,�û����Խ����ʴ�ķ�����

2.��װ��飺
��1���ȴ����ñ��ص����⻷�����������������⻷���������⻷���д򿪱���Ŀ��

��2��pip install -r requirements.txt , ��װ����Ҫ�İ���

��3����config���޸����ݿ������
SQLALCHEMY_DATABASE_URI = 'mysql://user:password@localhost/database_name'
��д������ݿ��˺ţ����룬����һ�㣬������Ҫ�������ݿ��д�����һ�����ݿ⣬�����滻�����е�database_name.

(4) �����������⻷���У����뵽��Ŀ�ļ����С�
python manage.py db init      :����Ǩ�ƵĲֿ�
python manage.py db migrate   :����Ǩ�ƵĽű�
python manage.py db upgrade   :�������ݿ�

��5����pycharm������platform����
