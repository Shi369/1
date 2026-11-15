# Project memory

## Product intent & audience

- Landing page for **MD轻页**, a lightweight mobile Markdown editor.
- Highlights core features, target audience, download CTA (placeholder link), app icon, and footer.
- Footer copyright by **水车**, dated November 2026.
- Publishable output intended for **GitHub Pages** (manual deploy; no auto-push).

## Brand personality & voice

- Modern, minimalist, calm tone.
- Chinese-language UI copy; product name "MD轻页" kept in Chinese.
- Title presentation favors a relaxed, unhurried feel (typewriter effect deliberately slowed).

## Visual design & UX direction

- Aesthetic: clean, minimalist, airy.
- Color palette: white base with light green gradients.
- Hero title uses a **typewriter (typewriter) reveal effect**; speed tuned to a slower, more comfortable interval (reduced from prior setting).
- Layout sections: hero with app icon + headline, features, target audience, download button, footer.
- Output is a **single-file homepage** plus app icon asset(s) for portable publishing.

## Decisions, constraints & rationale

- Build/generation produces a publish-ready static bundle (single-file index + icon resources).
- Typewriter interval was lowered to make the headline appear more gracefully; rationale is calmer first impression.
- GitHub Pages is the deployment target; generated files are prepared locally rather than auto-pushed.
- Download link remains a placeholder until a real distribution URL is provided.

## Open questions & assumptions

- No authoritative `.bolt/prompt` provided; current context is inferred from project summary and the single change request.
- Actual typewriter interval value not specified numerically; assumed "slower than previous" is sufficient.
- Real download URL still pending.
- GitHub repo/Pages configuration details not yet known.