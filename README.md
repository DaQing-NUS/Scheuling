# Scheuling

This project is done using SimPy package in python.

Assume a factory-based environment, where there are multiple types of products and multiple types of machines. We randomly generate and pre-define the number of products and number of machines for each type of machine. The production sequences for each product are also randomly generated. 

Suppose that the production sequence for Product Type 0 is [2,3,8,15,17] (just for an example)
Flow Shop Scheduling: The product needs to go through Machine Type 2, Mahine Type 3, Machine Type 8, Machine Type 15, Machine Type 17 in strict order.
Job Shop Scheduling: The product need to go through these mentioned machines but no need to go through them in strict order. For instance, if there's a long waiting line for Machine Type 2, then this product can skip Machine Type 2 and go to Machine type 3 first, then go back to Machine Type 2 later in the process.

About "match" or "mismatch" in the file's name, It suggests whether the "supply and demand" between machines and products are matched or not. When some certain types of machine are greatly in need while short in numbers, it's "mismatched". Otherwise, it's "matched".

The evaluation criteria for job shop or flow shop, "match" or "mismatch" are overall makespan, machine's occupation rate and product's block rate, etc.
