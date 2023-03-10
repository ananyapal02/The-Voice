# The Voice
"The Voice" is a dictionary that answers all your queries by reading aloud. Whether it's a male or a female voice, fast or slow, you can adjust your preferences in this new developing project. 

## Motive:
In the world of rat-race, many are hardly finding time to read. However, we all have the desire to know more constantly. "The Voice" will help you to solve this purpose. It is a voice dictionary that will answer your queries through audio. Hence, instead of searching thoroughly in the dictionary or finding the right website to know your answer, "The Voice" will provide you accurate and crisp results in seconds. 

## Modules used:
Module        | Use
:-------------: | :-------------:
wikipedia     | Fetches the content of the query.
pyttsx3       | Reads aloud the results fetched by `wikipedia`. <br/>Also adjusts rate, volume, gender and length.

## Functionalities:
- This project requires the installation of two modules at first - `wikipedia` and `pyttsx3`. You can install it by typing `pip install wikipedia` and `pip install pyttsx3` in command prompt. 
- Then first it takes the **rate** or speed at which you want your data to be read aloud. It ranges from 100 to 1000, and the default value is 200.
- Then it takes the **volume** at which you want your data to be read aloud. It ranges from 0 to 1, and the default value is 1.
- Then it takes the **choice** of voice at which you want your data to be read aloud. It can be 0 for male and 1 for female. Its default value is 1.
- Then finally it takes the **query**, about which you want to know about.
- Then, it wants to know the **length** of your results for your query.
- Whoa! Your query is answered.
- Finally, an update to save the results in __.mp3__ or **.txt** or both formats is provided.

## Future Scope:
As it is still in the development stage, I have plans to implement the functions in the project:
- Read aloud results in different **languages**.
- **Translates** a phrase from one language to another.

*Thanks for making it till here. Any suggestions and improvements are gladly appreciated! :)*
