<!DOCTYPE html>
<html>
    <head>
        <title>form</title>
        <style>
            .bg{
                color:blueviolet;
                font-size: medium;
                font-family: 'Times New Roman';
            }
        </style>
    </head>
    <body bg-color= <"red">
            <h1align="center">REGISTER </h1>
            <hr color="black" size="2px" width="100px"text-align="left" />
            <br>
        <form>
            <input type="text" placeholder="FirstName" name="fname" />
            <br>
            <input type="text" placeholder="LastName" name="lname" />
            <br>
            Gender:
            <br>
            Female<input type="radio" name="gender"/>
            male<input type="radio" name="gender"/>
            others<input type="radio" name="gender"/>
            <br/>
            <input type="email" placeholder="email" name="email"/>
            <br/>
        <input type="text" placeholder="Address" name="Address" />
        <br>
        <input type="radio" name="graduate">Graduate 
        <input type="radio" name="graduate"> Post Graduate 
         <input type="radio" name="graduate"> Under Graduate 
        <br>
        City:
        <br>
        <select name="City">
            <option>srinagar</option>
            <option>chennai</option>
            <option>hyderabad</option>
            <option>delhi</option>
            <option>bangaloor</option>
            <option>mumbai</option>
        </select>
        <br/>
        <input type="date" name="date">
        <br/>
        <input type="color" name="color"/>
        <br/>
        <input type="file" name="file"/>
        <br/>
        Comments:
        <br>
        <textarea></textarea>
        <br>
       <input type="Submit" value="Register">
       <input type="Reset" value="Clear">
        </form>
        </body>
</html>
