# release-notes-test

testing new release notes feature

current syntax:

`.github/release.yml`

```yml
changelog:
  categories:
  - title: Breaking Changes
    labels:
    - Semver-Major
    - breaking-change
  - title: Exciting New Features :tada:
    labels:
    - Semver-Minor
    - enhancement
  - title: Other Changes
    labels:
       - “*”
```
