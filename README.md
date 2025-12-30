# Xero MCP Server

<!-- mcp-name: io.github.asklokesh/xero-mcp-server -->

<div align="center">

# Xero Mcp Server

[![GitHub stars](https://img.shields.io/github/stars/LokiMCPUniverse/xero-mcp-server?style=social)](https://github.com/LokiMCPUniverse/xero-mcp-server/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/LokiMCPUniverse/xero-mcp-server?style=social)](https://github.com/LokiMCPUniverse/xero-mcp-server/network)
[![GitHub watchers](https://img.shields.io/github/watchers/LokiMCPUniverse/xero-mcp-server?style=social)](https://github.com/LokiMCPUniverse/xero-mcp-server/watchers)

[![License](https://img.shields.io/github/license/LokiMCPUniverse/xero-mcp-server?style=for-the-badge)](https://github.com/LokiMCPUniverse/xero-mcp-server/blob/main/LICENSE)
[![Issues](https://img.shields.io/github/issues/LokiMCPUniverse/xero-mcp-server?style=for-the-badge)](https://github.com/LokiMCPUniverse/xero-mcp-server/issues)
[![Pull Requests](https://img.shields.io/github/issues-pr/LokiMCPUniverse/xero-mcp-server?style=for-the-badge)](https://github.com/LokiMCPUniverse/xero-mcp-server/pulls)
[![Last Commit](https://img.shields.io/github/last-commit/LokiMCPUniverse/xero-mcp-server?style=for-the-badge)](https://github.com/LokiMCPUniverse/xero-mcp-server/commits)

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![MCP](https://img.shields.io/badge/Model_Context_Protocol-DC143C?style=for-the-badge)](https://modelcontextprotocol.io)

[![Commit Activity](https://img.shields.io/github/commit-activity/m/LokiMCPUniverse/xero-mcp-server?style=flat-square)](https://github.com/LokiMCPUniverse/xero-mcp-server/pulse)
[![Code Size](https://img.shields.io/github/languages/code-size/LokiMCPUniverse/xero-mcp-server?style=flat-square)](https://github.com/LokiMCPUniverse/xero-mcp-server)
[![Contributors](https://img.shields.io/github/contributors/LokiMCPUniverse/xero-mcp-server?style=flat-square)](https://github.com/LokiMCPUniverse/xero-mcp-server/graphs/contributors)

</div>

A Model Context Protocol (MCP) server for integrating Xero with GenAI applications.

## Overview

Cloud-based accounting software integration

## Features

- Comprehensive Xero API coverage
- Multiple authentication methods
- Enterprise-ready with rate limiting
- Full error handling and retry logic
- Async support for better performance

## Installation

```bash
pip install xero-mcp-server
```

Or install from source:

```bash
git clone https://github.com/asklokesh/xero-mcp-server.git
cd xero-mcp-server
pip install -e .
```

## Configuration

Create a `.env` file or set environment variables according to Xero API requirements.

## Quick Start

```python
from xero_mcp import XeroMCPServer

# Initialize the server
server = XeroMCPServer()

# Start the server
server.start()
```

## License

MIT License - see LICENSE file for details
