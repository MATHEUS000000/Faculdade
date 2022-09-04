# Faculdade
## Instalação 
```bash
cd  myapp 
php composer install
```

## create user
```rest
post http://localhost:8000/api/add-user
{
        "nome":"{{$randomFullName}}",
    "userName":"{{$randomUserName}}"
}
```
