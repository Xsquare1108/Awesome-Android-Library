# Awesome-Android-Library
TOP Android Library 

![alt text](https://photos.infinum.co/store/1fa7fb5d2d304d987ede135b2d54dcc6.jpg)

### Table of Contents
- [Retrofit](#retrofit)
- [Moshi](#moshi)
- [Chuck](#chuck)
- [Glide](#glide)
- [ThreeTen](#threeten)
- [Timber](#timber)
- [Room](#room)
- [RxJava](#rxjava)
- [Android KTX](#androidKTX)
- [Dagger](#dagger)

### Retrofit
Retrofit is type-safe HTTP client that allows you to define your REST API as an interface. You can manipulate the API requests’ body, headers, query parameters and much more via annotations, which makes everything clean and simple. Retrofit also allows synchronous and asynchronous API calls execution.
[Retrofit](http://square.github.io/retrofit/)
### Moshi
Moshi is a library that converts JSON into Java and Kotlin models. A lot of people refer to the Moshi as GSON 3.0. This library is superior to GSON in several aspects: it's faster, it includes Kotlin support, it's maintained, it throws predictable exceptions and it doesn't use broken DateTime adapter by default. Plus, converting JSON to Java model (and vice-versa) is straightforward with Moshi.
[Moshi](https://github.com/square/moshi)
### Chuck
Chuck is an HTTP inspector for Android that allows you to dig into your application’s HTTP history on your mobile phone. The HTTP log is displayed as a notification, which you can expand to open full Chuck UI. When you use Chuck, your quality assurance team will applaud you as they will be able to see whether an issue persists on Android or the backend side. This library is also sometimes more useful than logcat. That’s because your HTTP history persists even if the app is killed, while logcat sometimes cleans itself after the app is restarted.
[Chuck](https://github.com/jgilfelt/chuck)
### Glide
As you probably know by now, Android image loading and handling API is terrible. It’s a nightmare to even resize an image without getting “OutOfMemoryException.” Glide is an image loading library that exposes a nice API, allowing you to transform your image however you want.
[Glide](https://bumptech.github.io/glide/)
### ThreeTen
ThreeTen is a date and time handling library for Android. It is a backport of JSR-310, which was included in Java 8 as a standard “java.time.*” package. We love this library because the standard Android Calendar API is a nightmare to work with.
[ThreeTen](https://github.com/JakeWharton/ThreeTenABP)
### Timber
Timber is powerful, yet simple, logging library built on top of Android “Log” class. It allows you to easily turn logging on or off. It also offers nice support for logging formatted strings and exceptions. Because of all these benefits, Timber is one of the core libraries we use on almost all our Android projects.
[Timber](https://github.com/JakeWharton/timber)
### Room
Room is an official Android ORM, and there are multiple reasons for that status. This library features a beautiful API that is similar to Retrofit. It also relies heavily on annotations and standard SQL syntax.
[Room](https://developer.android.com/training/data-storage/room/)
### RxJava
RxJava is a Java implementation of ReactiveX API that allows you to chain asynchronous tasks and events into observable sequences. Users expect modern applications to display data in real-time. In other words, they want to see data updated automatically. That’s where RxJava can help.
When fetching real-time data, it becomes extremely difficult to merge multiple API calls, switch threads and handle errors. This is where RxJava shines, and it is the reason why we started using this library. I will admit that RxJava is confusing and hard to learn, but it is completely worth your time. Even after we switched to Kotlin, we continued to use RxJava because of its benefits. Together with Kotlin, the API is even better thanks to the additional extension functions.
[RxJava](https://github.com/ReactiveX/RxJava)
### Android KTX
Android KTX is a set of Kotlin extensions that wraps Android API, making it more user-friendly. The whole purpose of this library is to make Android API more pleasant to use. It adds a lot of methods and cool new features of Kotlin, such as named parameters, lambdas, and default parameter values.
[Android KTX](https://github.com/android/android-ktx)
### Dagger
Without Dagger, our Top 10 libraries list would be incomplete. Dagger is a fully static, compile-time dependency injection framework. Similar to RxJava, Dagger is really hard to understand (it took me a while to understand their CoffeeMaker example), but completely worth your time and effort.
Dependency injection is a way to provide smaller components to another model and glue them together with minimum effort. For example, if you have a Car model, you can provide tires to it and easily replace the tire implementation in the future—all without having to change a single line in your Car model.
When developing larger applications, you don’t want to handle dependency injection yourself because the code will grow quickly and become extremely difficult to maintain. Dagger helps you avoid this because it creates your dependency injection graph in compile-time via annotation processing.
In the last year, Google also included a separate Dagger Android module, which allows you to write less boilerplate code and inject dependencies easier.
[Dagger](https://google.github.io/dagger/)
