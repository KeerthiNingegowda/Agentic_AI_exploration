# Agentic_AI_exploration
The goal of this exploration is to build a "true" agent - in this case specifically an onboarding agent with dynamic reasoning and tool use

# Distinction between workflows and agents 
<b> Workflow </b> The steps are pre-defined in order 
<b> Agents </b> Perceives a state, reasons what to do to next, uses tools, handles failures and adapts. Note that an agent doesn't operate by a checklist, it has a goal and will try to take steps to achieve that goal.

# Example agent - Onboarding agent
Managers spend a ton of time submitting a whole bunch of support tickets to onboard a new employee and post new emp joining they spend time manually checking which tools they have access to and submits more tickets to fill those gaps, leading to inefficient use of time.

In this example, we explore how can one build an onboarding agent to automate some of these tasks along with steps to implement Human In The Loop (HITL)

# Relevant research
1) Measuring agents in production - https://arxiv.org/abs/2512.04123; Learning from real-world agent deployments
2) Databricks State of AI Agents - https://www.databricks.com/resources/ebook/state-of-ai-agents 

# Architecture design
Tool of choice - Google ADK
