# Smileyhojin's blog

Built with Zola and the Serenity theme submodule.

## Develop

```sh
git submodule update --init --recursive
nix develop
zola serve --drafts --base-url /
```

## Build and check

```sh
nix develop -c zola check --drafts --skip-external-links
nix develop -c zola build
```
