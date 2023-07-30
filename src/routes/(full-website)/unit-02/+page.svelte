<script lang="ts">
    import Modal from "$lib/modal.svelte";
    let showHomework4: boolean = false;
    let showHomework5: boolean = false;
    let showExample71: boolean = false;
    let showExample72: boolean = false;
    let showExample73: boolean = false;
    let showExample74: boolean = false;
    let showExample76: boolean = false;
    let showExample84: boolean = false;
    let showExample85: boolean = false;
    let showExample86: boolean = false;
    let showExample87: boolean = false;
    let showExample88: boolean = false;
</script>

<body class="slay">
    <table align="center" width="900px" cellpadding="60px">
    <tr>
    <td class="yuh">
        <p><span style="font-size: 24px"><b>Unit 2</b></span></p>
        <p>
            <span style="font-size: 18px"><b>Homeworks</b></span><br>
            <a on:click={() => (showHomework4 = true)}>Homework 4</a><span style="color: #FF628B">*</span><br>
            <a on:click={() => (showHomework5 = true)}>Homework 5</a><span style="color: #FF628B">*</span>
        </p>
        <p>
            <span style="font-size: 18px"><b>From Lectures</b></span><br>
            <a on:click={() => (showExample71 = true)}>Example 7.1: Self-Investment Incentives</a><span style="color: #FF628B">*</span><br>
            <a on:click={() => (showExample72 = true)}>Example 7.2: Signaling Profitability</a><span style="color: #FF628B">*</span><br>
            <a on:click={() => (showExample73 = true)}>Example 7.3: Collateral as a Sorting Device</a><span style="color: #FF628B">*</span><br>
            <a on:click={() => (showExample74 = true)}>Example 7.4: Collateral in Moral Hazard</a><span style="color: #FF628B">*</span><br>
            <a on:click={() => (showExample76 = true)}>Example 7.6: Moral Hazard of Effort</a><span style="color: #FF628B">*</span><br>
            <a on:click={() => (showExample84 = true)}>Example 8.4: Multi-Period Contracts</a><span style="color: #FF628B">*</span> (from slides)<br>
            <a on:click={() => (showExample85 = true)}>Example 8.5: Learning over Time</a><span style="color: #FF628B">*</span> (from slides)<br>
            <a on:click={() => (showExample86 = true)}>Example 8.6: Restructuring</a><span style="color: #FF628B">*</span> (from slides)<br>
            <a on:click={() => (showExample87 = true)}>Example 8.7: Restructuring with Multiple Creditors</a><span style="color: #FF628B">*</span> (from slides)<br>
            <a on:click={() => (showExample88 = true)}>Example 8.8: Creditor Coalitions and Coordination Problems</a><span style="color: #FF628B">*</span>
        </p>
        <p><span style="font-size: 12px"><span style="color: #FF628B">*</span> This content is from the previous academic year and has not been updated to reflect this year's lecture content. This is likely due to the content not yet being covered.</span></p>
    </td>
    </tr>
    </table>

    <!-- Modals -->

    <Modal bind:showModal = {showHomework4}>
        <center>
            <p><b><span style="font-size: 24px">Homework 4</span></b></p>
            <p>There is no content currently available. If you believe this to be a mistake, please <b><a href="/contact-me">contact me</a></b>.</p>
            <!-- <p>The following materials are available:</p> -->
            <!-- <a href="" target="_blank"><button class="button button1"><b>Solutions</b></button></a>
            <a href="" target="_blank"><button class="button button1"><b>Questions</b></button></a> -->
            <p><i>Last updated 07/30/2023.</i></p>
        </center>  
    </Modal>
    <Modal bind:showModal = {showHomework5}>
        <center>
            <p><b><span style="font-size: 24px">Homework 5</span></b></p>
            <p>There is no content currently available. If you believe this to be a mistake, please <b><a href="/contact-me">contact me</a></b>.</p>
            <!-- <p>The following materials are available:</p> -->
            <!-- <a href="" target="_blank"><button class="button button1"><b>Solutions</b></button></a>
            <a href="" target="_blank"><button class="button button1"><b>Questions</b></button></a> -->
            <p><i>Last updated 07/30/2023.</i></p>
        </center>  
    </Modal>
    <Modal bind:showModal = {showExample71}>
        <center>
            <p><b><span style="font-size: 24px">Example 7.1</span></b></p>
            <!-- <p>There is no content currently available. If you believe this to be a mistake, please <b><a href="/contact-me">contact me</a></b>.</p> -->
            <p>The following materials are available:</p>
            <!-- <a href="" target="_blank"><button class="button button1"><b>Solutions</b></button></a> -->
            <a href="https://drive.google.com/file/d/1KhMjJgc62dxMeGUz21bg3hQLtda8dJgH/view?usp=share_link" target="_blank"><button class="button button1"><b>Questions</b></button></a>
            <p><i>Last updated 07/30/2023.</i></p>
        </center>  
    </Modal>
    <Modal bind:showModal = {showExample72}>
        <center>
            <p><b><span style="font-size: 24px">Example 7.2</span></b></p>
            <p>There is no content currently available. If you believe this to be a mistake, please <b><a href="/contact-me">contact me</a></b>.</p>
            <!-- <p>The following materials are available:</p> -->
            <!-- <a href="" target="_blank"><button class="button button1"><b>Solutions</b></button></a>
            <a href="" target="_blank"><button class="button button1"><b>Questions</b></button></a> -->
            <p><i>Last updated 07/30/2023.</i></p>
        </center>  
    </Modal>
    <Modal bind:showModal = {showExample73}>
        <center>
            <p><b><span style="font-size: 24px">Example 7.3</span></b></p>
            <!-- <p>There is no content currently available. If you believe this to be a mistake, please <b><a href="/contact-me">contact me</a></b>.</p> -->
            <p>The following materials are available:</p>
            <a href="https://drive.google.com/file/d/1ieE1YoJ-wE2-Sv_2BBOThL0poxYbAT5Q/view?usp=share_link" target="_blank"><button class="button button1"><b>Solutions</b></button></a>
            <a href="https://drive.google.com/file/d/1W2ivXSKuKlIrWOC7LfJxUalsR81SZJIW/view?usp=share_link" target="_blank"><button class="button button1"><b>Questions</b></button></a>
            <p><i>Last updated 07/30/2023.</i></p>
        </center>  
    </Modal>
    <Modal bind:showModal = {showExample74}>
        <center>
            <p><b><span style="font-size: 24px">Example 7.4</span></b></p>
            <!-- <p>There is no content currently available. If you believe this to be a mistake, please <b><a href="/contact-me">contact me</a></b>.</p> -->
            <p>The following materials are available:</p>
            <a href="https://drive.google.com/file/d/1LsWq6tjDsnwe80XNiVybVPezK2_qbmNM/view?usp=share_link" target="_blank"><button class="button button1"><b>Solutions</b></button></a>
            <a href="https://drive.google.com/file/d/1z_uD-OZ9xeEJcCNW9hYLTzdC77tM89w2/view?usp=share_link" target="_blank"><button class="button button1"><b>Questions</b></button></a>
            <p><i>Last updated 07/30/2023.</i></p>
        </center>  
    </Modal>
    <Modal bind:showModal = {showExample76}>
        <center>
            <p><b><span style="font-size: 24px">Example 7.6</span></b></p>
            <p>There is no content currently available. If you believe this to be a mistake, please <b><a href="/contact-me">contact me</a></b>.</p>
            <!-- <p>The following materials are available:</p> -->
            <!-- <a href="" target="_blank"><button class="button button1"><b>Solutions</b></button></a>
            <a href="" target="_blank"><button class="button button1"><b>Questions</b></button></a> -->
            <p><i>Last updated 07/30/2023.</i></p>
        </center>  
    </Modal>
    <Modal bind:showModal = {showExample84}>
        <center>
            <p><b><span style="font-size: 24px">Example 8.4</span></b></p>
            <p>There is no content currently available. If you believe this to be a mistake, please <b><a href="/contact-me">contact me</a></b>.</p>
            <!-- <p>The following materials are available:</p> -->
            <!-- <a href="" target="_blank"><button class="button button1"><b>Solutions</b></button></a>
            <a href="" target="_blank"><button class="button button1"><b>Questions</b></button></a> -->
            <p><i>Last updated 07/30/2023.</i></p>
        </center>  
    </Modal>
    <Modal bind:showModal = {showExample85}>
        <center>
            <p><b><span style="font-size: 24px">Example 8.5</span></b></p>
            <p>There is no content currently available. If you believe this to be a mistake, please <b><a href="/contact-me">contact me</a></b>.</p>
            <!-- <p>The following materials are available:</p> -->
            <!-- <a href="" target="_blank"><button class="button button1"><b>Solutions</b></button></a>
            <a href="" target="_blank"><button class="button button1"><b>Questions</b></button></a> -->
            <p><i>Last updated 07/30/2023.</i></p>
        </center>  
    </Modal>
    <Modal bind:showModal = {showExample86}>
        <center>
            <p><b><span style="font-size: 24px">Example 8.6</span></b></p>
            <p>There is no content currently available. If you believe this to be a mistake, please <b><a href="/contact-me">contact me</a></b>.</p>
            <!-- <p>The following materials are available:</p> -->
            <!-- <a href="" target="_blank"><button class="button button1"><b>Solutions</b></button></a>
            <a href="" target="_blank"><button class="button button1"><b>Questions</b></button></a> -->
            <p><i>Last updated 07/30/2023.</i></p>
        </center>  
    </Modal>
    <Modal bind:showModal = {showExample87}>
        <center>
            <p><b><span style="font-size: 24px">Example 8.7</span></b></p>
            <p>There is no content currently available. If you believe this to be a mistake, please <b><a href="/contact-me">contact me</a></b>.</p>
            <!-- <p>The following materials are available:</p> -->
            <!-- <a href="" target="_blank"><button class="button button1"><b>Solutions</b></button></a>
            <a href="" target="_blank"><button class="button button1"><b>Questions</b></button></a> -->
            <p><i>Last updated 07/30/2023.</i></p>
        </center>  
    </Modal>
    <Modal bind:showModal = {showExample88}>
        <center>
            <p><b><span style="font-size: 24px">Example 8.8</span></b></p>
            <p>There is no content currently available. If you believe this to be a mistake, please <b><a href="/contact-me">contact me</a></b>.</p>
            <!-- <p>The following materials are available:</p> -->
            <!-- <a href="" target="_blank"><button class="button button1"><b>Solutions</b></button></a>
            <a href="" target="_blank"><button class="button button1"><b>Questions</b></button></a> -->
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
    .button {
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
    }
    .button1 {
        background-color: #F4BC53;
    }
    .button1:hover {
        background-color: #33A7BA;
    }
    /* .button2 {
        background-color: #FF628B;
    } */
</style>
    