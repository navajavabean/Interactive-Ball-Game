### README: Interactive Ball Game

---

#### **Overview**
This is a JavaFX-based interactive ball game where players aim to click on a moving ball. Each successful click:
- **Increases the score.**
- **Speeds up the ball.**
- **Reduces the ball's size.**

The game ends after 5 missed clicks, displaying a "Game Over" message.

---

#### **Features**
1. **Interactive Gameplay:**
   - Players click the moving ball to score.
   - The ball moves faster and shrinks with each successful click.
   
2. **Game Over Mechanism:**
   - The game stops after 5 missed clicks.
   - Displays "Game Over" text when the game ends.

3. **Pause and Reset Buttons:**
   - **Pause Button:** Toggles between pausing and resuming the game.
   - **Reset Button:** Resets the game variables and UI, allowing a fresh start.

4. **Dynamic Animations:**
   - Ball movement and velocity update in real time.
   - Circle dynamically shrinks and changes position after each click.

5. **Statistics Display:**
   - Tracks and displays the player's hits and misses.

---

#### **Controls**
- **Click the ball:** Increases your score and speeds up the game.
- **Pause Button:** Pauses or resumes the game.
- **Reset Button:** Resets the game state, including score, misses, ball size, and velocity.

---

#### **Game Rules**
1. Successfully click the ball to score and avoid missing it.
2. If you miss clicking the ball 5 times, the game ends.
3. Each successful click makes the ball smaller and faster.

---

#### **How to Run the Game**
1. Install **Java Development Kit (JDK)** and ensure **JavaFX** libraries are configured.
2. Clone or download the source code from the repository.
3. Compile and run the program in your IDE (e.g., IntelliJ, Eclipse, or NetBeans) or using a terminal:
   ```bash
   javac Animation.java
   java Animation
   ```
4. Enjoy the game!

---

#### **Code Highlights**
1. **Ball Movement and Animation:**
   - Implemented using `AnimationTimer` to update the ball's position in real time.
   
2. **Collision Detection:**
   - Uses the `contains()` method to detect if the mouse click intersects the ball.

3. **Dynamic Difficulty:**
   - Ball speed and size dynamically adjust based on the player's performance.

4. **UI Design:**
   - Buttons (`Pause`, `Reset`) and real-time text updates (`Hits`, `Misses`) enhance gameplay interactivity.
   - Layout created using `BorderPane`, `Pane`, and `HBox`.

---

#### **Technologies Used**
- **Programming Language:** Java
- **Framework:** JavaFX
- **Animation:** `AnimationTimer`
- **Event Handling:** Mouse and Button click events

---

#### **Future Improvements**
- Add multiple difficulty levels (easy, medium, hard).
- Introduce sound effects for clicks and game over.
- Track and display the highest score across sessions.
- Add a start menu or a replay button after "Game Over."

---

Enjoy playing the Interactive Ball Game! Feedback and suggestions are always welcome. 😊
