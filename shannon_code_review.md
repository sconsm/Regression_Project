## Shannon Code Review

### Prepared by: Tim Dooley

**Suggestions:** 

*  Visualizations. They are very hard to read. Make sure your legends tell the user what you are trying to show. Your pie charts show relatively even splits across different types, but I'm not sure what they are. The labels are floats. Also, pie charts are almost always discouraged. Perhaps a histogram or some sort of dist plot would have worked better here. 

  * You also have at least one countplot that shows almost all with a count of one, with only some outliers. It is hard to read and I'm not sure what its trying to convey. 
  * Another countplot shows some distribution but the x axis labels are impossible to read. Always clearly label your axes. 
  * Another viz is blank. Remove for final product. 
  * Your corr heatmaps need reformating. One has text that is too small to read. Another is too small and so text runs into iteslef. 
  * Your pairplot has a lot of not very interesting pairs. Remove those pairs for a more effective viz. 

* General repo point: With jupyter notebooks, you should make sure that the output of your cells is still there when you push to repo. Otherwise, it is really hard to impossible for others to interpret your results. 

* Your residual plot does not look homoscedastic. In other words, a residual plot is meant to show whether your residuals are randomly distributed (homoscedastic). When there are apparent patterns in your residual plot there is a problem in your data. This might mean that you are overfitting for some feature, or you have significant outliers in your data, among other issues. 

* Some of your repo files seem unneccessary. Ex. `extra_code_test`, don't include working files in your final product. 

* Your `readme` looks nice! I'd consider putting some of your visualizations in there. Make a seperate directory file in your repo called something like `images` and then link to those viz in your `readme`. 

  * Maybe add your name and some description to your repo. This should be part of your portfolio and we want to make sure employers know who made it and what they're looking at! 

  

