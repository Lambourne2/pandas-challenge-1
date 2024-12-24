# Data Analysis Project

**Author:** Peyton Lambourne  

This project focuses on exploring, transforming, and analyzing a dataset while confirming specific results and summarizing findings. Below are the details of the requirements for the project:

---

## Requirements

### Part 1: Explore the Data (30 points)
1. View the column names. (4 points)
2. Use the `describe` function. (4 points)
3. Correctly identify the category with the most entries. (4 points)
4. For the category with the most entries, correctly identify the subcategory with the most entries. (5 points)
5. Correctly identify the 5 clients with the most entries in the data. (5 points)
6. Store the client IDs of those top 5 clients in a list. (4 points)
7. Display the total units (from the `qty` column) that the client with the most entries ordered. (4 points)

### Part 2: Transform the Data (30 points)
1. Create a column that calculates the subtotal for each line using `unit_price` and `qty`. (6 points)
2. Create a column for shipping price:
   - Assume a shipping price of $7 per pound for orders over 50 pounds.
   - Assume a shipping price of $10 per pound for orders 50 pounds or under. (6 points)
3. Create a column for the total price using the subtotal and the shipping price, including a sales tax of 9.25%. (6 points)
4. Create a column for the cost of each line using `unit_cost`, `qty`, and `shipping price`. Assume the shipping cost is exactly what is charged to the client. (6 points)
5. Create a column for the profit of each line using the line cost and line price. (6 points)

### Part 3: Confirm Your Work (15 points)
1. Confirm that `Order ID 2742071` had a total price of $152,811.89. (5 points)
2. Confirm that `Order ID 2173913` had a total price of $162,388.71. (5 points)
3. Confirm that `Order ID 6128929` had a total price of $923,441.25. (5 points)

### Part 4: Summarize and Analyze (25 points)
1. Calculate the total revenue from each of the top 5 clients in Part 1. (5 points)
2. Create a summary DataFrame showing totals for the top 5 clients with the following information:
   - Total units purchased
   - Total shipping price
   - Total revenue
   - Total profit (5 points)
3. Create a function to change the currency to millions of dollars. Format the data, rename columns for presentation, and sort the DataFrame in descending order by total profits. (5 points)
4. Write a brief 2-3 sentence summary of your findings. (10 points)

---

### Summary of my findings:

My analysis revealed that "our" top client generated a profit exceeding ten times that of the next highest client. Additionally, the revenue exhibited a gradual decline across the remaining clients. Overall very interesting and a fun challenge!