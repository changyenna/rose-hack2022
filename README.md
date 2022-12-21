# Rose Hacks 2022 Submission
This project was created as a submission to [Rose Hacks 2022](https://rosehack.com/index.html) and won 2nd place overall.
**Team Members**:  *Jonathan Lo, Eric Wang, and Yenna Chang*

![image](https://user-images.githubusercontent.com/97314187/208971663-eae066e7-b513-4792-a277-4a6c9f1799e4.png)
![image](https://user-images.githubusercontent.com/97314187/208971972-81eb7a58-17a3-40e2-ab48-95ea93c6ad64.png)

## Songnality
Songnality is a WebApp designed to predict an Animal Crossing character that the user most closely aligns with using their top song choices. In addition, users can see their assigned characters top/preferred songs. Currently Songnality features 8 Animal Crossing characters.

## Running Songnality
In order to run Songnality locally, you will need its dependencies and a Spotify Client ID and Secret.
### Set Up
 1. Clone the repository.
 2. Install pipenv and Django.
 3. Create a `config.json` and input Spotify Client ID and Secret according to `config.json.example`
 4. Start local server using: 
  ```
  python3 manage.py runserver
  ```


## Tech Stack
The backend is entirely written in Python using the [Django](https://www.djangoproject.com/) framework. The frontend is written in HTML and CSS. Songnality utilizes [Spotify's](https://developer.spotify.com/documentation/) REST API to search for songs and connect users to their previously created playlists.
