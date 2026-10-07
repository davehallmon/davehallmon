<img src="assets/profile-banner.png" alt="OCCAMI NOVACULA" width="100%">

## AI cannot decide which problems should matter to us. That part stays human.

There is value in choosing a problem, struggling with it, seeing it from different angles, and working toward an answer.

That process is not something to automate. **It is one of the best ways we learn.**

**OCCAMI [NOVACULA](https://academic.oup.com/brain/article/145/6/1870/6575832) is a growing suite of AI Skills built to support that struggle.**

The Skills shared here do not solve our problems for us. They help us think differently about them.

We question assumptions. Change perspectives. Expose disagreements. Generate alternatives. Find a place to begin.

**But simplicity is only one lens.**

Sometimes we ask the wrong question. Sometimes we miss another perspective. Sometimes two reasonable ways of thinking lead to different places. Sometimes what matters most is the thing we have not thought to ask.

## Why [NOVACULA](https://doi.org/10.1093/brain/awac159)?

A razor can cut things away. A scribe's *novacula* did something more interesting: it made revision possible.

Medieval writers used scraping knives to remove mistakes from parchment and continue the work. A 2022 essay in *Brain* proposes this as another way to understand Ockham's razor: not as a call for simplicity, but as a tool for updating, amending, and evaluating ideas.

That interpretation fits OCCAMI.

The goal is not always to make a problem simpler. It is to question, revise, reframe, and improve how we are thinking about it.

**[Read the essay →](https://doi.org/10.1093/brain/awac159)**

## Skills

<table>
<tr>
<td width="42%" valign="top">
  <a href="https://github.com/davehallmon/reasoning-lens">
    <img src="assets/card-reasoning-lens.png" alt="reasoning-lens" width="100%">
  </a>
</td>
<td width="58%" valign="top">
  <h3><a href="https://github.com/davehallmon/reasoning-lens">reasoning-lens</a></h3>
  <p><strong>How should I think about this?</strong></p>
  <p>Seven philosophical methods examine one idea and surface the disagreements that matter.</p>
</td>
</tr>
<tr>
<td width="42%" valign="top">
  <a href="https://github.com/davehallmon/problem-lens">
    <img src="assets/card-problem-lens.png" alt="problem-lens" width="100%">
  </a>
</td>
<td width="58%" valign="top">
  <h3><a href="https://github.com/davehallmon/problem-lens">problem-lens</a></h3>
  <p><strong>What should I do about this?</strong></p>
  <p>Multiple problem-solving lenses generate ranked options and identify a place to begin.</p>
</td>
</tr>
</table>

### Planned

Not built yet, and the names may change. Each one has to pass the same test before it ships: **does it help you revise your thinking, or does it only tell you that you are wrong?** If it only does the second, it becomes a mode inside an existing Skill, not a new one.

<table>
<tr>
<td width="42%" valign="top">
  <img src="assets/card-evaluation-lens.png" alt="evaluation-lens" width="100%">
</td>
<td width="58%" valign="top">
  <h3>evaluation-lens</h3>
  <p><strong>How good is this draft, and how would I improve it?</strong></p>
  <p>Freezes your draft, scores it against a rubric built from your purpose, and hands you a revision roadmap before it changes a word.</p>
</td>
</tr>
<tr>
<td width="42%" valign="top">
  <img src="assets/card-bias-lens.png" alt="bias-lens" width="100%">
</td>
<td width="58%" valign="top">
  <h3>bias-lens</h3>
  <p><strong>What is steering my thinking?</strong></p>
  <p>Flags the biases a situation invites, and says plainly when it finds none.</p>
</td>
</tr>
<tr>
<td width="42%" valign="top">
  <img src="assets/card-model-lens.png" alt="model-lens" width="100%">
</td>
<td width="58%" valign="top">
  <h3>model-lens</h3>
  <p><strong>Which mental model fits, and where does it stop working?</strong></p>
  <p>Matches your situation to a mental model, labels what kind of claim it is (law, regularity, heuristic, metaphor), and warns when you stretch it too far.</p>
</td>
</tr>
<tr>
<td width="42%" valign="top">
  <img src="assets/card-expert-lens.png" alt="expert-lens" width="100%">
</td>
<td width="58%" valign="top">
  <h3>expert-lens</h3>
  <p><strong>How would experts who disagree argue this?</strong></p>
  <p>Three archetypes cross-examine one idea.</p>
</td>
</tr>
<tr>
<td width="42%" valign="top">
  <img src="assets/card-failure-lens.png" alt="failure-lens" width="100%">
</td>
<td width="58%" valign="top">
  <h3>failure-lens</h3>
  <p><strong>How might this fail?</strong></p>
  <p>Assumes the plan has already collapsed and traces the internal causes back to today's decisions.</p>
</td>
</tr>
<tr>
<td width="42%" valign="top">
  <img src="assets/card-fluency-lens.png" alt="fluency-lens" width="100%">
</td>
<td width="58%" valign="top">
  <h3>fluency-lens</h3>
  <p><strong>Is the way I work with AI ready for what comes next?</strong></p>
  <p>Audits an AI-assisted workflow against six Ds and sets a 30-day change.</p>
</td>
</tr>
<tr>
<td width="42%" valign="top">
  <img src="assets/card-other-minds-lens.png" alt="other-minds-lens" width="100%">
</td>
<td width="58%" valign="top">
  <h3>other-minds-lens</h3>
  <p><strong>How would someone with different incentives see this?</strong></p>
  <p>Reasons from another party's incentives, information, and constraints. Optional, and built last.</p>
</td>
</tr>
</table>

fluency-lens builds on the four Ds of the [AI Fluency Framework](https://aifluencyframework.org/) by Rick Dakan and Joseph Feller, developed with Anthropic: Delegation, Description, Discernment, and Diligence. It adds two: Data Decisions and Development.

### How the Skills fit together

You choose the problem. You use whichever lenses help, in any order, and you can return to the struggle as often as you need. No Skill decides for you. Dashed Skills are planned, not built.

```mermaid
flowchart LR
    Hub["OCCAMI NOVACULA<br/>Hub"]
    Choose["Choose<br/>your problem"]

    subgraph Struggle["Struggle: view it from many angles"]
        direction TB
        RL["reasoning-lens<br/>Think it through"]
        PL["problem-lens<br/>Find a first move"]
        EV["evaluation-lens<br/>Judge the draft"]
        BI["bias-lens<br/>Spot what steers you"]
        MO["model-lens<br/>Pick a mental model"]
        EX["expert-lens<br/>Hear experts disagree"]
        FA["failure-lens<br/>Imagine it failing"]
        FL["fluency-lens<br/>Audit your AI workflow"]
        OM["other-minds-lens<br/>Take their view"]
    end

    Revise["Revise<br/>your thinking"]
    Decide["You decide<br/>and act"]

    Hub --> Choose
    Choose --> Struggle
    Struggle --> Revise
    Revise -->|"Still unclear:<br/>try another lens"| Struggle
    Revise --> Decide

    classDef hub fill:#f94d13,stroke:#612815,stroke-width:2px,color:#ffffff
    classDef built fill:#f8f0e1,stroke:#f94d13,stroke-width:2px,color:#2a2422
    classDef planned fill:#fffdfa,stroke:#b29d8f,stroke-width:1px,color:#6d5a4e,stroke-dasharray: 5 5
    classDef human fill:#2a2422,stroke:#f94d13,stroke-width:2px,color:#ffffff

    class Hub hub
    class RL,PL built
    class EV,BI,MO,EX,FA,FL,OM planned
    class Choose,Revise,Decide human

    style Struggle fill:#fdeee6,stroke:#f94d13,stroke-width:2px,color:#2a2422
    linkStyle default stroke:#f94d13,stroke-width:2px
```

### What these Skills can't judge

A lens focuses, and it also narrows. Each published Skill says what its lens cannot see. None of them can judge taste: whether a design, a sentence, or an argument feels right. They can show what a draft does. What it should be stays with you.

## Building in public

A small snapshot of the work behind the ideas.

<picture>
  <img src="profile/stats.svg" alt="GitHub activity" width="100%">
</picture>

---

## Let's discover our unknown unknowns together.

Ideas, criticism, experiments, and contributions are welcome.

<img src="assets/footer.png" alt="OCCAMI NOVACULA" width="100%">
