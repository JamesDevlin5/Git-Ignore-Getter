# Git-Ignore Template Fetcher

**Fetches a template `.gitignore` file matching your specific needs!**

- The API: `gitignore.io` is used to retrieve the files

## Features

- Will not overwrite an existing gitignore file, an error will be propagated if the
  output path already exists.
- The list of gitignore templates from the remote host is cached between sessions, so
  startup time should be negligible if this cached file exists.
- The fuzzy finder, `fzf`, is used to select templates interactively
- Will not retrieve an empty gitignore file if no templates are selected

## Sample Usage

[![asciicast](https://asciinema.org/a/455107.svg)](https://asciinema.org/a/455107)

