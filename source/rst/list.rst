列表
======


无序列表
---------

无序列表可以使用 ``* - +`` 标记，如：

* 吃饭
* 睡觉
* 打豆豆

语法如下： ::

   * 吃饭
   * 睡觉
   * 打豆豆

.. note::

   - 不同的符号混用结尾需要加上空行。
   - 列表支持嵌套，但需要空行和缩进。

::

    - 符号列表1
    - 符号列表2

      + 二级符号列表1

      - 二级符号列表2

      * 二级符号列表3

    * 符号列表3

    + 符号列表4


有序列表
---------

有序列表最常见是使用数字和点号进行标记，如：

1. 把冰箱打开
2. 把大象塞进去
3. 把冰箱关上

语法为： ::

   1. 把冰箱打开
   2. 把大象塞进去
   3. 把冰箱关上


.. note::

   使用 ``#`` 可以自动生成枚举序号。

1. 枚举列表1
#. 枚举列表2
#. 枚举列表3

::

   1. 枚举列表1
   #. 枚举列表2
   #. 枚举列表3


.. note::

   其他可以使用的标记有：

   - 字母：a-z A-Z
   - 罗马数字：I II III IV...（或小写 i ii iii iv...）


字段列表
---------

:Date: 2001-08-16
:Version: 1
:Authors: - Me
          - Myself
          - I
:Indentation: Since the field marker may be quite long, the second
   and subsequent lines of the field body do not have to line up
   with the first line, but they must be indented relative to the
   field name marker, and they must line up with each other.
:Parameter i: integer


::

    :Date: 2001-08-16
    :Version: 1
    :Authors: - Me
              - Myself
              - I
    :Indentation: Since the field marker may be quite long, the second
       and subsequent lines of the field body do not have to line up
       with the first line, but they must be indented relative to the
       field name marker, and they must line up with each other.
    :Parameter i: integer


选项列表
----------

-a         Output all.
-b         Output both (this description is
           quite long).
-c arg     Output just arg.
--long     Output all day long.

--very-long-option  A VMS-style option.  Note the adjustment for
                    the required two spaces.

--an-even-longer-option
           The description can also start on the next line.

-2, --two  This option has two variants.

-f FILE, --file=FILE  These two options are synonyms; both have
                      arguments.

::

    -a         Output all.
    -b         Output both (this description is
               quite long).
    -c arg     Output just arg.
    --long     Output all day long.

    --very-long-option  A VMS-style option.  Note the adjustment for
                        the required two spaces.

    --an-even-longer-option
               The description can also start on the next line.

    -2, --two  This option has two variants.

    -f FILE, --file=FILE  These two options are synonyms; both have
                          arguments.
