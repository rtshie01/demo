# demo
for demo only

This is an interface to allow user to add/edit/delete report subscription.

The angularJS is a mini SAP that provide subscription listing and an entry page that modify the subscription entity.
One report subscription can have many users attached. 

Each subscription will be processed in the backend where report is generated and email as attachment to user list (this is not covered in this demo). 

MVP project is the web api that interactive with the frontend for CRUD actions.

TODO: create factory service for the CRUD actions call to encapsulate the complexity.
      bootstrap the template
