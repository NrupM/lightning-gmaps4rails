# <img src="https://www.seeklogo.net/wp-content/uploads/2016/07/Ruby-logo.png" height="20px"> Lightning talk on Ruby gem `gmaps4rails`

## What is it?

1. `gem geocoder`

  * Adds geocoding (by street or IP address), reverse geocoding (find street address based on given coordinates), and distance queries.
  * Used to create latitude and longitude data using street addresses.

2. `gem gmaps4rails`
  * Helps make developing maps for large data sets easier.
  * All map objects created with this gem have customizable models and builder methods.
  * Can be integrated with other JS libraries, such as jQuery, and works well with Rails controllers and views.

> Each model instance is a point on the map.
> Although you do use some javascript for the Google maps API its not nearly as much as without the gem - allowing you to start working with the map immediately and not having to take the time to implement basic functionality.

## Steps to get started

1. git clone repo
2. `$ bundle install `
3. `$ rails db:create`
4. `$ rails s`
5. open your browser and go to localhost:3000

## You should see.....
![](https://github.com/NrupM/lightning-gmaps4rails/blob/master/app/assets/images/Gmaps4rails.png)
Go ahead and click **add user**, fill out the form inputs (keep latitude and longitude field blank) and come back to localhost:3000 to see your new "user".

## What's so cool about that?

Google Maps for Rails   |  Code Snippets
:----------------------:|:-------------------------:
index.html.erb <script> |![](https://github.com/NrupM/lightning-gmaps4rails/blob/master/app/assets/images/users_indexview.png)
UsersController method  |![](https://github.com/NrupM/lightning-gmaps4rails/blob/master/app/assets/images/users_controller.png)

JS & jQuery's AJAX      |  Code Snippets
:----------------------:|:-------------------------:
app.js                  |![](https://github.com/NrupM/lightning-gmaps4rails/blob/master/app/assets/images/jqueryajax.png)


## Want a map for YOUR app?

 * I suggest going through this [tutorial](https://www.youtube.com/watch?v=R0l-7en3dUw&feature=youtu.be) before setting up the gem in your app. It takes less than 30 minutes(depending on familiarity with Rails) and gives you a good idea of how the gem works within an app. *Afterwards*, your implementation will be smooth sailing!
 * Be aware that the first setup takes at *least* 30 minutes.

### Helpful links below:

* [Google Maps for Rails github](https://github.com/apneadiving/Google-Maps-for-Rails)
* [Blog article discussing why you might wan to use gmaps4rails](https://anadea.info/blog/how-to-integrate-google-maps-into-ruby-on-rails-app)
* [Helpful tutorial](https://www.youtube.com/watch?v=R0l-7en3dUw&feature=youtu.be)
