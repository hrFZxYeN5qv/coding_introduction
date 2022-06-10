JavaScript與前端程式設計入門自學參考
=======================

(https://tw.twincl.com/javascript/*6731)
想要自學JavaScript與前端程式設計，網路上有很多資源，應該先學哪些，也是見人見智。要做好前端程式設計的工作，我認為至少應該瞭解JavaScript、資料結構與演算法、網路協定、HTML、CSS、DOM API和RWD這幾個領域。以下介紹內容與所列資源僅代表個人看法，歡迎大家補充。

![](https://farm8.staticflickr.com/7564/16003638861_218931090d_z_d.jpg)  
_Photo credit [Hernán Piñera@flickr](https://www.flickr.com/photos/hernanpc/16003638861/)_

1\. JavaScript基礎
----------------

JavaScript的語法，風格與Java、C/C++類似，若是你有學過這些程式語言，上手JavaScript應該很快。如果JavaScript是你的第一門程式語言，那麼可能要花多一點時間學習。基礎的JavaScript學習，至少應包括這些：

*   Data types, control flow, loops
*   Functions, operators, error handling
*   String, Date, Math
*   Arrays, objects
*   Regular expressions

對初學者而言，regular expression（正規表示式）是我認為比較難的部份。其實regular expression本身就是個小型語言，專門用來處理字串的比對、替換。熟悉regular expression的人，可以用一行正規表示式完成幾十行程式才能做到的事情，功能強大。而且不同程式語言的regular expression語法大同小異，將來不用重覆再學。

前幾天陳鍾誠老師剛完成一本「[專為中學生寫的JavaScript程式書](https://ccckmit.gitbooks.io/javascript/content/index.html)」，如果JavaScript是你的第一門程式語言，這本電子書可能會對你有幫助。不過請記得，它是以Node.js為學習範例，所以有些東西在前端瀏覽器是沒有的（例如檔案存取、資料庫、http模組……等等）。

2\. 資料結構與演算法
------------

資料結構與演算法是資訊相關科系的必修課，自學程式設計的人，最好也可以學一下，因為我認為這是軟體開發的基礎之一。基本的資料結構與演算法學習，至少包括這些：

*   資料結構
    *   陣列（array）、串列（list）、堆疊（stack）、佇列（queue）
    *   樹（tree）、二元樹（binary tree）、雜湊表（hash table）
*   演算法
    *   對以上資料結構的各項操作
    *   排序（sort）：至少搞懂3、4種基本的排序演算法，例如bubble sort、quick sort、merge sort等
    *   搜尋（search）：depth-first-search、breadth-first-search、binary search等
    *   其它：迭代（iteration）、遞迴（recursive）、分治法（divide and conquer）、時間/空間複雜度的基本概念（big O）等

關於資料結構與演算法入門，陳鐘誠老師有一份整理得很好的材料：「[用十分鐘學會《資料結構、演算法和計算理論》](http://www.slideshare.net/ccckmit/ss-56891871)」。十分鐘學會可能有點難，不過這份材料可以減少你不少摸索的時間。觀念學會之後，再運用剛上手的JavaScript語言，演練這些演算法及資料結構，一舉兩得。

3\. 網路協定
--------

在我的另一篇文章「[程式員求生指南：關於寫程式的二三事](https://tw.twincl.com/@arthurtw/*652e)」中，我提到網路協定也是程式員基本功之一，理由就不在這裡重覆。基礎的網路協定，包括OSI 7-layer model、TCP/IP、DNS、HTTP等等：

*   [OSI 7層模型](https://zh.wikipedia.org/wiki/OSI%E6%A8%A1%E5%9E%8B)：這屬於知識性的內容，大致看一下，了解每一層的作用就行了。
*   [TCP/IP](https://zh.wikipedia.org/wiki/TCP/IP%E5%8D%8F%E8%AE%AE%E6%97%8F)：TCP架在IP協定之上，兩者都是網路日常運作的重要協定。UDP也是架在IP協定上，可以順便了解一下。
*   [DNS](https://zh.wikipedia.org/wiki/%E5%9F%9F%E5%90%8D%E7%B3%BB%E7%BB%9F)：大概知道DNS裡的幾種常見record（A、CNAME、NS、MX等），primary/secondary DNS的角色，以及從domain name解析到IP的過程，就可以了。
*   [HTTP](https://zh.wikipedia.org/wiki/%E8%B6%85%E6%96%87%E6%9C%AC%E4%BC%A0%E8%BE%93%E5%8D%8F%E8%AE%AE)：HTTP與軟體開發人員的關係很密切，在以上這些網路協定裡，值得花比較多的時間去學習。例如：
    *   HTTP methods（GET、POST……）
    *   HTTP status code（2xx、3xx、4xx……）
    *   HTTP headers（Content-Length、User-Agent、Cache-Control、Cookie/Set-Cookie……）

（我之前寫的一篇文章「[簡明RESTful API設計要點](https://tw.twincl.com/programming/*641y)」，講的雖然是RESTful API設計，但也列了許多HTTP的要點，可以參考一下。）

如果你在自學這些網路協定的過程中，感到一個頭兩個大，不用擔心，這是正常現象。看不懂可以先擱一邊，以後回頭再找時間看就行了。入門初學也不需要掌握得很深入，大致瞭解即可。（例如HTTP status code知道一個大概就行了，不需要每個status code都瞭如指掌。）

4\. HTML
--------

HTML在前端的技術學習裡，算是相對容易的部份。隨便打開一個網頁（例如Mozilla Developer Network「[給開發者的網頁技術文件](https://developer.mozilla.org/zh-TW/docs/Web/HTML)」），用瀏覽器看看裡面的HTML原始碼長甚麼樣子，就會有點感覺了。基礎的HTML學習，大致上包括這些：

*   Text, formatting, lists, tables
*   Forms, frames, header elements
*   HTML5

HTML學習的資源很多，像前面提到的MDN（Mozilla Developer Network）網站，也是其中一個。

5\. CSS基礎
---------

CSS在前端開發裡，佔有非常重要的角色。一般的看法是：HTML-內容，CSS-外觀，JavaScript-動作。比起HTML，CSS本身帶有程式碼的特性，是我認為前端專案中最容易搞壞、最難維護的一塊。基礎的CSS學習包括：

*   Text styles, colors, lists, boxes
*   CSS selectors
*   CSS specificity
*   Psuedo-classes, psuedo-elements
*   Floats, positioning

對初學者而言，CSS positioning可能有點複雜，這個網站「[Learn CSS Positioning in Ten Steps](http://www.barelyfitz.com/screencast/html-training/css/positioning/)」寫得很好，大家可以參考看看。（補充說明：我發現這個網站在Chrome瀏覽器有些小bug，每個步驟的連結要點第2次才會顯示正確的positioning效果。）

6\. DOM API
-----------

網頁的互動性，離不開DOM的操作。DOM（Document Object Model）是一種表示網頁內容的模型，而JavaScript可以透過DOM API新增、修改、刪除網頁上的元件。DOM API的學習，大致上包括：

*   DOM selector
*   DOM manipulation
*   DOM event

最簡單的例子，就是用像`document.getElementById(id)`或`getElementsByName(name)`這類DOM selector，取得網頁上的某個元件，然後修改它的內容、或為它加上event handler等等。

除了用瀏覽器本身的HTML DOM，jQuery也是一個被普遍用來操作DOM的工具。早期的瀏覽器由於DOM API不統一，採用jQuery這類工具有其必要性，但現在已經沒有這個問題了。是否採用jQuery，取決於專案需求。對初學者而言，我個人建議先學會HTML DOM，畢竟這是W3C標準。如果專案有用到jQuery，再學jQuery即可。

順便提一下，另一個很多人用jQuery的理由，是`$.ajax`很好用。如果你不用jQuery而需要做Ajax呼叫（也就是在背景向伺服器發出API請求），可以考慮用[`fetch`](https://developer.mozilla.org/en/docs/Web/API/Fetch_API)。`fetch`是取代`XMLHttpRequest`的新標準，很多瀏覽器都已經支援了，而且可以用[fetch polyfill](https://github.com/github/fetch)解決瀏覽器支援性的問題。

7\. RWD
-------

由於行動裝置的普及，RWD（Responsive Web Design，響應式網頁設計）已成為前端工程師的必備技能了。如果懂CSS，RWD其實並不複雜。除了在HTML header加上類似`<meta name="viewport" content="width=device-width, initial-scale=1">`的一行宣告，其它RWD的實現都與CSS有關，包括：

*   Fluid grid
*   Flexible image
*   Media queries

最原始的RWD文章，是Ethan Marcotte的「[Responsive Web Design](http://alistapart.com/article/responsive-web-design)」，但現在介紹RWD的文章非常多。另外，很多前端專案採用Bootstrap框架，Bootstrap本身也支援RWD，不過RWD的原理還是要會，畢竟總有自己來的時候。

其它資源
----

*   MDN Learning Area（英文）：[https://developer.mozilla.org/en-US/Learn](https://developer.mozilla.org/en-US/Learn)（中文介紹：[為了Web學寫程式碼吧！](http://blog.mozilla.com.tw/posts/8917/mdn-learning-area)）
*   [JSFiddle](https://jsfiddle.net/)或[CodePen](http://codepen.io/pen/)：線上寫HTML/CSS/JavaScript練習很方便

希望以上的說明，對大家自學JavaScript與前端程式設計有些幫助！如有其它好的初學者資源，也請各路高手幫忙補充。
