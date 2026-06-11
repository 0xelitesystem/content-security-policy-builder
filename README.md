# Content Security Policy Builder

This tool builds a Content-Security-Policy header by toggling directives and choosing their allowed sources. It assembles the header string live, flags the sources that weaken the policy, and lets you copy the result.

**Live demo:** https://0xelitesystem.github.io/content-security-policy-builder/

## What it does

Switch on the directives you need, default-src, script-src, style-src, img-src, frame-ancestors, and more, and pick each one's sources, such as self, none, https, data, or specific hosts you type in. The tool builds the header value live and warns when a directive has no source or includes unsafe-inline or unsafe-eval.

Deploy any policy in report-only mode first to see what it would block before it blocks anything. Start strict and loosen only where the page genuinely loads from. This pairs with the security-headers reference in the wider collection.

## Aesthetic

A dark green printed circuit board: white silkscreen labels, pill-shaped source pads, sliding toggles, and the header rendered on a copper-trace field.

## Privacy

Everything runs in your browser. Nothing you type is sent anywhere, stored, or saved. Closing the tab clears it.

## Use it

Open `index.html` in any modern browser, or host it as a static page. No build step, no dependencies, no network calls.

## License

MIT. Copyright (c) 2026 0xelitesystem.
