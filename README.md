# dummy rdfa editor
Dummy app of the rdfa-editor-addon for testing purposes.

## Running and maintaining

  General information on running and maintaining an installation

### Running your setup

#### Running the regular setup

  ```
  docker-compose up
  ```
Make sure, by using docker-compose.override.yml, to map port 80. By example:
```
version: "3.4"

services:
  rdfa-editor:
    ports:
      - "4201:80"
```
