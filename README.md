# How-To-Walk-in-a-Crowd-Fast
This project refers to a simple problem: have you ever been stuck in a crowded room and tried to get out of it fast? Whats the best rout to take between standing still and moving people? What about moving with a crowd in a narrow street andf there are people walking one way and the opposite way? What is the fastest way to get ahead? Certainly not to just keep following the crowd. But how then? Common tactics to be tested are: - walk close to the 2 walls, - zigzag between people, - follow closely behind one person, take over them and follow the next one and repeat. Does it make a difference if you ask "scuse me coming through"?

The setup.
The first thing we need to do is to record a bunch of crows of people walking. This will give us an idea of how crowds behave

Imagine you have to join a friend at the end of a street that is waiting for you and you are already late and she is texing you "Where are you?" Imagine now that the street is crowded with people coming your same direction, other people walking the opposite direction, some stopping unexpectedly to check out a pair of shoes they saw in a window, others turning around and going the opposite direction.
The question is: Is there a strategy to adopt with its own pattern, that will lead to the fastest way to walk through such an unpredictable crowd, or it doesnt really matter?

Step1:
record walking crowds in random streets of Florence.

Step2:
Analyze the video and create a ML that identify people in the crowd. These people will be boxes and their walking pattern will be recorded on 5 dimensions:
1 Speed
2 Wobbliness (walking in a straight line or going side to side)
3 Friction (are they following ohers or going around them)
4 Composition (single, couple that doesn't want to be separated or a larger group)
5 Stop (are they stopping frequently or not (window shoppers)

Step3:
The street will become a grid and the ML will calculate the total time that each person will take to reach a certain point. For example from the beginning of the street to the end. Since some people will not be motivated to reach the end of the street but others are, the ML will then "shed" the slowest walkers and only consider the fastest walkers.

![Screenshot](url_to_screenshot_or_demo.gif)

## ✨ Features
- ✅ Feature 1
- ✅ Feature 2
- ✅ Bonus Feature

## 📦 Tech Stack
**Backend:** Django / Flask / FastAPI  
**Frontend:** React / Bootstrap / HTML  
**Database:** PostgreSQL / SQLite / Firebase

## 🚀 Getting Started
```bash
git clone https://github.com/yourname/project.git
cd project
pip install -r requirements.txt
python manage.py runserver
