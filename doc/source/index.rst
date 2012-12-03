Sphinx主题——朱雀
================

“朱雀（rosefinch）”是一款基于\ `Twitter Bootstrap`__\ 的\ `Sphinx`__\ 主题，它集成了由\ `@ethantw`__\ 开发的“\ `汉字标准格式`__\ ”CSS框架，从而优化了汉字的网页显示效果。

.. note::

   本主题尚在开发中，暂不推荐使用。

.. compound::

   “朱雀”这个名字取自该主题的三个要素：

   *   希腊神话怪物斯芬克斯（Sphinx）
   *   鸟（Twitter）
   *   中文文档优化

主题选项
========

Rosefinch主题的选项包括：

``sidebar_enabled``
    是否开启侧边栏。取值：

    *   ``true``\ ：开启
    *   ``false``\ ：关闭

    默认为\ ``true``\ 。

``sidebar_position``
    侧边栏位置，当\ ``sidebar_enabled``\ 为\ ``false``\ 时该选项无效。取值：

    *   ``left``\ ：左侧
    *   ``right``\ ：右侧

    默认为\ ``right``\ 。

``han_enabled``
    是否开启简/繁/日汉字显示效果优化。取值：

    *   ``true``\ ：开启
    *   ``false``\ ：关闭

    默认为\ ``true``\ 。

``han_indent``
    是否开启汉字首行缩进，当\ ``han_eanbled``\ 为\ ``false``\ 时无效。取值：

    *   ``true``\ ：开启
    *   ``false``\ ：关闭

    默认为\ ``true``\ 。

``search_enabled``
    是否开启搜索功能。取值：

    *   ``true``\ ：开启
    *   ``false``\ ：关闭

    默认为\ ``false``\ 。

    .. note::

        由于汉字分词功能尚未开发，暂时禁用本主题的搜索功能。对于部署到线上的文档，可以考虑利用Google的site search代替Sphinx的搜索功能。

__ http://twitter.github.com/bootstrap/
__ http://sphinx.pocoo.org/
__ http://twitter.com/ethantw/
__ http://ethantw.net/projects/han/
