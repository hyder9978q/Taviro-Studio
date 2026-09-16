# Taviro Studio — Project Definition

## Objective

Build a low-cost, automation-first faceless media system that can repeatedly discover opportunities, research topics, produce useful short-form content, publish it across platforms, measure results, and improve its own content decisions.

## Business model

Start with audience and distribution validation. Monetization paths are evaluated from evidence, with affiliate revenue as an early candidate and additional products/services considered only after traction.

## Operating rule

The system must create content itself. Human involvement is limited to supervision, approvals where necessary, and strategic intervention.

## Content quality rule

Avoid generic AI filler. Prefer content grounded in real tools, experiments, comparisons, demonstrations, data, or verifiable sources.

## Initial workflow

1. Discover topics/tools/opportunities.
2. Gather evidence and record sources.
3. Score ideas against audience and business criteria.
4. Generate a structured content brief.
5. Generate script and production assets.
6. Assemble the video.
7. Run automated quality checks.
8. Queue and publish.
9. Collect platform metrics.
10. Feed results back into topic and format selection.

## Architecture direction

Use a modular monolith for the first implementation. Keep orchestration, research, content strategy, production, QA, publishing, analytics, and learning as replaceable modules.

## First validation target

Produce and publish a small controlled batch before expanding automation complexity. Every experiment should have a hypothesis, measurable outcome, and recorded result.
