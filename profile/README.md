<h1>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/ytw-logo-simple-mono-white-transparent.svg">
    <img src="assets/ytw-logo-simple-mono-black-transparent.svg" width="40" height="40" alt="Waytrine mark">
  </picture>
  Waytrine
</h1>

**Fine-tuned small models that make agent systems convenient, fast and cheap to run.**

**[wyt.si](https://wyt.si)** · **[PugPort](https://pugport.com)**, the production use case · **[yutong.wiki](https://yutong.wiki)**, the author

## Projects

### [Task Router](https://github.com/Waytrine/task-router)

A classifier and inference API that answers ten routing questions about a request to an AI agent system in one forward pass: what kind of task it is, how hard it is, and which tools it needs. It routes requests in production in [PugPort](https://pugport.com), a multi-agent desktop app.

**72.0% → 91.0%** on sealed real requests (v4 → v5) · **322M** parameters · **37 ms** median latency

[Case study](https://wyt.si/task-router/) · [API reference](https://wyt.si/task-router/api/) · [Model card](https://github.com/Waytrine/task-router/blob/main/MODEL_CARD.md)
