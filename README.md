# fmEZCharts
Author NorthEast DataBase Solutions - Brian Ouimette on 2018-Aug-05 

------------------------------------------------------------------------------------------
fmEZCharts is Powered by the ChartJS Library. For more information go to the javascript tab and click on the Labels to view the full license and javascript libraries.


------------------------------------------------------------------------------------------ 
Instructions

1. Use the plus button to create a new chart or explore through the pre-loaded charts
2. Start editing the options of the charts. On commit the chart will reload
3. Once your chart is looking the way you want, go to the instructions tab and export chart to html 4. Paste HTML from document that was produced into a text field in your preference table
5. In a webviewer - Substitute out the placeholder for Labels and the palceholder for Data with the labels and data arrays from your file. **NOTE** If using multiple datasets or if you chose not to add placeholders you will need to add your own place holders for each dataset, and a placeholder for the labels.

------------------------------------------------------------------------------------------ 
Special Considerations

1. Data formatting - Data must be formatted in a JSON Array as numbers - [12,24,36,48,60]
2. Chart Labels - Labels must be formatted in a JSON Array as string - ["Label1","Label2","Label3","Label4","Label5"]
3. The total count of labels and the total count of data should match - IE. If you have 5 labels you should have 5 points of data like shown above
4. When working with colors - If the field label has array in the label, you can either use a single hex value with no quotes - IE. #676767 or you can use the label

