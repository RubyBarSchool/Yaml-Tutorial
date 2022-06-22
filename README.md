# Yaml-Tutorial

This repository is used to store introductory articles about yaml. Help familiarize yourself with yaml:

## YAML_Syntax

```bash
    key-value pairs
    comments
    object
    lists
    booleans
    multi line strings
    env variables
```

## YAML_POPULAR

<img src="https://img.icons8.com/color/2x/docker.png" alt="Docker icon" width="40" height="33"> Docker<br/>
<img src="https://cdn.icon-icons.com/icons2/2699/PNG/128/kubernetes_logo_icon_168359.png" alt="Kubernetes icon" width="40" height="40"> Kubernetes<br/>
<img src="https://symbols.getvecta.com/stencil_73/122_ansible-icon.c76e065140.svg" alt="Ansible icon" width="40" height="40"> Ansible<br/>
<img src="https://cdn.icon-icons.com/icons2/2107/PNG/128/file_type_prometheus_icon_130229.png" alt="Prometheus icon" width="40" height="40"> Prometheus<br/>

- configuration files all written in YAML
- widely used format
- for different DevOps tools and applications

## What is YAML

- YAML is a data serialization language ( XML / JSON )
-

### What is a serialization language?

- standard format to transfer data

YAML Ain't Markup Language

### File extension:

- .yaml .yml

## YAML Format compared to others

- human readable and intuitive

### YAML

```yaml
microservices:
  - app: user-authentication
    port: 9000
    version: 1.0
```

### XML

```xml
<microservices>
    <microservice>
        <app>user-authentication</app>
        <port>9000</port>
        <version>1.0</version>
    <microservice>
</microservices>
```

### JSON

```json
{
  "microservices": [
    {
      "app": "user-authentication",
      "port": 9000,
      "version": "1.0"
    }
  ]
}
```

<img src="https://cdn-icons-png.flaticon.com/128/3176/3176298.png" alt="Idea icon" width="40" height="40"> YAML is superset of JSON: any valid JSON file is also a valid YAML file.

[Tool yaml online](https://onlineyamltools.com/)
