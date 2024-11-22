# Dream
The main features are Masonry Layout Posts and Flippable About Page.

https://github.com/g1eny0ung/hugo-theme-dream

### Setup Dream as Git submodule

```
hugo new site . --force
git submodule add https://github.com/g1eny0ung/hugo-theme-dream.git themes/dream
hugo new content/_index.md
hugo server
```

Then open `hugo.toml` and add `theme = 'dream'`.