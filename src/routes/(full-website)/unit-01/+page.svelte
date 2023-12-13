<script lang="ts">
    import {base} from "$app/paths";
    import Modal from "$lib/modal.svelte";
    let showHomework1: boolean = false;
    let showHomework2: boolean = false;
    let showHomework3: boolean = false;
    let showTheAdvantagesofFIs: boolean = false;
    let showAdverseSelectionwithScreening: boolean = false;
    let showMoralHazard: boolean = false;
    let showOldMoneyCreation: boolean = false;
</script>

<!-- To add a modal: make sure that make a new Boolean at the top and then add a new modal where you want in the text -->

<body class="slay">
    <table align="center" width="900px" cellpadding="60px">
    <tr>
    <td class="yuh">
        <p><span style="font-size: 24px"><b>Unit 1</b></span></p>
        <p>
            <span style="font-size: 18px"><b>Homeworks</b></span><br>
            <a on:click={() => (showHomework1 = true)}>Homework 1</a><br>
            <a on:click={() => (showHomework2 = true)}>Homework 2</a><br>
            <!-- <a on:click={() => (showHomework3 = true)}>Homework 3</a> -->
        </p>
        <p>
            <span style="font-size: 18px"><b>From Lectures</b></span><br>
            <a on:click={() => (showTheAdvantagesofFIs = true)}>The Advantages of F.I.s</a><br>
            <a on:click={() => (showAdverseSelectionwithScreening = true)}>Adverse Selection with Screening</a><br>
            <a on:click={() => (showMoralHazard = true)}>Moral Hazard</a><br>
            <a on:click={() => (showOldMoneyCreation = true)}>Old Money Creation</a>
        </p>
        <!-- <p>
            <span style="font-size: 18px"><b>Review Materials</b></span><br>
            <a href="https://drive.google.com/file/d/1E4BGnd0VGszbuGRekmKs_7nGp_0YrkZd/view?usp=share_link" target="_blank">Exam 1 Review Slides</a><br>
            <a href="https://youtu.be/hggeYwvviso" target="_blank">Exam 1 Review Recording</a>
        </p>         -->
    </td>
    </tr>
    </table>

    <!-- Modals -->

    <Modal bind:showModal = {showHomework1}>
        <center>
            <p><b><span style="font-size: 24px">Homework 1</span></b></p>
            <!-- <p>There is no content currently available. If you believe this to be a mistake, please <b><a href="{base}/contact-me">contact me</a></b>.</p> -->
            <p>The following materials are available:</p>
            <a href="https://raw.githubusercontent.com/pittlestix/ECON-612/master/PDFs/unit-01-homework-1.pdf"><button class="button button1"><b>Solutions</b></button></a>
            <p><i>Last updated 12/11/2023.</i></p>

            
        </center>  
    </Modal>
    <Modal bind:showModal = {showHomework2}>
        <center>
            <p><b><span style="font-size: 24px">Homework 2</span></b></p>
            <!-- <p>There is no content currently available. If you believe this to be a mistake, please <b><a href="{base}/contact-me">contact me</a></b>.</p> -->
            <p>The following materials are available:</p>
            <a href="https://raw.githubusercontent.com/pittlestix/ECON-612/master/PDFs/unit-01-homework-2.pdf"><button class="button button1"><b>Solutions</b></button></a>
            <p><i>Last updated 12/11/2023.</i></p>
        </center>
    </Modal>
    <Modal bind:showModal = {showHomework3}>
        <center>
            <p><b><span style="font-size: 24px">Homework 3</span></b></p>
            <!-- <p>There is no content currently available. If you believe this to be a mistake, please <b><a href="{base}/contact-me">contact me</a></b>.</p> -->
            <p>The following materials are available:</p>
            <a href="https://raw.githubusercontent.com/pittlestix/ECON-612/master/PDFs/unit-01-homework-3.pdf"><button class="button button1"><b>Solutions</b></button></a>
            <p><i>Last updated 12/12/2023.</i></p>
        </center>
    </Modal>
    <Modal bind:showModal = {showTheAdvantagesofFIs}>
        <center> 
            <p><b><span style="font-size: 24px">The Advantages of F.I.s</span></b></p>
            <!-- <p>There is no content currently available. If you believe this to be a mistake, please <b><a href="{base}/contact-me">contact me</a></b>.</p> -->
            <p>The following materials are available:</p>
            <a href="https://raw.githubusercontent.com/pittlestix/ECON-612/master/PDFs/unit-01-advantages-of-FIs.pdf"><button class="button button1"><b>Solutions</b></button></a>
            <p><i>Last updated 12/12/2023.</i></p>
        </center>
    </Modal>
    <Modal bind:showModal = {showAdverseSelectionwithScreening}>
        <center>
            <p><b><span style="font-size: 24px">Adverse Selection with Screening</span></b></p>
            <!-- <p>There is no content currently available. If you believe this to be a mistake, please <b><a href="{base}/contact-me">contact me</a></b>.</p> -->
            <p>The following materials are available:</p>
            <a href="https://raw.githubusercontent.com/pittlestix/ECON-612/master/PDFs/unit-01-adverse-selection-with-screening.pdf"><button class="button button1"><b>Solutions</b></button></a>
            <p><i>Last updated 12/12/2023.</i></p>
        </center>
    </Modal>
    <Modal bind:showModal = {showMoralHazard}>
        <center>
            <p><b><span style="font-size: 24px">Moral Hazard</span></b></p>
            <!-- <p>There is no content currently available. If you believe this to be a mistake, please <b><a href="{base}/contact-me">contact me</a></b>.</p> -->
            <p>The following materials are available:</p>
            <a href="https://raw.githubusercontent.com/pittlestix/ECON-612/master/PDFs/unit-01-moral-hazard.pdf"><button class="button button1"><b>Solutions</b></button></a>
            <p><i>Last updated 12/12/2023.</i></p>
        </center>
    </Modal>
    <Modal bind:showModal = {showOldMoneyCreation}>
        <center>
            <p><b><span style="font-size: 24px">Old Money Creation</span></b></p>
            <!-- <p>There is no content currently available. If you believe this to be a mistake, please <b><a href="{base}/contact-me">contact me</a></b>.</p> -->
            <p>The following materials are available:</p>
            <a href="https://raw.githubusercontent.com/pittlestix/ECON-612/master/PDFs/unit-01-old-money-creation.pdf"><button class="button button1"><b>Solutions</b></button></a>
            <p><i>Last updated 12/12/2023.</i></p>
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