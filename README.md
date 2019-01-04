# Byld Sessions
For keeping track of all the events by Byld

## How to use it?

### For the general audience

- Suggest events you want to be organized by Byld (in the *Issues* section)
- Suggest improvements in the current/proposed offering of an event (in the *Issues* section)
- Get the first update on the new/proposed events(If you watch the repo)

### For volunteers

Showcase that you volunteered for an event. Since volunteering for Byld events is one of the membership criteria, we will be using this repo to keep track of your contribution as a volunteer.   
You can actively participate in the event discussion to suggest improvement(in content, organization, or anything you want).  
Maintaining this repo is a bit tedious. Hence, any help would be appreciated.

### For speakers

Open a new issue and add the speakers-needed and proposed-events labels, or you an use this handy [shortcut](https://github.com/IIIT-Delhi/talks/issues/new?assignees=&labels=proposed_events%2C+speakers-needed&template=event-proposal.md&title=). Make sure event you're proposing hasn't already been proposed!

## FAQs

### How to watch the repo?
See the top right portion of the screen. The first button in the group of "Watch", "Star" and "Fork". Just click on it.

### How to propose/suggest a new event?
You need to make a new issue for proposing or suggesting a new event. This can done by clicking [here](https://github.com/IIIT-Delhi/talks/issues/new?assignees=&labels=proposed_events%2C+speakers-needed&template=event-proposal.md&title=). Please ensure no duplicate issue exists for that event.

### How to volunteer for an event?

**Before the event:**  
In the issue for the corresponding event, add a comment that you want to volunteer for the event.

**After the event:**  
Having volunteered for the event, you need to add your name in the volunteers sections of the event and send a PR. The byld admin responsible for the event will approve the PR, if your efforts were okay.

## Conventions:

This is under progress.

- `archive` stores previous info about the talks
- `current` folder stores events from the current semester
- each event will have its own folder
- the name of the folder must be in the following format: `hackeve_011-name_of_the_hackeve`
- the folder should have one `README.md` file
- the `README.md`  should have atleast the following meta data in this specific format:
```
type: HackEve | HackNight | Hackathon | Colab 
name:  Event Name
event-description:
location:
start-date: DD MONTH YY
start-time: HH:MM AM/PM
speaker: comma seperateted list of GitHub id
duration: write any details of the event timing here
volunteers: comma seperateted list of GitHub id
byld-admin-poc:
```
- other suggested contents:
    - slides: both renders and source(if apply)
    - code used in the talk
    - instructions

You're encouraged to put as much as you can on here. This makes the material of the sessions useful for future sessions, reference for the audience and for public information that the club if alive and functioning.
