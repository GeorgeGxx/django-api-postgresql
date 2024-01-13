.\venv\Scripts\activate

Enpoints

- GET 

localhost:8000/api/companies

- POST

localhost:8000/api/companies

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

localhost:8000/api/companies/1

{
    "name": "Apple Inc",
    "website": "http://www.apple.com/la/",
    "foundation": 1976
}

- DELETE

localhost:8000/api/companies/1