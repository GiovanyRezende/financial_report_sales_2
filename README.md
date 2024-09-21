# Power BI Report in Financial Sales
*This is a challenge of Data Engineering NTT DATA Bootcamp in [DIO](https://web.dio.me/).* It consists in creating a better report for Data Analysis in Power BI, using [the previous project](https://github.com/GiovanyRezende/financial_report_sales/).

## Theme Change
The theme was changed to dark backgrounds and a blue-palette.

## First Page
It's just an introduction, like a menu in a game.
![image](https://github.com/user-attachments/assets/86ac1312-6e5a-49e4-94bd-2f6da2ae4f90)

### Button
The button shows the first analysis of the report.

## Second Page
It's the first analysis. There's a first analysis and a KPI analysis.
![image](https://github.com/user-attachments/assets/ecd3ed33-dbd7-4858-8d6d-32c86b7630bd)
![image](https://github.com/user-attachments/assets/3dbd102e-43ab-4814-9c34-4dc628917560)

### Second Page Buttons
There's two buttons for page changing. The ```KPI``` button shows KPI analysis, while ```Data``` shows frist analysis.

### First Analysis Buttons
The ```Segment``` button shows the sales chart by segment, while the ```Country``` shows the sales by country.

### KPI Analysis
The two KPIs are based in 130% of, respectively, average sales and average profit. The two goals were made with DAX:

```
sales_goal = AVERAGEX(Sheet1,[ Sales]) * 1.3
profit_goal = AVERAGEX(Sheet1,[Profit]) * 1.3
```
## Third Page
There weren't any important changes, only the main theme was changed and the superior bar was removed.
![image](https://github.com/user-attachments/assets/427bf52e-fb77-4b14-8255-3eb5585ffc87)

