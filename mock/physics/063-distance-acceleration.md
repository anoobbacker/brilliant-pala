## Question
A body starts from rest and has an acceleration of $20 \mathrm{~cm} / \mathrm{s}^2$. The distance covered by the body in first 8 s in cm is :


## Understand the situation (build from everyday thinking)
- Imagine a trolley that starts from rest on a smooth, gentle slope. Each second, its speed increases by the same amount. That steady “gain in speed per second” is called acceleration.
- Here, the acceleration is 20 cm/s². That literally means: every second, the speed increases by 20 cm/s.

We want the distance it travels in the first 8 seconds.

## Step 1: What does constant acceleration do to speed?
- Acceleration = how fast velocity changes. If it adds 20 cm/s every second, then:
  - After 1 s: speed = 20 cm/s
  - After 2 s: speed = 40 cm/s
  - After t s: speed = 20 t cm/s

From first principles, think of it as stacking equal “speed-chunks” each second.

Mathematically, we’re saying:
```math
\text{acceleration} = \frac{\Delta v}{\Delta t} \quad \Rightarrow \quad v(t) = v(0) + a t
```
Since it starts from rest, $v(0) = 0$, so:
```math
v(t) = a t
```

## Step 2: How do we connect distance to speed?
- Distance is how far you go when you keep moving at certain speeds over time.
- If speed were constant, distance would be speed × time. But here speed is changing.
- So, think of time as many tiny slices. In each tiny slice $\Delta t$, distance ≈ speed × time for that slice. Adding all the slices gives total distance.
- Graphically: distance = area under the speed–time graph.

For constant acceleration from rest, the $v$–$t$ graph is a straight line from 0 to $v = a t$. The area under this line in time $t$ is a triangle.

Area of that triangle:
```math
s(t) = \text{area} = \frac{1}{2} \times \text{base} \times \text{height}
     = \frac{1}{2} \times t \times (a t)
     = \frac{1}{2} a t^2
```

Alternate (equally first-principles) view: The speed grows linearly from 0 to $a t$, so the average speed over the interval is the midpoint:
```math
v_{\text{avg}} = \frac{0 + a t}{2} = \frac{a t}{2}
```
Then distance = average speed × time:
```math
s(t) = v_{\text{avg}} \, t = \frac{a t}{2} \cdot t = \frac{1}{2} a t^2
```

Dimensional check: $[a] = \text{L}/\text{T}^2$, so $a t^2$ has units of length L. Good.

## Step 3: Compute for 8 seconds
Given $a = 20$ cm/s² and $t = 8$ s:
```math
s = \frac{1}{2} \cdot 20 \cdot (8)^2
  = 10 \cdot 64
  = 640 \text{ cm}
```

Answer: 640 cm.

## Multiple approaches (for deeper trust)
- Graph/area method: We used area under the v–t graph (triangle).
- Calculus method: If $a = \frac{dv}{dt}$ and $a$ is constant, integrate:
  ```math
  \frac{dv}{dt} = a \Rightarrow v = a t \quad (\text{using } v(0)=0)
  ```
  Distance is $s = \int_0^t v \, dt = \int_0^t a t \, dt = \frac{1}{2} a t^2$.
- Experimental method: Use a ticker-tape timer or smartphone motion app on a gentle slope; plot distance vs time. You’ll observe $s \propto t^2$ for constant acceleration.

---

## Conceptual follow-up questions
1. If the body started with an initial speed of 50 cm/s but the same acceleration, how would the distance formula change, and why?
2. If acceleration were negative (object slowing down), what happens to the v–t graph area and the distance?
3. Why is it incorrect to compute distance as final speed × time here?
4. If you double the time while keeping the same acceleration from rest, by what factor does the distance change? Explain intuitively.

## Application questions
- Car design: Why do stopping distances increase roughly with the square of reaction time or braking time when braking force (hence deceleration) is nearly constant?
- Spaceflight: During a rocket’s constant-thrust burn (roughly constant acceleration early on), how does the displacement scale with burn time?
- Sports: In a 100 m sprint start, why do early steps cover shorter distances even though the runner accelerates strongly?

## Common misconceptions and how to avoid them
- Mixing units: If acceleration is in cm/s², keep distance in cm. Convert only once at the start or end to avoid mistakes.
- Using final speed × time: That assumes constant speed, which is false for acceleration. Use average speed or the area under the v–t graph.
- Forgetting “starts from rest”: If initial speed isn’t zero, you must include that part of motion. The correct expression becomes $s = ut + \tfrac{1}{2} a t^2$ only after we’ve reasoned out the average speed for a linearly changing velocity.

## Extension challenges
1. Variable acceleration: Suppose acceleration increases with time, $a(t) = k t$. Derive $v(t)$ and $s(t)$ from scratch by integrating.
2. Between-times distance: How far does the body travel between $t=8$ s and $t=9$ s? Do it via v–t area or by $s(9)-s(8)$.
3. Energy lens: Starting from work–energy ideas, argue that with constant acceleration from rest, $s \propto v^2$ and connect that to $s \propto t^2$ via $v \propto t$.
4. Discrete reasoning: If time is counted in whole seconds and acceleration adds 20 cm/s each second, write the distance after $n$ seconds as a sum of an arithmetic series and show it equals $\tfrac{1}{2} a t^2$.

## Reflective insight
The essence: Constant acceleration means velocity grows linearly with time. Distance is the accumulation of velocity over time—geometrically, the area under the v–t line. A straight line’s area scales with the square of time, giving $s \propto t^2$. Once you see motion as “area under a rate,” you can handle any motion—constant, changing, or even irregular—by reasoning about shapes, slopes, and sums.