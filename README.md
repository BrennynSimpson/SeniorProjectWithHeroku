# SeniorProject

# Storage unit facility management software
Live URL: https://storage-facility-project.herokuapp.com/

## Resources

**Client**
Attributes:

* stripeId (String)
* firstName (String)
* lastName(Date)
* email (String)
* phone (String)
* address (String)
* zipCode (String)
* state (String)
* movieInDate (Date)
* moveOutDate (Date)

**Unit**
Attributes:

* customerId (String)
* unitNumber (Number)
* unitSize(String)
* occupied (Boolean)

**Task**
Attributes:

* title (String)
* dateCreated (Date)
* dueDate(Date)
* details (String)
* creadtedBy (String)
* complete(Boolean)


**Lead**
Attributes:
* type (String)
* source (String)
* firstName (String)
* lastName (String)
* email (String)
* phone (String)
* desiredUnit (String)
* date (Date)
* contacted (Boolean)

**Charge**
Attributes:
* customerId(String)
* paymentIntent (String)
* paymentMethod (String)


## REST Endpoints

Name                           | Method | Path
-------------------------------|--------|------------------
Retrieve client collection     | GET    | /clients
Create client member           | POST   | /clients
Update client member           | PUT    | /clients/*\<id\>*
Delete client member           | DELETE | /clients/*\<id\>*
Retrieve charge collection     | GET    | /charges
Create charge member           | POST   | /charges
Retreive charge member         | Get    | /charges/*\<id\>*
Retrieve unit collection       | GET    | /units
Create unit member             | POST   | /units
Retreive unit member           | Get    | /units/*\<id\>*
Delete unit member             | DELETE | /units/*\<id\>*
Update unit member             | PUT    | /units/*\<id\>*
Retrieve task collection       | GET    | /tasks
Create task member             | POST   | /tasks
Retreive task member           | Get    | /tasks/*\<id\>*
Delete task member             | DELETE | /tasks/*\<id\>*
Update task member             | PUT    | /tasks/*\<id\>*
Retrieve lead collection       | GET    | /leads
Create lead member             | POST   | /leads
Retreive lead member           | Get    | /leads/*\<id\>*
Delete lead member             | DELETE | /leads/*\<id\>*
Update lead member             | PUT    | /leads/*\<id\>*



