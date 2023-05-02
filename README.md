Download Link: https://assignmentchef.com/product/solved-cmis141-final-project-v2
<br>
This assignment demonstrates your understanding of the concepts from the CMIS 141 class.

Before attempting this project, be sure you have completed all of the reading assignments, hands-on labs, discussions, and assignments to date.

Design a Java application that will read a file containing data related to the US. Crime statistics from 1994-2013. The description of the file is at the end of this file.  The application should provide statistical results on the data including:

<ol>

 <li>Population growth in percentages from each consecutive year (e.g. 1994-1995 calculation is ((262803276 – 260327021)/260327021)*100 = 0.9512%, 1995-1996 would be ((265228572 – 262803276)/262803276)*100 = 0.9229%)</li>

 <li>Years where the maximum and minimum Murder rates occurred.</li>

 <li>Years where the maximum and minimum Robbery rates occurred.</li>

</ol>




The following are some design criteria and specific requirements that need to be addressed:

<ol>

 <li>Use command line arguments to send in the name of the US Crime Data file.</li>

 <li>You should also use Java classes to their full extent to include multiple methods and at least two classes</li>

 <li>You are not allowed to modify the Crime.csv Statistic data file included in this assignment.</li>

 <li>Use arrays and Java classes to store the data. (Hint: You can and should create a</li>

</ol>

USCrimeClass to store the fields. You can also have an Array of US Crime Objects.)

<ol>

 <li>You should create separate methods for each of the required functionality. (e.g. getMaxMurderYear() will return the Year where the Murder rate was highest. )</li>

 <li>A user-friendly and well-organized menu should be used for users to select which data to return. A sample menu is shown in run example. You are free to enhance your design and you should add additional menu items and functionality.</li>

 <li>The menu system should be displayed at the command prompt, and continue to redisplay after results are returned or until Q is selected. If a user enters an invalid menu item, the system should redisplay the menu with a prompt asking them to enter a valid menu selection</li>

 <li>The application should keep track of the elapsed time (in seconds) between once the application starts and when the user quits the program. After the program is exited, the application should provide a prompt thanking the user for trying the US Crime Statistics program and providing the total time elapsed.</li>

 <li>Hint: When reading the Crimes file, read one line at a time (See ReadEmail.java) and then within the loop parse each line into the USCrimeClass fields and then store that USCrimeClass Object into an array. Note you can use String.split(“,”) to split the CSV line into a the fields for setting the USCrimeClass Object.</li>

</ol>

Here is sample run:

java TestUSCrime Crime.csv

********** Welcome to the US Crime Statistical Application ************************** Enter the number of the question you want answered.  Enter ‘Q’ to quit the program :

<ol>

 <li>What were the percentages in population growth for each consecutive year from 1994 – 2013?</li>

 <li>What year was the Murder rate the highest?</li>

 <li>What year was the Murder rate the lowest?</li>

 <li>What year was the Robbery rate the highest?</li>

 <li>What year was the Robbery rate the lowest?</li>

 <li>Quit the program</li>

</ol>




Enter your selection: 2




The Murder rate was highest in 1994

Enter the number of the question you want answered.  Enter ‘Q’ to quit the program :

<ol>

 <li>What were the percentages in population growth for each consecutive year from 1994 – 2013?</li>

 <li>What year was the Murder rate the highest?</li>

 <li>What year was the Murder rate the lowest?</li>

 <li>What year was the Robbery rate the highest?</li>

 <li>What year was the Robbery rate the lowest?</li>

 <li>Quit the program</li>

</ol>




Enter your selection: 5




The Robbery rate was lowest in 2013

Enter the number of the question you want answered.  Enter ‘Q’ to quit the program :

<ol>

 <li>What were the percentages in population growth for each consecutive year from 1994 – 2013?</li>

 <li>What year was the Murder rate the highest?</li>

 <li>What year was the Murder rate the lowest?</li>

 <li>What year was the Robbery rate the highest?</li>

 <li>What year was the Robbery rate the lowest?</li>

 <li>Quit the program</li>

