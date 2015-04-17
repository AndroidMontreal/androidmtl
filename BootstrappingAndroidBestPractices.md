# Introduction #

Like human language, programming languages are
  * part syntax,
  * part vocabulary, and
  * part culture/socio-linguistics.

Too often when learning a new language we focus on syntax and vocabulary, but not enough on culture/best practices. Sure, in our courses we might learn that the French like wine and baguettes, and wear berets, but on the ground its not really that simple (n'est pas). In this tutorial we "immerse" ourselves in the culture of a few projects to simultaneously learn syntax, vocab and best practices for getting things done in Android Development.

We have selected a few repositories, 2 which show best practices, and 2 pairs of [pidgins](http://fr.wikipedia.org/wiki/Pidgin) vs. best practices which show not fully formed Android development.

# Beginner-Friendly Best Practice Learning Grounds #

  * [MyTracks](http://code.google.com/p/mytracks/w/list)
    * Beginners: [Using the GPS](http://code.google.com/p/mytracks/source/browse/MyTracks/src/com/google/android/apps/mytracks/services/TrackRecordingService.java)
    * Beginners: [Localization](http://code.google.com/p/mytracks/source/browse/#hg%2FMyTracks%2Fres)
    * Beginners: Choosing the right tool in your toolbox for saving [persistent application](http://code.google.com/p/mytracks/source/browse/MyTracks/res/xml/preferences.xml) [data](http://code.google.com/p/mytracks/source/browse/MyTracks/src/com/google/android/apps/mytracks/content/MyTracksProvider.java)
    * Advanced: [Using library projects](http://code.google.com/p/mytracks/source/browse/MyTracksLib/src/com/google/android/apps/mytracks/content/)
    * Advanced: good project management ([instructions end to end](http://code.google.com/p/mytracks/wiki/DevelopmentProcess): how others can set up the code and contribute to the project)

  * [Replica Island](http://www.youtube.com/watch?v=7-62tRHLcHk)
    * Beginners: [flashing image click animations](http://code.google.com/p/replicaisland/source/browse/trunk/src/com/replica/replicaisland/MainMenuActivity.java)
    * Advanced: [Game](http://code.google.com/p/replicaisland/source/browse/trunk/src/com/replica/replicaisland/Game.java) engine
    * Advanced: letting users decide [which buttons/touches](http://code.google.com/p/replicaisland/source/browse/trunk/src/com/replica/replicaisland/Game.java) do [what action](http://code.google.com/p/replicaisland/source/browse/trunk/src/com/replica/replicaisland/KeyboardConfigDialogPreference.java) in your app


## Pidgins vs. Best Practices Pairs ##

  * Two page-curl repos
    * [Don't lock the orientation](http://code.google.com/p/android-page-curl/source/browse/trunk/src/com/mystictreegames/pagecurl/StandaloneExample.java) [unnecessarily](https://github.com/harism/android_page_curl/blob/master/src/fi/harism/curl/CurlActivity.java)
    * [Do provide booleans so other devs can change arbitrary decisions](https://github.com/harism/android_page_curl/blob/master/src/fi/harism/curl/CurlView.java)
> > (1 page book vs. 2 page book, margins vs no margins)

  * Three Blogger clients
    * Do try to [use the  ContentProvider](http://code.google.com/p/mytracks/source/browse/MyTracks/src/com/google/android/apps/mytracks/content/MyTracksProvider.java),  [even if its hard to figure out](http://code.google.com/p/androblogger/source/browse/trunk/AndroBlogger/src/com/sadko/androblogger/MainActivity.java) when you are first learning.


# Some of our favorite Open Source Repositories #

  * Google IO Sched 2011
    * Advanced: using [fragments](http://code.google.com/p/iosched/source/browse/android/src/com/google/android/apps/iosched/ui/SessionDetailFragment.java) for phones and tablets (warning: this creates many layers of abstraction so its hard to navigate as a beginner)
  * [Shelves is a personal books management application for Android](http://code.google.com/p/shelves/)

> Shelves lets you manage your collection of books from your phone. With Shelves, you can add books by scanning their barcodes, using Web searches or entering information manually. Shelves help you find books in your collection with various search capabilities including by scanning a book's barcode.
    * [GreenDroid](https://github.com/cyrilmottier/GreenDroid)
> GreenDroid is a development library for the Android platform. It makes UI developments easier and consistent through your applications.
    * [Android Snippets](http://www.androidsnippets.com/)
    * [Firefox codebase runs on Android ](https://wiki.mozilla.org/Mobile/Fennec/Android)