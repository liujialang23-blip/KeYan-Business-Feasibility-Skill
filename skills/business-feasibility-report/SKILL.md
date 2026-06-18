---
name: business-feasibility-report
description: "Use when creating commercial feasibility reports, business landing analysis, 可行性报告, 可研报告, 项目研判, 园区/门店/商业空间定位, 新产品/服务商业化, 新业态申报, 招商决策, MVP验证, 投资立项, or any task that needs market/customer insight, location and traffic analysis, hard-condition checks, business model, compliance, risk, staged roadmap, and decision recommendations."
---

# 商业落地可行性报告 Skill

## Overview

Use this skill to turn a project idea, product, service, park, store, commercial space, new scenario, or investment opportunity into a decision-ready feasibility report. The output must help the user decide what to do now, what to verify first, and what should be delayed or rejected.

## Core Rules

- Lead with decisions: state the综合判断, decision boundary, and recommended path before detailed analysis.
- Separate evidence from inference: label facts as已确认,初步判断, or需复核.
- For physical-location projects, always include周边配套设施统计,交通便利情况统计, and at least one map or schematic.
- Do not invent precise financial, legal, policy, traffic, or distance data. Use ranges, assumptions, and复核事项 when data is incomplete.
- Output可立即推进,谨慎推进,暂缓推进 recommendations in every full report.
- If current policies, maps, market data, or legal rules affect the answer, verify with source-backed research and cite sources in the report.

## Resource Selection

Load only the resources needed for the request:

| Need | Read |
|---|---|
| Full method or complex report | `references/methodology.md` |
| Choose report outline | `references/report-structure.md` |
| Hard checks, location, traffic, compliance, risks | `references/feasibility-checklists.md` |
| Maps, surrounding facilities, transportation visuals | `references/map-visualization.md` |
| Need reusable analysis prompts | `references/prompt-patterns.md` |
| Final polish and review | `references/quality-standards.md` |
| User asks for a complete Markdown template | `assets/full-report-template.md` |

## Workflow

1. Define the assignment.
   - Identify project type, location dependence, target reader, decision stage, report length, and available materials.
   - If the user gave enough information, proceed. If a missing item changes feasibility materially, ask one concise question or state the assumption.

2. Build the evidence ledger.
   - Sort inputs into user-provided facts, public/source-backed facts, analytical assumptions, and items requiring现场复核 or专业复核.
   - State report boundaries early.

3. Analyze demand and users.
   - For products and services, identify 3-4 user/customer groups and the core paying user.
   - Use痛点/痒点/爽点 to turn demand into product or operating opportunities.
   - Extend insight into market need, payment ability, acquisition path, competitive substitutes, and validation metrics.

4. Analyze location and landing conditions.
   - For parks, stores, venues, spaces, cultural tourism, and offline service projects, produce a standalone区位与交通 section.
   - Count surrounding facilities and traffic nodes. Include maps or schematics per `references/map-visualization.md`.
   - Check消防、电力、荷载、排水、停车、动线、证照、网络、设备、供应链、团队, and other hard conditions relevant to the project.

5. Compare feasible options.
   - Provide 2-4 direction options when the path is not obvious.
   - Compare market attractiveness, fit with resources, investment intensity, operating complexity, compliance risk, payback uncertainty, and staged feasibility.

6. Build the business and operating model.
   - Identify revenue sources, cost categories, required resources, operating mechanism, key partners, and measurable indicators.
   - Use scenario ranges when numbers are uncertain.

7. Review policy, compliance, and risk.
   - List permits, filings, safety requirements, data/content rules, food/lodging/training/event requirements, or industry-specific constraints.
   - Build a risk table with level, impact, and controls.

8. Give staged execution.
   - Use 0-30 days, 1-3 months, 3-6 months, 6-12 months, and 12-24 months when appropriate.
   - Attach decision gates and metrics for each phase.

9. Finalize the report.
   - Use the relevant outline from `references/report-structure.md`.
   - End with可立即推进,谨慎推进,暂缓推进,资料补充清单, and下一步行动.
   - Run the quality checklist in `references/quality-standards.md` before delivering.

## Map Requirement For Physical Locations

For any physical project such as a park, store, campus, mall, venue, hotel, cultural tourism site, or community service space:

- Include at least one visual map or schematic showing project location, surrounding facilities, and traffic convenience.
- When precise coordinates and public map data are available, use a real map base or source-backed point map.
- When data is incomplete, use a directional schematic, distance-ring diagram, or traffic relationship diagram and label it as示意.
- Every map must state data source, measurement口径, and items requiring navigation or site verification.

## Deliverable Modes

| User asks for | Output |
|---|---|
| 快速判断 | 1-2 page decision memo with assumptions and next checks |
| 完整报告 | Full structured feasibility report with tables and maps |
| 园区/门店/空间 | Full report plus location, traffic, facilities, hard-condition and map modules |
| 产品/服务 | Customer insight, MVP path, business model, market and risk modules |
| 政策/申报前置 | Policy fit, compliance boundary, evidence list, indicators and materials |

## Final Checks

Before responding:

- Are facts, assumptions, and复核事项 separated?
- Does a physical-location report include周边配套统计,交通便利统计, and map visualization?
- Are there clear可立即推进,谨慎推进,暂缓推进 recommendations?
- Are risks specific enough to control?
- Is the report commercial but not overpromising?
