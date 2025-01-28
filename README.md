# life_expectancy_regression

<center><h1>Motivation</h1></center>

<p>
    Although there have been lot of studies undertaken in the past on factors affecting life expectancy considering demographic variables, income composition and mortality rates, it was found that affect of immunization and human development index was not taken into account in the past. Also, some of the past research was done considering multiple linear regression based on data set of one year for all the countries. Hence, this gives motivation to resolve both the factors stated previously by formulating a regression model based on mixed effects model and multiple linear regression while considering data from a period of 2000 to 2015 for all the countries. For that, we are going to study a datased created with help of The Global Health Observatory (GHO), who keeps track of the health status as well as many other related factors for all countries. Therefore, we split this dataset into this parts:
</p>

<ol>
    <li>Importing libraries;</li>
    <li>Reading the dataset;</li>
    <li>Preparing the dataset:
        <ol>
            <li>Dtypes and null values:
                <ol>
                    <li>Removing unnecessary spaces from column names;</li>
                    <li>Removing unnecessary columns;</li>
                    <li>Removing rows with null values;</li>
                    <li>Transform object columns into binary;</li>
                </ol>
            </li>
            <li>Functions:
                <ol>
                    <li><code>comparing_histogramns</code>;</li>
                    <li><code>comparing_scatters</code>;</li>
                    <li><code>plot_bars</code>;</li>
                </ol>
            </li>
        </ol>
    </li>
    <li>Answering questions:
        <ol>
            <li>What are the predicting variables actually affecting the life expectancy?</li>
            <li>Should a country having a lower life expectancy value(<65) increase its healthcare expenditure in order to improve its average lifespan?</li>
            <li>How does Infant and Adult mortality rates affect life expectancy?</li>
            <li>Does Life Expectancy have positive or negative relationship with drinking alcohol?</li>
            <li>What is the impact of schooling on the lifespan of humans?</li>
            <li>Do densely populated countries tend to have lower life expectancy?</li>
        </ol>
    </li>
    <li>Cleaning the dataset;
        <ol>
            <li>Delete columns;</li>
            <li>Remove outliers;</li>
        </ol>
    </li>
    <li>Build a regression model;</li>
    <li>Chosing the model;</li>
    <li>Saving the model;</li>
</ol>

<h2>1. Importing libraries:</h2>
