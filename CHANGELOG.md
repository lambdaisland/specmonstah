# Unreleased

## Changed

- Introduce lambdaisland friendly fork
- When adding multiple ents of the same type, don't have them all point at the
  same related ents, but instead cycle through the ents that are already in the
  DB.
  
# [2.0.0] - 2019-11-5

## New

- It's all entirely different now. Please see https://sweet-tooth.gitbook.io/specmonstah/ for a tutorial.

## Changed

- **BREAKING** renamed `reifyhealth.specmonstah.core/build-ent-db` to `reifyhealth.specmonstah.core/add-ents`

# [1.1.1] - 2017-07-27

## New

- Added CLJS test tasks

## Fixed

- Fixed tests when run as CLJS

# [1.1.0] - 2017-06-05

## New

- Added a new binding syntax that ensures references are consistent across a query term's graph
- Added the `bind-relations` helper which adds bindings to many query terms

# [1.0.1] - 2017-03-09

## Fixed

- Fix issue where, if you referenced the same entity in multiple locations, attributes would not be set unless you set them on the last reference.
