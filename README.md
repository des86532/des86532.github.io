# Neil's Blog

使用 keep 主題
參考 https://keep-docs.xpoet.cn/usage-tutorial/quick-start.html

## Blog 使用方法紀錄

參考 https://hexo.io/zh-tw/docs/commands

### new
```
$ hexo new [layout] <title>
```
建立一篇新的文章。如果沒有設定 layout 的話，則會使用 _config.yml 中的 default_layout 設定代替。如果標題包含空格的話，請使用引號括起來。

### generate
```
$ hexo generate
```
產生靜態檔案。

- -d, --deploy	產生完成即部署網站
- -w, --watch	監看檔案變更

### publish
```
$ hexo publish [layout] <filename>
```
發表草稿。

### server
```
$ hexo server
```
啟動伺服器，預設是 http://localhost:4000/。

- -p, --port	覆蓋連接埠設定
- -s, --static	只使用靜態檔案
- -l, --log	啟動記錄器，或覆蓋記錄格式

### deploy
```
$ hexo deploy
```
部署網站。
- -g, --generate	部署網站前先產生靜態檔案

### clean
```
$ hexo clean
```
清除快取檔案 (db.json) 和已產生的靜態檔案 (public)。

### 顯示草稿
```
$ hexo --draft
```
顯示 source/_drafts 資料夾中的草稿文章。

### render
```
$ hexo render <file> [file2] ...
```
渲染檔案。
- -o, --output	輸出位置

### list
```
$ hexo list <type>
```
列出網站資料。

### version
```
$ hexo version
```
顯示版本資訊。