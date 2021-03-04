# これは
- javascriptでmarkdownをパースする
- markdown -> html　への変換

# 使い方
- `docker-compose up -d node`
- `docker-compose exec node bash`
- `node app.js`

# 注意
- cssがtailwindなのでliなどに個別にclassを付与する必要あり
- custom/tailwind.cssに書き込み、`npx tailwindcss-cli@latest build ./custom/tailwind.css -o ./dist/tailwind.css`を実行