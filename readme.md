![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# Lab | Global Superstore Dashboard in Looker Studio 

This lab serves as a hands-on application of the Looker Studio concepts covered in our previous lessons.

## Dataset Overview  

Using the Global Superstore dataset, you'll build a Looker Studio dashboard.  

You'll be working with:  
- `sample_superstore.xls` (included in drive datasets folder [here](https://docs.google.com/spreadsheets/d/1EKlKhvkqcG6DE4vhPuYg0G2neIU-EB08/edit?usp=sharing&ouid=103598963919852099637&rtpof=true&sd=true))  or in the [data folder in this repo](./data)

## Lab Requirements  

### Core Requirements (Must Complete)  

1. **Data Preparation**  
   - Connect the CSV file in Looker Studio  
   - Create 2 calculated fields:  
     - `Profit Margin` ([Profit]/[Sales])  
     - `Shipping Time` ([Ship Date] - [Order Date])  

2. **Dashboard Pages**  
   - **Executive Summary Page**:  
     - 3 Scorecards (Sales, Profit, Profit Margin)  
     - Time series chart of key metrics  
     - Date range control  
   - **Geographic Analysis Page**:  
     - Geo chart showing sales by State  
     - Bar chart of profit by City  
   - **Product Drill-Down Page**:  
     - Drill-down hierarchy (Category → Sub-Category → Product)  

3. **Interactivity**  
   - Add cross-filtering between all charts  
   - Include at least 2 filter controls (date + region)  

### Advanced Challenges (Bonus) 

- ⭐ Choose a Logo for the company  
- ⭐ Implement a custom theme using your organization's colors  
- ⭐ Add a dynamic title that updates with filter selections  
- ⭐ Create a "Top/Bottom N" table showing best/worst products  

## Deliverables

- `main.txt` file with a Shareable link to published version of your Looker Studio Dashboard.

## Submission

Upon completion, add your deliverables to git. Then commit git and push your branch to the remote.