# Patika_HW1
My first Patika Homework
<html>
    <head>
        <title>Done by Baran :)</title>
        <style type="text/css">
            body {
                background-image: url('https://raw.githubusercontent.com/Kofana-Software-Developer-Bootcamp/assignment1-baranergl/main/justpatikajpg.jpg?token=GHSAT0AAAAAABRLIVX45GK2LFMZ5IN3A6MYYQY4VNQ');
            }
            </style>   
    </head>
    <body>
    
        <center>
        <hl>
            <br/>
        <br/>
        <br/>
          <p style="font-family: Verdana, Geneva, Tahoma, sans-serif;">  <h1><p style="color:rgb(255, 217, 0)"> Patika Application Form </h1> </p> </p> <br/>
        </hl>
        <br/>
        <br/>
        <br/>
        <br/>
        <br/>
        <br/>
            Enter your mail adress: <input type = "text" id = "foo" value=""/><br/>
            <br/>
            Enter your name and surname: <input type = "text" id = "zoo" value=""/><br/>
            <br/>
            Enter your phone number: <input type = "text" id = "koo" value=""/><br/>
            <br/>
            Enter your birth year: <input type = "text" id = "poo" value=""/><br/>          
            <br/>
            Enter your github's link :): <input type = "text" id = "goo" value=""/><br/>
            <br/>
            Enter your linkedin's link: <input type = "text" id = "loo" value=""/><br/>
            <br/>
            Enter the reason why you want to be in patika <input type = "text" id = "roo" value=""/><br/>
            <br/>
            Enter the uni name <input type = "text" id = "uoo" value=""/><br/>
            <br/>
            Where do you live? <input type = "text" id = "coo" value=""/><br/>
            <br/>
            Where would you like to work? <input type = "text" id = "doo" value=""/><br/>
            <br/>
            What did you research about sponsorship company? What makes you excited? <input type = "text" id = "aoo" value=""/><br/>
            <br/>
            What will you put in this bootcamp?<input type = "text" id = "soo" value=""/><br/>
           
            <br/>
            <br/>

            <div class="custom-select2" style="width:200px;">
                <select id="combo1">
                  <option hidden="true">Where did you hear Patika?</option>
                  <option value="1">Linkedin</option>
                  <option value="2">Friend</option>           
                  <option value="3">Facebook</option>           
                  <option value="4">Twitter</option>
                  <option value="5">Youtube</option>
                </select>
              </div>  
              <br/>
              <br/>
              <br/>
            
              <div class="custom-select3" style="width:200px;">
                <select id="combo2">
                  <option hidden="true">What is your estimated graduate date?</option>
                  <option value="1">Already Graduated</option>
                  <option value="2">July 2022</option>           
                  <option value="3">January 2023</option>       
                  <option value="4">July 2023</option>
                </select>
              </div>  
              <br/>
              <br/>
              <br/>
             
              <div class="custom-select4" style="width:200px;">
                <select id="combo3">
                  <option hidden="true">What is your English Level?</option>
                  <option value="1">None</option>
                  <option value="2">Beginner</option>           
                  <option value="3">İntermadiate</option>
                  <option value="4">Fluent</option>
                
                </select>
              </div>  
              <br/>
              <br/>
              <br/>
             
              <div class="custom-select5" style="width:200px;">
                <select id="combo4">
                  <option hidden="true">What is your Educational Background?</option>
                  <option value="1">Primary School</option>
                  <option value="2">High School</option>        
                  <option value="3">Under Graduate Student</option>
                  <option value="4">Bachleros</option>
                  <option value="5">Master</option>
                  <option value="6">PhD</option>
                </select>
            </div>  
            <br/>
        <br/>
        
        
        <div class="custom-select1" style="width:200px;">
          <select id="combo5">
            <option hidden="true">What is your department?</option>
            <option value="1">Computer Science</option>
            <option value="2">Electrical & Electronics Engineering</option>            
            <option value="3">Software Engineering</option>           
            <option value="4">Industrial Engineering</option>           
          </select>
      </div>  
      <br/>
      <br/>
    
      
            <div class="custom-select6" style="width:200px;">
                <select id="combo6">
                  <option hidden="true"> Sex?</option>
                  <option value="1">Man</option>
                  <option value="2">Woman</option>                 
                  <option value="3">Dont want to specify</option>
                </select>
              </div>  
              <br/>
              <br/>
              
            <div class="custom-select7" style="width:200px;">
                <select id="combo7">
                  <option hidden="true">Where would you improve yourself?</option>
                  <option value="1">Front-end</option>
                  <option value="2">UI/UX</option>           
                  <option value="3">Mobile</option>
                  <option value="4">Data Analyst</option>
                  <option value="5">Game Developer</option>
                  <option value="6">Game Artist</option>
                  <option value="7">Other</option>
                </select>
              </div>  
              <br/>
              <br/>
              <div class="custom-select8" style="width:200px;">
                <select id="combo8">
                  <option hidden="true"> What is your total coding hours</option>
                  <option value="1">Less than 50 hours</option>
                  <option value="2">50-100 hours</option>                 
                  <option value="3">100-200 hours</option>
                  <option value="4">200+ hours</option>
                </select>
              </div>  
              <br/>
              <br/>
              <div class="custom-select9" style="width:200px;">
                <select id="combo9">
                  <option hidden="true"> Total experience?</option>
                  <option value="1">Less than 6 months</option>
                  <option value="2">6 months - 1 year</option>                 
                  <option value="3">1 year - 2 years</option>
                </select>
              </div>  
              <br/>
              <br/>
              <br/>
                 
              </div>  
              <p><h4>GDPR Approval? **</h4> </p>
              <div>
              <input type="checkbox" id="GDPR_app" name="GDPR_app1"       checked>
              <label for="GDPR_app">Yes, I do</label>               
              </div>
         
        <button onclick="getValue()">Enter</button>
        <p id="boo">
        </p>
        <p id="foo">
        </p>
        
        <script>
            function getValue(){
    
                var y = document.getElementById('boo'); //we get the id boo here
                var x = document.getElementById('foo').value; //we get the foo's value
                var z = document.getElementById('zoo').value; //we get the zoo's value
                var k = document.getElementById('koo').value; //we get the koo's value
                var p = document.getElementById('poo').value; //we get the poo's value      
                var g = document.getElementById('goo').value; //we get the goo's value
                var l = document.getElementById('loo').value; //we get the loo's value
                var r = document.getElementById('roo').value; //we get the roo's value
                var u = document.getElementById('uoo').value; //we get the uoo's value
                var c = document.getElementById('coo').value; //we get the coo's value
                var doo = document.getElementById('doo').value; //we get the coo's value
                var aoo = document.getElementById('aoo').value; //we get the coo's value
                var soo = document.getElementById('soo').value; //we get the coo's value
                var asd = document.getElementById('combo1').options[document.getElementById('combo1').selectedIndex].text; //we get the combo box1 value
                var acb = document.getElementById('combo2').options[document.getElementById('combo2').selectedIndex].text; //we get the combo box2's value
                var adb = document.getElementById('combo3').options[document.getElementById('combo3').selectedIndex].text; //we get the combo box3's value
                var asf = document.getElementById('combo4').options[document.getElementById('combo4').selectedIndex].text; //we get the combo box4's value
                var asg = document.getElementById('combo5').options[document.getElementById('combo5').selectedIndex].text; //we get the combo box5's value
                var ash = document.getElementById('combo6').options[document.getElementById('combo6').selectedIndex].text; //we get the combo box6's value
                var asj = document.getElementById('combo7').options[document.getElementById('combo7').selectedIndex].text; //we get the combo box7's value
                var asq = document.getElementById('combo8').options[document.getElementById('combo8').selectedIndex].text; //we get the combo box8's value
                var asw = document.getElementById('combo9').options[document.getElementById('combo9').selectedIndex].text; //we get the combo box9's value
                var asp = document.getElementById('GDPR_app').checked; //we get the GDPR_app's value and this value is boolean
                
                if(!asp){
                    alert("Please confirm GDPR Aprrovment!");
                    return      //if statement of GDPR
                }
                
                y.innerHTML=x; //check this out
                y.innerHTML=z;
                y.innerHTML=k;
                y.innerHTML=p;
                y.innerHTML=g;
                y.innerHTML=l;
                y.innerHTML=r;
                y.innerHTML=u;
                y.innerHTML=c;
                y.innerHTML=asd;
                y.innerHTML=acb;
                y.innerHTML=adb;
                y.innerHTML=asf;
                y.innerHTML=asg;
                y.innerHTML.ash;
                y.innerHTML.asj;
                y.innerHTML.asp;
                y.innerHTML.doo;
                y.innerHTML.aoo;
                y.innerHTML.soo;
                y.innerHTML.asq;
                y.innerHTML.asw;
               
               
                let person = {
                    mail_adress: x,
                    full_name:z,
                    phone_number:k,
                    birth_year:p,
                    github_link:g,
                    linkedin_link:l,
                    reason:r,       //Person's all the information
                    university:u,
                    place_where_you_live:c,
                    place_of_work:doo,
                    sponsorship:aoo,
                    what_will_you_put_bootcamp:soo,
                    where_did_you_hear_patika:asd,
                    graduate_date:acb,
                    english_level:adb,
                    department:asf,
                    major:asg,
                    sex:ash,
                    work_area:asj,
                    coding_hours:asq,
                    total_experience:asw,
                    GDPR:asp,


                    
                }

                console.log(person)

            }
    
           

        </script>
        <center>
    </body>
   
    

</html>
