<template>
<div id="index" class="ui basic segment">
  <header class="ui icon header">
    <h1>板橋高中資訊社</h1>
    <div class="sub header">pcshic</div>
  </header>
  <section class="ui left aligned basic segment">
    <header class="ui large header">
      <i class="book icon"></i>
      <div class="content">
        講義
        <div class="sub header">OwO</div>
      </div>
    </header>
    <div class="ui doubling grid">
      <div class="ui eight wide column">
        <article class="ui blue segment">
          <header class="ui medium header">
            <i class="refresh icon"></i>
            <div class="content">
              程式與計算
              <div class="sub header">slide 01</div>
            </div>
          </header>
          <div class="ui bulleted list">
            <div class="item">
            <div class="content">
              <div class="header">程式架構</div>
              <div class="description">輸入、變數、輸出、資料型態</div>
            </div>
            </div>
            <div class="item">
              <div class="content">
                <div class="header">運算子</div>
                <div class="description">算術運算子、結合性與運算順序、比較運算子、邏輯運算子、短路運算</div>
              </div>
            </div>
            <div class="item">
              <div class="content">
                <div class="header">位元運算子</div>
                <div class="description">int 儲存形式、連續 1、遮罩與指定位元、xor 性質</div>
              </div>
            </div>
            <div class="item">
              <div class="content">
                <div class="header">其他</div>
                <div class="description">指定運算子、未定義行為</div>
              </div>
            </div>
          </div>
          <div class="ui basic right aligned segment">
            <a class="ui basic green button"
              href="http://m80126colin.github.io/icomalgo/basic/slide01.pdf"
              target="_blank">連結</a>
          </div>
        </article>
      </div>
    </div>
  </section>
</div>
</template>

<script>
export default {
  name: 'index',
  data () {
    return {}
  }
}
</script>
