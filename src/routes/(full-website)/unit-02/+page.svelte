<script lang="ts">
    import {base} from "$app/paths";
    import Modal from "$lib/modal.svelte";
    let showHomework4: boolean = false;
    let showHomework5: boolean = false;
    let showExample71: boolean = false;
    let showExample72: boolean = false;
    let showExample73: boolean = false;
    let showExample74: boolean = false;
    let showExample76: boolean = false;
    let showExample82: boolean = false;
    let showExample84: boolean = false;
    let showExample85: boolean = false;
    let showExample86: boolean = false;
    let showExample87: boolean = false;
    let showExample88: boolean = false;
    let showExam2Review: boolean = false;
</script>

<body class="slay">
    <table align="center" width="900px" cellpadding="60px">
    <tr>
    <td class="yuh">
        <p><span style="font-size: 24px"><b>Unit 2</b></span></p>
        <p>
            <span style="font-size: 18px"><b>Homeworks</b></span><br>
            <a on:click={() => (showHomework4 = true)}>Homework 4</a><br>
            <a on:click={() => (showHomework5 = true)}>Homework 5</a><span style="color: #FF628B">*</span>
        </p>
        <p>
            <span style="font-size: 18px"><b>From Lectures</b></span><br>
            <a on:click={() => (showExample73 = true)}>Example 7.3: Adverse Selection with Collateral</a><span style="color: #FF628B">*</span><br>
            <a on:click={() => (showExample74 = true)}>Example 7.4: Moral Hazard with Collateral</a><span style="color: #FF628B">*</span><br>
            <a on:click={() => (showExample76 = true)}>Example 7.6: Moral Hazard of Effort</a><span style="color: #FF628B">*</span><br>
            <a on:click={() => (showExample82 = true)}>Example 8.2: Credit Rationing</a><span style="color: #FF628B">*</span><br>
            <a on:click={() => (showExample84 = true)}>Example 8.4: Multi-Period Contracts</a><span style="color: #FF628B">*</span><br>
            <a on:click={() => (showExample85 = true)}>Example 8.5: Bayesian Updating</a><br>
            <a on:click={() => (showExample86 = true)}>Example 8.6: Restructuring</a><span style="color: #FF628B">*</span><br>
            <a on:click={() => (showExample87 = true)}>Example 8.7: Restructuring with Multiple Creditors</a><span style="color: #FF628B">*</span><br>
            UPLOAD <a on:click={() => (showExample88 = true)}>Example 8.8: Creditor Coalitions and Coordination Problems</a><span style="color: #FF628B">*</span>
        </p>
        <p>
            <span style="font-size: 18px"><b>Review Materials</b></span><br>
            <a on:click={() => (showExam2Review = true)}>Exam 2 Review Slides</a><br>
            <a href="https://youtu.be/yOX_2al_-hc" target="_blank">Exam 2 Review Recording</a>
        </p>
        <p><span style="font-size: 12px"><span style="color: #FF628B">*</span> This content has a different structure than the one presented in class or posted on Canvas. While the answers and processes should be the same, the structure or wording of the questions is altered. I suggest you reference the provided Questions file, which you can access separately or at the end of the Solutions file.</span></p>
    </td>
    </tr>
    </table>

    <!-- Modals -->

    <Modal bind:showModal = {showHomework4}>
        <center>
            <p><b><span style="font-size: 24px">Homework 4</span></b></p>
            <!-- <p>There is no content currently available. If you believe this to be a mistake, please <b><a href="{base}/contact-me">contact me</a></b>.</p> -->
            <p>The following materials are available:</p>
            <a href="https://drive.google.com/file/d/1bW_OSsAn-GxO0I1_DKEJKQ6dgsSXwewa/view?usp=share_link" target="_blank"><button class="button button1"><b>Solutions</b></button></a>
            <a href="https://drive.google.com/file/d/16y-GxeyRoD1EnEsQOZb429Hml2lngS8l/view?usp=share_link" target="_blank"><button class="button button1"><b>Questions</b></button></a>
            <p><i>Last updated 10/06/2023.</i></p>
        </center>  
    </Modal>
    <Modal bind:showModal = {showHomework5}>
        <center>
            <p><b><span style="font-size: 24px">Homework 5</span></b></p>
            <p>There is no content currently available. If you believe this to be a mistake, please <b><a href="{base}/contact-me">contact me</a></b>.</p>
            <p>The following materials are available:</p>
            <a href="https://drive.google.com/file/d/1kCQkCPnb3nRMInSwvSHZhMpdCbJivFdV/view?usp=share_link" target="_blank"><button class="button button1"><b>Solutions</b></button></a>
            <a href="https://drive.google.com/file/d/1n529cBK_EEDXF8rWRvVWO_sBF0DDpE0m/view?usp=share_link" target="_blank"><button class="button button1"><b>Questions</b></button></a>
            <p><i>Last updated 10/24/2023.</i></p>
        </center>  
    </Modal>
    <Modal bind:showModal = {showExample71}>
        <center>
            <p><b><span style="font-size: 24px">Example 7.1</span></b></p>
            <!-- <p>There is no content currently available. If you believe this to be a mistake, please <b><a href="{base}/contact-me">contact me</a></b>.</p> -->
            <p>The following materials are available:</p>
            <a href="https://drive.google.com/file/d/1zMYIqe0wohUEs4cUBnIxGZ4j_6hWQapi/view?usp=share_link" target="_blank"><button class="button button1"><b>Solutions</b></button></a>
            <a href="https://drive.google.com/file/d/1KhMjJgc62dxMeGUz21bg3hQLtda8dJgH/view?usp=share_link" target="_blank"><button class="button button1"><b>Questions</b></button></a>
            <p><i>Last updated 07/31/2023.</i></p>
        </center>  
    </Modal>
    <Modal bind:showModal = {showExample72}>
        <center>
            <p><b><span style="font-size: 24px">Example 7.2</span></b></p>
            <!-- <p>There is no content currently available. If you believe this to be a mistake, please <b><a href="{base}/contact-me">contact me</a></b>.</p> -->
            <p>The following materials are available:</p>
            <a href="https://drive.google.com/file/d/1RMAFEwRUe0hVq-muyixxthxOdskTo6jQ/view?usp=share_link" target="_blank"><button class="button button1"><b>Solutions</b></button></a>
            <a href="https://drive.google.com/file/d/10PcwmdrN1BDH7BYfRsJhmeO9pu33mgTj/view?usp=share_link" target="_blank"><button class="button button1"><b>Questions</b></button></a>
            <p><i>Last updated 08/03/2023.</i></p>
        </center>  
    </Modal>
    <Modal bind:showModal = {showExample73}>
        <center>
            <p><b><span style="font-size: 24px">Example 7.3</span></b></p>
            <!-- <p>There is no content currently available. If you believe this to be a mistake, please <b><a href="{base}/contact-me">contact me</a></b>.</p> -->
            <p>The following materials are available:</p>
            <a href="https://drive.google.com/file/d/1ieE1YoJ-wE2-Sv_2BBOThL0poxYbAT5Q/view?usp=share_link" target="_blank"><button class="button button1"><b>Solutions</b></button></a>
            <a href="https://drive.google.com/file/d/1W2ivXSKuKlIrWOC7LfJxUalsR81SZJIW/view?usp=share_link" target="_blank"><button class="button button1"><b>Questions</b></button></a>
            <p><i>Last updated 10/05/2023.</i></p>
        </center>  
    </Modal>
    <Modal bind:showModal = {showExample74}>
        <center>
            <p><b><span style="font-size: 24px">Example 7.4</span></b></p>
            <!-- <p>There is no content currently available. If you believe this to be a mistake, please <b><a href="{base}/contact-me">contact me</a></b>.</p> -->
            <p>The following materials are available:</p>
            <a href="https://drive.google.com/file/d/1ZGreuGTw5LNYv640_zayHOzVxIGaoePN/view?usp=share_link" target="_blank"><button class="button button1"><b>Solutions</b></button></a>
            <a href="https://drive.google.com/file/d/1ux_kpQwSKzDcJmHGYePyF5rwvOJ24vxl/view?usp=share_link" target="_blank"><button class="button button1"><b>Questions</b></button></a>
            <p><i>Last updated 10/24/2023.</i></p>
        </center>  
    </Modal>
    <Modal bind:showModal = {showExample76}>
        <center>
            <p><b><span style="font-size: 24px">Example 7.6</span></b></p>
            <!-- <p>There is no content currently available. If you believe this to be a mistake, please <b><a href="{base}/contact-me">contact me</a></b>.</p> -->
            <p>The following materials are available:</p>
            <a href="https://drive.google.com/file/d/158ej7DEVLRoRCG-cIWQsvP9dKDXuRRxq/view?usp=share_link" target="_blank"><button class="button button1"><b>Solutions</b></button></a>
            <a href="https://drive.google.com/file/d/1uRlSzRqu-6AqBLUSOcaasnlvw0YHp2yb/view?usp=share_link" target="_blank"><button class="button button1"><b>Questions</b></button></a>
            <p><i>Last updated 10/24/2023.</i></p>
        </center>
    </Modal>
    <Modal bind:showModal = {showExample82}>
        <center>
            <p><b><span style="font-size: 24px">Example 8.2</span></b></p>
            <!-- <p>There is no content currently available. If you believe this to be a mistake, please <b><a href="{base}/contact-me">contact me</a></b>.</p> -->
            <p>The following materials are available:</p>
            <a href="https://drive.google.com/file/d/1LQH1rohrw6VuARRA3OC8NjVI4hB0eCJv/view?usp=share_link" target="_blank"><button class="button button1"><b>Solutions</b></button></a>
            <a href="https://drive.google.com/file/d/16d-BrPwRElwLfSM9C93rZmt6UBj8ZThU/view?usp=share_link" target="_blank"><button class="button button1"><b>Questions</b></button></a>
            <p><i>Last updated 10/24/2023.</i></p>
        </center>  
    </Modal>
    <Modal bind:showModal = {showExample84}>
        <center>
            <p><b><span style="font-size: 24px">Example 8.4</span></b></p>
            <!-- <p>There is no content currently available. If you believe this to be a mistake, please <b><a href="{base}/contact-me">contact me</a></b>.</p> -->
            <p>The following materials are available:</p>
            <a href="https://drive.google.com/file/d/165T-CEUpTsB5cQRgKKL_tahE3wurGgTL/view?usp=share_link" target="_blank"><button class="button button1"><b>Solutions</b></button></a>
            <a href="https://drive.google.com/file/d/1-W0cibvwKiDi6sqXLjr-4uXC7y4j8Fd8/view?usp=share_link" target="_blank"><button class="button button1"><b>Questions</b></button></a>
            <p><i>Last updated 10/24/2023.</i></p>
        </center>  
    </Modal>
    <Modal bind:showModal = {showExample85}>
        <center>
            <p><b><span style="font-size: 24px">Example 8.5</span></b></p>
            <!-- <p>There is no content currently available. If you believe this to be a mistake, please <b><a href="{base}/contact-me">contact me</a></b>.</p> -->
            <p>The following materials are available:</p>
            <a href="https://drive.google.com/file/d/1qT7LXVerm0Q6at-vWcc0FrneXWygs5g1/view?usp=share_link" target="_blank"><button class="button button1"><b>Solutions</b></button></a>
            <a href="https://drive.google.com/file/d/1JqOueYgo9sgRdPyaK47ZX--6ZU-0W5O7/view?usp=share_link" target="_blank"><button class="button button1"><b>Questions</b></button></a>
            <p><i>Last updated 10/24/2023.</i></p>
        </center>  
    </Modal>
    <Modal bind:showModal = {showExample86}>
        <center>
            <p><b><span style="font-size: 24px">Example 8.6</span></b></p>
            <!-- <p>There is no content currently available. If you believe this to be a mistake, please <b><a href="{base}/contact-me">contact me</a></b>.</p> -->
            <p>The following materials are available:</p>
            <a href="https://drive.google.com/file/d/1ALOXgAlxT7K5qEIn1l6WWlQLpLXpewl2/view?usp=share_link" target="_blank"><button class="button button1"><b>Solutions</b></button></a>
            <a href="https://drive.google.com/file/d/1WuF4C3WZqU9dhHf_bNHcDQjSa9_eGOQ0/view?usp=share_link" target="_blank"><button class="button button1"><b>Questions</b></button></a>
            <p><i>Last updated 07/30/2023.</i></p>
        </center>  
    </Modal>
    <Modal bind:showModal = {showExample87}>
        <center>
            <p><b><span style="font-size: 24px">Example 8.7</span></b></p>
            <!-- <p>There is no content currently available. If you believe this to be a mistake, please <b><a href="{base}/contact-me">contact me</a></b>.</p> -->
            <p>The following materials are available:</p>
            <a href="https://drive.google.com/file/d/1Xh_IqfyW4QkfOHQ56reJKkvVAZW_tw57/view?usp=share_link" target="_blank"><button class="button button1"><b>Solutions</b></button></a>
            <a href="https://drive.google.com/file/d/1PaIGvLX-8Yq-XEAAbHC-2UYdkum6qEN1/view?usp=share_link" target="_blank"><button class="button button1"><b>Questions</b></button></a>
            <p><i>Last updated 10/08/2023.</i></p>
        </center>  
    </Modal>
    <Modal bind:showModal = {showExample88}>
        <center>
            <p><b><span style="font-size: 24px">Example 8.8</span></b></p>
            <!-- <p>There is no content currently available. If you believe this to be a mistake, please <b><a href="{base}/contact-me">contact me</a></b>.</p> -->
            <p>The following materials are available:</p>
            <a href="https://drive.google.com/file/d/1IEm-tbvbwZbWse6m5TNKPbSym11V60tW/view?usp=share_link" target="_blank"><button class="button button1"><b>Solutions</b></button></a>
            <a href="https://drive.google.com/file/d/1OuixGRpsPps_ox2XNxPh6RZ6AoMbVpc0/view?usp=share_link" target="_blank"><button class="button button1"><b>Questions</b></button></a>
            <p><i>Last updated 10/24/2023.</i></p>
        </center>  
    </Modal>
    <Modal bind:showModal = {showExam2Review}>
        <center>
            <p><b><span style="font-size: 24px">Exam 2 Review</span></b></p>
            <!-- <p>There is no content currently available. If you believe this to be a mistake, please <b><a href="{base}/contact-me">contact me</a></b>.</p> -->
            <p>The following materials are available:</p>
            <a href="https://drive.google.com/file/d/19KIhe4-O1kKOMJpgduVkbXjIX1AY-aK-/view?usp=share_link" target="_blank"><button class="button button1"><b>Solutions</b></button></a>
            <a href="https://drive.google.com/file/d/1zYzErtqhBaFQDy9iiICPI4h-ng8sWDFI/view?usp=share_link" target="_blank"><button class="button button1"><b>Questions</b></button></a>
            <p><i>Last updated 10/24/2023.</i></p>
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
    