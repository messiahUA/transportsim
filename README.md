> **🚧 Experimental LLM project — early development.** Not yet playable. No release date or guarantees. No source code for now.

# TransportSim

**A simulation-first transport management game where you build and operate networks in a living, evolving world.**

Build roads, railways, and transport services. Connect people, businesses, and industries. Watch settlements grow, economies evolve, and entire region transform in response to your decisions.

The ambition is to combine the depth of a serious transport simulation with modern 3D construction tools, intuitive gameplay, and a world governed by believable rules rather than arbitrary game mechanics.

## Why am I building this?

I've loved transport management games since discovering *Transport Tycoon* in the late 1990s.

Games like *OpenTTD*, *Simutrans Extended*, *Transport Fever*, *Railroad Tycoon*, *SimCity*, and *Workers & Resources: Soviet Republic* have all influenced what I'd love to see in a transport game.

Each does certain things exceptionally well, but I've always wanted something that combines deeper, more believable simulation with modern construction tools and an approachable interface.

Building such a game alone would normally be an unrealistic undertaking. **Modern LLMs made me curious enough to try anyway.**

TransportSim is fully AI-coded, with the vision, design decisions, testing, and development direction guided by me.

It's a hobby experiment, not a commercial project. I'm interested in discovering how far this approach can go, and whether a complex, coherent simulation can emerge from it.

## The vision

TransportSim puts you in charge of a private transport company operating in a fictional country. You build infrastructure, manage services, balance finances, and respond to an economy that has a life of its own.

The guiding idea is that **good decisions in the game should resemble good decisions in the real world**.

### What makes it interesting?

- **📐 True 1:1 scale** — One meter is one meter; one simulated second is one second. Distances, speeds, journey times, and infrastructure geometry follow consistent real-world units, with no stretched maps or compressed distances. To play through decades, the calendar can run faster than the real-time clock: you choose how many days of economy each simulated day stands for, and the speed controls go up to as fast as your machine can manage.
- **🧑‍🤝‍🧑 Individual citizens** — People have homes, jobs, needs, and preferences, and each vehicle on the road carries one citizen: no representative or weighted traffic. Their decisions generate transport demand instead of relying on arbitrary passenger counts.
- **🏙️ Living world** — Towns and industries develop in response to accessibility, population, economic opportunities, and other conditions. You influence their growth through transport.
- **🏭 Interconnected economy** — Businesses, employment, production, consumption, and logistics are intended to form a coherent economic system that responds to changing circumstances.
- **🚂 Meaningful transport management** — Plan infrastructure, operate vehicles and services, manage schedules, fares, maintenance, and finances. Decisions have costs and long-term consequences.
- **🛤️ Modern 3D construction** — Flexible roads, railways, bridges, tunnels, curves, and gradients, with simple low-poly visuals and a focus on usability.
- **📅 Two centuries of progress** — An intended timeline spanning roughly 1850–2050, with evolving technology, infrastructure, and economic conditions.

These are the project's design ambitions, not a list of completed features.

## Simulation first, but still a game

Reality is far too complicated to reproduce. The goal isn't perfect realism, but **plausibility**: systems that behave consistently, interact meaningfully, and produce understandable consequences.

Ideally, the player should always be able to ask *"Why did this happen?"* and find an answer.

At the same time, TransportSim should be enjoyable to play, not merely interesting to observe. Financial constraints, progression, challenges, and the possibility of failure are just as important as simulation depth.

A few deliberate choices:

- **Single-player**, to prioritize simulation complexity and performance.
- **Performance-conscious**, targeting ordinary modern PCs rather than high-end hardware.
- **Data-driven and moddable**, with extensibility as a long-term goal.
- **Simple, procedural low-poly graphics**, prioritizing gameplay over visuals.

## Development & community

Development is at a very early, experimental stage. Initial simulation systems are being implemented and tested, particularly around citizens, economic behavior, road simulation, and performance.

**There is no playable release yet, and the source code is currently private.** I might make it available for non-commercial collaboration in the future.

This repository is a public home for the project, where I'll share development updates, experiments, screenshots, and interesting design questions as things progress.

**Interested in transport simulations, economics, or game design?**

Visit [Discussions](../../discussions) to follow development, exchange ideas, or share feedback.

*There is no promise this will ever become a finished game. For now, I'm simply enjoying the challenge of trying to build it.*