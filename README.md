# README

## 成立此项目的目的

1. 用于总结梳理知识体系（计算机专业知识，日后可能扩增其他内容的知识），知识库是内部知识库，旨在内部分享使用。
1. 用于记录每个人的进步过程。
    此项目其实类似于习惯进化，最终还是要靠自己自觉，但是有一个目标存在不至于每天颓废下去。  
    以我个人的经验来看，学习的痛苦其实很大程度在于决定要学习的那段时间。类似考试一样，开考前感觉就像处刑，考试期间其实痛苦并不这么大。
1. 养成一个健康良好的学习方式，以更好的心态应对未来的就业挑战。

## 知识库维护规则

1. 硬性规则：使用 markdown 语法编写，其实非常简单，半天即可学会 [markdown 语法](https://www.runoob.com/markdown/md-tutorial.html)。
1. 假如你想学习/整理某一些具体的知识到知识库，建议自己开一个 issue，指定给自己，这样相当于有一个目标一直在催你。
1. 不要直接 push 到 master 分支，自己新开分支，然后提交一个合并请求（Merge Request、MR）。
    > 不要直接 push 到 master 分支，自己新开分支，然后提交一个合并请求（Merge Request、MR）。  
    
    注意提交到远端时，一定要在 commit 中写清楚自己这次做了什么，而且注意最好只留下一个 commit（使用 git commit --amend）方便查看。  
    同时注意，MR 的描述中贴上对应的 issue 链接。
1. 如果感觉其他人的知识库中有内容不对，提一个 issue，然后 at 对应的人，这样就做到了双方的共同成长。
1. 目前知识库的分层暂时只做计算机专业技能，大概为：
    - `/base/*`：存放一些通用技能，例如《计算机网络》、《计算机组成原理》、《数据结构》、《设计模式》等。  
        考虑到前后端语言不同（比如数据结构的实现），可以分出 `/base/frontend` 和 `/base/backend`。
    - `/frontend`：前端专业技能。
    - `/backend`：后端专业技能。

## 如何让你的大脑就范

**慢一点**

不只是看看而已，停下来好好想一想，想的越多就越有可能学会并记住。欲速则不达。

**勤做练习，记笔记**

不要只是看着练习发呆，拿出笔写一写，画一画。

**上床睡觉之前不要看别的书了，至少不要看有难度的东西**

学习有一部分是在合上书之后才开始的，特别是要将知识长久地记住，不仅仅是靠看书就能完成的。
大脑也需要一段时间来做一些处理，如果在这段时间内向大脑中灌输了其他东西，那么刚才的东西就会被丢掉。

**喝水，而且要多喝点水**

能够提供充足的水，大脑才能有最佳表现，如果缺水（你在口渴之前可能就已经缺水了）学习能力就会下降。

**大声说出来**

说话可以刺激大脑的另一部分，如果你想看懂什么或者更加牢记，那么就要大声说出来，最好解释给其他人听。
在这个过程中，你可能会有一些新的认知，而这些是之前只看不说未曾发现的。

**听听大脑怎么说**

注意不要让大脑负荷太重了，如果发现自己开始浮光掠影地看，或者刚看的东西就忘记了，那么说明该休息了。
这个时候如果还一个劲往大脑里塞东西，对学习没有任何帮助，甚至还可能影响正常的学习。

**有点感觉**

为知识配上自己的说明，比如加点自己的笑话，有时候可能会有些蹩脚，但是总比没有好。

**设计一些东西**

将新知识运用到新的项目中，甚至重构旧的项目。应用和实践很重要。
