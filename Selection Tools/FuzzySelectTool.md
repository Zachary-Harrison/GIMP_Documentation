# Using the Fuzzy Select Tool

*Written by Zachary Harrison*

The ![FuzzySelectTool.png](../images/FuzzySelectTool.png) *Fuzzy Select Tool* is a powerful tool that allows you to select an area of your image based on its color. 

![FuzzySelectToolOverview](../images/FuzzySelectToolOverview.png)

### 1. Open your image in GIMP. 

1. Go to the `File` menu and select `Open` (Or press `Ctrl` + `O` for Windows and ⌘ `Cmd` + `O` for Mac). 
2. On the pop-up menu, navigate to your file by clicking on one of the folders on the left or by using the **Location** search bar.
    > $\color{lightgreen} \text{Tip:}$ If you want to add a folder to the bar on the left for easy access, first navigate to it using the **Location** search bar. Then click on the `+` in the bottom left, and the name of the folder you've selected will show up at the bottom.

### 2. Select the ![FuzzySelectTool.png](../images/FuzzySelectTool.png) *Fuzzy Select Tool*

![FindingFuzzySelectTool.png](../images/FindingFuzzySelectTool.png)

Click the icon outlined above if it is the ![FuzzySelectTool.png](../images/FuzzySelectTool.png) *Fuzzy Select Tool*. 
> $\color{lightblue} \text{Note:}$ If a different tool is shown in the above location, hover over the other tool and perform the keyboard actions corresponding to the *Fuzzy Select Tool* (`U`).

### 3. Use  the ![FuzzySelectTool.png](../images/FuzzySelectTool.png) *Fuzzy Select Tool*

Click on the area of your image that you want to select. The ![FuzzySelectTool.png](../images/FuzzySelectTool.png) *Fuzzy Select Tool* will select all pixels in your image that have a similar color to the one you clicked on. 

If the selection is not accurate enough, you can adjust the threshold and feathering of the selection. 
- The **Threshold** slider determines how similar the colors need to be to be selected. A lower value will select colors that are very similar to the one you clicked on, while a higher value will select a broader range of colors.
- The **Feathering** option determines how smooth the edges of the selection are. A higher value will create softer, more feathered edges (a gradual transition between two colors), while a lower value will create sharper edges.
> ${\color{lightblue}\text{Note: }}$ When a portion of an image is selected, that selected area becomes the active focus for any subsequent operations. This means that any changes you make will only apply to this selected area. If you want to manipulate a different part of the image or use other tools that aren't applicable to the selected area, you'll need to deselect the current selection. To do this, navigate to the `Select` menu on the topbar and choose `None` (or press `Shift` + `Ctrl` + `A` for Windows and `Shift` + ⌘ `Cmd` + `A` for Mac). 

Once you're happy with the selection, manipulate it using other tools (Move, Rotate, Add Border, etc...), or press `Delete` to replace it with the active background color (located directly below the toolbox).

## Common Uses

### Selecting and Changing a Specific Color

1. Follow the aforementioned steps to make your selection.
2. Choose the `Bucket Fill Tool` or the `Colorize` function to change the color.


### Adding a Border to an Irregular Object

1. Follow the aforementioned steps to make your selection.
2. Go to the `Select` topbar menu > `Border`, then choose the width of your border and border style. 
3. Fill the border using a Tool of your choice ([Colorize Tool](../Color%20Tools/ColorizeTool.md) or [Bucket Fill Tool](../Paint%20Tools/BucketFillTool.md) are recommended)!


### Making the Background of an Image Transparent

1. Right-click on the Layer (outlined above on the right) your image is in and click `Add Alpha Channel`.
2. Follow the aforementioned steps to make your selection.
3. Press `Delete` to make the selection transparent.

## Tips 

Here are some tips for using the ![FuzzySelectTool.png](../images/FuzzySelectTool.png) *Fuzzy Select Tool* effectively:

- **Zoom In**: Press `Ctrl` + `Scroll` with your mouse for Windows or ⌘ `Cmd` + `Scroll` on Mac to zoom in/out. This will help you select more accurately.
- **Add to Selection**: If you accidentally deselect part of your selection, hold down `Shift` before you click and drag an area, which will be added to the selection. 
- **Subtract from Selection**: If you want to remove a part of the selection, hold down `Ctrl` for Windows or ⌘ `Cmd` on Mac before you click and drag an area, which will be removed from the selection.
- **Invert Selection** If you want to select everything except your current selection, go to `Select` > `Invert`. Alternatively, press `Ctrl` + `I` for Windows or ⌘ `Cmd` + `I` for Mac.
    > ${\color{lightgreen}\text{Tip: }}$ You can also use this to select something you otherwise couldn't before. For instance, some patterns are nearly impossible to select using the *Fuzzy Select Tool*, but if the rest of the image can be selected with this tool, you can just invert your selection! You don't have to resort to using the *Free Select Tool*.

Remember, practice makes perfect. The more you use the ![FuzzySelectTool.png](../images/FuzzySelectTool.png) *Fuzzy Select Tool*, the more comfortable you'll become with its settings and capabilities.

## Troubleshooting

- **Tool Not Responding**: If the tool is not responding or behaving unexpectedly, try resetting it. You can do this by going to the `Edit` menu and selecting `Preferences`. In the dialog box that appears, click on `Tool Options` and then `Reset All Tool Options`.

- **Selection Disappears**: Some tools disappear when you try to use another tool. If this happens, press `Ctrl` + `Z` on Windows or ⌘`Cmd` + `Z` on Mac to undo your previous action(s). If you need to use another tool but keep your selection, go to the `Select` menu and choose `Save to Channel`. You can then reselect it later by going to the `Channels` panel and clicking on the saved selection.

If you're still having trouble, consider searching for your issue on the [GIMP forums](https://www.gimp-forum.net/) or the [GIMP subreddit](https://www.reddit.com/r/GIMP/).