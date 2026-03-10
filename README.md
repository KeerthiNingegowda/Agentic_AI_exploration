# Agentic_AI_exploration
The goal of this exploration is to build a "true" agent - in this case specifically an onboarding agent with dynamic reasoning and tool use

# Distinction between workflows and agents 

<b> Workflow </b> The steps are pre-defined in order <br >
<b> Agents </b> Perceives a state, reasons what to do to next, uses tools, handles failures and adapts. Note that an agent doesn't operate by a checklist, it has a goal and will try to take steps to achieve that goal.

# Example agent - Onboarding agent
Managers spend a ton of time submitting a whole bunch of support tickets to onboard a new employee and post new emp joining they spend time manually checking which tools they have access to and submits more tickets to fill those gaps, leading to inefficient use of time.

In this example, we explore how can one build an onboarding agent to automate some of these tasks along with steps to implement Human In The Loop (HITL)

# Relevant research
1) Measuring agents in production - https://arxiv.org/abs/2512.04123; Learning from real-world agent deployments
2) Databricks State of AI Agents - https://www.databricks.com/resources/ebook/state-of-ai-agents 

# Architecture design
Tool of choice - Google ADK

## Schematic diagram of Onboarding agent















# Evals 
1) As a starting point checkout this playbook created using Claude - <a href = "https://github.com/KeerthiNingegowda/Agentic_AI_exploration/blob/main/Evals/Lenny's_podcast_Evals_playbook_checklist_created_by_Claude.pdf"> Evals Playbook </a>
PS:- Personally we think this podcast falls short in cold start scenarios, i.e. where there are no real users yet in prod. Start by some member of your team to test it initially as opposed to just doing "vibe checks"
2) Evals are not unit tests - https://www.youtube.com/watch?v=L8OoYeDI_ls
