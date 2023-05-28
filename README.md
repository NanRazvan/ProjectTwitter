# ProjectTwitter
We propose to recreate the popular social networking platform Twitter. An observant eye will notice that any text-based social networking platform serves as the foundation for other social networking platforms with more complex features.
-----------------------------------------------------------------------------------------------

    The functionalities of the client application are as follows:
- Upon starting, a user is given the option to log into their account or create a new account. Logging in/registering requires entering a username.

- Attention: the username must be unique!

- The main menu displays the following options (functionalities):

- Post: The user can make a text post of up to 140 characters.

- Personal Profile: The user can view their post history.

- Follow function: The user can "follow" other users. This way, you can build the social graph of the platform.

- Feed: Viewing posts. One post will be displayed at a time - see details below. Under the post, the following options will be available:

- Like or Dislike: The user can like/dislike a post and can undo their reaction.

- Comment: The user can write a comment, and the list of comments will be updated.

- Retweet: The user can add a comment to their own post.

- Go to referenced tweet: If the post is a retweet, the original post can be accessed.

- Keyword Search: The user enters a query consisting of multiple keywords, and posts containing at least one of the keywords will be displayed - see Inverted Index.

- User Search: The user enters a username as a query, and the result list is displayed. A result does not have to be identical to the query; approximate matches can also be displayed. To compare strings, implement the Levenshtein distance.

- Networking: Communication between the client applications and the server will be done using sockets.

- Databases: The data used by the server will be manipulated using a database.
