===============
Django 简介
===============

.. image:: ../_static/django.jpg
    :align: right

**Django** 是一个开源的 Web应用框架，由 *Python* 编写。采用了 MVT 的软件设计模式，即 模型 ``Model`` ，视图 ``View``  和 模板 ``Template`` 。




Django 是什么?
=================




Django 起源
===============

Django 从一个非常实际的需求成长而来：World Web 是一家新闻网站，负责在新闻截止期限内建立密集的 Web 应用程序。在快节奏的新闻编辑室，World Online 往往需要几个小时内将一个复杂的 Web应用程序从概念推向发布上线。

在 2003 年秋季，世界在线开发者（Adrian Holovaty 和 Simon Willison）放弃使用 PHP 而开始使用 Python 开发网站。当他们构建了密集的，强互动型的网站时，他们开始提取一个通用的 Web 开发框架，使他们可以更快地构建 Web 应用程序。

在 2005 年夏天，World Online 决定开源 Django。`如果没有大量的开源项目 - “Apache”，“Python” 和 “PostgreSQL” 等等，Django 是不可能完成的 - 我们很高兴能够回馈一些东西给开源社区。`

在 2008 年 9 月发布了第一个正式版本 1.0。

.. code-block:: python
    :caption: Code can.
    :linenos:

    def nihao():
        print(1)
        print(1)
        print(1)
        .. 这是一个注释吧
        print(1)
        print(1)
