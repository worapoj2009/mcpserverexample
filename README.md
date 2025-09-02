"# mcpserverexample" 

add the following commands to your client:

'''
 json
{
  "mcpServers": {
    "calculator-tool": {
      "command": "uvx",
      "args": [
        "--from",
        "git+https://github.com/worapoj2009/mcpserverexample.git",
        "mcp-server"
      ]},
    }
}

'''