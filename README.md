# ghaction

## vX.Y.Z
* `v0.0.0 -> v.0.0.1` produces nothing
* `v0.0.0 -> v0.0.1` produces patch update
* `v0.0.0 -> v0.1.1` produces minor update
* `v0.0.0 -> v1.1.1` produces major update
* `v0.0.0 -> v2/2.2` prduces nothing

## X/Y.Z
* `v2/2.2 -> v2/2.3` prodces [not-classified update](https://github.com/dependabot/dependabot-core/issues/4386)
* `v2/2.2 -> v2/3.3` prodces [not-classified update](https://github.com/dependabot/dependabot-core/issues/4386)
* `v2/2.2 -> v3/3.3` prduces nothing
* `v2/2.2 -> v3/3.3.3` prduces nothing

## X/X.Y.Z

* `v3/3.3.3 -> v3/3.3.4` prodces [not-classified update](https://github.com/
* `v3/3.3.3 -> v4/4.4.4` prduces nothing
* `v3/3.3.3 -> v/4.4.4` prduces nothing


## v/X.Y.Z

* `v/4.4.4 -> v/4.4.5` prodces [not-classified update](https://github.com/
* `v/4.4.4 -> v.5.5.5` prduces nothing

## v.X.Y.Z

* `v.5.5.5 -> v.5.5.6` prodces [not-classified update](https://github.com/
