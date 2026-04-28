<p align="center">
  <h2 align="center"><% .Repo.Name %></h2>
  <p align="center">Description</p>
  <p align="center">
    <a href="https://github.com/<% .Repo.FullName %>/actions/workflows/ci.yml"><img src="https://github.com/<% .Repo.FullName %>/actions/workflows/ci.yml/badge.svg?branch=main" alt="CI" /></a>
    <a href="https://pkg.go.dev/github.com/<% .Repo.FullName %>"><img src="https://pkg.go.dev/badge/github.com/<% .Repo.FullName %>.svg" alt="Go Reference" /></a>
    <a href="https://goreportcard.com/report/github.com/<% .Repo.FullName %>"><img src="https://goreportcard.com/badge/github.com/<% .Repo.FullName %>" alt="Go Report Card" /></a>
    <img src="https://img.shields.io/github/license/<% .Repo.FullName %>" alt="LICENSE" />
    <a href="https://deepwiki.com/<% .Repo.FullName %>"><img src="https://deepwiki.com/badge.svg" alt="Ask DeepWiki" /></a>
  </p>
</p>

## Overview

## Features

## Usage

## Example

## Benchmark

## Warning

## Installation

Install with homebrew

```sh
brew install <% .Repo.Owner %>/tap/<% .Repo.Name %>
```

Install with go

```sh
go install github.com/<% .Repo.FullName %>@latest
```

Or download binary from [releases](https://github.com/<% .Repo.FullName %>/releases)

## Shell completion

Supported Shells are as follows:

- bash
- zsh
- fish
- pwsh

```sh
<% .Repo.Name %> completion bash|zsh|fish|pwsh

# In the case of bash
source <(<% .Repo.Name %> completion bash)
```

## Todo

## Author

[<% .Repo.Owner %>](https://github.com/<% .Repo.Owner %>)

## License

[MIT](https://github.com/<% .Repo.FullName %>/blob/main/LICENSE
