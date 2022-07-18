# Music_Player
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Swapnisha Music Player</title>
    <!-- it is connected to two stylesheets -->
    <link rel="stylesheet" type="text/css" href="Stylesheet_main.css"><!-- this is the main stylesheet -->
    <!-- desktop first approach is used for the same. -->
    <link rel="stylesheet" type="text/css" href="primary page responsive.css"><!-- this is the style sheet with all the media queries -->
    <!-- this script is just for font awesome fonts -->
    <script src="https://kit.fontawesome.com/2d9b67a497.js" crossorigin="anonymous"></script>
</head>
<!-- body -->

<body>
    <!-- top navigation bar -->
    <nav class="navigation-bar">
        <!--This div contains the logo and title of the page-->
        <div class="title-combo">
            <div class="website-logo">
                <img src="media/website_logo.png">
            </div>
            <div class="website-name">
                <h2>
                    Swapnisha
                </h2>
                <h6>
                    Music Player
                </h6>
            </div>
        </div>
        <!-- this is the animated favourites text -->
        <div class="favs">
            <h4>
                Favourites
            </h4>
        </div>
        <!-- this is for search bar -->
        <div class="search-bar">
            <div>
                <!-- magnifying glass- search icon -->
                <i class="fas fa-search search-ico"></i>
            </div>
            <input type="text" name="search" placeholder="Search">
            <div>
                <!-- mic icon -->
                <i class="fas fa-microphone mic-ico"></i>
            </div>
        </div>
        <!-- this is for notification bell -->
        <div class="notification-bell">
            <img src="media/bell_icon.png"> Notifications

        </div>
        <!-- this is for profile picture -->
        <div class="profile-picture">
            <img src="media/music-icon.png">
        </div>
    </nav>
    <!-- this is the main center part of the page and it is divided into two sections, namely section 1 and section 2-->
    <!-- I have separated these sections using the aside tag for each section -->
    <main>
        <!-- aside section 1 -->
        <aside class="aside section-1">
            <!-- this is for the carousel -->
            <div class="outer-carousel">
                <div class="carousel">
                    <!-- these are the 3 images in the carousel -->
                    <img src="media/crousel/carousel1.jpg">
                    <img src="media/crousel/carousel2.jpg">
                    <img src="media/crousel/carousel3.jpg">
                </div>
            </div>
            <!-- this is the latest release section -->
            <div class="latest-release">
                <h1 style="margin-bottom: 12px;">
                    Latest Release
                </h1>
                <!-- this is the content of the latest release section -->
                <!-- it will contain the "cards" -->
                <div class="latest-release-content">
                    <!-- first card -->
                    <div class="card">
                        <div>
                            <!-- image corresponding to the card -->
                            <img src="media/songs/willow.jpeg">
                            <!-- play button, which will be shown on hover on the card image -->
                            <div class="play-button">
                                <i class="fas fa-play" style="width:45%; height:45%; display:inline-block"></i>
                            </div>
                        </div>
                        <!-- it will contain the name and date of release of the song -->
                        <div class="song-description">
                            <h3>
                                Wildest Dreams
                            </h3>
                            <p>
                                Dec , 2020
                            </p>
                        </div>
                        <!-- if someone clicks on the three dots, options will be shown to the user for further action -->
                        <div class="options">
                            <label for="latest-release-checkbox"><i class="fas fa-ellipsis-h"></i></label>
                            <input type="checkbox" id="latest-release-checkbox">
                            <div class="latest-release-dropdown">
                                <div class="drop-item">
                                    <!-- if user clicks on play now button, he/she will be taken to the single playlist page -->
                                    <p><i class="fas fa-play-circle"></i> <a href="Single Playlist Screen.html">Play
                                            Now</a></p>
                                </div>
                                <hr>
                                <div class="drop-item">
                                    <p><i class="fas fa-list-ul"></i> Add to Queue</p>
                                </div>
                                <hr>
                                <div class="drop-item">
                                    <p><i class="fas fa-music"></i> Add to playlist</p>
                                </div>
                                <hr>
                                <div class="drop-item">
                                    <p><i class="fas fa-info-circle"></i> Get Info</p>
                                </div>
                            </div>
                            <!-- duration of the song -->
                            <p>
                                4:17
                            </p>
                        </div>
                    </div>
                    <!-- second card -->
                    <div class="card">
                        <div>
                            <img src="media/songs/Weeknd.jpg">
                            <div class="play-button">
                                <i class="fas fa-play" style="width:45%; height:45%; display:inline-block"></i>
                            </div>
                        </div>
                        <div class="song-description">
                            <h3>
                               Gerua
                            </h3>
                            <p>
                                Dec, 2020
                            </p>
                        </div>
                        <div class="options">
                            <label for="latest-release-checkbox2"><i class="fas fa-ellipsis-h"></i></label>
                            <input type="checkbox" id="latest-release-checkbox2">
                            <div class="latest-release-dropdown">
                                <div class="drop-item">
                                    <p><i class="fas fa-play-circle"></i> <a href="Single Playlist Screen.html">Play
                                            Now</a></p>
                                </div>
                                <hr>
                                <div class="drop-item">
                                    <p><i class="fas fa-list-ul"></i> Add to Queue</p>
                                </div>
                                <hr>
                                <div class="drop-item">
                                    <p><i class="fas fa-music"></i> Add to playlist</p>
                                </div>
                                <hr>
                                <div class="drop-item">
                                    <p><i class="fas fa-info-circle"></i> Get Info</p>
                                </div>
                            </div>
                            <p>
                                4:08
                            </p>
                        </div>
                    </div>
                    <!-- third card -->
                    <div class="card">
                        <div>
                            <img src="media/songs/DaBaby.jpg">
                            <div class="play-button">
                                <i class="fas fa-play" style="width:45%; height:45%; display:inline-block"></i>
                            </div>
                        </div>
                        <div class="song-description">
                            <h3>
                                Ranjha
                            </h3>
                            <p>
                                Dec, 2020
                            </p>
                        </div>
                        <div class="options">
                            <label for="latest-release-checkbox3"><i class="fas fa-ellipsis-h"></i></label>
                            <input type="checkbox" id="latest-release-checkbox3">
                            <div class="latest-release-dropdown">
                                <div class="drop-item">
                                    <p><i class="fas fa-play-circle"></i> <a href="Single Playlist Screen.html">Play
                                            Now</a></p>
                                </div>
                                <hr>
                                <div class="drop-item">
                                    <p><i class="fas fa-list-ul"></i> Add to Queue</p>
                                </div>
                                <hr>
                                <div class="drop-item">
                                    <p><i class="fas fa-music"></i> Add to playlist</p>
                                </div>
                                <hr>
                                <div class="drop-item">
                                    <p><i class="fas fa-info-circle"></i> Get Info</p>
                                </div>
                            </div>
                            <p>
                                4:32
                            </p>
                        </div>
                    </div>
                    <!-- fourth card -->
                    <div class="card">
                        <div>
                            <img src="media/songs/dynamite.jpg">
                            <div class="play-button">
                                <i class="fas fa-play" style="width:45%; height:45%; display:inline-block"></i>
                            </div>
                        </div>
                        <div class="song-description">
                            <h3>
                                Dilbar
                            </h3>
                            <p>
                                Dec, 2020
                            </p>
                        </div>
                        <div class="options">
                            <!-- NOTE THAT POSITION OF OPTIONS DIV IS RELATIVE -->
                            <label for="latest-release-checkbox4"><i class="fas fa-ellipsis-h"></i></label>
                            <input type="checkbox" id="latest-release-checkbox4">
                            <div class="latest-release-dropdown">
                                <!-- POSITION OF LATEST RELEASE DROPDOWN IS ABSOLUTE TO THE RELATIVE OPTIONS. THIS IS VERY IMPORTANT AS THE DROPDOWN BOX SHOULD BE PLACED RELATIVE TO THE PARTICULAR ITEM IN THE LATEST RELEASE SECTION. IT SHOULD NOT BE ABSAOLUTE TO THE WHOLE LATEST RELEASE SECTION. THROUGH THIS PROJECT i UNDERSTOOD THE NEED OF POSITION:ABSOLUTE. ABSOLUTE POSITION AND RELATIVE ARE GENERALLY USED TOGETHER-->
                                <div class="drop-item">
                                    <p><i class="fas fa-play-circle"></i> <a href="Single Playlist Screen.html">Play
                                            Now</a></p>
                                </div>
                                <hr>
                                <div class="drop-item">
                                    <p><i class="fas fa-list-ul"></i> Add to Queue</p>
                                </div>
                                <hr>
                                <div class="drop-item">
                                    <p><i class="fas fa-music"></i> Add to playlist</p>
                                </div>
                                <hr>
                                <div class="drop-item">
                                    <p><i class="fas fa-info-circle"></i> Get Info</p>
                                </div>
                            </div>
                            <p>
                                4:48
                            </p>
                        </div>
                    </div>
                    <!-- fifth card -->
                    <div class="card">
                        <div>
                            <img src="media/songs/shit.png">
                            <div class="play-button">
                                <i class="fas fa-play" style="width:45%; height:45%; display:inline-block"></i>
                            </div>
                        </div>
                        <div class="song-description">
                            <h3>
                                Believer
                            </h3>
                            <p>
                                Dec, 2020
                            </p>
                        </div>
                        <div class="options">
                            <label for="latest-release-checkbox5"><i class="fas fa-ellipsis-h"></i></label>
                            <input type="checkbox" id="latest-release-checkbox5">
                            <div class="latest-release-dropdown">
                                <div class="drop-item">
                                    <p><i class="fas fa-play-circle"></i> <a href="Single Playlist Screen.html">Play
                                            Now</a></p>
                                </div>
                                <hr>
                                <div class="drop-item">
                                    <p><i class="fas fa-list-ul"></i> Add to Queue</p>
                                </div>
                                <hr>
                                <div class="drop-item">
                                    <p><i class="fas fa-music"></i> Add to playlist</p>
                                </div>
                                <hr>
                                <div class="drop-item">
                                    <p><i class="fas fa-info-circle"></i> Get Info</p>
                                </div>
                            </div>
                            <p>
                                5:23
                            </p>
                        </div>
                    </div>
                    <!-- sixth card -->
                    <div class="card">
                        <div>
                            <img src="media/songs/falling.jpg">
                            <div class="play-button">
                                <i class="fas fa-play" style="width:45%; height:45%; display:inline-block"></i>
                            </div>
                        </div>
                        <div class="song-description">
                            <h3>
                                Tere Liye
                            </h3>
                            <p>
                                Dec, 2020
                            </p>
                        </div>
                        <div class="options">
                            <label for="latest-release-checkbox6"><i class="fas fa-ellipsis-h"></i></label>
                            <input type="checkbox" id="latest-release-checkbox6">
                            <div class="latest-release-dropdown">
                                <div class="drop-item">
                                    <p><i class="fas fa-play-circle"></i> <a href="Single Playlist Screen.html">Play
                                            Now</a></p>
                                </div>
                                <hr>
                                <div class="drop-item">
                                    <p><i class="fas fa-list-ul"></i> Add to Queue</p>
                                </div>
                                <hr>
                                <div class="drop-item">
                                    <p><i class="fas fa-music"></i> Add to playlist</p>
                                </div>
                                <hr>
                                <div class="drop-item">
                                    <p><i class="fas fa-info-circle"></i> Get Info</p>
                                </div>
                            </div>
                            <p>
                              2:39
                            </p>
                        </div>
                    </div>
                </div>
            </div>
          
            <!-- this is the music themes part, the one with the tri-gradient background -->
            <div class="music-themes">
                <!-- this div will be the logo of music themes, see the output, the one with 3 squares/rects  -->
                <!-- the logo with orange, green and yellow color -->
                <div class="stations">
                    <div id="div1">
                        <div id="div2">
                            <div id="div3">
                                <img src="media/website_logo.png">
                                <p>Stations</p>
                            </div>
                        </div>
                    </div>
                </div>
                <!-- this is the content part of them themes -->
                <!-- the one which changes colors on hover -->
                <div class="theme-main">
                    <div class="theme-content">
                        <img src="media/music themes/chill.jpg">
                        <p>Vibe</p>
                    </div>
                    <div class="theme-content">
                        <img src="media/music themes/rock.jpg">
                        <p>Rock</p>
                    </div>
                    <div class="theme-content">
                        <img src="media/music themes/love.jpg">
                        <p>Love</p>
                    </div>
                    <div class="theme-content">
                        <img src="media/music themes/pop.jpg">
                        <p>Pop</p>
                    </div>
                    <div class="theme-content">
                        <img src="media/music themes/retro.jpg">
                        <p>Retro</p>
                    </div>
                    <div class="theme-content">
                        <img src="media/music themes/workout.jpg">
                        <p>Gym</p>
                    </div>
                </div>
            </div>
            <!-- this is another themes portion, that electronic, party and road theme -->
            <div class="music-themes-2">
                <!-- 3 divs content -->
                <div class="outer-div">
                    <div class="inner-div">
                        <span>Party</span>
                    </div>
                </div>
                <div class="outer-div">
                    <div class="inner-div">
                        <span>Electronic</span>
                    </div>
                </div>
                <div class="outer-div">
                    <div class="inner-div">
                        <span>Travel</span>
                    </div>
                </div>
            </div>
            <!-- div over -->
            <!-- this div contains the language section of the page -->
            <!-- "language class is common to both hindi and english sections" -->
            <!-- in this way redundancy is handled. considering the re-usability of the code -->
            <div class="language english">
                <!-- latest english section -->
                <h1 class="language-heading">
                    Popular Artist
                </h1>
                <!-- contents of latest bengali -->
                <div class="language-content">
                    <div>
                        <img src="media/latest bengali/shreyaghosal.jpg">
                        <p>Shreya Ghoshal</p>
                    </div>
                    <div>
                        <img src="media/latest bengali/arijitsingh.jpg">
                        <p>Arijit Singh</p>
                    </div>
                    <div>
                        <img src="media/latest bengali/Shaan.jpg">
                        <p>Shaan</p>
                    </div>
                    <div>
                        <img src="media/latest bengali/RDBurman.jpg">
                        <p>RD Burman</p>
                    </div>
                    <div>
                        <img src="media/latest bengali/MannaDey.jpg">
                        <p>MannaDey</p>
                    </div>
                    <div>
                        <img src="media/latest bengali/HemantKumar.jpg">
                        <p>HemantKumar</p>
                    </div>
                </div>
            </div>
            <!-- this is the hindi section -->
            <div class="language hindi">
                <!-- hindi section heading -->
                <h1 class="language-heading">
                    Latest Hindi
                </h1>
                <!-- hindi section contents -->
                <div class="language-content">

                    <div>
                        <img src="media/latest hindi/baarish.jpeg">
                        <p>Ehsaas</p>
                    </div>
                    <div>
                        <img src="media/latest hindi/galiyaan.jpg">
                        <p>Dil se Utar Gaye</p>
                    </div>
                    <div>
                        <img src="media/latest hindi/giveme some sunshine.jpg">
                        <p>Macha Macha Re</p>
                    </div>
                    <div>
                        <img src="media/latest hindi/kaun tujhe.jpg">
                        <p>Rehna Tere Paas</p>
                    </div>
                    <div>
                        <img src="media/latest hindi/tera ban jaunga.jpg">
                        <p>Ishq Nahi Karte</p>
                    </div>
                    <div>
                        <img src="media/latest hindi/tere sang yara.jpg">
                        <p>Tere Saath Ho</p>
                    </div>
                </div>
            </div>
            <div class="language hindi">
                <!-- Bengali section heading -->
                <h1 class="language-heading">
                    Latest Bengali
                </h1>
                <!-- hindi section contents -->
                <div class="language-content">

                    <div>
                        <img src="media/bengali_music/beng_1.jpg">
                        <p>Yaad Kiya Dil Ne</p>
                    </div>
                    <div>
                        <img src="media/bengali_music/beng_2.jpg">
                        <p>Mone pore....</p>
                    </div>
                    <div>
                        <img src="media/bengali_music/beng_3.jpg">
                        <p>Coffee House...</p>
                    </div>
                    <div>
                        <img src="media/bengali_music/beng_4.jpg">
                        <p>Tumi robe nirobe...</p>
                    </div>
                    <div>
                        <img src="media/bengali_music/beng_5.jpg">
                        <p>Amaro porano jaha chai</p>
                    </div>
                    <div>
                        <img src="media/bengali_music/beng_6.jpg">
                        <p>Preme pora baron</p>
                    </div>
                </div>
            </div>
        </aside>
        <!-- one aside section is complete -->
        <!-- now the second aside section will start from here -->
        <!-- the page is responsive. please try reducing the width of the page -->
        <!-- the aside section will collapse and a "more button will be shown to you." -->
        <!-- clicking on this more button, you will be shown the aside section 2  -->
        <!-- its position will be absolute at lower resolutions -->
        <!-- this is the label for that more button -->
        <label for="more"><i class="fas fa-angle-double-left"></i>More</label>
        <!-- this is that more button -->
        <!-- and this is the check box. this will always be hidden -->
        <!-- check the stylesheet_main.css when the label is clicked, this checkbox will be checked -->
        <!-- which will invoke the aside section 2 on lower resolutions -->
        <input type="checkbox" id="more">
        <!-- here starts the section 2 of our page -->
        <aside class="aside section-2">
            <!-- this is the section heading part. the heading will be static -->
            <div class="heading">
                <h1>Playlist</h1>
                <h4>
                    <a href="#queue-option-box">Queue <i class="fas fa-chevron-circle-down"></i></a>
                </h4>
            </div>
            <!-- this is the queue box which will be shown when the user clicks on the Queue button -->
            <!-- it will have 3 options, playlists, favourite songs and Close button. it will close when one clicks on the close button. -->
            <div class="queue-options" id="queue-option-box">
                <p><a href style="color:#007bff; font-weight:bolder;">Playlists</a></p>
                <hr>
                <p><a href style="color:#007bff; font-weight:bolder;">Favourite songs</a></p>
                <hr>
                <p><a href="#" style="color:red; font-weight:bolder;">Close</a></p>
            </div>
            <!-- this is the content of the playlist. it will be dynamic. -->
            <div class="playlist-content">
                <!-- first playlist item -->
                <div class=playlist-item>
                    <div class="left-content">
                        <!-- index -->
                        <div style="margin-right:4px;">
                            01
                        </div>
                        <div class="coverer">
                            <!-- coverer class is for those items which when hovered will show an effect -->
                            <!-- in this effect, when the user hovers on the item, it will show black background -->
                            <!-- with opacity value less than 1 and a play button icon at the center -->
                            <img src="media/playlist/austin-neill-kKlVSrFbjYY-unsplash.jpg">
                            <div class="play-button">
                                <i class="fas fa-play" aria-hidden="true"></i>
                            </div>
                        </div>
                        <!-- name and author of the song -->
                        <div>
                            <div>
                                Rab Ne Bana Di Jodi
                            </div>
                            <p>
                                Roopkumar Rathod
                            </p>
                        </div>
                    </div>
                    <!-- like button -->
                    <div class="right-content">
                        <i class="far fa-heart"></i>
                    </div>
                </div>
                <!-- second playlist item -->
                <div class=playlist-item>
                    <div class="left-content">
                        <div style="margin-right:4px;">
                            02
                        </div>
                        <div class="coverer">
                            <img src="media/playlist/after.jpg">
                            <div class="play-button">
                                <i class="fas fa-play" aria-hidden="true"></i>
                            </div>
                        </div>
                        <div>
                            <div>
                                Sun Raha Hai Na Tu
                            </div>
                            <p>
                                Shreya Ghoshal
                            </p>
                        </div>
                    </div>
                    <div class="right-content">
                        <i class="far fa-heart"></i>
                    </div>
                </div>
                <!-- third playlist item -->
                <div class=playlist-item>
                    <div class="left-content">
                        <div style="margin-right:4px;">
                            03
                        </div>
                        <div class="coverer">
                            <img src="media/playlist/stoney.jpg">
                            <div class="play-button">
                                <i class="fas fa-play" aria-hidden="true"></i>
                            </div>
                        </div>
                        <div>
                            <div>
                                Lovestory
                            </div>
                            <p>
                                Taylor Swift
                            </p>
                        </div>
                    </div>
                    <div class="right-content">
                        <i class="far fa-heart"></i>
                    </div>
                </div>
                <!-- fourth playlist item -->
                <div class=playlist-item>
                    <div class="left-content">
                        <div style="margin-right:4px;">
                            04
                        </div>
                        <div class="coverer">
                            <img src="media/playlist/stoney.jpg">
                            <div class="play-button">
                                <i class="fas fa-play" aria-hidden="true"></i>
                            </div>
                        </div>
                        <div>
                            <div>
                                Love Me Like You Do
                            </div>
                            <p>
                                Ellie Gouldling
                            </p>
                        </div>
                    </div>
                    <div class="right-content">
                        <i class="far fa-heart"></i>
                    </div>
                </div>
                <!-- fifth playlist item -->
                <div class=playlist-item>
                    <div class="left-content">
                        <div style="margin-right:4px;">
                            05
                        </div>
                        <div class="coverer">
                            <img src="media/playlist/stoney.jpg">
                            <div class="play-button">
                                <i class="fas fa-play" aria-hidden="true"></i>
                            </div>
                        </div>
                        <div>
                            <div>
                                Cheap Thrills
                            </div>
                            <p>
                                Sia
                            </p>
                        </div>
                    </div>
                    <div class="right-content">
                        <i class="far fa-heart"></i>
                    </div>
                </div>
                <!-- sixth playlist item -->
                <div class=playlist-item>
                    <div class="left-content">
                        <div style="margin-right:4px;">
                            06
                        </div>
                        <div class="coverer">
                            <img src="media/playlist/after.jpg">
                            <div class="play-button">
                                <i class="fas fa-play" aria-hidden="true"></i>
                            </div>
                        </div>
                        <div>
                            <div>
                                Banjara
                            </div>
                            <p>
                                Mohammad Irfan
                            </p>
                        </div>
                    </div>
                    <div class="right-content">
                        <i class="far fa-heart"></i>
                    </div>
                </div>
                <!-- seventh playlist item -->
                <div class=playlist-item>
                    <div class="left-content">
                        <div style="margin-right:4px;">
                            07
                        </div>
                        <div class="coverer">
                            <img src="media/playlist/beer.jpg">
                            <div class="play-button">
                                <i class="fas fa-play" aria-hidden="true"></i>
                            </div>
                        </div>
                        <div>
                            <div>
                                Shabashiyaan
                            </div>
                            <p>
                                Shilpa Rao
                            </p>
                        </div>
                    </div>
                    <div class="right-content">
                        <i class="far fa-heart"></i>
                    </div>
                </div>
                <!-- eighth playlist item -->
                <div class=playlist-item>
                    <div class="left-content">
                        <div style="margin-right:4px;">
                            08
                        </div>
                        <div class="coverer">
                            <img src="media/playlist/beer.jpg">
                            <div class="play-button">
                                <i class="fas fa-play" aria-hidden="true"></i>
                            </div>
                        </div>
                        <div>
                            <div>
                                Zinda
                            </div>
                            <p>
                               Sunidhi Chauhan
                            </p>
                        </div>
                    </div>
                    <div class="right-content">
                        <i class="far fa-heart"></i>
                    </div>
                </div>
                <!-- ninth playlist item -->
                <div class=playlist-item>
                    <div class="left-content">
                        <div style="margin-right:4px;">
                            09
                        </div>
                        <div class="coverer">
                            <img src="media/playlist/stoney.jpg">
                            <div class="play-button">
                                <i class="fas fa-play" aria-hidden="true"></i>
                            </div>
                        </div>
                        <div>
                            <div>
                                Deja Vu
                            </div>
                            <p>
                                Post Malone & Justin Beiber
                            </p>
                        </div>
                    </div>
                    <div class="right-content">
                        <i class="far fa-heart"></i>
                    </div>
                </div>
                <!-- tenth playlist item -->
                <div class=playlist-item>
                    <div class="left-content">
                        <div style="margin-right:4px;">
                            10
                        </div>
                        <div class="coverer">
                            <img src="media/popular artists/billie eilish.jpg">
                            <div class="play-button">
                                <i class="fas fa-play" aria-hidden="true"></i>
                            </div>
                        </div>
                        <div>
                            <div>
                                Bad Guy
                            </div>
                            <p>
                                Billie Eilish
                            </p>
                        </div>
                    </div>
                    <div class="right-content">
                        <i class="far fa-heart"></i>
                    </div>
                </div>
                <!-- eleventh playlist item -->
                <div class=playlist-item>
                    <div class="left-content">
                        <div style="margin-right:4px;">
                            11
                        </div>
                        <div class="coverer">
                            <img src="media/songs/sorry.jpg">
                            <div class="play-button">
                                <i class="fas fa-play" aria-hidden="true"></i>
                            </div>
                        </div>
                        <div>
                            <div>
                                Sorry
                            </div>
                            <p>
                                Justin Bieber
                            </p>
                        </div>
                    </div>
                    <div class="right-content">
                        <i class="far fa-heart"></i>
                    </div>
                </div>
                <!-- twelfth playlist item -->
                <div class=playlist-item>
                    <div class="left-content">
                        <div style="margin-right:4px;">
                            12
                        </div>
                        <div class="coverer">
                            <img src="https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/166e992b-4534-4bd8-bb41-3be395f82cde/daojfrr-facc1540-40b8-455f-b8b6-ba4f14738b32.png/v1/fill/w_894,h_894,q_75,strp/bts___wings_by_goldendesigncover-daojfrr.png?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwic3ViIjoidXJuOmFwcDo3ZTBkMTg4OTgyMjY0MzczYTVmMGQ0MTVlYTBkMjZlMCIsImF1ZCI6WyJ1cm46c2VydmljZTppbWFnZS5vcGVyYXRpb25zIl0sIm9iaiI6W1t7InBhdGgiOiIvZi8xNjZlOTkyYi00NTM0LTRiZDgtYmI0MS0zYmUzOTVmODJjZGUvZGFvamZyci1mYWNjMTU0MC00MGI4LTQ1NWYtYjhiNi1iYTRmMTQ3MzhiMzIucG5nIiwid2lkdGgiOiI8PTg5NCIsImhlaWdodCI6Ijw9ODk0In1dXX0.VXwplpd8rbngUYyW306GbKo_PdH8B_g3gw3fr1V0Mes">
                            <div class="play-button">
                                <i class="fas fa-play" aria-hidden="true"></i>
                            </div>
                        </div>
                        <div>
                            <div>
                                Golden
                            </div>
                            <p>
                                BTS
                            </p>
                        </div>
                    </div>
                    <div class="right-content">
                        <i class="far fa-heart"></i>
                    </div>
                </div>
            </div>
        </aside>
    </main>
    <!-- main part of the page is over. -->
    <!-- this is the footer part. -->
    <!-- its position will be fixed to the screen bottom. -->
    <footer>
        <div class="active-song-description">
            <!-- song image -->
            <div id="song-image">
                <img src="media/latest bengali/Galiyaan.jpg">
            </div>
            <!-- song name and author -->
            <div class="song-desc">
                <div>
                    Galiyaan
                </div>
                <div>
                    Ankit Tiwari
                </div>
                <!-- heart icon and ban icon -->
            </div>
            <div class="heart-and-ban-icon">
                <span>
                    <i class="far fa-heart"></i>
                </span>
                <span>
                    <i class="fas fa-ban"></i>
                </span>
            </div>
        </div>
        <!-- these are the main player controls -->
        <div class="player">
            <div class="controls">
                <div><i class="fas fa-random"></i></div>
                <div><i class="fas fa-step-backward"></i></div>
                <div><i class="fas fa-pause-circle"></i></div>
                <div><i class="fas fa-step-forward"></i></div>
                <div><i class="fas fa-redo"></i></div>
            </div>
            <!-- this is the slider -->
            <div id="slider">
                <!-- current time -->
                <div class="time">
                    1:39
                </div>
                <div class="slidecontainer">
                    <input type="range" min="0" max="100" value="0" class="slider" id="myRange">
                </div>
                <!-- total time -->
                <div class="time">
                    4:44
                </div>
            </div>
        </div>
        <!-- other icons including the volume slider and all -->
        <div class="extras">
            <div>
                <i class="fas fa-list-ul"></i>
            </div>
            <div>
                <i class="fas fa-laptop"></i>
            </div>
            <div>
                <i class="fas fa-volume-up"></i>
            </div>
            <div class="slidecontainer" style="width:30%;">
                <input type="range" min="0" max="100" value="0" class="slider" id="myRange" style="margin-top:0px;">
            </div>
            <div>
                <i class="fas fa-expand-alt"></i>
            </div>
        </div>
    </footer>
</body>

</html>
