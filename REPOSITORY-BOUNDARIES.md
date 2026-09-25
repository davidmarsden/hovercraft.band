# Repository Boundaries

This repository is the **public content/data home for hovercraft.band**.

It should contain material that is ready to appear publicly on the site, plus generated/exported site content where required by the Micro.blog workflow.

## What belongs here

- final public lyrics;
- approved album and track metadata;
- published essays and track notes;
- public archive pages;
- press copy and public biography;
- artwork references;
- public release information;
- Micro.blog-exported/generated site content where needed.

This repository represents **what Hovercraft publishes**.

## What does not belong here

- private release planning;
- unresolved rights discussions;
- source-confidence debates;
- private correspondence;
- working lyric transcriptions;
- unpublished archival interpretation;
- internal release checklists;
- theme/layout implementation that belongs in the theme repository.

Those belong in `davidmarsden/hovercraft-release-2026`.

## Relationship to the other repositories

### davidmarsden/hovercraft-release-2026
Private documentary and release-control repository.

That is the source of truth for:
- why a lyric or credit is considered canonical;
- provenance;
- reconstruction history;
- release decisions;
- unresolved issues.

Only approved material should be promoted from there into this repository.

### davidmarsden/hovercraft.band-theme
Presentation/theme repository.

It controls:
- layouts;
- CSS;
- JavaScript;
- components;
- Micro.blog/Hugo theme behaviour.

## Working flow

```
hovercraft-release-2026
        ↓ review / approve
hovercraft.band
        ↓ rendered by
hovercraft.band-theme
        ↓
hovercraft.band
```

## Rule of thumb

**hovercraft-release-2026 = what we know and why**  
**hovercraft.band = what we publish**  
**hovercraft.band-theme = how it looks and behaves**
