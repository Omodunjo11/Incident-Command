# Incident Command

> Coordination overhead compounds outages. This removes it.

**Live demo:** [incident-command-ebon.vercel.app](https://incident-command-ebon.vercel.app)  
**Portfolio:** [lapoodunjo.com/projects/incident-command](https://lapoodunjo.com/projects/incident-command)

## The problem

During live incidents, the biggest time-waster isn't fixing the problem — it's figuring out who knows what and who owns what action. Unclear ownership, duplicated work, and decisions that aren't logged anywhere extend outages beyond the technical fix.

## What this is

An opinionated incident management interface built from real post-mortem findings — not a generic project management tool adapted to emergencies.

- Single-screen command view: who owns what, what's been tried, current status
- Decision logging with timestamp and owner on every key call
- Explicit action ownership — no "I thought you were handling that"
- Zero navigation overhead: built for stressed engineers under time pressure

## Why opinionated

Generic PM tools offer too much optionality during incidents. Incident Command has one view, one way to log a decision, one way to assign an action. That rigidity is the feature.

## Stack

HTML · JavaScript · Vanilla (no build step — ready when you need it)

## Outcome

Built from 14 post-mortems, validated in tabletop incident simulations with an engineering team.
