<!DOCTYPE html>
<html>
<head lang="en">
    <meta charset="UTF-8">

    <!--Page Title-->
    <title>SIGNAL Bucket List</title>

    <!--Meta Keywords and Description-->
    <meta name="keywords" content="SIGNAL">
    <meta name="description" content="SIGNAL Bucket List">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no"/>

    /*<!--Favicon-->
    <link rel="apple-touch-icon" sizes="57x57" href="favicon/apple-icon-57x57.png">
    <link rel="apple-touch-icon" sizes="60x60" href="favicon/apple-icon-60x60.png">
    <link rel="apple-touch-icon" sizes="72x72" href="favicon/apple-icon-72x72.png">
    <link rel="apple-touch-icon" sizes="76x76" href="favicon/apple-icon-76x76.png">
    <link rel="apple-touch-icon" sizes="114x114" href="favicon/apple-icon-114x114.png">
    <link rel="apple-touch-icon" sizes="120x120" href="favicon/apple-icon-120x120.png">
    <link rel="apple-touch-icon" sizes="144x144" href="favicon/apple-icon-144x144.png">
    <link rel="apple-touch-icon" sizes="152x152" href="favicon/apple-icon-152x152.png">
    <link rel="apple-touch-icon" sizes="180x180" href="favicon/apple-icon-180x180.png">
    <link rel="icon" type="image/png" sizes="192x192"  href="favicon/android-icon-192x192.png">
    <link rel="icon" type="image/png" sizes="32x32" href="favicon/favicon-32x32.png">
    <link rel="icon" type="image/png" sizes="96x96" href="favicon/favicon-96x96.png">
    <link rel="icon" type="image/png" sizes="16x16" href="favicon/favicon-16x16.png">
    <link rel="icon" type="image/png" href="favicon/favicon-32x32.png">
    <link rel="manifest" href="favicon/manifest.json">
    <meta name="msapplication-TileColor" content="#ffffff">
    <meta name="msapplication-TileImage" content="favicon/ms-icon-144x144.png">
    <meta name="theme-color" content="#ffffff">

    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css">
    <link rel="stylesheet" href="css/style.css">
    <link href="https://fonts.googleapis.com/css?family=Montserrat&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css?family=Roboto+Condensed&display=swap" rel="stylesheet">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js"></script>*/

</head>

