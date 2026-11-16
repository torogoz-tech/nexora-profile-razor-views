# Nexora Razor Views analysis profile

This repository independently maintains the declarative Nexora profile for Razor Views (`razor_views`). It recognizes the documented view/template subset without executing markup or embedded C#.

`language.yaml`, `lexer.yaml`, `grammar.yaml`, and `graph.yaml` are the profile contract. Fixtures and limitation notes are the evidence for support. Validate with `nexora-api` `0.1.0`. Profile version: `0.1.0`.

## Architecture and stewardship

Nexora's architecture and the independent profile model are led by [Abner Velasco](https://www.linkedin.com/in/abnervelasco/), who is also responsible for the ongoing maintenance and evolution of this profile repository. Profile changes remain independently versioned, tested, and reviewed.

MIT. See `LICENSE`.
