---
layout: default
title: The Case for Pair Programming
permalink: /the-case-for-pair-programming
meta: An attempt to argue for the benefits of pair programming based on extensive personal experience.
---

# The Case for Pair Programming

<!-- _This article focuses on an argument based on the author's extensive experience with development and pairing. If you'd like to read a summary of scientific studies conducted on pair programming, check out our [Scientific Research Into Pairing](https://tuple.app/pair-programming-guide/scientific-research-into-pair-programming) article._ -->
_本文基於作者在開發和結對方面的豐富經驗，著重討論了一個論點。如果您想閱讀關於結對編程的科學研究的摘要，請查看我們的《結對研究》（https://tuple.app/pair-programming-guide/scientific-research-into-pair-programming ） 文章。_

## 用三句話解釋 In three sentences

團隊往往會隨著時間的流逝而放慢速度，因為他們積累了阻礙其進度的低於標準的代碼。

一對程序員傾向於比單獨工作的人產生更好的代碼。

結對的團隊通常會保持更快的交付速度。
<!-- Teams tend to ship slower over time because they accumulate sub-par code that impedes their progress.

A pair of programmers tends to produce better code than someone working alone.

Teams that pair often will maintain a fast shipping speed longer. -->


## 用三個描述解釋 In three paragraphs

一個運行緩慢的團隊幾乎總是這樣子的緩慢，因為它正在與低於標準的代碼庫抗衡。它花費大量時間來修復錯誤和回歸（regressions），並發現任何更改將會對系統產生令人驚訝的波動，需要進行深入研究才可以進行更改。您雖然可以撰寫使這些問題最小化的程式碼，但是這會困難得多。
<!-- A team that ships slowly almost always does so because it is fighting a sub-par codebase. It spends lots of time fixing bugs and regressions, and finds that changes ripple across the system in surprising ways, requiring deep exploration to make changes. You can write code that minimizes these problems, it's just much harder. -->

結對編程帶來了更多的知識產出以應對這一挑戰。通過兩雙眼睛，可以更早地發現錯誤。只要動動兩個腦袋，就可以找到更多有創意的解決方案。因為有人看顧著，貪方便走捷徑的次數也減少了（也減少了分心的煩惱）。
<!-- Pair programming brings more intellectual firepower to bear on this challenge. With two sets of eyes, bugs are caught earlier. With two brains to storm, more creative solutions can be found. With someone always watching, fewer corners are cut (and fewer distractions are indulged in). -->

通過結對編程來投資更高質量的程式碼會導致更好的代碼庫，從而使以後的開發更快地進行。

<!-- 
Investing in higher-quality code through pair programming leads to a better codebase, which allows future development to proceed faster.
 -->


## 分為三部分
<!-- ## In three long sections  -->

### 是什麼實際上減慢了開發速度？
 <!-- ### What actually slows down development? -->

回答此問題的最佳方法是查看那些交付緩慢的團隊花費大量時間來做什麼事情：
<!-- The best way to answer this is to look at what teams that ship slowly spend a lot of time doing: -->

* **修復回歸問題。** 行動緩慢的團隊通常會破壞以前可以使用的功能（而且不會注意到）。
<!-- * **Fixing regressions.** Slow teams often break previously-working features (without noticing it). -->

* **修復新的錯誤。** 緩慢的團隊無法涵蓋新功能中的所有極端情況，它們往往在 “完成” 並導入 “Production”後才會發現它們。
<!-- * **Fixing fresh bugs.** Slow teams fail to cover all the edge cases in new functionality, and tend to discover them once they're "done" and in production. -->


* **對抗糟糕的架構。** 緩慢的團隊建立在搖搖欲墜的基礎上。當發現架構很差時，他們不會硬著頭皮去解決它。
<!-- * **Fighting bad architecture.** Slow teams build on shaky foundations. When the architecture is discovered to be poor, they don't bite the bullet and fix it.  -->


* **重寫。** 緩慢的團隊發現他們的項目品質下降到了一個質量水平，在這個水平上，理解和更改比扔掉所有東西然後重新開始變得更加困難。
<!-- * **Rewrites.** Slow teams find their projects sink to a quality level where comprehension and changes become harder than throwing everything away and starting again. -->



* **分心。** 緩慢的團隊經常被會議和社交媒體分心。
<!-- * **Being distracted.** Slow teams are frequently distracted by meetings and social media.  -->

### 結對編程如何提供幫助？
<!-- ### How can pair programming help? -->


* **回歸。** 良好的測試套裝可以防止回歸問題。大多數人都知道他們應該編寫測試，但並不能始終如一地進行。在一對測試中，測試水平接近於所參與的兩個開發人員的最大能力。
<!-- * **Regressions.** Regressions are preventable with a good test suite. Most folks know they should be writing tests, but don't do it consistently. In a pair, the level of testing trends towards the maximum of the two developers involved. -->


* **修復新漏洞。** 漏洞往往隱藏在未經考慮的邊界條件中。在一組結對中，一個開發人員在另一位撰寫時明確地承擔了考慮這些極端情況的任務，承擔了適當處理這些事情的機會。
<!-- * **Fixing fresh bugs.** Bugs tend to hide in unconsidered edge cases. In a pair, one developer is explicitly tasked with thinking about these edge cases while the other types, increasing the chances they're handled properly. -->


* **對抗糟糕的系統架構。** 當兩個人自動考慮每個系統架構的決策時，團隊將傾向於找到更好的解決方案。
<!-- * **Fighting bad architecture.** When every architectural decision is automatically considered by two people, teams will tend to find superior solutions. -->


* **重寫。** 這件事可能仍然會發生，但是因為有了更高水準，就只會在需要的使用。
<!-- * **Rewrites.** This might still happen, but with a higher quality bar, it'll be longer before it's necessary. -->


* **分心。** 沒有任何事情比一個坐在電腦旁邊的人更能夠破壞您的滑 Twitter 的習慣。
<!-- * **Being distracted.** Nothing like a person at your desk to break your Twitter habit.  -->




### 我們應該如何開始？

查閱有關[您的第一次結對](02-your-first-pairing-session.md)的指南。

<!-- ### How should we get started?

Check out our guide on [your first pairing session](your-first-pairing-session). -->

[Next: Your first Pairing session](https://blog.csdn.net/weixin_34221276/article/details/88981836)