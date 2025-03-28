**Changelog** is a [Nerve](https://github.com/evilsocket/nerve) agent that uses `git` to determine the new commits since the last release in a git repository folder and generates a nicely formatted markdown changelog [like this one](https://github.com/evilsocket/nerve/releases/tag/v1.3.0).

Install with (requires nerve >= 1.4.x):

```bash
# this will download and install (or update) to ~/.nerve/agents
nerve install evilsocket/changelog 
```

Run from inside a git repository folder with:

```bash
# use with -q to only print the changelog markdown and disable logs
nerve run changelog -q
```

In action:

[![asciicast](https://asciinema.org/a/710433.svg)](https://asciinema.org/a/710433)