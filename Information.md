# 小白不走弯路完全速成

URL:[机器学习小白不走弯路完全速成经验和资料推荐（真干货）|一亩三分地机器学习版 (1point3acres.com)](https://www.1point3acres.com/bbs/thread-739215-1-1.html)

**直接看大厚书没用而且坚持不下来，所以上一些实践的课，再看一本书就OK了**

> 真正开始学机器学习的时候是在master时候上机器学习课程时候，那个老师带着我们把机器学习最常用的算法（最难的算法只是SVM）全部推导了一下，并且要求我们搭了除SVM，PCA的框架。但是，如果你现在让我再推导这些算法，我肯定不行，而且我感觉没必要记住推导过程和自己手推，很多算法能看得懂算法公式，大概懂得如何来的就行了。 上机器学习课时候，我自己买了本Kevin Murphy的 Machine Learning A Probabilistic Perspective 书，当时立志把这本书读完，但后面2年多次拿出来看，没几天就不看了，不是看不懂，是公式太多，看了也记不住，很多和我的research没有帮助。我觉得，这本书不适合学习用，只适合当作reference，在自己做research或者写paper要精确的reference时候去看相关的章节即可。我自己写第二篇paper时候要用Gaussian-mixture Model（GMM），我查相关的paper对GMM的定义都不是太清楚（大家都好像在避免什么），但这本书上面对GMM的定义就非常清楚，所以，我写公式时候直接按这本书的来写。

**书本推荐**

> 如果你只要1本书，那么我建议Hands-On Machine Learning with Scikit-Learn, Keras & Tensorflow。这本书很多人把它当作“圣经”。这本书如果可以完全掌握，机器学习和深度学习完全可以达到优秀的机器学习硕士毕业生水平和应付目前面试对机器学习和深度学习的面试题。学习这本书时候如果有一些公式不太懂，可以查阅网上资料。

> 如果你需要第2本书，我建议Mathematics for Machine Learning。你不用去啃厚书，因为厚书的效率低，很多内容陈旧和不太实用。这本书是你只要花功夫就可以精读完的，而且当你有了机器学习的数学基础，你再去学新的算法会不难的。

> 如果你还想买本书，那就是Murphy的 Machine Learning A Probabilistic Perspective。但这本书只适合当reference，不建议通读。第二版马上也会出来，是分基础版和高阶版2本。基础版就有800页，作者已经在他的Github里面放出基础版的PDF让读者去审稿纠错。 至于PRML和ESL，没有Murphy的全和新，作为Reference不是太全，作为学习的书又太多。我不建议使用。除非你这学期学校里的机器学习用的是这2本教材，那就使劲读，因为这可能是你最后一次花大量时间学习这2本书的机会。

**动手实践，看论文复现才是重点，而不是钻在数学上**

> 经验：如果学校有机器学习的研究生课程，那就果断去选。学校的课程可以帮助入门，但是学校的课只能帮助入门，要想深入，还得去啃书。如果没机会在学校选机器学习的课程，那就推荐看第一本书和第二本书，很多时候，机器学习难度只是数学表达式子上，你把数学表达式的含义搞懂就不难了。对绝大部分人（包括大部分机器学习的研究者）机器学习特别是深度学习部分，实践很重要，甚至比推导更重要，因为当你发文章时候，你需要复现别人的算法或跑别人的源码，这时候如果实践能力不行，复现都很难，更别提如何在别人的复杂模型上改进了。如果你目前做机器学习和深度学习研究，我建议也要多看有关自己研究领域的论文和源码，看多了自然有自己的想法 并且自己的工程能力也会提高。 不建议为了学机器学习去看一本本数学教材，那样做效率非常低，因为大部分内容你不会用到，而且很多地方缺少老师去讲解，很难搞得很清楚。你要清楚，机器学习是CS系，不是数学系，CS系侧重点和数学系不一样的。假如你真想在机器学习数学理论上有创新，我建议去学一个数学系的master 或者 机器学习理论研究的PhD。而不是自我陶醉去读很多数学系的书。人的精力都有限，不可能把所有知识都学个明白。即便我的导师（IEEE Fellow），只是在他的领域是专家，其他的最多也只是了解一下。码字不易，句句真实经验，如果有用，请加点大米。

# **ML资料路径**

URL：[机器学习`侠`练成记录 Becoming a Machine Learning Practitioner|一亩三分地机器学习版 (1point3acres.com)](https://www.1point3acres.com/bbs/thread-462348-1-1.html)

Why this post It’s an opinionated list of core skills that I found useful in the daily work of a machine learning practitioner, in the tech industry. I am not a researcher and am not interested in becoming one, so the list does not go in depth into any active research domain.  需要强调的是，我不是做ML科研的，也不想做科研，所以本文就是于业界做ML的大家交流讨论，并不打算深入任何科研领域，请做科研的大牛轻拍。 I’ll be maintaining this list just as I maintained the learning path for data science in the past here https://www.1point3acres.com/bbs/forum.php?mod=viewthread&tid=76429&extra=&page=1. It’s not meant to be exhaustive, and we probably don’t need to know them all. 另外这篇内容也并不会多完备。机器学习领域大牛很多，领域很广，应用更是广阔到难以尽数，所以不求尽善尽美，只是抛砖引玉，求交流学习。 Suggestions/discussions welcome.  本文适合什么人

## 0. Who is this for

This is a practitioner’s approach. Researchers: This post is not for you. 不是给ML方向做研究的人；牛人路过就好，不喜勿进。 Data analyst: you don’t need this. Read this instead: https://www.1point3acres.com/bbs ... 76429&extra=&page=1 Data scientist who’s more junior in modeling or focuses on causal inference: 3, some of 4. This list will give more resources: https://www.1point3acres.com/bbs ... 76429&extra=&page=1 Machine learning scientist: 2, 3, expert knowledge of 4, Machine learning engineer: 1, 2, some 3, good knowledge of 4, 5, some knowledge of 6 Machine learning systems engineer: 1, 2, maybe 3, some knowledge of 4, expert knowledge of 5 and 6

## 1. CS Fundamentals 计算机基础

Introduction to Python or Introduction to Java Data structure ( 地里关于Berkeley 61B的板块 or Coursera specialization ) Design and analysis of algorithms（ Coursera Part 1, Coursera Part 2）

Database (Stanford archived DB course or Using Database with Python) Discrete math (Coursera Discrete Math specialization) Operating System (Book: Modern Operating Systems)

## 2. Programming languages 编程语言

为什么与上一节计算机基础分开来说：因为老是遇到同学说我会numpy啊为什么你说我基础不行。。。。实际上是可以在不太懂基础的情况下楞刷题，或者写些基本能用的代码的。但是稍微深一点的地方会感觉基础知识的缺乏会让人难以在ML道路上上升到一定高度。 Must have :Python, Java 必须一门Python（因为ML好多framework就是python)，和一门compiled language. 仅仅只会python，作为scientist是够了，作为engineer就会有显著差距。 Good to have: C++ 不一定是必须的。但是如果做的工作对速度有比较强的要求，那还是需要会C++的 Will likely encounter at work: scala/go/js 这些看每家tech stack不一样，会有不同涉及。遇到了再学即可。 Will likely encounter in academic settings: Matlab/Octave, R, Julia 这些是学校里面用的多，我至今（2018年底）没看见公司里面用julia的。

## 3. Math Fundamentals 数学和统计基础

Linear algebra 线性代数，必须的 Calculus 这个大家应该都上过 Optimization 优化：必须的 Statistics 基础统计（不是概率论 which is also good to have，这里是特指统计） (real analysis and functional analysis might be useful, but is not required) 有空的话学实分析和泛函也可以，但是不是必须的

## 4. Machine Learning, from intro to advanced

这部分稍微区分一下从入门到进阶

### 4a. Intro 入门

- 这门课可能没有人不知道了 Introductiont to Machine Learning by Andrew Ng
- 这本书是ESL的简单版，作为直觉培养和思路练成，仍然是不错的，但是那里面的编程就很轻很轻了，真的只够本科生用 Very light but still a good book: an introduction to statistical learning
- 深度学习，也是Ng这课来入门还是不错的 Introudction to Deep Learning by Andrew Ng
- 另外个人比较喜欢Udacity的第一门旗舰课程讲AI的，基于斯坦福的一门本科生课程。会稍微设计一点比前几门入门课更宽广的概念，虽然很浅但是对了解domain很有好处。 Introduction to Artificial Intelligence by Udacity

### 4b. Advanced 进阶

- 前面几门主要还是supervised learning，下面这门稍微宽广一点，并不完全是ML，但是也是因此感觉对知识面和落地有帮助 Data mining & other topics: Mining Massive Data Sets http://web.stanford.edu/class/cs246/
- 这门课可惜没有录像，关于实战的部分讲的还是不错的，而且是其他课程都没有涉及到，但是工作里面的确需要的部分 Cornel course (slides only) adv ml http://www.cs.cornell.edu/courses/cs6780/2010fa/lectures.html
- Book: 经典ESL 不必多说，统计角度 Elements of Statistical Learning

经典不必多说，CS角度 Pattern Recognition and Machine Learning

- 下面看几个应用大方向
- Info retrieval & search engine 信息提取和搜索 Some intro here: https://www.searchtechnologies.com/blog/relevancy-ranking-301http://web.stanford.edu/class/cs276/ UIUC course slides https://github.com/SSQ/Coursera-UIUC-Text-Retrieval-and-Search-Engines-Lecture-Slides
- Recommender systems 推荐系统 Book: Recommender Systems: The Textbook by Charu Aggarwal
- Image: 图像识别，如今主要就是CNN了 Andrej版的CS231n堪称经典 stanford CS231n Convolutional Neural Networks for Visual Recognition
- NLP 自然语言处理 CS224n: Natural Language Processing with Deep Learning others to be added NLU 暂时不知道哪里有比较好的课
- Reinforcement Learning, Deep Reinforcement Learning 加强学习 (book and course TBD)
- Lots more stuff in DL here 经典课本（但是我觉得读起来还是蛮晦涩。。。不知道我是不是一个人）Deep learning book by Ian Goodfellow and Yoshua Bengio

之前学DL的时候的一些收集 看这里

### 4c. Frameworks

非深度学习，最常用的肯定就是 General ML framework: sci-kit-learn

深度学习的目前很多了 DL: Tensorflow(Keras), Caffe, Pytorch(Caffe2)

TF的看狗家自己的内容，或者Ng那个课；[Pytorch的看fast.ai](http://xn--pytorchfast-v790af4c.ai/) Up & coming 或者已经下去了的: theano, MXnet, dl4j

## 5. Scaling considerations: Big data, distributed systems etc 数据量大了面临的问题

做小数据ML（笔记本上跑跑regression or classification，产生个报告给别人看）严格来说算不上ML，其实主要只能算是modeling（统计建模） high dimensional data 是另外一个故事，这里先按下不提。 只说业界，面试会考系统设计的地方，需要用到的机器学习系统： 从最最小白的地方看起：（非科班同学不妨看看，科班的可以绕过） This blog post: thorough intro to distributed systems https://hackernoon.com/a-thorough-introduction-to-distributed-systems-3b91562c9b3c And this [🔗www.youtube.com](http://xn--www-3p23b.youtube.com/) System Design: 虽然这个是准备面试用的，但是作为大致入门也是差不多了 Grokking system design interview (for brushing up fundamentals and case studies) DDIA 堪称经典 Book Designing Data Intensive Applications : for an in-depth look, refer back to fundamental knowledge in OS

Distributed OLTP and OLAP [🔗www.youtube.com🔗www.youtube.com](http://xn--www-3p23b.youtube.com/)

## 6. ML Systems & Platforms 机器学习系统和平台

- 这门课还是可惜没有录像只有slides Adv ML systems (Cornell, slides only) http://www.cs.cornell.edu/courses/cs6787/2017fa/
- Book: 这本书我也只有翻过，还不知道到底多好 Building Intelligent Systems - A Guide to Machine Learning Engineering
- NIPS2018: to find some talks http://learningsys.org/nips18/schedule.html

### ML Systems 什么是机器学习系统

- Prod ML, paper 1 (tech debt) https://ai.google/research/pubs/pub43146,
- paper 2 (test score), https://ai.google/research/pubs/pub46555
- tbd

### ML Platforms 机器学习平台

- Google: TFX https://www.tensorflow.org/tfx/ & KDD talk https://www.kdd.org/kdd2017/papers/view/tfx-a-tensorflow-based-production-scale-machine-learning-platform
- Facebook: FB Learner flow https://code.fb.com/ml-applications/introducing-fblearner-flow-facebook-s-ai-backbone/
- Uber: Michelangelo https://eng.uber.com/scaling-michelangelo/ 深度学习 Horovod https://eng.uber.com/horovod/
- Linkedin: Pro ML https://twimlai.com/twiml-talk-200-productive-machine-learning-at-linkedin-with-bee-chung-chen/
- Airbnb: Bighead https://databricks.com/session/bighead-airbnbs-end-to-end-machine-learning-platform 居然缺logo 另外这个podcast很不错，建议不要错过 Podcast TwimlAI is featuring a lot of these systems lately, a fantastic listen https://twimlai.com/shows/