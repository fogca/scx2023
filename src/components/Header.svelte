<script>
    import Logo from "./Logo.svelte";
    import { slide } from 'svelte/transition';
    import Menu from './Menu.svelte';
	import { onMount } from 'svelte';
    import { page } from '$app/stores'; 
    import { browser } from '$app/environment';

    let clicked = false;
	let isExpanded = false
	function clickHandler() {
		isExpanded = !isExpanded  
    }
</script>
    
    <header>
    
        
        <div class="left">
            <a href="/" class="h6">カート</a>
        </div>

        <div class="center">
            <a href="/" class="logo"><Logo /></a>
        </div>

        <div class="right">
            <div
            class="h6"
            class:clicked={clicked} 
            on:click="{() => clicked = !clicked}"
            on:click|preventDefault={clickHandler}
            >メニュー</div>
        </div>
    
    </header>


    {#if isExpanded}
    <Menu />
    {/if}
    
    
<style>
    
header {
    width: 100vw;
    padding: 2.5rem var(--padding) 1.8rem;
    position: fixed;
    z-index: 99;
    display: flex;
    justify-content: space-between;
    align-items: center;
    top: 0;
    left: 0;
    background-color: var(--backgroundColor);
    border-bottom: 1px rgba(150,150,150,0.1) solid;
}
header .center {height: 2rem;}


@media screen and (min-width: 720px) {

    
    header {
        padding: 2.5rem var(--pcPadding) 1.8rem;
    }


}
    
    
    
</style>