---
id: Nvim-latex
aliases:
  - nvim-latex
tags:
  - Editor
  - LaTex
created: "17-10-2026 13:54"
status:
---

# nvim-latex

To setup nvim for latex workflow we need to use a plugin named [vim-tex](https://github.com/lervag/vimtex.git)

What is [[Latex]]

## Installation

We can you use plugin managers like packer or lazy for installing this plugin in nvim. since i am using lazyvim i will use lazy manager to install the plugin.

```lua
return {
  'lervag/vimtex',
  lazy = false,
  init = function ()
    vim.g.vimtex_view_method='zathura'
    end
}
```

## References

[Git Repo](https://github.com/lervag/vimtex.git)
