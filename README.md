# ghaction

## vX.Y.Z
* `v0.0.0 -> v0.0.1` produces patch update
* `v0.0.0 -> v0.1.1` produces minor update
* `v0.0.0 -> v1.1.1` produces major update


* `v8.8.8 -> 8.8.9` produces patch update
* `v8.8.8 -> 8.9.9` produces minor update
* `v8.8.8 -> 9.9.9` produces major update


* `v0.0.0 -> v.0.0.1` produces nothing
* `v0.0.0 -> v2/2.2` produces nothing


## X.Y.Z
* `6.6.6 -> 6.6.7` produces patch update
* `6.6.6 -> 6.7.7` produces minor update
* `6.6.6 -> 7.7.7` produces major update


* `7.7.7 -> v7.7.8` produces patch update
* `7.7.7 -> v7.8.8` produces minor update
* `7.7.7 -> v8.8.8` produces major update


* `7.7.7 -> v.8.8.8` produces nothing
* `7.7.7 -> v8/8.8` produces nothing
* `7.7.7 -> v/8.8.8` produces nothing


## X/Y.Z
* `v2/2.2 -> v2/2.3` prodces [not-classified update](https://github.com/dependabot/dependabot-core/issues/4386)
* `v2/2.2 -> v2/3.3` prodces [not-classified update](https://github.com/dependabot/dependabot-core/issues/4386)
* `v2/2.2 -> v3/3.3` produces nothing
* `v2/2.2 -> v3/3.3.3` produces nothing


## X/X.Y.Z
* `v3/3.3.3 -> v3/3.3.4` prodces [not-classified update](https://github.com/
* `v3/3.3.3 -> v4/4.4.4` produces nothing
* `v3/3.3.3 -> v/4.4.4` produces nothing


## v/X.Y.Z
* `v/4.4.4 -> v/4.4.5` prodces [not-classified update](https://github.com/
* `v/4.4.4 -> v.5.5.5` produces nothing


## v.X.Y.Z
* `v.5.5.5 -> v.5.5.6` prodces [not-classified update](https://github.com/
* `v.5.5.5 -> 5.5.6` produces nothing
* `v.5.5.5 -> 6.6.6` produces nothing

