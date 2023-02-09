
# Postgres Installation

* `sudo apt update`

* `sudo apt install postgresql`

## Check if Postgresql is active:
* `sudo systemctl is-active postgresql`

* `sudo systemctl is-enabled postgresql`

* `sudo systemctl status postgresql`

* `sudo pg_isready`
 
* If you don't see any error messages, we are good to go. 

## Creating a DB:

* Access Postgres database shell:

* `sudo su - postgres`

* `psql`

* Here it should enter in the psql shell like this:

* `postgres=#` 
