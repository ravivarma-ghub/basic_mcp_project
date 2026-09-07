# Weather MCP Server

This project is a simple **Model Context Protocol (MCP) server** built using Python.

It provides an AI assistant with a tool to fetch active weather alerts for a given US state using the **National Weather Service API**.

## Features

* Get active weather alerts for US states.
* Uses MCP tools to connect AI applications with external APIs.
* Uses `httpx` for asynchronous API requests.
* Includes a simple MCP resource example.

## Technologies Used

* Python
* MCP
* FastMCP
* httpx
* National Weather Service API

## Run the Project

```bash
uv run mcp dev server/weather.py:mcp
```

This project demonstrates how MCP can be used to connect AI models with external tools and real-world data.
