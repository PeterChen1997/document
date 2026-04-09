# 2026-04-09 · Brainstorming and Runbook

## Part 1. Product Brainstorming

### 1. The real problem is not saving information
The real problem is that saved information rarely turns into judgment, memory, or output.

Common failure chain:
- discover content
- feel it might be useful
- save it
- never return
- or return later but cannot quickly judge value
- or finish reading but fail to extract anything reusable

### 2. Better wedge: judgment before deep reading
Do not start from a full reading product.
Start from a smaller and more painful question:
- should I read this now?
- what is this piece mainly trying to say?
- what is fact vs assumption vs subjective stance?
- is the argument one-sided?
- what is the fastest way to decide whether this deserves 5 more minutes?

### 3. A practical product ladder
#### Step A. Article Judgment Extension
Input:
- current webpage
- selected text
- user-triggered action

Output:
- worth reading or not
- main claim
- stance
- evidence quality
- fact / assumption / opinion separation
- strongest counterpoint

Why this wedge works:
- small scope
- close to your strongest surface: web
- naturally embedded in behavior
- easier compliance boundary
- easier to test repeatedly on yourself

#### Step B. Reading Companion
After judgment works, extend to:
- section-by-section reading map
- contradiction / weak evidence hints
- summary optimized for output, not just compression
- save reusable insight cards

#### Step C. Understanding-to-Output Workflow
Only later consider:
- turning notes into writing seeds
- topic comparison across articles
- argument synthesis
- long-term knowledge organization

### 4. Product modules worth building eventually
- extraction module
- structure detection module
- claim classifier
- fact / assumption / opinion classifier
- stance detector
- counter-argument generator
- output card generator
- lightweight feedback loop

### 5. What not to do in v1
- do not build a giant read-it-later platform
- do not solve every input source at once
- do not start from sync-heavy knowledge management
- do not over-design accounts, teams, or billing first
- do not try to replace Cubox, Obsidian, or Readwise end to end

### 6. Best first user
The best early user is probably not the mass market.
Best v1 user profile:
- reads lots of web content
- saves too many things
- needs quick judgment
- cares about argument quality
- wants help converting reading into decision or output

This can include:
- builders
- product people
- researchers
- content creators
- intellectually curious heavy readers

### 7. Key product risks
- the pain may be real but not frequent enough
- users may say they want deep analysis but only use quick triage
- quality has to feel trustworthy very quickly
- the extension may become slow or noisy
- compliance boundaries must stay conservative

## Part 2. How the system should run

### 1. Operating layers
This system should run in four layers.

#### Layer A. Canonical thinking layer
Use Notion as the living strategy page.
Store:
- current direction
- decisions
- open questions
- next priorities

#### Layer B. Durable documentation layer
Use GitHub as the durable written record.
Store:
- long-form docs
- brainstorm notes
- runbooks
- architecture notes
- product thinking snapshots

#### Layer C. Execution layer
Use Linear for actionable work.
Store:
- small tasks
- sequencing
- priorities
- progress state
- execution notes

#### Layer D. Conversation layer
Use this chat as the place for:
- brainstorming
- synthesis
- reframing
- decision support
- task generation

### 2. Per-conversation persistence workflow
After each meaningful conversation:
1. identify new decisions, insights, and changes
2. update Notion summary page
3. add or update GitHub doc if the content deserves durable prose
4. create or refine Linear tasks if something becomes executable
5. return a short sync summary with links or identifiers

### 3. Weekly rhythm
#### Once per week
- review all open issues in Linear
- close outdated ones
- merge duplicates
- pick 1 work-track priority
- pick 1 personal-track priority
- pick 1 expression / feedback priority

#### Every two weeks
- review whether the chosen personal product direction still feels like the best wedge
- review whether the work-track exploration is producing reusable insight
- update the Notion top section with any directional changes

#### Once per month
- write one synthesis note
- update public positioning if needed
- review whether the system is too heavy

### 4. Small-task rule
A task is good if it can usually be done in 15 to 90 minutes.
If not, split again.

Good tasks:
- write 3 hero title options
- list 10 failure modes
- define 3 MVP outputs
- map one day of information intake

Bad tasks:
- build the whole product
- redesign the whole blog
- define the whole AI testing platform

### 5. Priority rule
At any moment, only keep:
- 1 current work-track task cluster
- 1 current personal product task cluster
- 1 current brand / expression task cluster

This prevents the system from collapsing into 20 parallel ambitions.

### 6. Decision rule for new ideas
When a new idea appears, do not promote it directly into a project.
Pass it through this filter:
- is it aligned with the main theme?
- is it painful enough?
- is it frequent enough?
- can it be tested cheaply?
- does it strengthen your existing narrative?

If three or more answers are weak, keep it in notes, not in active execution.

### 7. Suggested immediate next sequence
- finish positioning sentence
- finish work-track boundary note
- finish daily information intake map
- finish product pain hypotheses
- finish browser extension MVP boundary
- only then decide whether to prototype

## Part 3. Working philosophy

The system should not optimize for completeness.
It should optimize for momentum, clarity, and compounding.

You do not need a perfect second brain.
You need a system that helps you repeatedly:
- think clearly
- choose narrowly
- ship small
- learn quickly
- write publicly
- update direction without losing history
