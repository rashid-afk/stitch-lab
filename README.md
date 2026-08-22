```
        ██╗   ██╗███████╗██╗██╗
        ██║   ██║██╔════╝██║██║
        ██║   ██║█████╗  ██║██║
        ╚██╗ ██╔╝██╔══╝  ██║██║
         ╚████╔╝ ███████╗██║███████╗
          ╚═══╝  ╚══════╝╚═╝╚══════╝

    ╌╌╌╌╌  S T I T C H   L A B  ╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌

         embroidery digitising that does
              the hard part itself
```

<div align="center">

### [→ &nbsp;Open it now &nbsp;·&nbsp; free &nbsp;·&nbsp; no signup&nbsp;](https://stitch.veildetail.co.uk)

**Made in the UK by [VEIL Detail Co.](https://stitch.veildetail.co.uk)** — because sometimes the software that
comes with an embroidery machine costs more than the machine...

</div>

```
· — · — · — · — · — · — · — · — · — · — · — · — · — · — · — · — · — · — ·
```

## What it does

Drop in a logo. Get a stitch file your machine can sew. **Nothing is uploaded
anywhere** — the whole thing runs on your own computer.

```
   ┌─────────────┐      ┌──────────────┐      ┌─────────────┐
   │   your.png  │ ───▶ │  STITCH LAB  │ ───▶ │  design.pes │
   └─────────────┘      └──────────────┘      └─────────────┘
                          ▲                          │
                     you fix whatever            straight to
                     it got wrong                 the machine
```

It reduces the colours, splits each one into separate shapes, measures how wide
every stroke is with a distance transform, and picks satin or fill per shape the
way a person would. Then it hands you the nodes so you can fix whatever it got
wrong — because auto-digitising that won't let you correct it is a toy.

```
· — · — · — · — · — · — · — · — · — · — · — · — · — · — · — · — · — · — ·
```

## Real digitised alphabets

Not TTF outlines converted to a fill. **Stitch skeletons** — a spine per stroke
with a designed satin column width, the way a hand-digitised alphabet is
actually built.

```
                    filled outline      satin skeleton
                    --------------      --------------

   at 25mm tall     ██████████████      ██████████████        both fine
   at 12mm tall     ▓▓▓▓▓▓▓▓▓▓▓▓        ████████████
   at  8mm tall     ▒▒▒░░ ░▒▒           ████████              ← still reads
   at  5mm tall     ░ ░  ░              ──────                ← drops to a run

   The outline knows where the edge is. It has no idea how wide a thread
   column should be — so it thins out. The skeleton carries that width
   as part of the design, which is why it survives.
```

Below about 6mm it drops to a single run stitch by itself — because satin that
narrow has nothing to bite on — and tells you why instead of quietly failing.

```
· — · — · — · — · — · — · — · — · — · — · — · — · — · — · — · — · — · — ·
```

## The toolkit

| | |
|---|---|
| **Auto-digitising** | Logo in, stitches out, nodes still editable |
| **Badge & patch maker** | Shield, banner, circle — with a proper raised merrow edge |
| **Appliqué** | Placement, stop, tackdown, stop, cover satin — sequenced right |
| **Monogramming** | Including the classic layout, surname larger and in the middle |
| **Freestanding lace** | Interlocking net at 60° with a heavy satin edge |
| **Cutwork** | Outline, reinforce, stop to cut, satin edge |
| **Photo stitching** | Stitch length modulated by luminance, in tonal bands |
| **Puffy foam 3D** | The raised lettering on fitted caps |
| **Colour blending** | Two threads interleaved by ordered dithering |
| **Cording & sequins** | For machines with the attachment — it tells you if yours hasn't |
| **Multi-hoop splitting** | Registration crosses on shared edges, plus a how-to-sew sheet |
| **Batch name-drop** | A list of names in, a zip of files out |

### A badge, in the order it sews

```
   Placement line   ····································   ▌ STOP — lay fabric
   Tackdown         ····································   ▌ STOP — trim it
   Edge underlay    ▂▂▂▂▂▂▂▂▂▂▂▂▂▂▂▂▂▂▂▂▂▂▂▂▂▂▂▂▂▂▂▂▂▂
   Merrow edge      ████████████████████████████████████
   Merrow edge  ×2  ████████████████████████████████████
   Cut line         ┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄
```

That double pass on a raised underlay is the whole difference between a patch
that looks bought and one that looks printed on.

```
· — · — · — · — · — · — · — · — · — · — · — · — · — · — · — · — · — · — ·
```

## Formats

| Format | Machines | Read | Write |
|---|---|:--:|:--:|
| **PES / PEC** | Brother, Baby Lock | ✅ | ✅ |
| **DST** | Tajima, and virtually every commercial machine | ✅ | ✅ |
| **EXP** | Melco, Bernina | ✅ | ✅ |
| **JEF** | Janome, Elna | ✅ | ✅ |
| **XXX** | Singer Futura | ✅ | — |
| **SEW** | Older Janome | ✅ | — |
| **VP3** | Husqvarna Viking, Pfaff | — | — |

Every file it writes is verified by **decoding the bytes back before it saves**,
so a corrupt file can't reach your machine.

Formats marked `—` for write aren't guessed at. A format writer that's 95% right
produces a file that looks perfect and fails on the machine — and *you'd* find
that out, not us. They get added when there's a real reference file to check
against, not before.

**It's honest about your machine, too.** Pick yours and the panel tells you what
it physically can't do — no sequin device, no cap frame — instead of letting you
sew a file that does nothing.

```
· — · — · — · — · — · — · — · — · — · — · — · — · — · — · — · — · — · — ·
```

## Getting it

```
   ┌───────────────────┬─────────────────────────────────────────────┐
   │  In your browser  │  Nothing to install. Works offline.         │
   │  Installed app    │  One click in Chrome or Edge. Recommended.  │
   │  Windows desktop  │  Finds your machine's USB drive itself.     │
   └───────────────────┴─────────────────────────────────────────────┘
```

Latest build: [**Releases**](../../releases) &nbsp;·&nbsp; or [install it from the site](https://stitch.veildetail.co.uk/download)

**Requirements** — Windows 10/11 64-bit, ~250 MB, 4 GB RAM, 1024×680 screen.
No installer: unzip and run. The browser version needs any current browser and
nothing else.

```
· — · — · — · — · — · — · — · — · — · — · — · — · — · — · — · — · — · — ·
```

## Pricing

Free covers lettering, shapes, every hoop size and unlimited exports. **That's
not a trial** — it just works, forever.

| | |
|---|---|
| **Free** | Lettering, shapes, all hoops, unlimited exports |
| **£19/mo** | Everything. 30-day free trial, cancel any time |
| **£149 once** | Pro. Yours permanently, works offline forever |
| **£499 once** | Factory. Multi-hoop splitting and production tooling |
| **£39** | Students, with a student card or .ac.uk email |

Course technicians: **departmental licences are free**. [Get in touch.](https://stitch.veildetail.co.uk/buy#contact)

> A one-off key never checks in with a server. If this project disappears
> tomorrow you keep working, and every file it has made is a standard format any
> other software can open.

```
· — · — · — · — · — · — · — · — · — · — · — · — · — · — · — · — · — · — ·
```

<div align="center">

**[stitch.veildetail.co.uk](https://stitch.veildetail.co.uk)** &nbsp;·&nbsp;
[Questions](https://stitch.veildetail.co.uk/buy#contact)

```
    ╌╌╌  V E I L   D E T A I L   C O .   ·   E S S E X  ╌╌╌
```

<sub>© VEIL Detail Co. This repository hosts the release builds and issues.<br>
The application source is not open source.</sub>

</div>
