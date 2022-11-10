# Todo-Restful-webservices

## Rest endpoints

### Api Documentation

1 . **To save the task**  
`Post` `localhost:9090/todo/addtask`  

`Requestbody` 
```JSON
{
    "taskName": "Install Eclipse 1",
    "taskEndDate": "2022-11-20",
    "taskStatus": "Y"
}
```
`Response` 
```JSON
{
    "taskId": 4,
    "taskName": "Install Eclipse 1",
    "taskEndDate": "2022-11-20",
    "taskStatus": "Y"
}
```
--------------------------------------------------------------------------------------------------------------------------------------------

2 . **To list all tasks **

`Get` `localhost:9090/todo/list`  

`Requestbody` 
```JSON
{
    "taskName": "Install Eclipse 1",
    "taskEndDate": "2022-11-20",
    "taskStatus": "Y"
}
```
`Response` 
```JSON
{
    "taskId": 4,
    "taskName": "Install Eclipse 1",
    "taskEndDate": "2022-11-20",
    "taskStatus": "Y"
}
```
--------------------------------------------------------------------------------------------------------------------------------------------

3. **To update a task **

`Post` `localhost:9090/todo/updatetask`  

`Requestbody` 
```JSON
{
    "taskName": "Install Eclipse 1",
    "taskEndDate": "2022-11-20",
    "taskStatus": "Y"
}
```
`Response` 
```JSON
{
    "taskId": 4,
    "taskName": "Install Eclipse 1",
    "taskEndDate": "2022-11-20",
    "taskStatus": "Y"
}
```
--------------------------------------------------------------------------------------------------------------------------------------------

4. **To delete a task  **

`Post` `localhost:9090/todo/deletetask/1`  

`Requestbody` 
```JSON
{
    "taskName": "Install Eclipse 1",
    "taskEndDate": "2022-11-20",
    "taskStatus": "Y"
}
```
`Response` 
```JSON
{
    "taskId": 4,
    "taskName": "Install Eclipse 1",
    "taskEndDate": "2022-11-20",
    "taskStatus": "Y"
}
```
--------------------------------------------------------------------------------------------------------------------------------------------
