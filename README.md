# MenuApp01
A simple HTML static menu board application for digital screens. Great for use with charlieuniform (coming soon, currently in Beta.)

It shows menu item images ontop of a background image with menu items and prices. It is a first pass and is relatively repsonsive.

This is a very rudimentary sample of a web application that can be shown on a digital screen. Great for use with [Charlie Uniform](https://charlieuniform.com).

## CharlieUniform
ChalieUniform is an application (Coming soon. Currently in Beta) tha lets you manage html content on unattended digital screens. Virtually any HTML content will work on any combination of hardware and browser. 

It is just a browser in full screen mode with your content. You can change that content from anywhere using charlieunifrom without touching the screen itself.

For info about CharlieUniform contact charlieuniformco+info@gmail.com.

## CharlieUniform
[Charlie Uniform](https://charlieuniform.com) is an app for your PC, tablet or cellphone that lets you manage HTML content on unattended digital screens. Virtually any HTML content will work on any combination of hardware and browser. 

It is just a browser in full screen mode with your content. You can change that content from anywhere using Charlie Uniform without touching the screen itself.

For info about CharlieUniform contact charlieuniformco+info@gmail.com.

## Usage
If you create several copies of the app, each with different images and swap them periodically with [Charlie Uniform](https://charlieuniform.com) your digital screen becomes effective for targeting your audience thruout the day. Maybe a breakfast menu early, a lunch menu around noon and a dinner menu in the evening. Upload them independantly to [Charlie Uniform](https://charlieuniform.com) with different names to have each available to show in any of your digital screens at different times during the day.

## To Change for your Menu
Download the zipfile from github. Extract into you filesystem. The top level directory of the app should be MenuApp01-master, we will change this later. The top level directory or folder name will be the name of the content app in [Charlie Uniform](https://charlieuniform.com). 

You can change the menu by editing the menu items and prices in the index.html file.
```
<li>Farm Burger Deluxe $3.29</li>
```

The images are background for divs iin the html structure. You can change them by creating a new image. Adding it to the img folder and modifying tapp.css inthe lines like:
```
#img1 {
	...
	background-image: url(../img/<your image file name>);
	background-position: center;
	background-size: contain; 
	background-repeat: no-repeat;
}
```
Images with transparent backgrounds work better.

Now name the top level folder something to help you know which menu you are using. Say you want to display on one of your digital screens in the morning your breakfast menu. So upload an image of the breakfast dishes and change the menu text as above. Now rename the top level directory from "MenuApp01-master" to "BreafastMenu". At this point you can drag and drop the new BreafastMenu directory to [Charlie Uniform](https://charlieuniform.com) app. It is now a content application for any of your screens managed by [Charlie Uniform](https://charlieuniform.com). In the morning set the BreafastMenu content app to any of the screens that you want to display it on.

