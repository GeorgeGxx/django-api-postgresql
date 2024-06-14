### Activar virtualenv

`.\venv\Scripts\activate`

`.\.venv\Scripts\activate`

### Actualizar pip

python.exe -m pip install --upgrade pip

### Instalar dependencias

`pip install -r requirements.txt`

### Endpoints

- GET 

`localhost:8080/api/companies`

- POST

`localhost:8080/api/companies`

{
    "name": "Apple",
    "website": "http://www.apple.com/la/",
    "foundation": 1976
}

{
    "name": "Microsoft",
    "website": "https://www.microsoft.com/es-es",
    "foundation": 1975
}

- PUT

`localhost:8080/api/companies/1`

{
    "name": "Apple Inc",
    "website": "http://www.apple.com/la/",
    "foundation": 1976
}

- DELETE

`localhost:8080/api/companies/1`