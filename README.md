# back_00_go_API_gin

this is a basic API made with go and gin that shows books and lets you:  
  
. list all books                GET(/books)  
. search by id                  GET(/books/{id})  
. add a new book                POST(/books)  
. checkout aa avaliable copy    PATCH(/checkout?id={id})  
. return a copy                 PATCH(/return?id={id})  
  
  
This API does not use a database.
