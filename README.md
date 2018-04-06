# menu-selector
React app for restaurant menu dish/drinks selection with search


# Menu JSON structure
[
	{
		"menuCategory": "starters",
		"menuItems": [
			{
				"name": "Kadoo Buranee",
				"desc": "Mashed pumpkin in oil and mixed herbs and spices, topped with yoghurt, comes with Naan.",
				"dineInPrice": [
					{
						"label": "L",
						"price": 3.00
					},
					{
						"label": "S",
						"price": 2.00
					}
				],
				"takeawayPrice":  [
					{
						"label": "L",
						"price": 3.50
					},
					{
						"label": "S",
						"price": 2.50
					}
				]
			},
			{
				"name": "Aush Soup",
				"desc": "Homemade noodles with mixed vegetables",
				"dineInPrice": 2.00,
				"takeawayPrice": 2.50
			}
		]
	},
	{
		"menuCategory": "Mains",
		"menuItems": [
			{
				"name": "Lamb Shank",
				"desc": "THis is awesome",
				"dineInPrice": 8.00,
				"takeawayPrice": 8.50
			},
			{
				"name": "Aush Soup",
				"desc": "Homemade noodles with mixed vegetables",
				"dineInPrice": 7.00,
				"takeawayPrice": 7.50
			},
			{
				"name": "Kabuli Palow",
				"desc": "Tenderly cooked lamb shank seasoned with Basmati rice, topped with carrots, raisins, almond & pistachios and comes with side dish. (Chef's choice)",
				"dineInPrice": 7.00,
				"takeawayPrice": 7.50
			}
		]
	},
	{
		"menuCategory": "Drinks",
		"menuItems": [
			{
				"name": "Coca Cola",
				"desc": "Always the real thing",	
				"dineInPrice": 1.00,
				"takeawayPrice": 1.00
			},
			{
				"name": "Diet Coke",
				"desc": "Zero calories",
				"dineInPrice": 1.00,
				"takeawayPrice": 1.00
			},
			{
				"name": "Kabuli Palow",
				"desc": "Tenderly cooked lamb shank seasoned with Basmati rice, topped with carrots, raisins, almond & pistachios and comes with side dish. (Chef's choice)",
				"dineInPrice": 7.00,
				"takeawayPrice": 7.50
			}
		]
	}
]
