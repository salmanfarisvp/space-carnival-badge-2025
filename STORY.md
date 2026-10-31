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

It's the cheapest prototype there is, and it catches the most expensive mistakes. The printout in the photo is stamped **9 December 2025**: we paper-checked the board that morning and placed the PCB order the same day.

![1:1 paper printout of both sides with a coin cell placed on it](docs/story/01-paper-fit-check.jpg)

## 3. Rush order from Lion Circuits

With the size confirmed, on **9 December 2025** we placed a **rush order for 255 PCBs** with [Lion Circuits](https://www.lioncircuits.com), an Indian PCB fab in Bengaluru, so the boards would arrive in time for the Carnival. We also called Lion Circuits and asked them to push it through as fast as possible, and they agreed. **Thank you, Lion Circuits!** They delivered **300 boards**.

It went right down to the wire. The package reached Kochi on **20 December 2025**, the **opening day of the Carnival**. Rather than wait for the courier to deliver it, we **went to the Blue Dart office in person** and collected it ourselves, so we had the boards in hand by **noon on day 1**. The PCBs were sponsored by **TinkerHub** (see [what it cost](#6-what-it-cost-and-who-sponsored-it)).

| Delivery | Unboxing |
|---|---|
| ![Lion Circuits box being opened](docs/story/02-lion-circuits-delivery.jpg) | ![Vacuum-packed stacks of PCBs](docs/story/03-pcbs-unboxed.jpg) |

The boards arrived blue with white silkscreen, just as designed:

| Front | Back | Back, with the cell |
|---|---|---|
| ![Bare PCB front](docs/story/04-bare-pcb-front.jpg) | ![Bare PCB back](docs/story/05-bare-pcb-back.jpg) | ![PCB back with CR2032 holder and cell](docs/story/06-pcb-with-cell.jpg) |

The parts were sponsored by **MakerGram**: CR2032 cells from RX Electronics, Kochi, coin-cell holders from FlyRobo, and LEDs from New Digital Electronics, a local electronics shop in Nilambur. Here are the CR2032 cells:

<img src="docs/story/07-cr2032-cells.jpg" alt="Boxes and strips of CR2032 coin cells" width="520">

## 4. Kitting with the community, factory style

With the boards in hand at noon, there was no time to lose. That **same afternoon**, on day 1 of the Carnival, we packed the kits together with **makers from the Carnival**. 300 kits is a lot of tiny parts, so instead of packing them alone, we turned it into a **community build session** at TinkerSpace, set up like a small factory line:

1. **Briefing:** everyone gathered to go over the kit contents and how the line would run.
2. **Assembly line:** volunteers sat around the table, and **each person added one part to the kit**: a PCB, the LEDs, the coin-cell holder, a CR2032.
3. **Done:** each bag moved down the table, and what came off the end was a **complete kit**.

It was faster, it was more fun, and everyone who helped had a hand in every badge. **A big thanks to all the makers who jumped in on day 1 and made it happen.**

![Community briefing before the kitting session](docs/story/08-team-briefing.jpg)

<p align="center">
  <img src="docs/story/kitting-time-lapse.gif" alt="Time-lapse of the community kitting line" width="300"><br>
  <sub>Time-lapse of the kitting line: each person adds one part, and a complete kit comes out at the end. <a href="docs/story/kitting-time-lapse.mp4">Watch the full-quality MP4</a></sub>
</p>

The result was a box full of ready-to-build kits. Each bag holds a PCB, two LEDs, the coin-cell holder, a CR2032 and an instruction card:

<p align="center"><img src="docs/story/14-finished-kits.jpg" alt="Box full of finished badge kits in zip bags" width="420"></p>

## 5. Assembling the badges at the Carnival

The [Space Carnival](https://tinkerhub.org/events/SIE69TMDOS/space-carnival) ran on **20–21 December 2025** (9 AM–6 PM) at TinkerSpace.

- **Day 1, night: test run.** We held a test soldering session as part of the **Intro to Hardware** session, to try out the kit and the build steps with real people before opening it up to everyone.
- **Day 2, morning: open soldering station.** We set up a soldering station at the front of the space. **Anyone could walk in, solder a badge and take their kit home.**

At the station, people assembled their own badges: two LEDs on the front, the coin-cell holder on the back, a CR2032 in, and the badge lights up. For many it was their first time soldering.

<p align="center">
  <img src="docs/story/soldering-at-carnival.gif" alt="People assembling their badges at the Carnival soldering station" width="300"><br>
  <sub>Badge assembly at the Carnival soldering station (sped up). <a href="docs/story/soldering-at-carnival.mp4">Watch the full-quality MP4 with sound</a></sub>
</p>

| | | |
|---|---|---|
| ![Soldering a badge at the station](docs/story/11-soldering-1.jpg) | ![Soldering a badge with helping hands](docs/story/12-soldering-2.jpg) | ![Building a badge at the Carnival soldering table](docs/story/13-soldering-3.jpg) |

### Your badge is your Maker certificate

On the back of the badge there's a blank **"Maker"** strip, and it's there on purpose.

A lot of people made their **first-ever solder joint** on this badge: school and college students, and community members from completely different fields who had never held a soldering iron before. We wanted to acknowledge that moment. Once you've soldered your badge, you're **officially a Maker**, and the badge is your certificate. That's why there's a space to write your name on it.

### Open and hackable

There's no "right" way to build it. The design puts the LEDs on the front, but we saw people solder them on the **other side**, at different angles, or however they liked, and that's absolutely fine. The badge is about creativity and making it your own, so it's **open and hackable** by design.

### Why there's no off switch

You'll notice there's no power switch. Here's the official reason. 😄

The coin cell sits right behind the **TinkerSpace** artwork, so TinkerSpace is the **powerhouse**. The two LEDs are the **people and their ideas**. The space and the community power them, and that power is never meant to be switched off. **TinkerSpace and its community are always on.**

<sub>(It's definitely, absolutely *not* because a switch would have blown the budget. 😉)</sub>

---

## 6. What it cost, and who sponsored it

The **PCBs were sponsored by [TinkerHub](https://tinkerhub.org)**, and the **components were sponsored by [MakerGram](https://makergram.com)**.

### PCBs: Lion Circuits (sponsored by TinkerHub)

We ordered **255 boards** as a rush order, and Lion Circuits delivered **300**.

| Item | Qty | Rate (₹) | Amount (₹) |
|---|---:|---:|---:|
| PCB fabrication (*TinkerSpace-SpaceCarnival-Badge-v01*) | 255 | 28.23 | 7,197.89 |
| Fabrication NRE charges | 1 | 2,200.00 | 2,200.00 |
| Outward shipping | 1 | 593.22 | 593.22 |
| **Subtotal** | | | **9,991.11** |
| IGST 18% | | | 1,798.40 |
| Rounding | | | 0.49 |
| **Total** | | | **₹11,790.00** |

### Components (sponsored by MakerGram)

| Part | Source | Qty | Rate (₹) | Amount (₹) |
|---|---|---:|---:|---:|
| CR2032 coin cell | RX Electronics, Kochi | 300 | 5.80 | 1,740.00 |
| CR2032/CR2025 coin-cell holder | [FlyRobo](https://www.flyrobo.in) | 300 | 3.04 | 912.00 |
| 5 mm colour-cycling RGB LED | New Digital Electronics, Nilambur (local shop) | 600 | 2.00 | 1,200.00 |
| **Total** | | | | **₹3,852.00** |

### Totals

| | Amount (₹) |
|---|---:|
| PCBs (TinkerHub) | 11,790.00 |
| Components (MakerGram) | 3,852.00 |
| **Grand total** | **₹15,642.00** |

That works out to about **₹39 per board** (₹11,790 over the 300 boards delivered) plus **₹12.84 in parts per badge** (cell ₹5.80, holder ₹3.04, 2 × LED ₹2). That's roughly **₹52 per badge**.

---

## Timeline at a glance

| Step | What happened |
|---|---|
| Design | Schematic and PCB in EasyEDA (early Dec 2025) |
| Verify | **9 Dec 2025**: 1:1 paper printout to check board, cell and holder size |
| Order | **9 Dec 2025**: rush order of 255 PCBs placed with Lion Circuits |
| Delivery | **20 Dec 2025, noon** (Carnival day 1): **300 boards** collected in person from the Blue Dart office |
| Kit | **20 Dec, afternoon**: 300 kits packed on a factory-style line with makers from the Carnival |
| Test | **20 Dec, night**: test soldering session during the *Intro to Hardware* session |
| Build | **21 Dec, from morning**: walk-in soldering station at the front of the space; anyone could solder a badge |
| Cost | ₹15,642 in total: PCBs ₹11,790 (TinkerHub), parts ₹3,852 (MakerGram) |

---

## Lessons learned

The schedule was tight, so the top priority was simple: **get the badge designed, fabricated and into people's hands in time for the Carnival.** That meant some things we would normally do got left out.

### What worked

- **Print it 1:1 first.** A paper printout with the real parts on top catches sizing mistakes for free.
- **Make kitting a community event.** A one-part-per-person line is quick, and it gets more people involved in the badge.
- **Keep the circuit simple.** Two LEDs and a coin cell are easy for first-timers to solder and hard to get wrong.

### What we missed, and would do next time

- **No power switch.** The community is always on ([see why](#why-theres-no-off-switch) 😄), but practically, once a cell is in, the LEDs run until the battery drains, and the only way to turn the badge off is to pop the cell out. A small slide switch or a tactile button would be a nice addition in the next revision.
- **No panelization.** The boards were ordered as single 40 × 40 mm pieces. Panelizing them, with several badges per panel joined by V-cuts or mouse-bites, would have lowered the per-board cost and made kitting and handling faster.
- **Plan earlier.** The boards arrived at noon on the opening day, and that only worked because Lion Circuits rushed the order and we collected the package from Blue Dart ourselves. Ordering earlier would have avoided the stress and left time for a proper prototype round before the full run.

---

## Thank you

A huge thank you to the **TinkerSpace community members** who helped and motivated this project. Everyone was super supportive throughout the whole process, from the first paper printout and the kitting line to the soldering table at the Carnival.

Thanks as well to **TinkerHub** for sponsoring the PCBs, **MakerGram** for sponsoring the components, **Lion Circuits** for agreeing to rush the order, and all the **makers at the Carnival** who packed 300 kits on day 1 afternoon.

> I'm so proud and happy every time I see someone wearing the badge and using it. 💙
> — Salman Faris
