### 用Github+Hexo 作部落格

#### 1.事前安裝

Node.js
Notepad++

----

![](https://i.imgur.com/uV58xJo.png)

----

![](https://i.imgur.com/SwOpf4I.png)

---

### 2.進入github

1.設定repository( 將名稱設為帳號 + github.io )
2.選擇theme
3.你將會看到一副半完成品

----

![](https://i.imgur.com/6ozpNoe.png)


----

![](https://i.imgur.com/I7Qi3zB.png)

----

![](https://i.imgur.com/ugdS1DG.png)

---

### 3.進入建立環節

1.開啟git bash
2.輸入npm install -g hexo-cli
安裝完 Hexo 套件後
3.hexo init + 資料夾名稱(以myblog為例)
4.cd進入myblog
5.npm install (安裝 Hexo)
6.npm install hexo-deployer-git --save (安裝 git 部署套件)

----

![](https://i.imgur.com/mUBjpoq.png)

----

![](https://i.imgur.com/cQRYAbW.png)

----

![](https://i.imgur.com/ZGqWOGq.png)

---

### 4.設定部落格

1.電腦中找到myblog資料夾。
2.點選_config.yml ,修改第 6~12 行資訊,URL,Deploy。
url: https://帳號名稱.github.io
deploy:
  type: git
  repo: https://github.com/帳號名稱/帳號名稱.github.io.git
  branch: master
修改完畢後存檔。

----

![](https://i.imgur.com/UB2dUJO.png)

----

![](https://i.imgur.com/1bZdUhj.png)

----

![](https://i.imgur.com/S6JgxNF.png)

---

### 5.部屬至Github

1.hexo cl  //清除之前建立的靜態檔案，也可以輸入 hexo clean
2.hexo g  //建立靜態檔案，也可以輸入 hexo generate
3.hexo d  //部署至 Github Pages，也可以輸入 hexo deploy
若出現deploy dong : git 代表部屬成功

----

![](https://i.imgur.com/hgQakME.png)

----

![](https://i.imgur.com/nAlwROT.png)

----

![](https://i.imgur.com/Y5lS2P0.png)

---

### 6.完成後上網查看自己的部落格

https://帳號名稱.github.io
![](https://i.imgur.com/ZGsoCgp.png)
