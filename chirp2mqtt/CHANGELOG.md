<!-- https://developers.home-assistant.io/docs/add-ons/presentation#keeping-a-changelog -->

## +1.1.102

- Initial release

## 1.1.108

- Added MQTT server naming requirements to documentation. Added payload checks. Fixed MQTT server IP naming in region description file. Upgrade to ghcr.io/hassio-addons/base:17.1.0, CHIRPSTACK_VERSION: 4.11.0

## 1.1.116

- Code extended to support MQTT component integrations. Replaced custom js evaluator with dukpy package

## 1.1.125

- Tests extension and minor fixes in code, file cleanup. Initialization re-factoring, fixed issue with log level

## 1.1.126

- Added logging control via MQTT message: topic application/{ChirpStack appId}/bridge/info, message '{"log_level":"debug"}'. Added per device online checks. Initialization and logging re-factoring

## 1.1.127

- Added optional expire after MQTT configuration item discovery message
