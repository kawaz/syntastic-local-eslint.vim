# syntastic-local-eslint.vim

Prefer local repo install of eslint over global install with syntastic

Installation Instructions
-------------------------

Using [dein.vim](https://github.com/Shougo/dein.vim) you just need to add:

```toml
[[plugins]]
repo = 'kawaz/syntastic-local-eslint.vim'
hook_add = "let g:syntastic_javascript_checkers = ['eslint']"
```

