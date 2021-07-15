# VueTutorial

一直在寻找Vue存在的意义，到底是一个东西很酷所以我们要去用，还是说大家都用，那我们要去用。除了重复和取代旧的方法，也不知道有什么别的“新魔法”没。所以，笔者一直对Vue存在疑惑。今天，我准备用Vue做个投票应用，看看Vue到底能减少多少代码量。

不准备用很复杂的例子，而是用最简单的例子。

实验项目是一个投票应用，poll-list.html展示待投票问题和问题的投票选项，用户点击投票选项单选按钮，然后点击提交按钮，就会打开polls-detail.html展示投票结果，然后点击返回又回到达poll-list.html，投票结果页面显示该问题的各个投票选项的票数。

做这个东西，差点要了我的老命，真想让这个可怕的经历快点结束。

下面是做出来的结果：

![](https://github.com/cs246810/VueTutorial/blob/master/vue_tutorial.gif)

有人说，最好是在vue中不要使用jquery。笔者在编写这个demo的过程中已经好几次惹不住想将jquery用起来了。我讨厌这个可怕的vue使用经历。

对了，最后`polls-detail.html`文件名应该为`poll-detail.html`，由于笔者想让这个可怕对经历快点结束，所以笔者不决定修改了。:musical_note:	