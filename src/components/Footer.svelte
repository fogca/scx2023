<script>
import Logo from "./Logo.svelte";
</script>


<footer>

    <section id="footer_line">

        <h2 class="h3 uppercase" lang="en">Line Official Account</h2>
        <p class="h4">LINE公式アカウントにて新商品リリース等の<br>最新情報をいち早くお届けしています。</p>
        <a href="/" class="l-button h4">友達追加する</a>

    </section>

    <section id="footer_links">

        <h3 class="h6 half uppercase" lang="en">Our Collection</h3>
        <ul>
            <li><a href="/" lang="en">Limited</a></li>
            <li><a href="/" lang="en">Coming Soon</a></li>
            <li><a href="/" lang="en">White Spirits</a></li>
        </ul>


        <div class="jp">
            <ul>
                <li><a href="/">お問い合わせ</a></li>
                <li><a href="/">よくある質問</a></li>
                <li><a href="/">キャンセル・返金について</a></li>
                <li><a href="/">利用規約</a></li>
            </ul>
            <ul>
                <li><a href="/">メールマガジン</a></li>
                <li><a href="/">会社概要</a></li>
                <li><a href="/">プライバシーポリシー</a></li>
                <li><a href="/">特定商取引法に基づく表記</a></li>
            </ul>
        </div>

    </section>

    <section id="footer_bottom">
        <Logo />
    </section>

</footer>



<style>

footer {
    margin-top: 10rem;
    padding: 8rem 0 4rem;
    background-color: #000;
    text-align: center;
    background-image: url("/image/footer.jpg");
    background-size: cover;
}


footer * {
    color: #fff;
    text-align: center;
}

#footer_line p {margin: 1.5rem 0;}


footer .l-button {
    padding-left: 10rem;
    padding-right: 10rem;
}

#footer_links {margin-top: 4rem;}
#footer_links h3 {margin-bottom: 1.5rem;}
#footer_links a {
    font-size: 1.2rem;
    text-transform: uppercase;
    line-height: 2.2;
}
#footer_links .jp {
    margin-top: 4rem;
    display: flex;
    justify-content: center;
    align-self: start;
}
#footer_links .jp a {font-size: 1.0rem;}


#footer_bottom {
    padding-top: 6rem;
}


@media screen and (min-width: 720px) {

    footer {
        margin-top: 15rem;
        padding-top: 18rem;
        padding-bottom: 10rem;
        display: flex;
        text-align: left;
        background-position: center;
    }

}

</style>