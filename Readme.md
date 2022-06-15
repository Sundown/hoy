### (A)hoy!

Convenient wrapper for the *`git add, commit, push`* sequence.

Written for Node with Google's [zx](https://github.com/google/zx) scripting library.

```sh
hoy "commit message" [-f] [-a]
```

Run Hoy anywhere you would run Git.

Hoy **will respect your current branch**.

`-a` add all files, `-f` force push to remote.

**Requires** Node version >= 16.0.0 and [zx](https://github.com/google/zx) installed with `npm i -g zx`.

<p align="center">
  <img src="screenshot.png" width="65%" title="Sample">
</p>
