# 🛠️ Phase 2: Classical Mechanics

## 🔹 Topic 1: Motion (Kinematics)

**Kinematics** = describing motion without worrying about *why* it happens.

---

### 📐 What is a Vector?

A **vector** is a measurement with two pieces of information:
1. **Size** (how much)
2. **Direction** (which way)

**Examples:**
- "5 meters" → **Scalar** (just a number, no direction)
- "5 meters north" → **Vector** (size + direction)

A **scalar** is just a number with no direction (like temperature, mass, or speed).

---

### 📏 Distance vs. Displacement

#### Distance:
- Total path traveled
- Always positive
- **Scalar** (no direction)

#### Displacement:
- Straight-line distance from start to finish
- Has direction
- Can be zero even if you moved
- **Vector** (size + direction)

**Example:**
- You walk 3 m east, then 3 m west back to your starting point.
- **Distance** = 6 m (total path)
- **Displacement** = 0 m (you ended where you started)

---

### 🏃 Speed vs. Velocity vs. Acceleration

| Term           | What it measures                     | Has direction? | Type   |
|----------------|--------------------------------------|----------------|--------|
| **Speed**      | How fast                             | No             | Scalar |
| **Velocity**   | How fast + direction                 | Yes            | Vector |
| **Acceleration** | How quickly velocity is changing   | Yes            | Vector |

---

#### Speed
- How fast you're moving (no direction)
- Example: "The car is going 60 km/h"

#### Velocity
- How fast + which direction
- Example: "The car is going 60 km/h north"
- Formula (for context): \( v = \frac{\text{displacement}}{\text{time}} \)

#### Acceleration
- **How quickly velocity is changing**
- Happens when you:
  1. Speed up
  2. Slow down
  3. Change direction (even at constant speed!)
- Formula (for context): \( a = \frac{\Delta v}{\Delta t} \) (change in velocity over time)

**Key insight:** Acceleration = any change in velocity

---

### 🚗 Examples:

**Speeding up:**
- Car goes from 20 km/h to 40 km/h → velocity increased → acceleration

**Slowing down:**
- Car goes from 60 km/h to 30 km/h → velocity decreased → acceleration (negative)

**Turning at constant speed:**
- Car drives 50 km/h around a curve
- Speed stays the same, but **direction changes**
- Velocity changed → acceleration!

**Constant velocity:**
- Car moves at 100 km/h north in a straight line
- No change in speed or direction
- **Acceleration = 0**

---

### 🌍 Reference Frames

Motion is **relative** — it depends on the observer.

**Example:**
- You're on a train moving at 100 km/h
- To someone on the ground: you're moving at 100 km/h
- To someone else on the train: you're standing still (velocity = 0)

**Both are correct** — motion only makes sense relative to a chosen reference frame.

---

### 🎯 Key Takeaways:

1. **Vectors** have size and direction; **scalars** have only size
2. **Displacement** cares about start/end position; **distance** cares about total path
3. **Velocity** = speed + direction
4. **Acceleration** = how fast velocity changes (can be from speeding up, slowing down, or changing direction)
5. If velocity is constant (same speed, same direction) → **acceleration = 0**
6. Motion is relative to your reference frame

---
# 🔹 Topic 2: Newton's Laws of Motion

Newton's three laws explain **why** objects move (or don't move) the way they do.

---

## ⚖️ Newton's First Law: The Law of Inertia

### The Law:
**"An object at rest stays at rest, and an object in motion stays in motion at constant velocity, unless acted upon by an external force."**

### Key Concepts:

#### Inertia
- An object's resistance to changes in motion
- **Mass is the measure of inertia**
- More mass = more inertia = harder to start moving, stop, or change direction
- Less mass = less inertia = easier to accelerate

### What This Means:
- Objects naturally resist changes to their motion
- **Forces don't keep things moving — forces CHANGE motion**
- Without friction, a moving object would continue forever at constant velocity
- At rest or constant velocity → net force must be zero

---

### 🚗 Examples:

**Car braking:**
- Your body lurches forward when car stops suddenly
- Your body has inertia — it wants to keep moving forward
- Seatbelt applies force to change your motion

**Hockey puck on ice:**
- Puck glides for a long time before stopping
- Wants to keep moving (inertia), but friction gradually stops it
- In space (no friction), it would glide forever

**Space:**
- Objects keep moving at constant velocity forever
- No force needed to maintain motion — only to change it

---

## ⚡ Newton's Second Law: F = ma

### The Law:
**"The acceleration of an object is directly proportional to the net force acting on it, and inversely proportional to its mass."**

