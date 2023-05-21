# Pymaceuticals - Statistics concepts using python.
Pymaceuticals is a data visualization project that was developed using Pandas, Scipy, and Matplotlib. This project aimed to analyze and visualize drug testing results on mice.

![image](https://user-images.githubusercontent.com/124798004/232278733-2cd92fa7-ed95-4680-aeef-c05a594029e8.png)

"The above image shows a boxplot variation between tumour volume and 4 different drug medications"

This project was developed as part of the UWA Data Analytics Bootcamp course.
I have worked in collaboration with Anuja Yadwadkar to get the code results listed here.

Our first challenge was to remove duplicates from the dataset, which we achieved using Pandas' duplicate() and isin() functions. We then created summary statistic tables, which included the mean, median, variance, standard deviation, and standard error of the mean.
We visualize the data using two different plot options:
- Pandas with DataFrame.plot()
- Matplotlib with plt.plot()

![image](https://user-images.githubusercontent.com/124798004/232279928-6b5f004e-6c4a-4fc1-a271-6b9caedc87ae.png)

"The image above shows one of the bar chart created using Matplotlib."

In the final section of the project, we used Scipy and intermediate statistic concepts to create a box plot and scatter plot with a linear regression line. We created a loop to calculate the quartiles and identify any possible outliers. The box plot shows the variation in tumour volume for mice treated with four different drugs, while the scatter plot visualizes the correlation between tumour volume and mouse weight, along with a linear regression line.

![image](https://user-images.githubusercontent.com/124798004/232280529-290c97e0-cca5-4e38-a44e-792cb16a958c.png)
