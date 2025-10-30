# Contributing Policy

Hey, thanks for your interest in contributing to Vanilla Reimagined! We appreciate your help and taking your time to contribute.

We have only one main rule for contributions to keep our project consistent and maintainable.

- [Commit Convention](#commit-convention)

## Commit Convention

In order to keep our commit history clean and understandable, we follow a specific commit message format based on the Conventional Commits specification.

### Commit Message Format

```
<type>[optional scope]: <description>

[optional body]

[optional footer(s)]
```

#### Type

Must be one of the following:

- **mod**: Add, update, or remove a mod
- **config**: Changes to mod configurations or packwiz settings
- **resource**: Changes to resourcepacks, shaders, or other resources
- **docs**: Documentation changes
- **chore**: Maintenance tasks, such as updating hashes or dependencies
- **release**: Publish a new version to Modrinth (triggers automatic release)

#### Scope (optional)

You can specify the affected area, for example:
- `mod(performance)`: for performance-related mods
- `mod(gameplay)`: for gameplay-affecting mods
- `config(jei)`: for JEI configuration changes

#### Examples

```
mod: add Sodium for better performance
mod(gameplay): update Create to version 0.5.1
config: adjust JEI recipe visibility settings
release: version 1.2.0
```

Thank you for your contribution!
