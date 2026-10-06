# Contribution Guidelines

Please note that this project is released with a [Contributor Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/). By participating in this project you agree to abide by its terms.

## What Belongs Here

<!-- TODO: inclusion criteria -->

## Adding an Entry

- Search previous suggestions before making a new one, as yours may be a duplicate.
- Make an individual pull request for each suggestion.
- Use the following format: `- [Name](https://link) - Description.`
- Keep descriptions short and simple, start with a capital letter, and end with a period.
- Add the entry to the most fitting section, in alphabetical order within that section.
- Link to the project homepage or repository, not to a fork or a package registry page.
- New categories or improvements to existing categories are welcome. Update the Contents list when adding a section.
- Check your spelling and grammar.
- Make sure your text editor is set to remove trailing whitespace.
- The pull request and commit should have a useful title.

## Validating Locally

With [Nix](https://nixos.org) installed:

```sh
nix develop -c npx awesome-lint
nix develop -c lychee --config lychee.toml README.md
```

Thank you for your suggestions!
