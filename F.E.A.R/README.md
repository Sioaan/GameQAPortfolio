# F.E.A.R. — Game QA Portfolio Project

**Personal Manual QA portfolio project based on _F.E.A.R. (2005)_ by Monolith Productions.**
The project demonstrates practical game QA skills through test planning, test case design, checklist-based testing, defect reporting, performance and compatibility testing, regression planning, and final test reporting.


## Tester

**Tester:** Sioaan  
**Test period:** September 18, 2026  
**Project type:** Personal / educational QA portfolio project

##  Project Overview

This project was created to simulate a real QA workflow for a PC game and to demonstrate how a Junior Game QA tester approaches a structured testing task.
The testing covers the main gameplay systems, technical areas, user interface, input, audio, graphics, save/load functionality, performance, compatibility, and stability.
The project is based on the **stock PC version of F.E.A.R. 1.08** used as the defined test baseline.



## Test Environment

| Parameter | Configuration |
|---|---|
| Game | F.E.A.R. — First Encounter Assault Recon |
| Developer | Monolith Productions |
| Game Version | 1.08 |
| Distribution | GOG |
| Platform | PC |
| Operating System | Windows 11 |
| CPU | i5-14400F |
| GPU |  Nvidia RTX 3060 12 GB |
| RAM | 16 GB |
| Storage | 2 TB |
| Display | 60 Hz |
| Audio Device | High Definition Audio Device |
| Input | Keyboard / Mouse |

## Testing Scope

The project covers the following areas:

- Gameplay and player movement
- Combat and damage handling
- Weapons and ammunition
- Weapon switching, reload and recoil
- Slow-motion mechanic
- Health and armor
- Enemy AI
- Physics and collision
- Ragdoll behavior
- Object interactions
- Doors and gameplay interactions
- Scripted events and horror sequences
- UI and HUD
- Controls and input
- Save / Load and checkpoints
- Audio
- Graphics
- Performance
- Compatibility
- Stability
- Regression coverage

## Out of Scope

- Multiplayer functionality
- Features not available in the selected PC build
- Modded builds mixed with the stock-game test baseline



## Testing Approach

The project uses a combination of:

- Smoke testing
- Functional testing
- Exploratory testing
- Regression testing
- Compatibility testing
- Performance testing
- Stability testing
- UI testing
- Audio and visual testing
- Save / Load testing
- Boundary and edge-case testing

## Repository Structure

```
1-Test-Plan/
    TestPlan.docx
    TestPlan.pdf

2-Test-Cases/
    Test-Cases.xlsx
    
3-Checklists/
    ai.xlsx
    Audio.xlsx
    compatibility.xlsx
    gameplay.xlsx
    graphics.xlsx
    saveload.xlsx

4-Bug-Reports/
    BugReports.xlsx

5-Performance/
    Performance-Report.xlsx

6-Compatibility/
    Compatibility-Report.xlsx

7-Regression/
    Regression-Report.xlsx

8-Final-Report/
    Final-QA-Report.xlsx
    
```


##  Defects Found

The current test run identified two unique defects.

| Bug ID | Area | Title | Severity | Priority | Status |
| BUG-UI-001 | UI / Input | Custom control settings reset after opening Options | Major | High | Open |
| BUG-PERF-001 | Performance | Game unexpectedly locks FPS to 30 | Major | High | Open |

### BUG-UI-001 — Control Settings Reset

Custom control settings can be reset after opening the Options menu. The issue affects persistence of user-defined controls and is covered by the related UI and input test cases.

### BUG-PERF-001 — 30 FPS Lock

The game can become unexpectedly limited to 30 FPS even when a higher frame-rate configuration is expected. The issue was recorded as a performance defect and linked to the relevant performance test coverage.

---

##  Test Run Summary

The current documented test run contains **92 test cases**.

| Result | Count |
|---|---:|
| Passed | 88 |
| Failed | 4 |
| Total | 92 |

The four failed test cases include coverage of two unique defects. Some failed cases are linked to the same underlying issue and are therefore not counted as separate bugs.
The test run also records controller support as a compatibility limitation rather than treating unsupported controller input as a separate product defect.

##  Performance Testing

Performance testing focuses on representative gameplay situations rather than synthetic benchmark-only scenarios.
Covered areas include:
- Idle / low-load gameplay
- Combat with multiple Replica soldiers
- Explosions
- Heavy visual effects
- FPS limit behavior
- Higher-FPS configuration behavior

The performance test results are documented separately so that observed behavior and reported defects can be distinguished from general gameplay testing.

##  Compatibility Testing

Compatibility coverage includes:

- Windows launch and gameplay startup
- Display resolution
- Fullscreen mode
- Windowed mode
- Alt+Tab recovery
- Audio output
- Controller compatibility

The controller check is documented as a compatibility limitation because the game does not support the tested gamepad input.

##  Regression Testing

Regression coverage is included to demonstrate how fixed defects would be retested and how affected areas would be checked for side effects.
Regression results are kept separate from the original defect report so that a defect is only marked as fixed after a new build or verified change has actually been tested.

## Main QA Artifacts

The repository contains the following main deliverables:

### Test Plan
Defines the test scope, objectives, environment, test types, entry criteria, exit criteria, and test data.

### Test Cases
Detailed functional and technical test coverage across gameplay, AI, weapons, physics, UI, save/load, input, audio, graphics, performance, and compatibility.

### Checklists
Compact verification lists for faster functional and regression-style passes.

### Bug Reports
Structured defect reports linked to failed test cases and reproducible issues.

### Performance Report
Performance-specific test results and observations.

### Compatibility Report
Compatibility coverage for the selected Windows and hardware environment.

### Regression Report
Regression coverage linked to the defect workflow.

### Final QA Report
A consolidated summary of the test scope, execution results, defects, and overall test outcome.

---

## What This Project Demonstrates

This portfolio project demonstrates practical knowledge of:

- Writing clear and reproducible test cases
- Designing test scenarios around gameplay mechanics
- Building and using QA checklists
- Distinguishing expected and actual results
- Reporting defects with severity and priority
- Linking defects back to failed test cases
- Testing game-specific mechanics instead of only generic software behavior
- Performing performance and compatibility checks
- Organizing regression coverage
- Producing a structured QA final report

## 📌 Project Notes

This is an **independent educational portfolio project** and is not an official QA report from Monolith Productions, Warner Bros. Games, or any other rights holder.

The purpose of the project is to demonstrate a practical manual QA workflow using a real PC game as the test subject.

---

##  References

- [F.E.A.R. — GOG](https://www.gog.com/en/game/fear_platinum)
- [F.E.A.R. — PCGamingWiki](https://www.pcgamingwiki.com/wiki/F.E.A.R)

## Project Status

**Current status: Completed test run / portfolio documentation.**

The repository contains the planning, execution, defect, performance, compatibility, regression, and final reporting artifacts for the defined F.E.A.R. 1.08 test baseline.
