Product Catalog API
===================

Playing with Apiary: API blueprint of a Product Catalog - a sample microservice.

Files
-----

- `apiary.apib` -> API Blueprint
- `dredd.yml` -> config file for Dredd, the testing tool
- `setenv.sh` -> set local environment (workaround for not being able to install dredd in global mode)

Notes
-----

### Testing with Dredd

- Could not `npm install -g dredd`
  - but `npn install dredd` is OK
  - then you need to add your local bin to path
    - you can get the path by `npm bin`
    - or use `. setenv.sh`
 

