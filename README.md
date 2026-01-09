# Genesis

**Evolution Simulator**

Watch natural selection unfold in real-time. Creatures with unique genetic traits compete for survival - the fit reproduce, the weak perish.

## [Live Demo](https://matthewpdingle.github.io/genesis/)

## How It Works

Creatures have **5 genetic traits** encoded in their DNA:
- **Speed** - How fast they move (costs more energy)
- **Size** - Physical size (larger = more energy to maintain, but can eat smaller creatures)
- **Sense Range** - How far they can detect food/prey
- **Diet** - Herbivore (0) to Carnivore (1) spectrum
- **Efficiency** - How well they convert food to energy

### Diet Types
| Type | Color | Behavior |
|------|-------|----------|
| Herbivore | Green | Eats plants only |
| Omnivore | Yellow | Eats plants and smaller creatures |
| Carnivore | Red | Hunts other creatures |

### The Cycle of Life
1. Creatures lose energy over time (more if larger/faster)
2. They must eat to survive
3. When energy is high enough, they reproduce asexually
4. Offspring inherit genes with random mutations
5. Creatures with 0 energy die

**Natural selection** determines which traits survive across generations.

## Controls

| Key | Action |
|-----|--------|
| `Space` | Pause / Resume |
| `,` | Slow down |
| `.` | Speed up |
| `R` | Reset simulation |
| `Click` | Inspect creature genetics |

## Parameters

Adjust in real-time:
- **Mutation Rate** - How often genes mutate during reproduction
- **Food Spawn Rate** - How quickly plants appear
- **Initial Creatures** - Starting population
- **Energy Drain** - Base metabolism rate

## What to Watch For

- **Extinction events** - Species dying out (carnivores often go first)
- **Omnivore dominance** - Flexible diet usually wins
- **Size/speed tradeoffs** - Can't be big AND fast
- **Boom/bust cycles** - Population explosions followed by crashes
- **Emergent behaviors** - Creatures clustering around food

## Usage

Open `index.html` in any modern browser. No dependencies required.

```bash
# Or serve locally
python3 -m http.server 8080
# Open http://localhost:8080
```

## License

MIT

---

*Created with Claude Opus 4.5*
