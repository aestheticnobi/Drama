#  A Legacy of Ashes

Welcome to an interactive psychological drama where your decisions determine whether you escape with your fortune, your family, or just your life.

##  About The Project
'A Legacy of Ashes' is a text-based Choose Your Own Adventure game set inside a burning, debt-ridden family mansion. Every choice you make alters the course of the story, leading to different paths, obstacles, and distinct endings. 

* **Genre:** Text-based interactive fiction / Choice-driven narrative
* **Tech Stack:** HTML5 (leveraging semantic tags like `<blockquote>` and `<em>` for immersive storytelling)
* **Features:** Multiple branching paths, distinct endings, and high replayability.

---

##  The 3 Rules of the Game
1. **Click to Decide:** Read the narrative text, then click on the linked text options at the bottom to make your move and turn the page.
2. **Accept Your Fate:** There's no 'undo' button mid-game. Once you click a choice, you must face the consequences of the path until you reach the ending.
3. **Explore All Paths:** Reaching one ending isn't the end of the project. Use 'Rewind Time' to restart from the beginning and discover how different choices completely change your destiny.

---

##  Story Flow & Map
```text
index.html (Home Page / Rules)
 └── scene1.html (The Fire Breaks Out)
      ├── choice A -> hallway.html (The Hallway Choice)
      │    ├── choice 1 -> safe_room.html (Ending: The Fortune's Price)
      │    └── choice 2 -> exit_door.html (Ending: Bare Survival)
      │
      └── choice B -> west_wing.html (Saving the Sibling)
           ├── choice 1 -> balcony.html (Ending: The Hero's Sacrifice)
           └── choice 2 -> trapped.html (Ending: A Legacy of Ashes)
