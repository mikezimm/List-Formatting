# Tree format

## Summary
This sample includes format to add a tree in 3 different stages "**alt**" as top, "**body**" as tree and "**wood**" as bottom. Format also allow to include icons in the tree. When clicked on icon the **Title** message appear as tooltip.

![Tree](./assets/ChristmasTree.gif)

## Full Christmas Tree 

![Christmas Tree](./assets/TreePresentes.PNG)

## View requirements
- The format expect the following fields:

Field |Type
--------|---------
Title | Single line of text 
Structure | Single line of text - The tree is composed by the following structure: "**alt**" - Header of Tree (**Triangle**), "**body**" - body of tree (**Trapezoid**) and "**wood**" - Base of Tree (**Smaller Trapezoid**)
color | Single line of text - (recommended colors for the tree **79a83f**, **7cad40**, **c19c00**. For the base of tree recommend color **7e5224**). PS: no need to include #
Gift |  Single line of text - icons of gifts (samples **GiftboxOpen**, **GiftCard**, **Giftbox**, **GiftBoxSolid** and **FavoriteStarFill** for top of tree, )
GiftSide | Single line of text - options "**Left**" or "**Right**"

### Edit View requirements

- Edit View where format will be included, access to "**Sort**" Area and select column "**Structure**" and check as **ascending order**, this option order tree correctly from top to bottom event when included new levels in the tree.


## Sample

Solution|Author(s)
--------|---------
[tree-format.json](./christmas-tree-format.json) | [André Lage](https://twitter.com/aaclage)

## Version history

Version|Date|Comments
-------|----|--------
1.0|December 09, 2021|Initial release


## Disclaimer
**THIS CODE IS PROVIDED *AS IS* WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING ANY IMPLIED WARRANTIES OF FITNESS FOR A PARTICULAR PURPOSE, MERCHANTABILITY, OR NON-INFRINGEMENT.**

<img src="https://pnptelemetry.azurewebsites.net/list-formatting/view-samples/tree-format" />