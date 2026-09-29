<!-- LOVABLE:BEGIN -->
> [!IMPORTANT]
> This project is connected to [Lovable](https://lovable.dev). Avoid rewriting
> published git history — force pushing, or rebasing/amending/squashing commits
> that are already pushed — as it rewrites history on Lovable's side and the
> user will likely lose their project history.
>
> Commits you push to the connected branch sync back to Lovable and show up in
> the editor, so keep the branch in a working state.
<!-- LOVABLE:END -->

- All Invictus client, memory, regulation and insight data lives in src/data/invictus.ts, including the demo recall/impact functions — the app must run fully without external services.
- Optional live integrations use server functions and a read-only health endpoint; live Hindsight writes require authenticated sessions so public visitors cannot spend credits or alter memories.
