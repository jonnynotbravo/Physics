# 🛠️ Phase 2: Classical Mechanics

## Motion (Kinematics)

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
# Newton's Laws of Motion

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
# Types of Forces

These are common forces we encounter in everyday life. Remember: these are **not fundamental forces** — they emerge from electromagnetic and gravitational interactions at the particle level.

---

## 🌍 1. Gravity (Weight)

### What is it?
The force of attraction between any two objects with mass. On Earth, it's what pulls everything toward the center of the planet.

### Formula:
\[ F_g = mg \]

Where:
- **F_g** = gravitational force / weight (N)
- **m** = mass (kg)
- **g** = gravitational acceleration = **9.8 m/s²** on Earth

---

### Key Points:

**Weight ≠ Mass**
- **Mass** = amount of matter (kg) — same everywhere in universe
- **Weight** = force due to gravity (N) — changes based on location

**Gravitational acceleration varies:**
- On Earth: \( g = 9.8 \text{ m/s}^2 \)
- On Moon: \( g \approx 1.6 \text{ m/s}^2 \) (about 1/6 of Earth)
- In space (far from planets): \( g \approx 0 \) (weightless, but still have mass!)

**Direction:**
Always points toward the center of the Earth (downward)

---

### 🍎 Examples:

**Dropping an apple:**
- Mass = 0.1 kg
- \( F_g = mg = 0.1 \times 9.8 = 0.98 \text{ N} \)
- Apple accelerates downward at 9.8 m/s²

**You standing:**
- If your mass = 70 kg
- Your weight = \( 70 \times 9.8 = 686 \text{ N} \)
- Gravity pulls you down with 686 N
- Floor pushes you up with 686 N (normal force)
- Net force = 0 → you don't accelerate

**Why do all objects fall at the same rate?**
- Heavy object: more force (mg), but also more mass (m)
  - \( a = \frac{F}{m} = \frac{mg}{m} = g \)
- Light object: less force (mg), but also less mass (m)
  - \( a = \frac{F}{m} = \frac{mg}{m} = g \)
- **The mass cancels out!**
- Everything accelerates at g = 9.8 m/s² (ignoring air resistance)

---

## 🧱 2. Normal Force

### What is it?
The force a surface exerts on an object in contact with it, **perpendicular** to the surface.

### Symbol:
\[ F_N \text{ or } N \]

---

### Key Points:

- **"Normal" = perpendicular** (not "ordinary")
- Always pushes **away from the surface**
- Prevents objects from passing through each other
- This is an **electromagnetic force** at the atomic level (atoms repelling each other)
- Magnitude varies depending on situation

---

### 📚 Examples:

**Book on a table:**
- Gravity pulls book down: \( F_g = mg \)
- Table pushes book up: \( F_N = mg \)
- Net force = 0 → book doesn't accelerate

**You standing on floor:**
- Weight pulls you down: \( F_g = mg \)
- Floor pushes you up: \( F_N = mg \)
- Net force = 0

**On a slope:**
- Normal force is **perpendicular to the slope** (not vertical)
- \( F_N < mg \) on a slope

**In an elevator:**
- **Accelerating up:** \( F_N > mg \) (you feel heavier)
- **Accelerating down:** \( F_N < mg \) (you feel lighter)
- **Constant velocity:** \( F_N = mg \) (normal feeling)

---

## 🔥 3. Friction

### What is it?
The force that opposes motion (or attempted motion) between two surfaces in contact.

---

### Types of Friction:

#### Static Friction (\( f_s \))
- Prevents object from starting to move
- Acts when object is **stationary**
- Must be overcome to start motion
- Variable force (adjusts to match applied force, up to a maximum)

#### Kinetic Friction (\( f_k \))
- Acts when object is **already moving**
- Usually **less than static friction**
- This is why it's easier to keep something sliding than to start it sliding
- Constant force (for a given situation)

---

### Formulas:

**Static friction (maximum):**
\[ f_s \leq \mu_s F_N \]

**Kinetic friction:**
\[ f_k = \mu_k F_N \]

