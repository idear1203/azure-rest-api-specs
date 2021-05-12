## TypeScript

These settings apply only when `--typescript` is specified on the command line.
Please also specify `--typescript-sdks-folder=<path to root folder of your azure-sdk-for-js clone>`.

``` yaml $(typescript)
typescript:
  azure-arm: true
  package-name: "@azure/arm-synapse-sqlv3"
  output-folder: "$(typescript-sdks-folder)/sdk/synapse/arm-synapse-sqlv3"
  generate-metadata: true
  clear-output-folder: true 
```
