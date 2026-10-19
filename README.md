# Smileyhojin's blog

Built with Zola and the Serenity theme submodule.

## Develop

```sh
git submodule update --init --recursive
# nix develop
zola check --drafts --skip-external-links
zola build
zola serve --drafts --base-url /
```
