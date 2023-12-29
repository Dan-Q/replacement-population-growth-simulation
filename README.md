# Replacement Population Growth Simulation

It's widely-believed that a "replacement-rate" of population (of 2 children per couple, i.e. 1 child per person) results in a stable total population. However, this isn't true in a population whose life expectancy is increasing, because each successive generation will - after having children - be around for longer than their predecessors.

This is a JavaScript simulation to demonstrate this phenomenon.

## Usage

Open `index.html` in a web browser of your choice. A random population of 100 individuals, with ages spread across a skewed Gaussian distribution, will be generated (you can press <kbd>Reset</kbd> to get a new one at any time). Press <kbd>Play/pause</kbd> to begin the simulation.

The population will age. Each person will spawn exactly one child when the parent reaches a randomly-selected age (with a probability represented as a bell curve between the ages of 20 and 30). Each person will die exactly when they exceed the life expectancy, which begins at 70.

Let the simulation run for a while: you can change the speed using the <kbd>Faster</kbd> and <kbd>Slower</kbd> buttons. To begin with, you will see generational "waves", but random factors will flatten this out over time. The "Highest population" and "Lowest population" will stabilise.

Now, try hitting the <kbd>Increase life expectancy</kbd> button a few times so that people live longer. You'll probably see the population increase, pushing up the "Highest population" to a never-before-seen level (if you don't, it's probably a rare random quirk of your population: reset and try again!). The population has increased despite the birth rate still being at "replacement" levels, on account of increasing life expectancy.
