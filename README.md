<!DOCTYPE html>
<html lang="en">
    <head> 
       <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <title>Submission Form</title>
        <link rel="Stylesheet" href="Stylesheet.css"></link>
    </head>
    <body>

<style>


body {
   background-color: #0b0c10; 
   display:flex;
   flex-direction:column;
}

.Nav-header{
    display:flex;
    flex-direction:row;
    border-bottom:0.5px solid #2c2f36;
    height:30px;
    gap:13px;
}

.cinelist{
    color:blue;
    font-weight:bold;
    font-size:13px;
    
}
.Browse{
    color:white;
    font-size:11px;
    
}
.Request{
    background-color:grey;
    color:white;
    border-radius:4px;
    height:23px;
    font-size:13px;
    width:60px;
    text-align:center;
    margin-bottom:30px;
    
}
p{
    color:white;
    text-align:center;
    font-size:10px;
}


.mid-section{
    height:100px;
    width:200px;
    margin-left:60px;
    padding:2px;

}

h1{
    font-size:20px;
    text-align:center ;
    color:white;
    font-weight:bold;    
}

form{
    color:white;
    background-color:#1a1d23;
    height:320px;
    align-items:center;
    width:300px;
    margin-left:15px;
    
}

.sub{
    width:301px;
    background-color:#1a1d23;
    margin-left:15px;
    margin-right:35px;
    color:white;
    font-weight:bold;
    font-size:13px;
    border-bottom:1px solid #2c2f36;
}
span{
    font-size:10px;
    margin-left:14px;
    font-weight:bold;
}
input{
    background-color:#030001;
    border:1px solid #030001;
    margin-left:14px;
    width:260px;
    color:white;
    font-size:1px;
    height:20px;
}
label{
    font-size:9px;
    font-weight:bold;
    margin-left:14px;
}

textarea{
    background-color:#030001;
    height:75px;
    width:260px;
    margin-left:14px;
    color:white;
    font-size:1px;
    border:1px solid #2c2f36;
}

.box{
    height:35px;
    width:265px;
    background-color:#2c2f36;
    border:1px solid #2c2f36;
    margin-left:15px;
    margin-right:15px;
    margin-top:10px;
    border-radius:3px;
}

h5{
    font-size:1px;
    color:blue;
    font-weight:bold;
}
p{
    text-align:center;
    font-size:0.05px;
    margin-top:1px;
    padding-bottom:10px;
}

.button{
    background-color:blue;
    margin-top:10px;
    width:270px;
    margin-left:14px;
    border:1px solid blue;
    color:white;
    border-radius:2px;
    font-weight:bold;
    font-size:3px;
    height:25px;
}

.footer{
   border-top:1px solid #2c2f36;
   margin-top:10px;
   font-weight:bold;
   font-size:1px;
   padding-top:5px;

}

.mid-footer{
    display:flex;
    flex-direction:row;
    margin-top:33px;
}

.mid-footer1{
    height:40px;
    width:148px;
    border:1px solid #2c2f36;
    margin-left:13px;
    color:white;
    
}

#rules{
    font-size:2px;
    padding-left:5px;
    text-align:left;
    padding-bottom:10px;
}

#guide{
    font-size:2px;
    padding-left:5px;
    padding-bottom:2px;
    font-weight:bold;
}

#faq{
    font-size:2px;
    font-weight:bold; 
    padding-left:2px;   
    
}

#learn{
    font-size:1.5px;
    font-weight:;
    text-align:left ;
    padding-left:3px;
    padding-top:4px;
    font-weight:bold;
}

.nav-bar{
    border-top:1px solid #2c2f36;
    margin-top:35px;
    color:white;
    display:flex;
    flex-direction:row;
    font-size:3px;
    font-weight:bold;
}

.nav-bar1{
    display:flex;
    gap:15px;
    font-size:3px;
    margin-top:20px;
    margin-left:45px;
    font-weight:bold;
}

.h6{
    color:blue;
    text-align:center;
    padding-top:3px;
    font-weight:bold;
}

</style>


    
    <!--the header section-->
    
    <header class="Nav-header">
        <div class="cinelist">CineList</div>
        <div class="Browse">Browse</div>
        <div class="Request">Request</div>
    </header>

    <!---the request section-->
    
        <div class="mid-section">
            <h1>REQUEST A TITLE</h1>
            <p>can't find what you're looking for? Let our Courators know and we'll add it to the vault </p>
            
        </div>
        
        <!--the form section-->

      <div class="form-container">
   <div class="sub"><span>SUBMISSION PORTAL</span></div>
   <form>
   <label>YOUR NAME</label></br>
   <input type="text" id="name" class=" fullname" placeholder=".e.g. John doe"></br>
   
   <label>MOVIE TITLE</label></br>
   <input  type="text" class="movie-title" placeholder="Enter the title exactly..."></br>
   
   <label>WHY SHOULD WE ADD IT</label></br>
   <textarea type="text" class"text-area" placeholder="Tell us abit about this film or why you want to see it here"></textarea></br>
   
   <div class="box"><h5>NOTICE</h5>
       <P>Requests are typical processed within within 48 hours.Ensure the title is spelled correctly.</P>
   </div>
   <button class="button">✈️ Sumbit Request </button>
   
   <div class="footer"> <p>FLAT INTERFACE v2.4 // CINELIST CORE</p></div>
       
   </form>
   <!---the form ends here--->   
   <div class="mid-footer">
       <div class="mid-footer1">
           <h6 id="guide">GUIDELINES</h6>
           <p id="rules">We priortize HD quality  metadata.</p>
       </div>
       <div class="mid-footer1"><h6 id="faq">FAQ</h6>
           <P id="learn">learn  about regional restrictions.</P>
       </div>
   </div>
     
    
</div>


<div class="nav-bar">
    <div>
    <h6 class="h6">CINELIST</h6>
    <p>©2024 Cinelist inc.high contrast entertainment.</p>
        
    </div>
    
    <div class="nav-bar1">
    <div>Terms</div>
    <div>Privacy</div>
    <div>Support</div>
    </div>
</div>
    </body>
</html>