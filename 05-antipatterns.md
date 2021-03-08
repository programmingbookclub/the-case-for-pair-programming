# 配對編程反模式
<!-- title: Pair Programming Antipatterns -->
> 結對編程時不應該做的事情。
<!-- meta: What you shouldn't do when pair programming. -->

可以通過避免不良結對來簡單地優良結對。
<!-- It's possible to pair well simply by avoiding pairing poorly.  -->


遠離這些常見錯誤，您將獲得成功的機會。
<!-- Stay away from these common mistakes and you'll up your chances of success. -->



## 對於導航員：
<!-- ## For navigators: -->

###跨越錯誤的步伐太快了
<!-- ### Leaping on errors too quickly -->

讓您的操作員有機會注意到他們自己的語法錯誤和錯別字。
<!-- Give your driver a chance to notice their own syntax errors and typos.  -->

不斷指出小錯誤會損害流程。包含您的和他的。這也可能使您的伴侶自覺。
<!-- Constantly pointing out small errors hurts flow. Yours _and_ theirs. It may also make your pair self-conscious. -->


請記住：您的工作是考慮全局，而不是在發現拼寫錯誤的單詞後立即指出它們。
<!-- Remember: your job is to consider the bigger picture, not to point out misspelled words as soon as you spot them. -->

### 提供低層級指令
<!-- ### Giving low-level instructions -->

如果您對操作者有建議，請以他們會理解的最高抽像水平進行交流。
<!-- If you have a suggestion for the driver, communicate it at the highest level of abstraction they'll understand. -->

如果發現自己在命令代碼（或者更糟的是，每次擊鍵），請停下來看看是否可以在更高層次上傳達您的想法。
<!-- If you find yourself dictating code (or worse, individual keystrokes), stop and see if you can communicate your idea at a higher level.  -->


如果失敗了，請稍作努力，以使您的想法得以勾勒。
<!-- If that fails, ask to drive for a bit to get your idea sketched out. -->


### 不帶鍵盤
<!-- ### Not bringing a keyboard -->


每次配對時都請帶上自己的鍵盤。開始之前將其接上電腦。
<!-- Bring your own keyboard to every pairing session. Plug it in before you start. -->


這使角色交換更加容易，並且允許您顯示而不是告訴您單詞何時失敗。
<!-- This makes swapping roles easier and allows you to show rather than tell when words fail. -->


