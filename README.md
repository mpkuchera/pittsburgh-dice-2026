# Pittsburgh DICE 2026

Materials from the PICUP Pittsburgh DICE 2026 session on building interactive teaching pages with AI.

**Live site:** https://mpkuchera.github.io/pittsburgh-dice-2026/

## Infinite square well inquiry

[`square-well-inquiry/index.html`](square-well-inquiry/index.html) · [open it live](https://mpkuchera.github.io/pittsburgh-dice-2026/square-well-inquiry/)

A five-step guided activity built around the initial state
ψ(x, 0) = A sin(πx/L) [1 + cos(πx/L)]:

1. **Coefficients:** students enter c₁ and c₂ from their own derivation and see ψ(x, 0) rebuilt from their numbers, with feedback on common errors.
2. **Predict:** what the probability density will do, and its period.
3. **Watch:** Re ψ, Im ψ and |ψ|² evolve against the t = 0 density.
4. **Measure:** simulated energy measurements against |cₙ|².
5. **Explore:** two-state mixes with an adjustable phase, and Ax(L − x) as a many-state contrast.

It is a single self-contained HTML file with no libraries. Download it and open it in any browser, or adapt it for your own course. Student responses stay in their browser; "Copy my responses" puts them on the clipboard.

## Inside the Well: the Codex version

[`codex-version/index.html`](codex-version/index.html) · [open it live](https://mpkuchera.github.io/pittsburgh-dice-2026/codex-version/)

The same lecture example built with OpenAI's Codex, for comparison. It walks through the hand derivation step by step (coefficients, assembling ψ(x, t), prediction, animation) and adds a wave-packet investigation: truncation, a momentum kick, and reflection off the wall.

## From a past DICE

[Standard Model force map](https://mpkuchera.github.io/standard-model-force-map/): an interactive map of the fundamental particles and the forces that act on them, built with AI at an earlier DICE workshop.

## License

Both square well activities are dedicated to the public domain under [CC0 1.0](LICENSE). You may copy, modify and reuse them for any purpose, without asking.
