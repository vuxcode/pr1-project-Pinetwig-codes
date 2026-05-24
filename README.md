[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/F4JWjZ9e)
# Project Instructions
Follow the instructions here: https://vuxcode.netlify.app/new/pr1/lessons/major-project-brief/

REMEMBER TO "COMMIT" YOUR CHANGES REGULARLY TO SHOW HOW YOU HAVE BUILT THIS PROJECT! 

The final program is not the goal! The aim of the project is to show how you have developed your program, the steps you have taken and the problems you have solved!

# Project Notes

- As this game currently stands I want to work on a couple of things
    - *Abstracting a lot of the repetetive code*
    - *Clean up the unused code*
    - *Learn more about objects as they could easily make coding easier and more compact*


# Project Summary

## Project Description

This project is a HTML based RPG-like game experience inspired by Disco Elysium, Betrayal at the House on the Hill and DnD among others.

Player creates a simple character with different stat-values that are then tested through checks during gameplay.
Stats include Strength, Motorics, Intuition and Health.

The overall goal with the program was to learn JavaScript by experimenting with "game engine" like structure which align with my personal interests.

---

## Reflections

This project quickly became humbled in size due to *some* poor time management and unfortunate timing with other obligations. (work, travel, other courses, *other things*)

Some of the biggest struggles include:
- The difficulty of creating the character creator.
    - This took a lot more time than I ever could have ever forseen.
- Figuring out HTML-element-manipulation. (DOM)
- Making the game visually understandable with minimal HTML and CSS knowledge.
- Functions and parameter passing. General function structure with multiple functions are interacting.
- Keeping functions and other elements "modular". Reusable.
- Debugging intertwined code. 

All that being said, I feel genuinely proud of what I have created and feel inspired to continue working with this and similar projects.

---

## What Could Be Improved

A lot of things frankly.

The biggest areas I am going to focus on right now include:

- Abstracting repeated code into reusable functions.
- Improving transition systems. Making it easier to add more content.
- Rework text variables using arrays
- Cleaning up HTML elements and overall making it look nicer using CSS.
- Adding inventory system.
- Adding interactive event history.
- Removing unused and experimental code.

- This project is begging me to make use of objects.

Long term I also would like to work on:

- Writing quality
- Making player interactions meaningful.
- Gameplay balancing and difficulty.
- Making it fun.

---

## Budget / Time Reflection

This project was ambitious relative to my current capabilities and the time restriction.
With that said, I have learned a lot more than I could have ever expected to.

I wish I would have been better about tracking my time spent on the project.
It quickly got complicated when factoring in:
- Multitasking during work on the project.
- My hypersomnia causing me to take unexpected naps during the process.
- Work done during travels.
- Work done outside of the main program file.

One thing I could have done better would have been to scale the character creator down so that I could have spent more time on working on the game's systems more.

I definitely hit the required time spent on the project. And hope my work reflects this. 

---

# User Guide

## Starting the Game

1. Open the project in a web browser.
2. The game begins at the **Character Creation** screen.
3. Choose one of two options:
   - **Roll Dice** — randomly generate stat values.
   - **Allocate** — manually distribute stat points.

---

## Creating Your Character

### Roll Dice Mode

- Press the **Roll Dice** button.
- Three random dice values will appear.
- Select a value using the radio buttons.
- Click on a stat to assign the selected value:
  - Strength
  - Motorics
  - Intuition
- Each value can only be used once.
- Press **Continue** when finished.

### Allocate Mode

- Press the **Allocate** button.
- Spend points using the `+` and `-` buttons.
- Assign points to:
  - Strength
  - Motorics
  - Intuition
- Press **Continue** when finished.

---

## Stats Explained

**Strength**  Represents physical power and endurance.
**Motorics**  Represents dexterity, coordination, and precision.
**Intuition**  Represents awareness, perception, and problem solving.
**Health**  Players current health points.

---

## Gameplay

- The game is a text-based RPG.
- Text and story progression is displayed in the middle.
- Stats and health are displayed in the top left corner.
- Progress through story text using the **Continue** buttons.
- Certain events trigger **Skill Checks**.

During a skill check:

1. Choose a stat.
2. A dice roll is performed.
3. Your stat is added to the roll total.
4. If the total beats the difficulty value, you succeed.

Example:

Success!
Strength + 12 = 25
You had to beat: 20

Failing skillchecks may:

- Deal damage to player character.
- Disable chosen stat option when check is reattempted.
- Ultimately cause death and fail-state of the game.

Currently the game lacks:

- Text content.
- A proper goal and victory screen.
- A proper failstate.