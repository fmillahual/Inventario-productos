# Inventario Productos

## Tecnologias
* Java: 17
* SpringBoot: 6.0.9 
* Spring Data JPA
* Maven
* Lombok 1.18.26
* MySQL

### Descripcion
Proyecto 'Inventario Productos' para practicar SpringBoot y Angular
### Base de datos
DB:MYSQL </br>
SCRIPT:scripts/category/category.sql
### Kanban 
Trello:https://trello.com/b/9rVKgkWA/proyecto-control-de-inventario \

### Test API

* Recuperar todas las categorias
* Recuperar categoria mediante id
* Agregar una nueva categoria

```
┌──────────┬──────────────────────────────────────┐
│  METODO  │              RECURSO                 │
├──────────┼──────────────────────────────────────┤
│GET       │localhost:8080/api/v1/categories      │
├──────────┼──────────────────────────────────────┤
│GET       │localhost:8080/api/v1/categories/<ID> │
├──────────┼──────────────────────────────────────┤
│POST      │                                      │ 
└──────────┴──────────────────────────────────────┘
```
Ejemplo POST categoria

```
{
	"name": "Deportes",
	"description": "Artículos y equipos deportivos"
}
```
