# Data-Science - Open Food Fact

## What is Open Food Fact ? 

A food products database. There are informations on ingredients, nutritional information, labels. The data comes from crowdsourcing, a data made by everyone, for everyone.

## Dataset Description 

You can find the Open Food Fact dataset here : https://world.openfoodfacts.org/data. 
It provides nutrition facts for food products sold in each country and all nutrition information we need. 
This database contains more than 100 000 records. 
It has five main fields :

- Generalities : 
  Fields related to the general information such as the name of the product, the contributor who added the product, the barcode and the url of the product.
  
- Tags : 
  Some informations related to the brands or packaging of the products. 
  
- Ingredients :
  List of ingredients of the products.
  
- Misc.:
  Extra information such as image of the product, number of food additives or ingredients from palm oil, carbon footprint (indicated on some product).
  
- Nutrition Facts : 
  The amount of a nutrient (in g or kJ for energy) for 100 g or ml of product. We also have the nutrition score defined by UK Food Standards Administration (FSA). The french nutrition score is derived from the UK FSA score and adapted for the french market.
 
## Our Goal 

We want to define the brands that sold the healthiest products. So we will make a ranking based on the nutrition score.
