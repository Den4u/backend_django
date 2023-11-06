### ������� ������ �Kittygram�

### 1. �������� �������:
Kittygram - ��������� ������������� ����������� ����� �� ������ �������� ��������, �������� �� ������������ � ������������.

### 2. ��� ��������� ������:

����������� ����������� � ������� � ���� � ��������� ������:

```
git clone git@github.com:Den4u/infra_sprint1.git
```

```
cd infra_sprint1/backend
```

C������ � ������������ ����������� ���������:

```
python3 -m venv venv
```

```
source venv/bin/activate
```

���������� ����������� �� ����� requirements.txt:

```
python3 -m pip install --upgrade pip
```

```
pip install -r requirements.txt
```

��������� ��������:

```
python manage.py migrate
```

C������ ���� .env (� ���������� /backend), ���������� ���� ����-�������� ���� ���������� ���������.

```
SECRET_KEY=***
DEBUG=***
ALLOWED_HOSTS=***
```

��������� ������:

```
python manage.py runserver 0:8090
```
