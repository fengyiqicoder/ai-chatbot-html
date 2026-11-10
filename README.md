# AI chatbot in HTML, CSS and JavaScript

A free AI chatbot in one `index.html` file. No backend, no build step, no paid API.

**Live demo:** https://fengyiqicoder.github.io/ai-chatbot-html/

## Use it

1. Get a free key at [onetagai.com](https://onetagai.com) (1,000,000 tokens a month, no card).
2. Put it in `data-key` on line 9 of `index.html`.
3. Open the file, or host it free on GitHub Pages (Settings → Pages → Branch: main).

The AI call is one function, `onetag.ask(text, null, { system, history, stream })`. Change the `system` line to make it a tutor, a support bot, anything.

The `data-key` in this repo is a public demo key with a small shared quota. Use your own key on your site.
