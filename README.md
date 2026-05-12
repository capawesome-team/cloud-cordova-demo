# cloud-cordova-demo

[![Capawesome](https://github.com/capawesome-team/cloud-cordova-demo/actions/workflows/capawesome.yml/badge.svg)](https://github.com/capawesome-team/cloud-cordova-demo/actions/workflows/capawesome.yml)

A demo project that shows how to build an [Apache Cordova](https://cordova.apache.org/) app using [Capawesome Cloud](https://capawesome.io/cloud/).

## Stack

- [Apache Cordova](https://cordova.apache.org/) — Android + iOS
- Plain HTML / CSS / JavaScript

## Continuous Integration

[`.github/workflows/capawesome.yml`](.github/workflows/capawesome.yml) builds the app on every push to `main`, on pull requests, and on manual dispatch using the [Capawesome CLI](https://capawesome.io/docs/cloud/cli/).

### Required GitHub Secrets

| Secret | Description |
| --- | --- |
| `CAPAWESOME_CLOUD_TOKEN` | API token for Capawesome Cloud. |
| `CAPAWESOME_CLOUD_APP_ID` | ID of the corresponding app in Capawesome Cloud. |

## License

See [LICENSE](LICENSE).
