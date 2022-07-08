# ADRs

<p>
  <a href="https://jpandres.github.io/adrs/">
    <img src="https://img.shields.io/badge/ADRs-6-ff69b4" alt="Number of Architectural Decision Records in this repo" />
  </a>
</p>

To try out ADR tools and generating a page to share with broader audience.


## Howto

1. Install `adr-tools2` in your mac (https://github.com/jpandres/adr-tools2)
2. Create ADR structure in your project 
   `adr init`
3. Add a badge in your README.md like the one on top in this one. It will automatically get updated every time you run `adr new` (edit the link to your repo)
4. Setup github action to use [`adr-viewer`](https://github.com/mrwilson/adr-viewer) and deploy generated HTML page to github pages.


ADRs sample from this project: https://jpandres.github.io/adrs/


Interesting links:
- https://jon.sprig.gs/blog/post/2101
- ADRs templates: https://github.com/joelparkerhenderson/architecture-decision-record
- orginal ADR blog post: https://cognitect.com/blog/2011/11/15/documenting-architecture-decisions
