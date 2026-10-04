# Awesome-Work-Management

# Top Work Management Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Task Collaboration, Project Planning & Team Productivity*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Work Management**. These tools help teams plan projects, assign tasks, track progress, and collaborate across departments — from simple kanban boards to full enterprise portfolio management.

**Examples** include Microsoft Planner, Monday.com, Asana, Trello, ClickUp, Smartsheet, Wrike, Airtable, Notion, and Jira Work Management (the category leaders).

**Open-source emphasis**: Work management is one of the strongest open-source domains. **OpenProject**, **Plane**, **Focalboard**, **Vikunja**, and **Wekan** power project teams worldwide, with **OpenProject** recently adding XWiki integration and Jira migration tooling to position itself as a full proprietary replacement . This section is heavily expanded.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Microsoft Planner](https://www.microsoft.com/microsoft-365/business/task-management-software)**  
  Task management integrated with Microsoft 365 and Teams. Simple kanban boards, task assignments, and progress tracking with deep Outlook and SharePoint integration.

- **[Monday.com](https://monday.com/)**  
  Work OS platform with customizable boards, automations, and dashboards. Popular for marketing, operations, and project teams seeking visual workflow management.

- **[Asana](https://asana.com/)**  
  Project management platform with list, board, timeline, and calendar views. Strong for cross-functional collaboration and goal tracking (OKRs).

- **[Trello](https://trello.com/)**  
  Kanban-based task management with simple cards and lists. Free tier generous; popular for personal and small-team organization.

- **[ClickUp](https://clickup.com/)**  
  All-in-one productivity platform combining tasks, docs, goals, chat, and whiteboards. Aggressive free tier and feature breadth.

- **[Smartsheet](https://www.smartsheet.com/)**  
  Spreadsheet-based work management with Gantt charts, automations, and enterprise governance. Strong for PMO and operations teams.

- **[Wrike](https://www.wrike.com/)**  
  Enterprise work management with project portfolios, resource management, and proofing. Strong for marketing and professional services.

- **[Airtable](https://airtable.com/)**  
  Flexible database-spreadsheet hybrid for building custom workflows and tracking. Popular for content calendars, CRM, and project trackers.

- **[Notion](https://www.notion.so/)**  
  All-in-one workspace combining notes, databases, kanban, and wikis. Popular for startups and small teams.

- **[Jira Work Management](https://www.atlassian.com/software/jira/work-management)**  
  Atlassian's business team offering with list, board, timeline, and calendar views. Bridges the gap between Jira Software and general work management.

## Open-Source GitHub Projects

- **[OpenProject](https://github.com/opf/openproject)**  
  The leading open-source project management suite with 14.7K+ GitHub stars and AGPLv3 license . Full-featured with tasks (Work Packages), Gantt charts, Agile boards (Scrum/Kanban), meetings, time tracking, cost management, and documentation . Recent 17.6/17.9 releases add **XWiki integration** (wiki tab in Work Packages), **sprint goals**, **backlog buckets**, **task creation from documents**, deadline warnings in Community Edition, and **parallel Jira migration** with resumable imports . Docker deployment recommended; enterprise edition adds support and advanced features .

- **[Plane](https://github.com/makeplane/plane)**  
  Modern open-source alternative to Jira, Linear, Monday, and ClickUp with 47.8K+ GitHub stars and AGPLv3 license . AI-native project management with Work Items (tasks, bugs, features), Cycles (sprints with burn-down charts), Modules (grouping related work), Pages (wiki with AI), and five view layouts (List, Board, Spreadsheet, Gantt, Calendar) . Integrations with GitHub, GitLab, Slack, Sentry; importers from Jira, Linear, Asana, ClickUp, Monday . Deployable via Docker AIO container on Railway or self-hosted .

- **[Focalboard](https://github.com/mattermost-community/focalboard)**  
  Open-source, self-hosted alternative to Trello, Notion, and Asana with MIT/AGPL/Apache licenses . Kanban boards, table views, and gallery views for individuals and teams. Maintained by Mattermost community .

- **[Wekan](https://github.com/wekan/wekan)**  
  Open-source Trello-like kanban board with MIT license . Real-time collaboration, swimlanes, and card dependencies.

- **[Leantime](https://github.com/Leantime/leantime)**  
  PHP-based project management designed for non-project managers with accessibility features for ADHD, autism, and dyslexia, 10.2K GitHub stars and AGPL-3.0 license . Kanban, Gantt, calendar, and table views with goal tracking, wikis, and Slack/Mattermost integrations . LDAP/OIDC authentication, S3 storage, REST API, 20+ languages .

- **[Vikunja](https://github.com/go-vikunja/vikunja)**  
  Open-source task management with hierarchical structure, smart recurring tasks, and Telegram integration . To-do app for organizing life and work with list/table/gantt views.

- **[Kanboard](https://github.com/kanboard/kanboard)**  
  Simple visual task board with MIT license . Minimalist kanban with drag-and-drop, swimlanes, and plugin ecosystem.

- **[4ga Boards](https://github.com/RARgames/4gaBoards)**  
  Straightforward real-time kanban boards with elegant dark mode, collapsible todo lists, and multitasking tools, MIT license . Node.js/Docker/K8S deployment.

- **[Orangescrum Community Edition](https://github.com/Orangescrum/opensource-community-edition)**  
  Free self-hosted project management with GNU AGPL v3, no seat limit, no paid tier . Released August 2026 with CakePHP 4, PHP 8.2+, PostgreSQL 16 . Projects, tasks, subtasks, list/Kanban/calendar/overview views, custom task statuses, checklists, milestones, time logging, comments, mentions, labels, saved search filters, task reminders, roles/permissions, personal dashboards, file attachments, 2FA, REST API . **Not included**: Scrum/sprints, Gantt charts, resource management, timesheets, budget/cost, invoicing, defect tracking, test cases, document management, wiki, risk management, AI chat, MCP server, SSO .

- **[Paca](https://github.com/Paca-AI/paca)**  
  AI-native project management platform with MCP server for connecting AI agents directly to workspace data . Available tools: projects, tasks, sprints, documents, members, roles, task types/statuses, views, custom fields, attachments, activity/comments . Claude Code skills for managing workspace via natural-language slash commands . Docker deployment with PostgreSQL, Valkey .

- **[WorkBase](https://github.com/vocso-com/WorkBase)**  
  Local-first desktop project manager (offline Trello alternative) with unlimited nesting (project → module → task → subtask), weighted progress rollup, four views (Board, Kanban, Outline, Projects home), My Work across all projects, 15 templates, dependencies with blocked-state propagation, full-text search, export to PNG/PDF/Markdown/CSV/JSON . Tauri-based (Rust + Node) for macOS and Windows; local-only storage, no accounts .

- **[Project Manager (Boisti13)](https://github.com/Boisti13/project-manager)**  
  Self-hosted task manager with FastAPI + React + PostgreSQL . Projects, categories, subtasks, list/board/calendar/timeline (Gantt) views, recurring tasks, estimates, templates, weekly review, calendar feed, @mentions, notifications, archive, share read-only link, REST API . Proxmox LXC one-command install, offline Windows/Linux app .

- **[Redmine](https://github.com/redmine/redmine)**  
  Classic open-source issue tracking and project management with Gantt charts, calendars, wikis, forums, and role-based access . Mature ecosystem with hundreds of plugins.

- **[Taiga](https://github.com/kaleidos-ventures/taiga)**  
  Agile project management for Scrum and Kanban teams with backlog management, sprint planning, and kanban boards .

### Additional Strong Open-Source Options

- **epicd** — Markdown-native task manager and kanban visualizer for any Git repository, MIT licensed, AI-ready with MCP support for Claude Code, Gemini CLI, Codex .
- **Jotter** — Local-first privacy-focused task management stored as Markdown files, Kanban/list/Eisenhower Matrix views, git sync, Android app, MCP support .
- **AppFlowy** — Open-source Notion alternative with to-do lists, kanban, and databases, AGPL-3.0 licensed .
- **Donetick** — Task and chore management for personal/family use with scheduling, assignment, and group sharing, Go-based .
- **Nullboard** — Single-page minimalist kanban board, BSD-2-Clause licensed, compact and highly readable .
- **Taskwarrior** — Command-line TODO list manager, flexible, fast, and unobtrusive .
- **Vikunja** — Hierarchical task management with smart recurring tasks and Telegram integration .
- **Mimrai** — Lightweight open-source task management (early stage), AGPL-3.0 for non-commercial use .

**Frameworks for building custom work management solutions**: Combine **OpenProject** for full-featured project management with Gantt, Agile, and wiki integration . Use **Plane** for modern AI-native issue tracking with cycles and modules . Deploy **Focalboard** or **Wekan** for lightweight Trello-style kanban. Choose **Leantime** for accessibility-focused teams or those seeking Trello simplicity with Jira features . Use **Orangescrum Community Edition** for self-hosted teams wanting core PM without proprietary licensing . Integrate **Paca** for AI-agent-driven project management with MCP . Note that true enterprise work management with resource management, portfolio planning, and compliance certifications remains primarily commercial territory; open-source stacks provide strong task, project, and collaboration foundations that require integration for complete enterprise deployment.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Work management tools handle sensitive project and organizational data. Self-hosted solutions require proper security hardening, access controls, and backup procedures.
- Open-source work management platforms vary significantly in maturity. Evaluate gaps in enterprise features (resource management, portfolio planning, SLA tracking, SSO) before deployment. Orangescrum Community Edition explicitly excludes Scrum, Gantt, timesheets, budget, and document management .
- The open-source ecosystem provides strong task, project, and collaboration foundations, but enterprise support, compliance certifications, and managed SLAs remain primarily commercial offerings.

---

**Made for project managers, team leads, operations professionals, and organizations seeking work management sovereignty.**  
Let's make work management more open, transparent, and efficient.
