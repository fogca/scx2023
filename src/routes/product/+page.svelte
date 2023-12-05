<script>


</script>




<main>

  <section id="P_top">

    <img src="../image/001.jpg" alt="" class="w100">
    <div class="left">

      <div class="container center">
        <h1 class="h1" lang="en">American Oak Single Cask 2000 Nikkei [LIMITED]</h1>
        <h2 class="h4">2000年よりアメリカンオーク樽にて熟成を重ねたNikkeiシングルカスク</h2>
        <h3 class="h2" lang="en">¥36,000 <span class="h6" lang="jp">(税込)</span></h3>
        <div class="buy">
          <a href="/" class="l-button h4">今すぐ購入する</a>
        </div>
      </div>


      <div id="P_body">
        <p>私たちジャパニーズダークスピリッツ(通称：JDS)は、数百年の歴史と伝統の技術を継承する蔵元と、密接な協業体制を築くことで、非常に希少な熟成原酒を取り扱っております。そして日本の蒸溜酒、焼酎のボトラーズブランドとして、原酒の選定やブレンドに真摯に向き合い、その歴史が紡いできた、至高の味わいを追求します。</p>
    
        <div class="wrapper l-accordion">
    
          <h4 class="h6">詳細情報</h4>
          
          <input id="block-01" type="checkbox" class="toggle">
          <label class="h3" for="block-01">味わい・香り</label>
          <div class="content">
            <p>ダミーテキスト。このテキストセクションに、各タイトルに沿った概要やプロダクト紹介文を挿入する予定です。吾輩は猫である。名前はまだ無い。どこで生れたかとんと見当がつかぬ。何でも薄暗いじめじめした所でニャーニャー泣いていた事だけは記憶している。吾輩はここで始めて人間というものを見た。</p>
          </div>
    
          <input id="block-02" type="checkbox" class="toggle">
          <label class="h3" for="block-02">商品詳細</label>
          <div class="content">
            <p>ダミーテキスト。このテキストセクションに、各タイトルに沿った概要やプロダクト紹介文を挿入する予定です。吾輩は猫である。名前はまだ無い。どこで生れたかとんと見当がつかぬ。何でも薄暗いじめじめした所でニャーニャー泣いていた事だけは記憶している。吾輩はここで始めて人間というものを見た。</p>
          </div>
    
          <input id="block-03" type="checkbox" class="toggle">
          <label class="h3" for="block-03">熟成のこだわり</label>
          <div class="content">
            <p>ダミーテキスト。このテキストセクションに、各タイトルに沿った概要やプロダクト紹介文を挿入する予定です。吾輩は猫である。名前はまだ無い。どこで生れたかとんと見当がつかぬ。何でも薄暗いじめじめした所でニャーニャー泣いていた事だけは記憶している。吾輩はここで始めて人間というものを見た。</p>
          </div>
    
          <input id="block-04" type="checkbox" class="toggle">
          <label class="h3" for="block-04">蒸溜所について</label>
          <div class="content">
            <p>ダミーテキスト。このテキストセクションに、各タイトルに沿った概要やプロダクト紹介文を挿入する予定です。吾輩は猫である。名前はまだ無い。どこで生れたかとんと見当がつかぬ。何でも薄暗いじめじめした所でニャーニャー泣いていた事だけは記憶している。吾輩はここで始めて人間というものを見た。</p>
          </div>
    
        </div>
      </div>
    
      <div id="P_line">
        <div class="wrapper center">
          <h1 class="h1">予想を上回る人気につき</h1>
          <p class="center">
            現在ジャパニーズダークスピリッツとして<br>
            販売する限定商品は大変好評を頂いており、<br>
            販売開始後、数分で完売する状況が続いております。<br>
            <br>
            LINE公式アカウントにて、新商品に関する情報や<br>
            お友達限定のお得な情報をお届けしていますので、<br>
            ぜひお友達登録をしてお待ちください。
          </p>
          <a href="/" class="h4 l-button">LINE公式アカウントはこちら</a>
        </div>
      </div>

    </div>

  </section>





</main>


<style>

#P_top {margin-top: 6.4rem;}
#P_top img {
  height: 65vh;
}

#P_top .container {
  width: 80%;
  margin: 3rem auto;
}

#P_top .container h2 {margin: 1rem 0 2rem;}
#P_top .container .buy {margin-top: 2.5rem;}

#P_body .wrapper {margin: 5rem 0 8rem;}
#P_body .wrapper h4 {margin-bottom: 1rem;}

#P_line p {margin: 3rem auto;}




/***/

.toggle {
	display: none;
}
label {
	padding: 1.4rem 0 1.8rem;
	display: block;
	border-bottom: .5px solid #000;
}
label::before{		/*タイトル横の矢印*/
	content:"";
	width: 10px;
	height: 10px;
	border-top: 1px solid #000;
	border-right: 1px solid #000;
	-webkit-transform: rotate(45deg);
	position: absolute;
	top: calc( 50% - 12px );
	right: 20px;
	transform: rotate(135deg);
}
label,
.content {
	-webkit-backface-visibility: hidden;
	backface-visibility: hidden;
	transform: translateZ(0);
	transition: all 0.3s;
}
.content {		/*本文*/
	height: 0;
	margin-bottom:10px;
	padding: 0 .5rem;
	overflow: hidden;
}
.toggle:checked + label + .content {	/*開閉時*/
	height: auto;
	padding: 3rem 0.5rem 1.5rem;
	transition: .5s ease-in-out;
}
.toggle:checked + label::before {
	transform: rotate(-45deg) !important;
  top: calc( 50% - 8px );
}



@media screen and (min-width: 720px) {

  #P_top {
    padding: 0;
    display: flex;
    justify-content: center;
  }
  #P_top img {
    width: 50vw;
    height: 100vh;
    margin-left: 0;
  }

  #P_top .left {
    width: 50vw;
    height: 100vh;
    padding: 30vh 10vw 8rem;
    overflow-y: scroll;
  }

  #P_body .wrapper {margin: 10rem 0 8rem;}


}

</style>