# Semantic frontend versioning


## Aim

Frontend can have zero-dependents. This project proposes a semver-like versioning system for frontend projects

Specific aims:
- describe the amount of difference/complexity between different versions
- exist along side Semver if it is used

## Rules

Given a version number MAJOR.MINOR.PATCH, increment the:

* MAJOR version when you add a new problem domain solution (e.g. new site page)
* MINOR version when you add a feature an existing problem domain (e.g. add control to admin page, )
* PATCH version when you make feature tweaks, bug fixes, style or text changes (e.g. change css rules)

Additional labels for pre-release and build metadata could mirror Semver when appropriate

## References

* [Semantic versioning](http://semver.org/)
* [VIDEO Semver in a nutshell](https://www.youtube.com/watch?v=aK0-SrdHriw#t=20m22s)
* [VIDEO Why is npm so good](https://www.youtube.com/watch?v=aK0-SrdHriw#t=23m08s)
