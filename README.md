# UFOs - Visualizing UFO Sighting Data
---

## Overview of the Project

The purpose of the project is to explore a Unidentified Flying Object (UFO) data and visualize the data in a table format on a accessible website.

In order to present a working website we use the following tools for the development, design and interactiveness of the webpage;

* HTML - Set-up the framework of the website
* CSS - Develop the design layout of the website
* JavaScript - Develop the interactiveness of the website

The module challenge is keenly focused on the interactiveness of the website, by using JavaScript to code buttons and filters to the website layout for users/ UFO enthusiasts to filter sighting data by means on the following characteristics;

1. Date of sighting
2. Location of sighting (filtered on City/ State/ Country)
3. Shape of UFO sighting

The following report sections describe some key highlights on the outcome of the project.

## Results of the Project

### Developing the StoryBoard

When setting out on the development of the webpage, we designed a storyboard to better visualize the layout of what we intend to include and how it will visually look to have a better understanding of the interactivity.

In essence, the storyboard served as a blueprint for our website containing the UFO sighting data table. Once we finalized on the storyboard, it helped us better inform our decisions on the input required to our HTML, CSS and Javascript files in developing the final website product.

An overview of our storyboard layout is presented as follows (as recommended through course material)

![Story_Board_UFO_Data](/static/images/Story_Board_UFO_Data.png)

### Filtering Data - Sighting Date

The UFO sighting data is consisted in a table with hundreds of rows. With the filter functionality, a user can fiter out specific data from the table based on date choice entered in the following format of M/D/YYYY.

In the example image given, the UFO sighting data is filtered on the date of 1/7/2010 and provides us with a data output of 6 rows for UFO sightings on that particular date.

![UFO_Date_Filter](/static/images/UFO_Date_Filter.png)

### Filtering Data - Sighting Location

In addition to the date filter, UFO sightings can be filtered through the location of sighting using the City, State and Country filters. The effect of using the location filters on search results can be seen through the following image;

![UFO_Location_Filter](/static/images/UFO_Location_Filter.png)

### Filtering Data - UFO Shape

Furthermore, entering the shape of the UFO, will provide a filtered UFO sighting output based on the shape preference as depicted in the following image;

![UFO_Shape_Filter](/static/images/UFO_Shape_Filter.png)

### Filtering Data - Combined Filters

Finally, we can use our filter options in combination to select data from the table based on date,  location and shape of UFO as seen below;

![UFO_Combined_Filter](/static/images/UFO_Combined_Filter.png)

## Summary

As depicted through the results of the development of the website, a user can access multiple rows of UFO sighting data through their prefferred filters to obtain a summary of what their looking for. In addition to the level of interactiveness that has been coded to the site using our filters, we can explore additional areas of improvement which can contribute to the overall user friendliness of the website;

### Drawback of existing design

#### Limitations on filtering data

The key drawback seen in the UFO sighting data is the user cannot assume all the possible data points which can be used in the filter to filter appropriate search results.

In use of the website, the user will have to first scroll down the website to determine what data points he can filter by. For example, if the user requires to filter data by UFO shape, he first needs to scroll down to determine what shape options are available in the dataset. Then enter the preferred shape to obtain results.

The above scenario limits the interactiveness of the website and can prove to be challenging when we add more UFO sighting data into our sighting table.

### Recommendations on improving the design

#### Adding dropdown options to filter data

To address the key drawback, we can implement a dropdown list of existing filter options. This enables the user to have a snapshot view of what all the existing filter options are for them to better choose their preferred filter.

The drop down list can be attached to the existing filter, but when a user clicks on a filter to input the data, instead of typing it will be easier for the user to just select one of the options available on the dropdown list. This will greatly enhance the user experience of the website.

#### Expanding data on UFO sighting

The current state of the website, only displays data pertaining to the following;

* Date of sighting
* Location of sighting
* Shape of UFO sighted
* Duration of sighting
* Comments on sighting

But, this data can be expanded by drawing on other sources to enable facilitation of broader and better information. Such examples can be considered;

* Links to news articles on the sighting data
* Information people or number of people reported sighting
* Estimates on reliability of the sighting data

Adding additional columns will expand the data columns of our data, but we can consider adding additional filters for users to select which columns of data they like to view.

Another point of interactivity is to enable users to be able to download the dataset in a csv file either as a whole or through thier filtered preference.