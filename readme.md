**[AI in Automation]**  
<br/>
This Repository contains all the learnings of my AI in Automation R&D. Along with this, it will also be containing any projects that I believe would make sense doing.  
<br />

> AI Terminologies:
- LLM: Large Language Model -> Tools/Service/System trained with huge sets of data.
- Agent: An Agent is a system or program that takes instructions from an LLM and performs real-world tasks using external tools. It acts as a helper that `"does"` things the LLM cannot do on it's own.
- MCP: Model Context Protocol

> Task Flow:
- User --> [Prompt] --> `LLM` --> `Agent` --> `MCP` --> [Action Execution]

> What is MCP?
- Model Context Protocol (MCP) is a framework that connects LLM(s) to real-world-tools (like browsers, databases, APIs).
- It allows LLM(s) to send commands to these tools and get results.
- Think of MCP as a bridge between the LLM and your computer/tools.
- `Example:` If you write a prompt in Chat GPT: "Write me a playwright-python automation code that will visit www.google.com and after successful navigation validate the URL", the LLM [Chat GPT] will only be able to write the code for you. In order to execute that code, you will be needing an Agent, who with the help of the MCP server will be running this LLM generated code.