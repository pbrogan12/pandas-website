v0.22.0 Final (December 29, 2017)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

This is a major release from 0.21.1 and includes a single, API-breaking change.
We recommend that all users upgrade to this version after carefully reading the
release note.

The only changes are:

- The sum of an empty or all-*NA* ``Series`` is now ``0``
- The product of an empty or all-*NA* ``Series`` is now ``1``
- We've added a ``min_count`` parameter to ``.sum()`` and ``.prod()`` controlling
  the minimum number of valid values for the result to be valid. If fewer than
  ``min_count`` non-*NA* values are present, the result is *NA*. The default is
  ``0``. To return ``NaN``, the 0.21 behavior, use ``min_count=1``.

See the `pandas 0.22.0 whatsnew <https://pandas.pydata.org/pandas-docs/version/0.22.0/whatsnew.html#whatsnew-0220>`__
overview for further explanation of all the places in the library this affects.
