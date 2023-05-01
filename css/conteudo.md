<!-- 
	<video>

	- src
	- controls
	- se não funcionar?
		- fallback content
	- source
		- src
		type

	- sobre serviços de terceiros
 -->

 ```html
<video controls
	width="200px"
	height="200px"
	autoplay
	preload="metadata"
	loop
	muted
	poster="./icon.png">
	<source src="" type="video/mp4">
	<p>Esse browser não suporta o vídeo, baixe-o aqui.</p>
</video>
 ```