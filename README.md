# JustApp Workshop - Σημειώσεις Εργαστηρίου και Υλικό Παρουσιάσεων

## Εβδομάδα 1η

### Εισαγωγή
* [Εισαγωγή](https://docs.google.com/presentation/d/1AAZmbbWhKPyoUTJNhaMEGWt1jhg749qOTRyYReL-oYw/edit?usp=sharing)

### Prepare your box for Ionic development
* [Linux / MacOS] (https://github.com/just-app-workshop/notes/blob/master/linux-macos.md)
* [Windows] (https://github.com/just-app-workshop/notes/blob/master/windows.md)

### Cordova / Phonegap and Ionic
* [JustApp - Cordova & Ionic - Εισαγωγή και παραδείγματα](https://docs.google.com/presentation/d/1AdYCEbb-PMWlEkLFrWk0vg-fmSOXycT6A7uBpg9122E/edit?usp=sharing)

### Emulators
* iOS Simulator
* [Genymotion](https://www.genymotion.com/)
* Demo .APK
    * [Restaurant App](http://codecanyon.net/item/restaurant-ionic-full-application-with-firebase-backend/14680675)

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

### Grunt and Bower
* [GRUNT, The JavaScript Task Runner](http://gruntjs.com/)
    * [Grunt Demo 1](https://github.com/just-app-workshop/grunt-demo-1) 
* [Bower, A package manager for the web](http://bower.io/)
    * [Bower Demo 1](https://github.com/just-app-workshop/bower-demo-1)

### Bonus: Dependency injection
* [Dependency Injection @ wikipedia](https://en.wikipedia.org/wiki/Dependency_injection)
* [Dependency Injection and AngularJS](https://docs.angularjs.org/guide/di)
* [A beginners guide to Dependency Injection](http://www.theserverside.com/news/1321158/A-beginners-guide-to-Dependency-Injection)
* [Martin Fowler, Dependency Injection pattern](http://www.martinfowler.com/articles/injection.html)
* Επίδειξη: [Inject a service in `controllers.js`](https://github.com/just-app-workshop/ionic-demo-1/blob/master/www/js/controllers.js#L5)
