# ツ Subject
<p align="justify">Interactive website creation with rating and district filters for restaurants in Ankara via Leaflet.</p>


# ツ Abstract

<p align="justify">The website involves the development of a web-based application for geospatial data management, focusing on using a web framework and integrating the geographic aspect through Leaflet. Primary goals include implementing functions such as data filtering, insertion and deletion. Leaflet, an open-source JavaScript library for displaying maps, is instrumental in incorporating the geographic features required for the project.</p>

# ツ Basic Functions

<p align="justify">Data Filtering: The application allows users to filter data based on specific attributes. For example, users can choose to view only cafes with a score of 4.5 and above. Similarly, when shopping on a website, it provides convenience for people to choose to shop from sellers with a score above 4. This improves user experience by providing relevant and targeted information. Additionally, the user can reach restaurants in the relevant district by filtering by district.</p>

<p align="justify">Adding Data: The interface provides a mechanism for adding new data. Thanks to the database we have created, the data on our site is updated instantly. In this way, the application stays up to date with the latest information and coordinate data.</p>

<p align="justify">Data Deletion: The app allows users to delete existing data through a user-friendly interface. This functionality is critical to maintaining data accuracy and validity over time. Again, this is a necessary process for up-to-dateness. We must remove a cafe that is no longer in place.</p>

# ツ Summary

<p align="justify">This project, developped a web-based application focusing on Geospatial Data Management. Using Leaflet, geospatial data is effectively managed through a user-friendly interface. The application organizes access to geospatial data on a role-based basis, providing users with filtering, adding and deleting capabilities. Future enhancements include more advanced filtering options, integration with additional mapping APIs and optimization for mobile devices. The project focuses on the goal of becoming a long-lasting application through regular updates and maintenance.</p>

Restaurant data created using "PostgreSQL" was used with the help of "JavaScript". As a result, "Live Server", a "VS Code" add-on, published the written website to us via "128.0.0.1", that is, "localhost". The restaurant added to this database in the desired format will appear on the website.

There are two filters available on the website for now. The first of these is "rating" and the second is "districts" filters.

The rating filter allows you to display the average restaurant score, which is a result of the evaluation of restaurants by real users, and the scores between 3 and 5 with the help of a slider.

The Districts filter is a filter that helps show restaurants in your area of residence. By selecting the district name from the filter tool, it filters out the restaurants on the map that do not interest you.

The control units located on the left contain buttons to zoom in and out of the map and show the current location.

![1](https://github.com/user-attachments/assets/0e2cd312-bfee-4c36-88f4-70c9c93365f5)

Here is the "District" filter.

![2](https://github.com/user-attachments/assets/e18d3142-7a00-45c6-8e61-688f501c8c21)

And restaurants in "Çankaya" filtered by "4.4" points.

![3](https://github.com/user-attachments/assets/54fcc714-8b80-414f-990b-f8f59c708302)

And we can gather info from pop-up as well.

![4](https://github.com/user-attachments/assets/22944d4f-70f7-4d30-b033-4e98a24e2ce2)


The process of renewing the project: I encountered such a react error. Then started the project again. In this project, created a database instead of pulling live data from google. I aimed to provide up-to-date data on our site by continuously updating the data in this SQL-based database. The process was successful and uploaded the current data from database to web page using java script. I did the necessary checks on web page and did not encounter any errors. I added the video of project below.

Video of project: https://youtu.be/GnIrxWrma5Q

