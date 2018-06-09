图片
=======


.. image:: ../images/python.jpeg

::

   .. image:: ../images/python.jpeg

Sphinx 延伸了标准的文档化行为，只需在后面加星号:::

   .. image:: gnu.*

上面这样写，Sphinx 会搜索所有名字匹配的图像，而不管图像类型。
每个生成器则会选择最合适的图像。
一般，在源文件目录里文件名 gnu.* 会含有两个文件 gnu.pdf 和 gnu.png，
LaTeX 生成器会选择前者，而 HTML 生成器则匹配后者.

