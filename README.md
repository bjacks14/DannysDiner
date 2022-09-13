# Dannys Diner Case Study

![DannysDiner](https://user-images.githubusercontent.com/111879997/189985525-09a44fa4-fa8b-4734-a082-866d5307af2a.png)

## Introduction
Danny seriously loves Japanese food so in the beginning of 2021, he decides to embark upon a risky venture and opens up a cute little restaurant that sells his 3 favourite foods: sushi, curry and ramen.

Danny’s Diner is in need of your assistance to help the restaurant stay afloat - the restaurant has captured some very basic data from their few months of operation but have no idea how to use their data to help them run the business.

## Business Problem 
Danny wants to use the data to answer a few simple questions about his customers, especially about their visiting patterns, how much money they’ve spent and also which menu items are their favourite. Having this deeper connection with his customers will help him deliver a better and more personalised experience for his loyal customers.

He plans on using these insights to help him decide whether he should expand the existing customer loyalty program - additionally he needs help to generate some basic datasets so his team can easily inspect the data without needing to use SQL.

## Datasets

![DannysDinerData](https://user-images.githubusercontent.com/111879997/189985891-14fa2685-57bd-4c20-bb50-fdb2896b3a4c.png)

## Question 1

### What is the total amount each customer spent at the restaurant?

<img width="410" alt="Screen Shot 2022-09-13 at 2 59 33 PM" src="https://user-images.githubusercontent.com/111879997/189987601-810cca01-cd2c-4791-8906-4272fb23f35b.png">


<img width="396" alt="Screen Shot 2022-09-13 at 2 55 49 PM" src="https://user-images.githubusercontent.com/111879997/189987148-39c38438-9d44-41c2-8131-593ab3bcc300.png">

#### Customer A spent $76, customer B spent $74, and customer C spent $36.

## Question 2

### How many days has each customer visited the restaurant?

<img width="484" alt="Screen Shot 2022-09-13 at 3 07 06 PM" src="https://user-images.githubusercontent.com/111879997/189988767-3f9adfdc-260f-4143-8661-9774977389b6.png">

<img width="339" alt="Screen Shot 2022-09-13 at 3 10 04 PM" src="https://user-images.githubusercontent.com/111879997/189989201-7102bb1a-b335-4955-914e-f803d85b8e3e.png">

#### Customer A visited the restaurant 4 times, Customer B visited the restaurant 6 times, and Customer C visited the restaurant twice. 

## Question 3

### What was the first item from the menu purchased by each customer?

<img width="574" alt="Screen Shot 2022-09-13 at 3 12 51 PM" src="https://user-images.githubusercontent.com/111879997/189989696-7a2eea6f-fcc5-4d43-a409-6a738ad9424c.png">

<img width="630" alt="Screen Shot 2022-09-13 at 3 40 16 PM" src="https://user-images.githubusercontent.com/111879997/189994277-d785de8a-0c74-459b-b733-efe168c7c662.png">

On the first visit, Customer A ordered both Curry and Sushi while Customer B ordered Curry and Customer C ordered Ramen.

## Question 4

### What is the most purchased item on the menu and how many times was it purchased by all customers?

<img width="590" alt="Screen Shot 2022-09-13 at 3 15 58 PM" src="https://user-images.githubusercontent.com/111879997/189990215-9ef92cb5-f469-4f2b-9292-d8976fbe4f80.png">

<img width="658" alt="Screen Shot 2022-09-13 at 3 16 51 PM" src="https://user-images.githubusercontent.com/111879997/189990328-8ccb509e-e279-47a5-b280-64b6cb6b3b30.png">

The most purchased item on the menu overall was Ramen as it had 8 total purchases. Both Customers A and C purchased Ramen 3 times while Customer B purchased Ramen twice.

## Question 5

### Which item was the most popular for each customer?

<img width="1001" alt="Screen Shot 2022-09-13 at 3 19 19 PM" src="https://user-images.githubusercontent.com/111879997/189990739-cd06a22d-ad8a-4db3-a9c3-3a0dafb5b6b1.png">

<img width="604" alt="Screen Shot 2022-09-13 at 3 21 03 PM" src="https://user-images.githubusercontent.com/111879997/189991010-9d7773ec-5526-4b52-96f0-1462e4405860.png">

Both Customer A and C's most purchased menu item was Ramen. Customer B purchased all 3 menu items an equal number of times.

## Question 6

### Which item was purchased first by the customer after they became a member?

<img width="965" alt="Screen Shot 2022-09-13 at 3 23 39 PM" src="https://user-images.githubusercontent.com/111879997/189991465-5aaac2cb-d8fd-4e3a-bc31-4ae3bdf59c36.png">

<img width="602" alt="Screen Shot 2022-09-13 at 3 24 54 PM" src="https://user-images.githubusercontent.com/111879997/189991675-6ff09555-4bd8-4b9d-a669-4dda96d958d5.png">

After becoming a member, Customer A's first purchase was Ramen while Customer B's first purchase was Sushi.

## Question 7

### Which item was purchased just before the customer became a member?

<img width="973" alt="Screen Shot 2022-09-13 at 3 26 20 PM" src="https://user-images.githubusercontent.com/111879997/189991968-27e8530a-4b9a-44e0-a98f-a71e1942915f.png">

<img width="599" alt="Screen Shot 2022-09-13 at 3 27 16 PM" src="https://user-images.githubusercontent.com/111879997/189992091-3d0122cf-17b7-4e5b-adff-a37bc97b7446.png">

Before becoming a member, Customer A purchased both Sushi and Curry while Customer B only purchased Sushi.

## Question 8

### What is the total items and amount spent for each member before they became a member?

<img width="675" alt="Screen Shot 2022-09-13 at 3 28 42 PM" src="https://user-images.githubusercontent.com/111879997/189992359-1b1a4913-81b5-45e5-a8c3-ebd6a65b390e.png">

<img width="400" alt="Screen Shot 2022-09-13 at 3 29 32 PM" src="https://user-images.githubusercontent.com/111879997/189992475-3ceebe40-127a-4506-88c6-3f1bf24ff3e5.png">

Before becoming a member, Customer A purchased 2 items and spent $25 total. Customer B purchased 3 items and spent $40 prior to becoming a member.

## Question 9

### If each $1 spent equates to 10 points and sushi has a 2x points multiplier - how many points would each customer have?

<img width="384" alt="Screen Shot 2022-09-13 at 3 31 16 PM" src="https://user-images.githubusercontent.com/111879997/189992790-7b38192f-bf5e-49ef-88b3-14f07cd1126b.png">

<img width="367" alt="Screen Shot 2022-09-13 at 3 31 53 PM" src="https://user-images.githubusercontent.com/111879997/189992929-b4ccecfd-16db-4f3f-8ae0-7aca25ad0d49.png">

Customer A would have 860 points, Customer B would have 940 points, and Customer C would have 360 points. 

## Question 10

### In the first week after a customer joins the program (including their join date) they earn 2x points on all items, not just sushi - how many points do customer A and B have at the end of January?

<img width="929" alt="Screen Shot 2022-09-13 at 3 36 12 PM" src="https://user-images.githubusercontent.com/111879997/189993681-b9599caa-8599-4674-b833-edc1d375a2e9.png">

<img width="301" alt="Screen Shot 2022-09-13 at 3 37 11 PM" src="https://user-images.githubusercontent.com/111879997/189993824-604b4840-2b44-4b01-9fa7-9067bab1ac0b.png">

After the first week, Customer A would have 1,370 points while Customer B would have 820 points.





