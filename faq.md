# ClawCode FAQ

Frequently asked questions about ClawCode — the desktop workspace for OpenClaw users.

## What is ClawCode?
ClawCode is a desktop app for macOS and Windows that wraps OpenClaw with a multi-project workspace. It adds a dashboard, planning tools, role-based agents, task management, and git actions on top of the OpenClaw CLI runtime.

## Do I need OpenClaw to use ClawCode?
Yes. OpenClaw is the underlying agent runtime. ClawCode is the desktop layer on top of it. You need OpenClaw installed and configured before using ClawCode.

## What model providers does ClawCode support?
ClawCode supports any model you have configured in OpenClaw — including GPT-4o, GPT-4.1, Claude, Gemini, and others. You bring your own API keys via OpenClaw. ClawCode does not require a separate model subscription.

## Is ClawCode an editor or IDE?
No. ClawCode is not a code editor. It is a multi-project operations layer. It works alongside your existing editor (VS Code, Cursor, etc.) and adds project management, agent orchestration, planning, and shipping tools.

## How is ClawCode different from just using OpenClaw in a terminal?
OpenClaw in a terminal is one agent, one project, one session. ClawCode gives you a dashboard for many projects at once, role-based agents per project, a planner, task list, workflow builder, agent loops, logs, and one-click git actions — all without switching terminals or folders.

## Can I run agents on multiple projects at the same time?
Yes. ClawCode supports parallel agent execution across projects. Each project has isolated agents and you can queue work and monitor all of them from the central dashboard.

## What are role-based agents?
Each project in ClawCode gets a set of specialized agents:
- **Planner** — breaks goals into plans and tasks
- **Coder** — writes and modifies code based on task instructions
- **UI Agent** — handles frontend, layout, and design work
- **Bug Fixer** — diagnoses and resolves errors

## What is the orchestration chat?
The orchestration chat is a central agent that can see all your projects and instruct any project agent. Instead of jumping into each project, you send one message and the orchestration agent delegates to the right place.

## What are agent loops?
Agent loops let you queue a set of tasks and have agents run through them automatically without manual re-prompting. Useful for long build sessions or batch work.

## What planning tools are built in?
- **Plan mode** — define direction, outcomes, and milestones
- **Workflow builder** — design repeatable step-by-step processes
- **Task list** — convert plans into executable tasks and assign to agents

## Does ClawCode have git built in?
Yes. You can stage, commit, and push directly from the dashboard without opening a terminal. A recent changes view shows diffs per project.

## What platforms does ClawCode run on?
- macOS (Apple Silicon)
- macOS (Intel)
- Windows

## How is ClawCode priced?
- Pro Monthly — full access, billed monthly
- Pro Yearly — full access, discounted annual billing
OpenClaw itself is free.

## Where can I download ClawCode?
[clawcode.app/download](https://clawcode.app/download)

## Where is the documentation?
[docs.clawcode.app](https://docs.clawcode.app)

## How do I get support?
Email clawcodeapp@gmail.com or submit a feature request at [clawcode.featurebase.app](https://clawcode.featurebase.app)
