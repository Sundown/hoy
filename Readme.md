### (A)hoy! :octopus:

Git wrapper for stupid people like you, who are too lazy to write two commands.

Written for Node with Google's [zx](https://github.com/google/zx) scripting library.

This is bloated for a Git wrapper, but everyone has the dependencies installed anyway so that doesn't matter.

---

#### Usage

```sh
hoy "commit message" [-f] [-a]
```

Hoy **will respect your current branch** and push to it specifically.

`-a` will ask Git to add all files `git add *`, omitting this will just commit tracked files.

`-f` will force push to remote

Run anywhere in your Git working directory.

---

#### Installation

Put this in local bin, or alias in your shell runcom.

---

#### Requirements

Node version >= 16.0.0

[zx](https://github.com/google/zx) installde with `npm i -g zx`

and Git...

---

#### Licence

GPL 2.0

**Disclaimer:** Not my problem if you stuff up your repo using this.
