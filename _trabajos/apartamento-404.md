---
title: Apartamento 404
categories: Series
list: false
layout: ''
type: Web
client: Emprendimiento personal
description: "Esteban es un joven introvertido que acaba de conseguir su nuevo apartamento pierde el control cuando es despedido de su trabajo, su novia termina de dejarlo y un nuevo vecino lo acosa continuamente."
---

<!DOCTYPE html>
<html lang="es-ES" prefix="og: http://ogp.me/ns#">
{% include _head.html %}

<body class="single single-recent_works postid-275 logged-in">

	<div id="up"></div>

	{% include _nav.html %}

	<section class="work page-padding" id="work">
		<div class="container">
			<div class="titleBar">
				<h2>{{page.title}}</h2>
			</div>
			
			<article class="page" style="padding-top:8px;">
				<div class="featured-image img-frame">
					<img src="/img/work/apartamento-404.jpg" alt="Apartamento 404" class="scale-with-grid">
				</div>
				<div class="content single clearfix">
					<div class="one-third column">
						<p>INFORMACIÓN</p>
						<p>
							CATEGORÍA: <span style="font-weight: 400;">{{page.categories | join: " " | remove: "Reciente" | remove: "Festival"}}</span><br>
							TIPO: <span style="font-weight: 400;">{{page.type}}</span><br>
							CLIENTE: <span style="font-weight: 400;">{{page.client}}</span>
						</p>
					</div>
					<div class="two-thirds column">
						<p>DETALLES</p>
						<p>
							<span style="font-weight: 400;">{{page.description}}</span>
						</p>
					</div>
				</div>
			</article>
		</div>
	</section>
</body>
</html>