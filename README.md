# Setup jcli

Download the specified version of jcli and configure it with given jet-endpoint.

## Usage

```yaml
- name: Setup jcli
  uses: byzanteam/setup-jcli
  with:
    version: 0.0.1
    jet-endpoint: https://work.jet.app/api/v1
```

## Inputs

| name         | description                       | required | example                     |
| ------------ | --------------------------------- | -------- | --------------------------- |
| version      | version of jcli                   | ✅       | v0.0.1                      |
| latest       | whether to use the latest version | ❌       | true                        |
| jet-endpoint | GraphQL API endpoint of Jet       | ✅       | https://work.jet.app/api/v1 |
