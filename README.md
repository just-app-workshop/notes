# JustApp Workshop - Σημειώσεις Εργαστηρίου και Υλικό Παρουσιάσεων

## Εβδομάδα 1η

### Εισαγωγή
* [Εισαγωγή](https://docs.google.com/presentation/d/1AAZmbbWhKPyoUTJNhaMEGWt1jhg749qOTRyYReL-oYw/edit?usp=sharing)

### Prepare your box for Ionic development
* [Linux / MacOS] (https://github.com/just-app-workshop/notes/blob/master/linux-macos.md)
* [Windows] (https://github.com/just-app-workshop/notes/blob/master/windows.md)

### Cordova / Phonegap and Ionic
* [JustApp - Cordova & Ionic - Εισαγωγή και παραδείγματα](https://docs.google.com/presentation/d/1AdYCEbb-PMWlEkLFrWk0vg-fmSOXycT6A7uBpg9122E/edit?usp=sharing)

### AngularJS / Ionic και AngularJS

#### [Angular Demo 1](https://github.com/just-app-workshop/angular-demo-1)
1. Create an HTML workspace [commit](https://github.com/just-app-workshop/angular-demo-1/commit/cd59cf45676cf3050da0b4dd32ca77eed66cd440)
2. Προσθήκη AngularJS `1.5.x` στην σελίδα `index.html` [commit](https://github.com/just-app-workshop/angular-demo-1/commit/1a5ea434b0bb6afb2e9d0a71a71126b67ad68129)
    * https://angularjs.org/
3. Δημιουργία Angular Application [commit](https://github.com/just-app-workshop/angular-demo-1/commit/12a942d2a519bd1cd1ca1897391c214eddffa8fe)
4. Προετοιμασία του `Controller` [commit](https://github.com/just-app-workshop/angular-demo-1/commit/f4adc39d11c2be73ae01dc5166755637210edcf0)
5. Πρετοιμασία του μοντέλου [commit](https://github.com/just-app-workshop/angular-demo-1/commit/83fff0b5319c0aa6a9ebc1490985160fe2771ebb)
6. Προετοιμασία της HTML σελίδας (View) [commit](https://github.com/just-app-workshop/angular-demo-1/commit/13a0397b400db6e1d675d9cde34bf866188be771)
7. Εμφάνιση δεδομένων στην σελίδα (View) [commit](https://github.com/just-app-workshop/angular-demo-1/commit/21f953d55139541587dbfeccab02c685f564761b)
8. Φάε ένα snack [commit](https://github.com/just-app-workshop/angular-demo-1/commit/d101cb047a27bbf4ac693376c5765f3f077df0de)
9. Επίδειξη Google Chrome Debugger
10. Κάνε μια βόλτα [commit](https://github.com/just-app-workshop/angular-demo-1/commit/c8f62f6d21a1655c09862e33e2b78be8ae9d2adb)
11. Πρόσεχε μην εξουθενωθείς [commit](https://github.com/just-app-workshop/angular-demo-1/commit/7525b9529c0859f13264fbef68e8a0a6cffb3fc8)

##### Online tutorial
* [Learn to build an application using Angular.js](http://campus.codeschool.com/courses/shaping-up-with-angular-js/intro)

#### [Ionic Demo 1](https://github.com/just-app-workshop/ionic-demo-1)
* Αρχικοποίηση `ionic start demo-1`
* Εκκίνηση `ionic serve`
* Chats
    * Σχέση/Σύνδεση View με Controller [`app.js` / Chats](https://github.com/just-app-workshop/ionic-demo-1/blob/master/www/js/app.js#L55)
    * View [`tab-chats.html`](https://github.com/just-app-workshop/ionic-demo-1/blob/master/www/templates/tab-chats.html)
    * Controller [`controllers.js`](https://github.com/just-app-workshop/ionic-demo-1/blob/master/www/js/controllers.js#L5)
    * Model
        * [`controller.js`](https://github.com/just-app-workshop/ionic-demo-1/blob/master/www/js/controllers.js#L14)
        * [`services.js`](https://github.com/just-app-workshop/ionic-demo-1/blob/master/www/js/services.js#L3)
* Επίδειξη: Παρακολούθηση με Debugger. Breakpoints σε
   * [`app.js`](https://github.com/just-app-workshop/ionic-demo-1/blob/master/www/js/app.js#L53)
   * [`services.js`](https://github.com/just-app-workshop/ionic-demo-1/blob/master/www/js/services.js#L7)
   * [`controller.js`](https://github.com/just-app-workshop/ionic-demo-1/blob/master/www/js/controllers.js#L14)
* Επίδειξη: Προσθήκη νέας επαφής

### Bower
* [Bower, A package manager for the web](http://bower.io/)
    * [Bower Demo 1](https://github.com/just-app-workshop/bower-demo-1)

## Εβδομάδα 2η

### Grunt
* [GRUNT, The JavaScript Task Runner](http://gruntjs.com/)
    * [Grunt Demo 1](https://github.com/just-app-workshop/grunt-demo-1) 

### SASS
* [Εισαγωγη και παραδείγματα](https://docs.google.com/presentation/d/1byfD9FaImigvrwrF4HETpmp89SNQPjmA-1epmYnpaUI/edit?usp=sharing)
    * HTML / CSS / SASS
    * Ionic

### Modular Αρχιτεκτονική με AngularJS. 
Καλές πρακτικές και τεχνικές στην δόμηση του κώδικα.
* [Supermodular Ionic](https://github.com/skounis/supermodular)
    * [`App` folder](https://github.com/skounis/supermodular/tree/master/app/)
    * [Home module](https://github.com/skounis/supermodular/tree/master/app/scripts/home)
        * [Αναφορά στο `app.js`](https://github.com/skounis/supermodular/blob/master/app/scripts/app.js#L14)

### Ionic Starter Kit - Supermodular 
Δημιουργία Ionic εφαρμογής με χρήση του Supermodular Starter Kit.

1. Fork του SuperModular
2. Δημιουργία και προσθήκη του `movies` module
3. [Scaffold your next Ionic application](https://docs.google.com/document/d/1uxCuULrZwO0YBaJdbcy4omMs3e4bGPXmYpeb7kRu55Y/edit?usp=sharing)


## Εβδομάδα 3η

### Ασκηση 1 - Λύση και Παραδείγματα
* [Ασκηση 1](https://github.com/just-app-workshop/assignment-1)
* [Forks](https://github.com/just-app-workshop/assignment-1/network/members)
* Βιβλιοθήκες
    * [Underscore](http://underscorejs.org/#) 
    * [Javascript Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array)
* Τελεστές
    * [Javascript reference](http://www.w3schools.com/jsref/jsref_operators.asp)
* Χρήσιμοι σύνδεσμοι
    * [Bitwise operators](http://www.cprogramming.com/tutorial/bitwise_operators.html)
    * [Βitwise calculator](http://www.miniwebtool.com/bitwise-calculator/)
    * [Decimat to Binary](http://www.binaryhexconverter.com/decimal-to-binary-converter)
        * `2 & 1` = `00000010 & 00000001` = `0`
        * `3 & 1` = `00000011 & 00000001` = `1`
        * https://github.com/achatzit/assignment-1/blob/master/app/scripts/controllers/play2.js
* By Reference
    * [Angular Copy](https://docs.angularjs.org/api/ng/function/angular.copy) 

### Emulation / Run on device
* Emulation / Simulation
    * iOS Simulator
    * [Genymotion](https://www.genymotion.com/)
        * [Virtual Box](https://www.virtualbox.org/)
* Run on Device
    * iOS
        * XCode
        * [TestFlight](https://developer.apple.com/testflight/)
    * Android
       * Google / Dropbox
          * [Restaurant App](https://goo.gl/cHPRzD) `AB64F538`
          * [Business Directory](https://goo.gl/VEoJc2) `E1F02EDD`
          * [Catalogue](https://goo.gl/w8rJkJ) `eca7b2b5`
          * [Music Band](https://goo.gl/DEGfxP) `0cfd4232`
       * [Android File Transfer](https://www.android.com/filetransfer/)
    * [Ionic View](http://view.ionic.io/)
        * [Screen 1](https://github.com/just-app-workshop/notes/blob/master/assets/ionic-view-1.png)
        * [Screen 2](https://github.com/just-app-workshop/notes/blob/master/assets/ionic-view-2.png)
        * [Screen 3](https://github.com/just-app-workshop/notes/blob/master/assets/ionic-view-3.png)

### News App Ionic
* Δημιουργία και Αρχικοποίηση Git Repo και σκελετού εφαρμογής
* Πηγές δεδομένων
    * Static JSONs
        * Articles JSON {TBD: URL} 
    * Wordpress site
        * http://demo.titaniumtemplates.com/wordpress/
        * [JSON API Plugin](https://wordpress.org/plugins/json-api/)
* Εργαλεία και αναφορές
    * [Postman](https://www.getpostman.com/)
    * [Ionicons](http://ionicons.com/)
    * AngularJS Filters
        * `limitTo` https://docs.angularjs.org/api/ng/filter/limitTo 
    * Ionic Components
       * Thumbnail left: http://ionicframework.com/docs/components/#item-thumbnails 
    * [Source code](https://github.com/skounis/eestec-articles-ionic)

## Εβδομάδα 4η

### Yeoman Generators. 
Εισαγωγη στις γεννήτριες κώδικα και παραδείγματα χρήσης τους.
* [yeoman.io](http://yeoman.io/)
* Παραδείγματα
    * [HTML5 Boilerplate generator](https://github.com/h5bp/generator-h5bp)
    * [AngularJS generator](https://github.com/yeoman/generator-angular)


### [Amazon S3](https://aws.amazon.com/s3/)
> Amazon Simple Storage Service (Amazon S3), provides developers and IT teams with secure, durable, highly-scalable cloud storage. Amazon S3 is easy to use object storage, with a simple web service interface to store and retrieve any amount of data from anywhere on the web. With Amazon S3, you pay only for the storage you actually use. There is no minimum fee and no setup cost.

* Πιστωτική Κάρτα 
    * [Number26](https://number26.eu/)  

#### Παραδείγματα
1. Δημιουργία Bucket
2. Δημιουργία access key 
3. Upload και ρύθμιση δικαιωμάτων 

#### Tools
* https://cyberduck.io
* http://s3browser.com/

### Version control
Τεχνικές ανάπτυξης κώδικα, παρακολούθησης και συνεργασίας. 
* [Git](https://git-scm.com/)
* [GitHub](https://github.com/)
* [Bitbucket](https://bitbucket.org/)
* Παράδειγμα

### News App Ionic - Μερος 2ο
* Πηγές δεδομένων
    * Wordpress site
        * http://demo.titaniumtemplates.com/wordpress/
        * [JSON API Plugin](https://wordpress.org/plugins/json-api/)
    * Demo URLs
       * http://demo.titaniumtemplates.com/wordpress/
       * http://demo.titaniumtemplates.com/wordpress/?json=1
       * http://demo.titaniumtemplates.com/wordpress/?p=38
       * http://demo.titaniumtemplates.com/wordpress/?p=38&json=1
* Δημιουργία ασύγχρονης μεθόδου
    * https://github.com/skounis/eestec-articles-ionic/blob/master/app/scripts/wordpress/wordpress.service.js#L53
    * https://github.com/skounis/eestec-articles-ionic/blob/master/app/scripts/wordpress/wordpress-articles.controller.js#L26
* Εργαλεία και αναφορές
    * [Postman](https://www.getpostman.com/)
    * [Source code](https://github.com/skounis/eestec-articles-ionic)
    * Promise, the `$q` service
        * https://docs.angularjs.org/api/ng/service/$q 

### Firebase App Ionic 
* Δημιουργία και Αρχικοποίηση Git Repo και σκελετού εφαρμογής
* Firebase Project
    * [JSON Data for Import](https://github.com/just-app-workshop/firebase-ionic/blob/master/misc/firebase/business-directory-export.json)
* Εργαλεία και αναφορές
    * [Firebase](https://www.firebase.com/)
        * [Interactive Tutorial](https://www.firebase.com/tutorial/#gettingstarted)
    * [Angular fire](https://www.firebase.com/docs/web/libraries/angular/)
    * [Source code](https://github.com/just-app-workshop/firebase-ionic)

### Real Ionic Applications
Πραγματικές Ionic εφαρμογες
* [Barebone Ionic](http://codecanyon.net/item/barebone-ionic-full-application/115651960
    * Download links {TBD}
* [Business Directory](http://codecanyon.net/item/business-directory-ionic-full-application-with-firebase-backend/14681052)
    * Download links {TBD} 

## Εβδομάδα 5η

### Ασκήσεις 2 και 3
* Παρουσίαση pull requests
    * Articles Ionic - https://github.com/just-app-workshop/articles-ionic/pulls
    * Firebase Ionic - https://github.com/just-app-workshop/firebase-ionic/pulls
* Παρουσίαση της πρότασης υλοποίησης

### Async
Λύσεις στα προβλήμματα που προκαλεί η ασύγχρονη φύση του call back.
* https://github.com/caolan/async

#### Παραδείγματα
* Playground Project: [Ionic Async](https://github.com/just-app-workshop/ionic-async) 

### Postmap - Παράδειγμα
* Appseed Restaurant (TBD)
    * Authentication 
    * Δοκιμαστικές κλήσης

### Συζήτηση
* Γνωριμία με τις ομάδες
* Προγραμματισμός 

## Ασκήσεις
### Άσκηση 1 - AngularJS / Javascript
Κάντε fork το παρακάτω repository και συμπληρώστε τα κενά στο αρχείο `app/scripts/controllers/play.js`. Υπάρχουν σχόλια με την ένδειξη `TODO`.

* https://github.com/just-app-workshop/assignment-1

Δουλέψτε στο δικό σας repository που θα προκύψει από την διαδικασία fork. Κάντε commit/push εκεί τις αλλαγές σας και όταν έχετε τελειώσει ετοιμάστε ένα [Pull Request](https://help.github.com/articles/using-pull-requests/)

#### Οδηγίες
Στο αρχείο `play.js` υπάρχουν 3 συναρτήσεις που 
1. Αφαιρούν τους μονούς αριθμούς από έναν πίνακα τιμών.
2. Αφαιρούνε τους ζυγούς αριρμούς από τον ίδιο πίνακα τιμών.
3. Ταξινομούν το περιεχόμενο του πίνακα .

Εχει προετοιμαστεί η δομή του κώδικα και ο σκελετός των μεθόδων, απουσιάζει όμως η υλοποίηση. Συμπληρώστε τα κενά σε αυτές τις μεθόδους και εξετάστε το αποτέλεσμα εκτελώντας την εφαρμογή `grunt serve` και εξετάζοντας το περιεχόμενο της σελίδας "Play".

Τα σημεία όπου πρέπει να συμπληρώσετε τον κώδικα έχουν σημειωθεί με την ένδειξη `TODO`

### Άσκηση 2 - Wordpress Call
Κάντε fork το παρακάτω repository και συμπληρώστε τα κενά στο αρχείο `app/scripts/wordpress/wordpress.service.js`. Υπάρχουν σχόλια με την ένδειξη `TODO`.

* https://github.com/just-app-workshop/articles-ionic

Δουλέψτε στο δικό σας repository που θα προκύψει από την διαδικασία fork. Κάντε commit/push εκεί τις αλλαγές σας και όταν έχετε τελειώσει ετοιμάστε ένα [Pull Request](https://help.github.com/articles/using-pull-requests/)

#### Οδηγίες
Στο αρχείο `wordpress.service.js` υπάρχει η μέθοδος `getArticle` που αναζητά ένα article μέσα στο collection που ήδη υπάρχει cached στην μνήμη και έχει δημιουργηθεί από προηγουμενη κλήση της `getArticles`

Τροποποιήστε την υλοποίηση και κάντε ανάκτηση του συγκεκριμένου κάθε φορά άρθρου με εκτέλεση ενός νέου `http` request 

Παράδειγμα:

* http://demo.titaniumtemplates.com/wordpress/?p=38&json=1

### Άσκηση 3 - Firebase call
Κάντε fork το παρακάτω repository και συμπληρώστε τα κενά στο αρχείο `app/scripts/firebase/firebase.service.js`. Υπάρχουν σχόλια με την ένδειξη `TODO`.

* https://github.com/just-app-workshop/firebase-ionic

Δουλέψτε στο δικό σας repository που θα προκύψει από την διαδικασία fork. Κάντε commit/push εκεί τις αλλαγές σας και όταν έχετε τελειώσει ετοιμάστε ένα [Pull Request](https://help.github.com/articles/using-pull-requests/)

#### Οδηγίες
Στο αρχείο `firebase.service.js` υπάρχει η μέθοδος `getArticle`. Σκοπός της `getArticle` είναι η ανάκτηση από την υπηρεσία Firebase του `article` για το συγκεκριμένο κάθε φορά id. 

Συμπληρώστε την υλοποίηση και κάντε ανάκτηση του συγκεκριμένου κάθε φορά άρθρου με χρήση των υπηρεσιών (services) `$firebaseArray` ή/και `$firebaseObject`.

Εξετάστε πιθανές βελτιώσεις ή τροποποιήσεις στα αρχεία

* `app/scripts/firebase/firebase-article.controller.js`
* `app/scripts/firebase/firebase-article.html`

Χρήσιμοι σύνδεσμοι:

* https://www.firebase.com/docs/web/
* https://www.firebase.com/docs/web/libraries/angular/
* https://www.firebase.com/docs/web/libraries/angular/api.html
* https://www.firebase.com/docs/web/examples.html



## Bonus: Dependency injection
* [Dependency Injection @ wikipedia](https://en.wikipedia.org/wiki/Dependency_injection)
* [Dependency Injection and AngularJS](https://docs.angularjs.org/guide/di)
* [A beginners guide to Dependency Injection](http://www.theserverside.com/news/1321158/A-beginners-guide-to-Dependency-Injection)
* [Martin Fowler, Dependency Injection pattern](http://www.martinfowler.com/articles/injection.html)
* Επίδειξη: [Inject a service in `controllers.js`](https://github.com/just-app-workshop/ionic-demo-1/blob/master/www/js/controllers.js#L5)

## Χρήσιμοι σύνδεσμοι
* [lorempixel](http://lorempixel.com/)
* [lipsum](http://www.lipsum.com/)
* GitHub Organization: just-app-workshop
    * https://github.com/just-app-workshop/ 
* Σημειώσεις Εργαστηρίου
    * https://github.com/just-app-workshop/notes 
* Facebook Event 
    * https://www.facebook.com/events/1678337132424362/
* Slack Channel
    * https://justapp.slack.com 
