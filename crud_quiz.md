# CRUD Quiz

Use the solution to this afternoon's Property Tracker lab to answer the following questions. Please write your answers under each question, push the file to GitHub, and submit in the usual way.

## MVP Questions

In our Property Tracker application:

Q1. Where are we instantiating instances of the `Property` class?

#console.rb


Q2. Where are we defining the SQL that enables us to save the ruby `Property` object into the database?
#property.rb

Q3. In console.rb, which lines modify the database?
#fx property1.save()

Q4. Why do we not define the id of a `Property` object at the point we instantiate it (‘new it up’)?
#Databases gives id automatically

Q5. Where and how do we assign the id (that is generated by the database) to the ruby `Property` object?
#property.rb

Q6. Why do we put a guard (an `if` clause) on the `@id` attribute in the constructor?
#prevent NIL returning

Q7. Why are some of the CRUD actions represented by instance methods, and others by class methods?
#class methods action exectuted in the whole table.     instance methods action exectuted in the selected row within the table


Q8. What type of data structure is returned by calls to `db.exec_prepared()`? In the `save` method, how do we access the id from the returned data structure?
## array of hashes

Q9. Why do we use prepared statements when performing database operations?
#To prevent SQL injections

## Extension Questions

Look at the `find_by_id` and `find_by_address` methods in the `Property` class.

Q10. What do they take in as their arguments?

Q11. What are their return values?
