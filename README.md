
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<link rel="stylesheet" type="text/css" href="styles.css">
<title>Simple Omelette Recipe Page</title>
</head>
<div class="page-layout">
<body>
	<img class="image" src="assets/images/image-omelette.jpeg" alt="This image displays an omelette.">
	<h1>Simple Omelette Recipe</h1>
	<div class="description">
		<p>An easy and quick dish, perfect for any meal. This classic omelette combines beaten eggs cooked to perfection, optionally filled with your choice of cheese, vegetables or meats.</p>
	</div>
	<div class="preparation-customize">
		<h2 class="preparation-time">Preparation Time</h2>
		<ul>
			<li><span>Total:</span> Approximately 10 minutes</li>
			<li><span>Preparation:</span> 5 minutes</li>
			<li><span>Cooking:</span> 5 minutes</li>
		</ul>
	</div>
	<div class="ingredients-customize">
		<h3 class="ingredients">Ingredients</h3>
		<ul>
			<li>2-3 large eggs</li>
			<li>Salt, to taste</li>
			<li>Pepper, to taste</li>
			<li>1 tablespoon of butter or oil</li>
			<li>Optional fillings: cheese, diced vegetables, cooked meats, herbs</li>
		</ul>
    </div>
    <hr class="dashed-line">
    	<h4 class="Instructions">Instructions</h4>
    		<div class="instructions-customize">
    	<ol>
    		<li><span>Beat the eggs:</span> In a bowl, beat the eggs with a pinch of salt and pepper until they are well mixed. You can add a tablespoon of water or milk for a fluffier texture.</li>
    		<li><span>Heat the pan:</span> Place a non-stick frying pan over medium heat and add butter or oil. </li>
    		<li><span>Heat the pan:</span> Place a non-stick frying pan over medium heat and add butter or oil. </li>
    		<li><span>Add fillings (optional):</span> When the eggs begin to set at the edges but are still slightly runny in the middle, sprinkle your chosen fillings over one half of the omelette.</li>
    		<li><span>Fold and serve:</span> As the omelette continues to cook, carefully lift one edge and fold it over the fillings. Let it cook for another minute, then slide it onto a plate.</li>
    		<li><span>Enjoy:</span> Serve hot, with additional salt and pepper if needed. </li>
    	</ol>
    </div>
    <hr class="dashed-line">
    	<h5>Nutrition</h5>
    	<p class="Nutrition-description">The table below shows nutritional values per serving without the additional fillings.</p>
    	<div class="nutrition">
    	<table>
    		<tr>
    		<td>
    			Calories
    		</td>	
    		<td class="nutrition-bold">
    			277kcal
    		</td>	
    		</tr>
    		<tr>
    		<td>
    			Carbs
    		</td>	
    		<td class="nutrition-bold">
    			0g
    		</td>		
    		</tr>
    		<tr>
    		<td>
    			Protein
    		</td>	
    		<td class="nutrition-bold">
    			20g
    		</td>	
    		</tr>
    		<tr>
    			<td>
    				Fat
    			</td>
    			<td class="nutrition-bold">
    				22g
    			</td>		
    		</tr>
    	</table>
    	 </div>
    	</div>
           </body>
              </div>
           </html>


h1{
	margin: 25px;
	font-family: 'Young Serif'; 
	font-weight: bold;
	font-size: 50px;
}
.description{
	font-size: 16px;
	font-family: 'Young Serif';
	margin: 25px;
}
.preparation-customize{
	margin: 25px;
	background-color: hsl(330, 100%, 98%);
	padding: 20px;
	line-height: 2;
}
h2{
	color: hsl(270, 100%, 25%);
}
.preparation-customize span{
	font-weight: bold;
}
h3{
	margin: 25px;
	font-weight: bold;
	color: hsl(14, 45%, 36%);
	font-size: 35px;
}
.ingredients-customize{
	line-height: 2;
	font-family: 'sans-serif;'
}
h4{
	margin: 25px;
	font-size: 35px;
	font-weight: bold;
	color: hsl(14, 45%, 36%);
}
.instructions-customize{
	line-height: 2;
}
.instructions-customize span{
	font-weight: bold;	
}
h5{
	margin: 25px;
	font-weight: bold;
	color: hsl(14, 45%, 36%);
	font-size: 35px;
}
.Nutrition-description{
	margin: 25px;
}
.nutrition table{
	width: 100%;
	margin: 25px;
}
.nutrition td{
	padding: 5px 10px;
}
.nutrition td:first-child
}
.nutrition .nutrition-bold{
	font-weight: bold;
}
