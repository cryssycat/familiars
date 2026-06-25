Familiar Adoption Center

Upload this folder as a new page/site section, for example:

/familiars/index.html
/familiars/style.css

The page expects your Worker/API endpoint to return a list of familiar objects.

Default endpoint inside index.html:

https://charahub.crysthigpen.workers.dev/familiars

If your endpoint is different, change:

const API_URL = "https://charahub.crysthigpen.workers.dev/familiars";

Expected Notion properties:

Name -> name
Image -> image
Adoption Status -> adoptionStatus
Species -> species
Type -> type
Rarity -> rarity
Age -> age
Size -> size
Temperament -> temperament
Magic -> magic
Ability -> ability
Favorite Treat -> favoriteTreat
Summary -> summary
Notes -> notes
Price -> price
Link -> link

Adoption Status should be a Notion Select property with:

Available
Adopted

The page has only two public tabs:

Available
Adopted
