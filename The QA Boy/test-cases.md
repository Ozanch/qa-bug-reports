# Test Case Report – The QA Boy by Roquen_Pale

**Tested On:** Windows 11  
**Platform:** Unity Engine (Standalone Build)  
**Tester:** Ozan Çınar  
**Date:** 18.06.2025

---

## Test Cases

| Test ID | Description                              | Steps to Reproduce                          | Expected Result                               | Actual Result                                | Status |
|---------|------------------------------------------|---------------------------------------------|------------------------------------------------|----------------------------------------------|--------|
| TC01    | Game launches successfully                | Open game on Windows 11                     | Game launches and reaches title/start screen  | Launches without error                       | ✅ Pass |
| TC02    | Player movement with WASD                 | Press W, A, S, D keys                       | Player moves in the intended directions       | Movement responds correctly, but feels floaty | ⚠️ Pass with UX concern |
| TC03    | Player can jump using Space               | Press Space key                             | Character jumps from ground                   | Jumping works as expected                    | ✅ Pass |
| TC04    | Player can interact with environment      | Press "E" key near interactable objects     | Object responds to interaction                | Most work, but one statue doesn’t respond    | ❌ Partial Fail |
| TC05    | Collision boundaries                      | Attempt to move outside map or through objects | Player is blocked by invisible walls       | Found area where player can exit map & clip  | ❌ Fail |

---

## Notes

- Interaction failure occurred with one of the in-game statues (no prompt or response).  
- There is a specific location where the player can jump out of bounds and walk through buildings due to missing collision.
