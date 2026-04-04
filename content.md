# Solid26

## A stable foundation to build on

> **Note:** Solid26 is currently under development. The primer and some specification documents referenced here have not yet been put through the W3C Solid Community Group process. We are working to have this done by the end of April 2026.

### Goals of this document

This page works to capture and communicate the goals and planned contents of Solid26, based on discussions in W3C Solid Community Group calls — providing a written reference for what has so far been discussed verbally.

---

Solid26 is a planned collection of Solid specification versions (written as a new implementors guide), best practices, and documentation intended to give developers, organisations, and communities a stable target to build against. **This does not change or remove existing parts of the Solid Specification in any way**. Solid26 adds to the existing set of resources in the Solid Community, and is aims to make Solid more accessible. The current contents have been proposed by members of the [W3C Solid Community Group](https://www.w3.org/community/solid/), including the [Open Data Institute](https://theodi.org), and will be subject to the group's processes before release.

Whether you're a developer building your first Solid app, an enterprise evaluating the technology, or a researcher exploring new data architectures — Solid26 aims to be your starting point.

---

## What is Solid26?

Solid has been evolving since it was developed by Sir Tim Berners-Lee and his team at MIT. Decades of development has produced a rich set of specifications, tools, and community knowledge — but there is not yet a single, clearly defined collection that says: *this is ready to build on*.

Solid26 aims to change that. It proposes to bring together core Solid specification versions alongside new best practice documents, developer guidance, and sector-specific materials into one coherent collection. Think of it as a planned stable snapshot of the Solid platform — a known-good baseline that application developers and server implementers could target with confidence.

The name "Solid26" reflects the aspiration for Solid to adopt a rolling release model. Like modern browsers and platforms, the Solid ecosystem would continue to evolve — with annual collections that build on real-world feedback and adoption. Whether this model is adopted is subject to discussion within the W3C Solid Community Group.

---

## What's included

**Core specifications**

Solid26 proposes to collect fixed versions of the most critical and stable specification documents needed to build functional Solid servers and applications. The planned specifications include the [Solid Protocol](https://solidproject.org/TR/protocol) (v0.11.0), [Solid WebID Profile](https://solid.github.io/webid-profile/) (v1.0.0), [Solid-OIDC](https://solidproject.org/TR/oidc) (v0.1.0), and one of [Web Access Control (WAC)](https://solidproject.org/TR/wac) or [Access Control Policy (ACP)](https://solidproject.org/TR/acp) for access control (see [discussion thread](https://lists.w3.org/Archives/Public/public-solid/2026Mar/0019.html)) — alongside specifications for notifications, access requests, and client authentication for scripts. The included specifications and their versions are subject to confirmation through the W3C Solid Community Group process. The collection will clearly signpost where there may be breaking changes in future versions, so developers can plan accordingly.

Full technical details, including proposed version pinning and amendment notes, are available in the [Solid26 Primer](https://docs.google.com/document/d/1da2J-NsU3K-4kWEFOvhzIdrvy_KftewXdlxfu401kY0/edit) (draft).

**Best practice documents**

New guidance covering practical topics that developers and organisations need, including:
- How to organise data within a Solid Pod — including conventions for application-specific data namespacing and container structure
- How to store and share digital credentials (such as digital driving licences) using Verifiable Credentials
- How to record data provenance and usage controls — where data came from and what you're permitted to do with it — using PROV-O and ODRL

These best practices should be considered early-stage and are likely to mature into standalone specification documents in future releases.

**Developer tools and documentation**

A growing suite of open-source libraries, templates, and resources hosted at [dev.solidproject.org](https://dev.solidproject.org), including an RDF object mapping library, project templates for popular frameworks like Next.js, and SKILLS.md documents to support AI-assisted development with tools like GitHub Copilot and Claude Code.

**Sector-specific adoption packs**

Tailored materials for distinct communities — from enterprise and government to social good, research, and individual users — containing domain-relevant demos, ontology guidance, and onboarding resources.

**Non-technical materials**

UX demonstrations, explainers, and education materials designed to help non-technical audiences understand what Solid makes possible and why it matters.

---

## Who is Solid26 for?

**Developers** who want a clear, stable specification to build applications against — with documentation, tutorials, and tools that make it straightforward to get started.

**Organisations** exploring how Solid can support their data strategy — whether in financial services, healthcare, government, or other sectors — with adoption packs tailored to their domain.

**Researchers** investigating decentralised data architectures, personal AI, or privacy-preserving technologies, with a production-ready platform and an active academic community.

**The Solid community** — contributors, implementers, and advocates — who now have a shared reference point for collaboration, feedback, and growth.

---

## Relationship to Linked Web Storage

The [Linked Web Storage (LWS) W3C Working Group](https://www.w3.org/groups/wg/lws/) is currently developing a W3C specification with the Solid specification as one of its input documents. LWS is expected to define a subset of Solid's functionality as a formal W3C standard. Future Solid releases will align with and extend the LWS specification as it matures.

---

## Get involved

Solid26 is launching alongside **Solid Week** at the end of April 2026 — a series of events designed to bring the community together:

- **[Solid Hackathon](https://theodi.org/news-and-events/news/announcing-the-solid-symposium-2026/)** (April 27–29) — A hybrid international event with in-person participation in London, and remote nodes in Belgium, Australia, the United States, and beyond. Build with Solid26 and help shape the next generation of applications.
- **[Solid Symposium](https://sosy2026.eu/)** (April 30 – May 1) — An international conference dedicated to Solid, featuring talks from researchers, implementers, and organisations working across the ecosystem.
- **[Linked Web Storage Working Group](https://www.w3.org/groups/wg/lws/) focus meeting** (April 27–28) — An in-person meeting in London advancing the W3C specification work that underpins Solid's future.

Following the launch, sector-specific working groups will form to test Solid26 in their domains, gather feedback, and identify where the standard needs to go next. If you're interested in leading or joining a working group in your sector, [get in touch](mailto:solid+info@theodi.org).

---

## Help shape what comes next

Solid26 is the beginning, not the destination. We are actively tracking the [barriers to adoption](https://docs.google.com/spreadsheets/d/1F0_TRi3p2caS5oaktYjvnZy5jbElenkIBMkXNA3MCME/edit?gid=0#gid=0) that the community has identified, and feedback from developers, organisations, and working groups will feed directly into the Solid Community Group — informing priorities for the specification and tooling throughout 2026 and beyond.

The [Open Data Institute](https://theodi.org) [stewards the Solid Project](https://theodi.org/insights/projects/odi-and-solid-building-a-future-where-data-works-for-everyone/) and is coordinating the development of supporting materials for Solid26 in collaboration with the global Solid community. [Learn more about how the project is governed](/community) or [explore the developer documentation](https://dev.solidproject.org) to start building today.
