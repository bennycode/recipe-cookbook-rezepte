# Halloween

Recipes for Halloween (ingredients ordered 2026-10-29).

## [Götterspeise mit Obst](https://cookidoo.de/recipes/recipe/de-DE/r27191)

10 min active, 6 h total (pure chilling), 4 portions, easy.

- 500g Wasser
- 80g Zucker
- 1 Pck. Götterspeise (Waldmeister oder Zitrone) – Dr. Oetker 25g Pulver, NOT the 150g "Dessert" cup from the fridge aisle
- 100g helle Trauben, halbiert
- 4 TL Crème fraîche Alternative

Notes:

- Halloween version: use gummy spiders / vampires instead of grapes. Add them once
  the jelly starts to set, otherwise they sink to the bottom.
- Crème fraîche is only a decorative blob, a spoon of plain soy yoghurt works.
- Erythritol instead of sugar works here (the powder does the gelling, not the sugar):
  110g for the 80g of sugar, since it only sweetens ~70% as much. 110g over 4 glasses
  is a lot per portion, so 60g erythritol plus a pinch of stevia is easier on the
  stomach. In the cookies erythritol is a bad swap – it does not brown and turns the
  short dough sandy; use xylitol there, or just keep the 40g of sugar.
- To speed up the 6 hours: let the liquid cool to room temperature before pouring,
  then 20 min in the freezer instead of hours in the fridge. Longer than that gives
  ice crystals and watery jelly.
- Only one layer here, so nothing can bleed. Layered versions (two colours) need each
  layer fully set before the next one goes in, which is where the long times come from.

## [Spinnenkekse](https://cookidoo.de/recipes/recipe/de-DE/r903750)

50 min active, 3 h total, 30 pieces, medium.

- 150g Butter, in Stücken
- 1 Ei
- 40g Zucker
- 10g Vanillezucker
- 240g Mehl
- 1 Prise Salz
- 100g Zartbitter-Kuvertüre, in 2-3cm Stücken
- 30 Schokoladen-Eier (Schoko-Bons oder Maltesers – 93g Maltesers ≈ 35 pieces)
- Zuckerschrift weiß, zum Verzieren

Notes:

- Not rolled out, not cut: divide into 30 balls, press a dent into each with the
  handle of a wooden spoon. 15-20 min at 180C, then cool completely.
- The legs are piped couverture, not Zuckerschrift: melt it, pour into a freezer bag,
  snip a corner, fill the dent, set the chocolate egg on top, draw the legs with the
  rest. Zuckerschrift is only for the eyes on the eggs.
- Dough rests 1 h in the fridge, wrapped. That hour is the bottleneck of the recipe.
- Knuspr only stocks "Dr. Oetker Zuckerschrift 4 Farben", and it was sold out on
  2026-10-29 (back 2026-10-30). Same for the Zuckeraugen.

## Also looked at

- [Spinnen-Augen-Dessert](https://cookidoo.de/recipes/recipe/de-DE/r912287) – Oreo base,
  vanilla pudding, red jelly, gummy eyes. 2 h, 10 portions. Knuspr has no red jelly
  powder (Waldmeister only); Tortenguss rot with water and sugar works but sets softer.
- [Crossie-Monster](https://cookidoo.de/recipes/recipe/de-DE/r791782) – 15 min active,
  75 min total, easy, 12 portions. White chocolate, cornflakes, almonds, beetroot juice,
  Zuckeraugen. Simplest of the lot.
- [Halloween Dessert im Glas (RUF)](https://www.ruf.eu/a/magazin/rezept/halloween-dessert-rezept/) –
  two-layer jelly, ~500ml per glass. Page gives no glass size and contradicts itself on
  portions. Cherry jelly is not available at Knuspr.

## Zubehör / non-food

Cookidoo DOES list this, as "Notwendiges Zubehör" in `div#useful-items-section` – but
only for logged-in users. Logged out, the page carries neither that section nor
`recipeInstructions`, and `tmx recipe show` prints neither. To read both:

```
python3 -c "import json;d=json.load(open('cookidoo_cookies.json'));print('; '.join(f\"{c['name']}={c['value']}\" for c in d))"
curl -sL -H "Cookie: $(cat cookie.txt)" https://cookidoo.de/recipes/recipe/de-DE/r903750
```

(cookie file lives in `~/.local/share/uv/tools/tmx-cli/lib/python3.11/site-packages/`)

- Spinnenkekse: Frischhaltefolie, Backblech, Backpapier, Gefrierbeutel
- Spinnen-Augen-Dessert: Auflaufform 30x20x6 cm – it is not a glass dessert at all
- Portionsgläser for the RUF version: Knuspr does not sell glasses

Check these before ordering, not while standing in the kitchen.
