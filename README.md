# uData-croquemort

This plugin provides integration between uData and Croquemort link checker.

## Compatibility

**udata-croquemort** requires Python 2.7+ and [uData][].

## Installation

Install [uData][].

Remain in the same virtual environment (for Python) and use the same version of npm (for JS).

Install **udata-croquemort**:

```shell
pip install udata-croquemort
```

Modify your local configuration file of **udata** (typically, `udata.cfg`) as following:

```python
PLUGINS = ['croquemort']
LINKCHECKING_DEFAULT_LINKCHECKER = 'croquemort'
CROQUEMORT_URL = 'http://localhost:8000'
CROQUEMORT_NB_RETRY = 10
CROQUEMORT_DELAY = 1
```

[uData]: https://github.com/opendatateam/udata
