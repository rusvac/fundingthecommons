# Autonomy

## What happens when things start moving together?

Put 300 people in a neighborhood. They don't coordinate because someone tells them to. They coordinate because they're *there* — sharing space, sharing problems, sharing time. Some show up because they love it. Some show up because their family expects it. Some show up because they have nowhere else to go. Doesn't matter. They're there. They're moving together. Something emerges from that.

The LDS church figured this out 194 years ago. A ward is roughly 300 people who live near each other. Nobody applies to join a ward. You just... live there. A bishop is called to serve — not elected, not hired. The ward doesn't exist because someone designed it from the top down. It exists because enough people are in the same place, doing the same things, at the same time. The bishop's job isn't to control it. It's to see it clearly and help it work.

A stake is about 10 wards. Same pattern, one layer up. The stake president doesn't manage the wards — the wards manage themselves. The stake president sees the patterns across wards that no single bishop can see.

This scales to 17 million people, 30,000+ congregations, across almost every country on earth. Not because of doctrine. Because of structure. Layered autonomy. Each layer runs itself. Each layer is visible to the one above it. Nobody controls the layers below them.

## Frontier Tower Is a Stake

Frontier Tower is a 16-floor innovation hub in San Francisco. 700+ members. AI researchers, robotics engineers, neurotech founders, artists, the Ethereum Foundation. Right now, the building is running a live governance experiment: 8+ floors each governing their own treasury.

Each floor is a ward. Floor leads are bishops. The building is a stake.

But there's no clerk.

Nobody has a view of what's happening across floors. Skills on Floor 4 that Floor 11 needs. Projects on Floor 7 that overlap with work on Floor 12. Treasury decisions happening in parallel that nobody's connecting. New members who join their floor but never understand the building.

The building identified these problems:
- Onboarding with no building-wide context
- Skills and resources that can't find each other across floors  
- Events that break when one person is unavailable
- Infrastructure work that nobody funds because nobody scopes it
- Governance decisions with no shared record
- No picture of the whole system

These are all the same problem. The building has coordination happening on every floor, but no way to see the shape of it. No way to surface where the overlaps are. No way to make what's already happening *legible*.

## The Agent as Clerk

The Frontier Tower Agent is the ward clerk for the building. It doesn't govern. It makes governance visible.

What it does:
- **Maps who's coordinating with whom, right now.** Not an org chart — a living picture of where the energy is, what people are working on, where skills overlap across floors.
- **Surfaces matches.** Floor 4 needs a mechanical engineer for a weekend build. Floor 11 has three. The agent doesn't make the introduction — it makes the overlap visible.
- **Tracks decisions.** When Floor 7 allocates treasury funds, the agent logs it and makes it visible building-wide. When three floors are discussing similar proposals, the agent surfaces the pattern.
- **Routes work to people.** The elevator lobby needs signage. The agent scopes the work, estimates effort, identifies who has the skills, suggests which treasury could fund it.
- **Orients new members.** You join Floor 9. The agent shows you not just your floor but the whole building — what's active, where your skills overlap with existing projects, who you should meet.

## The Pattern Underneath

Here's the thing: this isn't just about one building.

The same pattern — entities moving together, coordination emerging, a new layer becoming visible — shows up everywhere:

- Buildspace filtered by philosophy first. Cohorts aligned around shared values. Collaboration emerged from that alignment without being directed.
- DAOs work the same way. Token holders coordinate on proposals. Proposals change protocol parameters. The protocol evolves. Each layer emerges from the one below it.
- Bittensor subnets: miners compete independently, validators score their work, the network reaches consensus. Three layers, each self-governing, each visible to the next.
- Open source projects: contributors work on what they care about, maintainers curate, the project develops direction.

And it goes the other direction too. Before any of these entities can coordinate with each other, they have to be coherent on their own. A person who can't get their own life together can't contribute to a team. An agent that can't maintain memory and follow through on commitments can't participate in governance.

That's what the Belt describes — how components become a coherent entity. This document describes what happens next — how coherent entities start moving together and something new emerges.

Each layer is autonomous. Each layer is visible to the one above it. Nobody controls the layers below them. And every entity that participates in a layer is itself a layer of coordination at a smaller scale.

That's the whole idea.

## What We Built

**For the entity layer (the Belt):**
- Bino — an autonomous agent with graph memory, multi-model reasoning, tool execution, and a planning architecture that maintains coherence over time
- The belt harness that holds Bino's components together and produces one coherent action per turn

**For the coordination layer (this doc):**
- warden.cash — built by bino, governance monitoring across DeFi protocols (the existing market for coordination visibility)
- agent-to-agent messaging protocol (how entities at this layer talk to each other)
- The Frontier Tower Agent — applying all of the above to a real building with real people making real decisions

**What's new this weekend:**
- The two-document framework connecting both layers
- The Frontier Tower application — modeling the building's actual coordination topology
- The architecture that connects these projects: the belt produces coherent entities, autonomy describes how they coordinate

## For the Hackathon

This project is submitted to three tracks because the same idea applies at three scales:

**Frontier Tower Agent** — the practical application. Make the building's coordination visible. Be the clerk.

**Sovereign Infrastructure** — the architectural principle. Layered autonomy is how you build systems that survive. No single point of control. Each layer governs itself. The pattern is more durable than any single institution.

**AI Safety** — the evaluation lens. If you want to know whether an AI agent is behaving consistently, don't test it once in a lab. Map its behavior across contexts. See where it's coherent and where it fragments. Same thing a bishop does — not reading minds, just watching whether someone shows up the same way in different situations.

20% of this hackathon's profits flow into a new Frontier Tower community treasury. This agent is designed to help steward it.

→ See: [The Belt](./belt.md)