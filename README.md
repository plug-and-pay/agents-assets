# agents-assets

Image assets for the Plug&Pay `.claude` skills & rules (and the Confluence pages generated from them).

Layout mirrors the `.claude/` tree in `plug-and-pay/plug-and-pay`, **without** the `.claude/` prefix, with a folder per document:

```
skills/<skill>/references/<doc>/<NN-name>.png
rules/<rule>/<NN-name>.png
```

Reference an image from a skill/rule (and from the generated Confluence page) via the raw URL:

```
https://raw.githubusercontent.com/plug-and-pay/agents-assets/main/skills/<skill>/references/<doc>/<file>.png
```
