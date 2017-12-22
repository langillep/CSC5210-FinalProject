# CSC5210-FinalProject

---
First-person cliff diving game.

User will be able to run and jump and perform flips. If the user lands in the water incorrectly an
ambient light will make the screen glow red. The scene will include point lights that glow red when the user is unable to jump and green when it is okay to jump.

---

Project source code can be downloaded from https://github.com/langillep/CSC5210-FinalPoject.git

---

Author and Contributor List
---

John Wyeth

Thomas Kelley

Pat Langille

---

Terrain:
---
 - textured
 - large
 - water (collision detection)
 - tesselation/geometry shader for cliff and water
 ---
 
 First-Person View:
 ---
 
 - 'F' rotates the camera to simulate a flip
 - 'R' rotates the camera to simulate a backflip
 - camera is translated based on simulated gravity
 
 
 Lighting and Shaders:
 ---
 
 - scene should be lit using ambient light (turns red as a result of a bad dive)
 - scene should be lit using directional light from above the scene(like the sun)/will be toggled on and off using 'T' (maybe)
 - scene should have two point lights at the top of the cliff which are red prior to the jump and green when the user can jump
 
 
 How to Use
 ---
 
 1. 'J' initiates the run leading to the jump and the two lights at the top of the cliff will turn from red to green
 2. 'Space' allows the user to jump from the cliff
 3. 'F' allows the user to perform a front-flip
 4. 'R' allows the user to perform a back-flip
 5. user is then be prompted if they'd like to jump again
 ---
 
 To Be Done
 ---

 - geometry shader for the cliff
 - point lighting

---

