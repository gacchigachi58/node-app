# node-app
## 「ターミナルで遊べるHit-Blowゲーム」
### 使い方
1. インストール
```bash
# npm install
```
2. ビルド
```bash
# npm run build
```
3. 実行
```bash
#npm run start
```

4. mode選択(normal or hard)
```bash
> node-app@1.0.0 start /home/keitaro/node-app
> node dist/index.js


モードを入力してください
- normal
- hard
> 
```
### ルール
- 複数個選ばれている0から9の数字を順番に当てるゲーム。normalモードでは3つ。hardモードでは4つ。
- Hit: 数字も場所もあっている個数
- Blow: 数字は合っているが、場所が合っていない個数
- 試行回数をできるだけ減らして正解するとえらい。