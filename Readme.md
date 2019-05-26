Birder
======

Birder is a convenient clone of Twitter.

## Setup

1.  Clone the repository.

```bash
git clone https://github.com/Samyibekov/birder.git
```

2.  Create the `.env` file
    specifying the database and web server configuration
    parameters.

```bash

# Inside .env file...
# Database Configurations
BIRDER_DB_HOST=
BIRDER_DB_PORT=
BIRDER_DB_NAME=
BIRDER_DB_USER=
BIRDER_DB_PASSWORD=
BIRDER_DB_DIALECT= # one of 'mysql' | 'mariadb' | 'postgres' | 'mssql' 

# Web Server Configurations
BIRDER_DB_PORT=
```

3.  Install all the dependencies.

```bash
npm install
```

4.  Start the server.

```bash
node index.js
```

## Credits

Samyibekov Rasul Raiymbekovich <russell77intel@gmail.com>