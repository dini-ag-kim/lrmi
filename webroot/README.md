# Instructions for using Hugo with these website sources

***In the instructions below, `<LOCAL_FOLDER>` refers to the folder containing your checked-put working-copy of this Github repository.***

[The Hugo documentation is comprehensive and useful.](https://gohugo.io/documentation/)

Any changes committed to this repository, or pushed to this repository from a remote checked out copy, will **automatically** rebuild the website at: http://lrmi.dublincore.org

### Serving the website on your local machine with Hugo
1. Install Hugo ([instructions](https://gohugo.io/getting-started/installing/))
2. `git clone git@github.com:dcmi/lrmi.git <LOCAL_FOLDER>`
3. `cd <LOCAL_FOLDER>/webroot`
4. `hugo server`
5. Got to http://localhost:1313/ with your web browser

### Creating a new web-page

1. `cd <LOCAL_FOLDER>/webroot`
2. `hugo new <NAME_OF_WEB_PAGE>.md`
