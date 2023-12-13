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
		
		<h1><center>ECON 612 Examples & Solutions</center></h1>
		
		<!-- Navigation -->
		
		<p><center>
			<a href="{base}/"><button class = "button button1"><b>Home</b></button></a>
			<a href="{base}/unit-01"><button class="button button1"><b>Unit 1</b></button></a>
			<a href="{base}/unit-02"><button class="button button1"><b>Unit 2</b></button></a>
			<a href="{base}/unit-03"><button class="button button1"><b>Unit 3</b></button></a>
		</center></p>
		
		</td>
		</tr>
		</table>
	</body>
	
	<p></p>
	
	<slot/>
</main>