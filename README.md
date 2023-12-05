Please refer: [My Project Collection](https://github.com/AswinBalamurugan/Machine_Learning_Projects/blob/main/README.md)

# Objective
* Use PINN to model reactions in a CSTR.
* The model should handle the complexities of the reactions and be robust enough to provide accurate predictions even in the face of uncertainties or changes in the system parameters.

# Brief Description
1. *Industrial Significance:*
   Chemical reactors, particularly Continuous Stirred-Tank Reactors (_CSTRs_), play a crucial role in various industrial processes. Despite their advantages in simplicity and efficiency, modelling the dynamic behaviour of CSTRs for reaction series poses challenges due to inherent nonlinearities and dynamic complexities.

2. *Assumptions:*
   The key assumptions to simplify and focus on the dynamic aspects of CSTRs are:
   * Unsteady state - outlet concentrations vary with time initially
   * Uniform mixing - concentration of species in the reactor is the same as its outlet concentration
   * Isothermal conditions - rate constants don't change with time

4. *Neural Networks:*
   The aim is to develop predictive models that capture intricate dynamics, paving the way for more efficient and accurate modelling in chemical engineering. Integrating domain knowledge and ML capabilities using Physics-Informed Neural Networks (_PINN_) aims to contribute to process control and optimisation advancements within the chemical engineering domain.

# Methodology
The project was split into different stages:
1. Data Generation
2. Creating a reference model (without *PINN*)
3. Simplifying dataset for better interpretation of results
4. Modelling *'flow rate'* varied dataset using *PINN*
5. Create the final model with *PINN*
   
*(The links have further explanation for each stage.)*

# Conclusion

1. *Comprehensive Neural Network Understanding:*
   I delved into various Neural Network concepts throughout this project, including activation functions, optimisers, and result interpretation. This foundational knowledge laid the groundwork for the subsequent incorporation of advanced concepts.

2. *Enhanced Learning with PINNs:*
   The successful integration of the Physics-Informed Neural Networks (PINNs) loss concept was a significant achievement. This enhancement facilitated better learning for the model and contributed to its robustness in handling the complexities of dynamic CSTR systems.

3. *Model Application and Future Scalability:*
   The trained model showcases its capability to predict output concentrations of species in an unsteady state within an ideal CSTR. Hyper-parameter tuning and incorporating additional data could further enhance the model's scalability, making it suitable for deployment at an industry level.




