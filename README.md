# Agent-H: DeFi Security Auditing Agent

Agent Zero configured for DeFi protocol security testing and smart contract auditing.

## Setup
1. Container: `agent-h` running `agent0ai/agent-zero`
2. Port: `50001`
3. Data: `/workspaces/Agent-H/data` → `/a0/usr`

## Configuration
- `.env.example` - Template for API keys
- `config/` - Target protocol configurations
- `prompts/defi/` - Custom DeFi security agent prompts
- `tools/` - DeFi-specific tool definitions
- `evidence/` - Vulnerability findings and PoCs

## Next Steps
- [ ] Configure LLM API keys
- [ ] Create DeFi agent role prompts
- [ ] Set up blockchain analysis tools
- [ ] Define audit workflows
