# Custom-Minecraft-Recipe
This repository will help you in creating custom recipe for crafting in Minecraft: Bedrock Edition.
# What is Minecraft Recipe?
The recipe book can be displayed in inventory, crafting table, furnace, blast furnace and smoker. The player must enter the GUI and press the knowledge book icon; the recipe book then opens to the left. Recipes are stored in several different tabs: Crafting Table and Inventory.
# Required
**• Text-Editor**
# Clone
```

git clone https://github.com/Bubble4834/custom-minecraft-recipe
```
[install **git** to your computer to use this command in **CMD** (Command Prompt)]
# Steps
1. Go to ``%userprofile%\AppData\Local\Packages\Microsoft.MinecraftUWP_8wekyb3d8bbwe\LocalState\games\com.mojang\development_behavior_packs`` and create a folder, you can name whatever you want. Im gonna name ``recipe_test`` for this tutorial.
2. Again go to ``%userprofile%\AppData\Local\Packages\Microsoft.MinecraftUWP_8wekyb3d8bbwe\LocalState\games\com.mojang\development_behavior_packs/recipe_test`` and create a file name ``manifest.json``.
3. Once you've done that, open the ``manifest.json`` file and paste the code from ``recipe_test>manifest.json`` (found in this repository) to **your** ``manifest.json``.

```
{
    "format_version": 2,
    "header": {
        "description": "Example vanilla behavior pack",
        "name": "Vanilla Behavior Pack",
        "uuid": "ee649bcf-256c-4013-9068-6a802b89d756",
        "version": [ 0, 0, 1 ],
        "min_engine_version": [ 1, 16, 220 ]
    },
    "modules": [
        {
            "description": "Example vanilla behavior pack",
            "type": "data",
            "uuid": "fa6e90c8-c925-460f-8155-c8a60b753caa",
            "version": [0, 0, 1]
        }
    ],
    "dependencies": [
        {
            "uuid": "66c6e9a8-3093-462a-9c36-dbb052165822",
            "version": [0, 0, 1]
        }
    ]
}
```
4. To add recipes, you must create a folder names ``recipes``, within the main folder, within that folder, the game uses ``.json`` to create recipes. After that paste this code to your ``.json``.

```


5. There are many Crafting Style. 
# Shaped crafting
in a crafting table, there are two types of crafting, shaped and shapeless, we will begin with shaped.

In a shaped recipe, you have a specified pattern and a key of items like so, code found in ``recipe_test>recipes>.json`` in files (this repository)

# Shapeless Crafting
there is another type of crafting which is shapeless, the shapeless crafting has no pattern, but instead has a list and number of items for the craft, code found in ``recipe_test>recipes (2)>.json`` in files (this repository)
