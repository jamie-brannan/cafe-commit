# project-cafe-commit-format

- [project-cafe-commit-format](#project-cafe-commit-format)
  - [Duration](#duration)
    - [...depending on capacity that day](#depending-on-capacity-that-day)
      - [The variables](#the-variables)
      - [Step 1: Fixed and scaling overhead](#step-1-fixed-and-scaling-overhead)
      - [Step 2: Blocks first, since they don't split up well](#step-2-blocks-first-since-they-dont-split-up-well)
      - [Step 3: Crit gets the rest and runs in parallel](#step-3-crit-gets-the-rest-and-runs-in-parallel)
      - [Worked examples](#worked-examples)
    - [Structure](#structure)
    - [Opening (5 min)](#opening-5-min)
    - [Round (10 min)](#round-10-min)
    - [Blocks (30 min)](#blocks-30-min)
    - [Break (5 min)](#break-5-min)
    - [Crit (30 min)](#crit-30-min)
    - [Closing (10 min)](#closing-10-min)


## Duration

General rule of thumb at 75 min maximum

### ...depending on capacity that day 

There's a workable formula for this. The trick is to treat some parts of the meeting as fixed, some as scaling with attendance, and to divide what's left between blocks and crit based on demand. Knowing the numbers in advance helps a lot, so a simple pre-meeting ask in your async channel works well: "Coming? Bringing a block, bringing work for crit, or just listening?"

#### The variables
N = attendees, B = people bringing a block, C = people bringing work for crit. Everyone else is a listener or reviewer, and they matter too, because crit needs reviewers.

#### Step 1: Fixed and scaling overhead

Opening, break, and wrap-up take about 10 minutes no matter the size. The opening round takes about 1 minute per person, and the closing takeaway about 30 seconds per person. These grow with N, so cap them. Past about 10 people, the round becomes "type your one-liner in the chat" and the facilitator reads a few aloud. That keeps overhead at no more than about 25 minutes.

Working time: W = 75 − overhead, usually 40–55 minutes.

#### Step 2: Blocks first, since they don't split up well

Blocks benefit from the whole group's attention, so they stay together. Budget about 8 minutes each: a few minutes talking, questions, then suggestions. Blocks time = B × 8, capped at half of W. If more blocks come in than fit, the rest are offered either a crit breakout room or first slot next session.

#### Step 3: Crit gets the rest and runs in parallel

Crit time = W − blocks time. Budget about 10 minutes per piece of work. If all C pieces fit in plenary (C × 10 ≤ crit time), keep everyone together, since it's more interesting to watch. If not, use breakout rooms: each room can handle (crit time ÷ 10) pieces, so rooms = C divided by that, rounded up. Spread the listeners across rooms so each has at least three people.

#### Worked examples

| N	| B	| C	| Overhead | Blocks | 	Crit |	Format |
|---|---|---|---|---|---|---|
| 6	| 1	| 2	| ~19 min	| 8 min	| ~48 min |	All plenary, generous time |
| 10| 	2| 	4| 	~25 min	| 16 min |	~34 min |	Plenary for crit (just fits 3; tight) or 2 rooms |
| 14| 	3| 	6| 	~25 (chat round) |	24 min | ~26 min | 	3 rooms of ~4–5, 2 pieces each |


### Structure

### Opening (5 min)

"Welcome to [group name]. I'm ___, and I'm facilitating today." Read the purpose statement. "Anyone new? Feel free to say hi and what you work on."

### Round (10 min)

"Quick round: name, what you're working on, and where you're stuck, whether that's a bug, a design problem, or just not being able to get started. Passing is fine."

### Blocks (30 min)

"First half is for blocks: the things that aren't straightforward code problems. Lost momentum, a project you can't face, not knowing what to build next, second-guessing your approach. The person sharing gets to talk it through first. Then we ask questions before offering suggestions."

### Break (5 min)

### Crit (30 min)

"Second half is crit. Bring code, a design, a bug, a half-finished idea. Feedback is direct and about the work. Say what's working, what's unclear, and one concrete suggestion." Reciprocity rule: if you bring something, you give feedback on someone else's.

### Closing (10 min)

"Quick round: one thing you're taking away or trying next." Then relevant announcements and confirming next session's roles.
