# Tim Defense Blog Engine

Tim Defense Blog Engine (TDBE), is a "blog engine" powered by TurboWarp, made for the upcoming Tim Defense's new website).

# How does it work?

It works by basically fetching data from the JSON files (url.json and title.json) into the project, clicking on one of the posts will redirect into the post selected (if it is being run on an iframe, it will redirect inside it due to the way iframe works). The "posts" are basically pages made in GrapesJS Studio (although it may be possible using different website builders).

# How to use it?

Oh, it's pretty easy, it's a TurboWarp project, after all, just download the SB3 file, then use TurboWarp (you can use it online or download the desktop version) and start modifying it for your needs. You can also begin importing lists as "url.json" and "title.json" respectively. Then, you need to create a repository on GitHub, then you'll need to create a folder named "Data", you can do it manually or just importing the JSON files into the folder and then uploading it into your repository. Then import it as a ZIP file (HTML may work too), extract it (in case if it was exported as a ZIP file) and then upload it to GitHub. Then you need to deploy your repository as a website (you can use any web hosting that suits your needs). When you create a new post using GrapesJS Studio, You will need to modify both "url.json" and "title.json", don't worry about your TurboWarp project, it'll automatically update it.
