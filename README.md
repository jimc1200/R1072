# https://github.com/P4CSS/R1072
* TA: 
* https://github.com/P4CSS/R1072
* Joining [Facebook page R1062](https://www.facebook.com/groups/R1062/) for calling for help and gathering.
* [A cheatsheet to look up commands](RCheatSheep.pdf)
* [**Download** whole project before lessons](https://www.dropbox.com/sh/12cev4z4q9ankwj/AADR77HGAAtIbtpO3jgNInfKa?dl=0)
* [Youtube Video for review](https://www.youtube.com/playlist?list=PLK0n8HKZQ_VfJcqBGlcAc0IKoY00mdF1B)

# New Design of the course
1. 本門課專門為想從事資料新聞實作的學生所設計，故R語言教學不包含進階內容如回歸、主成分分析、SVM等進階內容，而著重在如何獲取資料並進行視覺化。如果你想學「程式」那您可以改選修下學期的課；若您想學怎麼做資料報導與視覺化，且全無基礎，那確實是適合的對象。
2. 課程報導議題將鎖定在2018年九合一選舉、PM2.5的歷史發展與591租屋網與實價登錄的不均問題。詳細指定議題將會在開學第一週公布，如對議題不感興趣者，尤其是外系同學，請勿選修。
3. 課程報導需包含有訪談內容以驗證實作成果。
4. 課程中安排有期中考確實驗收學生實作能力。
5. 課程亦考驗學生程式的應用能力：學生需要自行涉獵一個套件或分析案例（Datacamp, Online cases, or packages）以顯示其有能力在課後持續發展。


## Calendar
1. Google sheet: week 1
2. Midterm * 1
3. Case sharing: 2 times, 1.5 hours. week 3 
4. My case sharing: 1.5 hours around week 9 or 10.
5. Wen for data visualization with GIS



| Week| Date| Toipic| Activities|
| --- | --- | --- | --- |
| W01 | 0218 | Course overview| |
| W02 | 0225 | Using google sheet to process data: ubike and paid maternity leave| AS#1 |
| W03 | 0304 | R Basic: Reading CSV: paid maternity leave| AS#2: Sharing good data jouranlism cases|
| W04 | 0311 | R Reading hierarchical data: json and xml| AS#3 | |
| W05 | 0318 | R Scraping web data: rent591| AS#4 |
| W06 | 0325 | R Text processing and trump's tweets| AS#5|
| W07 | 0401 | R Scraping web data and parsing HTML files| AS#6: Scrpaing PTT Forums|
| W08 | 0408 | Sharing Data-driven news report by group ||
| W09 | 0415 | R Chinese text processing: Tokenization and collocation| AS#7 |
| W10 | 0422 | Midterm ([sample](https://github.com/P4CSS/Assignments/blob/master/RQUIZ.md)) | AS#8 |
| W11 | 0429 | Tableau| AS#9 |
| W12 | 0506 | Proposal||
| W13 | 0513 | Tableau| AS#11 (Submit proposal 2)|
| W14 | 0520 | Proposal: Group Meeting| AS#12 |
| W15 | 0526 | Tableau| |
| W16 | 0603 | Tableau| |
| W17 | 0610 | Topic modeling | |
| W18 | 0617 | Final presentation | Submit final project |




## Announcement
```
Sys.setlocale(category = "LC_ALL", locale = "UTF-8")
Sys.setlocale(category = "LC_ALL", locale = "C") 
Sys.setlocale(category = "LC_ALL", locale = "cht") # for win
```

## W18 - final report


### W17 - Random Forest 
* [Slide10: Random Forest](https://docs.google.com/presentation/d/e/2PACX-1vQRPmt4H5Pdys7pu7-SvNu7Y5p08OrINCJx-WFEm5PI2OM5k--pwNUUGjNxmGthpE2c66fzyP9Ms9ve/pub?start=false&loop=false&delayms=3000)
* Be sure to have `9_3_decision_tree_titanic.Rmd` and `TM08_stock_random_forest.Rmd`

### W16-SVM to predict stock up and down
* [Slide09: SVM](https://docs.google.com/presentation/d/e/2PACX-1vRVudHBYlfrtXZDu7zIdbde3_dB3gIXrl6S0lMSARfRfA__m0TPL-AmQvVMdEIE6BqU6dLgQWJ-QYwP/pub?start=false&loop=false&delayms=3000)
* [Slide08-1: PCA](https://docs.google.com/presentation/d/e/2PACX-1vRhbsGGw0xYHisqd9IxqiOJ7iDYic0WjipPEwlI3J8LkaBYokP20oyOlKiGE7lyXBCAhBnBL4harpmV/pub?start=false&loop=false&delayms=3000)
* [PCA iris]
* [PCA Marriage Equality]

### W15 Word2vec
* [Slide08: word2vec](https://docs.google.com/presentation/d/e/2PACX-1vSaDbagemtALMf0F5CJViNvLUI7U7cGJtelziV5IdKOridKI28DQ85sWWpVa1Y_1G3vH0bkKMAzW-XZ/pub?start=false&loop=false&delayms=3000)


### W14-report
* Pre-report and review of topic modeling

### W13-Topic modeling
* [Slide07. Processing Chinese text and topic modeling](https://docs.google.com/presentation/d/e/2PACX-1vRTSSO_8JuLTK_1OyM9eDrogA-K2fhXQwlKxh1PpRvNavkurCCcKBNftv9MpKGYM6EDXtNnqZvPDdKy/pub?start=false&loop=false&delayms=3000)
* Copy your slide link for next week report to [here](https://docs.google.com/document/d/1fvkO6czxHINFm9agVe7oFcLcGBGoTRHOXRh0BuTVQ9s/edit?usp=sharing) before class.


### W12-trump's case and Chinese text processing
* [Slide06. dplyr_trump's tweet](https://docs.google.com/presentation/d/e/2PACX-1vRNLWSWiTePNA5tmAhFcbkFWEzfa0LFiG0FENhalVpxz2lG2Z1lZ8pJHacaKHWpnC1SYhR-qxQOnKb7/pub?start=false&loop=false&delayms=3000)
* AS#9 Using **your own** data (no matter in English or in Chinese) to practice text processing skills (At least 3 charts).

### W11-ggplot and exploratory data analysis
* [Slide05. ggplot](https://docs.google.com/presentation/d/e/2PACX-1vR0MIoaDm9YaEvop3wYAYHnr5O-kCPtK2AlS9QR8zpgeoCBQCfJ39q55VrK4RvM_UJg18JDQa1I_pgJ/pub?start=false&loop=false&delayms=3000)
* [AS#8 EDA and text mining on tweets](https://github.com/R4CSS/Assignments/blob/master/07_tweet_text_mining.md#text-mining-tweet-data)
* [Topic preview and review](https://docs.google.com/spreadsheets/d/1SuEfbrDWFWKcw867h6eEHYCtkLeQIPjx8DuNKo96lnU/edit#gid=0)


### W10-Getting tweets and doing exploratory data analysis
* [AS#7 Getting tweets and doing exploratory data analysis](https://github.com/R4CSS/Assignments/blob/master/06_twitter_EDA.md#scraping-twitter-data-dand-doing-exploratory-data-analysis)

### W07-Parsing HTML
* [Slide04. HTML Parser](https://docs.google.com/presentation/d/e/2PACX-1vSGeNG6BcEUNjhZjqo1obJ9bijuMjKJ0WhEva29-AuishNv779rSC0nDShfkR5HcWp4EdlRUBaaiG0M/pub?start=false&loop=false&delayms=3000)
* 為了通熟本章節，你會需要額外花時間了解何謂html、css、xpath？在html中，id和class的目的為何？有和特性？何謂html元素（element）？何謂html元素的屬性（attribute）？
* 你可以略讀參考w3school所提供的說明，無論是英文或者切至中文畫面。
	* [Learning html](https://www.w3schools.com/html/default.asp): 包含Introduction, Basic, Elements, Attributes, Headings, CSS, Links, Blocks, Images, Tables, Lists, Classes, Id等節。
	* [css syntax](https://www.w3schools.com/css/css_syntax.asp)。
	* [css combinator](https://www.w3schools.com/css/css_combinators.asp)。
	* [xpath introduction](https://www.w3schools.com/xml/xpath_intro.asp)
* [AS#5 Crawling news media search page](https://github.com/R4CSS/Assignments/blob/master/assignments.md#crawling-news-search-results). No later than 4/23 23:59. 

### W06-Get data from the web
* [Slide03. crawler design](https://docs.google.com/presentation/d/e/2PACX-1vRW84XoB5sFRT1Eg-GrK4smX23qoNkFffz_h8oRU4AIvJAgrrxBn8059_0UeHv_pFBks_Z37vNbLGai/pub?start=false&loop=false&delayms=3000)
* [AS#4. Plotting Air Quality Index on Map](https://github.com/R4CSS/Assignments/blob/master/04_AQX.md). No later than 4/16, 23:59.


### W05-Read CSV and JSON
* [Slide02. Read csv and json](https://docs.google.com/presentation/d/e/2PACX-1vTFRVkwdscR3QNdVD6Q8JEKshlORtgdP_DUq19HPjbO6_8nN3ADTEtxuOr_Z28t3HKGdf9_m3icULpO/pub?start=false&loop=false&delayms=3000) 
* [AS#3. Reading open data](https://github.com/R4CSS/Assignments/blob/master/03_CSV_JSON.md#open-data). No later than 04/09 23:59. 

### W04-Read CSV and JSON
* [Slide02. Read csv and json](https://docs.google.com/presentation/d/e/2PACX-1vTFRVkwdscR3QNdVD6Q8JEKshlORtgdP_DUq19HPjbO6_8nN3ADTEtxuOr_Z28t3HKGdf9_m3icULpO/pub?start=false&loop=false&delayms=3000) - [Video02-1 Paid Maternity Leave](https://youtu.be/65zI6Zrj2zo).
* [AS#2 writing code with RMD](https://github.com/R4CSS/Assignments/blob/master/02UsingRMD.md). No later than **Mar 26 (MON) 23:59** (Remember our assignment policy). 


### W03-Importing data

* [Slide01. R Basic](https://docs.google.com/presentation/d/e/2PACX-1vRjb_W1Vo9-zD9F4FmWOiB6K4ezkF6W64OKcX7bZD6ordKvOT-6LFoGi0le-HzT2ABKudDNhr_qKt2x/pub?start=false&loop=false&delayms=3000&slide=id.g2074c710b4_0_293)


### W02-Rbasic
* [AS#1 Learning with datacamp](https://github.com/R4CSS/Assignments/blob/master/01DataCamp.md) announced. Submitting to ceiba AS#1 no later than 2018/3/13 23:59.
* Reading [Chapter 4 of R for data science](http://r4ds.had.co.nz/workflow-basics.html) to understand basic data types, assignments, variables, character vs. numeric variables, and functions.
* [R00. Install](https://docs.google.com/presentation/d/e/2PACX-1vSNj-P2-8cJptSy-eRMKXs4eSNgLgeaCHiF22THEDkmijIXaqFA8U67T3Lp-iR0ibXssD-NHUq5DEG2/pub?start=false&loop=false&delayms=3000),
* [R01. R Basic](https://docs.google.com/presentation/d/e/2PACX-1vRjb_W1Vo9-zD9F4FmWOiB6K4ezkF6W64OKcX7bZD6ordKvOT-6LFoGi0le-HzT2ABKudDNhr_qKt2x/pub?start=false&loop=false&delayms=3000&slide=id.g2074c710b4_0_293)


## Introduction
- 加退選原則：本門課除新聞所學生外，加選以曾選修新聞所開設之「新聞與數位創作」學程之學生為優先，社科院學生次之，生傳、文學院、管院學生再次之。理工科系學生由於相關程式學習資源多元，建議選修台大校方為培植學生資訊能力開設的精彩CS+X課程系列。
- 預設對象：本課程預設對象為「無程式寫作經驗」且對資料新聞抱有興趣的學生。不建議有程式撰寫經驗者選修，亦不開放旁聽。
- 課程抵用原則：新聞所學生得選修本課，但由於本課程內容與「新聞資料分析」雷同，兩門課僅可以一門抵用畢業學分。
- 由於以無程式經驗者為對象，教師得依學生學習情形調整授課內容，但至少包含以下內容：
  - R Programming basics
  - Reading files including CSV and JSON formats
  - Processing data by apply() family and dplyr package
  - Exploratory Data Analysis with ggplot()
  - Web crawler skill: getting data by GET and POST
  - Web APIs e.g., Google Map, Facebook, and Twitter
  - Text processing packages including tidytext and jiebaR

### Gradings

* **0% Quiz**: 本門課包含二次不計分的隨堂小考，分別用以了解學生期初之學習情形與驗收期末學習成果。
* **3% absence**: 未能到課需依學校規定之請假程序請假，經查缺席者一次得扣學期總成績三分。
* **40% Assignments**: 作業繳交時間一律為作業公布後的五天內繳交（Mon 23:59），以便助教批改並協助同學回顧作業內容。作業公布七天內可接受補交，然成績以八折計算，次週上課前不再接受補交（Wed 11:59）。作業繳交問題請聯絡助教（郁雯）。作業應按照指定格式繳交（第三次作業開始，需以RMarkdown或R Notebook撰寫，並繳交.rmd檔及其所衍生的HTML檔），如格式不合，經助教聯繫未在次週授課當天補交者該項亦不予計分。
* **30% Digital News Project**: 從政府開放資料、或指定的資料集發展一則資料新聞，著重在資料的彙整、資料的清理、視覺化敘事。該則新聞需投稿至台大新聞e論壇，或其他新聞媒體。
* **30% Data Science Project**: 自行爬取非結構化文本資料進行文字探勘，著重在文字的分析、模型的應用和事後詮釋。

### Books

* [R for data science](http://r4ds.had.co.nz/introduction.html)
* [Text mining using r](http://tidytextmining.com/)
* [Good jiebaR introduction](http://blog.fens.me/r-word-jiebar/)
* http://www.rdatamining.com/
* [Learning R in Y minutes](https://learnxinyminutes.com/docs/r/)
* [Datacamp for R](https://www.datacamp.com/courses/tech:r)

## Mid-Digital-News Project

- 以政府開放資料或利用網路爬蟲爬取相關資料作為分析對象，並以R語言分析與視覺化。採分組進行，所有組員均應參與報告。
- (-3%) R 程式、原始資料：必須以RMD撰寫，並繳交RMD、HTML二種格式，缺繳原始資料、RMD或HTML任一項者扣3%。
- (15%) 專題報告（10 slides）。評分標準包含問題、創新、文獻與背景。
- (15%) 書面新聞專題報導（中文800~1000字以Word撰寫） 。評分標準包含背景與問題意識、文獻探討與訪談結果、結果詮釋。
- (-3%) 新聞需編輯後上傳至Medium.com。
- (Option 5%) 結果包含人物專訪。

## Final-Data-Science Project

- 需以政府開放資料、Kaggle、Facebook、Twitter或利用網路爬蟲爬取相關資料作為分析對象，並以R語言分析與視覺化。採分組進行，所有組員均應參與計畫書與期末報告。應到未到而無請假紀錄者，扣總成績三分。
- (-3%) R 程式、原始資料：必須以RMD撰寫，並繳交RMD、HTML二種格式，缺繳原始資料、RMD或HTML任一項者扣3%。新聞需編輯後上傳至Medium.com。
- (30%) 專題報告（15 slides）。評分包含創新、展演、問題背景與文獻，現場同儕互評。
- (Option 5%) 衍生新聞。由台大新聞e論壇總主編林照真教授評分。
