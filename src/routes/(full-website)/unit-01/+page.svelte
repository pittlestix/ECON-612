<script lang="ts">
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
            <a on:click={() => (showHomework3 = true)}>Homework 3</a>
        </p>
        <p>
            <span style="font-size: 18px"><b>From Lectures</b></span><br>
            <a on:click={() => (showTheAdvantagesofFIs = true)}>The Advantages of F.I.s</a> (from slides)<br>
            <a on:click={() => (showAdverseSelectionwithScreening = true)}>Adverse Selection with Screening</a> (from slides)<br>
            <a on:click={() => (showMoralHazard = true)}>Moral Hazard</a> (from slides)<br>
            <a on:click={() => (showOldMoneyCreation = true)}>Old Money Creation</a> (from slides)
        </p>
    </td>
    </tr>
    </table>

    <!-- Modals -->

    <Modal bind:showModal = {showHomework1}>
        <center>
            <p><b><span style="font-size: 24px">Homework 1</span></b></p>
            <p>The following materials are available:</p>
            <a href="https://drive.google.com/file/d/1RvNbKGxh2VmRN-KWcY4a-beMJnZwRhtG/view?usp=share_link" target="_blank"><button class="button button1"><b>Solutions</b></button></a>
            <a href="https://drive.google.com/file/d/1wjukdtcaBgvuYpJYXFVW85IigzVvhtoD/view?usp=share_link" target="_blank"><button class="button button1"><b>Questions</b></button></a>
            <p><i>Last updated 07/21/2023.</i></p>
        </center>  
    </Modal>
    <Modal bind:showModal = {showHomework2}>
        <center>
            <p><b><span style="font-size: 24px">Homework 2</span></b></p>
            <p>The following materials are available:</p>
            <a href="https://drive.google.com/file/d/1EL_qkHjAZqF7w1_Pr0n_O7S2Tp6I-k0q/view?usp=share_link" target="_blank"><button class="button button1"><b>Solutions</b></button></a>
            <a href="https://drive.google.com/file/d/1SDkdo6QK-kU3uz9v215o6L8wXmrnBmoa/view?usp=share_link" target="_blank"><button class="button button1"><b>Questions</b></button></a>
            <p><i>Last updated 07/21/2023.</i></p>
        </center>
    </Modal>
    <Modal bind:showModal = {showHomework3}>
        <center>
            <p><b><span style="font-size: 24px">Homework 3</span></b></p>
            <p>The following materials are available:</p>
            <a href="https://drive.google.com/file/d/1JqWDPp0Zu7JoQ88vSGmpeYpr7NaKAOLK/view?usp=share_link" target="_blank"><button class="button button1"><b>Solutions</b></button></a>
            <a href="https://drive.google.com/file/d/1gd0lC7OWKsKdd9uJRKUtakkfCQ3C9Pj4/view?usp=share_link" target="_blank"><button class="button button1"><b>Questions</b></button></a>
            <p><i>Last updated 07/21/2023.</i></p>
        </center>
    </Modal>
    <Modal bind:showModal = {showTheAdvantagesofFIs}>
        <center> 
            <p><b><span style="font-size: 24px">The Advantages of FIs</span></b></p>
            <p>The following materials are available:</p>
            <a href="https://drive.google.com/file/d/13EdOz-85cL9NZ3Ru8TVS5GStTym-6Jbq/view?usp=share_link" target="_blank"><button class="button button1"><b>Solutions</b></button></a>
            <a href="https://drive.google.com/file/d/121-ViMU8uWI-LIYjeO7U7CMIaxy0aUnk/view?usp=share_link" target="_blank"><button class="button button1"><b>Questions</b></button></a>
            <p><i>Last updated 07/21/2023.</i></p>
        </center>
    </Modal>
    <Modal bind:showModal = {showAdverseSelectionwithScreening}>
        <center>
            <p><b><span style="font-size: 24px">Adverse Selection with Screening</span></b></p>
            <p>The following materials are available:</p>
            <a href="https://drive.google.com/file/d/1BHfTSIxXicZX7GZMhfJQiGfzR3HVdGec/view?usp=share_link" target="_blank"><button class="button button1"><b>Solutions</b></button></a>
            <a href="https://drive.google.com/file/d/1WUb82fo8n7NYzF3yyp_q3kZl5UI0kJOO/view?usp=share_link" target="_blank"><button class="button button1"><b>Questions</b></button></a>
            <p><i>Last updated 07/21/2023.</i></p>
        </center>
    </Modal>
    <Modal bind:showModal = {showMoralHazard}>
        <center>
            <p><b><span style="font-size: 24px">Moral Hazard</span></b></p>
            <p>The following materials are available:</p>
            <a href="https://drive.google.com/file/d/1EPRdIrOqtLM-bs7N8Jrz4cXpFhEsrenn/view?usp=share_link" target="_blank"><button class="button button1"><b>Solutions</b></button></a>
            <a href="https://drive.google.com/file/d/1YX9qxCr0y1qfwSV6UWju2pqz2Psg12jM/view?usp=share_link" target="_blank"><button class="button button1"><b>Questions</b></button></a>
            <p><i>Last updated 07/21/2023.</i></p>
        </center>
    </Modal>
    <Modal bind:showModal = {showOldMoneyCreation}>
        <center>
            <p><b><span style="font-size: 24px">Old Money Creation</span></b></p>
            <p>The following materials are available:</p>
            <a href="https://drive.google.com/file/d/1bxcgV_v6uC8qkfYjNk8SJWIutUiBwhEu/view?usp=share_link" target="_blank"><button class="button button1"><b>Solutions</b></button></a>
            <a href="https://drive.google.com/file/d/19KO7VVgfhfw26dyJ8kkxOvVoQQjCzqIn/view?usp=share_link" target="_blank"><button class="button button1"><b>Questions</b></button></a>
            <p><i>Last updated 07/21/2023.</i></p>
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
    hr {
        width: 45px;
    }
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
    .button2 {
        background-color: #FF628B;
    }
    /* The Modal (background) */
    .modal {
        display: none; /* Hidden by default */
        position: fixed; /* Stay in place */
        z-index: 1; /* Sit on top */
        left: 0;
        top: 0;
        width: 100%; /* Full width */
        height: 100%; /* Full height */
        overflow: auto; /* Enable scroll if needed */
        background-color: rgb(0,0,0); /* Fallback color */
        background-color: rgba(0,0,0,0.4); /* Black w/ opacity */
    }
    /* Modal Content/Box */
    .modal-content {
        background-color: #FEFEFE;
        margin: 15% auto; /* 15% from the top and centered */
        padding: 20px;
        border: 1px solid #888888;
        width: 80%; /* Could be more or less, depending on screen size */
    }
    /* The Close Button */
    .close {
        color: #aaa;
        float: right;
        font-size: 28px;
        font-weight: bold;
    }
    .close:hover,
    .close:focus {
        color: black;
        text-decoration: none;
        cursor: pointer;
    }
</style>