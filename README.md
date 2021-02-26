# ih_datamadpt1120_project_m2
Module 2 Project for Data Analytics Ironhack Bootcamp

<p align="center">
  <img width="300" height="300" src="https://d92mrp7hetgfk.cloudfront.net/images/sites/misc/ironhack/original.jpg?1568082165">
</p>

## **ABOUT**

This project has the purpose to show an exploratory analysis about diamonds, its characteristhics and which ones influence in their price.:gem:

You will be able to see the analysis from a Jupyter Notebook and from the link to my Tableau Public Dashboard right here: [Tableau Public link](https://public.tableau.com/profile/emily.paz#!/vizhome/DashboardProject2IH/Dashboard1)

---

### **So... what influences the price of diamonds?**

<p align="center"><img src="https://cdn.dribbble.com/users/115601/screenshots/1995210/diamond.gif"></p>

Diamonds, as we know them today, are a symbol of elegance, sophistication, wealth, purity, even love. We know they have a great value and an important social significance, but ... what makes them so expensive?

The most common criteria that determine the quality of diamonds are the popular "4 C's":

__Carat__
Diamond weight. As we can see in our exploratory visualization, the carat of a diamond will be the most determining characteristic that influences the price of the diamonds. The heavier the diamond is, the price gets more expensive, since it's more difficult for crystallization to take in larger sizes, so that makes more complicated to find heavy diamonds. 

__Clarity__
Clarity is a scale of flawlessness when it's about inclusions. Inclusions are largely diamond crystals or foreign material that has formen within the stone and affects the internal composition. The categories we have in our sample, from better clarity to worse, is:
- __1.__ IF: flawless, no inclusions.
- __2 and 3.__ VVS1, VVS2: very very slightly included.
- __4 and 5.__ VS1, VS2: very slightly included.
- __6 and 7.__ SI1, SI2: slightly included.
- __8.__ I1: included.

If we compare the average price and the average carat related to clarity, we can see that the most expensive diamonds are slightly included, one of the worst clarity scales, but also these are the ones with greater average carat. The first clarity scale with the greatest average carat are the included, and the lowest is the VVS1 followed by IF, really near one from each other in both results. There are not big differences between the average prices, it is more noticeable when we look at the average carat visualization. When the clarity is better, the average weight of the diamonds decreases. 

__Color__
It's about the transparency of diamonds. The scale we have in our sample, from more transparency to less, is:

- __Colorless__: D, E, F.
- __Near Colorless__: G, H, I, J.

The difference of transparency between these categories of color are almost imperceivable, so we can find normal that the most expensive and heavier diamonds are the color J ones, lower quality of transparency make them affordable to get them. Perfection is difficult to find. In our exploratory visualizations, we can appreciate that the average price and the average carat increase in order of the lower quality of diamonds color. 

__Cut__
A good cut will determine the external beauty of a diamond. Diamonds can lose its value and brightness if is not cut properly. The categories of cuts we can see in our sample, from better to worse, are:
- Ideal.
- Premium.
- Very good.
- Good.
- Fair.

So, as we can see in our exploratory visualizations, there are no big differences between cuts. Again, this characteristic of diamonds is determined by the weight, but here we can appreciate that Premium and Fair cuts are almost matching in average price, being Premium's average carat lower than Fair's. Even though, as I've said before, the difference between categories of cuts are not big.

To find another characteristic that cloud influence to diamond prices, I compared the average price and average carat of diamonds by depth, but we could notice that the results of the bar chart are flat, so depth is not a determinant of the price. It will be usual that the depth's percentages are depending on the weight of diamonds. 

In our sample, the most expensive diamond have these characteristics:
- Carat: 2.29
- Cut: Premium
- Color: I (second worse)
- Clarity: VS2

And the cheapest (two with the same price):
- Carat: 0.21/0.23
- Cut: Premium/Ideal
- Color: E
- Clarity: SI1/SI2

We can notice that the cheaper diamonds have better quality than the most expensive one!! The big difference is found in the carat.

As a conclusion of our exploratory analysis about diamonds, definitely we can say that the most important C of the four is the carat, that will influence on the rest of the characteristics of the diamonds when we have to know its prices. Even thought, the difference of quality about the categories we have seen in our sample is not huge, so that could explain the importance of the carat here.
 
Despite everything, diamonds have a huge and interesting history in our society, and I dare to say that what influences prices the most, besides carat, is the offer and demand, the kind of object that includes the diamonds, how much diamonds it has, the popularity of the brand where you get it, where the diamonds come from (mines or made in laboratories), etc.

---

## :bug: **STATUS**
My goal is to get these insights improved as much as I learn more about diamonds and their characteristics, and be able to appreciate more curiousities to improve the exploratory analysis.

## :computer: **TECHNOLOGY STACK**
- Python :snake:
- Pandas :panda_face: 
- Matplotlib :bar_chart:
- Seaborn :ocean:
- Tableau :chart_with_downwards_trend:

## :open_file_folder: **FOLDER STRUCTURE**
```
└── project
    ├── data
    ├── .gitignore
    ├── README.md
    └── data_analysis_report.ipynb
```
    
### :mailbox_with_mail: CONTACT INFO

If you have any comments or questions please contact me! emilypaz3012@gmail.com
