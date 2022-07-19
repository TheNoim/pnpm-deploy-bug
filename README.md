# Reproduce

Run: `pnpm --filter="{packages/server}" deploy dist`

Result:

```
Packages are copied from the content-addressable store to the virtual store.
  Content-addressable store is at: /Users/REMOVED/Library/pnpm/store/v3
  Virtual store is at:             dist/node_modules/.pnpm
 ERR_PNPM_LOCKFILE_MISSING_DEPENDENCY  Broken lockfile: no entry for '/tailwindcss/2.2.19' in pnpm-lock.yaml

This issue is probably caused by a badly resolved merge conflict.
To fix the lockfile, run 'pnpm install --no-frozen-lockfile'.
Progress: resolved 0, reused 1, downloaded 0, added 0
```