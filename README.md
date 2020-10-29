# SQL Project
## Project specifications
> This project required going to **[SQL Zoo](https://sqlzoo.net/wiki/SQL_Tutorial)** I was to do the quizzes from Tutorials 0-

# Quiz 1

## Question 1
<img src="que1.png">
## Answer

## Question 2
Pick the result you would obtain from this code:
  
``SELECT name, population
      FROM world
      WHERE name LIKE "Al%" ``

## Answer
<img src='que2.png'>

## Question 3
Select the code which shows the countries that end in A or L

## Answer
``SELECT name FROM world
 WHERE name LIKE '%a' OR name LIKE '%l'``
## Question 4
 Pick the result from the query

 ``SELECT name,length(name)
FROM world
WHERE length(name)=5 and region='Europe'``

## Answer
<img alt='' src='que4.png'>

## Question 5

Pick the result you would obtain from this code:

``SELECT name, area*2 FROM world WHERE population = 64000``
## Answer
<img alt='' src='quiz5.png'>
 
 ## Question 6
  Select the code that would show the countries with an area larger than 50000 and a population smaller than 10000000
## Answer
``SELECT name, area, population
  FROM world
 WHERE area > 50000 AND population < 10000000``
## Question 7
Select the code that shows the population density of China, Australia, Nigeria and France

## Answer

 ``SELECT name, population/area
  FROM world
 WHERE name IN ('China', 'Nigeria', 'France', 'Australia')``


 
_______________________________


## 👨🏽‍💻 👨🏿‍💻
👤 **Github: [@ggotora](https://github.com/ggotora)**
👤 **Linkedin: [@ggotora](https://www.linkedin.com/in/gilbert-gotora/)**

## 🤝 Contributing

Contributions, issues and feature requests are welcome!

Feel free to check the [issues page](https://github.com/ggotora/SQL-Project).

## Show your support

Give a ⭐️ if you like this project!

## 📝 License

This project is [MIT](LICENSE) licensed.