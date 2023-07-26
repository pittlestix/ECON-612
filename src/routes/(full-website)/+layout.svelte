<script lang = 'ts'>
	import "$lib/styles.css"
</script>

<!-- A message for Elise: npm run dev -->

<!-- Main body -->

<main>
	<body class = "slay">
		<table align="center" width="900px" cellpadding="60px">
		<tr>
		<td class = "yuh">
		
		<h1><center>ECON 612 Examples & Solutions</center></h1>
		
		<!-- Navigation -->
		
		<p><center>
			<a href="/"><button class = "button button1"><b>Home</b></button></a>
			<a href="/unit-01"><button class="button button1"><b>Unit 1</b></button></a>
			<a href="/unit-02"><button class="button button1"><b>Unit 2</b></button></a>
			<a href="/unit-03"><button class="button button1"><b>Unit 3</b></button></a>
		</center></p>
		
		<hr>
		
		<p><center>
			<a href="/office-hours"><button class="button button1"><b>Office Hours</b></button></a>
			<a href="/contact-me"><button class="button button1"><b>Contact Me</b></button></a>
		</center></p>
		
		</td>
		</tr>
		</table>
	</body>
	
	<p></p>
	
	<slot/>
</main>