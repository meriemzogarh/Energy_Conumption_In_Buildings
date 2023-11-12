# Energy_Consumption_In_Buildings
This repository contains the code and documentation for a research project that successfully explored the integration of CUDA, Particle Swarm Optimization (PSO) algorithm, and neural networks for predicting energy expenditures in buildings. The primary objective was to investigate how CUDA, as a powerful hardware acceleration resource, can enhance the performance of machine learning models, specifically in the context of energy data analysis.

## Key Findings

### CUDA Acceleration: 
The integration of CUDA significantly accelerated both the training and execution of the neural network model. This resulted in a substantial performance improvement compared to a CPU-based implementation. The accelerated computation played a crucial role in reducing calculation times, making it essential for real-time applications or large-scale data analyses.

### PSO Optimization: 
The PSO algorithm played a crucial role in optimizing the neural network's parameters, thereby improving the accuracy of predictions. This optimization approach enabled the model to adapt more efficiently to the specifics of energy data, contributing to a better fit to the domain's realities.

## Usage
To replicate the results of this project, follow these steps:

#### Clone the Repository:

git clone https://github.com/meriemzogarh/Energy_Conumption_In_Buildings.git 

cd Energy_Conumption_In_Buildings

#### Install Dependencies:

pip install -r requirements.txt

Ensure that you have a compatible CUDA-enabled GPU for optimal performance.

## Results

The obtained results showcase the successful combination of CUDA, PSO, and neural networks for energy expenditure prediction in buildings. The accelerated hardware significantly improved training and execution times, and the PSO optimization contributed to enhanced prediction accuracy.

## Challenges and Considerations

It's important to note that optimizing machine learning projects with CUDA may pose challenges, particularly in terms of GPU memory management and synchronization. Thorough planning and a deep understanding of CUDA features are crucial to maximize its benefits.

## Future Developments

This project has paved the way for new opportunities in leveraging hardware acceleration, such as CUDA, in the field of machine learning applied to energy and buildings. The implications extend beyond energy expenditure prediction, offering potential applications in other domains requiring intensive parallel computing.
