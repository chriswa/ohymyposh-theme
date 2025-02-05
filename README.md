# ohymyposh-theme

## install oh-my-posh

```
brew install jandedobbeleer/oh-my-posh/oh-my-posh
```

## add to ~/.zshrc

```
# per https://ohmyposh.dev/docs/installation/prompt
if [ "$TERM_PROGRAM" != "Apple_Terminal" ]; then
  eval "$(oh-my-posh init zsh --config ohymyposh-theme/chriswa.omp.json)"
fi
```

