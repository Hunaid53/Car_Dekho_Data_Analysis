# Car_Dekho_Data_Analysis

This repository contains Python scripts for analyzing a dataset of vehicle sales. The scripts use the pandas library to perform various analyses on the dataset.

## Dataset

The dataset used in these scripts includes the following columns: Car_Name, Year, Selling_Price, Present_Price, Kms_Driven, Fuel_Type, Seller_Type, Transmission, Owner.

## Analyses

The scripts perform the following analyses:
1. Counting the number of different vehicles in the dataset.<br>
2. Finding the most and least sold vehicles.<br>
3. Calculating the depreciation of each vehicle and identifying the vehicles with the most and least depreciation.<br>
4. Identifying the brands of vehicles that are less affected by cost depreciation.<br>
5. Filtering the dataset to only include vehicles manufactured after a certain year.<br>
6. Sorting the dataset by the ‘Year’ column to find the oldest and newest cars sold.<br>
7. Calculating the difference between the selling price and the present price of each vehicle to identify good deals.<br>

## Dependencies

The scripts require Python 3 and the following Python libraries installed:
<ul>
  <li>pandas</li>
</ul>

You can install these dependencies using pip:
```bash
pip install pandas
```

## Usage

To run the script, you’ll need to replace 'your_dataset.csv' in the script with the path to your actual dataset file.

For example, if your dataset file is located in the same directory as your script and is named 'car_data.csv', you would replace 'your_dataset.csv' with 'car_data.csv'.

Then, you can run the script using Python:
```bash
python script_name.py
```
Replace script_name.py with the name of the script you want to run.
