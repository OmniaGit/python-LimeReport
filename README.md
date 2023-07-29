Python bindings for [LimeReport](https://github.com/fralx/LimeReport)

🚧 work in progress 🚧

## Build

Default:

```
$ python setup.py build --parallel $(nproc) bdist_wheel
```

With zint (for barcodes):

```
$ LIMEREPORT_USE_ZINT=TRUE python setup.py build --parallel $(nproc) bdist_wheel
```