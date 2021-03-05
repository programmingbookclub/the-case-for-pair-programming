---
layout: default
title: A Pairing Session Template
permalink: /template
meta: A template to help guide your pair programming session
---

{% include article-top.html %}
# 結對會話模板
<!-- # A Pairing Session Template -->
> 幫助你如何引導一個結對會議的模板
<!-- > A template to help guide your pair programming session -->

這是您下一次配對會話的模板：
<!-- Here's a template for your next pairing session: -->

```text
[ ] 大聲同意高水平目標。
[ ] 將工作分解為少數幾個任務，並對它們進行優先排序。
[ ] 確定您的操作/導航角色的交換策略。
[ ] 配置 git 共享信用。
[ ] 消除干擾。
[ ] 工作。
[ ] 通過簡單的回溯來分析這個會議。
```



<!-- ```text
[ ] Agree on the high-level goal out loud.
[ ] Break the work into a handful of tasks and prioritize them.
[ ] Decide your driver/navigator swapping strategy.
[ ] Configure git to share credit.
[ ] Eliminate distractions.
[ ] Work.
[ ] Analyze the session with a mini retro.
``` -->

讓我們更多地討論每個步驟。
Let's talk more about each step.


## 1.大聲同意高水平目標

<!-- ## 1. Agree on the high-level goal out loud -->

大聲說出您希望高水平完成的工作。

<!-- State **out loud** what you hope to accomplish at a high level. -->

您可能會覺得兩個人不可能在沒有達成共識的情況下就開始配對，但這其實非常容易。
<!-- You wouldn't think it'd be possible for two people to start pairing without agreement about where they're headed, but it's surprisingly easy. -->


## 2.將工作分解為幾個任務（並優先處理它們）

<!-- ## 2. Break the work into a handful of tasks (and prioritize them) -->

值得嘗試將您的高層次目標分解為幾個較小的步驟。

<!-- It's worth trying to break your high-level goal into a handful of smaller steps. -->

這有很多好處：
<!-- This has a number of benefits: --> 

- 使目標不那麼嚇人。
<!-- - It makes the goal less intimidating. -->
- 您會更容易發現死胡同和陷阱。
<!-- - You'll spot dead ends and pitfalls more easily. -->
- 您可以按優先級對任務列表進行排序。
<!-- - You can sort your task list by priority. -->
- 您更有可能注意到完成任務 C 會使 B 變得更容易，並適當地重新排序。
<!-- - You're more likely to notice that accomplishing task C would make B easier, and reorder appropriately. -->
- 您可以根據當前的能量水平來決定一項任務。
<!-- - You can decide on a task based on your current energy levels. -->
- 它為您提供了一個清晰的地方來放置您在工作時想到的新任務。
<!-- - It gives you a clear place to put new tasks you think of while working. -->


