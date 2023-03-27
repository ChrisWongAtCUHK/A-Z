## A
* AppCmd.exe
  - [Listing a Specific Object](https://learn.microsoft.com/en-us/iis/get-started/getting-started-with-iis/getting-started-with-appcmdexe#listing-a-specific-object)

## B
* [Brackers](https://brackets.io/)

## C
* Cross-Site Request Forgery
  - [Cross-Site Request Forgery Prevention Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Cross-Site_Request_Forgery_Prevention_Cheat_Sheet.html#cross-site-request-forgery-prevention-cheat-sheet)
* Command
  - [[ Day 9 ] 初探設計模式 - 命令模式 ( Command Pattern )](https://ithelp.ithome.com.tw/articles/10204425) 
* CSS
  - [Margins](https://www.w3schools.com/css/css_margin.asp)

## D
* [Decorator Design Pattern](https://sourcemaking.com/design_patterns/decorator)
* [DNS](https://www.pcmag.com/encyclopedia/term/dns)

## E
* egrep
  - [What is egrep](https://pediaa.com/difference-between-grep-and-egrep/#egrep)
  
## F
* Flyweight Design Pattern
  - [The Flyweight Pattern Explained and Implemented in Java | Structural Design Patterns | Geekific](https://www.youtube.com/watch?v=qscOsQV-K14)

## G
* grep
  - [250+ TOP MCQs on Grep Command and Answers Quiz](https://engineeringinterviewquestions.com/mcqs-on-grep-command-1-answers/)
* git
  - [修改分支的名稱](https://backlog.com/git-tutorial/tw/reference/branch.html#sec3)
    + [Rename a branch](https://github.com/ChrisWongAtCUHK/git-learning-notes/commit/56135f36f13ac2340ee33c3601b01c4895ee21de)
  - [Git tag](https://www.atlassian.com/git/tutorials/inspecting-a-repository/git-tag#:~:text=Tagging%20is%20generally%20used%20to,no%20further%20history%20of%20commits.)

## H
* Hamming Code
    - [Hamming Code in Computer Network](https://www.geeksforgeeks.org/hamming-code-in-computer-network/)

## I
* Inotify
    - [inotifywait的安装及基本使用] (https://blog.csdn.net/qq_37788558/article/details/104985262)
* [Index Scan Vs. Index Seek in SQL Server](https://www.dbblogger.com/post/sql-server-performance-tuning-index-scan-vs-index-seek)

## J
* [jabba] (https://github.com/shyiko/jabba#usage)
* Java
  - Lombok
    + [五分鐘學會 Lombok 用法](https://kucw.github.io/blog/2020/3/java-lombok/)  
* [JVM (Java Virtual Machine) Architecture](https://www.javatpoint.com/jvm-java-virtual-machine)
* [jq](https://stedolan.github.io/jq/)
* Javascript
  - [Proxy](https://yucj.gitbooks.io/ecmascript-6/content/docs/proxy.html) 

## K
* Kotlin
    - [Explore the layout editor](https://developer.android.com/codelabs/build-your-first-android-app-kotlin#3)
    - [Kotlin 中文教程2023](https://www.youtube.com/playlist?list=PLsEC4qT8YxBI3WSShX8lAkNifboda7y-S)

## L
* Lazy Quantifier
    - https://www.rexegg.com/regex-quantifiers.html#lazy_solution
    - https://www.youtube.com/watch?v=bbZveyqVP40

## M
* Merge Sort
    - [Merge Sort Algorithm](https://www.geeksforgeeks.org/merge-sort/)
    - [.NET Fiddle](https://dotnetfiddle.net/IzReip)
* Multimedia Messaging Service(MMS)
  - [What is MMS(Multimedia Messaging Service)? ](https://www.geeksforgeeks.org/what-is-mmsmultimedia-messaging-service/)

## N
* nohup
  - [一分钟了解nohup和&的功效](https://blog.csdn.net/hl449006540/article/details/80216061)
* [NaN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/NaN)

## O
* Object Pool
    - [Object Pool Design Pattern](https://sourcemaking.com/design_patterns/object_pool)
* [Observer](https://refactoring.guru/design-patterns/observer)

## P
* Prototype
    - [Prototype 原型模式](https://ithelp.ithome.com.tw/articles/10221129)

## Q
* QR Code
    - [qrcode 7.4.2](https://pypi.org/project/qrcode/)
* Quotes
  - Coding like poetry should be short and concise. ― Santosh Kalwar   

## R
* [Reinforcement](https://en.wikipedia.org/wiki/Reinforcement)
* [【色彩學】色光三原色(RGB)與色料三原色(CMY)](https://www.gameislearning.url.tw/article_content.php?getb=5&foog=9998)
* React
  - [Hello World](https://legacy.reactjs.org/docs/hello-world.html)
  - [Introducing JSX](https://legacy.reactjs.org/docs/introducing-jsx.html)

## S
* Singleton
  - [[ Day 5 ] 初探設計模式 - 單例模式 (Singleton)](https://ithelp.ithome.com.tw/articles/10203092)
* SQL
  - [The SQL HAVING Clause](https://www.w3schools.com/sql/sql_having.asp)
* Svelte
  - [GETTING STARTED](https://svelte.dev/docs#before-we-begin) 

## T
* Tmux
  - [Tmux 使用教程](https://www.ruanyifeng.com/blog/2019/10/tmux.html)
* TSQL
  - Concate rows
```
DECLARE @t table
(
    Id int,
    Name varchar(10)
)
INSERT INTO @t
SELECT 1,'a' UNION ALL
SELECT 1,'b' UNION ALL
SELECT 2,'c' UNION ALL
SELECT 2,'d' 

SELECT ID,
stuff(
(
    SELECT ','+ [Name] FROM @t WHERE Id = t.Id FOR XML PATH('')
),1,1,'') 
FROM (SELECT DISTINCT ID FROM @t ) t
```

## U
* UML
  - [什么是统一建模语言（UML）？](https://www.visual-paradigm.com/cn/guide/uml-unified-modeling-language/what-is-uml/)
* Unix
  - [UNIX Introduction](http://www.ee.surrey.ac.uk/Teaching/Unix/unixintro.html) 

## V
* Vim
  - [Vim Cheat Sheet](https://vim.rtorr.com/)
  - Insert space with single keystroke
```
nnoremap <space> i<space><esc>
```

* Vue.js
  - Quick Start
    + [Creating a Vue Application](https://vuejs.org/guide/quick-start.html)

## W
* Web3
  - [Introduction to Web3](https://ethereum.org/en/web3/)
* Windows
  - [Keyboard shortcuts in Windows](https://support.microsoft.com/en-us/windows/keyboard-shortcuts-in-windows-dcc61a57-8ff0-cffe-9796-cb9706c75eec#WindowsVersion=Windows_11)

## X
* xargs
  - [12 Practical Examples of Linux Xargs Command for Beginners](https://www.tecmint.com/xargs-command-examples/)
  - xargs: illegal option -- d
```
echo '11@22@33' | xargs -d '@' echo
echo '11@22@33' | tr '@' '\0' | xargs -0 echo  # MacOS
``` 

## Y
* youtube-dl
    - [[YouTube] Unable to extract uploader id #31530](https://github.com/ytdl-org/youtube-dl/issues/31530)
* [YAML 1.2](https://yaml.org/)

## Z
* [ZIP](https://en.wikipedia.org/wiki/ZIP_(file_format))