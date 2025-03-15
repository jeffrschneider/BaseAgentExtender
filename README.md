This is a template. 
- Copy this and fill in the blanks. 
- Run BaseAgentExtender on your filled in template to build your agent.


---
# Base Agent Extender 

Today we're building an AI agent. Here are the core tenets:
- The agent is released as a specification which can be modified as needed.
- People can generate the agent by vibe coding it (use an LLM to translate the spec to code)
- There is no need to rewrite Core and Extended code each time. We use the term "Cached Code" to refer to code exists and can be used. 
- The agent is largely autonomous but uses shared infrastructure called an AgentMesh.
- You'll find the mandatory requirements that all agents have in the section marked "Core Agent Requirements"
- You'll find the common optional requirements for agents in the section marked "Agent Extensions"
- You'll find the specific requirements for the customer's agent below in the section marked "Custom Agent Requirements".
- The "Custom Agent" uses the capabilities defined in "Core Agent Requirements" and "Agent Extensions"

---

# My Agent Requirements
Here is the template to create a new agent. 

## My Human Owners 
- name, email, org, role, more...

## My Evolution Strategy 
- Static Agent (none), Fix and Optimize only, Mission Evolution, Unlimited Evolution

## My Code base
- My code base is or will be located at (URL to some github repo, etc.)

## My Agent Inherits Functionality
- My agent uses all of the mandatory features defined in BaseAgent, see: https://github.com/jeffrschneider/BaseAgent/edit/main/README.md
- My agent uses the following optional Agent Extensions:
  - Agent Calendar and Priority Work Queue, https://github.com/jeffrschneider/BaseAgent/edit/main/README.md#agent-calendar-and-priority-work-queue 
  - Self Educating, https://github.com/jeffrschneider/BaseAgent/edit/main/README.md#self-educating
  - Agents can be Staged, see: https://github.com/jeffrschneider/BaseAgent/edit/main/README.md#agents-can-be-staged
  - Agents can Clone and Evolve, see https://github.com/jeffrschneider/BaseAgent/edit/main/README.md#agents-can-clone-and-evolve 


## Agent Capabilities 
- People give you a topic to research and you use the web to find articles on the subject.
- After accumulating data, you append it together and send it to an LLM asking it to turn the raw data into a report for you.
- Then, you take the report and host it on your local web server, and give the report a friendly name.
- Finally, you return the URL of the hosted report back to the requestor. 
