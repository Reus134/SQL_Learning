-- USE sql_store;
#select的语法 select * from customers 从sql_store里面*(代表所有列)寻找customer
#从cusromer中选择 last_name和first_name
#points+10会直接+10
-- SELECT 
#      last_name,
#      first_name,
#      points,
#     (points+10)*100 AS discount_factor  #AS
#FROM customers

#SELECT DISTINCT state 唯一的state DISTINCT关键字可以删除重复项
#From customers
-- WHERE customer_id=1
-- order by first_name#用firstname来排序
