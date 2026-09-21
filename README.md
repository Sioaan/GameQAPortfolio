<div align="center">

🎮 Game QA Portfolio
Manual QA • Game Testing • Bug Hunting • Quality Mindset

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=36BCF7&center=true&vCenter=true&width=760&lines=I+play+games.+I+test+games.+I+break+games.;Turning+curiosity+into+structured+QA.;Exploring+gameplay%2C+systems%2C+performance+%26+bugs.;Building+my+Game+QA+journey+one+project+at+a+time." alt="Typing SVG" />

<br>







</div>

👋 About Me

I'm building my path into Game QA / Manual QA through practical testing projects.

Gaming has always been more than just entertainment for me. I enjoy discovering how games work, exploring their systems, noticing small details, and asking questions such as:

What happens if I do this?

What happens if I do it twice?

What if I do it at the wrong time?

What happens when two systems interact?

That curiosity is one of the main reasons why Game QA became a passion for me.

I don't just want to play a game.

I want to understand it, challenge it, break it, reproduce problems, document them clearly, and help make the experience better for the player.

🧪 What Is Game QA?

Game QA is much more than checking whether a game launches.

A QA tester investigates how different systems behave individually and together, looks for unexpected behavior, verifies fixes, and documents results in a way that developers can understand and reproduce.

A typical workflow looks like this:

        PLAN
          ↓
     DESIGN TESTS
          ↓
    EXECUTE TESTS
          ↓
   OBSERVE RESULTS
          ↓
   FIND / REPORT BUGS
          ↓
      RETEST FIXES
          ↓
      REGRESSION
          ↓
    FINAL REPORT

The goal is not simply to find bugs.

The goal is to provide useful information about product quality.

🎯 What I Test
🎮 Gameplay
Movement
Combat
Interactions
Progression
Objectives
Checkpoints
Game mechanics
Player feedback
Difficulty behavior
Scripted events
🔫 Game Systems
Weapons
Ammunition
Health
Armor
Inventory
Save / Load
AI behavior
Physics
Collision
Interactions
🖥️ Technical Areas
Performance
FPS stability
Frame drops
Loading
Crashes
Freezes
Input
Compatibility
Display modes
Audio devices
🎨 Presentation
UI / HUD
Menus
Graphics
Lighting
Shadows
Particles
Visual effects
Audio
Dialogue
Subtitles
🔬 Types of Testing
🚀 Smoke Testing

Question: Does the build work well enough to begin deeper testing?

Typical checks:

Launch
  ↓
Main Menu
  ↓
Start Game
  ↓
Basic Controls
  ↓
Basic Gameplay
  ↓
Save / Load
  ↓
Exit

Smoke testing is usually quick and focuses on critical functionality.

✅ Functional Testing

Question: Does a feature behave according to its requirements?

Example:

Action:
Reload weapon

Expected:
Magazine reloads and the weapon can fire again.

Actual:
Observed result is recorded after execution.

Result:
PASS / FAIL

Functional testing focuses on whether individual features work correctly.

🔍 Exploratory Testing

Question: What happens when I explore the system beyond predefined test cases?

Instead of following only a fixed script, the tester investigates.

For example:

Change setting
      ↓
Open another menu
      ↓
Return to gameplay
      ↓
Change weapon
      ↓
Save
      ↓
Load
      ↓
Check whether the original setting survived

Exploratory testing is especially useful for discovering unexpected interactions between systems.

🔄 Regression Testing

Question: Did a fix solve the problem without introducing another one?

Typical flow:

Bug Found
   ↓
Bug Fixed
   ↓
Retest Original Issue
   ↓
Run Related Tests
   ↓
Check For Side Effects

Regression testing is essential because fixing one system can sometimes affect another.

⚙️ Performance Testing

Question: Does the game remain responsive under different workloads?

Examples:

Idle scenes
Combat
Multiple enemies
Explosions
Heavy particle effects
Large environments
Loading
High FPS scenarios
Long play sessions

Measurements can include:

FPS
Frame-time
Loading time
Stutter
Freezes
Crashes
Responsiveness
💻 Compatibility Testing

Question: Does the game behave correctly across different environments?

Examples:

Operating systems
Resolutions
Aspect ratios
Fullscreen / Windowed
Audio devices
Input devices
Alt+Tab
Hardware configurations

Compatibility testing helps identify issues that may not appear on the primary test environment.

🖥️ UI Testing

Question: Is the interface functional, readable and consistent?

Examples:

Menus
Buttons
HUD
Health / ammo indicators
Settings
Key bindings
Subtitles
Navigation
Visual states

The tester checks not only whether the UI exists, but whether it behaves correctly.

🔊 Audio Testing

Question: Does sound behave correctly in context?

Examples:

Weapon sounds
Footsteps
Dialogue
Radio
Ambient sounds
Effects
Volume settings
Mute behavior
Missing or overlapping audio

