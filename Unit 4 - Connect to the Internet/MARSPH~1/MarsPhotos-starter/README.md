MarsPhotos - Starter Code
==================================

Starter code for [Android Basics in Kotlin](https://developer.android.com/courses/android-basics-kotlin/course).

Introduction
------------

Using this stater code you will create MarsPhotos is a demo app that shows actual images of Mar's surface. These images are
real-life photos from Mars captured by NASA's Mars rovers. The data is stored on a Web server
as a REST web service.  The solution app will demonstrate the use of [Retrofit](https://square.github.io/retrofit/) to make REST requests to the web service, [Moshi](https://github.com/square/moshi) to
handle the deserialization of the returned JSON to Kotlin data objects, and [Coil](https://coil-kt.github.io/coil/) to load images by URL.

The app also leverages [ViewModel](https://developer.android.com/topic/libraries/architecture/viewmodel),
[LiveData](https://developer.android.com/topic/libraries/architecture/livedata), and
[Data Binding](https://developer.android.com/topic/libraries/data-binding/) with binding 
adapters.

Pre-requisitesā
--------------

You need to know:
- How to create and use fragments.
- How to use architecture components including ViewModel, and LiveData.
- How to use coroutines for long-running tasks.


Resources
---------------

<details>
    <summary><b>Android developer documentation</b></summary>

- [ViewModel Overview](https://developer.android.com/topic/libraries/architecture/viewmodel)
- [LiveData Overview](https://developer.android.com/topic/libraries/architecture/livedata#kotlin)
- [MutableLiveData](https://developer.android.com/reference/android/arch/lifecycle/MutableLiveData)
- [ViewModelScope](https://developer.android.com/topic/libraries/architecture/coroutines#viewmodelscope)
- [Coroutines, official documentation](https://kotlinlang.org/docs/reference/coroutines-overview.html)
- [Binding adapters](https://developer.android.com/topic/libraries/data-binding/binding-adapters)
</details>

<details>
    <summary><b>Kotlin documentation</b></summary>

- [Exceptions: try, catch, finally, throw, Nothing](https://kotlinlang.org/docs/reference/exceptions.html)
- [Coroutines codelab](https://codelabs.developers.google.com/codelabs/kotlin-coroutines/)
- [Coroutines, official documentation](https://kotlinlang.org/docs/reference/coroutines-overview.html)
- [Coroutine context and dispatchers](https://kotlinlang.org/docs/reference/coroutines/coroutine-context-and-dispatchers.html)
</details>

<details>
    <summary><b>Other</b></summary>

- [Retrofit](https://square.github.io/retrofit/)
- [Moshi](https://github.com/square/moshi)
- [Moshi with Retrofit in Kotlin](https://proandroiddev.com/moshi-with-retrofit-in-kotlin-%EF%B8%8F-a69c2621708b)
- [Coil](https://coil-kt.github.io/coil/)
- [Binding adapters with Kotlin](https://android.jlelse.eu/binding-adapters-with-kotlin-part-1-78b957ad6b8b)
</details>
