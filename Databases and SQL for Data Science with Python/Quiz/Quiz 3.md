# Quiz - Refining Your Results

1. You want to select author's last name from a table, but you only remember the author’s last name starts with the letter B, which string pattern can you use? 
- [ ] SELECT lastname from author where lastname like ‘B#’ 
- [x] SELECT lastname from author where lastname like ‘B%’ 
- [ ] SELECT lastname from author where lastname like ‘B$’ 
- [ ] None of the above 

2. In a SELECT statement, which SQL clause controls how the result set is displayed? 
- [x] ORDER BY clause 
- [ ] ORDER IN clause 
- [ ] ORDER WITH clause 

3. Which of the following can be used in a SELECT statement to restrict a result set? 
- [ ] HAVING 
- [ ] WHERE
- [ ] DISTINCT 
- [x] All of the above 

4. When querying a table called Author that contains a list of authors and their country of residence, which of the following queries will return the number of authors from each country?
- [x] SELECT Country, count(Country) FROM Author GROUP BY Country
- [ ] SELECT Distinct(Country) FROM Author 
- [ ] SELECT Country, count(Country) FROM Author
- [ ] SELECT Country, distinct(Country) FROM Author GROUP BY Country

5. You want to retrieve a list of books that have between 450 and 600 pages. Which clause would you add to the following SQL statement:  
SELECT Title, Pages FROM Book ________________________________  
- [ ] IF Pages >= 450 and Pages <= 600
- [x] WHERE Pages >= 450 and pages <= 600
- [ ] WHERE Pages 450 – 600
- [ ] WHERE Pages = 450
