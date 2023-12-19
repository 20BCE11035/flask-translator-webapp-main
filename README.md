# flask-translator-webapp-main
This project is based on learning gained from Micrsoft Learn platform.
I have built a webapp using Flask, Python and Azure Cognitive Services to translate text in multiple languages.

We Learnt:
1. How to set up a Flask development environment
2. How to use Flask to build a form and
3. How to use the Translator service to translate text

Tools Used: Python(3.6 or above) and Visual Studio Code.

For translator service, we have used Azure Cloud Computing platform for accessing the keys for Cognitive Services.


Creating the app:
- I have created the core application in file named app.py
- The routes have been added for GET and POST methods for the user to fetch the HTML page (GET) and to provide the text, choose the translator language code and recieve the translated text along with the language code the user chose earlier (POST)
- The HTML code is present in 'templates' folder where we have two files index.html to take the input (to accept the text and language code as response for translation service) and result.html to show the output (original text, translated text and language code selected by the user)


#### Once you integrate html codes with flask application and cognitive service, on accessing the IP address at port 5000 the output should look like as shown below:
### For index.html
![image](https://user-images.githubusercontent.com/44521329/118927174-0614f300-b95f-11eb-93b8-caf6c9537b77.png)

### For results.html
![image](https://user-images.githubusercontent.com/44521329/118927296-32c90a80-b95f-11eb-985d-ffd3453a7d4b.png)

