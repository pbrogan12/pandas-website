v0.23.0 Final (May 15, 2018)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

This is a major release from 0.22.0 and includes a number of API changes, new features, enhancements, and performance improvements along with a large number of bug fixes.

Highlights include:

- `Round-trippable JSON format with 'table' orient <https://pandas.pydata.org/pandas-docs/version/0.23.0/whatsnew.html#json-read-write-round-trippable-with-orient-table>`_.
- `Instantiation from dicts respects order for Python 3.6+ <https://pandas.pydata.org/pandas-docs/version/0.23.0/whatsnew.html#instantation-from-dicts-preserves-dict-insertion-order-for-python-3-6>`_.
- `Dependent column arguments for assign <https://pandas.pydata.org/pandas-docs/version/0.23.0/whatsnew.html#assign-accepts-dependent-arguments>`_.
- `Merging / sorting on a combination of columns and index levels <https://pandas.pydata.org/pandas-docs/version/0.23.0/whatsnew.html#merging-on-a-combination-of-columns-and-index-levels>`_.
- `Extending Pandas with custom types <https://pandas.pydata.org/pandas-docs/version/0.23.0/whatsnew.html#extending-pandas-with-custom-types-experimental>`_.
- `Excluding unobserved categories from groupby <https://pandas.pydata.org/pandas-docs/version/0.23.0/whatsnew.html#categorical-groupers-has-gained-an-observed-keyword>`_.

The release candidate can be installed with conda from our development channel (builds for osx-64, linux-64 and win-64 for Python 2.7, Python 3.5, and Python 3.6 are all available)::

    conda install pandas

or conda forge::

    conda install -c conda-forge pandas

Or via PyPI::

    python3 -m pip install --upgrade pandas==0.23.0

See the `full whatsnew <https://pandas.pydata.org/pandas-docs/version/0.23.0/whatsnew.html#v0-23-0>`_ for a list of all the changes.
