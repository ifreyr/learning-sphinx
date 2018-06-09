超链接
========

reStructuredText 会自动将网址生成超链接，如 ``https://www.baidu.com/``：

https://www.baidu.com/



外部超链接
------------

只能是一个词语，引用的文字不能带有空格。

本文来自我的 Github，请参考 reference_。

.. _reference: https://github.com/example/

::

    本文来自我的 Github，请参考 reference_。

    .. _reference: https://github.com/example/

行内形式可以带有空格或者符号：::

   本文来自我的 Github，请参考 `example <https://github.com/example/>`_。



内部超链接
------------

内部超链接用于在文档内部创建锚点。

更多信息参考 hyperlink_

.. _hyperlink:

...这里是超链接的内容 http://docutils.sourceforge.net/docs/ref/rst/restructuredtext.html...

::

   更多信息参考 hyperlink_

   .. _hyperlink:

   ...这里是超链接的内容 http://docutils.sourceforge.net/docs/ref/rst/restructuredtext.html...


匿名超链接
-------------

使用双下划线，引用的文字可以带有空格或者符号，需要使用反引号引起来。

::

    这篇文章参考的是：`Quick reStructuredText`__。

    .. __: http://docutils.sourceforge.net/docs/user/rst/quickref.html


间接超链接
-----------

间接超链接是基于匿名链接的基础上的，就是将匿名链接地址换成了外部引用名。

::

    baidu_ 是 `百度 Baidu 的官方主页`__。

    .. _baidu: https://www.baidu.com/

    __ baidu_


隐式超链接
--------------

小节标题、脚注和引用参考会自动生成超链接地址，使用小节标题、脚注或引用参考名称作为超链接名称就可以生成隐式链接。

::

    第一节 介绍
    ===========

    其他内容...

    隐式链接到 `第一节 介绍`_，即可生成超链接。
