# Kenyan Hotel Menu Catalogue

This catalogue is a starting point for a convincing Kenyan hotel/restaurant demo. It intentionally covers familiar dishes across different regions and business types. **Not every hotel serves every item.** The actual menu should always be confirmed with the business owner.

## 1. Breakfast

- Kenyan tea (chai)
- African coffee
- Porridge (uji)
- Mandazi
- Chapati
- Bread toast with butter or jam
- Fried, boiled or scrambled eggs
- Spanish omelette
- Sausages
- Beef or chicken sausages
- Pancakes
- Sweet potatoes
- Arrow roots (nduma)
- Cassava
- Boiled green bananas
- Fresh fruit plate
- Breakfast combo (eggs, toast, sausage and tea/coffee)

## 2. Kenyan meals and traditional plates

- Ugali, sukuma wiki and beef stew
- Ugali, sukuma wiki and fried fish
- Ugali and omena (where commonly served)
- Mukimo with beef stew
- Githeri
- Githeri with avocado
- Matoke with beef or vegetables
- Irio
- Ndengu (green grams) with rice or chapati
- Beans stew with rice or chapati
- Njahi (black beans) with rice or chapati
- Traditional chicken stew
- Kienyeji chicken with ugali
- Goat meat stew
- Matumbo stew
- Beef wet fry with ugali
- Pilau
- Swahili biryani
- Coconut beans with rice
- Coconut fish curry

## 3. Main dishes and grills

- Grilled chicken
- Chicken wet fry
- Chicken stew
- Chicken curry
- Beef stew
- Beef wet fry
- Beef fry
- Beef steak
- Nyama choma (goat or beef)
- Grilled goat ribs
- Grilled tilapia
- Fried tilapia
- Fish curry
- Pork chops (only where served)
- Sausages and chips
- Mixed grill platter

## 4. Rice, chapati and other starches

- Steamed white rice
- Pilau rice
- Vegetable rice
- Coconut rice
- Chapati
- Ugali
- Mukimo
- Mashed potatoes
- French fries (chips)
- Wedges
- Roast potatoes
- Sweet potatoes
- Matoke

## 5. Vegetables and sides

- Sukuma wiki
- Cabbage
- Spinach
- Managu / African nightshade
- Terere / amaranth leaves
- Kunde / cowpea leaves
- Mixed vegetables
- Kachumbari
- Avocado
- Steamed seasonal vegetables
- Garden salad
- Coleslaw
- Fried plantain

## 6. Snacks and light bites

- Samosas (beef or vegetable)
- Bhajia
- Viazi karai
- Chips masala
- Smokies
- Sausages
- Boiled eggs
- Roasted maize (seasonal)
- Roasted groundnuts
- Chicken wings
- Chicken strips
- Beef burger
- Chicken burger
- Toasted sandwich
- Club sandwich
- Vegetable sandwich

## 7. Soups

- Beef soup
- Chicken soup
- Cream of mushroom soup
- Tomato soup
- Vegetable soup
- Pumpkin soup

## 8. Desserts

- Fruit salad
- Fresh seasonal fruit
- Ice cream
- Pancakes with syrup
- Cake slice
- Banana fritters
- Mandazi
- Pudding

## 9. Hot drinks

- Kenyan tea
- Masala tea
- Black tea
- White coffee
- Black coffee
- African coffee
- Drinking chocolate
- Hot chocolate
- Uji

## 10. Cold drinks and juices

- Bottled water (still / sparkling where available)
- Soda
- Fresh passion juice
- Fresh mango juice
- Fresh pineapple juice
- Fresh orange juice
- Fresh watermelon juice
- Tropical juice
- Lemonade
- Iced tea
- Milkshake
- Yoghurt / mala

## 11. Optional coastal and regional specials

These can help the demo show range, but should be included only where they fit the restaurant.

- Viazi vya karai
- Mahamri
- Mbaazi za nazi
- Wali wa nazi
- Swahili biryani
- Swahili pilau
- Coconut fish curry
- Octopus (pweza) curry
- Seafood platter
- Mishkaki

## 12. Example category structure for the demo

Recommended guest-facing order:

1. Popular
2. Breakfast
3. Kenyan favourites
4. Main dishes
5. Nyama choma & grills
6. Rice, chapati & ugali
7. Sides
8. Snacks
9. Desserts
10. Hot drinks
11. Cold drinks

## 13. Menu item data fields

Every item in the future menu database should support:

- `id`: stable unique identifier
- `name`: guest-facing item name
- `category_id`: category relationship
- `description`: concise description
- `price_kes`: price in KSh (owner-confirmed)
- `image_url`: optional optimized image
- `is_available`: whether the item can currently be ordered
- `dietary_tags`: e.g. vegetarian, vegan
- `allergen_notes`: owner-confirmed allergen information
- `is_featured`: whether it appears in Popular
- `sort_order`: display order

## 14. Content and accuracy rules

- Do not invent a restaurant's actual prices.
- Demo prices must be labelled as illustrative sample prices.
- Confirm ingredients, portion sizes and allergens with the restaurant.
- Do not label food halal, vegan, vegetarian or gluten-free without confirmation.
- Allow a restaurant to remove dishes that it does not serve.
- Use real, owner-approved food photographs for a paying customer's menu.
