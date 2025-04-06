<script lang="ts">
    let { children } = $props();
    import "./style.css";
</script>
<center>
    <div class = "container">
        <aside>
            <!-- FC2 Counter  Starts here -->
                <!-- svelte-ignore a11y_distracting_elements -->
                <marquee direction = "right">
                    <!-- svelte-ignore a11y_missing_attribute -->
                    <!-- svelte-ignore a11y_missing_attribute -->
                    <script language="javascript" type="text/javascript" src="//counter1.fc2.com/counter.php?id=89510396"></script><noscript><img src="//counter1.fc2.com/counter_img.php?id=89510396" /></noscript>
                </marquee>
            <!-- FC2 Counter  Ends here -->
            <h3>vote my children</h3>
            <form method="post" action="https://poll.pollcode.com/88266659">
                <div style="background-color:#EEEEEE;padding:2px;width:175px;font-family:Palatino Linotype;font-size:small;color:#B8BA7E;background-image: url('https://images.boardhost.com/bg/leather.gif');">
                    <div style="padding:2px 0px 4px 2px;">
                        <strong>opinions on the new look</strong>
                    </div>
                    <input type="radio" name="answer" value="1" id="answer882666591" style="float:left;" />
                    <label for="answer882666591" style="float:left;width:150px;">ew ew ew ugly</label>
                    <div style="clear:both;height:2px;"></div>
                    <input type="radio" name="answer" value="2" id="answer882666592" style="float:left;" />
                    <label for="answer882666592" style="float:left;width:150px;">ok</label>
                    <div style="clear:both;height:2px;"></div>
                    <div align="center" style="padding:3px;">
                        <input type="submit" value=" Vote ">&nbsp;
                        <input type="submit" name="view" value=" View ">
                    </div>
                    <div align="right" style="font-size:10px">pollcode.com <a href="https://pollcode.com/">free polls</a>
                    </div>
                </div>
            </form>
            <!-- FC2 Counter  Starts here -->
                <!-- svelte-ignore a11y_distracting_elements -->
                <marquee>
                    <!-- svelte-ignore a11y_missing_attribute -->
                    <script language="javascript" type="text/javascript" src="//counter1.fc2.com/views.php?id=89510396"></script><noscript><img src="//counter1.fc2.com/counter_now.php?id=89510396" /></noscript>
                </marquee>
            <!-- FC2 Counter  Ends here -->
        </aside>
        <main>
            <header>
                <!--<span>
                    <div id="statuscafe">
                        <div id="statuscafe-username">
                        </div>
                        <div id="statuscafe-content">
                        </div>
                    </div>
                    <script src="https://status.cafe/current-status.js?name=2254" defer></script>
                </span>-->
                <nav>
                    <span>
                        <a href = "/">home</a>
                    </span>
                    <span>
                        <a href = "/">about</a>
                        <a href = "/">diary</a>
                        <a href = "/">gallery</a>
                        <a href = "/">wrld</a>
                        <a href = "/">offsite</a>
                        <s><a href = "/">guestbook</a></s>
                    </span>
                </nav>
            </header>
            <article>
                {@render children()}
            </article>
            <footer>
                <span>This site is not copyrighted.</span>
                <span>last active : 06-04-25</span>
            </footer>
        </main>
    </div>
</center>