# Todo API Tareas.

## Api realizada en Node JS y Postgres.

### Su principal funcion es permitirnos crear tareas y asi saber si se realizo o no .

## Dependencias del Proyecto.

<ul>
<li>Node js</li>
<li>PostgreSQL</li>
<li>Express</li>
<li>Nodemon</li>
</ul>

## Instalar dapendencias

```sh
npm install
```

## Iniciar proyecto

```sh
npm run dev
```

## Models

```java
* {
*     title: 'Practicar express',
*     description: 'Ver videos de apoyo y crear otra API',
*     is_completed: false
* }
```

### Movies

<ul>
<li>Tiutlo</li>
<li>Descripcion</li>
<li>Completada/No completada</li>

</ul>

## Routes

### Todo

<ul>
<li>GET 
<br>
/api/v1/todo
<br>

```java
{TODOS LAS TAREAS/ALL TASK}
```

</li>
<li>POST 
<br>
/api/v1/todo
<br>

```java
{Crear Tarea/Create Task}
```

</li>
<li>GET 
<br>
/api/v1/todo/:id
<br>

```java
{Obtener Tarea segun ID/Get Task By ID}
```

</li>
<li>PATCH 
<br>
/api/v1/todo/:id
<br>

```java
{Modificar Tarea segun ID/Patch Task By ID}

```

</li>
<li>DELETE 
<br>
/api/v1/todo/:id
<br>

```java
{Eliminar Tarea segun ID/Delete Task By ID}

```

</li>
</ul>

<h4 style="text-align:center">Api creada por Snmoyano</h4>
