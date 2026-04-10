```bash
claude \
  --dangerously-skip-permissions \
  --output-format=stream-json \
  --verbose \
  -p "Read the source code of https://github.com/NousResearch/hermes-agent, especially the run_agent.py and tools/skill_manager_tool.py.
  
  Implement the similar self-improving feature based on Claude Code's hooks and skills ability.
  
  Use bun with TypeScript to implement the skill_manager_tool."
```