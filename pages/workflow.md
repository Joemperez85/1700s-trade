
# **Visualization**
	
The information used for the visualization was gathered by using 
**Webscraper,io** and after a bit of clean up that allowed the generated 
data to work with other programs the workflow became more manageable. 

Below are the steps taken that will demonstrate how the information generated
by **Webscraper.io** was used in the site **Palladio** and the results the 
information visually generated. Farther down the steps for how **Tableau** 
will also be demonstrated. 

***

![image]({{ site.baseurl}}/assets/images/1. Prep for palladio File demo.png)

Palladio

1. The information generated using **Webscraper.io** proved data in 
	Excel format. This allowed the image to be understood in a more plan 
	manner and edited to better fit the needs of the project. 
2. After organizing the data and ensuring the information in the Excel 
	format is what will be needed for visualization, the locations of each 
	port and/or region had to be located. By using Longitude and Latitude 
	finder with the help of  Google Earth most of the coordinates were located 
	for the project with the information provided from **Webscraper.io**. 
	Note: this method was a one by one location finder method and does take time. 
3. Once the coordinates were inputted into Excel they were combined into one 
	column. For **Palladio** <span style="color:red">Coordinates are read in one 
	Excel column i.e. |17.973379,-76.758667|</span>. In the program Tableau the 
	coordinates must be separated into two different columns. 
4. The information is double checked and ready to be converted to a **CSV** 
	file. Note: The more organize your input the easier it is for **Palladio** 
	to read and translate the data. 

![image]({{ site.baseurl}}/assets/images/2. Prep for palladio file Demo.png)
![image]({{ site.baseurl}}/assets/images/3. Prep Palladio point ot point.png)

Palladio continued…

5. Once step 4 is complete and the data is organized in a **Palladio** easy to
	understand manner the Excel file is ready to be converted to a **CSV** file. It
	is best to simplify your data to its most raw form and title each column –Place 
	and Coordinate- This allows **Palladio** to read the data as intended. 
6. Go on the **Palladio** website and simply drop your **CSV** file on to the site.
	The orange arrows show where to drop off the file. 
7. **Palladio** will bring up the work screen and any possible issues you might 
	have with your data. The more simple and consistent your data the less issues you 
	will have with **Palladio**.
8. Once the Data is submitted and you click on Map (Top Left Corner) this screen 
	will pop up. You will click on the Top right box and load your data to visualize
	your input. This is an example of the point manger that **Palladio** offers. 
9. This is an example when you use the point to point layer and its final 
	results. 
	
***

**Tableau**

![image]({{ site.baseurl}}/assets/images/6a. Tableau working flow.png)

The program **Tableau** was much more user friendly and no change of text file
was required. The only issue encountered was that unlike **Palladio** you DO need 
to make sure you have your Latitudes and Longitudes in different columns. By naming 
them Latitude and Longitude it made the process much easier.**Tableau** recognized 
the intentions and easily transferred the data.   

![image]({{ site.baseurl}}/assets/images/6.Tableau end result .png)

By having uniformed and clear data **Tableau** made it very easy to display the 
text into images that were easy to understand. 

---
# Workflow

More than a simple 'workflow', this should essentially be a **tutorial** to your reader how to do exactly what you did (whether or not the results were great). Remember: I am not your audience... nor are only DH specialists. The internet is your audience.

[Here is a student example of a workflow](https://confederate-memorials-project.readthedocs.io/en/latest/processes/).

Think of this as something like when a scientific paper describes their process. The idea is *repeatability*. People need to know how they can get a copy of the data. If you chopped up the data, altered it, or joined it with other data sets they need to know that too.

Discuss (in detail) the processes of

* Getting the data
* Cleaning/altering the data
* Visualizing the data
* **ANY DEADENDS YOU WENT DOWN** (so that others can avoid them).
* Discussing and sharing results with group members

---

What you need to cover: Talk about every step in your process, talk about how and why you made the decisions that you did. Why did you pick the website that you did? Did you download every record, or just some? Did you download the data directly from the website, or did you use a tool like Webscraper.io? Did you use OpenRefine to change the raw data in some form, and if so, why did you change it the way you did? What program(s) or techniques did you decide on to visualize or analyze it? Why did you feel those programs (e.g. Tableau or Gephi) were better than other options, given your research interest? Did you have to do anything to the data inside Tableau?

To make elegant workflow charts, use [LucidChart](https://lucidchart.com)

Take plenty of screenshots to document your process...
    * **Mac** press 'command' + 'shift' + '4' and then drag a rectangle to take a screenshot of whatever you select... On
    * **Windows**, click the 'Start' button then type 'Snipping' and select Snipping Tool, then click 'New' and drag a rectangle to take a screenshot of whatever you select.

---

To put your webscraper recipe online...

*If you post a recipe, you should also post instructions on how to import it, don't assume the reader knows!*

1. Open your sitemap.
2. Click the middle menu that says "Sitemap <your sitemap name>".
3. Click "Export Sitemap" and copy the JSON data from the form.
4. To help readability, go to [JSON Formatter](https://jsonformatter.curiousconcept.com/).
5. Paste the raw JSON, click "Process", then copy the output.
6. Select and copy the output and put it into a block quote (using the triple backtick ```````).
7. To enable syntax coloring, write the word `json` immediately afterward.
8. To see an example, look at the raw code for the blockquote below.
	

```json
{  
   "_id":"fake_sitemap",
   "startUrl":[  
      "https://www.fake-url.com"
   ],
   "selectors":[  

   ]
}
```


---