Where:
- **f** = friction force (N)
- **μ** (mu) = coefficient of friction (no units, just a number between 0 and ~1.5)
  - **μ_s** = static friction coefficient
  - **μ_k** = kinetic friction coefficient
- **F_N** = normal force (N)

**Usually:** \( \mu_s > \mu_k \) (harder to start moving than to keep moving)

---

### Key Points:

**Friction depends on:**
1. **Surface materials** (μ) — rough vs. smooth, rubber vs. ice
2. **How hard surfaces are pressed together** (F_N)

**Friction does NOT depend on:**
- Surface area in contact (in simple models)
- Speed (in simple models)

**Direction:**
- Always opposes motion (or attempted motion)
- Acts parallel to the surface

---

### 🚗 Examples:

**Car braking:**
- Friction between tires and road slows the car
- Without friction (ice), car slides and can't stop

**Walking:**
- Static friction between shoes and ground prevents slipping
- Allows you to push off the ground and move forward

**Rubbing hands together:**
- Kinetic friction creates heat
- Friction converts kinetic energy → thermal energy

**Different surfaces (approximate μ values):**
- Ice on ice: μ ≈ 0.02–0.04 (very slippery)
- Rubber on dry concrete: μ ≈ 0.6–1.0 (good grip)
- Teflon on Teflon: μ ≈ 0.04 (why non-stick pans work)
- Rubber on wet concrete: μ ≈ 0.3–0.5 (reduced grip)

---

## 🪢 4. Tension

### What is it?
The pulling force transmitted through a rope, string, cable, or chain when pulled tight.

### Symbol:
\[ T \text{ or } F_T \]

---

### Key Points:

- **Tension always pulls** (never pushes)
- Acts along the direction of the rope/string
- Same tension throughout an ideal rope (massless, unstretchable)
- Rope goes slack if you try to compress it (tension becomes zero)
- Real ropes have mass and stretch slightly, but we usually ignore this

---

### 🎣 Examples:

**Hanging object:**
- Object hangs motionless from rope
- Tension in rope = weight of object
- \( T = mg \)

