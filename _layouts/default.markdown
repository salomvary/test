<!DOCTYPE html>
<html>
<head>
	<title>{{ page.title}}</title>
  <link rel="stylesheet" href="/css/style.css">
</head>

<body>
  <header>
  </header>
  <div role="main" class="box">
		{{ content }}
  </div>
	<aside class="box">
		<h3>Something aside.</h3>
		<br><br><br><br>
		<ul>
		{% for k in site %}	
			<li>
			{% for l in k %}
				{{l}}
			{% endfor %}
			</li>
		{% endfor %}
		</ul>
	</aside>
  <footer>
  </footer>
</body>
</html>
