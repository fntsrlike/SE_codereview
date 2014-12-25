本 Repository 是為了碩班課程「軟體工程實務」的 Code Review 所建立的。若要觀看最後更新結果，請到下面網址下載：

- https://github.com/fntsrlike/SE_codereview

本程式是使用 Laravel 這套擁有 MVC 架構的 Framework，在後端的部分可以把主力專注放在 Controllers 和 Models ，所以我選擇了有關紀錄功能的 Controller 和 Modal 作為這次 Code Review 的程式碼。關於 Laravel 的用法，可以參考：

- http://laravel.com
- http://laravel.tw

如上所述，本 Repository 提供的程式碼主要是展示公佈欄位申請系統在記錄部分的處理，以 RESTFul Controller 為主，搭配三個去處理資料庫的 Models ，概略說明如下：

- ApplyRecordController.php: 處理記錄相關 Request 與 Response 的 Controller
- ApplyRecord.php: 處理記錄相關資料庫內容的 Model
- Board.php: 處理欄位相關資料庫內容的 Model
- User.php: 處理使用者相關資料庫內容的 Model

其他檔案說明如下：
- demo.pdf: 本程式的講解用投影片
- SRS.pdf: 本程式的系統需求規格書
- README.md: 說明文件，即本文件

本程式碼參考的是以 PHP-FIG 所規範的 PSR 為主，可參考下列文件：
- [PSR-1: Basic Coding Standard](https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-1-basic-coding-standard.md)
- [PSR-2: Coding Style Guide](https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-2-coding-style-guide.md)
- [PSR-2: PSR-2 Meta Document](https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-2-coding-style-guide-meta.md)
- [PSR-3: Logger Interface](https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-3-logger-interface.md)
- [PSR-4: Autoloader](https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-4-autoloader.md)
- [PSR-4: PSR-4 Meta Document](https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-4-autoloader-meta.md)
- [PSR-4: Example Implementations of PSR-4](https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-4-autoloader-examples.md)
