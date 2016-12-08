# pythonScriptForPullingTwitterUsernames

This python script will  automatically extract all the usernames from a .html download of the "People" output of Twitter's in-browser search engine. (See the following URL for an example: https://twitter.com/search?f=users&vertical=default&q=linguistics&src=typd)

Included in this repo is:

1) the python script itself. Written under Python 2.7.6. WARNING: May not work under Python 3, I have NOT tested it. (Feel free to fork/modify as needed.)
2) a sample .html file, of Twitter accounts associated with the search "lingustics"
3) sample output, based on the given .html file

Some notes:
- to keep your file system tidy, you may want to remove spaces when saving .html files from Twitter
- the script will run over every .html file in its current directory
- the console output is just the user names, the .csv output has two columns. The first column is the username, the second the file it was taken from.

Don't hesitate to contact me with questions.
