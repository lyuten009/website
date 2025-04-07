<script lang="ts">
    let { children } = $props();
    import "./style.css";
</script>
<div class = "decor">
    <div class = "top">
        <a href = "/">
            <img src = "https://media.discordapp.net/attachments/1268388793250222193/1358681248595447929/return_to_top.png?ex=67f4ba04&is=67f36884&hm=4aaa896456d8dc0e8c7fe61acb6423bafd6d378e47c1d12f8a40cba29e1836c2&=&format=webp&quality=lossless" alt = "my son">
        </a>
    </div>
</div>
<center>
    <div class = "container">
        <aside>
            <h3>navigation</h3>
            <nav>
                <a href = "/">home</a>
                <a href = "/">about</a>
                <a href = "/">diary</a>
                <a href = "/">gallery</a>
                <a href = "/">wlrd</a>
                <a href = "/">offsite</a>
            </nav>
            <img src = "https://99gifshop.neocities.org/img/88x31.png" alt = "99gifshop button">
        </aside>
        <main>
            <header>
                <h3>header...</h3>
            </header>
            <article>
                {@render children()}
            </article>
            <footer>
                <span>This site is not copyrighted.</span>
                <span>last active : 07-04-25</span>
            </footer>
        </main>
    </div>
</center>