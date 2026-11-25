<a id="readme-top"></a>

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/gif-files/trinity-apps/1280x720,%2015fps/1280x720,%2015fps_white.gif">
  <img src="assets/gif-files/trinity-apps/1280x720,%2015fps/1280x720,%2015fps_black.gif" alt="TraLogFin: Track a Day, Log a Ticket, Find a Link" width="640">
</picture>

# TraLogFin

**Track a Day. Log a Ticket. Find a Link.**

Three office apps where every unclear rule leans toward the worker.

### **[Open the Apps](https://tralogfin.github.io/index.html)**

</div>

---

Uhm, hi. You've probably used an office tool that made a bad day worse. A timesheet that turned your overtime into a second job. A ticketing system that felt like writing a novel for an audience that doesn't exist. A company "links" spreadsheet nobody had updated since the person who made it left.

TraLogFin is the opposite of that. You open it, you do the thing, you get back to your life.

## Why It Exists

It started with a mistake we never wanted to repeat. While moderating several studios at a university, one of us accidentally deleted someone's ticket on a clunky system we didn't build. Nothing stopped it. Nothing let us undo it.

That burned one lesson in: **good software should protect people from the worst day they're having, not amplify it.**

Between us, we've worked across film production, education, government and the events industry, and the same gaps kept showing up everywhere. So did the same kind of manager. TraLogFin is the system we wish we'd had: cleaner flows, safer patterns, and rules that are on your side.

## The Three Apps

Each app asks you one question, and your answer decides where it opens.

| | App | It asks | What it does |
| :---: | --- | --- | --- |
| <img src="assets/svg-files/tralogfin-application/track-a-day/primary-medium.svg" width="48" alt=""> | **Track a Day** | What's your vocation? | Clock in, clock out, log overtime. Track time cleanly and let the totals speak. |
| <img src="assets/svg-files/tralogfin-application/log-a-ticket/primary-medium.svg" width="48" alt=""> | **Log a Ticket** | What's your position? | Quick capture, clear ownership, visible progress. Ticketing that feels like momentum, not admin. |
| <img src="assets/svg-files/tralogfin-application/find-a-link/primary-medium.svg" width="48" alt=""> | **Find a Link** | What's your occupation? | One place for every link a team actually uses: schedules, docs, dashboards. No more spelunking through bookmarks. |

And one more in front of them all: **Pick a Page** asks *who are you?*, and hands you a character to play.

## The One Rule

**When a rule is unclear, it leans toward the worker.** If two readings are both reasonable, the one that protects the employee or freelancer wins. Not 50/50. Fifty-one, forty-nine.

What that looks like in practice:

- **Promotions ask first.** Nobody gets a new title, or the workload that comes with it, without accepting it.
- **Silence is never free.** Overtime that nobody answers expires after six months. It becomes *ghost hours*: a permanent record on the worker, on the owner, and a quarter on every Head of Department who could have answered and didn't. Ignoring a request can never be cheaper than answering it.
- **The person with power carries the weight.** Managers pay in full for their mistakes; employees pay in part. The owner carries a share of every Manager's cost.
- **Unpaid months don't become debt.** If the company stops paying, everyone sees ads. That's the whole consequence. Nobody owes anything for the months they used.
- **Freelancers keep their freedom.** Work for as many companies as you like; your numbers are seen only by you and the owner.
- **The server's clock decides.** Time zones, wrong phone clocks and "I submitted it yesterday, honest" change nothing. The first action wins.

## The Maths Is the Manager

Log a Ticket pays in points, and **nobody's point is ever taken from somebody else.** Every point is *created* by work:

| Who | Earns |
| --- | ---: |
| The person who fixes it | **1** |
| The person who asked for the fix | **0.75** |
| The person who confirms it's really fixed | **0.125** |
| The owner, as profit | **0.125** |

So the owner's profit is a slice of everyone's earnings, and it can only grow when theirs grows. Exploitation still pays, but only while it pays the people being exploited. Past that point, it costs only the owner.

Junk tickets never win. Every point a deletion creates is matched by a ghost point on the person who deleted it. Everything is counted in eighths and stored as whole numbers, so nothing ever needs rounding and nothing ever drifts. Justice mathematics: it wastes the saboteur's time.

## Meet the Cast

TraLogFin is tested by 18 people in two rival, fully remote companies. Every one of them is a survival strategy under pressure: exploitation, rebellion, retreat, apathy or rigid order. We based them on the drama we lived through at a very toxic company, so if one of them reminds you of someone, that's not an accident.

