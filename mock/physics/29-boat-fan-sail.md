# Question
An electric fan is placed on a stationary boat and air is blown with it on the sail of the boat. Which of the following statement(s) is/are correct?  
1) The boat will be uniformly accelerated in the direction of flow of air  
2) The boat will start moving with uniform speed  
3) The boat will remain stationary as before  
4) The boat will be uniformly accelerated opposite to the direction of flow of air

## Intuition First: Can you push yourself forward by blowing on your own shirt?

Imagine sitting on a skateboard holding a fan and a big sheet in front of you (like a sail). You turn the fan on and blow air onto the sheet. Will you roll forward?

Your gut might say “yes, the sheet is pushed forward by the air.” But remember: the fan had to push the air forward first. When the fan pushes air forward, the fan (and you) get pushed backward. Then that same air hits your sheet and pushes you forward by the same amount. The “backward” and “forward” pushes are two parts of the same internal interaction.

So, net effect in an ideal, frictionless world: you don’t move.

---

## What’s going on physically? The chain of causes

- Step 1 (Fan action): The fan grabs surrounding air and throws it toward the sail (forward). By Newton’s third law, the fan experiences an equal and opposite push (backward).
- Step 2 (Sail action): The fast-moving air hits the sail and pushes it forward. The air slows down again relative to the boat.

If the air starts at rest (relative to the boat’s environment) and ends at rest after bouncing off the sail, the environment’s total momentum stays zero. With no external net force, the boat’s momentum can’t change overall.

This is the same logic as “you can’t lift yourself by pulling up on your own shoelaces.”

---

## Build it from first principles (no formulas first)

Key idea: Internal forces can’t change the motion of the center of mass of a system. Only external forces can.

- If we treat “boat + fan + sail + the particular parcel of air that gets blown and later hits the sail” as our system, and if that air ends up at rest again after striking the sail, the system has no net external push from the outside world.

- So the total momentum change is zero: the backward kick from the fan and the forward push from the sail cancel on the boat.

### Momentum accounting

Let p be the forward momentum given to the air by the fan.

- Impulse on fan (and thus boat) from accelerating air forward = −p (backward).
- Impulse on sail (and thus boat) when that air stops on the sail = +p (forward).

Net impulse on boat:
$$
\Delta p_{\text{boat}} = (-p) + (+p) = 0
$$
So the boat’s momentum doesn’t change; if it was at rest, it stays at rest.

### Center-of-mass view (another angle)
No external force → center-of-mass velocity stays constant:
$$
F_\text{external} = M\,\frac{dV_\text{CM}}{dt} = 0 \Rightarrow V_\text{CM} = \text{constant}
$$
Started at rest → remains at rest.

---

## Answer to the question

- 1) Uniformly accelerated in direction of air flow → No.
- 2) Starts moving with uniform speed → No (it doesn’t start moving at all).
- 3) Remains stationary as before → Yes (in the ideal case).
- 4) Uniformly accelerated opposite to air flow → No (not in the ideal case).

Correct statement: 3) The boat will remain stationary as before.

Note: In real life, some air leaks around the sail or doesn’t transfer its full momentum back. That leftover forward air momentum makes the boat get a tiny backward drift (opposite to air flow). But exam-style idealization: choose option 3.

---

## Experimental view: What would you observe?

- On a low-friction cart: Fan blowing on a sheet mounted on the same cart → cart hardly moves.
- Remove the sheet so air is blown freely forward → cart moves backward (reaction to accelerating air forward).
- Put the sheet on a second cart in front → both carts move: the fan-cart moves backward, the sail-cart moves forward.

---

## 🧠 Quick Exam Tips

- Internal forces can’t change a system’s overall motion.
- Fan pushes air forward (boat pushed backward), air then hits sail (boat pushed forward) → cancels.
- If air escapes without giving its momentum back, the boat moves opposite the escaping air.
- Idealized exam answer: the boat remains stationary.

---

## Misconception Clinic

- Many students think “the sail gets pushed, so the boat moves forward.” But actually, the fan already pushed the boat backward by the same amount when it accelerated the air. Net zero in ideal conditions.
- A common mistake is assuming energy use implies motion. You can waste energy stirring air inside your system without moving the center of mass.
- “Uniform speed” is not the same as “no acceleration.” Starting from rest, you need a net external impulse to gain any speed at all.

---

## What-if and reverse logic

- What if you remove the sail? Then the accelerated air leaves with forward momentum, so the boat gets a backward thrust. That’s a jet/propeller principle.
- What if the sail is on another boat? Then the fan-boat goes backward, and the sail-boat goes forward.
- What if there’s water drag? With the perfect fan-on-sail setup, net driving force is zero, so drag just keeps you stationary. With leaks, you might drift slowly backward until drag balances the small net backward thrust.

---

## Extension links

- Rockets: hot gas expelled backward gives forward thrust because the gas doesn’t hand the momentum back.
- Drones/propellers: air is pushed downward/backward and not recaptured, so vehicles move upward/forward.

---

## Interactive practice

1) A person on frictionless skates throws a ball forward and catches it after it bounces off a wall they are carrying. Net motion?
- A) Forward
- B) Backward
- C) No net motion
Answer: C

2) Two carts on a track: rear cart has a fan, front cart holds a sail. Fan blows air to sail. What happens?
- A) Rear cart forward, front cart backward
- B) Rear cart backward, front cart forward
- C) Both stationary
Answer: B

3) A fan on a boat blows air backward into open air (no sail). Which way does the boat go?
- A) Forward
- B) Backward
- C) Stationary
Answer: A

4) In the original problem, if 20% of the air’s forward momentum escapes around the sail, the boat’s motion is mainly:
- A) Slightly forward
- B) Stationary
- C) Slightly backward
Answer: C

---

> Reflective essence
> Physics often says: you can’t cheat momentum. Shuffling forces inside a closed system changes who pushes whom, but without an external push, the whole group goes nowhere. Understanding “what counts as outside” is the key to predicting motion.