脚注
======

If [#note]_ is the first footnote reference, it will show up as
"[1]".  We can refer to it again as [#note]_ and again see
"[1]".  We can also refer to it as note_ (an ordinary internal
hyperlink reference).

.. [#note] This is the footnote labeled "note".

::

    If [#note]_ is the first footnote reference, it will show up as
    "[1]".  We can refer to it again as [#note]_ and again see
    "[1]".  We can also refer to it as note_ (an ordinary internal
    hyperlink reference).

    .. [#note] This is the footnote labeled "note".

.. note::

   使用 ``#`` 可以自动编号脚注。

[#]_ is a reference to footnote 2, and [#]_ is a reference to
footnote 3.

.. [#] This is footnote 2.
.. [#] This is footnote 3.
.. [#] This is footnote 4.

[#]_ is a reference to footnote 4.

::

    [#]_ is a reference to footnote 1, and [#]_ is a reference to
    footnote 2.

    .. [#] This is footnote 1.
    .. [#] This is footnote 2.
    .. [#] This is footnote 3.

    [#]_ is a reference to footnote 3.


