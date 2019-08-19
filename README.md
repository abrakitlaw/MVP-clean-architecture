# MVP Clean Architecture
MVP is architectural pattern which mostly used for building user interfaces. In MVP, the presenter assumes the functionality of the "middle-man". In MVP, all presentation logic is pushed to the presenter. MVP advocates separating business and persistence logic out of the Activity and fragment

Why use MVP?
1. Makes debugging easier in Applications — MVP enforces three different layers of abstractions which makes it easier to debug your applications. Moreover, since business logic is completely decoupled from View, it is more easier to perform unit testing while developing your application.
2. Enforces better separation of Concerns — MVP does the great job of separating out your business logic and persistence logic out of your Activity and Fragment classes which in turn better enforce good separation of concerns.
3. Code Re-usability — In MVP, the code can be better reused since you can have multiple presenters controlling your Views. This is more important as you definitely don’t want to rely on a single presenter to control your different Views.

## Key concepts
The big difference with base MVP sample is the use of the Domain layer and use cases. Moving the domain layer from the presenters will help to avoid code repetition on presenters.

Use cases define the operations that the app needs. This increases readability since the names of the classes make the purpose obvious.

Use cases are good for operation reuse over our domain code. 

The execution of these use cases is done in a background thread using the command pattern. The domain layer is completely decoupled from the Android SDK or other third party libraries.

### Clean Architecture
![alt text](https://github.com/abrakitlaw/MVP-clean-architecture/blob/master/Screenshot%202019-08-20%20at%2001.44.56.png)

### Architectural Approach
![alt text](https://github.com/abrakitlaw/MVP-clean-architecture/blob/master/Screenshot%202019-08-20%20at%2001.51.45.png)

### Architectural Reactive Approach
![alt text](https://github.com/abrakitlaw/MVP-clean-architecture/blob/master/Screenshot%202019-08-20%20at%2001.51.58.png)
