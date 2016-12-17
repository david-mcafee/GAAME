# THIS IS UNFINISHED


















# Component Hierarchy

NOTE: REVISE FOR SPLASH PAGE

- **AppContainer**
  - **NavContainer**
  - Nav
  - MainContent (home section)
    - SplashPage
    - **ArtistIndexContainer**
    - ArtistIndex
      - ArtistIndexItem
    - **SessionFormContainer**
      - SessionForm
    - **NewTrackContainer**
      - NewTrack
        - UploadTrackButton
    - **ArtistDetailContainer**
      - ArtistDetail
        - Header
        - **TrackIndexContainer**
          - TrackIndex
        - **TrackCommentsContainer**
          - TrackComments
            - CreateComment
            - CommentIndex
    - **AudioPlayerContainer**
      - AudioPlayer
        - Player
        - SongInfo
  - Footer  


## Routes

|Path   | Component   |
|-------|-------------|
| "/home" | "HomeContainer" |
| "home/sign-up" | "AuthFormContainer" |
| "home/log-in" | "AuthFormContainer" |
| "home/new-track" | "NewTrackContainer" |
| "home/artist/:artist-id" | "ArtistPageContainer" |
