# 博客來暢銷書排行榜爬蟲專案

## 📘 專案介紹
本專案透過 Python 的 Selenium 套件，自動爬取「博客來」網站中的中文書暢銷排行榜資料。程式將蒐集每本書的書名、作者、出版社、價格與連結資訊，並儲存為 CSV 和 Excel 格式，方便後續瀏覽與分析。

## 🔧 功能說明
本專案主要分為以下幾個功能頁面：

- [博客來暢銷書排行榜原始網頁](https://www.books.com.tw/web/sys_saletopb/books/)：資料爬取來源頁面。
- [展示個人網頁作品](https://umi0205.github.io/411205201/html5up-strata/)：使用 HTML5 UP 的 Strata 模板，呈現個人作品與簡介。
- 資料儲存：將爬取結果儲存為 `博客來暢銷書排行榜.csv` 及 `博客來暢銷書排行榜.xlsx`。

## 🛠 使用工具與套件

- Python 
- 套件：
  - `selenium`：用於模擬瀏覽器操作，自動化網頁資料擷取
  - `webdriver_manager`：自動下載並管理 ChromeDriver
  - `pandas`：資料整理與儲存為 Excel/CSV
- 瀏覽器自動化工具：Google Chrome

## 🖼 圖示與資料來源

**爬蟲資料來源：**  
[博客來中文書暢銷排行榜](https://www.books.com.tw/web/sys_saletopb/books/)

**資料截圖預覽：**  
![博客來截圖範例](https://raw.githubusercontent.com/umi0205/411205201/refs/heads/main/%E8%9E%A2%E5%B9%95%E6%93%B7%E5%8F%96%E7%95%AB%E9%9D%A2%202025-06-05%20131001.png)  


## 👤 作者與聯絡方式

- 作者：徐采妤
- Email：a0909637222@gmail.com