擁有自己的滑鼠也很不錯，但不是必需的。 （要求某人單擊某些內容很容易，但是很難讓他們鍵入許多字符。）
<!-- Having your own mouse is nice too, but not as essential. (It's easy to ask someone to click on something, harder to get them to type many characters.) -->



##對於操作員：
<!-- ## For drivers: -->


###操作地太快
<!-- ### Driving too fast --> 

如果您精通編輯器，那麼移動起來就很容易，甚至是經驗豐富的導航員。
<!-- If you're highly proficient with your editor, it's easy to move fast enough to lose even experienced navigators. -->


除非您確定自己的領航員跟得上，否則請不要以最快的速度處理代碼。
<!-- Unless you're sure your pair is keeping up, don't manipulate code quite as fast as you're able.  -->


如果您決定要做什麼，這會有所幫助。
<!-- It helps if you dictate what you're doing. --> 

### 允許導航員分心
<!-- ### Allowing a checked-out navigator -->


太快地移動或做他們不太理解的事情，很容易使導航員失去注意力。
<!-- It's easy to lose your navigator's attention by moving too fast, or doing things they don't quite understand. -->


如果您感覺到結對的夥伴的注意力在漂移，請停止並同步。
<!-- If you get the sense that your pair's attention is drifting, stop and sync up.  -->


壞問題範例：“你明白這一點，對吧？”
<!-- A bad question: "You understand this, right?" -->


好問題範例：“其中哪一部分最難理解？”
<!-- A good question: "Which part of this is hardest to follow?" -->

**配對應包括持續的雙向溝通。** 如果您或您的導航員變得安靜，請停下來檢查。
<!-- **Pairing should involve constant two-way communication.** If you or your navigator has gone quiet, stop and check in. -->

### 不平等的螢幕
<!-- ### Unequal screen access -->

坐下來，使螢幕位於你們兩個之間。確保兩個人都能看到同樣的效果（考慮提高字體大小）。
<!-- Sit so that the monitor is __between__ the two of you. Make sure both of you can see it equally well (consider bumping up font sizes). -->

如果一個人被困在一邊，就會造成一種潛意識的不平等等級。
<!-- If one person is tucked off to the side, it will create a subconscious unequal hierarchy. -->

一對是一個單位。你們兩個都一樣重要。
<!-- A pair is a unit. Neither of you is more important. -->

### 不休息
<!-- ### Not taking breaks -->


結對是很耗腦的。甚至比普通編程還更嚴重。
<!-- Pairing is draining. Even more so than normal programming. -->



確保您有足夠的休息時間的一種好方法，是採用番茄鐘技巧。在開始之前，請考慮與您結對夥伴就首選工作達成共識，並確定長度。
<!-- A nice way to ensure you take adequate breaks is to employ the Pomodoro Technique. Consider agreeing on preferred work and break lengths with your pair before you start. -->

### 左耳進右耳出
<!-- ### Listening without hearing -->


很難同時聽和打字。
<!-- It's hard to listen and type at the same time. -->


如果您的導航員提出建議，請考慮將手從鍵盤上移開。更好的是：轉動並進行眼神交流。
<!-- If your navigator is making a suggestion, consider taking your hands off the keyboard. Even better: turn and make eye contact. -->

##  對彼此而言：
<!-- ## For both: -->


### 允許沒有生產價值的注意力分散
<!-- ### Allowing unproductive distractions -->

在開始配對之前，請禁用所有通知（在您的電腦和電話上）。
<!-- Before you start pairing, disable all notifications (on your computer _and_ phone).  -->



結對會議應該被完全為零的 Slack 通知或訊息中斷。如果一個人漏了，就道歉並確認已保持禁用。
<!-- A pairing session should be interrupted by exactly zero Slack notifications or text messages. If one slips through, apologize and disable future ones. -->


不要在其他螢幕上打開電子郵件。
<!-- Don't leave your email open on another monitor. -->


（即使沒有結對，也應執行上述操作。提高編程效率的最快方法是減少中斷。）
<!-- (You should do the above even when you're not pairing. The quickest way to improve programming productivity is to reduce interruptions.) -->


### 不交換角色
<!-- ### Not swapping roles -->


由於不同的原因，操作和導航都很費力。
<!-- Driving and navigating are draining for different reasons. -->


交換角色使您可以休息大腦的疲憊部位，並激活閒置的部位。
<!-- Swapping roles lets you rest the tired parts of your brain and activate the idle ones. -->


交換操作員是激發失去動力的結對會議的好方法。考慮設置一個計時器以指示每次切換的時間。
<!-- Swapping drivers is a great way to energize a pairing session that's losing steam. Consider setting a timer to indicate every time it's time to switch. -->

### 忘記這是一種技能
<!-- ### Forgetting it's a skill -->

結對編程是一項必須學習的技能。
<!-- Pair programming is a skill which must be learned. -->



起初您不會擅長此事，但是持續的練習的將帶來改善。
<!-- You will not be good at it at first, but consistent practice will yield improvements. -->


在經歷了艱難的初體驗後，請不要放棄。不要以為有經驗的開發人員會自動成為良好的配對夥伴。沒有練習就不要指望。
<!-- Don't give up after a difficult first experience. Don't assume experienced developers are automatically good pairing partners. Don't expect to be good without practice. -->


考慮在每個環節之後與您的同伴進行反思或尋求反饋。還有什麼更好的呢？
<!-- Consider reflecting with your pair or asking for feedback after each session. What could have been better? -->





{% 
include navigation-buttons.html 
previous-title="Pair Programming Styles" 
previous-url="/pair-programming-guide/styles"
next-title="Lesser-known Benefits"
next-url="/pair-programming-guide/lesser-known-benefits-of-pair-programming"
%}


