## A
* AppCmd.exe
  - [Listing a Specific Object](https://learn.microsoft.com/en-us/iis/get-started/getting-started-with-iis/getting-started-with-appcmdexe#listing-a-specific-object)
* AutoHotkey
  - [EnvGet](https://www.autohotkey.com/docs/v2/lib/EnvGet.htm)
  - FormatTime
    + [Examples](https://www.autohotkey.com/docs/v2/lib/FormatTime.htm#Examples) 
* [Availability heuristic](https://en.wikipedia.org/wiki/Availability_heuristic)
  - [**What is the availability heuristic?**](https://www.scribbr.com/research-bias/availability-heuristic/#:~:text=sub%2Doptimal%20choices.-,What%20is%20the%20availability%20heuristic%3F,is%20most%20available%20to%20us.)
  **The availability heuristic** (or **availability bias**) is a type of cognitive bias that helps us make fast, but sometimes incorrect, assessments. It involves relying on information that comes to mind quickly or is most available to us. 

## B
* Bandizip
  - [Command Line Parameters](https://www.bandisoft.com/bandizip/help/parameter/)
* [Brackets](https://brackets.io/)
* bzip2
  - [Compressing directory with bzip2](https://www.linuxquestions.org/questions/linux-newbie-8/compressing-directory-with-bzip2-336204/) 
    + create a tar archive, then bzip2 compress the archive:
    ```
    tar -cf file.tar dir && bzip2 file.tar
    ```
    + or do this in one step:
    ```
    tar -cjf file.tar.bz2 dir
    ```
* [Breadcrumbs In Web Design: Examples And Best Practices](https://www.smashingmagazine.com/2009/03/breadcrumbs-in-web-design-examples-and-best-practices/)

## C
* Cross-Site Request Forgery
  - [Cross-Site Request Forgery Prevention Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Cross-Site_Request_Forgery_Prevention_Cheat_Sheet.html#cross-site-request-forgery-prevention-cheat-sheet)
  -  [[Day9] - CSRF(Cross Site Request Forgery)](https://ithelp.ithome.com.tw/articles/10241830)
* Command
  - [[ Day 9 ] 初探設計模式 - 命令模式 ( Command Pattern )](https://ithelp.ithome.com.tw/articles/10204425) 
* CSS
  - [Margins](https://www.w3schools.com/css/css_margin.asp)

## D
* Database
  - [[Day 17] Database Transaction & ACID - (2)](https://ithelp.ithome.com.tw/articles/10247034)
    + **Atomicity** - each statement in a transaction (to read, write, update or delete data) is treated as a single unit. Either the entire statement is executed, or none of it is executed. This property prevents data loss and corruption from occurring if, for example, if your streaming data source fails mid-stream.
    + **Consistency** - ensures that transactions only make changes to tables in predefined, predictable ways. Transactional consistency ensures that corruption or errors in your data do not create unintended consequences for the integrity of your table.
    + **Isolation** - when multiple users are reading and writing from the same table all at once, isolation of their transactions ensures that the concurrent transactions don't interfere with or affect one another. Each request can occur as though they were occurring one by one, even though they're actually occurring simultaneously.
    + **Durability** - ensures that changes to your data made by successfully executed transactions will be saved, even in the event of system failure.
  - [[Day 18] Transaction 併發錯誤與隔離層級 - (1)](https://ithelp.ithome.com.tw/articles/10247232)
    + **Dirty Read** A dirty read occurs when a transaction reads data that has not yet been committed.
    + **Non-repeatable Read** A nonrepeatable read occurs when a transaction reads the same row twice but gets different data each time.
    + **Phantom Read** A phantom is a row that matches the search criteria but is not initially seen.
  - [[Day 19] Transaction 併發錯誤與隔離層級 - (2)](https://ithelp.ithome.com.tw/articles/10247875)
    + **Read Uncommitted** – In this level, one transaction may read not yet committed changes made by other transactions, thereby allowing dirty reads. At this level, transactions are not isolated from each other.
    + **Read Committed** – This isolation level guarantees that any data read is committed at the moment it is read. Thus it does not allow dirty read. The transaction holds a read or write lock on the current row, and thus prevents other transactions from reading, updating, or deleting it.
    + **Repeatable Read** – This is the most restrictive isolation level. The transaction holds read locks on all rows it references and writes locks on referenced rows for update and delete actions. Since other transactions cannot read, update or delete these rows, consequently it avoids non-repeatable read.
    + **Serizable** – This is the highest isolation level. A serializable execution is guaranteed to be serializable. Serializable execution is defined to be an execution of operations in which concurrently executing transactions appears to be serially executing.
* [DBeaver 介面語言](https://blog.tenyi.com/2018/01/dbeaver.html)
* [What is DBF File Extension? How to Open DBF?](https://www.whatisfileextension.com/dbf/)
* [Decorator Design Pattern](https://sourcemaking.com/design_patterns/decorator)
* Design Pattern
  + [Factory Method](https://refactoring.guru/design-patterns/factory-method)
  + [Iterator Design Pattern](https://sourcemaking.com/design_patterns/iterator)
* .Net
  + [extern (C# Reference)](https://learn.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/extern) 
* [DNS](https://www.pcmag.com/encyclopedia/term/dns)
* Docker
  + Run CentOS 8 in a docker container
    ```
    $docker pull centos:centos8
    $docker run -it --name centos8server centos:centos8 /bin/bash
    ```
    ```
    $docker exec -it centos8server /bin/bash
    ```
  + [Container 應用](https://ithelp.ithome.com.tw/articles/10242637)

## E
* egrep
  - [What is egrep](https://pediaa.com/difference-between-grep-and-egrep/#egrep)
  
## F
* Flyweight Design Pattern
  - [The Flyweight Pattern Explained and Implemented in Java | Structural Design Patterns | Geekific](https://www.youtube.com/watch?v=qscOsQV-K14)
* ffmpeg
  ```
  # convert from 10s with duration 5s to gif
  $ ffmpeg -i input.mp4 -c:v gif -f gif -ss 00:00:10 -t 5 output.gif
  ```

## G
* Golang
  - [Map vs Struct in GOlang (When to use)](https://articles.wesionary.team/map-vs-struct-in-golang-when-to-use-b0b66446627a)
  - [Pointer receivers](https://go.dev/tour/methods/4) 
* grep
  - [250+ TOP MCQs on Grep Command and Answers Quiz](https://engineeringinterviewquestions.com/mcqs-on-grep-command-1-answers/)
  - [Grep Command In Unix With Simple Examples](https://www.softwaretestinghelp.com/grep-command-in-unix/)
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
  - [8 ways to use the Spread operator in JavaScript.](https://javascript.plainenglish.io/8-ways-to-use-spread-operator-in-javascript-b66fcf016efe)
  - [JavaScript Anonymous Functions](https://www.javascripttutorial.net/javascript-anonymous-functions/)
  - [淺談 JavaScript 頭號難題 this：絕對不完整，但保證好懂](https://blog.techbridge.cc/2019/02/23/javascript-this/)
  - [Chain of Responsibility in JavaScript](https://betterprogramming.pub/chain-of-responsibility-in-javascript-21942601ed9c)
  - [Object.freeze() vs Object.seal() vs Object.preventExtensions()](https://javascript.plainenglish.io/object-freeze-vs-object-seal-vs-object-preventextensions-e78ef3a24201)

## K
* Kotlin
    - [Explore the layout editor](https://developer.android.com/codelabs/build-your-first-android-app-kotlin#3)
    - [Kotlin 中文教程2023](https://www.youtube.com/playlist?list=PLsEC4qT8YxBI3WSShX8lAkNifboda7y-S)

## L
* Lazy Quantifier
  - https://www.rexegg.com/regex-quantifiers.html#lazy_solution
  - https://www.youtube.com/watch?v=bbZveyqVP40
* Linux
  - Command 
    + [Linux ln command examples](https://linuxhint.com/linux-ln-command-examples/)
    + [wc](https://ss64.com/bash/wc.html)

## M
* Merge Sort
    - [Merge Sort Algorithm](https://www.geeksforgeeks.org/merge-sort/)
    - [.NET Fiddle](https://dotnetfiddle.net/IzReip)
* [Middleware](https://www.pcmag.com/encyclopedia/term/middleware)
* Multimedia Messaging Service(MMS)
  - [What is MMS(Multimedia Messaging Service)? ](https://www.geeksforgeeks.org/what-is-mmsmultimedia-messaging-service/)
* MySQL
  - [Dealing with MySQL nulls and unique constraint](https://medium.com/@aleksandrasays/dealing-with-mysql-nulls-and-unique-constraint-d260f6b40e60)
 
## N
* nohup
  - [一分钟了解nohup和&的功效](https://blog.csdn.net/hl449006540/article/details/80216061)
* [NaN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/NaN)
* [nslookup](https://ss64.com/bash/nslookup.html)

## O
* Object Pool
    - [Object Pool Design Pattern](https://sourcemaking.com/design_patterns/object_pool)
* [Observer](https://refactoring.guru/design-patterns/observer)

## P
* Prototype
    - [Prototype 原型模式](https://ithelp.ithome.com.tw/articles/10221129)
* Python
    - [Playwright Python Tutorial: Getting Started With Python End To End Testing](https://www.lambdatest.com/blog/playwright-python-tutorial/)

## Q
* QR Code
  - [qrcode 7.4.2](https://pypi.org/project/qrcode/)
* Quick Sort
  - [【Day26】[演算法]-快速排序法Quick Sort](https://ithelp.ithome.com.tw/articles/10278644)
* Quotes
  - Coding like poetry should be short and concise. ― Santosh Kalwar   

## R
* [Reinforcement](https://en.wikipedia.org/wiki/Reinforcement)
* [【色彩學】色光三原色(RGB)與色料三原色(CMY)](https://www.gameislearning.url.tw/article_content.php?getb=5&foog=9998)
* React
  - [Hello World](https://legacy.reactjs.org/docs/hello-world.html)
  - [Introducing JSX](https://legacy.reactjs.org/docs/introducing-jsx.html)
  - [【Day.07】React入門 - 簡介React、從class到Hook的發展歷史](https://ithelp.ithome.com.tw/articles/10241674)
  - [Storybook for React tutorial](https://storybook.js.org/tutorials/intro-to-storybook/react/en/get-started/)

## S
* Singleton
  - [[ Day 5 ] 初探設計模式 - 單例模式 (Singleton)](https://ithelp.ithome.com.tw/articles/10203092)
* SOLID Design Principles
  - Open-Closed principle
    + [Open-Closed Principle – SOLID Architecture Concept Explained](https://www.freecodecamp.org/news/open-closed-principle-solid-architecture-concept-explained/)   
* SQL
  - [The SQL HAVING Clause](https://www.w3schools.com/sql/sql_having.asp)
* SQL Server
  - [Clustered and nonclustered indexes described](https://learn.microsoft.com/en-us/sql/relational-databases/indexes/clustered-and-nonclustered-indexes-described?view=sql-server-ver16)
  - [SELECT - HAVING (Transact-SQL)](https://learn.microsoft.com/en-us/sql/t-sql/queries/select-having-transact-sql?view=sql-server-ver16)
  - [CREATE TABLE (Transact-SQL) IDENTITY (Property)](https://learn.microsoft.com/en-gb/sql/t-sql/statements/create-table-transact-sql-identity-property?view=sql-server-ver16)
  - [SQL Server Table Variable Example](https://www.mssqltips.com/sqlservertip/6039/sql-server-table-variable-example/)
  - [Docker Express: Running a Local SQL Server on Your M1 Mac](https://medium.com/geekculture/docker-express-running-a-local-sql-server-on-your-m1-mac-8bbc22c49dc9)
    ```
    $ docker run -e "ACCEPT_EULA=1" -e "MSSQL_SA_PASSWORD=MyPass@word" -e "MSSQL_PID=Developer" -e "MSSQL_USER=SA" -d -v $(pwd)/files:/home/mssql/files --name=mssql -p 1433:1433 mcr.microsoft.com/azure-sql-edge 
    $ docker exec -it mssql bash
    ```
  - SELECT
    + [SELECT - GROUP BY- Transact-SQL](https://learn.microsoft.com/en-us/sql/t-sql/queries/select-group-by-transact-sql?view=sql-server-ver16#column-expression) 
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
    + [類圖(Class Diagram)](https://www.visual-paradigm.com/cn/guide/uml-unified-modeling-language/what-is-uml/#class-diagram) 
* Unix
  - [UNIX Introduction](http://www.ee.surrey.ac.uk/Teaching/Unix/unixintro.html) 
* [User Experience or UX Design](https://www.geeksforgeeks.org/user-experience-or-ux-design/)

## V
* Vim
  - [Vim Cheat Sheet](https://vim.rtorr.com/)
  - Insert space with single keystroke
  - [Vim has a Terminal Mode!](https://gist.github.com/mahemoff/8967b5de067cffc67cec174cb3a9f49d)

```
nnoremap <space> i<space><esc>
```
  - [How to open multiple files(as tabs) with single command? | VIM Editor](https://www.youtube.com/watch?v=lTWpBsb7EnI&list=PLpqQbpeQxfW0eJK-LSEzuEeC1u5vsQOUO&index=4)

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
* XSS
  - [Reflected XSS](https://portswigger.net/web-security/cross-site-scripting/reflected)
  - [Stored XSS](https://portswigger.net/web-security/cross-site-scripting/stored)

## Y
* Y2K bug
  - [A lazy fix 20 years ago means the Y2K bug is taking down computers now](https://www.newscientist.com/article/2229238-a-lazy-fix-20-years-ago-means-the-y2k-bug-is-taking-down-computers-now/)
* youtube-dl
  - [[YouTube] Unable to extract uploader id #31530](https://github.com/ytdl-org/youtube-dl/issues/31530)
* [YAML 1.2](https://yaml.org/)

## Z
* [ZIP](https://en.wikipedia.org/wiki/ZIP_(file_format))
* Zsh
  - [Oh My Zsh - a delightful & open source framework for Zsh](https://ohmyz.sh/)