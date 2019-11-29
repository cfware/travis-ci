# Usage

Please don't use this directly.  I will make changes here as needed for my own
repositories.  If you like these configs feel free to copy them into a repository
under your control.

## All supported node.js majors on each OS without npm caching

```yml
import:
  - cfware/travis-ci:node-supported.yml
  - cfware/travis-ci:os-all.yml
  - cfware/travis-ci:npm-no-cache.yml
```

## Firefox and Chrome with latest node.js

```yml
import:
  - cfware/travis-ci:node-latest.yml
  - cfware/travis-ci:browsers.yml
```
