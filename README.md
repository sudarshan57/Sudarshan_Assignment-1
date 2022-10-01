# Sudarshan_Assignment-1
Web Technology Assignment 1


<!DOCTYPE html>
<html lang="en">
<head>
    <style>
        .body,button {
    background-color: #4CAF50; 
    color: white;
    padding: 15px 32px;

  }
    </style>
     <script type="text/javascript">
        // Form validation code will come here. 
            function validate()
             {
                 var n = document.myForm.Name.value;
                 if( n == "" || n.length < 3 || n.length >= 18) 
                 {
                     alert( "Please enter valid name and minimum length 3 characters and maximum length 8 characters !" ); 
                     document.myForm.Name.focus(); 
                     return false; 
                 }
                   
                 let m = document.myForm.age.value;
                 if( m == "" || m.length < 2) 
                 {
                     alert( "Please enter valid age" ); 
                     document.myForm.age.focus(); 
                     return false; 
                 }
                 
                 let x = document.myForm.Phone.value;
                 
                 if( x == "" || x.length < 3 || x.length >= 100) 
                 {
                     alert( "Please Enter the address" ); 
                     document.myForm.Phone.focus(); 
                     return false; 
                 }

                 ErrorText= "";
  if ( ( form.gender[0].checked == false ) && ( form.gender[1].checked == false ) ) 
  {
  alert ( "Please choose your Gender: Male or Female" ); 
  return false;
  }
                 
               var c = document.myForm.Country.value; 
                 if( c == "-1" ) {
                  alert( "Please provide your Room type" );
                  return false; 
                 } 
                 return( true ); 

                 var u = document.myForm.cash.value; 
                 if( u == "-1" ) {
                  alert( "Please provide your Payement Type" );
                  return false; 
                 } 
                 return( true );
             }
             </script>
             <script type="text/javascript">
                // Form validation code will come here. 
                    function newvalidate()
                     {
                         var n = document.Form.Name.value;
                         if( n == "" || n.length < 3 || n.length >= 18) 
                         {
                             alert( "Please enter valid name and minimum length 3 characters and maximum length 8 characters !" ); 
                             document.Form.Name.focus(); 
                             return false; 
                         }
                             
                         var emailID = document.Form.EMail.value; 
                         if( emailID == "" ) 
                         {
                            alert( "Please provide your Email!" );
                            document.Form.EMail.focus() ;
                            return false;
                         }
                         atpos = emailID.indexOf("@");
                         dotpos = emailID.lastIndexOf(".");
                         if (atpos < 1 || ( dotpos - atpos < 2 ))
                         {
                            alert("Please enter correct email ID")
                            document.myForm.EMail.focus();
                            return false;
                         }
                         
                         let x = document.Form.Phone.value;
                         
                         if (isNaN(x) || x < 6000000000 || x > 9999999999) {
                            alert("Input not valid");
                            document.Form.Phone.focus();
                            return false;
                         }
                         
                                        
                         var z = document.Form.Zip.value;
                         if(z == "" ||isNaN(z) || z.length != 6 )
                         {
                            alert( "Please provide a zip in the format NNNNNN." );
                            document.myForm.Zip.focus();
                            return false;
                         }
                                            
                         var c = document.Form.Country.value; 
                         if( c == "-1" ) {
                          alert( "Please provide your country!" );
                          return false; 
                         } 
                         return( true ); 
                     }
                     </script>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SUDARSHAN PANDEY | ASSIGNMENT !</title>
