# Functional-Specification
# Exercises for kids MVP Specification
A simple application for keeping kids busy, to create good habits, give more self-confidence and improve physical health.

## Pain Point
For parents and kids if the try to find way to:
- redirect children's energy in right direction,
- give kids some activities for health,
- keep interested in sport,
- for excess or lack weight,
- controlling emotions and etc.

## User Stories
- As a user, I want to be able to register with my email and password, so that I can create an account to get access for challenges.
- As a user, I want to be able to edit my profile. 
- As a user, I want to be able to choose challenge and watch exercises for each day in challenge 
- As a user, I want to be able to track my progress.


## Domain Model

### Parents
- id
- email
- password
- name


### Children
- id
- parent_id
- name
- gender
- birthday


###Progress
- id
- challenge_day_id
- child_id

###ChalangeDay
- id
- challenge_id
- day_id


### Challenges
- id
- title

- ### Days
- id
- number

 ### Exercises
 - id
 - title
 - video_url
 - day_id
