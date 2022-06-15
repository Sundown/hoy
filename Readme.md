### (A)hoy!

Convenient wrapper for the *`git add, commit, push`* sequence.</br>
Written for Node with Google's [zx](https://github.com/google/zx) scripting library.</br>


<p align="center">
  <img src="screenshot.png" width="50%" title="Sample">
</p>

```sh
hoy "commit message" [-f] [-a]
```

Hoy **will respect your current branch**

`-a` add all files, `-f` force push to remote.

Run Hoy anywhere you would run Git.

**Requires** Node version >= 16.0.0 and [zx](https://github.com/google/zx) installed with `npm i -g zx`
