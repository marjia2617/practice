<!DOCTYPE html>
remote_theme: pages-themes/slate@v0.2.0
plugins:
- jekyll-remote-theme # add this line to the plugins list if you already have one<html>
    <head>
        <title>City</title>
    </head>

    <body>
       
       <div style="border: 2px solid black; background-color: tomato; color: white; padding: 20px; margin: 20px; width: 20%">
          <h2>London</h2>
          <p>London is the capital of England</p>

       </div>

        <div style="border: 2px solid black; background-color: tomato; color: white; padding: 20px; margin: 20px; width: 40%">
          <h2>Paris</h2>
          <p>Paris is the capital of France</p>

       </div>

       <div style="border: 2px solid black; background-color: tomato; color: white; padding: 20px; margin: 20px; width: 40%">
          <h2>Tokyo</h2>
          <p>Tokyo is the capital of Japan</p>

       </div>     

       <h1>My <span style="color:red; font-size: 39px">Important</span> Heading</h1>

       <p>This is some <span style="color: red">important</span> text.</p>  

       <iframe src="https://youtube/S0RqHzm1r5E?si=TV26LShwPGVQkAPw" width="100%" title="hello world"></iframe> 
 
       <iframe src="https://www.bing.com" height="200" width="900" title="Iframe Example" style="border:20px solid black"> </iframe> 
    
       <label for="fname">First Name: </label>
       <input type="text" id="fname" name="fname"></br>
       <label for="cars" style="color:red; font-size: 20px; border: 2px solid   black">Choose a car:</label>
       <select id="cars" name="cars">
            <option value="volvo">Volvo</option>
            <option value="saab">Saab</option>  
            <option value="fiat">Fiat</option> 
            <option value="audi" selected>Audi</option>
       </select></br></br>

       <select id="cars" name="cars" size="3" multiple>
            <option value="volvo">Volvo</option>
            <option value="saab">Saab</option>  
            <option value="fiat">Fiat</option> 
            <option value="audi" selected>Audi</option>
       </select>

       <textarea name="message" style="width:200px; height: 100px"></textarea></br>

       <fieldset>
         <legend>Personalis:</legend>
           <label for="fname">First Name:</label></br>
           <input type="text" id="fname" name="fname"></br>
           <label for="lname">Last Name:</label></br>
           <input type="text" id="lname" name="lname" value="John"></br>
       </fieldset></br>
        
       <input list="browser">
       <datalist id="browser">
           <option value="Edge">
           <option value="Firefox">
           <option value="Chrome">
           <option value="Opera">
           <option value="Safari">
       </datalist></br>
       
       <button type="button">Click me</button> 

       <form>
           <label for="Username">Username:</label></br>
           <input type="text" id="Username" name="Username"></br>
           <label for="password">Password:</label></br>
           <input type="password" id="password" name="password"></br></br>
           <input type="submit" value="submit">
           
       </form>

       
       <form>
           <label for="Username">Username:</label></br>
           <input type="text" id="Username" name="Username"></br>
           <label for="password">Password:</label></br>
           <input type="password" id="password" name="password"></br></br>
           <input type="submit"></br>
           
       </form>
         </br>
       <form>
           <input type="radio" id="html" name="coding" value="html">
           <label for="html">HTML</label></br>
           <input type="radio" id="css" name="coding" value="css">
           <label for="css">CSS</label> </br>
           <input type="radio" id="js" name="coding" value="js">
           <label for="js">JavaScript</label>
       </form>

          </br>

        <form>
           <input type="checkbox" id="ride" name="ride" value="bike">
           <label for="ride">I have a bike</label></br>
           <input type="checkbox" id="ride" name="ride" value="car">
           <label for="ride">I have a car</label> </br>
           <input type="checkbox" id="ride" name="ride" value="boat">
           <label for="ride">I have a boat</label>
       </form>

       <form>
           <label for="birthday">Birthday:</label>
           <input type="date" id="birthday" name="birthday"></br>
           <input type="submit">
       </form>

       <form>
           <label for="bday">Birthday (date and time):</label>
           <input type="datetime-local" id="bday" name="bday" value="bday">
           <input type="submit" value="Submit">
       </form>

       <form>
           <label for="email">Enter your email:</label>
           <input type="email" id="email" name="email">
           <input type="submit" value="Submit">
       </form>
       
       
       

       
   

       

      

       
 
 
       
        
    </body>
</html>
