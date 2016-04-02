# Contribution Guidelines

Please note that this project is released with a [Contributor Code of Conduct](CODE-OF-CONDUCT.md). By participating in this project you agree to abide by its terms.

## Pull Requests

Please ensure your pull request adheres to the following guidelines:

- Make a :sparkles:**separate pull request**:sparkles: for each suggestion/fix. (yep, really!) 
- Don't duplicate existing entries or suggestions. Search open and previous pull requests to see if your suggestion has already been made.
- Use the following format: `[resource](link) - Description.`
- Additions should be added to the bottom of the relevant category.
- New categories or improvements to existing categorizations are welcome.
- Start the description with a capital, end it with a period. 
- Check your spelling and grammar. (I'll kick back PRs on this.)
- Your pull request should have a useful title, the link (of course), and an explanation of why it should be included.

Thank you for your suggestions!

## Pull Request Templates

**Title:** `new([SECTION NAME]): [RESOURCE NAME]` 

```
Please add [RESOURCE](LINK).

This link is awesome enough because:
- 
- 

**Vote for this PR!**
If you agree with this change, add a reaction (e.g. :thumbsup:) to this pull request.
```

... or ...

**Title:** `fix([SECTION NAME]): [BRIEF SUMMARY]`
```
Fixes # .

Changes proposed in this pull request:
-
-
-

**Vote for this PR!**
If you agree with this change, add a reaction (e.g. :thumbsup:) to this pull request.
```

## Updating Pull Requests

Yeah, the list above is long and nit-picky. Submitting PRs that adhere to these standards can be a challenge. If the maintainers of the list notice anything we'd like changed, we'll ask you to edit your PR before it is merged.

If you're not sure how to do that, [here is a guide](https://github.com/RichardLitt/docs/blob/master/amending-a-commit-guide.md) on the different ways you can update your PR so it can be merged.

Note: You **do not** need to rebase your PR edits.

## Adding a Section

The main list is generated from a build process which uses [markdown-include](https://github.com/sethen/markdown-include) to manage the sections. To add a section, follow these steps:

  1. Create the section file in the `.README` directory. 
    - Section heading should be level 3 `###`.
    - After the section name, add ` !heading` to ensure the heading is included in the Contents.
    - Add optional description `*like so*` if appropriate.
  2. Submit a PR describing the need for the section. The PR should mention at least two links that should reside in this new category.
  
### Example

```
### Lua Additions !heading

*Sometimes these additional Lua bundle commands are just the thing you need.*

- [Wow](http://example.com) - Type all teh codez.
- [Neat](http://another-example.com) - A must for creating rocks.
```