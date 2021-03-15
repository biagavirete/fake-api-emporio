# Fake API - Empório

Fake API built with json-server to provide data to the following projects:

* <a href="https://github.com/biagavirete/emporio-dashboard">Dashboard - Empório da Cerveja</a>
* <a href="https://github.com/biagavirete/emporio_ecommerce">Ecommerce - Empório da Cerveja</a>

## Getting started

**Running fake API**

> Cloning fake API repository:

```bash
$ git clone https://github.com/biagavirete/fake-api-emporio.git
$ cd fake-api-emporio
```

> Installing dependencies

```bash
$ yarn
```

> Running fake server

```bash
$ json-server db.json -m ./node_modules/json-server-auth -r routes.json --port 4000
```