**Tug of war:**
- Both teams pull on rope
- Tension is the same throughout the rope
- If Team A pulls with 500 N and Team B pulls with 300 N:
  - Tension in rope = 500 N (or 300 N, they're the same!)
  - Net force on rope determines which way it moves

**Pulling a sled:**
- Tension in rope transmits your pull to the sled
- If you pull rope with 50 N, rope pulls sled with 50 N (Newton's 3rd Law)

**Elevator cable:**
- Tension holds elevator up
- **Accelerating upward:** \( T > mg \) (must support weight AND accelerate)
- **Constant velocity:** \( T = mg \) (just supports weight)
- **Accelerating downward:** \( T < mg \) (weight helps acceleration)

---

## 🎯 Summary Table:

| Force Type | Direction | Formula/Relation | What Causes It |
|------------|-----------|------------------|----------------|
| **Gravity (Weight)** | Toward Earth's center (down) | \( F_g = mg \) | Mass attracting mass |
| **Normal Force** | Perpendicular to surface (away from surface) | Varies by situation | Surface contact (electromagnetic) |
| **Friction** | Opposes motion (parallel to surface) | \( f_s \leq \mu_s F_N \) <br> \( f_k = \mu_k F_N \) | Surface roughness (electromagnetic) |
| **Tension** | Along rope/string (pulling only) | Varies by situation | Rope/string being pulled tight |

---

## 🔑 Key Insights:

1. **All these forces (except gravity) are electromagnetic in origin:**
   - Normal force = atoms/molecules repelling each other
   - Friction = interactions between surface atoms
   - Tension = molecular bonds in rope being stretched

2. **Forces can balance to create equilibrium:**
   - Gravity down + Normal force up = standing still (net = 0)
   - Applied force forward + Friction backward = constant velocity (net = 0)

3. **Net force determines motion** (Newton's 2nd Law):
   - Add all forces vectorially → get net force → \( a = F_{net}/m \)

4. **Same principles apply everywhere:**
   - On Earth, Moon, Mars — just g changes
   - In water, air, vacuum — just friction changes

---

## 📐 Important Formulas Summary:

**Gravity:**
\[ F_g = mg \]
\[ g_{\text{Earth}} = 9.8 \text{ m/s}^2 \]

**Friction:**
\[ f_s \leq \mu_s F_N \]
\[ f_k = \mu_k F_N \]

**Normal Force:**
No single formula — depends on situation
- On flat surface at rest: \( F_N = mg \)
- On slope: \( F_N = mg \cos(\theta) \)
- In accelerating elevator: \( F_N = m(g + a) \) or \( F_N = m(g - a) \)

**Tension:**
No single formula — solve using Newton's 2nd Law (\( F = ma \))

---
# Energy

Energy is one of the **most important concepts in all of physics**. It's the ability to do work, to cause change, to make things happen.

---

## ⚡ What is Energy?

**Energy** = the ability to do work or cause change

### Key Points:
- Energy is **not** a physical thing you can hold
- It's a **property** (specifically, a calculated/derived property)
- Energy is a **number we calculate** based on other factors (mass, speed, height, etc.)
- Measured in **Joules (J)**

\[ 1 \text{ J} = 1 \text{ kg} \cdot \text{m}^2/\text{s}^2 \]

### How We Discovered Energy:
1. People noticed moving things can do work (kinetic)
2. People noticed height matters (potential)
3. Realized these transform into each other
4. Discovered heat is also a form of energy
5. Found that the TOTAL of all forms is conserved

**Energy isn't a "thing" we found — it's a pattern we noticed and gave a name.**

---

## 🔑 The Law of Conservation of Energy

### The Most Important Law in Physics:

**"Energy cannot be created or destroyed — only transformed from one form to another."**

In a **closed system** (no energy enters or leaves), the total energy stays constant forever.

### What This Means:
- Energy constantly changes form (potential ↔ kinetic ↔ heat ↔ light, etc.)
- But the **total amount** never changes
- Energy never vanishes — it just spreads out or transforms

### Formula:
\[ E_{\text{total}} = PE + KE + \text{heat} + \text{sound} + ... = \text{constant} \]

---

## 🏔️ 1. Potential Energy (PE)

### What is it?
**Stored energy** due to an object's position or configuration.

It's energy that has the **potential** to do work later.

---

### Gravitational Potential Energy

Energy stored due to an object's **height** above a reference point.

### Formula:
\[ PE = mgh \]

Where:
- **PE** = potential energy (J)
- **m** = mass (kg)
- **g** = gravitational acceleration = 9.8 m/s²
- **h** = height above reference point (m)

### Key Points:
- Higher up = more potential energy
- Heavier object = more potential energy
- **Reference point matters** — you choose where h = 0
- PE is **relative** to your chosen reference
- Only the **difference** in PE matters (tells you how much energy transforms)

---

### 🎢 Examples:

**Ball held at height:**
- Mass = 2 kg, height = 5 m
- \( PE = mgh = 2 \times 9.8 \times 5 = 98 \text{ J} \)
- If you drop it, this PE converts to kinetic energy

**Water at top of waterfall:**
- Has gravitational PE
- As it falls: PE → KE
- At bottom: KE can turn turbines (hydroelectric power)

**Roller coaster at peak:**
- Maximum PE, minimum KE (slow at top)
- As it descends: PE → KE (speeds up)
- At bottom: minimum PE, maximum KE (moving fast)

**Two balls (one on ground, one on building):**
- Ball on ground: PE = 0 J (using ground as reference)
- Ball on building (20 m): PE = 196 J (if mass = 1 kg)
- The ball on building has MORE energy because of its position

---

### Other Types of Potential Energy:

**Elastic Potential Energy:**
- Stored in stretched/compressed springs, rubber bands
- Formula: \( PE_{\text{elastic}} = \frac{1}{2}kx^2 \)
  - k = spring constant
  - x = displacement from rest

**Chemical Potential Energy:**
- Stored in molecular bonds (food, fuel, batteries, gasoline)
- Released during chemical reactions

**Electrical Potential Energy:**
- Stored in separated charges (batteries)

---

## 🏃 2. Kinetic Energy (KE)

### What is it?
Energy of **motion**. Any object that's moving has kinetic energy.

### Formula:
\[ KE = \frac{1}{2}mv^2 \]

Where:
- **KE** = kinetic energy (J)
- **m** = mass (kg)
- **v** = velocity (m/s)

### Key Points:
- Faster = much more KE (velocity is **squared**!)
- Doubling speed = **4× the kinetic energy**
- Heavier object = more KE (at same speed)
- Direction doesn't matter (v² is always positive)

---

### 🚗 Examples:

**Moving car:**
- Mass = 1000 kg, velocity = 20 m/s
- \( KE = \frac{1}{2} \times 1000 \times 20^2 = \frac{1}{2} \times 1000 \times 400 = 200{,}000 \text{ J} \)

**Why speed limits matter:**
- Car at 30 mph: certain KE
- Same car at 60 mph (2× speed): **4× the KE**
- Much harder to stop, much more damage in crashes

**Why bullets are destructive:**
- Small mass, but **very high velocity**
- v² term makes KE huge despite low mass

---

## 🔄 Energy Transformations

Energy constantly changes form. The total stays constant, but individual forms change.

---

### 🎢 Roller Coaster Example:

**At the top:**
- PE = maximum (high up)
- KE = minimum (moving slowly)
- Total = PE + KE

**Falling down:**
- PE decreases (losing height)
- KE increases (speeding up)
- **PE → KE**

**At the bottom:**
- PE = minimum (low height)
- KE = maximum (moving fast)
- Total = same as at top!

**Throughout the ride:**
\[ E_{\text{total}} = PE + KE = \text{constant} \]

---

### 🏀 Bouncing Ball:

1. **Held at height:** PE = high, KE = 0
2. **Falling:** PE → KE
3. **Just before ground:** PE = 0, KE = maximum
4. **Hitting ground:** KE → heat + sound + deformation
5. **Bouncing up:** Remaining energy → PE (gravitational)
6. **Each bounce:** Loses energy to heat/sound, doesn't bounce as high

**Total energy still conserved** — just spread to surroundings as heat and sound!

---

### 🪨 Stone Falling from Building (20 m, 2 kg):

| Position | Height (m) | PE (J) | Speed (m/s) | KE (J) | Total (J) |
|----------|-----------|--------|-------------|--------|-----------|
| **Top** | 20 | 392 | 0 | 0 | **392** |
| **Middle** | 10 | 196 | ~14 | 196 | **392** |
| **Bottom** | 0 | 0 | ~20 | 392 | **392** |
| **After impact** | 0 | 0 | 0 | 0 | **392*** |

*Energy transformed to: heat (~300 J), sound (~50 J), deformation (~42 J) = still 392 J total!

---

### 🚗 Car Example (Full Journey):

**Starting with 50L gasoline = 1.65 billion J of chemical PE**

| Stage | Chemical PE | Kinetic | Heat | Total |
|-------|------------|---------|------|-------|
| **Gas station** | 1.65 billion J | 0 | 0 | **1.65 billion J** |
| **Engine starts** | 0 | 500 million J | 1.15 billion J | **1.65 billion J** |
| **Cruising** | Decreasing | 500 million J | Increasing | **1.65 billion J** |
| **After braking** | 0 | 0 | 1.65 billion J | **1.65 billion J** |

**Energy flow:** Chemical → Motion → Heat (all ends up as heat in environment)

**Why gas cars are inefficient:** ~70% wasted as heat immediately in combustion

**Why electric cars are better:** Electric motors ~85-90% efficient (vs. 30% for combustion)

**Regenerative braking (hybrids):**
- Normal braking: KE → heat (wasted)
- Regenerative: KE → electrical energy (captured in battery, ~80% recovered!)

---

## 💡 Work and Energy

**Work** = energy transferred through force

### Formula:
\[ W = Fd \cos(\theta) \]

Where:
- **W** = work (J)
- **F** = force (N)
- **d** = displacement (m)
- **θ** = angle between force and displacement

### Simple case (force parallel to motion):
\[ W = Fd \]

---

### Key Points:

- Work = energy transferred
- **Positive work** = energy added to object (force in direction of motion)
- **Negative work** = energy removed from object (force opposes motion)
- **Zero work** if:
  - No displacement (d = 0)
  - Force perpendicular to motion (θ = 90°)

---

### 🏋️ Examples:

**Lifting a box:**
- You apply upward force, box moves upward
- You do **positive work** on box
- Box gains PE

**Lowering a box:**
- Gravity does positive work (force and motion both down)
- You do negative work (force up, motion down)
- Box loses PE

**Carrying box horizontally:**
- You apply upward force, box moves horizontally
- Force ⊥ motion → **zero work** (on the box's motion)

---

## ⚖️ Work-Energy Theorem

**The net work done on an object equals its change in kinetic energy.**

### Formula:
\[ W_{\text{net}} = \Delta KE = KE_{\text{final}} - KE_{\text{initial}} \]

### What This Means:
- Net work positive → object speeds up
- Net work negative → object slows down
- Net work zero → speed stays constant

---

## 🎯 Why Conservation of Energy Matters

### 1. **Predictions Without Details**
- Don't need to track every force at every moment
- Just know: energy at start = energy at end
- Calculate final state directly!

### 2. **Tells Us What's Impossible**
- Ball can't bounce higher than dropped
- Perpetual motion machines impossible
- Can't get more energy out than you put in

### 3. **Explains Why Things Stop**
- Pendulum stops: energy → heat (air resistance, friction)
- Car stops: KE → heat (brakes)
- Energy still exists, just spread out

### 4. **Universal Law**
- Works for gravity, electricity, chemistry, nuclear, everything
- Same principle across all of physics

### 5. **Practical Applications**
- Power plants: convert one form → another
- Batteries: store and release energy
- Engines: optimize conversions
- All engineering based on energy conservation

---

## 📐 Important Formulas Summary:

**Gravitational Potential Energy:**
\[ PE = mgh \]

**Kinetic Energy:**
\[ KE = \frac{1}{2}mv^2 \]

**Conservation of Energy:**
\[ E_{\text{total}} = PE + KE + \text{other forms} = \text{constant} \]

**Work:**
\[ W = Fd \cos(\theta) \]
\[ W = Fd \text{ (parallel forces)} \]

**Work-Energy Theorem:**
\[ W_{\text{net}} = \Delta KE \]

---

## 🔑 Key Takeaways:

1. **Energy = ability to cause change** (calculated property, not physical substance)

2. **Conservation: Energy cannot be created or destroyed**
   - Only transforms from one form to another
   - Total in closed system = constant

3. **Two main types:**
   - **PE** = stored energy (position/configuration)
   - **KE** = energy of motion

4. **Energy constantly transforms:**
   - PE ↔ KE ↔ heat ↔ light ↔ sound ↔ chemical, etc.
   - Total always conserved

5. **Most energy ends up as heat:**
   - Heat = energy spreading out randomly
   - This is why things eventually stop (friction converts organized motion → random heat)

6. **Work = energy transfer through force**

7. **Conservation is the most powerful tool in physics:**
   - Predict outcomes
   - Know what's impossible
   - Design efficient systems

---

# 🔹 Momentum

Momentum is another fundamental concept in physics. Like energy, it's **conserved** — but momentum works differently and is especially powerful for analyzing collisions and explosions.

---

## 🎯 What is Momentum?

**Momentum** = mass in motion

It's a measure of how much "oomph" a moving object has — how hard it is to stop.

### Formula:
\[ p = mv \]

Where:
- **p** = momentum (kg·m/s)
- **m** = mass (kg)
- **v** = velocity (m/s)

### Key Points:
- Momentum is a **vector** (has direction)
- More mass = more momentum
- More velocity = more momentum
- **Direction matters** (unlike KE where v² eliminates direction)

---

## 🚗 Understanding Momentum

### Example 1: Mass Matters
- **Bicycle** (10 kg) at 5 m/s: p = 10 × 5 = **50 kg·m/s**
- **Truck** (5000 kg) at 5 m/s: p = 5000 × 5 = **25,000 kg·m/s**

**Truck has 500× more momentum** — much harder to stop!

### Example 2: Velocity Matters
- **Car** (1000 kg) at 10 m/s: p = **10,000 kg·m/s**
- **Same car** at 30 m/s: p = **30,000 kg·m/s**

**3× faster = 3× more momentum**

---

## 🔑 Momentum vs. Kinetic Energy

Both involve mass and velocity, but they're fundamentally different:

| Property | Formula | Velocity Dependence | Type | What It Measures |
|----------|---------|-------------------|------|------------------|
| **Momentum** | \( p = mv \) | Linear (v) | Vector (direction matters) | "Push" in a direction |
| **Kinetic Energy** | \( KE = \frac{1}{2}mv^2 \) | Squared (v²) | Scalar (no direction) | Energy stored in motion |

### Key Differences:

**Double the speed:**
- Momentum: doubles (2×)
- KE: quadruples (4×)

**Direction:**
- Momentum: east vs. west = opposite signs (different momentum)
- KE: east vs. west = same value (direction irrelevant)

---

## 💥 Critical Difference: Direction in Collisions

### Two Cars Colliding Head-On:

**Car A:** 1000 kg moving **east** at 20 m/s
**Car B:** 1000 kg moving **west** at 20 m/s
They crash and stop.

**Momentum:**
- Before: (+20,000) + (-20,000) = **0 kg·m/s**
- After: **0 kg·m/s**
- **Conserved!** ✓

**Kinetic Energy:**
- Before: 200,000 + 200,000 = **400,000 J**
- After: **0 J**
- **NOT conserved** — transformed to heat, sound, deformation

**Key Insight:** Momentum cares about direction and cancels out. KE doesn't care about direction and all converts to other forms.

---

## ⚖️ Conservation of Momentum

### The Law:
**"In a closed system (no external forces), the total momentum before an event equals the total momentum after the event."**

### Formula:
\[ p_{\text{before}} = p_{\text{after}} \]

Or more specifically:
\[ m_1v_1 + m_2v_2 = m_1v_1' + m_2v_2' \]

(Primed variables = after collision)

---

## 🎯 Key Points:

1. **Total momentum never changes** (in isolated system)
2. **Individual objects can gain/lose momentum** (but total stays same)
3. **Direction matters** (opposite directions = opposite signs)
4. **Works for ALL collisions** (momentum always conserved!)

---

## 🧊 Example 1: Ice Skaters Pushing Apart

**Before:**
- Skater A (50 kg): v = 0
- Skater B (50 kg): v = 0
- **Total momentum = 0 kg·m/s**

**After pushing:**
- Skater A: moves left at 2 m/s
- Skater B: moves right at ??? m/s

**Conservation:**
\[ 0 = (50)(-2) + (50)(v_B) \]
\[ 0 = -100 + 50v_B \]
\[ v_B = 2 \text{ m/s (right)} \]

**Both move away at same speed!**
Total momentum = -100 + 100 = **0** ✓

---

## 🎱 Example 2: Pool Ball Collision

**Before:**
- Ball 1 (moving): 0.2 kg at 5 m/s →
- Ball 2 (still): 0.2 kg at 0 m/s

**Total momentum before:**
\[ p = (0.2)(5) + 0 = 1 \text{ kg·m/s} \]

**After:**
- Ball 1 stops: v = 0 m/s
- Ball 2 moves: v = ??? m/s

**Conservation:**
\[ 1 = (0.2)(0) + (0.2)(v_2) \]
\[ v_2 = 5 \text{ m/s} \]

**Moving ball stopped, stationary ball picked up all its momentum!**

---

## 🚗 Example 3: Car Crash (Sticking Together)

**Before:**
- Car A: 1000 kg at 20 m/s → (positive)
- Car B: 1500 kg at 10 m/s ← (negative)

**Total momentum:**
\[ p = (1000)(20) + (1500)(-10) = 20{,}000 - 15{,}000 = 5{,}000 \text{ kg·m/s →} \]

**After (stuck together):**
- Combined mass = 2500 kg
- Combined velocity = ??? m/s

**Conservation:**
\[ 5{,}000 = (2500)(v) \]
\[ v = 2 \text{ m/s →} \]

**Both cars move together at 2 m/s to the right**
(Car A had more momentum, so final direction is right)

---

## 💥 Types of Collisions

When objects collide, **momentum is ALWAYS conserved**. But what happens to **kinetic energy** depends on the collision type:

---

## 🎾 1. Elastic Collisions

### Definition:
**Both momentum AND kinetic energy are conserved.**

### Characteristics:
- No energy lost to heat, sound, or deformation
- Objects bounce off each other
- Total KE before = Total KE after
- **Perfect, "bouncy" collisions**

### Formulas:
\[ p_{\text{before}} = p_{\text{after}} \] ✓
\[ KE_{\text{before}} = KE_{\text{after}} \] ✓

---

### 🎱 Example: Pool Balls

**Before:**
- Ball 1: 0.2 kg at 5 m/s →
- Ball 2: 0.2 kg at 0 m/s

**Momentum before:** 1 kg·m/s
**KE before:** 2.5 J

**After:**
- Ball 1 stops: 0 m/s
- Ball 2 moves: 5 m/s →

**Momentum after:** 1 kg·m/s ✓
**KE after:** 2.5 J ✓

**Both conserved = elastic collision!**

---

### Real-World Elastic Collisions:
- Pool/billiard balls (very close)
- Steel ball bearings
- Atoms/molecules (microscopic level)
- Bouncing superballs

**Note:** Perfect elastic collisions are rare in real life.

---

## 🚗 2. Inelastic Collisions

### Definition:
**Momentum is conserved, but kinetic energy is NOT.**

### Characteristics:
- Some KE transforms to other forms (heat, sound, deformation)
- Total KE after < Total KE before
- Objects might stick together or deform
- **Most real-world collisions are inelastic**

### Formulas:
\[ p_{\text{before}} = p_{\text{after}} \] ✓ (momentum still conserved!)
\[ KE_{\text{before}} > KE_{\text{after}} \] (some KE lost)

---

### 🚗 Example: Car Crash (Perfectly Inelastic)

**Perfectly inelastic** = objects stick together after collision (maximum KE loss)

**Before:**
- Car A: 1000 kg at 20 m/s →
- Car B: 1000 kg at 0 m/s (parked)

**Momentum before:** 20,000 kg·m/s
**KE before:** 200,000 J

**After (stuck together):**
- Combined: 2000 kg at 10 m/s →

**Momentum after:** 20,000 kg·m/s ✓ (conserved!)
**KE after:** 100,000 J

**KE lost = 100,000 J** → transformed to heat, sound, deformation

**Energy still conserved** (didn't disappear), just no longer kinetic!

---

## 🎯 Collision Comparison Table:

| Type | Momentum Conserved? | KE Conserved? | What Happens | Examples |
|------|-------------------|--------------|--------------|----------|
| **Elastic** | ✓ Yes | ✓ Yes | Objects bounce, no energy lost | Pool balls, atoms |
| **Inelastic** | ✓ Yes | ✗ No | Some KE → heat/sound | Most real collisions |
| **Perfectly Inelastic** | ✓ Yes | ✗ No (max loss) | Objects stick together | Car crashes, clay |

---

## 🎯 Why Momentum Matters

---

## 1. Explains Rockets and Propulsion

### 🚀 Rocket in Space:

No air, no ground — how does it move?

**Answer: Conservation of Momentum!**

**Before firing:**
- Rocket + fuel: 10,000 kg at 0 m/s
- Total momentum = **0 kg·m/s**

**After firing (expelling gas backward):**
- Gas: 100 kg at -1000 m/s ← (backward)
- Rocket: 9900 kg at ??? m/s →

**Conservation:**
\[ 0 = (100)(-1000) + (9900)(v) \]
\[ v = 10.1 \text{ m/s →} \]

**Rocket moves forward by throwing mass backward!**

---

## 2. Predicts Outcomes Even When Energy Is Lost

In inelastic collisions, we **don't need to track where energy went** — momentum still tells us the outcome!

### Example: Catching a Ball

**Before:**
- Ball: 0.5 kg at 20 m/s →
- You: 70 kg at 0 m/s

**Total momentum = 10 kg·m/s**

**After (you catch it):**
- You + ball: 70.5 kg at ??? m/s

**Conservation:**
\[ 10 = (70.5)(v) \]
\[ v = 0.14 \text{ m/s ←} \]

**You move backward at 0.14 m/s!**

(Lots of KE lost to heat/sound, but we don't need to track it!)

---

## 3. Reveals Forces in Collisions

### Newton's Second Law (Advanced Form):
\[ F = \frac{\Delta p}{\Delta t} \]

Where:
- **F** = force (N)
- **Δp** = change in momentum (kg·m/s)
- **Δt** = time interval (s)

### Key Insight:
**Same momentum change over shorter time = bigger force**
**Same momentum change over longer time = smaller force**

---

## 🥊 Example: Why Airbags Save Lives

**Car crash:** You go from 30 m/s → 0 m/s

Your momentum change:
\[ \Delta p = (70)(0 - 30) = -2100 \text{ kg·m/s} \]

---

**Without airbag (hit dashboard):**
- Stop in **0.01 seconds**
- \[ F = \frac{-2100}{0.01} = -210{,}000 \text{ N} \]
- **Huge force = death**

**With airbag:**
- Stop in **0.1 seconds** (10× longer)
- \[ F = \frac{-2100}{0.1} = -21{,}000 \text{ N} \]
- **10× less force = survivable!**

**Same momentum change, but spreading it over more time reduces force dramatically.**

---

## 🛡️ More Safety Applications:

**All work by increasing Δt to decrease F:**

- **Crumple zones in cars** → collision takes longer → less force on passengers
- **Padding/helmets** → impact takes longer → less force on head
- **Landing with bent knees** → stopping takes longer → less force on legs
- **Boxing gloves** → contact time longer → reduced force
- **Karate breaking boards** → very short contact → huge force → board breaks

---

## 📐 Important Formulas Summary:

**Momentum:**
\[ p = mv \]

**Conservation of Momentum:**
\[ p_{\text{before}} = p_{\text{after}} \]
\[ m_1v_1 + m_2v_2 = m_1v_1' + m_2v_2' \]

**Force from Momentum Change:**
\[ F = \frac{\Delta p}{\Delta t} \]

**Elastic Collision:**
- \( p_{\text{before}} = p_{\text{after}} \) ✓
- \( KE_{\text{before}} = KE_{\text{after}} \) ✓

**Inelastic Collision:**
- \( p_{\text{before}} = p_{\text{after}} \) ✓
- \( KE_{\text{before}} > KE_{\text{after}} \) (some lost)

---

## 🔑 Key Takeaways:

1. **Momentum = mass × velocity** (vector, direction matters)

2. **Always conserved in collisions** (unlike KE which can transform)

3. **Momentum vs. KE:**
   - Momentum: cares about direction, always conserved
   - KE: doesn't care about direction, only conserved in elastic collisions

4. **Elastic collisions:** Both momentum and KE conserved (rare)

5. **Inelastic collisions:** Only momentum conserved, KE lost to heat/sound (common)

6. **Perfectly inelastic:** Objects stick together (maximum KE loss)

7. **Explains rockets:** Throw mass backward → move forward (even in space!)

8. **Safety devices work via F = Δp/Δt:**
   - Increase time (Δt) → decrease force (F)
   - Airbags, crumple zones, padding all extend collision time

9. **Predicts outcomes without tracking energy loss:**
   - Don't need to know where heat/sound went
   - Just track mass × velocity

---
