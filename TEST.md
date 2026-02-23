# Time MCP Server Test File

This file is for testing the Time MCP Server functionality.

## Test Queries

Try asking GitHub Copilot Chat these questions to test the Time MCP Server:

### Basic Time Queries
- "What time is it in Tokyo right now?"
- "What's the current time in New York?"
- "Show me the current time in London"

### Timezone Conversions
- "Convert 3pm EST to Pacific Time"
- "What time will it be in Sydney when it's 9am in Los Angeles?"
- "Convert 14:30 UTC to Eastern Time"

### Multiple Timezone Queries
- "What time is it right now in Tokyo, London, and New York?"
- "Show me business hours (9am-5pm) in different timezones"

### Advanced Time Queries
- "If I have a meeting at 2pm PST, what time is that in GMT?"
- "What are the current times in all major crypto trading cities?"

## Expected MCP Tools Available

The Time MCP Server should provide these tools:
1. **get_current_time** - Get current time in any timezone
2. **convert_time** - Convert time between timezones

## Testing Instructions

1. Open this project in VS Code
2. Make sure the MCP extension is enabled
3. Start a GitHub Copilot Chat session
4. Ask any of the test queries above
5. Copilot should use the Time MCP Server to answer

## Troubleshooting

If the MCP server isn't working:
1. Check VS Code MCP server status in command palette
2. Verify `.vscode/mcp.json` configuration
3. Ensure virtual environment is properly activated
4. Check that dependencies are installed: `pip list | grep mcp`