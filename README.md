# fastapi-rest-api

1. create env

```
python3 -m venv env
source env/bin/activate
```

2. install requirements

```
pip install -r requirements.txt
```

or libraries

```
pip install fastapi uvicorn pydantic
```

3. start server

```
python3 main.py
```

4. If "Uvicorn running on http://0.0.0.0:8000" not working, try to "http://127.0.0.1:8000/"

5. get Docs

```
http://127.0.0.1:8000/docs
```

or

```
http://127.0.0.1:8000/redoc
```
