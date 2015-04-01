
To install dependencies: `npm install`

To install `bunyan` globally so you can convert JSON log messages to a more readable format: `npm install -g bunyan`

e.g. `./brooklyn-client | bunyan`

`./brooklyn-client --data "/path/to/yaml/blueprint.yaml" --method POST --host 127.0.0.1 --port 8081 --path "/v1/applications" | bunyan`