<body>
    <div class="container">
        <div class="row">
            <!-- For demo purpose -->
            <div class="col-lg-12 mx-auto mb-5 text-white text-center">
                <h1 class="display-4">SIGNAL Bucket List</h1>
                <p class="lead mb-0"> The goals that we want to achieve together as a LIFE group this semester </p>
                <!-- <p class="lead">Snippet by <a href="https://bootstrapious.com/snippets" class="text-white">
                            <u>Bootstrapious</u></a> -->
                <!-- </p> -->
            </div>
                <!-- END -->
        </div>
        <div class="row">
            <div class="col-md-4 mb-4">
                <div class="bg-white rounded-lg p-5 shadow">
                    <h2 class="h6 font-weight-bold text-center mb-4">Hikes</h2>
            
                    <!-- Progress bar 1 -->
                    <div class="progress mx-auto" id="bar0" data-value='0'>
                        <span class="progress-left">
                            <span class="progress-bar border-primary"></span>
                        </span>
                        <span class="progress-right">
                            <span class="progress-bar border-primary"></span>
                        </span>
                        <div class="progress-value w-100 h-100 rounded-circle d-flex align-items-center justify-content-center">
                            <div class="h2 font-weight-bold"><span id="value0">0</span> / 10</div>
                        </div>
                    </div>
                    <!-- END -->
                </div>
            </div>
            <div class="col-md-4 mb-4">
                <div class="bg-white rounded-lg p-5 shadow">
                    <h2 class="h6 font-weight-bold text-center mb-4">Unique Meetups</h2>
            
                    <!-- Progress bar 1 -->
                    <div class="progress mx-auto" id="bar1" data-value='0'>
                        <span class="progress-left">
                            <span class="progress-bar border-primary"></span>
                        </span>
                        <span class="progress-right">
                            <span class="progress-bar border-primary"></span>
                        </span>
                        <div class="progress-value w-100 h-100 rounded-circle d-flex align-items-center justify-content-center">
                            <div class="h2 font-weight-bold"><span id="value1">0</span> / 20</div>
                        </div>
                    </div>
                    <!-- END -->
                </div>
            </div>
            <div class="col-md-4 mb-4">
                <div class="bg-white rounded-lg p-5 shadow">
                    <h2 class="h6 font-weight-bold text-center mb-4">Breakfasts</h2>
            
                    <!-- Progress bar 1 -->
                    <div class="progress mx-auto" id="bar2" data-value='0'>
                        <span class="progress-left">
                            <span class="progress-bar border-primary"></span>
                        </span>
                        <span class="progress-right">
                            <span class="progress-bar border-primary"></span>
                        </span>
                        <div class="progress-value w-100 h-100 rounded-circle d-flex align-items-center justify-content-center">
                            <div class="h2 font-weight-bold"><span id="value2">0</span> / 100</div>
                        </div>
                    </div>
                    <!-- END -->
                </div>
            </div>
            <div class="col-md-4 mb-4">
                <div class="bg-white rounded-lg p-5 shadow">
                    <h2 class="h6 font-weight-bold text-center mb-4">Acts of Service</h2>
            
                    <!-- Progress bar 1 -->
                    <div class="progress mx-auto" id="bar3" data-value='0'>
                        <span class="progress-left">
                            <span class="progress-bar border-primary"></span>
                        </span>
                        <span class="progress-right">
                            <span class="progress-bar border-primary"></span>
                        </span>
                        <div class="progress-value w-100 h-100 rounded-circle d-flex align-items-center justify-content-center">
                            <div class="h2 font-weight-bold"><span id="value3">0</span> / 30</div>
                        </div>
                    </div>
                    <!-- END -->
                </div>
            </div>
            <div class="col-md-4 mb-4">
                <div class="bg-white rounded-lg p-5 shadow">
                    <h2 class="h6 font-weight-bold text-center mb-4">SOAPs or Reflections</h2>
            
                    <!-- Progress bar 1 -->
                    <div class="progress mx-auto" id="bar4" data-value='4'>
                        <span class="progress-left">
                            <span class="progress-bar border-primary"></span>
                        </span>
                        <span class="progress-right">
                            <span class="progress-bar border-primary"></span>
                        </span>
                        <div class="progress-value w-100 h-100 rounded-circle d-flex align-items-center justify-content-center">
                            <div class="h2 font-weight-bold"><span id="value4">0</span> / 200</div>
                        </div>
                    </div>
                    <!-- END -->
                </div>
            </div>
            <div class="col-md-4 mb-4">
                <div class="bg-white rounded-lg p-5 shadow">
                    <h2 class="h6 font-weight-bold text-center mb-4">Books Read</h2>
            
                    <!-- Progress bar 1 -->
                    <div class="progress mx-auto" id="bar5" data-value='0'>
                        <span class="progress-left">
                            <span class="progress-bar border-primary"></span>
                        </span>
                        <span class="progress-right">
                            <span class="progress-bar border-primary"></span>
                        </span>
                        <div class="progress-value w-100 h-100 rounded-circle d-flex align-items-center justify-content-center">
                            <div class="h2 font-weight-bold"><span id="value5">0</span> / 20</div>
                        </div>
                    </div>
                    <!-- END -->
                </div>
            </div>
            <div class="col-md-4 mb-4">
                <div class="bg-white rounded-lg p-5 shadow">
                    <h2 class="h6 font-weight-bold text-center mb-4">Church Visits</h2>
            
                    <!-- Progress bar 1 -->
                    <div class="progress mx-auto" id="bar6" data-value='0'>
                        <span class="progress-left">
                            <span class="progress-bar border-primary"></span>
                        </span>
                        <span class="progress-right">
                            <span class="progress-bar border-primary"></span>
                        </span>
                        <div class="progress-value w-100 h-100 rounded-circle d-flex align-items-center justify-content-center">
                            <div class="h2 font-weight-bold"><span id="value6">0</span> / 60</div>
                        </div>
                    </div>
                    <!-- END -->
                </div>
            </div>
            <div class="col-md-4 mb-4">
                <div class="bg-white rounded-lg p-5 shadow">
                    <h2 class="h6 font-weight-bold text-center mb-4">LG Outing</h2>
            
                    <!-- Progress bar 1 -->
                    <div class="progress mx-auto" id="bar7" data-value='0'>
                        <span class="progress-left">
                            <span class="progress-bar border-primary"></span>
                        </span>
                        <span class="progress-right">
                            <span class="progress-bar border-primary"></span>
                        </span>
                        <div class="progress-value w-100 h-100 rounded-circle d-flex align-items-center justify-content-center">
                            <div class="h2 font-weight-bold"><span id="value7">0</span> / 1</div>
                        </div>
                    </div>
                    <!-- END -->
                </div>
            </div>
            <div class="col-md-4 mb-4">
                <div class="bg-white rounded-lg p-5 shadow">
                    <h2 class="h6 font-weight-bold text-center mb-4">Times of Giving</h2>
            
                    <!-- Progress bar 1 -->
                    <div class="progress mx-auto" id="bar8" data-value='0'>
                        <span class="progress-left">
                            <span class="progress-bar border-primary"></span>
                        </span>
                        <span class="progress-right">
                            <span class="progress-bar border-primary"></span>
                        </span>
                        <div class="progress-value w-100 h-100 rounded-circle d-flex align-items-center justify-content-center">
                            <div class="h2 font-weight-bold"><span id="value8">0</span> / 50</div>
                        </div>
                    </div>
                    <!-- END -->
                </div>
            </div>
        </div>
    </div>
    
<script src="js/scripts.js"></script>

</body>

</html>
