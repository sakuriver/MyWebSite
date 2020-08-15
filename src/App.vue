<template>
    sakuriverの家です
    <button id="show-modal" @click="showModal = true">ご連絡(Notification)</button>
    <div>
        商業実績(公開可能分)
        CryptoDerby
        バックエンド実装
    </div>
    <div>
        作品集...移動中
        <a href="https://docs.google.com/spreadsheets/d/1I8TV2l-UcwWR5whEZT24nBveiK999qlD8ngEuhkaVzk/edit?usp=drive_open&ouid=112709719422071788648">オープンコンテンツ</a>
    </div>
    <!-- モーダルウィンドウ用 -->
    <div>
        <h2>ご連絡</h2>
        <h3>面談や各種登壇で以下の内容については、答えられないのでご留意ください。</h3>
        <p>2015年10月～2019年5月のゲーム会社における技術以外の担当やコミットした内容</p>
        <p>エンジニア以外のスプリント周りについてもなしでお願いいたします</p>
        <p>上記期間においては、タイトル名を上げての説明も、CryptoDerbyのみとなります</p>
        <p>CryptoDerbyの仕様や現運用については 総合ディレクターである Tomohiro Yakumaru <a href="https://twitter.com/txd890">地場 衛</a>さん  まででお願いいたします</p>
        <p>各案件の取引先情報</p>
        <p>各案件の非公開扱いとなる技術領域</p>
    </div>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      value: "World"
    };
  }
};
</script>
