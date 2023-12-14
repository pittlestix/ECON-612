<script lang="ts">
    import {base} from "$app/paths";
    import Modal from "$lib/modal.svelte";
    let showHomework6: boolean = false;
    let showHomework7: boolean = false;
    let showExample111: boolean = false;
    let showExample112: boolean = false;
    let showExample122: boolean = false;
    let showDiamondDybvigGameTheoreticModel: boolean = false;
    let showUnderstandingBankRuns: boolean = false;
</script>

<body class="slay">
    <table align="center" width="900px" cellpadding="60px">
    <tr>
    <td class="yuh">
        <!-- <p><span style="font-size: 24px"><b>Unit 3</b></span></p> -->
        <p>
            <!-- <center><i>This unit has no content. Please check back later.</i></center> -->
            <span style="font-size: 18px"><b>Homeworks</b></span><br>
            <!-- <a on:click={() => (showHomework6 = true)}>Homework 6</a><br> -->
            <a on:click={() => (showHomework7 = true)}>Homework 7</a>
        </p>
        <p>
            <span style="font-size: 18px"><b>Other Examples</b></span><br>
            <a on:click={() => (showExample111 = true)}>Example 11.1: Securitization</a><br>
            <!-- <a on:click={() => (showExample112 = true)}>Example 11.2: Securitization</a><br> -->
            <a on:click={() => (showExample122 = true)}>Example 12.2: The Diamond-Dybvig Model</a><br>
            <!-- <a on:click={() => (showDiamondDybvigGameTheoreticModel = true)}>Diamond-Dybvig Game Theoretic Model</a> (from slides)<br> -->
            <!-- <a on:click={() => (showUnderstandingBankRuns = true)}>Understanding Bank Runs</a> (discussion) -->
        </p>    
    </td>
    </tr>
    </table>

    <!-- Modals -->

    <Modal bind:showModal = {showHomework6}>
        <center>
            <p><b><span style="font-size: 24px">Homework 6</span></b></p>
            <p>There is no content currently available. If you believe this to be a mistake, please <b><a href="{base}/contact-me">contact me</a></b>.</p>
            <!-- <p>The following materials are available:</p> -->
            <!-- <a href=""><button class="button button1"><b>Solutions</b></button></a>
            <a href=""><button class="button button1"><b>Questions</b></button></a> -->
            <p><i>Last updated 07/30/2023.</i></p>
        </center>  
    </Modal>
    <Modal bind:showModal = {showHomework7}>
        <center>
            <p><b><span style="font-size: 24px">Homework 7</span></b></p>
            <!-- <p>There is no content currently available. If you believe this to be a mistake, please <b><a href="{base}/contact-me">contact me</a></b>.</p> -->
            <p>The following materials are available:</p>
            <a href="https://raw.githubusercontent.com/pittlestix/ECON-612/master/PDFs/unit-03-homework-7.pdf"><button class="button button1"><b>Solutions</b></button></a>
            <p><i>Last updated 12/13/2023.</i></p>
        </center>  
    </Modal>
    <Modal bind:showModal = {showExample111}>
        <center>
            <p><b><span style="font-size: 24px">Example 11.1</span></b></p>
            <!-- <p>There is no content currently available. If you believe this to be a mistake, please <b><a href="{base}/contact-me">contact me</a></b>.</p> -->
            <p>The following materials are available:</p>
            <a href="https://raw.githubusercontent.com/pittlestix/ECON-612/master/PDFs/unit-03-example-11-1-review.pdf"><button class="button button1"><b>Review</b></button></a>
            <p><i>Last updated 12/13/2023.</i></p>
        </center>  
    </Modal>
    <Modal bind:showModal = {showExample112}>
        <center>
            <p><b><span style="font-size: 24px">Example 11.2</span></b></p>
            <p>There is no content currently available. If you believe this to be a mistake, please <b><a href="{base}/contact-me">contact me</a></b>.</p>
            <!-- <p>The following materials are available:</p> -->
            <!-- <a href=""><button class="button button1"><b>Solutions</b></button></a>
            <a href=""><button class="button button1"><b>Questions</b></button></a> -->
            <p><i>Last updated 07/30/2023.</i></p>
        </center>  
    </Modal>
    <Modal bind:showModal = {showExample122}>
        <center>
            <p><b><span style="font-size: 24px">Example 12.2</span></b></p>
            <!-- <p>There is no content currently available. If you believe this to be a mistake, please <b><a href="{base}/contact-me">contact me</a></b>.</p> -->
            <p>The following materials are available:</p>
            <a href="https://raw.githubusercontent.com/pittlestix/ECON-612/master/PDFs/unit-03-example-12-2.pdf"><button class="button button1"><b>Solutions</b></button></a>
            <a href="https://raw.githubusercontent.com/pittlestix/ECON-612/master/PDFs/unit-03-example-12-2-review.pdf"><button class="button button1"><b>Review</b></button></a>
            <p><i>Last updated 12/13/2023.</i></p>
        </center>  
    </Modal>
    <Modal bind:showModal = {showDiamondDybvigGameTheoreticModel}>
        <center>
            <p><b><span style="font-size: 24px">Diamond-Dybvig Game Theoretic Model</span></b></p>
            <p>There is no content currently available. If you believe this to be a mistake, please <b><a href="{base}/contact-me">contact me</a></b>.</p>
            <!-- <p>The following materials are available:</p> -->
            <!-- <a href=""><button class="button button1"><b>Solutions</b></button></a>
            <a href=""><button class="button button1"><b>Questions</b></button></a> -->
            <p><i>Last updated 07/30/2023.</i></p>
        </center>  
    </Modal>
    <Modal bind:showModal = {showUnderstandingBankRuns}>
        <center>
            <p><b><span style="font-size: 24px">Understanding Bank Runs</span></b></p>
            <p>There is no content currently available. If you believe this to be a mistake, please <b><a href="{base}/contact-me">contact me</a></b>.</p>
            <!-- <p>The following materials are available:</p> -->
            <!-- <a href=""><button class="button button1"><b>Solutions</b></button></a>
            <a href=""><button class="button button1"><b>Questions</b></button></a> -->
            <p><i>Last updated 07/30/2023.</i></p>
        </center>  
    </Modal>
</body>

<style>
    .slay {
        background-color: #000000;
    }
    .yuh {
        background-color: #161616;
    }
    /* hr {
        width: 45px;
    } */
    a:link {
        color: #F4BC53;
        background-color: transparent;
        text-decoration: none;
    }
    a:visited {
        color: #F4BC53;
        background-color: transparent;
        text-decoration: none;
    }
    a:hover {
        color: #33A7BA;
        background-color: transparent;
        text-decoration: bold;
    }
    a:active {
        color: #F4BC53;
        background-color: transparent;
        text-decoration: bold;
    }
    b {
        font-family: Avenir Next;
    }
    /* .button {
        border: none;
        color: #FFFFFF;
        padding: 12px 28px;
        text-align: center;
        text-decoration: none;
        display: inline-block;
        font-family: Avenir Next;
        font-size: 16px;
        margin: 4px 2px;
        transition-duration: 0.4s;
        cursor: pointer;
    } */
    /* .button1 {
        background-color: #F4BC53;
    } */
    /* .button1:hover {
        background-color: #33A7BA;
    } */
    /* .button2 {
        background-color: #FF628B;
    } */
</style>