# POST
This project is describe the POST request in PHP.

POST request is for sending a data to the server. 

The code below is for sending the post data

```
   if(count($_POST)){
            foreach($_POST as $key => $getValues){
                echo "<div> $key : $getValues </div>";
            }
        }
```        
