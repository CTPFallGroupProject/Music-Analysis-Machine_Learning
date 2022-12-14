Visit our app: https://ctpfallgroupproject-vibify.streamlit.app/ 

# Vibify - NLP Analysis on Lyrical Data

Vibify (vibe-if-eye) is a web application that takes in lyrical data as input, passes it through our models and compares it against our database, and outputs a dashboard consisting of:

- Positive/Negative Sentiment Analysis (Valence)
- The genre of the lyrics (Pop, Rock, R&B, Country, etc.)
- Top-5 Lyrically Similar Songs

![Imgur](https://i.imgur.com/iAQgbMP.png)
![Imgur](https://i.imgur.com/hxFR4UZ.png)

# Who is Vibify For?
Vibify is a tool for songwriters and song-curious people to enhance their analysis and understanding of lyrics. Some use cases:
- Say you need to write a happy sounding song for a movie that you're scoring, but aren't sure how happy it sounds. Vibify will give you a continuous 0 (very sad) to 1 (very happy) rating based on existing songs that were used to train the model, helping you better understand how your song stacks up. 
- Maybe you've got writer's block and are looking for inspiration? Input the lyrics you have written so far, and Vibify returns the 5 most similar songs for you to peruse for content inspiration. 


# Table of Content:
- [Vibify](#vibify)
- [Who is Vibify For?](#who-is-vibify-for)
- [Table of Content:](#table-of-content)
  - [Authors](#authors)
  - [Dependencies](#dependencies)
  - [Datasets](#datasets)
  - [App Features](#app-features)
  - [Hosted on ](#hosted-on-)
- [What's Next for Vibify](#whats-next) 


## Authors

Vibify was created during CUNY Tech Prep's fall 2022 cohourt. The team consists of:

- Aleksandra Georgievska [@aleksgeorgi](https://github.com/aleksgeorgi)
- Deepankar Ckakraborty [@deepankarnk2](https://github.com/deepankarck2)
- Stephen Williams [@svalentinow](https://github.com/Svalentinow)

## Dependencies

- streamlit
- streamlit_option_menu
- streamlit-extras
- tensorflow
- nltk
- scikit-learn


## Datasets
- https://www.kaggle.com/datasets/edenbd/150k-lyrics-labeled-with-spotify-valence 
- Additional featurs were added by webscraping Genius.com
- [Our Preprocessed Dataset](https://drive.google.com/file/d/1Txh9TCzWfEc9ermiwQqYAljGyfml1Pxj/view?usp=share_link)
- [Our Lyrical Dataset + Webscraped Genres](https://drive.google.com/file/d/1w_OoHoDnicfSF3evibndVeDATbBzMI7K/view?usp=share_link)


## App Features

- The navbar allows the user to navigate to the Main page and an About Us page on the creators of the app
- After input has been received, the main page produces the dashboard. A user can then reset the dashboard to enter a new input


## Hosted on 

- https://streamlit.io/

## Project Management
- Timeline and deliverables was established by CUNY Tech Prep staff with a demo night scheduled 8 weeks after group formations
- Trello was used by group members to manage action items and progress statuses 
- Github was used by group members for version control 
- Weekly meetings were held via Zoom by group members
  - To-discuss agenda items and meeting minutes were tracked on Slack by group members


## What's Next for Vibify?

Improvements and additions we would like to make to Vibify in the future include:

- An expanded dataset containing more songs and a larger set of genres
- Additional inputs/filters from the user
  - Example: Input lyrics & genre -> get similar songs from a particular genre only 
- Audio analysis 
  -  Ability to extract lyrics 
  -  Ability to anylize positive/negative sentiment from the sound of the audio 





