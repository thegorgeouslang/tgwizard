# TheGorgeousWizard
Project and resource creator for the MVC Framework TheGorgeous

### Commands list
| Action | Command | Alt. Comm.
| ------ | ------ | ------ |
| Resources List | -list | -l |
| Create Project | -create-project | -c |
| Create Controller | -create-controller | -ct |
| Create Model | -create-model | -m |
| Create DAO | -create-dao | -dao |

**Listing the Resources**
```sh
$ tgwizard -l 

$ tgwizard -list
```

**Create a project**
By default the storing solution will be RAM and the session will be the default.
```sh
$ tgwizard -c ProjectName

$ tgwizard -create-project ProjectName
```
You can specifying a valid DBMS (MySQL, Postgresql, DynamoDB, MongoDB, SQLite or RAM -  case insensitive) and/or
a non default session approach (JWT or Default - case insensitive):
```sh
$ tgwizard -c ProjectName -db dynamodb -sess jwt

$ tgwizard -create-project ProjectName -database dynamodb -session jwt
```
**Create a Controller**
```sh
$ tgwizard -ct ControllerName

$ tgwizard -create-controller ControllerName
```
**Create a Model**
```sh
$ tgwizard -m ModeltName

$ tgwizard -create-model ModelName
```
**Create a DAO**
```sh
$ tgwizard -dao DAOName

$ tgwizard -create-dao DAOName
```

**by [James Mallon]**

[James Mallon]: <https://www.linkedin.com/in/thiago-mallon/>

