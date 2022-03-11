<!DOCTYPE html>
<html>
<head>
	<title>Javascript</title>
</head>
<body>
	<script>
		//membuat array
		var buah = ["pisang", "mangga", "pepaya", "melon", "jambu"];

		document.write("<h3>Keranjang Buah:</h3>");
		document.write("<ol>");

		//menggunakan perulangan untuk mencetak isi array
		for(let i = 0; i < buah.length; i++){
			document.write(`<li>${ buah[i] }</li>`);
		}
		document.write("</ol>");
	</script>
</body>
</html>
