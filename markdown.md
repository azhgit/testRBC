# This is h1 title
***
這是內文喔這是內文喔
這是內文喔這是內文喔這是內文喔
這是內文喔這是內文喔這是內文喔這是內文喔這是內文喔這是內文喔

## This is h2
***
這是內文喔這是內文喔這是內文喔這是內文喔這是內文喔這是內文喔這是內文喔

> 這是引言
Markdown的目標是實現「易讀易寫」。
>
>Markdown不是要來取代HTML，甚至也沒有要和它相似，它的*語法種類*不多，只和HTML的一部分有關係，**重點**不是要創造一種更容易寫作HTML文件的語法，我認為HTML已經很容易寫了，Markdow的重點在於，它能讓文件更容易閱讀、編寫。HTML 是一種發佈的格式，Markdown是一種編寫的格式，因此，Markdown的格式語法***只涵蓋***純文字可以涵蓋的範圍。


Markdown不是要來取代HTML，甚至也沒有要和它相似，它的語法種類不多，只和HTML的一部分有關係，**重點**不是要創造一種更容易寫作HTML文件的語法，我認為HTML已經很容易寫了，Markdow的重點在於，`它能讓文件更容易閱讀、編寫。HTML 是一種發佈的格式，Markdown是一種編寫的格式`，因此，Markdown的格式語法純文字可以涵蓋的範圍。

```javascript
window.alert("AAA")
```

[Google]:https://www.google.com "Google"
[Yahoo]:https://www.yahoo.com "Yahoo"
[IMG_MD]:https://markdown.tw/images/208x128.png "Markdown"

this is [Google]
this is [Yahoo]
![IMG_MD]

- HTML
- CSS
- Javascript

1.HTML
1.CSS
1.Javascript

- [ ] html
- [x] css
- [ ] ~~javascript~~

|HTML|CSS|Javascript|
|-:|:--:|--|
|5|3|ES6|

```mermaid
graph LR
A(開始)
B[執行動作]
C{判斷狀態}
A --> B
B --> C
C --> |Yes|D
C --No--> E
```


```mermaid
sequenceDiagram
participant A as Web Server
participant B as Token Server
participant C as API Server
participant D as Database

A ->> B: 要求 token
B ->> A: 回應token(有效時間1分鐘)
A ->> C: 使用 query: ?token={token} 呼叫
C ->> D: 讀取 token 對應資料
D ->> C: 回應資料庫內容
C ->> A: 回應資料
```

```mermaid
gantt
title 專案開發時間表
dateFormat YYYY-MM-DD
section 設計
電腦版: d1,2020-11-11,7d
手機板: d2,after d1, 3d
section 工程
前端: after d2, 7d
後端: after d2, 3d


section Andrew
列表畫面: a1,2020-11-11,2d
串接資料: a2,after a1,2d
欄位檢查: after a2,3d
```

