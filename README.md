# Faculdade

## create user
<code>
post http://localhost:8000/api/add-user
{
        "nome":"{{$randomFullName}}",
    "userName":"{{$randomUserName}}"
}
</code>

