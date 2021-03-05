---
layout: default
title: Pair Programming Styles
permalink: /styles
---


# 結對編程
<!-- title: Pair Programming Styles -->


## 驅動程序/導航器
<!-- ## Driver/Navigator -->


可能是最常見的配對類型。如果您是新手，這是一個不錯的起點。
<!-- Probably the most common type of pairing. This is a good place to start if you're new. -->


驅動程序鍵入代碼，並專注於當前任務。
<!-- The driver types the code and stays focused on the current task.  -->

導航員要向前思考，仔細考慮案例，發現錯誤，提出重構建議，提出很好的問題，保持精簡。

<!-- The navigator thinks ahead, ponders edge cases, spots bugs, suggests refactorings, asks good questions, stays zoomed out. -->

不要忘記定期更換角色。

<!-- Don't forget to switch roles regularly. -->

_（即將推出：有關良好駕駛和導航的指南。）_
<!-- _(Coming soon: guides on driving and navigating well.)_ -->



要查看這種樣式的實際效果，請查看[Pairing On Elixir，Phoenix和Elm]（/ pair-programming-guide / elixir-phoenix-elm）。
<!-- To see this style in action, check out [Pairing On Elixir, Phoenix, and Elm](/pair-programming-guide/elixir-phoenix-elm). -->

## 乒乓
<!-- ## Ping pong -->

如果您和您的一對練習TDD，這是一個不錯的選擇。
<!-- This is a great option if you and your pair practice TDD. -->

您肯定要為此使用兩個鍵盤（或[Tuple]（https://tuple.app）之類的遠程配對應用程序）。
<!-- You'll definitely want two keyboards for this one (or a remote pairing app like [Tuple](https://tuple.app)). -->

這是循環執行直到完成的流程：
<!-- Here's the flow, looped until you're done: -->



1. 人員1編寫失敗的測試。
<!-- 1. Person 1 writes a failing test. -->
2. 第二個人通過。
<!-- 2. Person 2 makes it pass. -->
3. 人員2編寫失敗的測試。
<!-- 3. Person 2 writes a failing test. -->
4. 人1通過。 
<!-- 4. Person 1 makes it pass. -->

這是一個很好的選擇，因為工作是自然劃分的，並且無需練習經常更換驅動程序的紀律。

<!-- This is a great option because the work is naturally divided, and there's no need to practice the discipline of swapping drivers often. -->

三項建議：
<!-- Three recommendations: -->

1. 有時編寫測試要比使測試通過的代碼花費更多的時間，反之亦然。不用擔心隨著時間的流逝，打字所花費的時間將會平均化。
<!-- 1. Sometimes it will take much longer to write the test than the code that makes it passes, or vice-versa. Don't worry about it. Time spent typing will even out over time. -->
2. 嘗試編寫一個_minimal_失敗的測試，以及將使它通過的_smallest_數量的代碼。此刻此刻很容易忘記。
<!-- 2. Try to write a _minimal_ failing test, and the _smallest_ amount of code that will make it pass. This is easy to forget in the moment. -->
3. 當事情變綠時，別忘了花一些時間進行重構。
<!-- 3. Don't forget to spend some time refactoring when things are green. -->

想要看到這種風格嗎？查看[TDD乒乓球配對]（/ pair-programming-guide / tdd-ping-pong-ruby）。
Want to see this style in action? Check out [TDD Ping-Pong Pairing](/pair-programming-guide/tdd-ping-pong-ruby).

## 堅強的風格
<!-- ## Strong style -->

這似乎是瘋狂的，但是為了完整起見，我們在這裡包括了它：
<!-- This seems like madness, but we're including it here for completeness: -->

> 這種配對方式的黃金法則是：“一個想法要從你的頭腦進入計算機，它必須經過別人的手”
<!-- > The golden rule for this style of pairing is: "For an idea to go from your head into the computer it MUST go through someone else's hands" -->



[本文]（http://llewellynfalco.blogspot.com/2014/06/llewellyns-strong-style-pairing.html）擁有更多詳細信息。
<!-- [This article](http://llewellynfalco.blogspot.com/2014/06/llewellyns-strong-style-pairing.html) has more details. -->

{% 
include navigation-buttons.html 
previous-title="A Pairing Session Template" 
previous-url="/pair-programming-guide/template"
next-title="Pair Programming Antipatterns"
next-url="/pair-programming-guide/antipatterns"
%}