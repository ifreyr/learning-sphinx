代码块
=========

文本代码块通过在段尾使用 ``::`` 标记，如

This is a normal text paragraph. The next paragraph is a code sample::

   It is not processed in any way, except
   that the indentation is removed.

   It can span multiple lines.

This is a normal text paragraph again.

语法为： ::

   This is a normal text paragraph. The next paragraph is a code sample::

      It is not processed in any way, except
      that the indentation is removed.

      It can span multiple lines.

   This is a normal text paragraph again.

.. important::

   代码块必须缩进，且使用空行分离。


.. note::

   ``::`` 可以紧接上一行或新起一行。

::

   Paragraph:

   ::

      Literal block


   Paragraph: ::

      Literal block

.. note::

   可以使用 ``.. code-block::`` 进行语法高亮。

::

    def foo():
        print("Life is short, use Python")

显示效果为：

.. code-block:: python

    def foo():
        print("Life is short, use Python")



.. tip::

   使用 ``:linenos:`` 显示行号。

::

   import sys

   print(sys.version)

显示效果如下：

.. code-block:: python
   :linenos:

   import sys

   print(sys.version)


.. tip::

   Python 文档测试块使用 ``>>>`` 标记，以空行结束。

>>> print "This is a doctest block."
This is a doctest block.