[某些人](https://www.jamesshore.com/Agile-Book/pair_programming.html)喜歡將每個任務寫在自己的索引卡上。它們的堆放在導航者面面前。 每張卡片是執行中斷時提出筆記或想法的記錄地方。
<!-- [Some folks](https://www.jamesshore.com/Agile-Book/pair_programming.html) like to write each task on its own index card. The stack of them lives in front of the navigator. Each card can be a nice home for notes or ideas to bring up when there is a break in the action. -->


## 3.確定您的操作/導航角色的交換策略。
<!-- ## 3. Decide what will trigger a driver/navigator swap -->

除非您已經知道哪種方法最適合您，否則我強烈建議您使用番茄鐘技巧：
<!-- Unless you already know what works best for you, I strongly recommend the Pomodoro Technique: -->

1.編寫 25 分鐘。
<!-- 1. Code for 25 minutes. -->
2.休息 5 分鐘。
<!-- 2. Take a 5 minute break. -->
3.交換驅動角色。
<!-- 3. Switch drivers. -->

還有其他[配對編程樣式](/pair-programming-guide/styles)可以嘗試看看。
<!-- Other [pair programming styles](/pair-programming-guide/styles) exist if you wish to try them. -->


## 4.配置git共享成果
<!-- ## 4. Configure git to share credit -->

如果你們兩個共同貢獻了代碼，則兩個名字都應出現在提交中（commit）。
<!-- If two of you work on some code, both your names should appear on the commit. -->

這個git的[方便指南](https://help.github.com/articles/creating-a-commit-with-multiple-authors/)可以教你如何適當的設定 git。
<!-- Here's [a handy guide](https://help.github.com/articles/creating-a-commit-with-multiple-authors/) to configuring git appropriately. -->

Bonus：GitHub 本身就了解這一點，並且會在提交方面標註作者。

<!-- Bonus: GitHub understands this natively and will give you both credit for the commit. -->

有一些工具可以使此操作變得更加容易：
<!-- A few tools exist to make this even easier: -->

- [git pair](https://github.com/chrisk/git-pair)
- [git duet](https://github.com/git-duet/git-duet)
- [git-together](https://github.com/kejadlen/git-together)


## 5.消除干擾
<!-- ## 5. Eliminate distractions -->

對您的成員和您將要做的工作表示尊重。
<!-- Show respect for your pair and the work you're about to do. -->

- 不要帶手機。如果不行，請使其靜音。
<!-- - Don't bring your phone. Silence it if you do. -->
- 在要結對的電腦裝置上禁用通知。（開啟勿擾）
<!-- - Disable notifications on the machine you're using to pair. -->
- 關閉電子郵件/ Slack / Twitter / 聊天室（IRC）。切勿讓其他顯示器（螢幕）分散注意力。
<!-- - Close email/Slack/Twitter/IRC. Never keep something distracting on a second monitor. -->


## 6.工作
<!-- ## 6. Work -->

做吧！
<!-- Do the work! -->


不要忘記：
<!-- Don't forget: -->

- *導航時：* 問問題而不是提出要求。
<!-- - *When navigating:* ask questions rather than making demands. -->
- *操作時：* 指出您在做什麼以及為什麼。
<!-- - *When driving:* dictate what you're doing and why. -->
- 過度溝通方面的錯誤。
<!-- - Err on the side of over-communication. -->
- 休息一下。
<!-- - Take lots of breaks. -->
- 經常交換角色。
<!-- - Swap roles frequently. -->
- 做可能會起作用的最簡單的事情（目前為主）。
<!-- - Do the simplest thing that could possibly work (for now). -->
- 避免使用這些 [pairing antipatterns](/pair-programming-guide/antipatterns).
<!-- - Avoid these [pairing antipatterns](/pair-programming-guide/antipatterns). -->



## 7.進行迷你復古

<!-- ## 7. Perform a mini retro -->
會議結束後花幾分鍾思考一下這個過程中的經驗。
<!-- Spend a few minutes after your session reflecting on the experience. -->


首先，討論什麼事情是進展順利。
<!-- First, discuss what went well. -->


然後，考慮什麼會使下一個會議提高 1％。
<!-- Then, consider what would make the next session 1% better. -->


可能需要改進的地方：
<!-- Possible areas for improvement: -->

* **專心**：注意力分散了嗎？
<!-- * **Focus**: did distractions sneak in? -->
* **溝通**：長時間沒有說話嗎？
<!-- * **Communication**: were there long stretches of no talking? -->
* **緩步的進行**：會議在任何時候都感覺像是在受苦（grind）嗎？
<!-- * **Pacing**: did the session feel like a grind at any point? -->
* **責任劃分**：您是否很好地劃分了工作？
<!-- * **Division of responsibility**: did you split the work up well? -->
* **程式碼質量**：您的最終產品是否高質量？
<!-- * **Code quality**: was your end-product high-quality? -->


<!-- 
{% 
include navigation-buttons.html 
previous-title="Your First Pairing Session" 
previous-url="/pair-programming-guide/your-first-pairing-session"
next-title="Pair Programming Styles"
next-url="/pair-programming-guide/styles"
%}
 -->