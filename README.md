# Medical Trial Dataset Analysis
**This project was inspired by the [Kaggle Medical Trial Dataset](https://www.kaggle.com/datasets/taweilo/medical-trial-dataset).**
## Project Overview
This project analyzes the usage of Medication A and Medication B in a trial conducted by an XYZ client. The goal is to evaluate the effectiveness of Medication B compared to Medication A, which is currently being used for all patients. The dataset includes approximately 130 patients and tracks data from 2 months before the switch to Medication B and up to 3 months afterward. 

## Key Considerations:
- Patients can be on either Medication A or Medication B, but not both simultaneously.
- Medication B is administered less frequently (~1 time per month) compared to Medication A.
- The dosage units for Medication A and Medication B are different and cannot be directly converted.
- A month is assumed to be 4.33 weeks, and a week is defined as 7 days.

**For more details on the dataset and to download the dataset files, you can check the Medical Trial Dataset on Kaggle.**

## Questions addressed:
1. Total Monthly Medication Usage: What is the total number of units administered for each medication in each month across all patients?
2. Patient Counts on Each Medication: How many patients received Medication A and Medication B from July to November?
3. Average Monthly Dose per Patient: What is the average total monthly dose per patient for each medication from July to November?
4. Medication Switch: How many patients switched from Medication A to Medication B in each month September, October and November?
5. Patients Starting on Medication B: How many patients started on Medication B without being on Medication A in the past in September, October and November?

## License
This project is licensed under the MIT License.

## Contributing
Contributions are welcome! Please fork the repository and create a pull request for any changes or improvements you would like to make.

---
