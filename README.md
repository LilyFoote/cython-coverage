# Cython Coverage

This coverage plugin works around [this cython bug](https://github.com/cython/cython/issues/3636). For more information, see [this comment](https://github.com/cython/cython/pull/3648#issuecomment-662448404).

## Usage

Install the plugin:

`pip install cython-coverage`

Add it to `.coveragerc`:

```
[run]
plugins = cython_coverage
```
