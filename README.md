# back_00_go_API_gin

this is a basic API made with go and gin that shows books and lets you:  
  
<code>. list all books----------------GET(/books)</code>  
<code>. search by id------------------GET(/books/{id})</code>  
<code>. add a new book----------------POST(/books)</code>  
<code>. checkout aa avaliable copy----PATCH(/checkout?id={id})</code>  
<code>. return a copy-----------------PATCH(/return?id={id})</code>    
  
  
	  
This API does not use a database.
