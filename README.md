The app has pull to refresh functionality that makes a network request in the background and updates its UI state based on the result.

An error message will be displayed if the network request is unsuccessful, but the app will continue to display the local app data. You can see the error state by disabling wifi and turning on airplane mode and then pulling to refresh. After seeing the error, please turn off airplane mode, enable wifi, and pull to refresh to have the message go away once the network request is successful.

Please look at MainActivityViewModelTest to run the tests on the main ViewModel class. I 2 test cases that validate the success, failure, and loading states after refreshing the app data.
