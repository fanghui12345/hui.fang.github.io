
<!DOCTYPE html>
<html>

<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8" />
    <title></title>
    <style type="text/css">
      
     
          
    
    
      .box1 {
        width: 500px;
        height: 300px;
        background-color: royalblue;
      
        padding: 20px;
        border: 2px  solid black;

        margin: 150px ;
        position: relative;
        top: 40px;
        left: 190px;

      }
  

 
      /*
			 * 创建一个子元素box2占满box1，box2把内容区撑满了
			 */
      .box2 {
        width: 495px;
        height: 300px;
        background-color: red;
        border:2px solid black;
        position:absolute;
         top: 20px;
        left: 20px;
        
        display: flex;
       /* justify-content: center;*/
        align-items: center;
        color: white;

       flex-direction: column;  /*flex-direction: column 子元素从上到下排列*/

       justify-content: initial;  
       text-align: center;

       text-align: center;

       justify-content: center;
       text-align: left

      }


    </style>
  </head>
  <body>



    <div class="box1">
    <div class="box2" >


    <h2  >Personal Information</h2>
        

     <ul>

    <li>name：Hui </li>
    <li>age    ：    28 </li>
    <li>email：John.doe@example.com</li>
    <li>hobby: Sport </li>
    <li>school: Illinois tech</li>
    <li>degree: Master</li>


    </ul> 


    </div>


  </body>
</html>
