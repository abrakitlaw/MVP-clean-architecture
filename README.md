# MVP-clean-architecture
MVP is architectural pattern which mostly used for building user interfaces. In MVP, the presenter assumes the functionality of the "middle-man". In MVP, all presentation logic is pushed to the presenter. MVP advocates separating business and persistence logic out of the Activity and fragment

Why use MVP?
1. Makes debugging easier in Applications — MVP enforces three different layers of abstractions which makes it easier to debug your applications. Moreover, since business logic is completely decoupled from View, it is more easier to perform unit testing while developing your application.
2. Enforces better separation of Concerns — MVP does the great job of separating out your business logic and persistence logic out of your Activity and Fragment classes which in turn better enforce good separation of concerns.
3. Code Re-usability — In MVP, the code can be better reused since you can have multiple presenters controlling your Views. This is more important as you definitely don’t want to rely on a single presenter to control your different Views.

### Clean Architecture
