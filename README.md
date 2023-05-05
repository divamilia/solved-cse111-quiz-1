Download Link: https://assignmentchef.com/product/solved-cse111-quiz-1
<br>
<strong>DATABASESYSTEMS</strong>

Quiz 1 (30 points)

Consider the following relational schema, provided as a SQLite database populated with sample data:

Product(maker, model, type)

PC(model, speed, ram, hd, price)

Laptop(model, speed, ram, hd, screen, price)

Printer(model, color, type, price)

Write SQL statements for the following queries (<strong>5 points each</strong>) in the given quiz-1.sql file:

<ol>

 <li>What makers produce color Printers cheaper than $120?</li>

 <li>What makers produce PCs but do not produce Laptops and Printers?</li>

 <li>For every maker that sells both PCs and Laptops, find the combination of PC and Laptop that hasmaximum price. Print the maker, the PC model, Laptop model, and the combination price (PC price + Laptop price).</li>

 <li>What Laptop screen sizes are offered in at least 2 different models?</li>

 <li>What Laptops are more expensive than all the PCs? Print the model and the price.</li>

 <li>What makers produce at least a PC or Laptop model and at least 2 Printer models?</li>

</ol>

We will grade your quiz by running the quiz-1.sql file on the given database and another database populated with different data. So, make sure your SQL statements are general. You should test that your code works without errors by running the command sqlite3 data.sqlite &lt; quiz-1.sql in the terminal. quiz-1.sql is the only file you have to turn in.