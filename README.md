<p align="center"><img src="https://user-images.githubusercontent.com/34022590/111371494-2cd65500-86a2-11eb-8479-f2241d6b6e51.jpg" width="300px"></p>

<h1 align="center">
    <strong>CookBook - Kokaraamat</strong>
</h1>
<h3 align="center">
    <p>CookBook App in ASP.NET</p>
</h3>

### Main page

<p align="center"><img src="https://user-images.githubusercontent.com/34022590/112002395-81f1eb00-8b28-11eb-8cb4-becff5d33bfa.png" width="450px"></p>
Full list of recipies from all users with
* Details link

<hr>

### Features
* To log in users
* Each user can create/read/update/delete their receipies
* All receipies displayed on main page

<hr>

### Database
Database 'Kitchen'

Table 'Recipe':
| Column Name | Data Type |
|-|-|
| Id(Primary Key) | int |
| Name | varchar(50) |
| Author | varchar(50) |
| Indrigents | varchar(1000) |
| Method | varchar(1000) |
| Comment | varchar(300) |
| Image | varbinary(MAX) |

Table 'User'
| Column Name | Data Type |
|-|-|
| UserName | nvarchar(50) |
| Password | nvarchar(50) |

<hr>

### Details view not logged in

<p align="center"><img src="/CookBook/pic/details.png" width="300px"></p>
With links to
* List

<hr>

### Login page

<p align="center"><img src="/CookBook/pic/login.png" width="300px"></p>

<hr>

### List of users receipies

<p align="center"><img src="/CookBook/pic/userlist.png" width="450px"></p>
With CRUD options

<hr>

### Edit page

<p align="center"><img src="/CookBook/pic/edit.png" width="300px"></p>
With
* Save button
* Back to list link

<hr>

### Create new page

<p align="center"><img src="/CookBook/pic/create.png" width="300px"></p>

<hr>

### Details view when logged in

<p align="center"><img src="/CookBook/pic/userdetails.png" width="300px"></p>
With links to
* Edit
* List

# HAPPY COOkING !!! :)
