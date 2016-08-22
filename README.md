# Build an Android Application:

- Podcasts List activity (RecyclerView is preferred)

    - List top 50 podcasts per selected country.
    - Progressively load 10 more podcast items in case of scrolling to the end of list.
    - Showing cover, title, description, author in each list item.
    - Open Podcast Detail Activity in case of clicking one podcast item.
    - Use below API to get data: `http://data.castbox.fm/top?country=us&skip=0&limit=20`

- User can change country list below

    - US/GB/ES/FR/DE/PO/CA/AU/CN

- Podcast Detail Activity

    - Show detailed info of selected podcast, including cover image, author, title and description.
    - Show tracks list of the podcast.
    - Each track item should include cover/title/description/releaseDate (show podcast cover in case of track cover is empty)
    - Show playing button on each track item.
    - Play the track audio when user clicks the play button, and replace play button with an playing gif.
    - Click the playing gif can pause the audio playback.
    - Show a playback widget on notification, even after user exits the app. User can start audio playback via the notification widget.
    - Get the tracks list per API: `http://data.castbox.fm/track?key=:tid`

# Requirements

- Retrofit/RxJava is preferred for API invoke, and Error handle is required.
- Fresco or Glide is preferred for image loading.
- Any dependency injector like Dagger/ButterKnife is preferred.
- Any other library to improve productivity and quality is preferred.
- Material Design preferred.
