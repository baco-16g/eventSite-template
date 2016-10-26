# eventSite-template

個人受注で請け負っているイベントサイト類のレイアウトは、だいたい似通っているのでテンプレートを作成した。(wip)

## Get started

```bash
$ git clone git@github.com:baco-16g/eventSite-template.git

$ cd eventSite-template
$ npm install
```

```bash
# run
$ npm run start # to develop
# Server running at: http://localhost:3000

```

jsonでコンテンツを管理したい場合は...

```json
// json/data.json

{
  "title": "ここにタイトル"
}
```
```html
// .pug

- var title = data.data.title;
h1 #{title}
```
