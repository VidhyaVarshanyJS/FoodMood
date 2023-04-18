# Mood Based Food Recommender

A simple flask app recommends restaurants in different cities based on User Moods and Other Filters.

# Installation 

- Create Virtual Environment for the project `python -m venv <venv-name>`
- Install the dependencies:
    `pip install numpy pandas matplotlib seaborn wordcloud nltk flask `

- For nltk package, download the `stopwords` and `wordnet3.1` (rename it to wordnet after download) from https://www.nltk.org/nltk_data/. After download , uzip them.Create `nltk_data\corpora` folder in the `C drive` and put the stopwords and wordnet folder there.Set your `NLTK_DATA` environment variable to point to your top level `C:\nltk_data` folder(system variables).Refer ,https://www.nltk.org/data.html

# Run the flask app
`flask run` -(redirect to)> `http://localhost:8080`
## Screenshots

![image](https://user-images.githubusercontent.com/76642252/232864638-eea77b4a-80e0-4d59-9931-552518b7bec8.png)

<b> Laziness mood food restaurants</b>
    
![image](https://user-images.githubusercontent.com/76642252/232864736-ad164aa3-6964-4616-8ebc-1aa6d28d9dff.png)

