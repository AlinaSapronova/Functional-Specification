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
- As a user, I want to register for an account to get access for challenges.
- As a user, I want to be able to watch video.
- As a user, I want to be able to see my progress.
- As a user, I want to be able to edit my profile.


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
- birthday

### Challenges
- id
- name
- parent_id
- child_id
- name
- title

- ### Days
- id
- challenge_id
- exercise_id
- comleted_at

 ### Exercises
 - id
 - title
 - video_url
