<script lang = 'ts'>
	import "$lib/styles.css"
	import { base } from "$app/paths";
</script>

<!-- Main body -->

<main>
	<body class = "slay">
		<table align="center" width="900px" cellpadding="60px">
		<tr>
		<td class = "yuh">
		<h1><center>Elise's Website</center></h1>
		<center>
			<a href="{base}/knit-main-code"><button class="button button1"><b>ECON 675</b></button></a> 
			<a href="{base}/ECON-612"><button class="button button1"><b>ECON 612</b></button></a>
		</center>
		</td>
		</tr>
		</table>
	</body>
	
	<p></p>
	
	<slot/>
</main>