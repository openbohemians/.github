# Open Bohemians Projects

The founding collection is being prepared. Admission to stewardship is
recorded here when a project has a named maintainer and meets the
[charter's expectations](CHARTER.md).

## Founding project family

| Repository | Purpose | Status | Initial maintainer |
| --- | --- | --- | --- |
| [Oyl](https://github.com/openbohemians/oyl) | SIMD-accelerated YAML 1.2 parser and emitter in C11 | Preparing for stewardship | Tom (@trans) |
| [Crystal bindings](https://github.com/trans/yam.cr) | Crystal bindings for the Oyl project family | Preparing for stewardship | Tom (@trans) |

Oyl, formerly named YAM, and its Crystal bindings form one project family.
The C repository is now under Open Bohemians. The Crystal bindings are
being moved and renamed to `openbohemians/oyl.cr`; the link above follows
their current location until that transfer completes. Their supported C
revision is being reviewed as part of the transition to Oyl.

Before admission, record the supported release or revision for each
repository, document how to contribute, and confirm which C library version
the bindings support. A transfer by itself does not establish compatibility
between their releases.

## Project statuses

| Status | Meaning |
| --- | --- |
| Preparing for stewardship | A candidate is being prepared for admission; outstanding work is still being resolved. |
| Maintained | Named maintainers accept responsibility under the charter and state what they support. |
| Seeking a maintainer | Continued maintenance needs someone to take responsibility; support may be limited. |
| Retired | The project is preserved for reference and no further maintenance is planned. |

## Other projects

Open Bohemians also hosts [Memo](https://github.com/openbohemians/memo),
a Crystal library for portable semantic memory, and
[March](https://github.com/openbohemians/march). Their stewardship status
will be recorded here after review. Use each repository's own documentation
for its present maintenance and release status.
