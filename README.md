# GitHub Config

GitHub repository management with [babarot/gh-infra](https://github.com/babarot/gh-infra).

## Usage

Initialize the Go CLI repositories with flat structure.

```sh
cd src/go/
gh infra plan repos.yaml files.cli.yaml
gh infra apply repos.yaml files.cli.yaml
```

Initialize the Go package repositories with flat structure.

```sh
cd src/go/
gh infra plan repos.yaml files.pkg.yaml
gh infra apply repos.yaml files.pkg.yaml
```

## Worktree

The directory tree has been optimized as follows:

```text
.
└── go
    ├── files.cli.yaml
    ├── files.pkg.yaml
    ├── repos.yaml
    └── templates
        ├── base
        │   ├── .editorconfig
        │   ├── .gitattributes
        │   ├── .gitignore
        │   ├── .golangci.yml
        │   ├── .tagpr
        │   ├── go.mod
        │   ├── LICENSE
        │   └── .vscode
        │       ├── extensions.json
        │       └── settings.json
        ├── cli
        │   ├── .goreleaser.yml
        │   ├── .octocov.yml
        │   ├── Makefile
        │   ├── README.md
        │   └── .github
        │       ├── CODEOWNERS
        │       ├── dependabot.yml
        │       ├── release.yml
        │       └── workflows
        │           ├── ci.yml
        │           └── release.yml
        └── pkg
            ├── .octocov.yml
            ├── Makefile
            ├── README.md
            ├── .github
            │   ├── CODEOWNERS
            │   ├── dependabot.yml
            │   ├── release.yml
            │   └── workflows
            │       ├── ci.yml
            │       └── release.yml
            └── benchmarks
                └── Makefile
```
