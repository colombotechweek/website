# Colombo Tech Week

The city domain now redirects to [Curious Commons](https://curiouscommons.com/). GitHub Pages is disabled. This repository retains the historical city website and its source history for future use. It is not the live hosting origin.

```mermaid
flowchart LR
  Domain[City domain] --> Edge[Cloudflare redirect Worker]
  Edge --> Commons[curiouscommons.com]
  History[GitHub source history] -. retained reference .-> Domain
```

No dates or city programme are announced by this redirect.
