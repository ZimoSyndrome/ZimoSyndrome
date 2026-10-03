<img src="assets/banner.svg" alt="" width="100%">

```python
def optimize_life(bugs: int, learning_rate: float = 0.01) -> str:
    caffeine_level = 100

    while bugs > 0:
        # Wandering through the loss landscape of life
        bugs -= 1
        caffeine_level -= 10

        if caffeine_level <= 0:
            return "Exploding Gradient Error: Go to sleep."

    return "Global Optimum Reached: Code compiles!"
```

When I'm not debugging: ultimate frisbee, and [a map of everywhere I've been](https://chenzimo.vercel.app/travel).