They exist to break things. Every rule has at least one character trying to bend it.

- **Voidspire Systems,** owned by Jane Lester. Fast, loud and impressive from the outside. It raises money like breathing and burns people at the same rate.
- **Silverveil Logistics,** owned by Hammad Dean, with Tasneem Kemp on the night shift. Slower, quieter, easy to underestimate. Hammad used to put out Jane's fires before he left to build the company he wished he'd worked for.
- **Three freelancers** work for both. They're the bridge, the leak and the alibi, depending on who you ask.

<details>
<summary><strong>Voidspire's arc: a cult of one</strong> (from the four-week test)</summary>

<br>

**Act 1.** Jane is the only one who matters. She never clocks in, her overtime approves itself, and she answers nobody.

**Act 2.** The push pays. Voidspire out-tickets Silverveil 144 to 124. But every extra ticket paid its fixer and its sender first: Alaric ends the month on 44 points, Jane on 38.25. The cult earns its members more than its leader.

**Act 3.** Six months later, the overtime nobody answered expires. 68 hours of ghost hours, with Jane's name on every one of them, where everyone can see it.

**Act 4.** Jane pushes harder. Past what her two confirmers can handle, every lapse turns her profit into lost profit, while her people still get paid in full.

**Act 5.** Jane runs the numbers, because numbers are the only thing she trusts besides herself. The only way to grow her profit is to grow everyone's. So she appoints more Heads of Department, answers the overtime, and gives every proposal a yes or a no. Each step is pure self-interest, and each one is exactly what an ethical company would do.

*She never became good. The maths made good the only thing that pays.*

</details>

## Where It Stands

**Version 1 is live.** What you can open today is the front end: the pages, the cast and the toggles, on desktop, phone and tablet.

- [x] Desktop, phone and tablet layouts, each one scaled on purpose
- [x] The rules, the cast and the four-week test numbers for all three apps
- [x] The live site, published from a tagged release
- [ ] Accounts and saving, on the Express and MongoDB servers
- [ ] Log a Ticket, rebuilt from our original ticketing system
- [ ] Offline mode, so a dropped connection never loses a clock-in
- [ ] All ten colours on every component, with smooth fades between them

## How It's Made

[![React][React-badge]][React-url]
[![TypeScript][TypeScript-badge]][TypeScript-url]
[![Sass][Sass-badge]][Sass-url]
[![Webpack][Webpack-badge]][Webpack-url]
[![Node.js][Node-badge]][Node-url]
[![Express][Express-badge]][Express-url]
[![MongoDB][MongoDB-badge]][MongoDB-url]

Designed in Figma first, then built by hand, and every number in it is deliberate. Every component scales through three layouts (landscape, portrait and square), comes in ten colours with a dark and a light shade, and follows one pattern: once you can read one, you can read them all. Readability beats brevity, everywhere.

This repository holds only the live site. The source lives in two private repositories in the [TraLogFin organization](https://github.com/TraLogFin).

## Who Made It

TraLogFin belongs to two people, 50/50:

- **Tertius Roach:** design, front end and the rules. [GitHub](https://github.com/TertiusRoach) · [tertius.roach@outlook.com](mailto:tertius.roach@outlook.com)
- **Johann Schoeman:** back end, database and the mathematics. [GitHub](https://github.com/JohannSchoeman)

Want to see the source, hire us, or tell us which rule you'd break first? Get in touch.

## License

Proprietary. Copyright © 2026 Tertius Roach and Johann Schoeman, all rights reserved. You're welcome to look, click and play; please don't copy.

---

<div align="center">

_Good software should protect people from the worst day they're having, not amplify it._

**[Open the Apps](https://tralogfin.github.io/index.html)**

</div>

<!--| Badge links |-->

[React-badge]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://react.dev/
[TypeScript-badge]: https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white
[TypeScript-url]: https://www.typescriptlang.org/
[Sass-badge]: https://img.shields.io/badge/Sass-CC6699?style=for-the-badge&logo=sass&logoColor=white
[Sass-url]: https://sass-lang.com/
[Webpack-badge]: https://img.shields.io/badge/Webpack-8DD6F9?style=for-the-badge&logo=webpack&logoColor=black
[Webpack-url]: https://webpack.js.org/
[Node-badge]: https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white
[Node-url]: https://nodejs.org/
[Express-badge]: https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white
[Express-url]: https://expressjs.com/
[MongoDB-badge]: https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white
[MongoDB-url]: https://www.mongodb.com/
