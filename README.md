Install this MCP server by adding the following JSON code to your JSON config file
'''
{
    "mcpChessServer": {
      "command": "uvx",
      "args": [
        "--from",
        "git+https://github.com/kiransy015/chess-mcpserver.git",
        "chess"
      ]
    }
}
'''