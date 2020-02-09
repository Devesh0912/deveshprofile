## Welcome to GitHub Pages
<!DOCTYPE html>
<html>
<head>
	<title>Login page</title>
</head>
<body>
	<form action="" method="POST">
		{{ form }}
		{% csrf_token %}
		<input type="submit" value="submit">
	</form>
</body>
</html>
