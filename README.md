# A Weather MCP server
A weather MCP server to provide AI Agents with weather alerts and forecasts from the US weather service

A fork of [A Simple MCP Weather Server written in Python](https://github.com/modelcontextprotocol/quickstart-resources/tree/main/weather-server-python)

Follow the guide [Build an MCP server](https://modelcontextprotocol.io/docs/develop/build-server)

## How to run

### Clone the repository
TBC


### Run the server
The server takes 2 env `MCP_SERVER_HOST` and `MCP_SERVER_PORT` to control the host and port bindings. 

The default values are as follows
```bash
export MCP_SERVER_HOST=127.0.0.1
export MCP_SERVER_PORT=8080
```

To expose the server to external services on port `5555`, run with the following commands
```bash
MCP_SERVER_HOST=0.0.0.0 MCP_SERVER_PORT=5555 python weather.py
```
