# The Story: Making 300 Badges for the TinkerSpace Carnival

How the 2025 TinkerSpace Carnival badge went from an EasyEDA file to 300 kits, built together with the community.

[← Back to README](README.md)

---

## 1. Design

The badge was designed in **EasyEDA**: a 40 × 40 mm board, two colour-cycling LEDs and a CR2032 coin cell. The circuit is as simple as it gets, so most of the design time went into the **artwork**:

- **Front:** the *Space Carnival* logotype and a line drawing of the space.
- **Back:** *"be kind. be curious."*, the MakerGram logo, a *Maker* name strip and *"Celebrating three years of TinkerSpace"*.

The schematic, layout and fabrication files are in [`hardware/`](hardware/).

## 2. Paper fit check

Before spending money on boards, we printed both sides of the PCB **1:1 on paper**. A coin cell placed on the printout let us confirm that:

- the overall board size felt right as a badge,
- the CR2032 and its holder fit inside the outline,
- the LEDs, the lanyard hole and the artwork didn't collide.

It's the cheapest prototype there is, and it catches the most expensive mistakes.

![1:1 paper printout of both sides with a coin cell placed on it](docs/story/01-paper-fit-check.jpg)

## 3. Rush order from Lion Circuits

With the size confirmed, we placed a **rush order for 300 PCBs** with [Lion Circuits](https://www.lioncircuits.com), an Indian PCB fab, so the boards would arrive in time for the Carnival.

| Delivery | Unboxing |
|---|---|
| ![Lion Circuits box being opened](docs/story/02-lion-circuits-delivery.jpg) | ![Vacuum-packed stacks of PCBs](docs/story/03-pcbs-unboxed.jpg) |

The boards arrived blue with white silkscreen, just as designed:

| Front | Back | Back, with the cell |
|---|---|---|
| ![Bare PCB front](docs/story/04-bare-pcb-front.jpg) | ![Bare PCB back](docs/story/05-bare-pcb-back.jpg) | ![PCB back with CR2032 holder and cell](docs/story/06-pcb-with-cell.jpg) |

The CR2032 coin cells were sourced in bulk alongside the boards:

<img src="docs/story/07-cr2032-cells.jpg" alt="Boxes and strips of CR2032 coin cells" width="360">

## 4. Kitting with the community, factory style

300 kits is a lot of tiny parts. Instead of packing them alone, we turned it into a **community build session** at TinkerSpace, set up like a small factory line:

1. **Briefing:** everyone gathered to go over the kit contents and how the line would run.
2. **Assembly line:** volunteers sat around the table, and **each person added one part to the kit**: a PCB, the LEDs, the coin-cell holder, a CR2032.
3. **Done:** each bag moved down the table, and what came off the end was a **complete kit**.

It was faster, it was more fun, and everyone who helped had a hand in every badge.

![Community briefing before the kitting session](docs/story/08-team-briefing.jpg)

<p align="center">
  <img src="docs/story/kitting-time-lapse.gif" alt="Time-lapse of the community kitting line" width="300"><br>
  <sub>Time-lapse of the kitting line: each person adds one part, and a complete kit comes out at the end. <a href="docs/story/kitting-time-lapse.mp4">Watch the full-quality MP4</a></sub>
</p>

| The line in action | Factory-style setup |
|---|---|
| ![Volunteers around the table packing kits](docs/story/09-kitting-line.jpg) | ![Wider view of the kitting tables](docs/story/10-kitting-line-wide.jpg) |

The result was a box full of ready-to-build kits. Each bag holds a PCB, two LEDs, the coin-cell holder, a CR2032 and an instruction card:

<p align="center"><img src="docs/story/14-finished-kits.jpg" alt="Box full of finished badge kits in zip bags" width="420"></p>

## 5. Assembling the badges at the Carnival

At the Carnival, people brought their kits to the soldering station and assembled their own badges: two LEDs on the front, the coin-cell holder on the back, a CR2032 in, and the badge lights up. For many it was their first time soldering.

<p align="center">
  <img src="docs/story/soldering-at-carnival.gif" alt="People assembling their badges at the Carnival soldering station" width="300"><br>
  <sub>Badge assembly at the Carnival soldering station (sped up). <a href="docs/story/soldering-at-carnival.mp4">Watch the full-quality MP4 with sound</a></sub>
</p>

| | | |
|---|---|---|
| ![Soldering a badge at the station](docs/story/11-soldering-1.jpg) | ![Soldering a badge with helping hands](docs/story/12-soldering-2.jpg) | ![Building a badge at the Carnival soldering table](docs/story/13-soldering-3.jpg) |

---

## Timeline at a glance

| Step | What happened |
|---|---|
| Design | Schematic and PCB in EasyEDA (Dec 2025) |
| Verify | 1:1 paper printout to check board, cell and holder size |
| Fabricate | Rush order of **300 PCBs** from Lion Circuits |
| Kit | Community, factory-style kitting line at TinkerSpace: 300 complete kits |
| Build | Attendees assembled their badges at the Carnival soldering station |

## Lessons for the next badge

- **Print it 1:1 first.** A paper printout and the real parts on top catch sizing mistakes for free.
- **Order early, or plan for a rush order.** Fab and shipping time is usually the tightest part of an event badge.
- **Make kitting a community event.** A one-part-per-person line is quick, and it gets more people involved in the badge.
- **Keep the circuit simple.** Two LEDs and a coin cell are easy for first-timers to solder and hard to get wrong.
