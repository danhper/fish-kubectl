# fishshell completions for kubectl

The completions are taken from the following gist

https://gist.github.com/terlar/28e1c2e4ac9a27be7a5950306bf45ab2#file-kubectl-fish

I created the repository to be able to manage this as a [fundle](https://github.com/tuvistavie/fundle) package.

## Installation

### Using fundle

Add

```
fundle plugin 'tuvistavie/fish-kubectl'
```

to your `config.fish`, reload your shell and run `fundle install`.

### Manually

Add `kubectl.fish` to `~/.config/fish/completions`
