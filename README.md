# Introduction to Data

## Types of Data

Within the broader landscape of the digital humanities, datasets are often described based on the type of data they contain. In the digital storytelling unit, you worked with physical primary sources that had been digitized.

The Iowa Township data is largely a quantitative data set, built on numeric and calculated data. Later in the semester, we’ll be using text files of Scarlet &amp; Black student newspaper issues as a data source for textual analysis.

The authors of <em>Exploring Big Historical Data </em>give us additional terms to use in describing our data (from page 183): nominal data (also called categorical data), relational data, ordinal data, interval data, and ratio data.

Some of these would be considered raw data sources, while others (like relational data) can be thought of as a type of metadata—or data about data.

Using the terms presented in <em>Exploring Big Historical Data </em>and other frameworks, how would you describe the different fields (or columns) in the Iowa Township Project data? How does understanding the type of data inform or shape the research questions you might have?

<hr />

## Ways We Organize Data

Most of the data you’ll use for tutorials in this class will be downloaded as a file of already-structured data. The work that goes into gathering, describing, and organizing this data happened before the course so you would be able to focus on analyzing and visualizing these datasets.

The Iowa Township data brings together federal, state, and local census records, as well as agricultural census records to collect demographic information and property ownership information for historic Iowa townships. In this tutorial, we'll use an excerpt of the Township data related to censuses conducted in the 1870s.

As another example, historian Cameron Blevins uses spatial data to study the relationship between state formation, westward expansion, and the U.S. postal service. We’ll work with Blevins’s data in a future tutorial on spatial analysis, but compare the <a href="https://babel.hathitrust.org/cgi/pt?id=loc.ark:/13960/t3kw65n8k;view=1up;seq=7">original data source</a> and what you see in the table excerpted below.

&nbsp;
<table width="0">
<tbody>
<tr>
<td width="78"><strong>Name</strong></td>
<td width="65"><strong>County1</strong></td>
<td width="65"><strong>County2</strong></td>
<td width="65"><strong>County3</strong></td>
<td width="64"><strong>State</strong></td>
<td width="81"><strong>PM_Salary</strong></td>
<td width="70"><strong>Latitude</strong></td>
<td width="75"><strong>Longitude</strong></td>
</tr>
<tr>
<td width="78"><strong>Arizona</strong></td>
<td width="65">Yuma</td>
<td width="65"></td>
<td width="65"></td>
<td width="64">AZ</td>
<td width="81">360</td>
<td width="70">32.72532</td>
<td width="75">-114.624</td>
</tr>
<tr>
<td width="78"><strong>Ehrenburg</strong></td>
<td width="65">La Paz</td>
<td width="65"></td>
<td width="65"></td>
<td width="64">AZ</td>
<td width="81">140</td>
<td width="70">33.60419</td>
<td width="75">-114.525</td>
</tr>
<tr>
<td width="78"><strong>Florence</strong></td>
<td width="65">Pinal</td>
<td width="65"></td>
<td width="65"></td>
<td width="64">AZ</td>
<td width="81">12</td>
<td width="70">33.03145</td>
<td width="75">-111.387</td>
</tr>
<tr>
<td width="78"><strong>Fort Bowie</strong></td>
<td width="65">Cochise</td>
<td width="65"></td>
<td width="65"></td>
<td width="64">AZ</td>
<td width="81">12</td>
<td width="70">32.1498</td>
<td width="75">-109.453</td>
</tr>
<tr>
<td width="78"><strong>Grant</strong></td>
<td width="65">Pinal</td>
<td width="65">Pima</td>
<td width="65"></td>
<td width="64">AZ</td>
<td width="81">12</td>
<td width="70">31.40315</td>
<td width="75">-110.916</td>
</tr>
<tr>
<td width="78"><strong>Hardyville</strong></td>
<td width="65">Mohave</td>
<td width="65"></td>
<td width="65"></td>
<td width="64">AZ</td>
<td width="81">180</td>
<td width="70">35.045</td>
<td width="75">-114.622</td>
</tr>
</tbody>
</table>
&nbsp;

