# NetworkMediaFinalProject

//StartPage.html is the start part.

//Things need to be addedd:
//1. News, Account Settings, Messages page
//2. It would be more fun to have time limit in the game.
//3. More detailed story

<!DOCTYPE html>
<html>

<head>
    <title>W3.CSS Template</title>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
    <link rel="stylesheet" href="https://www.w3schools.com/lib/w3-theme-blue-grey.css">
    <link rel='stylesheet' href='https://fonts.googleapis.com/css?family=Open+Sans'>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <style>
        html,
        body,
        h1,
        h2,
        h3,
        h4,
        h5 {
            font-family: "Open Sans", sans-serif
        }

    </style>
    <script src="libs/jquery-3.6.1.min.js"></script>
</head>

<body class="w3-theme-l5">

    <!-- Navbar -->
    <div class="w3-top">
        <div class="w3-bar w3-theme-d2 w3-left-align w3-large">
            <a class="w3-bar-item w3-button w3-hide-medium w3-hide-large w3-right w3-padding-large w3-hover-white w3-large w3-theme-d2"
                href="javascript:void(0);" onclick="openNav()"><i class="fa fa-bars"></i></a>
            <a href="StartPage.html" class="w3-bar-item w3-button w3-padding-large w3-theme-d4"><i
                    class="fa fa-home w3-margin-right"></i>GIS</a>
            <a href="#" onclick="NotYet()" class="w3-bar-item w3-button w3-hide-small w3-padding-large w3-hover-white" title="News"><i
                    class="fa fa-globe"></i></a>
            <a href="#" onclick="NotYet()" class="w3-bar-item w3-button w3-hide-small w3-padding-large w3-hover-white"
                title="Account Settings"><i class="fa fa-user"></i></a>
            <a href="#" onclick="NotYet()" class="w3-bar-item w3-button w3-hide-small w3-padding-large w3-hover-white" title="Messages"><i
                    class="fa fa-envelope"></i></a>
            <div class="w3-dropdown-hover w3-hide-small">
                <button class="w3-button w3-padding-large" title="Notifications"><i class="fa fa-bell"></i><span
                        class="w3-badge w3-right w3-small w3-green">3</span></button>
                <div class="w3-dropdown-content w3-card-4 w3-bar-block" style="width:300px">
                    <a href="#" onclick="Focus()" class="w3-bar-item w3-button">One new friend request</a>
                    <a href="#" onclick="Focus()" class="w3-bar-item w3-button">Bailey posted on your wall</a>
                    <a href="#" onclick="Focus()" class="w3-bar-item w3-button">Hailey likes your post</a>
                </div>
            </div>
            <a href="UserPage.html" class="w3-bar-item w3-button w3-hide-small w3-right w3-padding-large w3-hover-white"
                title="My Account">
                <img src="Sample_User_Icon.png" class="w3-circle" style="height:23px;width:23px" alt="Avatar">
            </a>
        </div>
    </div>

    <!-- Navbar on small screens -->
    <div id="navDemo" class="w3-bar-block w3-theme-d2 w3-hide w3-hide-large w3-hide-medium w3-large">
        <a href="#" onclick="NotYet()" class="w3-bar-item w3-button w3-padding-large">News</a>
        <a href="#" onclick="NotYet()" class="w3-bar-item w3-button w3-padding-large">Account Settings</a>
        <a href="#" onclick="NotYet()" class="w3-bar-item w3-button w3-padding-large">Messages</a>
        <a href="UserPAge.html" class="w3-bar-item w3-button w3-padding-large">My Profile</a>
    </div>

    <!-- Page Container -->
    <div class="w3-container w3-content" style="max-width:1400px;margin-top:80px">
        <!-- The Grid -->
        <div class="w3-row">
            <!-- Left Column -->
            <div class="w3-col m3">
                <!-- Profile -->
                <div class="w3-card w3-round w3-white">
                    <div class="w3-container">
                        <h4 class="w3-center">My Profile</h4>
                        <p class="w3-center"><img src="/img/profile.jpg" class="w3-circle"
                                style="height:106px;width:106px" alt="Avatar"></p>
                        <hr>
                        <p><i class="fa fa-pencil fa-fw w3-margin-right w3-text-theme"></i> Designer, UI</p>
                        <p><i class="fa fa-home fa-fw w3-margin-right w3-text-theme"></i> Korea</p>
                        <p><i class="fa fa-birthday-cake fa-fw w3-margin-right w3-text-theme"></i> May 7, 2002</p>
                    </div>
                </div>
                <br>

                <!-- Accordion -->
                <div class="w3-card w3-round">
                    <div class="w3-white">
                        <button onclick="myFunction('Demo1')" class="w3-button w3-block w3-theme-l1 w3-left-align"><i
                                class="fa fa-circle-o-notch fa-fw w3-margin-right"></i> My Groups</button>
                        <div id="Demo1" class="w3-hide w3-container">
                            <p>Amateur Orchestra</p>
                            <p>Korea Traditional Percussion Club</p>
                        </div>
                        <button onclick="myFunction('Demo2')" class="w3-button w3-block w3-theme-l1 w3-left-align"><i
                                class="fa fa-calendar-check-o fa-fw w3-margin-right"></i> My Events</button>
                        <div id="Demo2" class="w3-hide w3-container">
                            <p><span style="font-weight: bold;">12/21</span></br>Network Media Final Project</p>
                        </div>
                        <button onclick="myFunction('Demo3')" class="w3-button w3-block w3-theme-l1 w3-left-align"><i
                                class="fa fa-users fa-fw w3-margin-right"></i> My Photos</button>
                        <div id="Demo3" class="w3-hide w3-container">
                            <div class="w3-row-padding">
                                <br>
                                <div class="w3-half">
                                    <img src="/img/cat.JPG" style="width:100%" class="w3-margin-bottom">
                                </div>
                                <div class="w3-half">
                                    <img src="/img/ACES.JPG" style="width:100%" class="w3-margin-bottom">
                                </div>
                                <div class="w3-half">
                                    <img src="/img/rain.jpg" style="width:100%" class="w3-margin-bottom">
                                </div>
                                <div class="w3-half">
                                    <img src="/img/plants.jpg" style="width:100%" class="w3-margin-bottom">
                                </div>
                                <div class="w3-half">
                                    <img src="/img/airplane.jpg" style="width:100%" class="w3-margin-bottom">
                                </div>
                                <div class="w3-half">
                                    <img src="/img/eye.jpg" style="width:100%" class="w3-margin-bottom">
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <br>

                <!-- Interests -->
                <div class="w3-card w3-round w3-white w3-hide-small">
                    <div class="w3-container">
                        <p>Interests</p>
                        <p>
                            <span class="w3-tag w3-small w3-theme-d5">Music</span>
                            <span class="w3-tag w3-small w3-theme-d4">Fantasy</span>
                            <span class="w3-tag w3-small w3-theme-d3">Novels</span>
                            <span class="w3-tag w3-small w3-theme-d2">Games</span>
                            <span class="w3-tag w3-small w3-theme-d1">Friends</span>
                            <span class="w3-tag w3-small w3-theme">Doding</span>
                            <span class="w3-tag w3-small w3-theme-l1">Friends</span>
                            <span class="w3-tag w3-small w3-theme-l2">Food</span>
                            <span class="w3-tag w3-small w3-theme-l3">Design</span>
                            <span class="w3-tag w3-small w3-theme-l4">Art</span>
                            <span class="w3-tag w3-small w3-theme-l5">Photos</span>
                        </p>
                    </div>
                </div>
                <br>

                <!-- Alert Box -->
                <div class="w3-container w3-display-container w3-round w3-theme-l4 w3-border w3-theme-border w3-margin-bottom w3-hide-small"
                    id="alertparent">
                    <span class="w3-button w3-theme-l3 w3-display-topright" id="alertbox">
                        <i class="fa fa-remove"></i>
                    </span>
                    <p><strong>Hey!</strong></p>
                    <p>People are looking at your profile. Find out who.</p>
                </div>

                <!-- End Left Column -->
            </div>

            <!-- Middle Column -->
            <div class="w3-col m7">

                <div class="w3-row-padding">
                    <div class="w3-col m12">
                        <div class="w3-card w3-round w3-white">
                            <div class="w3-container w3-padding">
                                <h6 class="w3-opacity">What's happening?</h6>
                                <p contenteditable="true" class="w3-border w3-padding" id="demo">Status: Feeling Blue
                                </p>
                                <button type="button" class="w3-button w3-theme" onclick="ChangePost()"><i
                                        class="fa fa-pencil"></i>
                                     Post</button>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="w3-container w3-card w3-white w3-round w3-margin"><br>
                    <img src="/img/bailey.JPG" alt="Avatar" class="w3-left w3-circle w3-margin-right"
                        style="width:60px">
                    <span class="w3-right w3-opacity" id = "min1">1 min</span>
                    <h4>Bailey Catterel</h4><br>
                    <hr class="w3-clear">
                    <p>Hey Sun! Please contact us whenever possible. Where the hell did you go? I can't call you. I'm in front of your house.</p>
                    <div class="w3-row-padding" style="margin:0 -16px">
                        <div class="w3-half">
                            <img src="/img/policeline.jpg" style="width:100%; height: width;" alt="Northern Lights"
                                class="w3-margin-bottom">
                        </div>
                        <div class="w3-half">
                            <img src="/img/apartment.jpg" style="width:100%; height: width;" alt="Nature" class="w3-margin-bottom">
                        </div>
                    </div>
                    <button type="button" class="w3-button w3-theme-d1 w3-margin-bottom" onclick="Like()"><i
                            class="fa fa-thumbs-up"></i>
                         Like</button>
                    <button type="button" onclick="myFunction('Demo5')" class="w3-button w3-theme-d2 w3-margin-bottom"><i class="fa fa-comment"></i>
                         Comment</button>
                    <div id="Demo5" class="w3-hide w3-container" style="padding: 15px;">
                        <input type="text" id="comment1" style="height: 80px; width: 100%; text-align: center;" value="It's useless."><br>
                    </div>

                </div>

                <div class="w3-container w3-card w3-white w3-round w3-margin"><br>
                    <img src="/img/hailey.JPG" alt="Avatar" class="w3-left w3-circle w3-margin-right"
                        style="width:60px">
                    <span class="w3-right w3-opacity" id="min2">16 min</span>
                    <h4>Hailey Smart</h4><br>
                    <hr class="w3-clear">
                    <p>The Internet is wierd. Why GIS is not working smoothly? Uh...</p>
                    <button type="button" class="w3-button w3-theme-d1 w3-margin-bottom" onclick="Like()"><i
                            class="fa fa-thumbs-up"></i>
                         Like</button>
                    <button type="button" onclick="myFunction('Demo6')" class="w3-button w3-theme-d2 w3-margin-bottom"><i class="fa fa-comment"></i>
                         Comment</button>
                        <div id="Demo6" class="w3-hide w3-container" style="padding: 15px; ">
                            <input type="text" id="comment1" style="height: 80px; width: 100%; text-align: center;" value="You can't contact them. Give up."><br>
                        </div>
                </div>

                <div class="w3-container w3-card w3-white w3-round w3-margin"><br>
                    <img src="/img/clayton.jpg" alt="Avatar" class="w3-left w3-circle w3-margin-right"
                        style="width:60px">
                    <span class="w3-right w3-opacity" id="min3">32 min</span>
                    <h4>Clayton Doe</h4><br>
                    <hr class="w3-clear">
                    <p>Look what I've found!</p>
                    <img src="/img/truth.jpg" style="width:100%" class="w3-margin-bottom">
                    <p>Isn't this a postcard you made in the justice class? I don't know who threw it away, but I picked it up anyway.</p>
                    <button type="button" class="w3-button w3-theme-d1 w3-margin-bottom" onclick="Like()"><i
                            class="fa fa-thumbs-up"></i>
                         Like</button>
                    <button type="button" onclick="myFunction('Demo7')" class="w3-button w3-theme-d2 w3-margin-bottom"><i class="fa fa-comment"></i>
                         Comment</button>
                        <div id="Demo7" class="w3-hide w3-container" style="padding: 15px; ">
                            <input type="text" id="comment1" style="height: 80px; width: 100%; text-align: center;" value="Let me out."><br>
                        </div>
                </div>

                <!-- End Middle Column -->
            </div>

            <!-- Right Column -->
            <div class="w3-col m2">
                <div class="w3-card w3-round w3-white w3-center">
                    <div class="w3-container">
                        <p>Upcoming Events:</p>
                        <img src="/img/christmas.jpg" alt="Christmas" style="width:100%;">
                        <p><strong>Christmas</strong></p>
                        <p>Sunday</p>
                        <p><button onclick="myFunction('Demo4')" class="w3-button w3-block w3-theme-l4"><i
                            class="fa fa-calendar-check-o fa-fw w3-margin-right"></i>Info</button></p>
                            <div id="Demo4" class="w3-hide w3-container">
                        <p><span style="font-weight: bold;">18:00</span></br>Dinner with Bailey</p>
                    </div>
                    </div>
                </div>
                <br>

                <div class="w3-card w3-round w3-white w3-center" >
                    <div class="w3-container" id="friendRequest">
                        <p>Friend Request</p>
                        <img src="/img/TFOO.png" alt="Avatar" style="width:50%"><br>
                        <span>Tiger Fry-O-Octs</span>
                        <div class="w3-row w3-opacity">
                            <div class="w3-half">
                                <button class="w3-button w3-block w3-green w3-section" title="Accept" onclick="NotYet()"><i
                                        class="fa fa-check"></i></button>
                            </div>
                            <div class="w3-half">
                                <button class="w3-button w3-block w3-red w3-section" title="Decline" onclick="NoFriend()"><i
                                        class="fa fa-remove"></i></button>
                            </div>
                        </div>
                    </div>
                </div>
                <br>

                <div class="w3-card w3-round w3-white w3-padding-16 w3-center">
                    <img src="/img/aiAD/슬라이드1.JPG" style="width:100%;height: 100%;padding: 5px;" >
                </div>
                <br>

                <div class="w3-card w3-round w3-white w3-padding-32 w3-center">
                    <p><i class="fa fa-bug w3-xxlarge"></i></p>
                </div>

                <!-- End Right Column -->
            </div>

            <!-- End Grid -->
        </div>

        <!-- End Page Container -->
    </div>
    <br>

    <!-- Footer -->
    <footer class="w3-container w3-theme-d3 w3-padding-16">
        <h5>G.I.S.</h5>
    </footer>

    <footer class="w3-container w3-theme-d5">
        <p>Powered by <a href="https://www.w3schools.com/w3css/default.asp" target="_blank">w3.css</a></p>
    </footer>

    <script>
        // Accordion
        function myFunction(id) {
            var x = document.getElementById(id);
            if (x.className.indexOf("w3-show") == -1) {
                x.className += " w3-show";
                x.previousElementSibling.className += " w3-theme-d1";
            } else {
                x.className = x.className.replace("w3-show", "");
                x.previousElementSibling.className =
                    x.previousElementSibling.className.replace(" w3-theme-d1", "");
            }
        }

        // Used to toggle the menu on smaller screens when clicking on the menu button
        function openNav() {
            var x = document.getElementById("navDemo");
            if (x.className.indexOf("w3-show") == -1) {
                x.className += " w3-show";
            } else {
                x.className = x.className.replace(" w3-show", "");
            }
        }

        var postTime = 0;
        function ChangePost() {
            if (postTime == 0) {
                document.getElementById('demo').innerHTML = "Don't click the post button"
                postTime++;
            }
            else {
                document.getElementById('demo').innerHTML = "I said it."
            }

        }

        function Like() {
            alert("You like them than me?");
        }

        function Focus(){
            alert("Focus on me.");
        }
        function NotYet(){
            alert("Not Yet.");
        }
        function NoFriend(){
            $('#friendRequest').hide();
        }
        $(document).ready(function () {
            $('#alertbox').click(function () {
                $(this.parentElement).hide();
                setTimeout(function () {
                    $('#alertparent').show();
                }, 3000);
            });

        })


        $(document).ready(function () {
            var date = new Date();
            var start = date.getMinutes();
            var min = date.getMinutes();
            //var min = 3;
            $('#min1').text(1+min-start+" min");
            $('#min2').text(16+min-start+" min");
            $('#min3').text(32+min-start+" min");
            setInterval(function(){
                date = new Date();
                min = date.getMinutes();
                var sub = min-start;
                if(sub<0){sub+=60;}
                $('#min1').text(1+min-start+" min");
                $('#min2').text(16+min-start+" min");
                $('#min3').text(32+min-start+" min");

            },60000);
        
        })
    </script>

</body>

</html>
