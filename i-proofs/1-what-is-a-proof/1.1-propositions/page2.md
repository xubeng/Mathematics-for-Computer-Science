# 第二页

多个不正确的证明被发表了，包括了一个在十九世纪末存在了十年的证明，在它的错误被发现之前。最终，在1976年，一个生硬的证明被数学家Appel和Haken发现了，他们用复杂的计算机程序将四色图归类。该程序留下了数千张未归类的图片，这些图片被Haken和他的助手们手工归类了，这些助手还包括了Haken十五岁的女儿。

有理由怀疑该证明是否是合理的——该证明太大以至于不能不使用计算机检验它。没人能够保证计算机计算正确，也没有人热衷于用手重新检查数千张地图的四种颜色。二十年后，一个最[容易理解的四色定理证明](https://people.math.gatech.edu/\~thomas/FC/fourcolor.html)被发现了，尽管计算机也是必须的，用来检查成百上千张特殊图片的四色性。 $$^3$$

**命题 1.1.5（费马最后定理，又称费曼大定理）**

当整数n >2时，关于x，y，z的方程 $$x^n + y^n = z^n$$_没有正整数解。_

在他1630年前后读到的一本书中，费马声称找到一个该观点的证明，但是书本的边距没有足够的空间写下它。多年来，该定理被证明支持的n可以达到4，000，000，但是我们已经看到这无法增加我们对费马大定理支持所有n的自信心。毕竟，存在一个显然的相似性在费马大定理与欧拉的错误猜想。最终，在1994年，英国数学家Andrew Wiles在他的阁楼秘密且孤立地工作了七年后，给出了证明。他的证明没有适用于任意边界条件。 $$^4$$

最后，让我们来谈谈另一个简单陈述的命题，它的真相仍然未知。

**猜测 1.1.6（哥德巴赫猜想）**

_每个大于2的偶数是两个质数的和。_

哥德巴赫猜想可以追溯到1742年。众所周知，它支持所有的数直到10的18次方，但是直到今天，没有人知道它是否正确。

对于计算机科学家而言，一些最重要的需要去证明的事情是程序和系统的正确性——一个程序或者系统是否做它应该做的。众所周知，程序是任意出问题的，有一个茁壮成长的社区，研究者和实践者努力去证明程序的正确性。这些努力在证明CPU芯片的例子已经足够成功，现在这些努力的成果例行地被主要芯片制造商用来证明芯片的正确性并避免一些臭名昭著的、过去犯过的错误。

发展数学方法去验证程序和系统仍然是一个活跃的研究领域。我们将在[第五章](https://finit-xu.gitbook.io/msc20180606/proofs/5-induction)阐述这些方法中的部分。

> $$^3$$ 四色定理的证明的故事在一本备受好评的（非技术性的）畅销书中被讲述：“Four Colors Suffice. How the Map Problem was Solved.” Robin Wilson. Princeton Univ. Press, 2003, 276pp. ISBN 0-691-11533-8.
>
> $$^4$$ 事实上，Wiles的原始证明是错误的，但是他和他的几个合作伙伴在一年后利用了他的想法给出了正确的证明。这个故事是一本畅销书的主题，Fermat’s Enigma by Simon Singh, Walker & Company, November, 1997.
