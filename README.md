# python-lazy-sequential-data-types
a module to lazily populate sequential data types (taken from pytz package to be available to be available as module rather than a package)


usage sample:
```
from .lazy import LazyDict, LazyList, LazySet
# or from . import LazyDict, LazyList, LazySet


L1=["a long","list"]
LazyL1 = LazyList(item for item in L1)
```
