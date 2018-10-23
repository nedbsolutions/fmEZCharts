# fmEZCharts
Author NorthEast DataBase Solutions - Brian Ouimette on 2018-Oct-22 

***** NOTE ***** Charts will only work in FileMaker 16 and 17. If working on Windows please contact me with issues. Some versions of Windows/IE will not render the chart but there is a solution to the issue. 

------------------------------------------------------------------------------------------
fmEZCharts is Powered by the ChartJS Library. For more information go to the javascript tab and click on the Labels to view the full license and javascript libraries.


------------------------------------------------------------------------------------------ 
Instructions

1. Use the Records Menu to create a new chart or explore through the pre-loaded charts
2. Start editing the options of the charts. On commit the chart will reload, or use the refresh chart button to refresh. 
3. Once your chart is looking the way you want, go to Export and follow the instructions. 
4. Paste HTML from the clipboard to a text field in your preference table.
5. In a webviewer or using a calculation field - Paste the susbtitute calculation and map where the data and labels are coming from as well as where you stored the chart HTML. **NOTE** If you chose not to add placeholders you will need to remove the sample data and labels and add your own place holders for each dataset, and a placeholder for the labels.

------------------------------------------------------------------------------------------ 
Special Considerations

1. Data formatting - Data must be formatted in a JSON Array as numbers - [12,24,36,48,60]
2. Chart Labels - Labels must be formatted in a JSON Array as string - ["Label1","Label2","Label3","Label4","Label5"]
3. The total count of labels and the total count of data should match - IE. If you have 5 labels you should have 5 points of data like shown above.
4. When working with colors - If the field label has array in the label, you can either use a single hex value with no quotes - IE. #676767 or you can use an array. When working with these fields if there is already a value in the field it will add the newly selected color as well as any values in the field into an array. 

------------------------------------------------------------------------------------------ 
Video Demo

http://vimeo.com/283976343
