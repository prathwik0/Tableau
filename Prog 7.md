---
tags:
  - tableau
  - program
---
>[!question] Using the Sample-superstore data source, apply sorting on the field named discount by using the dimensions order date and Subcategory

Use the Sample - Superstore data source to apply dimension filters on the sub-category of products. We create a view for showing profit for each sub-category of products according to their shipping mode. For it, drag the dimension field “Sub-Category” to the Rows shelf and the measure field “profit” to the Columns shelf.

Next, drag the Sub-Category dimension to the Filters shelf to open the Filter dialog box. Click the None button at the bottom of the list to deselect all segments. Then, select the Exclude option in the lower right corner of the dialog box. Finally, select Labels and Storage and then click OK. The following screenshot shows the result with the above two categories excluded.

![[7_dimension.png]]