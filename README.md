This is an Android app code written in Kotlin. 
The app has a single activity called MainActivity which extends AppCompatActivity and sets the content view using R.layout.activity_main. 
The activity calls an AsyncTask named CallAPILoginAsyncTask to make a network call in the background. 
The AsyncTask class makes a GET request to the URL "https://run.mocky.io/v3/ccf54d29-5420-4518-bba9-3e855eb1c990" using HttpURLConnection. 
The response from the API call is logged with a tag "JSON RESPONSE RESULT". The AsyncTask also displays and hides a progress dialog during the network call.
