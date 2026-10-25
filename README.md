# Numalg_Final_Project_Genetic_Algorithm

# Genetic Algorithm Car Simulation 

**Authors:** Szabó Domonkos Sándor, Karácsonyi Milán  

This project is an evolution of a previous assignment. Instead of starting from scratch, we talked to Török János to allow us to take our old genetic algorithm (which simulates a car learning to drive around a track) and turn it into a testing ground. 

We aren't just trying to make a car finish a lap anymore, we are actively "playing" with the algorithm to understand what actually makes it tick, what makes it learn faster, and what makes it completely fail.

## What We Are Exploring
We are running a series of comparisons and experiments across several core areas of the simulation:

* **Different Pointing Systems:** How does the the car's behavior change if we reward pure speed versus rewarding safe, centered driving? We are tweaking the reward logic to see which pointing system creates the most efficient driver.
* **Genetic Models:** We are mixing up the evolutionary mechanics. We want to compare different selection methods, mutation rates, and crossover logic to see which "DNA" yields the most successful generations over time.
* **Track Variations:** An algorithm might overfit to a simple oval. What happens when we take a brain trained on an easy track and drop it into a complex circuit with hairpin turns? We are using different track geometries to test the adaptability of our models.
* **Parameter Tuning:** We are messing with the hidden numbers—population size, sensor ranges, generation limits—to find the absolute sweet spot between computational efficiency and driving performance. 

## The Goal
Building a working algorithm was step one. Step two is breaking it, tweaking it, and comparing the data to truly understand the mechanics behind evolutionary learning. By the end of this project, we'll have hard data showing exactly which configurations produce the best models.
