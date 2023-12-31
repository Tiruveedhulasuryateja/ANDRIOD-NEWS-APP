**# APP**
API(Application Programming Interface) for fetching the news from a server. API will work as an interface between your application and server, it will bring news and you will display all those news in a RecyclerView in your application
#Project as a part of Android Basics Nanodegree at Udacity

**# Project Overview**

The goal is to create a News Feed app which gives a user regularly-updated news from the internet related to a part
API Key Note
You need to insert your API key. Go to a file named Constants.java and find the value of API_KEY. Replace "test" with "YOUR-API-KEY".
public static final String API_KEY = "YOUR-API-KEY";

**# Features**

Navigation Drawer
Fragments
ViewPager plus TabLayout
Loaders
Intent
Guardian API
JSON Parsing
Glide
CardView
RecyclerView
SharedPreferences

**### Screenshots**

![screenshot_main](https://user-images.githubusercontent.com/33213229/35278055-2862b4ae-008c-11e8-8bed-651025e5b6cc.png)
![screenshot_navi](https://user-images.githubusercontent.com/33213229/35278047-1f11fd2e-008c-11e8-97dc-3ee12654b703.png)
![screenshot_swipe](https://user-images.githubusercontent.com/33213229/35278128-61fac558-008c-11e8-9ebe-95b93f98b117.png)
![screenshot_settings](https://user-images.githubusercontent.com/33213229/35278153-73bc8b14-008c-11e8-993e-5eb0320b9485.png)
![screenshot_from_date](https://user-images.githubusercontent.com/33213229/35278158-78bdb732-008c-11e8-8928-876699833e2f.png)
![screenshot_color_theme](https://user-images.githubusercontent.com/33213229/35278164-7b4c7402-008c-11e8-80f9-8718d3535464.png)
![screenshot_sky_blue_medium](https://user-images.githubusercontent.com/33213229/35278184-880c68a0-008c-11e8-9ec3-c7d0e6dc074a.png)
![screenshot_green_large](https://user-images.githubusercontent.com/33213229/35278192-8b7efa5c-008c-11e8-87eb-f1f426f1df96.png)

# Image resources
Icon by Yannick Lung
Icon by Just Icon

# MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

# NewsFeed 

I would like to share with you my first app published on the Google Play Store.

[![google-play-badge](https://user-images.githubusercontent.com/33213229/55871467-a23b7000-5bc5-11e9-846e-93a2958f6253.png)](https://play.google.com/store/apps/details?id=com.soojeongshin.newsfeed.free)
[![ic_launcher](https://user-images.githubusercontent.com/33213229/55873557-eda44d00-5bca-11e9-8272-50b56d971696.png)](https://play.google.com/store/apps/details?id=com.soojeongshin.newsfeed.free)

I built the **Guardian NewsFeed** app from scratch. I made use of the design of my News app one of the Android Basics Nanodegree projects, which is on this GitHub, but the code is different from my News app. I added the podcast feature which allows you to stream the guardian podcasts for free.

The differences are as follows.
*	Use the Paging library to load news data gradually and gracefully, so that you do not need to adjust the Number of Items in the Settings
*	Search articles by keyword
*	Add Podcast section. You can listen to Guardian podcasts anywhere, anytime for free, add favorite episodes, download episodes for offline listening
*	Use Constraint layout which allows you to make complex layouts with a flat view hierarchy
*	Use Third-party libraries – Android Architecture Components, Android Data Binding, Retrofit, Gson, OkHttp, ExoPlayer, Glide, Glide Transformations, SimpleXmlConverter, Timber, Firebase Analytics, Crashlytics
*	Replace Toast message with SnackBar message
*	Minimum SDK is 16, Android 4.1 (JELLY_BEAN)
*	Add the launcher icon that I created