What steps were necessary to transform the data from the original source to the structured table format? How much time do you think it took for this data to be wrangled into the table structure?

&nbsp;
<blockquote>A note on terminology

The process of getting data into a structured from is often called data wrangling, mashing, or transformation. Preparing data for analysis and visualization can often be one of the most labor-intensive and time-consuming parts of a digital project.</blockquote>
&nbsp;

As another example, later in the semester we’ll be working with textual data from digitized S&amp;B issues. Browse the <a href="http://usiagrc.arcasearch.com/Research.aspx?p=a5675f16-3614-4a71-889f-6dc645e3de47">digitized versions of the S&amp;B publication</a>, and compare that to the text file excerpted below.

<blockquote>
<pre>The name of this association shall he the
SCARLET AND BLACK Assn iATioN in: Iowa
COLLEGE.

ART. II ’OBJICCT.

The object of this asSo-siation shall be to
publish a semi—weekly newspaper at (itin-
nell. Iowa, devoted to the interests of Iowa
College, its students. alumni and friends.

ART. lII.-—IVII£.\‘IBEI{SIIII’

Any one, by paying one dollar (ﬁt) the'
subscription price of the paper. may he-
comea member of the Assot‘iATtoN for that
year. and shall be. entitled to a vote in the
meetings of the. Asst’i:iATio.\' if present</pre>

### Reflection Question

What steps were necessary to transform the data from the original source to the text file? How much time do you think it took for this data to be wrangled into a text file?

<hr />

## Ways We Get Data

As the authors in <em>Exploring Big Historical Data </em>outline, historical data for digital history projects can come from a wide range of sources. Social Studies and Data Services Librarian <a href="https://www.grinnell.edu/users/bauderj">Julia Bauder</a> has created a <a href="https://libweb.grinnell.edu/sp/subjects/data">guide</a> to data sources available through the Grinnell Library. The Sociology Department’s Research Tools <a href="https://www.grinnell.edu/academics/areas/sociology/resources/research">webpage</a> compiled by David Cook-Martin also lists a number of data sources. Most of these data sources have already been organized and structured as data tables.

However, sometimes you may want to collect data that is not already available. For example, social media data or website data is not always readily available in a structured data form. For example, literary scholar Melanie Walsh <a href="https://melaniewalsh.org/2016/11/07/building-tweets-of-a-native-son-part2.html">used a Twitter web API</a> to search for social media content about James Baldwin and Black Lives Matter. HTML files from websites can be downloaded using the <a href="https://programminghistorian.org/en/lessons/automated-downloading-with-wget">Wget command line program</a>. Resources like <a href="https://www.hathitrust.org/data">Hathi Trust</a> and the <a href="https://www.gutenberg.org/">Project Gutenberg</a> offer full-text downloads of a variety of historical and literary texts. The Library of Congress’s Chronicling America Historic Newspaper Project uses <a href="https://chroniclingamerica.loc.gov/about/api/">a web API</a> to make data about its vast newspaper collection available to users.

&nbsp;
<blockquote>What is an API?

An web application programming interface (API) allows a user to interact with another computer program, rather than access online content via the public, human-readable interface. Web APIs are useful for making large underlying datasets available for download.</blockquote>

<hr />

## Ways We Store Data

Most of the data we will be using for tutorials and projects in this course exists as single CSV files. A Comma-separated values (CSV) file is a text file that uses commas to delineate fields of text. CSV files can be opened in spreadsheet programs like Microsoft Excel and text editors like Notepad. A text (TXT) file stores plain text data without any additional formatting or markup added by a word processing program like Microsoft Word.

Organizations like the <a href="https://www.loc.gov/preservation/digital/formats/index.shtml">Library of Congress</a> and <a href="https://www.archives.gov/preservation/products/definitions/filetypes.html">National Archives and Records Administration</a> produce documentation about best practices and preferred file types for long-term storage and preservation for digital materials. Libraries, archives, and museums most often use these guidelines to support long-term access to data and other types of digital materials.

However, even though data can be stored in a stable file format for long-term preservation, those file types may not be the best way to interact with the data for analysis and visualization. For example, storing a large complex data set in a single CSV sheet might not be the most efficient way to analyze or visualize particular aspects or features of our data.

<hr />

## Exploring the Iowa Township Data

Navigate to \\storage\projects\HIS\HIS-295-02\Iowa_Township_Data\1870s\1870_Census_Data in File Explorer and open the 1870 Federal Census Grinnell Township file in Microsoft Excel.

In the same folder, open the 1870 Grinnell City Census file in Microsoft Excel.

### Reflection Questions:
<ul>
 	<li>What fields are included in these two data sets? What types of data are recorded in the Excel files?</li>
 	<li>What questions do you have about the data--how it was gathered, organized, or structured?</li>
 	<li>What types of research questions could you explore or address using this data? What types of questions would not be a good fit for this data?</li>
</ul>

However, even though data can be stored in a stable file format for long-term preservation, those file types may not be the best way to interact with the data for analysis and visualization. For example, storing a large complex data set in a single CSV sheet might not be the most efficient way to analyze or visualize particular aspects or features of our data.

Another way we can think about the structure of data is organizing it as a series of entities, attributes, and relationships. Those three elements are the foundation of entity-relationship diagrams (ERD) and data schema that are used to design and build databases. <a href="http://www.cs.uregina.ca/Links/class-info/215/erd/">Click here</a> to learn more about entity-relationship models and database structures.

Analyzing and visualizing data that exists in multiple linked tables, or a database, can require greater computing resources and sometimes additional technical knowledge. But as we’ll see in the next part of the tutorial, common programs like Microsoft Excel can be powerful tools for analyzing and visualizing large, complex data sets.

<hr />

## Ways We Analyze Data

A useful way to think about data analysis is to differentiate or start to categorize the types of activities that can happen under the umbrella of data analysis. <strong><em>Measures</em></strong> can involve performing simple arithmetic functions like adding or counting. <em><strong>Calculations</strong> </em>involve transforming the data through a more complex mathematical operation or formula. A measure might count the total number of records or values in a category, while a calculation might determine an average or median for a particular combination of data features.

Fields like "Number of...." in the 1870 Grinnell City Census file are an example of measures.

The data in "Age..." fields is determined via calculations, based on a person's date of birth and the date the census information was recorded.

### Reflection Questions:

What are other useful measures you can imagine for the township data? What types of calculations might help you more fully understand the data?

We can also think about the different between <em><strong>quantitative</strong> </em>and <em><strong>qualitative</strong></em> data analysis. As the authors of <em>Exploring Big Historical Data </em>point out in Chapter 5, even quantitative measures and calculations still involve a series of choices about how you label, organize, and analyze data. All data, data analyses, and data visualizations reflect a series of choices and decisions about information.

<hr />

## Ways We Visualize Data

To start exploring different types of data visualization, we can also think about the purpose or goal for why we are visualizing the data. Historical scholars can use data analysis to explain or illustrate. As data literacy scholar Enrico Bertini points out in <a href="https://medium.com/@FILWD/from-data-visualization-to-interactive-data-analysis-e24ae3751bf3">a Medium blog post</a>, “Data journalism has provided over the years most of the best contributions to the art of explaining complex things through data.” These types of data visualizations are often supported by narrative text and other types of analysis, research, and argumentation. In this scenario, the data visualization supports arguments made in other forms or modes of communication. The data analysis and visualization is driven or shaped by conclusions or arguments the author already has.

In contrast, researchers are increasingly moving toward data visualization as a type of analysis. As Bertini puts it, “The main goal here is to extract information out of data with the purpose of answering questions and advancing understanding of some phenomenon of interest.” Maybe a researcher wants to analyze an unmanageably large body of materials, like entire newspaper runs from multiple publications. In another scenario, a researcher might want to bring together a range of data sets that require computation tools to connect, integrate, or synthesize disparate elements. For example, Cameron Blevins’s <a href="http://www.cameronblevins.org/research/">research on political structures of power in the western U.S.</a> involved building a database with information on more than 100,000 post offices—a data set so large that reading or analyzing it manually would have been of little use for building a larger historical argument based on the data.

### Examples

However, as the authors in <em>Exploring Big Historical Data </em>point out, visualizations can just as easily confuse or misrepresent users in their attempt to use digital tools to analyze data and build historical arguments. An entire subfield of data science is devoted to promoting data reasoning and data literacy skills—learn more by exploring the <a href="https://callingbullshit.org/case_studies.html">Calling Bullshit curriculum</a> developed by Carl Bergstrom and Jevin West at the University of Washington. The examples provided below are adapted from case studies in the Calling Bullshit curriculum.

<p align="center"><a href="https://github.com/kwaldenphd/introduction-to-data/blob/master/screenshots/Pic4.png?raw=true"><img class="aligncenter" src="https://github.com/kwaldenphd/introduction-to-data/blob/master/screenshots/Pic4.png?raw=true" alt="" width="494" height="343" /></a></p>

As an example, what data is being represented in this line graph? What are the calculations or measures represented in by the X and Y axes? What is your initial understanding of the data based on how it is represented in the graph? What concerns or questions do you have about the data and/or this visualization?

<p align="center"><a href="https://github.com/kwaldenphd/introduction-to-data/blob/master/screenshots/Pic3.png?raw=true"><img class="aligncenter" src="https://github.com/kwaldenphd/introduction-to-data/blob/master/screenshots/Pic3.png?raw=true" alt="" width="462" height="578" /></a></p>

As another example, what data is being represented in this line graph? What are the calculations or measures represented in by the X and Y axes? What is your initial understanding of the data based on how it is represented in the graph? What concerns or questions do you have about the data and/or this visualization?

<p align="center"><a href="https://github.com/kwaldenphd/introduction-to-data/blob/master/screenshots/Pic2.jpg?raw=true"><img class="aligncenter" src="https://github.com/kwaldenphd/introduction-to-data/blob/master/screenshots/Pic2.jpg?raw=true" alt="" width="472" height="437" /></a></p>

What data is being represented in this <a href="http://www.businessinsider.com/the-top-10-most-read-books-in-the-world-infographic-2012-12">bar chart from <em>Business Insider</em></a>? What are the calculations or measures represented in by the X and Y axes? What is your initial understanding of the data based on how it is represented in the graph? What concerns or questions do you have about the data and/or this visualization?

<p align="center"><a href="https://github.com/kwaldenphd/introduction-to-data/blob/master/screenshots/Pic1.png?raw=true"><img class="aligncenter" src="https://github.com/kwaldenphd/introduction-to-data/blob/master/screenshots/Pic1.png?raw=true" alt="" width="499" height="315" /></a></p>

What data is being represented in this bar chart from <a href="http://time.com/3935281/what-are-my-health-risk-factors/"><em>Time </em>magazine</a>? What types of measures or calculations are represented in this visualization? What types of visualization or representation are happening in this image? What is your initial understanding of the data based on how it is represented in the visualization? What concerns or questions do you have about the data and/or this visualization?

Chapter 5 in <em>Exploring Big Historical Data </em>includes examples and explanations for a range of chart types. The Calling Bullshit website also walks through the common pitfalls or considerations for different chart types by looking at issues with <a href="https://callingbullshit.org/tools/tools_misleading_axes.html">axes</a> and <a href="https://callingbullshit.org/tools/tools_proportional_ink.html">proportional ink</a>.