### Formula:
\[ F = ma \]

or rearranged:
\[
a = \frac{F}{m}
\]

Where:
- **F** = Net Force (newtons, N)
- **m** = Mass (kilograms, kg)
- **a** = Acceleration (m/s²)

**1 Newton (N)** = the force needed to accelerate 1 kg at 1 m/s²

Also:  
\[
1\,\text{N} = 1\,\text{kg} \cdot \text{m/s}^2
\]

---

### What This Means:

1. **Force causes acceleration** (not velocity!)
2. **More force → more acceleration** (for same mass)
3. **More mass → less acceleration** (for same force)
4. **Net force = 0 → acceleration = 0** (constant velocity or at rest)

---

### Net Force

**Net force** = total force after adding all forces (considering direction)

Multiple forces can act on an object:
- Add forces in same direction
- Subtract forces in opposite directions
- Result = net force

**Example — Tug of war:**
- Team A pulls left: 500 N
- Team B pulls right: 300 N
- Net force = 500 - 300 = **200 N left**
- Rope accelerates left

**If forces balance (net = 0):**
- No acceleration
- Object maintains constant velocity (could be moving or still)

---

### 🚗 Examples:

**Pushing shopping carts:**
- Empty cart (low mass): Same force → accelerates quickly
- Full cart (high mass): Same force → accelerates slowly
- F = ma → same F, more m = less a

**Kicking balls:**
- Soccer ball (low mass): Kick with force F → flies away fast
- Bowling ball (high mass): Kick with same force F → barely moves
- Same force, different masses → different accelerations

**Forces acting, but no acceleration:**
- Book on table: Gravity pulls down, table pushes up → net = 0
- Car at constant speed: Engine forward, friction backward → net = 0
- You standing: Gravity down, ground up → net = 0

---

## 🔄 Newton's Third Law: Action-Reaction

### The Law:
**"For every action, there is an equal and opposite reaction."**

Or more precisely:
**"When object A exerts a force on object B, object B exerts an equal and opposite force on object A."**

### Key Points:

1. **Forces always come in pairs**
2. **Equal in magnitude, opposite in direction**
3. **Act on DIFFERENT objects** (this is critical!)
4. **Happen simultaneously** (not one after the other)

---

### Why Different Objects Matter:

The action-reaction forces don't cancel because they act on different things.

**Example: You push a box**
- **Action:** You push box with 10 N →
- **Reaction:** Box pushes you with 10 N ←

**Net force on box:**
- Your push: 10 N →
- Friction: 3 N ←
- Net = 7 N → (box accelerates)

**Net force on you:**
- Box pushes you: 10 N ←
- Ground pushes you: 10 N → (from your feet pushing ground)
- Net ≈ 0 (you don't move much)

---

### 🚶 Examples:

**Walking:**
- **Action:** Foot pushes ground backward
- **Reaction:** Ground pushes foot forward
- You move forward because ground pushes you forward

**Swimming:**
- **Action:** Hands push water backward
- **Reaction:** Water pushes you forward

**Rocket in space:**
- **Action:** Rocket expels gas backward/downward
- **Reaction:** Gas pushes rocket forward/upward
- No air or ground needed!

**Standing on floor:**
- **Action:** Gravity pulls you into floor (your weight)
- **Reaction:** Floor pushes you up (normal force)
- Equal and opposite → you don't accelerate

**You on skateboard pushing box:**
- You push box: 10 N →
- Box pushes you: 10 N ←
- **Both move!** But who moves more depends on mass:
  - \( a_{\text{box}} = \dfrac{10}{m_{\text{box}}} \)
  - \( a_{\text{you}} = \dfrac{10}{m_{\text{you}}} \)
- Lighter object accelerates more

---

## 🎯 Key Takeaways:

### First Law (Inertia):
- Objects resist changes in motion
- Mass = measure of inertia
- No net force = no acceleration (constant velocity)

### Second Law (F = ma):
- Force causes acceleration
- Same force: more mass = less acceleration
- Same mass: more force = more acceleration
- Net force = 0 → acceleration = 0

### Third Law (Action-Reaction):
- Forces always come in equal and opposite pairs
- Act on different objects (so they don't cancel)
- Both forces happen simultaneously
- Explains walking, swimming, rockets, why you don't fall through floor

---

## 📐 Important Formulas Summary:

\[
F = ma
\]


\[
a = \frac{F}{m}
\]

\[
m = \frac{F}{a}
\]


\[
F_{\text{net}} = \sum F \quad \text{(sum of all forces)}
\]
---
