# Genetic_Algo_Projects

## Genetic Algorithm
* Search-based optimization technique.
* Based on natural selection and genetics.
* Simulate “survival of the fittest”

### Rules:
* **Selection rules** prefers to the individuals with good fitness scores and allow them to pass there genes to the successive generations.
* **Crossover rules** combine two parents to form children for the next generation.
* **Mutation rules** apply random changes to individual parents to form children.

## Projects:
1. Coded a genetic algorithm that generates a sentence similar to original sentence based on fitness function to understand the working and effects of tweaking various parameters.
2. Developed a genetic algorithm that generates different bottle shapes by altering pixel values.
3. Developed a genetic algorithm that generates different bottle shapes by altering the vectors values.

    **GENRATING BOTTLE BY ALTERING VECTOR**

   ### Fitness function
    * Compares the population with the original image and calculates the fitness 
score. 
    * We are Calculating the difference in population member dimensions and actual dimensions, subtracting it from canvas size to get score.

    * ` fit=fit+(canvas_size-abs(member[i][0]-p[i-1][0])+canvas_size-abs(member[i][1]-p[i-1][1]))`

   ### Cross breed:
    * This function will take two members from population as input and generate two new offsprings using combination of both members.

   ### Mutate
    * To maintain genetic diversity from one generation of a population of genetic algorithm to the next we are altering one random point, replacing it with one random value.

   ### Original Image
    ![/blob](https://github.com/shakshisinghai/Genetic_Algo_Projects/blob/master/Images/Original.PNG "Original Image")

   ### Bottle Shapes after generations:
    ![Generation: 37](https://github.com/shakshisinghai/Genetic_Algo_Projects/blob/master/Images/37.PNG?raw=true "Generation: 37")

    ![Generation: 42](https://github.com/shakshisinghai/Genetic_Algo_Projects/blob/master/Images/42.PNG "Generation: 42")

    ![Generation: 46](https://github.com/shakshisinghai/Genetic_Algo_Projects/blob/master/Images/46.PNG "Generation: 46") 

    ![Generation: 55](https://github.com/shakshisinghai/Genetic_Algo_Projects/blob/master/Images/55.PNG "Generation: 55")

    ![Generation: 108](https://github.com/shakshisinghai/Genetic_Algo_Projects/blob/master/Images/188.PNG "Generation: 198")

    ![Generation: 503](https://github.com/shakshisinghai/Genetic_Algo_Projects/blob/master/Images/503.PNG "Generation: 503")

    ![Generation: 645](https://github.com/shakshisinghai/Genetic_Algo_Projects/blob/master/Images/645.PNG "Generation: 645")


