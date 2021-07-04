<!DOCTYPE html>
<html>
<body >
    <div>
      <b><h2 >Bio Data Form</h2></b>
            <form  method="GET" action="">
        <div style="padding: 10px;">
            <label>Name: </label>
            <input autofocus type="text" name="name" id="name" class="input-field" placeholder="Enter your name" required>
        </div>
        <div style="padding: 10px;">
          <div class="labels">
            <label id="number-label" for="age">Age: </label>
            <input type="number" name="age" id="number" min="1" max="125" class="input-field" placeholder="Age" required>
          </div>
        </div>
        <div style="padding: 10px;">
            <div class="labels">
              <label id="name-label" for="name">First Name: </label>
              <input autofocus type="text" name="name" id="name" class="input-field" placeholder="Enter your First name" required>
            </div>
          </div>
          <div style="padding: 10px;">
            <div class="labels">
              <label id="name-label" for="name"> LastName: </label>
              <input autofocus type="text" name="name" id="name" class="input-field" placeholder="Enter your last name" required>
            </div>
          </div>
          <div style="padding: 10px;">
            <label>Gender: </label>
            <input autofocus type="text" name="name" id="name" class="input-field" placeholder="Gender" required>
        </div>
        
        <div style="padding: 10px;">
          <div class="labels">
            <label id="dob-label" for="dob">D.O.B: </label>
            <input type="date" name="dob" id="iddob" class="input-field" required>
          </div>
        </div>
    
        <div style="padding: 10px;">
          <div class="labels">
            <label for="address">Address Line1: </label>
            <textarea id="comments" class="input-field" style="height:20px;resize:vertical;" name="address" placeholder="Door Number"></textarea>
          </div>          
        </div>
        <div style="padding: 10px;">
            <div class="labels">
              <label for="address">Address Line2: </label>
              <textarea id="comments" class="input-field" style="height:20px;resize:vertical;" name="address" placeholder="Street"></textarea>
            </div>          
          </div>
          <div style="padding: 10px;">
            <div class="labels">
              <label for="address">Address Line3: </label>
              <textarea id="comments" class="input-field" style="height:20px;resize:vertical;" name="address" placeholder="District"></textarea>
            </div>          
          </div>
        <div style="padding: 10px;">
            <div class="labels">
              <label for="address">State: </label>
              <textarea id="comments" class="input-field" style="height:20px;resize:vertical;" name="address" placeholder="State"></textarea>
            </div>          
          </div>
          <div style="padding: 10px;">
            <div class="labels">
              <label for="address">Country: </label>
              <textarea id="comments" class="input-field" style="height:20px;resize:vertical;" name="address" placeholder="Country"></textarea>
            </div>          
          </div>
        <div style="padding: 10px;">
          <div class="labels">
            <label for="pincode">Pincode: </label>
           <input type="number" name="pincode" id="idpincode" class="input-field" style="height:20px;resize:vertical;" placeholder="6  _ _ _ _ _">
        </div>
        </div>
        <div style="padding: 10px;">
          <div class="labels">
            <label for="pincode">Phone: </label>
           <input type="number" name="pincode" id="idpincode" class="input-field" style="height:20px;resize:vertical;" placeholder="9 1 _ _ _ _ _ _ _ _ _ _ ">
        </div>
        </div>
        <button id="submit" type="submit">Submit</button>
        <button id="reset" type="reset">Reset</button>
      </form>
    </div>
</body>
</html>
