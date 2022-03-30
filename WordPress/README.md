# WordPress CLI Cheatsheets

## Database Management

### Exports the database to a file (mysqldump)

Runs mysqldump utility using DB_HOST, DB_NAME, DB_USER and DB_PASSWORD database credentials specified in wp-config.php.

`wp db export`

### Imports a database from a file

Runs SQL queries using DB_HOST, DB_NAME, DB_USER and DB_PASSWORD database credentials specified in wp-config.php.

`wp db import`

### Imports a Database from a File

Runs SQL queries using DB_HOST, DB_NAME, DB_USER and DB_PASSWORD database credentials specified in wp-config.php.

`wp db import`

### Delete Expired Transients.

`wp transient delete --expired`

### Delete All Transients.

`wp transient delete --all`

## User Management

### To Create a New Administrator User

`wp user create USERNAME EMAIL@DOMAIN.COM --role=administrator`

### To Remove a User

`wp user delete USERNAME`

### To Change a User's Role

`wp user update USERNAME --role=ROLE`

---

[Check the official WP-CLI documentation for additional information.](https://developer.wordpress.org/cli/commands/)
