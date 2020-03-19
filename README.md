# Weatherapp
Weatherapp is a simple forecast app, which uses some APIs to fetch 5 day / 3 hour forecast data from the [OpenWeatherMap](https://openweathermap.org/forecast5) and to fetch places,cities,counties,coords etc. from [Algolia Places](https://community.algolia.com/places/) Was done in java first and refactored to kotlin!

## Libraries and tools 🛠

<li><a href="https://developer.android.com/topic/libraries/architecture/navigation/">Navigation</a></li>
<li><a href="https://developer.android.com/training/data-storage/shared-preferences">Shared Preferences</a></li>
<li><a href="https://developer.android.com/topic/libraries/architecture/viewmodel">ViewModel</a></li>
<li><a href="https://developer.android.com/topic/libraries/architecture/livedata">LiveData</a></li>
<li><a href="https://developer.android.com/reference/androidx/lifecycle/Transformations">Transformations</a></li>
<li><a href="https://developer.android.com/topic/libraries/data-binding">Data Binding</a></li>
<li><a href="https://developer.android.com/topic/libraries/architecture/room">RoomDB</a></li>
<li><a href="https://github.com/ReactiveX/RxJava">RxJava</a></li>
<li><a href="https://github.com/ReactiveX/RxAndroid">RxAndroid</a></li>
<li><a href="https://github.com/ReactiveX/RxKotlin">RxKotlin</a></li>
<li><a href="https://github.com/google/dagger">Dagger 2</a></li>
<li><a href="https://square.github.io/retrofit/">Retrofit</a></li>
<li><a href="https://github.com/square/okhttp">OkHttp</a></li>
<li><a href="https://github.com/square/moshi">Moshi</a></li>
<li><a href="https://github.com/facebook/stetho">Stetho</a></li>
<li><a href="https://github.com/square/picasso">Picasso</a></li>
<li><a href="https://material.io/develop/android/docs/getting-started/">Material Design</a></li>
<li><a href="https://github.com/lopspower/RxAnimation">RxAnimation</a></li>
<li><a href="https://github.com/JakeWharton/ThreeTenABP">ThreeTenABP</a></li>
<li><a href="https://github.com/pinterest/ktlint">Ktlint</a></li>
<li><a href="https://github.com/algolia/algoliasearch-client-android">Algolia Search API Client for Android</a></li>
<li><a href="https://github.com/loopeer/shadow">Shadow</a></li>

## Testing 🧪
<li><a href="https://github.com/mockk/mockk">Mockk</a></li>
<li><a href="https://github.com/google/truth">Truth</a></li>

## Architecture
The app uses MVVM [Model-View-ViewModel] architecture to have a unidirectional flow of data, separation of concern, testability, and a lot more.

![Architecture](https://developer.android.com/topic/libraries/architecture/images/final-architecture.png)

## Dependency Graph 🔪
The following diagram shows the dependency graph of the app.


Generated by [Daggraph](https://github.com/dvdciri/daggraph)

## Design
Inspired by [Ramonyv](https://www.uplabs.com/posts/weather-app-freebie) and weather icons taken from [isneezy/open-weather-icons](https://github.com/isneezy/open-weather-icons)

<h2 id="license">License</h2>

<pre><code>Copyright (c) 2019 Furkan Aşkın

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction.
SOFTWARE.
</code></pre>
