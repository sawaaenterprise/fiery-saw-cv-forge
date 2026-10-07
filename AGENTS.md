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

## Application rules
- Keep the imported portfolio at `/` and full CV at `/cv` using TanStack routes to preserve repository navigation.
- Define portfolio styling and reduced-motion-aware animation in the global design system so all views share semantic tokens.
- Store imported repository media and the downloadable PDF as project-scoped asset pointers so this site does not depend on another project's storage.
