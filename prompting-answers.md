## Unit 14: Intro to JavaScript
### Working with Variables & Comments

---

### Before You Start Prompting Today

- Copy/paste this markdown (`.md`) file into a **NEW** markdown file in your `js-intro` repo named: `js-variables-notes.md`
- Copy/paste the prompts below into Gemini
  - Take a few minutes to read and understand Gemini's response
  - If Gemini's response is unclear or you don't quite understand parts of Gemini's response, ask Gemini for more examples or to explain in simpler terms the parts of the response you still don't understand
  - **The idea is to have a back-and-forth conversation with Gemini.**
  - Think of Gemini as your personal tutor -- it is by asking questions and asking for examples that you learn from your tutor.
- Once you have a solid answer to your prompt, copy/paste the answer into your `js-variables-notes.md` markdown file.
- Click the 'Commit changes' button to save your work!

### Submitting Your Answers

- Copy/paste the web address of your `js-variables-notes.md` markdown file.
- Email the link to your teacher (set email subject line to: **JS Variables Notes**)

---

Welcome to the developer's shop! 

Understanding variables and comments is like learning how to label the product bins and write the instruction manual for a massive warehouse. 

If you don't get the labels right, the whole system falls apart when the next shift shows up to work.

### 🚀 Phase 1: Why This Matters in Your Career

In the industry, we don't just write code for computers; we write it for **humans**.

* **Variables (`let` vs `const`):** Think of variables as storage containers. Some are cardboard boxes you can swap items in and out of, and some are steel safes that stay locked once you put something inside.
  * Using the wrong one can lead to bugs that crash an app.
* **The Assignment Operator (`=`):** In math, this means "is equal to." In programming, it’s a **directional arrow**. It means "take this value and attach it or link it to this label."
* **Comments:** These are "Post-It Notes." or sticky notes for your code. Senior developers spend more time reading code than writing it. If you don't add brief, clear comments to your code, you're making the job harder for your teammates.

---

### 🧠 Phase 2: The Logic (Think & Record)

Before we touch the keyboard, I want to see your blueprint. Imagine you are building a profile for a high-end gaming account.

**In plain English (no code yet!), tell me:**

1. Which piece of data about a player would stay the same forever (requiring a "safe"), and which might change as the player plays (requiring a "box")?

*Account / User ID would require a "safe" because it would never change, while current health would require a "box" because it fluctuates.*

3. If you had to explain the `=` symbol to a non-coder using the analogy of a "bucket" and a "ball," how would you describe it?

*Gemini said
To explain the = symbol (the assignment operator) to a non-coder, you have to flip their mathematical brain upside down. In math, = means "these two things are currently the same." In coding, = is an action.

Using the bucket and ball analogy, here is how it works:

1. The Bucket is the Variable
Think of a bucket with a label on the side, like "PlayerScore" or "Username." This bucket is your variable. It’s a container designed to hold exactly one thing at a time.

2. The Ball is the Data
The ball represents the value or the piece of data you want to store (like the number 10 or the name "Alex").

3. The = is the Act of Dropping the Ball
In coding, the = symbol is the hand that picks up a ball and drops it into the bucket.

PlayerScore = 10

When a coder writes the line above, they aren't making a statement of fact; they are giving a command: "Take the ball labeled '10' and put it inside the bucket labeled 'PlayerScore'."

The Rules of the Bucket
To really understand how = works, there are two "physical" rules in this analogy:

The Old Ball Vanishes: If there was already a ball in the bucket (say, a 5), and you use the = to drop in a 10, the 5 instantly disappears. The bucket can only hold one ball at a time.

Right to Left: The action always moves from the right side to the left side. You look at the ball on the right, and move it into the bucket on the left.

Why this matters
If you tell a non-coder x = x + 1, their math teacher would scream because that's an impossible equation. But in "Bucket Logic," it makes perfect sense:

Look at the ball currently in the bucket (x).

Add 1 to it to create a new ball.

Use the = to drop that new ball back into the bucket, replacing the old one.

---

### 💡 Phase 3: A Quick Hint

As you start your script, remember that JavaScript treats text and numbers differently.

* **String:** A string is text that is enclosed in quotes (like a dialogue bubble in a comic).
* **Numbers:** Just the digits (like a score on a scoreboard).

Here is a simple example of how a professional programmer marks their "territory" with a comment:

```javascript
// This is a single-line comment: Setting the player's starting level
let playerLevel = 1; 

```

PROMPT: Now ask Gemini to give you three examples of JavaScript string variables that are declared (created) using the keyword `const`.  Tell Gemini to write the variable names in camel case.  Write the answer Gemini gives you below.

```javascript
// Write the example code Gemini gives you inside this code block
const playerUserName = "DragonSlayer99";
const favoriteGameGenre = "Platformer";
const currentLevelName = "Mystic Forest";

```

**Your Turn:**
To start your **Final Task**, how would you write a **single-line comment** at the very top of your JavaScript script to identify yourself as the lead developer on this project?

Add your answer to the JavaScript code block below.


```javascript
// Write your answer below this JavaScript comment
// Lead developer: Charles Petoskey

```

---

