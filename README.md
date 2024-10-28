<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Registration Page</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="registration-container">
        <h2>Register Yourself On NAGRE ENTERPRISES</h2>
        <form id="registrationForm">
            <div class="form-group">
                <label for="username">Username:- nagreaniket@123</label>
                <input type="text" id="username" name="username" required>
            </div>
            <div class="form-group">
                <label for="email">Email:- nagreaniket123@gmail.com</label>
                <input type="email" id="email" name="email" required>
            </div>
              <div class="form-group">
                <label for="phonenumber">Phone Number:- 9867776798</label>
                <input type="integer" id="phonenumber" name="phonenumber" required>
            <div class="form-group">
                <label for="password">Password:- aniketnagre@123</label>
                <input type="password" id="password" name="password" required>
            </div> 
            <div class="form-group">
                <label for="confirmpassword">Confirm Password:- aniketnagre@123</label>
                <input type="confrimpassword" id="confirmpassword" name="confrimpassword" required> 
               </div> <button type="submit">Registered</button>
               </div> <label type="THANKYOUFORREGISTERINGONNAGREENTERPRISESOUREXPERTIESWILLCONTACTYOUSOON">THANK YOU FOR REGISTERING ON NAGRE ENTERPRIESE ! OUR TEAM WILL CONTACT YOU SOON </button>
              
                  
           
          
             
        </form>
        <p class="success-message" id="success-message"></p>
        <p class="error-message" id="error-message"></p>
    </div>
    <script src="script.js"></script>
</body>
</html>

