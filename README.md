# Hypertrophic Cardiomyopathy Drug Discovery Project

Hypertrophic cardiomyopathy (HCM) is a medical condition characterized by the thickening of the heart muscle, making it difficult for the heart to pump blood effectively. This condition is often undiagnosed and can lead to serious health complications. Genetic mutations, particularly in genes such as MYH7, MYBPC3, TNNT2, and TNNI3, are known to be associated with hypertrophic cardiomyopathy.

## Project Focus

This project primarily focuses on computational drug discovery methods targeting the TNNI3 gene. The aim is to identify potential therapeutic compounds that can alleviate the symptoms of hypertrophic cardiomyopathy. The project involves filtering data based on IC50 standard values, performing data pre-processing, calculating Lipinski parameters, conducting chemical space analysis, and building predictive models using machine learning algorithms.

## Implementation Details

- **Target Search:** The project begins with identifying the target gene TNNI3 and gathering relevant data associated with it.
- **Data Pre-processing:** Raw data is filtered based on IC50 standard values to obtain a refined dataset meeting the required criteria.
- **Lipinski Parameters:** Lipinski parameters, such as molecular weight, hydrogen bond donors, hydrogen bond acceptors, and lipophilicity, are calculated to assess the drug-likeness of compounds.
- **Chemical Space Analysis:** Visualization techniques, using tools like seaborn and matplotlib, are employed to analyze the chemical space of the dataset and identify potential lead compounds.
- **Model Building:** The RandomForest machine learning algorithm is utilized to build predictive models comparing predicted pIC50 values (-log10(IC50)) with experimental pIC50 values.

## Tools Used

- **Python:** The project is implemented in Python programming language, leveraging its extensive libraries and frameworks for data analysis and machine learning.
- **Padel:** Padel (padel-descriptors) tool is used to calculate molecular descriptors necessary for drug-likeness assessment.
- **Seaborn and Matplotlib:** These Python visualization libraries are utilized to create insightful visualizations of the chemical space and model predictions.

## Sample Output

The output of the project includes predictive models comparing the predicted and experimental pIC50 values, providing insights into the efficacy of potential therapeutic compounds targeting the TNNI3 gene in hypertrophic cardiomyopathy treatment.

## Conclusion

The Hypertrophic Cardiomyopathy Drug Discovery Project demonstrates the application of computational drug discovery methods in identifying potential therapeutic compounds for treating hypertrophic cardiomyopathy. By leveraging data analysis techniques, molecular descriptors calculation, and machine learning algorithms, this project contributes to the ongoing efforts in drug discovery and personalized medicine.

For further insights and understanding, explore the code and experiment with different datasets and machine learning algorithms. Happy drug discovery journey!
