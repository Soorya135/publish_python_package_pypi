# `samplepackage`

The `samplepackage` is a simple testing example to understand the basics of developing your first Python package. 

## Install & Usage

You can install `samplepackage` as follows:

```
pip install --index-url https://test.pypi.org/simple/ --no-deps samplepackage-test_123
```
Try to have fun with `samplepackage`:

```
from multiply.by_three import multiply_by_three
from divide.by_three import divide_by_three

multiply_by_three(9)
divide_by_three(21)
```

## Useful Resources

* [Packaging Python Projects¶](https://packaging.python.org/en/latest/tutorials/packaging-projects/)
* [Configuring setuptools using setup.cfg files](https://setuptools.pypa.io/en/latest/userguide/declarative_config.html)
#comment
