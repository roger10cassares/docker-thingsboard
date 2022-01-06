# docker-thingsboard

From this top level directory:
```bash
mkdir -p ./thingsboard/data && sudo chown -R 799:799 ./thingsboard/data
mkdir -p ./thingsboard/logs && sudo chown -R 799:799 ./thingsboard/logs
```

Build the docker images:
```bash
docker-compose build
```

Run the docker images:
```bash
docker-compose up
```

Go to thingsboard home page and log in:
http://127.0.0.1:9090

System Administrator: sysadmin@thingsboard.org / sysadmin
Tenant Administrator: tenant@thingsboard.org / tenant
Customer User: customer@thingsboard.org / customer