# Test Case Report – PLAYTESTER by LilyDynamite

**Tested On:** Mozilla Firefox  
**Tester:** Ozan Çınar  
**Date:** 14/06/2025
**Platform:** Browser (HTML5)

---

## Summary

The game loaded successfully and all major mechanics functioned as intended across three different mini-games. No bugs, crashes, or broken transitions were observed.

---

## Test Cases

| Test ID | Description                                                      | Steps to Reproduce                                       | Expected Result                                          | Actual Result         | Status |
|---------|------------------------------------------------------------------|----------------------------------------------------------|----------------------------------------------------------|------------------------|--------|
| TC01    | Game loads in Firefox                                            | Open game URL in Firefox                                 | Game loads without errors                                | Loaded successfully    | ✅ Pass |
| TC02    | Movement in Minigame 1                                           | Use arrow keys to move                                   | Character responds to movement keys                      | Works as intended      | ✅ Pass |
| TC03    | Action in Minigame 1                                            | Press Space bar during interaction moments               | Space triggers appropriate action                        | Works correctly        | ✅ Pass |
| TC04    | Movement in Minigame 2                                           | Use arrow keys to move                                   | Movement functions as expected                           | Works as intended      | ✅ Pass |
| TC05    | Shooting in Minigame 3                                           | Press Left Mouse Button to shoot                         | Player shoots / action triggers                          | Works as intended      | ✅ Pass |
| TC06    | Transition after finishing 3 minigames (end of "day")            | Complete 3 minigames and press "Clock Out"               | End-of-day transition loads new scene                    | Loads properly         | ✅ Pass |
| TC07    | Transitions between minigames                                    | Wait for or trigger transition between minigames         | Next minigame loads without delay or issue               | Transitions correctly  | ✅ Pass |

---

## Notes

- All input types (keyboard and mouse) responded accurately.
- Transitions between scenes and days (after pressing "Clock Out") were smooth and consistent.
- No graphical glitches or performance issues observed.
