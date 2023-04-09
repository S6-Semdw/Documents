# Release notes sprint 2

## Sprint goals

- As a twitter user I want to be able to login so I can watch and post tweets
- As a twitter user I want to be able to register an account So I can save my tweets
- As a twitter user I want to be able to make tweets so I can share something with my friends if I want to

## Sprint achievements

- I was able to make the login and registration for the twitter users and get a JWT token back. I also setup the tweet service the functionallity is there when im building it out later with users.

## Project management tool

For the project management tool I used [Jira](https://semdewilde.atlassian.net/jira/software/projects/ST/boards/1).

## CI/CD pipelines and repository links

### Twitter user service
Service where users can login, register and authenticate.

- [Repository link](https://github.com/S6-Semdw/TwitterUserService)

### Twitter tweet service
Service where users can make tweets

- [Repository link](https://github.com/S6-Semdw/TwitterTweetService)

### Twitter API gateway
Service that get's api requests from the client

- [Repository link](https://github.com/S6-Semdw/TwitterApiGateway)


### Docker image pipelines

When pushing to the main branch of the repo, a docker image gets built and is put onto docker hub. This is made for the User, Tweetservice and API gateway. 

- https://github.com/S6-Semdw/TwitterUserService/actions/workflows/docker_image.yml
- https://github.com/S6-Semdw/TwitterTweetService/actions/workflows/docker_image.yml
- https://github.com/S6-Semdw/TwitterApiGateway/actions/workflows/docker_image.yml


## Sprint retrospective

Keep doing:
  -	Keep the speed  
  - Good planning
  
Should Improve:
  -	Writing documentation for the services
  
  
## Sprint 3 planning 

For the next sprint I will be working on the functionality that users can make a tweet with the JWT token integration I made this sprint. Besides that I will look more into kubernetes and messaging. As of now i have this very basic.
The API-gateway will also be improved. And if there is any time left I can also look into azure deployment.

