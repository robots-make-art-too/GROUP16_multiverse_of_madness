<html lang="en">
	<head>
		<meta charset="UTF-8"><meta name="viewport" content="width=device-width, initial-scale=1.0">
	</head>
	<center>
		<body>
			<h2>JavaScript Button to AR page(Phase 2)</h2>
			<p id="demo">Building Interactive Systems</p>

			<!-- MARKER BASED: MULTI MARKER | PRESET hiro | kanji -->
			<button type="button" onclick="openTab('./ar-index.html')">Take me to marker-based AR</button>
			<script>
				function openTab(url) {
					const link = document.createElement('a');
					link.href = url;
					link.target = '_blank';
					document.body.appendChild(link);
					link.click();
					link.remove();
				}
			</script>
        </body>
	</center>
</html>





# Project Idea
### The universe in you room

- You can find planets, nebulas and constellations.
- After download and install on your Android device, you can rotate to see what's around you.
- You also can interact with the object. Let the meteorite explode, or connect the stars into a constellation.




# Demo Exhibit

Watch [Full Video](https://drive.google.com/file/d/1GZh5S8cb0CitseI6WiguvvhZbLj8uNk5/view?usp=sharing)


# Project Process

### Marker info:
- Our project includes 6 major 3D models depicting a constellation- Aquarius, Aries, Cancer, Libra, Sagittarius, Scorpio . 
- Each model has a specific printed marker assigned to it.

### Future Updates

- Add more objects such as constellations
- Add animation and interactive system
- Develop Materials
- Develop Shaders
