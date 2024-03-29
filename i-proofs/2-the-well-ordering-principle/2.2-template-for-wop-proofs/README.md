# 2.2 良序证明模板

更通常来讲，使用良序证明证明某些特性是有一个标准方法的，_**P**(n) _对于每个非负整数n都成立。这里有一个标准的方式组织这样一个良序证明：

使用良序原则证明“_**P**(n)_对于所有的n∈N都为真”：

* 定义集合_**C**_为_**P **_为真值的反例。具体来说，定义

                   C ::={n∈N | NOT(P(n)) 为真}.

      （记号{n | Q(n) }意思是“所有Q(n)成立时元素的集合。”见章节[4.1.4](https://finit-xu.gitbook.io/msc20180606/i-proofs/4-mathematical-data-types/4.1-sets/4.1.4-set-builder-notation)）

* 通过反证法假设_**C **_非空。
* 根据良序原理，集合_**C** _中存在最小元素n。
* 以某种方式引起矛盾——通常指明_**P**(n)_确实为真或者指明存在另一个_**C **_的成员小于_n_。这是证明任务中可变的部分。
* 得出C一定是空的结论，即没有反例存在。

