# DVD Project: Analyzing Delay and Leakage Characteristics Across Technology Nodes

## Overview
This project, undertaken by Mayank Shivhare, Ashish Chokhani, Vedant Nipane, and Pronoy Patra, under the Department of Electronics and Communication Engineering at the International Institute of Information Technology, Hyderabad, India, focuses on analyzing delay and leakage characteristics across technology nodes using a machine learning approach.

## Abstract
The report outlines the process of generating datasets crucial for training regression-based machine learning models, which serve as the foundation for Project-2. This dataset generation process involves two main components: 
1. **Creation of Process, Voltage, and Temperature (PVT) combinations:** Sampling from predetermined distributions.
2. **Utilization of PVT combinations to simulate circuits:** Static Leakage power and Propagation delay are treated as target variables.

## Contents
1. **Dataset Generation**: Details on how the datasets were generated, including the sampling process and circuit simulation.
2. **Data Analysis**: Examination of the generated dataset to understand its characteristics and underlying patterns.
3. **Machine Learning Model**: Description of the proposed machine learning model aimed at efficiently estimating circuit leakage and delay based on input values.
4. **Contributors**: Information about the contributors to this project.

## Structure
- [Generation files](Generation%20files)
  - [temp_cqload.ipynb](Generation%20files/temp_cqload.ipynb)
  - [16 nm HP](Generation%20files/16%20nm%20HP)
    - [generate.ipynb](Generation%20files/16%20nm%20HP/generate.ipynb)
    - [main.ipynb](Generation%20files/16%20nm%20HP/main.ipynb)
  - [22 nm HP (and MGK)](Generation%20files/22%20nm%20HP%20(and%20MGK))
    - [generate.ipynb](Generation%20files/22%20nm%20HP%20(and%20MGK)/generate.ipynb)
    - [main.ipynb](Generation%20files/22%20nm%20HP%20(and%20MGK)/main.ipynb)
  - [32 nm HP (and MGK)](Generation%20files/32%20nm%20HP%20(and%20MGK))
    - [generate.ipynb](Generation%20files/32%20nm%20HP%20(and%20MGK)/generate.ipynb)
    - [main.ipynb](Generation%20files/32%20nm%20HP%20(and%20MGK)/main.ipynb)
  - [45 nm HP (and MGK)](Generation%20files/45%20nm%20HP%20(and%20MGK))
    - [generate.ipynb](Generation%20files/45%20nm%20HP%20(and%20MGK)/generate.ipynb)
    - [main.ipynb](Generation%20files/45%20nm%20HP%20(and%20MGK)/main.ipynb)
- [Data Analysis](Data%20Analysis)
- [Docs](Docs)
- [Report](Report)

## Contributors
- Mayank Shivhare: mayank.shivhare@students.iiit.ac.in
- Ashish Chokhani: ashish.chokhani@students.iiit.ac.in
- Vedant Nipane: vedant.nipane@students.iiit.ac.in
- Pronoy Patra: pronoy.patra@research.iiit.ac.in

## Dataset - [Link to the dataset](https://iiitaphyd-my.sharepoint.com/:f:/g/personal/vedant_nipane_students_iiit_ac_in/EkZc0Ok1BW5Csao8A986lEgB3eLN6N-yG0ZXYla7LgDZow?e=UN33h1)

## License
This project is licensed under the [MIT License](LICENSE).
