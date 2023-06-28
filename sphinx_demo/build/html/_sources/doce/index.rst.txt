
=========
res文本笔记
=========

自动编译
=============

|   **服务器上的指令是：** 
::

    sphinx-autobuild source build/html -H 0.0.0.0 -p 7000

|   **windows上的指令:** 
:: 
    
    sphinx-autobuild source  build/html


模块
=========

+ 代码模块
.. code:: python

  def my_function():
      "just a test"
      print 8/2

.. code-block:: c
    :linenos:
    :emphasize-lines: 3,6

    void foo()
    {
        int i;

        for(i=0; i<10; i++)
            printf("i: %d\n", a);
    }

.. code-block:: console
    :linenos:       

    $ ls
    $ uname -a

.. code-block:: shell

    echo "Hello World!";

+ 数学模块
  
.. math::

  α_t(i) = P(O_1, O_2, … O_t, q_t = S_i λ)

+ 名言模块
.. epigraph::

   No matter where you go, there you are.

   -- Buckaroo Banzai


文本块
=======

::

    for a in [5,4,3,2,1]:   # this is program code, shown as-is
        print a
    print "it's..."
    # a literal block continues until the indentation ends

段落跳转
=======

 段落格式_


标题1
=============

标题2
-------------

标题3
`````````````

标题4
'''''''''''''



字体格式
==========
1. 斜体的两种写法：*text* 和 :emphasis:`text`

2. 红字白框的效果字体: ``text`` 和 :literal:`text`

3. 加粗字体: **text**


段落格式
=========

* 段落符号是 *
* 段落符号开头符号可以是 "*","+" "-"

-  段落符号是r -
- 段落符号开头符号可以是 "*", "+", or "-".

+ 段落符号是 +
+ 段落符号开头符号可以是 "* + -"


1. This is an enumerated list.
2.  numbers, letters, or roman numerals.
3.  arcbic numbers, letters, or roman numerals 

a. 111111
b. 22222
c. 33333
d. 44444

表格形式
========

+------------+------------+-----------------+
| 时间       | 地点       |  人物           |
+============+============+=================+
| 2023.02    | London     | justin bieber   |
+------------+------------+-----------------+

=== ==== ====
 1    2   3
=== ==== ====
22   222  222
=== ==== ====


提示框
=========

.. note:: 注解注解


.. DANGER:: 危险危险
   
.. admonition:: 提示框标题

   内容内容.

.. sidebar:: 侧边提示框标题
   :subtitle: 提示框

   内容内容

图片格式
=========


.. image:: /image/maliao.gif
   :height: 400px
   :width: 400 px
   :scale: 50 %
   :alt: alternate text
   :align: center


.. figure:: /image/changshaxu.jpg
   :scale: 10


.. figure:: /image/changshaxu.jpg
   :scale: 50 %
   :alt: map to buried treasure

列表模块
==============

:Date: 2023-02-21
:Version: 1
:Authors: - Me
          - Myself
          - I
:Indentation: Since the field marker 
:Parameter i: integer


Since the field marker may be quite long, the second and subsequent
lines of the field body do not have to line upwith the first line, but they must be indented relative to the
field name marker, and they must line up with each other.






term 1
    Definition 1.

term 2
    Definition 2, paragraph 1.

    Definition 2, paragraph 2.

term 3 : classifier
    Definition 3.

term 4 : classifier one : classifier two
    Definition 4.

\-term 5
    Without escaping, this would be an option list item.


1. Item 1 initial text.

   a) Item 1a.
   b) Item 1b.

2. a) Item 2a.
   b) Item 2b.



.. topic:: Topic Title

    内容

"To Ma Own Beloved Lassie: A Poem on her 17th Birthday", by
Ewan McTeagle (for Lassie O'Shea):

    .. line-block::

        Lend us a couple of bob till Thursday.
        I'm absolutely skint.
        But I'm expecting a postal order and I can pay you back
            as soon as it comes.
        Love, Ewan.






