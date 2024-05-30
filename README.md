# PHP Simple CRUD

### ****Creating the Database Table****

Create a table named *user* inside your MySQL database using the following code.

```sql
CREATE TABLE `user` (
  `id` int(255) NOT NULL AUTO_INCREMENT,
  `first_name` varchar(255) NOT NULL,
  `last_name` varchar(255) NOT NULL,
  `date_birth` date NOT NULL,
  `email` varchar(255) NOT NULL,
  `gender` varchar(255) NOT NULL,
  `job` varchar(255) NOT NULL,
  PRIMARY KEY (`id`)
)
```

### ****Copy files to htdocs folder****

Download the above files. Create a folder named *crud* inside *htdocs* folder in *xampp* directory. Finally, copy the *crud* folder inside *htdocs* folder. Now, visit [localhost/crud](http://localhost/crud) in your browser and you should see the application.
