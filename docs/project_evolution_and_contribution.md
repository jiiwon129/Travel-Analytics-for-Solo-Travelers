# Project Evolution & Contribution

## How the project evolved

The project did not begin directly as a solo-travel route project.

### Initial idea

The earliest documented proposal focused on the question:

> How does regional transport infrastructure affect tourist spending?

The initial analysis plan included:

- constructing transport-infrastructure indicators,
- comparing regional transport accessibility with tourist spending,
- predicting spending with regression / machine-learning models,
- testing infrastructure-improvement scenarios,
- and translating the results into a travel-pass proposal.

### Target refinement

During team discussion, the target population and policy framing changed several times.

The project initially considered foreign tourists because they were assumed to rely more heavily on public transport. As the available data and analysis scope were reviewed, the final design moved toward **domestic solo travelers**, using the National Travel Survey.

The final structure became:

1. construct a regional transport-infrastructure index,
2. estimate private-car dependency among solo travelers,
3. predict regional travel spending,
4. simulate transport-infrastructure improvement,
5. identify transport-vulnerable regions,
6. propose linked tourism routes and transport-pass ideas.

## Individual Contribution — Kim Jiwon

The meeting materials support the following individual contributions.

### 1. Initial problem framing and project idea

Proposed the core analytical question linking **transport infrastructure and tourist spending**.

The proposal included:

- regional transport-infrastructure measurement,
- tourist-spending prediction,
- infrastructure-variable importance analysis,
- scenario testing such as improving transport access,
- and a travel-pass / policy recommendation layer.

This core structure remained in the final project even after the target population changed.

### 2. Motivation and research framing

Assigned to refine the motivation for why transport accessibility matters for tourism.

Research notes examined:

- regional transport-access inequality,
- possible consumption loss from poor accessibility,
- transport-information barriers,
- solo-travel growth,
- and why public-transport-dependent travelers are a useful target segment.

### 3. Demand-side transport indicators

Contributed to the **demand** component of the transport-infrastructure index.

Meeting notes explicitly assign:

- public-transport trip volume,
- per-capita public-transport usage

to Kim Jiwon.

These variables were later integrated with supply, accessibility, connectivity, and operational-efficiency indicators in the final transport-infrastructure index.

## Team-level work

The following components are presented in this repository as **team project outputs**, not as individual work by Kim Jiwon unless separately documented:

- final regression-based infrastructure-index weighting,
- private-car dependency extraction,
- XGBoost spending-prediction implementation,
- infrastructure-improvement scenario modeling,
- GIS route construction,
- final route and transport-pass design.

The repository keeps the complete team analysis flow while separating verified individual contribution from team results.
