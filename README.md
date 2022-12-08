We learned web development by building a React JS app, made up of video sections, custom categories, channel pages and most importantly, we can play videos directly from the YouTube app!

App features:

Interface is the same as Youtube.  

In the App.js folder, we have page routes, as in the criteria we created 4 pages. Components such as Navbar, SearchBar, Sidebar (categories) and Feed work on the main page. In the channel page, we have channelcard and channelDetails. 
As for the video - videoCard and videoDetail. And as for the video search - SearchBar and SearchFeed.

There are YouTube categories in the SideBar component, if you click on any category, you will get a video related to this category.
And you can also subscribe to YouTube channels that you are interested in and they will be in the list of your subscriptions.
Each channel has a channel card - that is, the ava of each channel and the name. And the videos of this channel will be visible.
If you go to the page of this channel, you can see the channel banner, channel login and the number of subscribers.

You can search YouTube videos in SearchBar, you will get a video, and if you click on any video, you can see the name of the video, the channel of this video and the number of likes and views. And you will also have similar videos. You can watch any 
youtube videos.

We worked with RapidAPI(which is an API marketplace) and material-ui(reactJS's framework).
'https://youtube-v31.p.rapidapi.com' - is URL or Host of Youtube.
'd0f601212emsh022dafbc47f299ep1e2005jsn618db42847fb' - is the Key of Youtube.
We sent axios request and got needed info about exact component data(channelID, videos, photos, number of subscriptions, likes etc.).

Using material-ui(reactJS's framework) we got icons to our categories. And got needed API 
documentation for our components(Box, Stack, Typography, CircularProgress etc.).
Material Ui provides google-ready solutions for fast and fairly simple web development. 

We used Lifecycle methods was included to useEffect().

We used hooks like useState() and useEffect() - ChannelDetail.jsx, Feed.jsx, SearchBar.jsx, VideoDetail.jsx.

We used Navigation to search videos in component SearchBar.jsx.

So in our React project we have everything about the criteries of project. Our Youtube app is directly connected
with real Youtube. 

