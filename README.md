# status-badge

Define the status badge for the [pcf-status](https://github.com/ECSTeam/pcf-status) project.

To use this, just make the SVG public and set a query string as follows `http(s):\\<path-to-image>.svg?server=<the name of the server>`. This will then generate an image like this:

![Badge](https://rawgit.com/ECSTeam/status-badge/master/example.svg)

## Query Parameters

| Parameter | Required | Value Type | Description |
|:----------|:--------:|:----------:|:------------|
| `server`  | **Yes**  | *<domain>* | The server to query. |
| `scv`     | **No**   | `true` or `false` | Add the stem cell versions. |
