# Big-Query-Assignment
Business Analytics Assignment
CODE NO.1
SELECT * FROM `bigquery-public-data.census_bureau_international.mortality_life_expectancy` LIMIT 5
CODE NO.2
SELECT year as year FROM `bigquery-public-data.census_bureau_international.mortality_life_expectancy` LIMIT 5
CODE 3
SELECT avg(infant_mortality) FROM `bigquery-public-data.census_bureau_international.mortality_life_expectancy` LIMIT 5
CODE 4
SELECT max(mortality_rate_1to4) FROM `bigquery-public-data.census_bureau_international.mortality_life_expectancy` LIMIT 5
CODE 5
SELECT sum(life_expectancy) FROM `bigquery-public-data.census_bureau_international.mortality_life_expectancy` LIMIT 5
CODE 6
SELECT COUNT(life_expectancy) FROM `bigquery-public-data.census_bureau_international.mortality_life_expectancy` LIMIT 5
CODE 7
SELECT SUM(life_expectancy) FROM `bigquery-public-data.census_bureau_international.mortality_life_expectancy` 
WHERE year > 1981
LIMIT 5
