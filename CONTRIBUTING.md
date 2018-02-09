# How to contribute

## Branches and pull requests

Tool wrapper development happens on the master branch and this is what most
pull requests should be made against.

Version-specific branches are for maintenance of tool wrapper versions
distributed with released versions of MiModD. Pull requests against these
branches should only be made for proposed changes that should **not** be
applied to other versions.

Pull requests made against the master branch will be backported to maintenance
branches if necessary.

## Toolshed updates and github releases

Toolshed updates are only done from the latest maintenance branch - once upon
release of a new MiModD version, then whenever relevant backports to that
branch occur while it is still the latest version branch. Every changeset
corresponding to a toolshed update should be tagged as a github release.

Additional significant changesets on any maintenance branch can be tagged as
well, and all tagged changesets within a maintenance branch are available to
end users of the corresponding MiModD version via the `upgrade` tool.