Audio issues can strongly affect immersion, so they are part of the overall testing process.

🎨 Graphics Testing

Question: Are visual elements rendered correctly?

Examples:

Resolution
Aspect ratio
Fullscreen
Windowed mode
Lighting
Shadows
Particles
Visual effects
Texture issues
Flickering
Rendering artifacts
🐞 Bug Reporting

Finding a bug is only the beginning.

A useful bug report should allow another person to understand and reproduce the issue without needing a long explanation.

A typical report contains:

Field	Purpose
Bug ID	Unique identifier
Title	Short description
Environment	Where the issue was found
Preconditions	Required setup
Steps to Reproduce	Exact reproduction path
Expected Result	What should happen
Actual Result	What actually happened
Severity	Impact of the defect
Priority	How urgently it should be addressed
Reproducibility	How consistently it can be reproduced
Status	Current state of the issue

The objective is simple:

Clear enough to reproduce. Clear enough to understand.

📋 Test Cases & Checklists

I use both detailed Test Cases and lightweight Checklists.

Test Case

Used when a feature needs a structured verification flow.

Preconditions
      ↓
Steps
      ↓
Expected Result
      ↓
Actual Result
      ↓
Status
Checklist

Used when a faster verification pass is more practical.

☐ Launch
☐ Movement
☐ Combat
☐ Audio
☐ Save / Load
☐ UI
☐ Exit

Test Cases provide detail.

Checklists provide speed and coverage.

🧠 Edge Cases

One of the parts of QA I enjoy most is thinking about things a normal player might do accidentally or unexpectedly.

Examples:

Save during combat
Load during a scripted sequence
Switch weapons during reload
Pause at an unusual moment
Alt+Tab during gameplay
Alt+Tab during loading
Change settings repeatedly
Perform the same action many times
Interact from maximum distance
Save immediately before death

These scenarios can reveal issues that normal testing may miss.

📊 Severity vs Priority

A useful QA distinction:

Severity

How much does the bug affect the product?

Critical
High
Major
Minor
Trivial
Priority

How urgently should the issue be addressed?

High
Medium
Low

A bug can have high severity but different priority depending on the context and release goals.

🗂️ Portfolio Structure
Game-QA-Portfolio/
│
├── 01-Test-Plan/
│
├── 02-Test-Cases/
│
├── 03-Checklists/
│
├── 04-Bug-Reports/
│
├── 05-Performance/
│
├── 06-Compatibility/
│
├── 07-Regression/
│
├── 08-Evidence/
│
├── 09-Final-Report/
│
└── README.md

Each game or testing project can follow the same general QA structure while keeping its own documentation.

🛠️ Tools

I'm building my workflow around practical QA documentation and lightweight tools.

Tool / Format	Purpose
Excel / Spreadsheet	Test Cases, Checklists, Bug Tracking, Reports
Markdown	Documentation, Bug Reports, Project Notes
GitHub	Portfolio, Version Control, Documentation
Windows	PC Game Testing
Screenshots / Recordings	Supporting test results where needed

The tools may change over time, but the core QA process stays the same:

Observe → Reproduce → Document → Verify

❤️ Why Game QA?

Because I genuinely enjoy games.

I can spend hours playing a game and wondering how its systems work behind the scenes.

Why does an enemy react this way?

Why did that animation break?

Why did the UI reset?

Why does the game stutter only in one situation?

Why does the bug appear after a specific sequence of actions?

Those questions are exactly what make testing interesting to me.

For me, Game QA combines two things I enjoy:

🎮 Games

and

🔎 Problem solving

That combination is what motivates me to keep learning and improving.

🚀 Growing This Portfolio

This repository is continuously evolving.

I plan to expand it over time with:

🎮 More games
      ↓
🧪 More test cases
      ↓
🔍 More exploratory testing
      ↓
🐞 More real-world bug reports
      ↓
⚙️ More performance testing
      ↓
💻 More compatibility testing
      ↓
🔄 More regression scenarios
      ↓
📊 Better reports

New projects will be added gradually as I test different games, genres and technical environments.

The goal is not simply to make the repository bigger.

The goal is to make it better.

Every new project is an opportunity to improve:

Test design
Coverage
Bug analysis
Documentation
Exploratory thinking
Technical understanding
QA methodology
🌱 My QA Journey

This repository is also a record of my progress.

I want to be able to look back over time and see how my testing skills develop from project to project.

Learning
   ↓
Practicing
   ↓
Testing
   ↓
Finding Problems
   ↓
Understanding Why
   ↓
Improving
   ↓
Repeating

There is always something new to learn in QA.

And there is always another bug waiting to be found.

<div align="center">

🎮 Test. Break. Investigate. Improve.
Building my Game QA portfolio — one game at a time.

<br>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:36BCF7,100:8A2BE2&height=120&section=footer" width="100%" />

</div>
