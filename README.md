# UFOs

## Overview of Project:

This website provides a way to filter UFO sightings data by multiple criteria, including date, city, state, country, and shape. To build this website, we utilized HTML, CSS, and JavaScript. The [Bootstrap](https://getbootstrap.com/) library was used in order to help style the page.

## Results:

In order to use the website, scroll to the bottom of the page in order to view the filters and UFO data results. By default you will see the following:

<img src="https://github.com/brown-rox20/UFOs/blob/main/static/images/step_1.png">

Click the desired input box you want to filter by and enter in whatever you'd like to search for. For example, you could type `OR` in the `State` input. Then as soon as you hit enter/return on your keyboard, or tab to the next input, you will see results returned on the right:

<img src="https://github.com/brown-rox20/UFOs/blob/main/static/images/step_2.png">

You can then enter another search criteria in another input box. For example, you could enter a date. Now, based upon the city _and_ date, you will get a more specific set of results returned. Notice that for the state of `OR` and a date of `1/1/2010`, now only one result is returned on the right:

<img src="https://github.com/brown-rox20/UFOs/blob/main/static/images/step_3.png">

## Summary:

One drawback of this design is that if you don't hit enter/return or tab away from the input after you submit your criteria, the results aren't automatically returned. This is a bit confusing especially since we removed the `Filter Table` button we had previously.

One recommendation to improve the above user experience is to have the search results returned immediately after you type in the input.

Another improvement that could be made is to allow for partial searches of the data. So instead of requiring an exact match, a user could enter in just some of the text and still get results back.
