# Usage

Please don't use this directly.  I will make changes here as needed for my own
repositories.  If you like these configs feel free to copy them into a repository
under your control.

## All supported node.js majors on each OS without npm caching

```yml
version: ~> 1.0
import:
  - cfware/travis-ci:node-supported.yml
  - cfware/travis-ci:os-all.yml
  - cfware/travis-ci:npm-no-cache.yml
```

## Node.js with unflagged ESM support on each OS without npm caching

```yml
version: ~> 1.0
import:
  - cfware/travis-ci:node-esm.yml
  - cfware/travis-ci:os-all.yml
  - cfware/travis-ci:npm-no-cache.yml
```

## Firefox and Chrome with latest node.js

```yml
version: ~> 1.0
import:
  - cfware/travis-ci:node-latest.yml
  - cfware/travis-ci:browsers.yml
```