</ol>




Enter your selection: Q




Thank you for trying the US Crimes Statistics Program.

Elapsed time in seconds was: 32

The google recommended Java style guide, provided as link in the week 2 content, should be used to format and document your code. Specifically, the following style guide attributes should be addressed:

<ul>

 <li>Header comments include filename, author, date and brief purpose of the program.</li>

 <li>In-line comments used to describe major functionality of the code.</li>

 <li>Meaningful variable names and prompts applied.</li>

 <li>Class names are written in UpperCamelCase.</li>

 <li>Variable names are written in lowerCamelCase.</li>

 <li>Constant names are in written in All Capitals.</li>

 <li>Braces use K&amp;R style<strong>. </strong></li>

</ul>

<strong> </strong>

<strong>Submission requirements </strong>

Deliverables include all Java files (.java) and a single word (or PDF) document. The Java files should be named appropriately for your applications. The word (or PDF) document should include screen captures showing the successful compiling and running of each of the test cases. Each screen capture should be properly labeled clearly indicated what the screen capture represents. The test cases table should be included in your word or PDF document and properly labeled as well.

Submit your files to the Final Project area no later than the due date listed in your LEO classroom. You should include your name and FP in your word (or PDF) file submitted (e.g. firstnamelastnameFP.docx or firstnamelastnameFP.pdf)

<strong> </strong>

<strong>Grading Rubric: </strong>

The following grading rubric will be used to determine your grade:

<table width="623">

 <tbody>

  <tr>

   <td width="208"><strong>Attribute </strong></td>

   <td width="208"><strong>Meets </strong></td>

   <td width="208"><strong>Does not meet </strong></td>

  </tr>

  <tr>

   <td width="208">Crimes Class</td>

   <td width="208">15 pointsPopulation growth in percentages is calculated from each consecutive yearYears where the maximum and minimum Murder rates occurred are calculated.Years where the maximum and minimum Robbery rates occurred are calculated.Command line arguments to send in the name of the US Crime Data file were used.Java classes to their full extent to include multiple methods and at least two classes were used.</td>

   <td width="208">0 pointsPopulation growth in percentages is not calculated from each consecutive yearYears where the maximum and minimum Murder rates occurred are not calculated.Years where the maximum and minimum Robbery rates occurred are not calculated.Command line arguments to send in the name of the US Crime Data file are not used.Java classes to their full extent to include multiple methods and at least two classes are not used.</td>

  </tr>

 </tbody>

</table>




<table width="623">

 <tbody>

  <tr>

   <td width="208"></td>

   <td width="208">Crime.csv Statistic data file was not modified.Use arrays and Java classes were used to store the data.Creates separate methods for each of the required functionality.A user-friendly and wellorganized menu was used.The menu system is displayed at the command prompt.The menu system continues to redisplay after results are returned or until Q is selected.If a user enters an invalid menu item, the system redisplays the menu with a prompt asking them to enter a valid menu selection.The application keeps track of the elapsed time (in seconds) between the application start and when the user quits the program.After the program is exited, the application provides a prompt thanking the user for trying the US Crime Statistics program and providing the total time elapsed in seconds.</td>

   <td width="208">Crime.csv Statistic data file was modified.Use arrays and Java classes are not used to store the data.Does not create separate methods for each of the required functionality.A user-friendly and wellorganized menu was not used.The menu system is not displayed at the command prompt.The menu system does not continue to redisplay after results are returned or until Q is selected.If a user enters an invalid menu item, the system does not redisplay the menu with a prompt asking them to enter a valid menu selection.The application does not keep track of the elapsed time (in seconds) between the application start and when the user quits the program.After the program is exited, the application does not provides a prompt thanking the user for trying the US Crime Statistics program and providing the total time elapsed in seconds.</td>

  </tr>

  <tr>

   <td width="208">Test Cases</td>

   <td width="208">5 pointsA minimum of 3 test cases was used in the form of table with columns indicating the input values, expected output, actual output and if the test case passed or failed. The table</td>

   <td width="208">0 pointsNo test cases were provided.</td>

  </tr>

  <tr>

   <td width="208"></td>

   <td width="208">should contains 4 columns with appropriate labels and a row for each test case.Test cases were included in the supporting word or PDF documentation.</td>

   <td width="208"></td>

  </tr>

  <tr>

   <td width="208">Documentation and Style guide</td>

   <td width="208">5 pointsScreen captures were provided and labeled for compiling your code, and running each of your 3 test cases.Header comments include filename, author, date and brief purpose of the program.In-line comments used to describe major functionality of the code.Meaningful variable names and prompts applied.Class names are written in UpperCamelCase.Variable names are written in lowerCamelCase.Constant names are in written in All Capitals.Braces use K&amp;R style<strong>.</strong></td>

   <td width="208">0 pointsNo documentation includedJava style guide was not used to prepare the Java code.</td>

  </tr>

 </tbody>

