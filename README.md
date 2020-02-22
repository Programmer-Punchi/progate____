<!DOCTYPE html>
<html lang="ja">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Progate中級</title>
    <link rel="stylesheet" href="style.css">

    <!-- responsive.cssを読み込むための<link>タグ -->
    <link rel="stylesheet" href="responsive.css">

    <!-- Font Awesomeの読み込み -->
    <link rel="stylesheet" href="//maxcdn.bootstrapcdn.com/font-awesome/4.3.0/css/font-awesome.min.css">

    <!-- jQueryの読み込み -->
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/2.1.4/jquery.min.js"></script>
  </head>

  <body>
    <header>
      <div class="container">

        <!-- ヘッダー左側 -->
        <div class="header-left">
          <a href="https://prog-8.com/"><img class="logo" src="https://punchi.org/wp-content/uploads/2020/01/animal_chara_smartphone_usagi.png" alt="スマホを持つウサギ"></a>
          <a href="https://prog-8.com/"><p>Progate</p></a>
        </div>

        <!-- ヘッダー右側 -->
        <div class="header-right">
          <a class="login" href="#">ログイン</a>
        </div>

        <!-- ハンバーガーメニューの作成 -->
        

      </div>
    </header>
    <!-- スマホを触っている女性の画像 -->
    <div class="top-wrapper">

      <div class="container">
        <h1>LEARN TO CODE.</h1>
        <h1>LEARN TO BE CREATIVE.</h1>
        <p>Progateはオンラインプログラミング学習サービスです。</p>
        <p>初心者にもやさしいスライドとレッスンで、Webサービスを作りながらプログラミングを学んでいきましょう。</p>

        <!-- ボタンを作成 -->
        <div class="btn-wrapper">

          <!-- "btn signup"のように半角スペースで区切れば、複数のクラスを指定することができる。 -->
          <a href="#" class="btn signup">新規登録はこちら</a>
          <p class="sign">or<span> sign up with</span></p>

          <a href="#" class="btn facebook">
            <!-- Font Awesomeを使うための<span> -->
            <span class="fa fa-facebook"></span>
            Facebookで登録</a>

          <a href="#" class="btn twitter">
            <!-- Font Awesomeを使うための<span> -->
              <span class="fa fa-twitter"></span>
            Twitterで登録</a>
        </div>
        <!-- /ボタンを作成 -->

      </div>

    </div>
    <!-- /スマホを触っている女性の画像 -->

    <div class="lesson-wrapper">
      <div class="container">
        <div class="heading">
          <h2>Learn Where to Get Started!</h2>
        </div>

        <div class="lessons">
          <!-- html -->
          <div class="lesson">
            <div class="lesson-icon">
              <img src="https://prog-8.com/images/html/advanced/html.png" alt="">
              <p>HTML & CSS</p>
            </div>
            <p class="txt-contents">Webページの作成に使用される言語です。HTMLとCSSを組み合わせることで、静的なページを作り上げることができます。</p>
          </div>

          <!-- jQuery -->
          <div class="lesson">
            <div class="lesson-icon">
              <img src="https://prog-8.com/images/html/advanced/jQuery.png" alt="">
              <p>jQuery</p>
            </div>
            <p class="txt-contents">素敵な動きを手軽に実装できるJavaScriptライブラリです。 アニメーション効果をつけたり、Ajax（エイジャックス）を使って外部ファイルを読み込んだりと色々なことができます。</p>
          </div>

          <!-- Ruby -->
          <div class="lesson">
            <div class="lesson-icon">
              <img src="https://prog-8.com/images/html/advanced/ruby.png" alt="">
              <p>Ruby</p>
            </div>
            <p class="txt-contents">オープンソースの動的なプログラミング言語で、 シンプルさと高い生産性を備えています。大きなWebアプリケーションから小さな日用ツールまで、さまざまなソフトウェアを作ることができます。</p>
          </div>

          <!-- PHP -->
          <div class="lesson">
            <div class="lesson-icon">
              <img src="https://prog-8.com/images/html/advanced/php.png" alt="">
              <p>PHP</p>
            </div>
            <p class="txt-contents">HTMLだけではページの内容を変えることはできません。PHPはHTMLにプログラムを埋め込み、それを可能にします。</p>
          </div>

          <div class="clear"></div>

        </div>
      </div>
    </div>
    <div class="message-wrapper">
      <div class="container">
        <div class="heading">
          <h2>さぁ、あなたもProgateでプログラミングを学んでみませんか?</h2>
          <h3>Let's learn to code, learn to be creative!</h3>
        </div>
        <!-- <span class="btn message">さっそく始めてみる</span> -->
        <a href="https://prog-8.com/" class="btn progate">さっそく始めてみる</a>
      </div>
    </div>

    <!-- 問い合わせフォーム -->
    <div class="contact-form">
        <h3>お問い合わせ</h3>
        <p>メールアドレス（必須）</p>
        <input>

        <p>お問い合わせ内容（必須）</p>
        <textarea></textarea>

        <p><span class="under">※必須項目は必ずご入力ください</span></p>
        <input class="contact-submit" type="submit" value"送信">
    </div>

    <!-- フッター -->
    <footer>
      <div class="container">
        <a href="https://prog-8.com/"><img class="footer-left" src="https://prog-8.com/images/html/advanced/footer_logo.png" alt=""></a>

        <p class="footer-right">Learn to Code, Learn to be Creative.</p>
      </div>
    </footer>

    <!-- scriptタグを用いて、script.jsを読み込む -->
  <script src="script.js"></script>
  </body>
</html>
