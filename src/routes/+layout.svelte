<script>
    import './app.css'

    /**
     * uncomment to fix
     */
    // import { afterNavigate } from '$app/navigation';

    // afterNavigate(() => {
    //     document.getElementById('page')?.scrollTo(0, 0);
    // }); 
</script>

<div class="root">
    <div class="header">
        header
    </div>
    <div class="body" id="page">
        <div class="content">
            <p>every page is really long</p>
            <p>every page is really long</p>
            <p>every page is really long</p>
            <p>every page is really long</p>
            <p>every page is really long</p>
            <p>every page is really long</p>
            <p>every page is really long</p>
            <p>every page is really long</p>
            <p>every page is really long</p>
            <p>every page is really long</p>
            <p>every page is really long</p>
            <p>every page is really long</p>
            <p>every page is really long</p>
            <p>every page is really long</p>
            <p>every page is really long</p>
            <p>every page is really long</p>
            <p>every page is really long</p>
            <p>every page is really long</p>
            <p>every page is really long</p>
            <slot />
        </div>
        <div class="footer">
            footer
        </div>
    </div>
</div>

<style>
    .root {
        height: 100vh;
        overflow: hidden;
        display: flex;
        flex-direction: column;
    }
    .header {
        padding: 32px;
        background: #eaeaea;
        border-bottom: 1px solid #000;
    }
    .body {
        flex-grow: 1;
        display: flex;
        flex-direction: column;
        overflow: auto;
    }
    .content {
        flex-grow: 1;
        padding: 32px;
    }
    .footer {
        border-top: 1px solid #000;
        background: #eaeaea;
        padding: 32px;
    }
</style>