# Car Evaluation Dataset

This repository contains the Car Evaluation dataset, which was donated on 5/31/1997. The dataset is derived from a simple hierarchical decision model and may be useful for testing constructive induction and structure discovery methods.

## Dataset Characteristics

- **Type**: Multivariate
- **Subject Area**: Other
- **Associated Tasks**: Classification
- **Feature Type**: Categorical
- **Number of Instances**: 1728
- **Number of Features**: 6

## Dataset Information

The Car Evaluation Database was derived from a simple hierarchical decision model originally developed for the demonstration of DEX. The model evaluates cars according to the following concept structure:

- **CAR**: car acceptability
  - **PRICE**: overall price
    - **buying**: buying price
    - **maint**: price of the maintenance
  - **TECH**: technical characteristics
    - **COMFORT**: comfort
      - **doors**: number of doors
      - **persons**: capacity in terms of persons to carry
      - **lug_boot**: the size of luggage boot
    - **safety**: estimated safety of the car

Input attributes are in lowercase. Besides the target concept (CAR), the model includes three intermediate concepts: PRICE, TECH, and COMFORT. Each concept is related to its lower-level descendants by a set of examples.

The Car Evaluation Database contains examples with the structural information removed, directly relating CAR to the six input attributes: buying, maint, doors, persons, lug_boot, and safety.

Due to its known underlying concept structure, this database may be particularly useful for testing constructive induction and structure discovery methods.

- **Missing Values**: No

## References

- M. Bohanec, V. Rajkovic: Expert system for decision making. Sistemica 1(1), pp. 145-157, 1990.
- For more information on the original model and example sets, visit: [DEX Car Model](http://www-ai.ijs.si/BlazZupan/car.html).

## Usage

You can find the `Car_Evaluation.ipynb` notebook in this repository, which contains the analysis and use of the Car Evaluation dataset.

## License

This dataset is available for public use. Please refer to the original publication for citation.

