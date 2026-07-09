# HSK Take From Mending Patch

Compatibility patch for RimWorld HSK 1.5: applies **Take It To Storage!** bill `Take from ...` restrictions to vanilla/HSK bill ingredient search and **Core SK - MendAndRecycle** ingredient search. v1.6 prunes stale `ExtraBillData` bill keys after save load.

## Dependencies

- Harmony
- Take It To Storage!
- Core SK - MendAndRecycle

Load this mod after all three.

## What it fixes

Pawns were ignoring the bill's `Take from` storage selection and taking ingredients from anywhere on the map - not anymore.