</head>
<body>
    <h1>1-)</h1>
    <h1 style="text-align:center">The Mobile AMBULANCE -EMRI 108</h1>
    <center>
        <table border="2">
            <tr>
                <th>Special Equipments</th>
                <th colspan="2">Specification/Performance</th>
            </tr>
            <tr>
                <td>Retracable protective armour</td>
                <td>Engine Type</td>
                <td>Jet Turbine</td>
            </tr>
            <tr>
                <td>Weapon System</td>
                <td>Thrust</td>
                <td>150lbs@<br>103%ROS</td>
            </tr>
            <tr>
                <td>Weapon System</td>
                <td>Torque</td>
                <td>175lbs@<br>98.7%ROS</td>
            </tr>
            <tr>
                <td rowspan="9"><img src="img1.jpg" width="200" height="150"></td>
                <td>0-60MPH></td>
                <td>3.7sec</td>
            </tr>
            <tr>
                <td>Top speed</td>
                <td>Unknown</td>
            </tr>
            
            <tr>
                <td>Break Rate</td>
                <td>Excellent</td>
            </tr>

            <tr>
                <td>Wheel Base</td>
                <td>141.12in</td>
            </tr>

            <tr>
                <td>Length</td>
                <td>300.5in</td>
            </tr>

            <tr>
                <td>Width</td>
                <td>100.0in</td>
            </tr>
            <tr>
                <td>Height</td>
                <td>200.21in</td>
            </tr>

            <tr>
                <td>Wheels</td>
                <td>Cast Alloy 15X7.5</td>
            </tr>
            <tr>
                <td>Fuel Required</td>
                <td>pure petrol with 99.9% free carbon</td>
            </tr>
        </table>
    </center>

    <hr><hr><br>
    <h1>2-)</h1>
    <img src="img1.jpg" width="350" height="200"><span>GVK EMRI (Emergency Management and Research Institute) is a pioneer in Emergency Management Services in India. As a not – for – profit professional organization operating in the Public-Private Partnership (PPP) mode, GVK EMRI is the largest professional Emergency Service Provider in India today.With increased focus on research and analytics, GVK EMRI now, also enters into the arena of protecting law and order in the society. GVK EMRI has left no stone unturned to reach out the needy by extending its reach through various Help Line and Specific Segment oriented Focused Services as an offshoot of the vast expertise gained through the last 14 years of 108 EMS <br>Operations across the length and breadth of it’s operational states in India.Today, 108 is synonymous with the best-in-class emergency service and has been acknowledged as the most efficient, speedy, reliable, and caring service provider in its category.</span>
    <br> <br> <br> <br> <br> <br><p style="text-align:center ;">Thank You For Having Interest</p>
    <hr><hr>
    <h1>3-)</h1>
    <h3 style="color:blue;font-family: Georgia, 'Times New Roman', Times, serif;text-align: center;">Bootstrap Portfolio Link</h3>
    <center>
        <button class="button"><a href="http://43.206.152.214/dist/" target="_blank" style="text-decoration: none ;color:white";><b>Click Here</b></a></button>
    </center>
    <hr><hr><br>
    <h1>4-)</h1>
    <h1><p align="center"><b>Data Entry Of Customer In A Hotel </b></p></h1>
    <form name="myForm" onsubmit="return(validate());">
        <table cellspacing="5" cellpadding="5" align="center" border="5" width="438">
            <tr> <td align="right"><b>Name</b></td>
                 <td><input type="text" name="Name" size="50" /></td>
            </tr>
            <tr> <td align="right"><b>Address</b></td>
                <td><input type="text" name="Phone" size="50" /></td>
           </tr>
            <tr> <td align="right"><b>Age</b></td>
                 <td><input type="text" name="age" size="50" /></td>
            </tr>
            <tr> <td align="right"><b>Gender</b></td>
                <td>
                    <input type="radio" name="gender" value="Male"> Male
                   <input type="radio" name="gender" value="Female"> Female
                </td>
           </tr>
             <tr> <td align="right" ><b>Room Type</b></td>
                 <td> <select name="Country"> 
                    <option value="-1" selected>[choose yours]</option>
                        <option value="1">A/C</option>
                        <option value="2">Non-Ac</option>
                        <option value="3">Deluxe</option>
                     </select>
                 </td>
            </tr>
            <tr> <td align="right" ><b>Type Of Payement</b></td>
                    <td><select name="cash"> 
                        <option value="-1" selected>[choose yours]</option>
                       <option value="1">Cash Only</option>
                       <option value="2">Credit/Debit Card</option>
                       <option value="3">Coupons</option>
                    </select>
                </td>
           </tr>
            <tr> <td align="right"></td>
                 <td><input type="submit" value="Submit" /></td>
        </tr>
        </table>
    </form>
    <hr><hr>
    <h1>5-)</h1>
    <h1><p align="center"><b>Bio Data Information</b></p></h1>
    <form name="Form" onsubmit="return(newvalidate());">
        <table cellspacing="5" cellpadding="5" align="center" border="5" width="438">
            <tr> <td align="right"><b>Name</b></td>
                 <td><input type="text" name="Name" size="50" /></td>
            </tr>
            <tr> <td align="right"><b>Phone number</b></td>
                <td><input type="text" name="Phone" size="50" /></td>
           </tr>
            <tr> <td align="right"><b>EMail</b></td>
                 <td><input type="text" name="EMail" size="50" /></td>
            </tr>
            <tr> <td align="right"><b>Zip Code</b></td>
                 <td><input type="text" name="Zip" size="50" /></td>
            </tr>
            
            <tr> <td align="right" ><b>Country</b></td>
                 <td> <select name="Country"> 
                        <option value="-1" selected>[choose yours]</option>
                        <option value="1">INDIA</option>
                        <option value="2">UK</option>
                        <option value="3">USA</option>
                     </select>
                 </td>
            </tr>
            <tr> <td align="right"></td>
                 <td><input type="submit" value="Submit" /></td>
                    
                    
            </tr>
        </table>
    </form>
         <hr><hr>
    </body>
</html>
