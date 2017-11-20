# SMC-CS81-Unit-9

<!DOCTYPE html>

<!-- 
Angelo Vila 
CS 81 Section 1796
Unit 9 Assignment
 -->

<html>

	<head>
		<meta charset = "utf-8">
		<title>Unit 9 Assignment</title>
	</head>
	
	<body>
		<p>
		<strong>We</strong> have just started <strong>this</strong> section for the users (<strong>beginner</strong> to intermediate)
		who want to work with <strong>various</strong> JavaScript problems and write scripts online to <strong>test</strong> their 
		JavaScript <strong>skill.</strong>
		</p>
		
		<script>
		
		var wordterms = document.getElementsByTagName("strong");
		
		for (var i = 0; i < wordterms.length; i++) {
        wordterms[i].addEventListener("mouseover", function () {
            this.style.color = "red";
        })
		}
		
		
		</script>
	</body>
	
</html>
