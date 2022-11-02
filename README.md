# HAIL-MARY

#### Team Members: @Aravind Dasarathy | @Divya Shree | @Geetha Parthasarathy | @Dhruv Parthasarathy 

 

GitHub : [github.com/neu-mis-info6150-fall-2022/final-project-final-project-hail_mary ]( https://github.com/neu-mis-info6150-fall-2022/final-project-final-project-hail_mary)


### About

  * Imagine you are running a company, say, a mobile company, and there are millions of customers reaching out to you daily regarding several hardware and    software mobile issues through email. How hard will it be to manage every concern through just a platform like an email?  

  * Hail Mary is a project that aims to provide convenient and frictionless customer-support domain. It consists of two parts - the customer’s side, where     a customer logs the complaint regarding issues governing a product, and the customer support’s side, where the (support) agent handles the issues           raised by the customer. The main aim is to provide a seamless experience between the customer and the company (customer support).  
  
### Entities

     The basic entities that govern our application are:  

      1. CUSTOMER 
      2. AGENT/RESOLVER 
      3. TICKET 
      4. CONTACT DETAILS 
      5. NOTES 
      6. TO-DO 
      
### Value Objects 

  All analytical data that we will be generating as an aggregate of entity parameters would be our Value Objects. A few of them are:  

   * Number of tickets created/open in a period  

   * Number of resolved unresolved, due, and unassigned tickets  

   * Average time taken to resolve or respond on tickets  

   * Communication between a customer and an agent 

   * Customer satisfaction 
   
The relationship among the actors and different entities are as follows:  

    1. Admin: Manage Profile Entity, Ticket Entity. 

    2. Agent: Create and Update Profile Entity, Ticket Entity, Forum, Escalation, and To-do Entity. 

    3. Customer: Create and Update Profile Entity, Ticket Entity, Escalation and Feedback Entity. 
