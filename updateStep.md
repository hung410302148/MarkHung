###網站更新步驟

1.打開cmd進入目標資料夾，例如D槽
```
d:
```

2.git clone [repositoriesURL]
```
git clone https://github.com/hung410302148/MarkHungWeb.git
```

3.初始化本地端repositories
```
cd MarkHungWeb
git init
```

4.連結repositoriesURL
```
git remote add origin https://github.com/hung410302148/MarkHungWeb.git
```

5.將所有檔案新增至Git版本控制中
```
git add .
```

6.更新檔案描述
```
git commit -m "更新描述"
```
將“更新描述”改為你的更新描述資訊，以便更好地記錄更改。

7.推送
```
git push origin master
```

完成更新


