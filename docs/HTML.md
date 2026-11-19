# ページの遷移について
遷移方法
- aタグをつけてリンク用のボタンを生成する（CSSによってボタンの見た目にする）
- buttonタグを使ってボタンを作る（CSSなしでボタンの見た目になる）
- inputタグで表示できるようにする
aタグは<a herf="URL" class"btn">< /a>のように書く。herfに遷移先のURLをつけることで遷移できるようにする。
aタグの間にimgタグを入れると画像をクリックできるようになる。

buttonタグは名前の通りボタンを配置できる。
<button onclick="location.href = 'URL'">< /button>このように書くことでURｌに飛ぶボタンを作れる。こちらはCSSで見た目を作らなくても最初からボタンで生成される。

inputタグは属性をbuttonにすることでボタンを表示できるようになる。
<input type ="button" onclick = "location.href = 'URL'"value = "sample">これでURLの先にt部ボタンを生成することができる。