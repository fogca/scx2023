<script>
    import Logo from './Logo.svelte'
    import { fade, slide, fly } from 'svelte/transition';
    import { expoInOut, expoOut, sineInOut,quadInOut } from 'svelte/easing';
    
    </script>
    
    <div class="Menu" 
        in:fly={{ delay: 0, duration: 500, x: "-100vw", opacity: 1, easing: quadInOut }}
        out:fly={{ delay: 0, duration: 500, x: "-100vw", opacity: 1, easing: quadInOut }}
    >   
        

    <section id="M_collection">
        <a href="/collection" lang="en">Limited collection</a>
        <a href="/collection" lang="en">New collection - Coming soon</a>
        <a href="/collection" lang="en">White spirits - Shochu</a>
    </section>

    <section id="M_bottom">
        <a href="" class="l-overlay">
            <div class="container">
                <div class="h3 uppercase" lang="en">Line Official Account</div>
                <span class="h4">友達限定情報を入手する</span>
            </div>    
        </a>
        <a href="/" lang="en" class="h4 uppercase">Craftsmanship</a>
        <a href="/" lang="en" class="h4 uppercase">Restaurant and stores</a>
        <a href="/" lang="en" class="h4 uppercase">Press kit and media</a>
    
    </section>
        
        
    </div>
    
    <style>


    .Menu {
        width: 100vw;
        height: 100vh;        
        padding-top: 10.5rem;
        position: fixed;
        top: 0;
        left: 0;
        z-index: 98;
        background-color: #FEFEFE;
    }
    .Menu * {color: #000;}


    #M_collection a {
        display: block;
        font-size: 1.2rem;
        text-transform: uppercase;
        padding: 1.4rem 0 1.2rem;
        border-bottom: 1px solid rgba(150,150,150,.1);
    }

    #M_bottom {margin-top: 4rem;}
    #M_bottom .l-overlay {
        width: 100%;
        height: 50vw;
        margin-left: 0;
        background-image: url("../image/menu.jpg");
        justify-content: left;
        align-items: center;
        margin-bottom: 1.5rem;
    }

    #M_bottom a {
        display: block;
        margin-bottom: .5rem;
    }
    
    
    
    
    </style>