## Configuration

The following table lists the configurable parameters of the httpd chart and their default values.

|          Parameter           |                Description                 |                   Default               |
| ---------------------------- | ------------------------------------------ | --------------------------------------- |
| `image.registry`             | Httpd image registry                       | `192.168.201.163:8080`                  |
| `image.repostiory`           | Httpd image name                           | `public/httpd`                          |
| `image.tag`                  | Httpd image tag                            | `{VERSION}`                             |
| `image.pullPolicy`           | Image pull policy                          | `Always` if `imageTag` is `latest`, else `IfNotPresent`  |