</table>

<strong>US Crimes Data Description: </strong>

The attached Comma delimited file, named Crime.csv contains US Crime data from 1994 – 2013. The first line in the file contains the field names. (Note: Do not modify this file in anyway. You should use it as is for input for your application)

The US Crime data were obtained from this Web Site:

<a href="https://www.fbi.gov/about-us/cjis/ucr/crime-in-the-u.s/2013/crime-in-the-u.s.-2013/tables/1tabledatadecoverviewpdf/table_1_crime_in_the_united_states_by_volume_and_rate_per_100000_inhabitants_1994-2013.xls#overview">https://www.fbi.gov/about</a><a href="https://www.fbi.gov/about-us/cjis/ucr/crime-in-the-u.s/2013/crime-in-the-u.s.-2013/tables/1tabledatadecoverviewpdf/table_1_crime_in_the_united_states_by_volume_and_rate_per_100000_inhabitants_1994-2013.xls#overview">–</a><a href="https://www.fbi.gov/about-us/cjis/ucr/crime-in-the-u.s/2013/crime-in-the-u.s.-2013/tables/1tabledatadecoverviewpdf/table_1_crime_in_the_united_states_by_volume_and_rate_per_100000_inhabitants_1994-2013.xls#overview">us/cjis/ucr/crime</a><a href="https://www.fbi.gov/about-us/cjis/ucr/crime-in-the-u.s/2013/crime-in-the-u.s.-2013/tables/1tabledatadecoverviewpdf/table_1_crime_in_the_united_states_by_volume_and_rate_per_100000_inhabitants_1994-2013.xls#overview">–</a><a href="https://www.fbi.gov/about-us/cjis/ucr/crime-in-the-u.s/2013/crime-in-the-u.s.-2013/tables/1tabledatadecoverviewpdf/table_1_crime_in_the_united_states_by_volume_and_rate_per_100000_inhabitants_1994-2013.xls#overview">in</a><a href="https://www.fbi.gov/about-us/cjis/ucr/crime-in-the-u.s/2013/crime-in-the-u.s.-2013/tables/1tabledatadecoverviewpdf/table_1_crime_in_the_united_states_by_volume_and_rate_per_100000_inhabitants_1994-2013.xls#overview">–</a><a href="https://www.fbi.gov/about-us/cjis/ucr/crime-in-the-u.s/2013/crime-in-the-u.s.-2013/tables/1tabledatadecoverviewpdf/table_1_crime_in_the_united_states_by_volume_and_rate_per_100000_inhabitants_1994-2013.xls#overview">the</a><a href="https://www.fbi.gov/about-us/cjis/ucr/crime-in-the-u.s/2013/crime-in-the-u.s.-2013/tables/1tabledatadecoverviewpdf/table_1_crime_in_the_united_states_by_volume_and_rate_per_100000_inhabitants_1994-2013.xls#overview">–</a><a href="https://www.fbi.gov/about-us/cjis/ucr/crime-in-the-u.s/2013/crime-in-the-u.s.-2013/tables/1tabledatadecoverviewpdf/table_1_crime_in_the_united_states_by_volume_and_rate_per_100000_inhabitants_1994-2013.xls#overview">u.s/2013/crime</a><a href="https://www.fbi.gov/about-us/cjis/ucr/crime-in-the-u.s/2013/crime-in-the-u.s.-2013/tables/1tabledatadecoverviewpdf/table_1_crime_in_the_united_states_by_volume_and_rate_per_100000_inhabitants_1994-2013.xls#overview">–</a><a href="https://www.fbi.gov/about-us/cjis/ucr/crime-in-the-u.s/2013/crime-in-the-u.s.-2013/tables/1tabledatadecoverviewpdf/table_1_crime_in_the_united_states_by_volume_and_rate_per_100000_inhabitants_1994-2013.xls#overview">in</a><a href="https://www.fbi.gov/about-us/cjis/ucr/crime-in-the-u.s/2013/crime-in-the-u.s.-2013/tables/1tabledatadecoverviewpdf/table_1_crime_in_the_united_states_by_volume_and_rate_per_100000_inhabitants_1994-2013.xls#overview">–</a><a href="https://www.fbi.gov/about-us/cjis/ucr/crime-in-the-u.s/2013/crime-in-the-u.s.-2013/tables/1tabledatadecoverviewpdf/table_1_crime_in_the_united_states_by_volume_and_rate_per_100000_inhabitants_1994-2013.xls#overview">the</a><a href="https://www.fbi.gov/about-us/cjis/ucr/crime-in-the-u.s/2013/crime-in-the-u.s.-2013/tables/1tabledatadecoverviewpdf/table_1_crime_in_the_united_states_by_volume_and_rate_per_100000_inhabitants_1994-2013.xls#overview">–</a><a href="https://www.fbi.gov/about-us/cjis/ucr/crime-in-the-u.s/2013/crime-in-the-u.s.-2013/tables/1tabledatadecoverviewpdf/table_1_crime_in_the_united_states_by_volume_and_rate_per_100000_inhabitants_1994-2013.xls#overview">u.s.</a><a href="https://www.fbi.gov/about-us/cjis/ucr/crime-in-the-u.s/2013/crime-in-the-u.s.-2013/tables/1tabledatadecoverviewpdf/table_1_crime_in_the_united_states_by_volume_and_rate_per_100000_inhabitants_1994-2013.xls#overview">–</a>

