GitProfile is an android app which communicates with the public Github API in order to display information about a specific user.

Functionality as per Scotia Bank requirements.
The app should accept a github user's id as input and display the specified user's avatar and name.
For each public repository owned by the user, the name and description are shown in a scrollable list.
When a repository is selected, the app displays the details regarding that specific repo.

Architecture
The application utilizes MVVM pattern Model-View-ViewModel.
Restful API - Retrofit, OkHttp, LoggingInterceptor, Gson
DI (Dependency injection) - Hilt.
