# Getting started clincubating image processing workflows
Open your 3D+channel+time data set. Consider using your data as [virtual stacks](https://imagej.nih.gov/ij/docs/guide/146-8.html)
if it's huge. Afterwards, activate CLIncubator by clicking on its tool icon.

![Image](images/installation_ok.png)

## Building workflows - step by step
CLIncubator has a built-in suggestions of what to do next:. 
Just right click in any image that has been clincubated.

![Image](images/suggestion_make_isotropic.png) 
[Image data source: Irene Seijo Barandiaran, Grapin-Botton lab, MPI CBG]

Consider them but also explore the cateories of all available operations. 

![Image](images/menu_rigid_tranform.png)
[Image data source: Irene Seijo Barandiaran, Grapin-Botton lab, MPI CBG]

You also find all CLIncubator operations in Fijis search bar.

![Image](images/fiji_search.png)

## Interoperabilty with classical ImageJ and Fiji operations
As CLIncubator runs in classical ImageJ windows, you can use ImageJ operations on the shown images. 
However, they may be overwritten as soon as CLIncubator recomputes its results.
Thus, it is recommended to duplicate an image before applying classial functions to it. 
You can use ImageJs `Duplicate...` menu or the built in menu:

![Image](images/interoperability_imagej.png)


Back to [CLIncubator](https://clij.github.io/clincubator)