<a href="https://www.fbi.gov/about-us/cjis/ucr/crime-in-the-u.s/2013/crime-in-the-u.s.-2013/tables/1tabledatadecoverviewpdf/table_1_crime_in_the_united_states_by_volume_and_rate_per_100000_inhabitants_1994-2013.xls#overview">2013/tables/1tabledatadecoverviewpdf/table_1_crime_in_the_united_states_by_volume_and_rate_pe </a><a href="https://www.fbi.gov/about-us/cjis/ucr/crime-in-the-u.s/2013/crime-in-the-u.s.-2013/tables/1tabledatadecoverviewpdf/table_1_crime_in_the_united_states_by_volume_and_rate_per_100000_inhabitants_1994-2013.xls#overview">r_100000_inhabitants_1994</a><a href="https://www.fbi.gov/about-us/cjis/ucr/crime-in-the-u.s/2013/crime-in-the-u.s.-2013/tables/1tabledatadecoverviewpdf/table_1_crime_in_the_united_states_by_volume_and_rate_per_100000_inhabitants_1994-2013.xls#overview">–</a><a href="https://www.fbi.gov/about-us/cjis/ucr/crime-in-the-u.s/2013/crime-in-the-u.s.-2013/tables/1tabledatadecoverviewpdf/table_1_crime_in_the_united_states_by_volume_and_rate_per_100000_inhabitants_1994-2013.xls#overview">2013.xls#overview</a>