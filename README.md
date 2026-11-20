# UCL Live prompts

The prompts from "Just Because AI Can Doesn't Mean You Should" at UCL Live Austin, on one fast page.

Live page: https://theuncommonbusiness.github.io/ucl-prompts/

The whole site is `index.html`. It has no fonts to download, no images, no analytics and no other files, so it loads fast on slow event wifi. Keep it that way, and keep the file under 25 KB.

## Add a prompt

1. Open `index.html` and find the last card. Each card starts with a `CARD START` comment and ends with a `CARD END` comment.
2. Copy one whole card, from `CARD START` to `CARD END`, and paste it after the last card (above `CARDS END`).
3. Change the `id`, the "Prompt" number, the name, the one line under the name, the "What you get" bullets and the time.
4. Paste the prompt between `<pre id="...">` and `</pre>`. Start the text right after the `>` with no blank line, and make the Copy button's `data-copy` match the `<pre>` id.
5. In the prompt text, write `&lt;` for `<` and `&amp;` for `&`. Everything else can stay as is.
6. Leave `open` off new cards. Only The Mirror starts open.

Commit to `main` and GitHub Pages updates the live page in about a minute.

## Before you push

- If a prompt is also on a slide, the words on the page and the slide must match.
- Open the page on your phone, tap Copy and paste it somewhere to check you got the whole prompt.
- Page copy follows plain words: no em dashes and no semicolons.
