# 🛰️ StructureIQ Xnode

The **StructureIQ Xnode** is a wireless sensor node built for continuous monitoring of real-world infrastructure — bridges, buildings, and other large structures.

I led end-to-end hardware development for this node as **Lead Hardware Engineer** at StructureIQ.

This repo isn't a schematic dump or a design archive — the product is active StructureIQ IP. It's a quick look at the board I designed, and a write-up of what the node achieves and what owning the hardware function on this team was like.

---

## 🎯 What it achieves

- **Highly capable sensing on real infrastructure.** The node captures meaningful, high-fidelity signals from a physical structure, so engineers and asset owners can see how the structure is actually behaving over time — not just whether it is "still standing."
- **Built for long, unattended field deployments.** Designed around the realities of infrastructure monitoring: hard-to-reach mounting locations, no wall power, real environmental conditions, and a service life measured in years rather than weeks.
- **Wireless reporting at scale.** Many nodes can be deployed across a single asset and report back without per-sensor cabling, so coverage is not bottlenecked by what you can physically wire up.
- **Early warning, not just postmortem.** Catches the early signs of degradation while there is still time to plan and act, instead of after damage has already accumulated.
- **Designed for the people deploying it.** The form factor, connectors, and indicators are built so a field tech, not just an EE, can install and validate one in the field.

---

## 🧑‍🔧 What it was like to work on

I was the sole hardware owner for this product. That meant being responsible for the whole hardware function: making the architectural calls, doing the schematic and multi-layer PCB layout, choosing parts, working with suppliers, bringing the boards up, and debugging them when they didn't behave the way I expected.

It was the kind of role where there was no senior EE above me to defer to. So I had to learn fast — read datasheets carefully, sanity-check my own assumptions on the bench, and solve problems methodically rather than guessing. It taught me to think in failure modes: not just "does this work right now," but "how is this going to fail later, and under what conditions."

---

## 🖼️ The board

### 🟢 3D render
![Xnode 3D render](xnode_3d_render.png)

### 🔴 PCB layout
![Xnode PCB layout](xnode_layout.png)

---

*Renders are from KiCad. The product itself, including the underlying schematic, BOM, firmware, and sensing approach, remains proprietary to StructureIQ.*
