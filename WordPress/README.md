# WordPress CLI Cheatsheets

## Database Management

### Exports the database to a file (mysqldump)

Runs mysqldump utility using DB_HOST, DB_NAME, DB_USER and DB_PASSWORD database credentials specified in wp-config.php.

`wp db export`

### Imports a database from a file

Runs SQL queries using DB_HOST, DB_NAME, DB_USER and DB_PASSWORD database credentials specified in wp-config.php.

`wp db import`

### Imports a database from a file

Runs SQL queries using DB_HOST, DB_NAME, DB_USER and DB_PASSWORD database credentials specified in wp-config.php.

`wp db import`

### Delete expired transients.

`wp transient delete --expired`

### Delete all transients.

`wp transient delete --all`

## User Management

### To Create a New Administrator User

`wp user create USERNAME EMAIL@DOMAIN.COM --role=administrator`

### To Remove a User

`wp user delete USERNAME`

### To Change a User's Role

`wp user update USERNAME --role=ROLE`
