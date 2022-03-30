# WordPress CLI Cheatsheets

## Database management

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
