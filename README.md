# Запуск автотестов для разных языков интерфейса

Ссылка на курс: [Автоматизация тестирования с помощью Selenium и Python](https://stepik.org/course/575)

## HOW TO INSTALL:

### Python version -- 3.8.5


#### 1) Activate your virtual environment:

##### For Mac:
```python
python3 -m venv venv
source venv/bin/activate
```

##### For Windows:
```python
pip install virtualenv
virtualenv venv
venv\Scripts\activate
```


#### 2) Clone the repository to your local machine:

```python
git clone https://github.com/oldevgeny/autotesting_project.git
```


#### 3) Install the requirements:

```python
pip install --upgrade pip
pip install -r requirements.txt
```


## START:

#### Run PyTests

```python
pytest test_items.py
```

You also can add some arguments:

```python
--language
``` 
and 
```python
--browser_name
```
Examples:

```python
pytest --language=es test_items.py
```

```python
pytest --language=pt --browser_name=firefox test_items.py
```
