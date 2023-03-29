# Homebrew Formulae for MeshFEM/RodAssembly

## List of packages?

- `suite-sparse@5.13`

## How do I install these formulae?

`brew install desmondlzy/rod/<formula>`

Or `brew tap desmondlzy/rod` and then `brew install <formula>`.

If you also have other versions of the same software already installed with brew, probably you need to unlink the existing version and link the new version.

```
brew install desmondlzy/rod/suite-sparse@5.13
brew unlink suite-sparse  # this is the version from homebrew/core which is always the latest
brew link suite-sparse@5.13
```

## Documentation

`brew help`, `man brew` or check [Homebrew's documentation](https://docs.brew.sh).
