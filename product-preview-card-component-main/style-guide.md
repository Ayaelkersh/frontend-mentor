body{
  background-color: hsl(30, 38%, 92%);
  font-family: 'Fraunces', serif; 
}   
   

.parent{
  background-color: hsl(0, 0%, 100%);
  gap: 10px;
  border-radius: 10px;
  margin: 50px auto;
  width: 600px;
  height: 500px;
  display: flex;
  flex-direction: row;
  -webkit-border-radius: 10px;
  -moz-border-radius: 10px;
  -ms-border-radius: 10px;
  -o-border-radius: 10px;
}
.parent .child-1 img{
  border-radius: 10px 0 0 10px;
  width: 334px;
  -webkit-border-radius: 10px 0 0 10px;
  -moz-border-radius: 10px 0 0 10px;
  -ms-border-radius: 10px 0 0 10px;
  -o-border-radius: 10px 0 0 10px;
}

p{
  font-size: 14px;
  font-weight: 500px;
  color: dimgrey;
  
}

.child-2{
margin: 20px;

}
.price{
  display: flex;
  flex-direction: row;
  justify-content: space-evenly;  
}
.price p{
  font-weight: bold;
  font-size: 22px;
  color: hsl(158, 36%, 37%);
  font-family: 'Fraunces', serif;
}
.box{
  width: 200px;
  border-radius: 10px;
  text-align: center;
  padding: 10px;
  background-color: hsl(158, 36%, 37%);
  color: hsl(0, 0%, 100%);
  border: hsl(158, 36%, 37%);
  -webkit-border-radius: 10px;
  -moz-border-radius: 10px;
  -ms-border-radius: 10px;
  -o-border-radius: 10px;
}
.price del{
  margin: 30px;
  font-size: 10px;
  color: dimgray;
}

h1{
  font-family: 'Fraunces', serif;
}

          /* small */
    @media(max-width: 768px){
      .parent{
        flex-direction: column;
      width: 300px;
      height: 600px;
      }
      .parent .child-1 img{
        height: 200px;
        width: 300px;
      }
      .child-2{
        height: 20px;
        margin: 0 5px;
        font-weight: 10px;
      }
      .box{
margin: 0 20px;
      }
      
    }      