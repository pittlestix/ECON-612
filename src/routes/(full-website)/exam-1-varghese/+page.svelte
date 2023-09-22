<script lang="ts">
    import {base} from "$app/paths";
    import Modal from "$lib/modal.svelte";
</script>

<body class="slay">
    <table align="center" width="900px" cellpadding="60px">
        <tr>
        <td class="yuh">
            <p><span style="font-size: 24px"><b>Exam Results</b></span></p>
            <p>Click to <a href="/exam-1">review the exam results</a>. This includes the grading distribution, most missed questions, and grading guidelines.</p>
            <br>
            <p>Requested exams: <a href="https://drive.google.com/file/d/1lIJ6kGYJJWDl_2Huwm2aGtdciv4nIp3c/view?usp=share_link" target="_blank">High B</a> (89), <a href="https://drive.google.com/file/d/1JB-yEP7LJp3_JvXenlGQ2lMTaYg9FK0B/view?usp=share_link" target="_blank">High C</a> (78.5)</p>
            <p>You must be logged into your TAMU Google Drive to view these files.</p>
        </td>
        </tr>
        </table>
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