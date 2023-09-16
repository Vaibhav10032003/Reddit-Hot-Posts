# Reddit-Hot-Posts

It is a java application which support various operations through api calling.Here we can also add post in the subreddit which we want with the help of api call. 1)The reddit api used to get access token is: https://www.reddit.com/api/v1/access_token 2)The api used for fetching subreddit data is https://oauth.reddit.com/r/ + subReddit + /hot 3)The api used for adding post to some subreddit is https://oauth.reddit.com/api/submit

Here I kept server to localhost:8099. The project provide access to following things: 1)To view hot posts for some subreddit also it will add the post into database if it doesn't exist localhost:8099/{subredditname} 2)To search by word for in the posts is localhost:8099/search/{word} 3)To delete some subreddit from your database localhost:8099/delete/{subredditname} 4)To sort all posts in your database by creation time is localhost:8099/sort 5)To add post into some subreddit from api calling is localhost:8099/reddit/addpost Here the method is POST and and additional details needed to provide are (String subreddit,String title,String text)

List of All subReddits of Reddit Present in our Database
![image](https://github.com/Vaibhav10032003/Reddit-Hot-Posts/assets/77986932/a9deb8e0-cfb9-4c34-a7a1-e9b4c4186ecc)

List of All Hot Posts sorted on creation time in Reddit Present in our Database
![image](https://github.com/Vaibhav10032003/Reddit-Hot-Posts/assets/77986932/38adb3f8-832d-4091-a276-eaebb3930561)

List of All Hot Posts which include programming word in their body or title
![image](https://github.com/Vaibhav10032003/Reddit-Hot-Posts/assets/77986932/2901087a-d265-43ea-b17d-ded393781b93)

Also, We can create a post into subreddit by using postman
![image](https://github.com/Vaibhav10032003/Reddit-Hot-Posts/assets/77986932/9f28f0fa-3551-49cd-9668-6daf0d4e79eb)
![image](https://github.com/Vaibhav10032003/Reddit-Hot-Posts/assets/77986932/c358a29e-d4de-4333-8a3d-188338e02efb)
