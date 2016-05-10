
# The Structure

/application
	/css
	/js
	/img

# Introduction to HTML

1.  HTML Element(tag) Syntax

	```
	<element>
		[content]
	</element>
	```

	- HTML
		
		```
		<!DOCTYPE html>
		<html>
			<head>
				<title></title>
			</head>
			<body>

			</body>
		</html>
		```

	- Headings 

		- `<h1></h1>`
		- `<h2></h2>`
		- `<h3></h3>`
		- `<h4></h4>`
		- `<h5></h5>`
		- `<h6></h6>`

	- Paragraph - `<p></p>`

2. Attributes

	- Global
		- `id`
		- `name`
		- `class`
	- Local
		- `href`
		- `src`

# Introduction to CSS

1. Embedded in HTML
	
	```
		<style type="text/css">
			p {
				color: red
			}
		</style>
	```

2. Link to external 

	```
		<link rel="stylesheet" type="text/css" href="css/styles.css">
	```

3. Define styling

	```
	/* 
		Styling based on ID,  
		Add hash-tag at the front
		of the element's ID
	*/
	#heading-one {
		color: black;
	}

	/* 
		Styling based on class name,  
		Add dot(.) at the front
		of the class name
	*/
	.heading {
		color: blue;
	}

	/* 
		Styling based on element's name,  
	*/
	p {
		color: green;
		font-size: 20px;
	}

	/*
		Grouping Styling
	*/
	h1, h2, h3, h4, h5, h6, .heading, #heading-one {
		font-size: 40px;

		/* 
			!important
			Force all target elements 
			to use this syling
		*/
		color: red !important;
	}
	```

# Introduction to JavaScript

1. Alerts
	
	```
		confirm('Are you sure?');

		alert('alamak!');

		prompt('Please enter your IC number');
	```