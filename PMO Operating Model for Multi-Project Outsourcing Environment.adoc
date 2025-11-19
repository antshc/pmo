= PMO Operating Model for Multi-Project Outsourcing Environment
Anton Shcherbyna

== 1. Context and Problem Overview
In an outsourcing company where developers and PMs work across 3+ projects, weekly planning often becomes chaotic:
* Developers are shared across multiple clients.
* PMs compete for the same developers.
* PMO becomes a bottleneck during planning.
* No unified view of real developer capacity.
* PMs rely on PMO to micromanage, instead of owning delivery.

Goal:
* Delegate maximum responsibility to PMs.
* Reduce context-switching.
* Improve predictability.
* Create a stable planning and delivery model.

== 2. Target Solution: Allocation-First Model
The key best practice is shifting from “developers report tasks to PMO weekly” to “PMs plan inside fixed allocations.”

=== Step 1: Monthly Capacity Allocation
Define each developer’s % allocation per project.

Example:

[cols="1,1,1,1,1",options="header"]
|===
| Developer | Project A | Project B | Project C | Notes
| Dev1 | 40% | 40% | 20% | Max 2 context switches/day
| Dev2 | 60% | 40% | —  | Lead Dev on Project A
| Dev3 | 30% | 30% | 40% | Junior, avoid critical path
|===

This allocation is updated monthly, not weekly.

=== Step 2: PM Weekly Planning Based on Allocations
Each PM:
* Receives fixed capacity (hours or %).
* Plans tasks to fill that capacity.
* Prioritizes within their own project.
* Cannot assign tasks outside their allocated share.

=== Step 3: Weekly Planning Meeting (PM-Owned)
PMs present:
* Weekly plan per developer
* Risk, priority, dependencies

Developers do **not** report tasks to PMO.  
PMO approves load distribution and resolves conflicts.

== 3. RACI Model for Clear Delegation
[cols="1,3",options="header"]
|===
| Role | Responsibility
| PMO | Allocate capacity, resolve conflicts, track health
| PM | Plan tasks weekly, ensure delivery, escalate blockers
| Developer | Execute tasks, report progress to PM
| CTO/Delivery Lead | Approve changes to allocation model
|===

== 4. Operational Best Practices

=== 4.1 Limit Context Switching
Rules:
* Max 2 projects/day per developer.
* Prefer 1 primary + 1 secondary.
* 3+ projects only across the week, not the day.

This significantly increases delivery throughput.

=== 4.2 Weekly Planning Template (PM Submission)
Each PM prepares a plan:

*Developer:* Anton S.  
*Project A (40%):* Feature X, Bug #112  
*Project B (40%):* API refactor  
*Project C (20%):* Support ticket #551  

PMO checks for:
* Fit into allocation
* Overcommitment
* Priority alignment

=== 4.3 Priority Rules for Conflict Resolution
If multiple PMs need the same developer, PMO uses:

1. Client priority  
2. Contractual deadlines  
3. Revenue impact  
4. Severity (e.g., blocks release?)  
5. Strategic importance  

Highest business value wins.

=== 4.4 PMO Dashboard
PMO tracks:
* Developer workload
* Capacity per project
* Risks & bottlenecks
* PM delivery performance
* Forecasted workload

Makes load distribution transparent.

== 5. PM Responsibility Increase
PMs are responsible for:
* Weekly planning
* Internal prioritization
* Backlog readiness
* Delivery commitments
* Client communication
* Risk and delay reporting

PMO no longer:
* Assigns specific tasks  
* Collects work status from developers  
* Helps PMs prioritize backlog  
* Re-plans developer week  

PMO focuses on governance and fairness.

== 6. Recommended Tools

=== Capacity Planning
* Jira Advanced Roadmaps
* Tempo Planner
* Float
* Toggl Plan
* ClickUp Workload
* Azure DevOps Capacity Planning

=== Weekly Planning & Tracking
* Jira Scrum/Sprints
* Trello weekly boards
* Notion planning blocks
* Monday.com workloads

=== PMO Dashboard
* Power BI
* Jira Dashboards
* Excel capacity matrix

== 7. Summary
* PMO controls allocation and governance.
* PMs own planning and delivery.
* Developers follow one unified plan per week.
* Context switching is minimized.
* Planning becomes predictable and scalable.

== 8. Optional Deliverables
Tell me which you want exported:
* Capacity matrix (Excel/Asciidoc)
* Weekly planning template
* RACI matrix
* PMO operating model 1-pager
* Developer workload matrix template
