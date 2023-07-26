<script lang="ts">
    import Modal from "$lib/modal.svelte";
    let showHomework1: boolean = false;
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
            <a href=unit_01_homework_2.html>Homework 2</a><br>
            <a href=unit_01_homework_3.html>Homework 3</a>
        </p>
        <p>
            <span style="font-size: 18px"><b>From Lectures</b></span><br>
            <a href=unit_01_advantages_of_FIs.html>The Advantages of F.I.s</a> (from slides)<br>
            <a href=unit_01_adverse_selection_with_screening.html>Adverse Selection with Screening</a> (from slides)<br>
            <a href=unit_01_moral_hazard.html>Moral Hazard</a> (from slides)<br>
            <a href=unit_01_old_money_creation>Old Money Creation</a> (from slides)
        </p>



    </td>
    </tr>
    </table>
    <Modal bind:showModal = {showHomework1}>
        <p><b><span style="font-size: 24px">Homework 1</span></b></p>
        <p>The following materials are available:</p>
        <a href="https://drive.google.com/file/d/1RvNbKGxh2VmRN-KWcY4a-beMJnZwRhtG/view?usp=share_link" target="_blank"><button class="button button1"><b>Solutions</b></button></a>
        <a href="https://drive.google.com/file/d/1wjukdtcaBgvuYpJYXFVW85IigzVvhtoD/view?usp=share_link" target="_blank"><button class="button button1"><b>Questions</b></button></a>
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