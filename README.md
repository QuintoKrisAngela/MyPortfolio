# MyPortfolio
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Personal Portfolio Website</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div id="header">
        <div class="container">
            <nav>
                <img src="Image/Screenshot 2023-07-25 23.35.06.png" class="logo">
                <ul>
                    <li><a href="#">Personal Data</a></li>
                    <li><a href="#">Educational Background</a></li>
                    <li><a hr ef="#">Hobbies</a></li>
                </ul>
            </nav>
            <div class="header-text">
                <p>Student</p>
                <h1>Kris Angela </span><br> Quinto</h1>
            </div>
        </div>
    </div>
    
    <div id="About Me">
        <div class="container">
            <div class="row">
                <div class="about-col-1">
                <img src="Image/profile.jpg">
            </div> 
                <div class="about-col-2">
                <h1 class="sub-title">About Me</h1>
                <p>I am an enthusiastic, self-motivated, reliable, responsible and hard working person.
                    I am friendly, helpful and polite, have a good sense of humour.
                    I am outgoing and tactful, and able to listen effectively when solving problems.
                    I'm a nice fun and friendly person, I'm honest and punctual, I work well in a team but also on my own as I like to set myself goals which I will achieve, I have good listening and communication skills.
                    I have a creative mind and am always up for new challenges.</p>

                    <div class="tab-titles">
                        <p class="tab-links active-link" onclick="opentab('personal data')">Personal Data</p>
                        <p class="tab-links" onclick="opentab('educational background')">Educational Background</p>
                        <p class="tab-links" onclick="opentab('hobbies')">Hobbies</p>
                    </div>
                    <div class="tab-contents active-tab" id="personal data">
                        <ul>
                            <li><span>Date of Birth:</span><br><h3>August 21, 2022</h3></li>
                            <li><span>Place of Birth:</span><br><h3>Embarcadero, Mangaldan</h3></li>
                            <li><span>Civil Status:</span><br><h3>Single</h3></li>
                            <li><span>Citizenship:</span><br><h3>Filipino</h3></li>
                            <li><span>Religion:</span><br><h3>Born Again</h3></li>
                            <li><span>Weight:</span><br><h3>99.21lbs.</h3></li>
                            <li><span>Height:</span><br><h3>4'11</h3></li>
                        </ul>
                    </div>
                    <div class="tab-contents" id="educational background">
                        <ul>
                            <li><span>Elementary:</span><br><h3>Embarcadero Elementary School<br>Mangaldan,Pangasinan<br>2008-2014</h3></li>
                            <li><span>High School:</span><br><h3>Mangaldan National High School<br>Mangaldan, Pangasinan<br>2014-2018</h3></li>
                            <li><span>Senior High School:</span><br><h3>Phinma University of Pangasinan<br>Dagupan City, Pangasinan<br>2018-2020</h3></li>
                            <li><span>College:</span></span><br><h3>Phinma University of Pangasinan<br>Dagupan City, Pangasinan<br>Bachelor of Science in Information Technology<br>(Undergraduate)</h3></li>
                        </ul>
                    </div>
                    <div class="tab-contents" id="hobbies">
                        <ul>
                            <li><span><h3>Experimenting in the kitchen:</h3></span><br>Enjoy learning new cooking/baking techniques.</li>
                            <li><span><h3>Gardening:</h3></span><br>Enjoying growing my own vegetables.</li>      
                            <li><span><h3>Traveling:</h3></span><br>I enjoy traveling specialy when we are going to the beach for swimming.</li>                       
                        </ul>
                        </div>
                
                </div>
            </div>

        </div>
    </div>
<script>

    var tablinks = document.getElementsByClassName("tab-links");
    var tabcontents = document.getElementsByClassName("tab-contents");
  
    function opentab(tabname){
        for(tablink of tablinks){
            tablink.classList.remove("active-link");
        }
        for(tabcontent of tabcontents){
            tabcontent.classList.remove("active-tab");
        }
        event.currentTarget.classList.add("active-link");
        document.getElementById(tabname).classList.add("active-tab");



    }


</script>

</body>
</html>
