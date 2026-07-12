### 🎯 Step 1 — Prior probabilities P(C1),P(C2),P(C3)
Before Monty opens any door, the car is equally likely to be behind any of the three doors.
There is no information yet, so:
P(C1)=P(C2)=P(C3)=13

This is pure symmetry: one car, three doors.

### 🎯 Step 2 — Conditional probabilities P(D3∣Cj)

This means:
“If the car is behind door j, what is the probability that Monty opens door 3?”

To compute this, we use Monty’s rules:
1. Monty never opens the door with the car
2. Monty never opens the door you picked (Door 1)
3. If Monty has two valid doors, he chooses randomly
4. If Monty has only one valid door, he must open it

Let’s analyze each case.

### ⭐ Case 1 — Car behind Door 1 → C1
You picked Door 1.
Monty cannot open Door 1 (your choice).
Monty cannot open Door 1 because it has the car.

So Monty chooses between:
* Door 2
* Door 3

Both contain goats.

He chooses randomly:
P(D3∣C1) = 1/2

### ⭐ Case 2 — Car behind Door 2 → C2
You picked Door 1.
Monty cannot open Door 1 (your choice).
Monty cannot open Door 2 (car behind it).

So Monty has only one option:
* Door 3

Thus:
P(D3∣C2) = 1

### ⭐ Case 3 — Car behind Door 3 → C3
You picked Door 1.
Monty cannot open Door 1 (your choice).
Monty cannot open Door 3 (car behind it).

So Monty must open:
* Door 2

Thus:
P(D3∣C3) = 0

### ⭐ Final results (reduced fractions)
Probability	Value

| Probability | Value |
|-------------|-------|
| P(C1)       | 1/3   |
| P(C2)       | 1/3   |
| P(C3)       | 1/3   |
| P(D3 ∣ C1)  | 1/2   |
| P(D3 ∣ C2)  | 1     |
| P(D3 ∣ C3)  | 0     |