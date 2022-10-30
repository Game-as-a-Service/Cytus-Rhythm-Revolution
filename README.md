# Cytus Rhythm Revolution (CRR)
[第一屆RayarkMania Contest - RMC直播](https://www.youtube.com/watch?v=SuIYPuLOlaI&t=16218s)
## 遊戲介紹
音GAME結合TCG  
16組首性不同的歌曲組成不一樣的牌組來進行對戰

### 內容物
1. 元素盤*1
2. 16種角色，每種角色各配有四張式與七張法，共176張牌。
3. 16張腳色決鬥盤

### 規則
(真的要在這補???)

## My Practice Stack
OOA、OOD、OOP
ATDD(最少)→BDD
經過吐司會後決定嘗試 Event storming、Example Mapping

## Tech Stack
- Python 核心規則
- Django 前端
- PostgreSQL DB

## 開發流程
TODO: (改畫圖，這個無法表達任務階級)
1. 取得授權
2. 整理資源
3. 玩16組牌
4. 嘗試規範BDD內容
5. 完成遊戲紀錄規則

## 開發規範

1. git commit sytle：
[gitmoji](https://gitmoji.dev/)

2. WorkFlow：
(待決定)(由 code review 者決定)
git flow、github flow、gitlab flow

3. Python linter
pep8

4. autoCodeReview
原本我都是用 Codacy 來做，但這次既然是遊戲微服務，考量到整套應該是可以被 follew 做出來，所以打算嘗試建一個 SonarQube 出來，並用 docker-compose 達到 Infrastructure as Code (IaC)
這套是短期要做↑，排在正式寫code之前

5. (找一個可以規範python風格的咚咚，python界的eslintrc.js是什麼呢？ 這樣可以透過檔案直接規範比較好)


# 開發心態、歷程(之後移到專門的markdown去)

TODO:
**(下面寫這麼長有必要？能達成什麼效果？有沒有更好的表達方式？)**

遊戲微服務，"分享軟體工程大集成的方法"

通常來說應該要畫自己能力難度+30%，才能有一定進步又不會半途而廢
但我想在這裡就畫立目標，"盡我所能開源所以工具、流程、思維"，這個工程很漫長，畢竟我自己近期可能2、3個月都必須要把先前沒補上的坑收尾，給他人交代也給自己交代，所以為了維持這個專案的進度，要先排出固定的時間來開發

考量的點：
(事先聲明:可更改)(不聲明這個我會太謹慎)
那天通常會留下多少精力、時間被打擾的可能性、如果被打擾補救時間的納入

~~遊戲微服務的開會是固定在星期二，考量到 code review 的時間，應該要在上個星期四就發 pr 上 github，星期二開完會也該睡了，排除~~



<!--  -->
