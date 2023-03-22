# A [Giter8][g8] template for nigeleke Scala projects.

## Template license

Written in 2003 by Nigel Eke.

To the extent possible under law, the author(s) have dedicated all copyright and related
and neighboring rights to this template to the public domain worldwide.
This template is distributed without any warranty. See <http://creativecommons.org/publicdomain/zero/1.0/>.

## Usage

### Prerequisites

[nix](https://nixos.org/) and [sbt](https://www.scala-sbt.org/) on your tool-chain.

### Run

```
> sbt new nigeleke/scala-seed.g8
name [My Something Project]: xyz
> cd xyz
xyz> nix flake update
xyz> nix develop
xyz> sbt compile test
xyz> ...
```

[g8]: http://www.foundweekends.org/giter8/
