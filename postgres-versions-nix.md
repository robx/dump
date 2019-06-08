---
date: 2019-06-08
tags: postgres nix
---
Installing specific postgres versions with nix:

```
nix-env -iA nixpkgs.postgresql_9_6
nix-env -iA nixpkgs.postgresql_10
nix-env -iA nixpkgs.postgresql_11
```

