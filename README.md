
<!-- ABOUT THE PROJECT -->
## About The Project
myFitnesspal's premium "Export your Information" feature exports a CSV file of your progress meal data into 4 categories being Breakfast, Lunch, Dinner and Snacks. This converter is created to show the average of those 4 categories to add up towards the whole day to be able to see total Macronutrients and Micronutrients for the day or month instead of total Macronutrients and Micronutrients for Breakfast, Lunch, Dinner, and Snacks. 

This was created to be able to see the average Macronutrients and Micronutrients including vitamins and other data pieces as a whole per day or month in a CSV instead of the total being split up. Seeing this data as a whole helps understand progress better and allows for better visualization and data analysis depending on the use case.


![converter](https://i.gyazo.com/8fc6817903d664ce945f75f2744d6d99.png)
![converterday](https://i.gyazo.com/ba7a3ed0c244dc6fc0904eb1111c28dd.png)

### Built With

* [VSCode](https://code.visualstudio.com/download) 
* [Python](https://www.python.org/downloads/) 
* [Pandas Python Library](https://pandas.pydata.org/)
* [Jupyter Notebook](https://jupyter.org/install/)



<!-- GETTING STARTED -->
## Getting Started

This is an example on setting up an environment on your computer even for a non-programmer who wishes to have a better view of their progress on myFitnesspal and wants to convert their data that they have exported into totals per day/month.

\n - Install everything under the "Built With" section
- Open the file Nutrition.ipynb with VSCode
- Replace "Insert-Here.csv" with the name of your exported myFitnesspal CSV file that you emailed to yourself (Make sure Nutrition.ipynb and your .csv are in the same location/folder)
- Click Run All (Runs all code) 
- Check desktop for converted CSV files (myFitnesspal_avgbyday.csv) is averages by day and (myFitnesspal_avgbymonth.csv) is averages by month

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request
