# Getting started

```
python3 -m venv venv
```

```
. venv/bin/activate
```

## Within the virtual env:

```
pip install Flask
```

```
pip install --upgrade pip
```

```
pip install pytest coverage
```

```
export FLASK_APP=flaskr
export FLASK_ENV=development
flask run
```

## To test:

```
curl http://localhost:5000/hello
```

## Unit tests:

```
pytest -v
```

