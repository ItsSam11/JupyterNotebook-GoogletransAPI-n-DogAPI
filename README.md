# JupyterNotebook-GoogletransAPI-n-DogAPI

This JupyterNotebook retrieve 5 facts about dogs from the [Dog API](https://kinduff.github.io/dog-api/) with the get method from the request library, those facts are in english so I decided to translate them to spanish using the [GoogleTrans](https://pypi.org/project/googletrans/) library, this library use the [Google translate ajax API](https://translate.google.com/) to make calls to such methods and translate the information, and the way I show the information is using the pandas library to create a Data Frame and display all the facts in spanish, like this: ![image](https://user-images.githubusercontent.com/83468277/213096308-946699b8-f603-41eb-bb34-26e73a597f25.png)

The main idea was to retrieve information from a random api and create a data frame with that information and then convert the data frame into a json and send it to an api from amazon, all this using LambdaAWS.
