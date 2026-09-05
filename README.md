> # Towards Collective Robotic Operating Systems through Aggregate Computing
> Angela Cortecchia
> ### ACSOS 2026 Ph.D. Symposium — 1-minute flash talk

## Abstract

Collective robotic systems are groups of heterogeneous devices that must act as a
single system while their environment, network, and mission conditions keep
changing. This research explores macro-programming as a way to express and manage
collective behavior above the level of the individual robot. Building on Aggregate
Computing, it develops reusable distributed mechanisms for formation, replanning,
consensus, collective sensing, and safety, and frames them as steps toward a
Collective Robotic Operating System: a runtime layer for composing and controlling
collective processes across dynamic robot teams.

## 60-second script

> Target: ~140 words, ~55 s spoken. One slide, no transitions.

Hi, I'm Angela Cortecchia, from the University of Bologna.

If you program one robot, you have ROS. If you have a hundred, you have a problem:
you want to say what the *swarm* should do, but the code runs on devices that move,
fail, and disappear.

So my PhD asks: what would an *operating system for the collective* look like?

I build it with Aggregate Computing. Everything moving on this slide is one service
of that system: robots growing a formation, replanning a mission when one of them
fails, agreeing on a value under faults, tracking targets together, and staying
collision-free while they adapt.

What's missing is making them run *together*: concurrent collective processes,
preemption, and safety during the transient.

That's what I'll present at the PhD Symposium — come and tell me where I'm wrong.

### Delivery notes

- **Beat 1 (0–8 s)** — name + affiliation. Look at the room, not the slide.
- **Beat 2 (8–22 s)** — the ROS contrast. This is the hook: pause after "you have a problem".
- **Beat 3 (22–28 s)** — the research question. Slow down on *operating system for the collective*.
- **Beat 4 (28–46 s)** — gesture once at the strip of GIFs, then list the five services at pace.
  Do not name papers or venues; the slide and the symposium talk carry that.
- **Beat 5 (46–55 s)** — the gap + invitation. End on the last line and stop talking.

### Contributions behind the five GIFs

| Slide label | Work | Venue |
|---|---|---|
| Formation | Aggregate vascular morphogenesis / FieldVMC | ACSOS 2024, Complex & Intelligent Systems 2026 |
| Replanning | Field-based runtime replanning in swarm missions | ACSOS 2025 |
| Consensus | Self-stabilizing min–max consensus via path–loop detection | COORDINATION 2026 |
| Sensing | Multi-target tracking via field-based distributed particle filtering | ACSOS 2026 (also DCOSS-IoT 2026) |
| Safety | Distributed control-theoretic safety filter for robot swarms | ACSOS 2026 Companion (SISSY) |

#### Resources

- (**suggested**) Online presentation: [https://angelacorte.github.io/phd-symposium-2026-flash-talk/](https://angelacorte.github.io/phd-symposium-2026-flash-talk/)
- PDF download: [https://github.com/angelacorte/phd-symposium-2026-flash-talk/releases/download/latest/poster.pdf](https://github.com/angelacorte/phd-symposium-2026-flash-talk/releases/download/latest/poster.pdf)
