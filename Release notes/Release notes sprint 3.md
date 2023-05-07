# Release notes sprint 3

## Sprint achievements

- I made sure everything is on kubernetes and I made the user and auth service sepherate. RabbitMQ is implemnted aswell.

## Project management tool

For the project management tool I used [Jira](https://semdewilde.atlassian.net/jira/software/projects/ST/boards/1).

## CI/CD pipelines and repository links

### Twitter user service
Service for twitter users

- [Repository link](https://github.com/S6-Semdw/TwitterUserService)

### Twitter auth service
Service where users can login and authenticate.

- [Repository link](https://github.com/S6-Semdw/TwitterAuthService)

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
  
  
## Sprint 4 planning 

Next sprint I will focus on the cloud and security so that I implented everything.

