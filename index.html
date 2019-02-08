<?php
require_once 'core/init.php';

if(logged_in() === TRUE) {
    header('location: index.php');
}

if(isset($_POST['login_student']) and isset($_POST['student_name'])){
    $name = $_POST['student_name'];
    $password = $_POST['student_password'];
    $user_id = $_POST['student_user_id'];
    if($name == "") {
        echo " * Username Field is Required <br />";
    }

    if($password == "") {
        echo " * Password Field is Required <br />";
    }

    if($user_id == "") {
        echo " * User Id Field is Required <br />";
    }


    if($name && $password && $user_id) {
        if(userExists($user_id) == TRUE) {
            $login = login($name, $password,$user_id);
            if($login) {
                $userdata = userdata($user_id);

                $_SESSION['user_id'] = $userdata['given_id'];
                $_SESSION['name'] = $userdata['name'];
                echo $_SESSION['name'];

                header('location: student_dashboard.php');
                exit();

            } else {
                echo "Incorrect username/password combination";
            }
        } else{
            echo "user does not exists";
        }
    }
}
elseif(isset($_POST['login_teacher']) and isset($_POST['name'])){
    $name = $_POST['name'];
    echo $_POST['name'];
    $password = $_POST['password'];
    $user_id = $_POST['user_id'];
    if($name == "") {
        echo " * Username Field is Required <br />";
    }

    if($password == "") {
        echo " * Password Field is Required <br />";
    }

    if($user_id == "") {
        echo " * User Id Field is Required <br />";
    }

    if($name && $password && $user_id) {
        if(userExists($user_id) == TRUE) {
            $login = login($name, $password,$user_id);
            if($login) {
                $userdata = userdata($user_id);
                $_SESSION['user_id'] = $userdata['given_id'];
                $_SESSION['name'] = $userdata['name'];
                header('location: teacher_dashboard.php');
                exit();
            } else {
                echo "Incorrect username/password combination";
            }
        } else{
            echo "user does not exists";
        }
    }
}
?>


<!DOCTYPE HTML>
<html>
	<head>
	<meta charset="utf-8">
	<meta http-equiv="X-UA-Compatible" content="IE=edge">
	<title>Healthy School</title>
	<link href="https://fonts.googleapis.com/css?family=Roboto:300,400,700" rel="stylesheet">
	
	<!-- Animate.css -->
	<link rel="stylesheet" href="css/animate.css">
	<!-- Icomoon Icon Fonts-->
	<link rel="stylesheet" href="css/icomoon.css">
	<!-- Themify Icons-->
	<link rel="stylesheet" href="css/themify-icons.css">
	<!-- Bootstrap  -->
	<link rel="stylesheet" href="css/bootstrap.css">

	<!-- Magnific Popup -->
	<link rel="stylesheet" href="css/magnific-popup.css">

	<!-- Owl Carousel  -->
	<link rel="stylesheet" href="css/owl.carousel.min.css">
	<link rel="stylesheet" href="css/owl.theme.default.min.css">

	<!-- Theme style  -->
	<link rel="stylesheet" href="css/style.css">

	<!-- Modernizr JS -->
	<script src="js/modernizr-2.6.2.min.js"></script>
	<!-- FOR IE9 below -->
	<!--[if lt IE 9]>
	<script src="js/respond.min.js"></script>
	<![endif]-->

	</head>
	<body>
		
	<div class="gtco-loader"></div>
	
	<div id="page">

	
	<div class="page-inner">
	<nav class="gtco-nav" role="navigation">
		<div class="gtco-container">
			
			<div class="row">
				<div class="col-sm-4 col-xs-12">
					<div id="gtco-logo"><a href="index.php">Healthy School <em>.</em></a></div>
				</div>
				<div class="col-xs-8 text-right menu-1">
					<ul>
						<li><a href="#gtco-products">Awards</a></li>
						<li><a href="feedback.php">Feedback</a></li>
						<li><a href="#gtco-footer">About</a></li>
						<li><a href="#gtco-footer">Contact Us</a></li>
						</ul>
				</div>
			</div>
			
		</div>
	</nav>
	
	<header id="gtco-header" class="gtco-cover" role="banner" style="background-image: url(images/img_4.jpg)">
		<div class="overlay"></div>
		<div class="gtco-container">
			<div class="row">
				<div class="col-md-12 col-md-offset-0 text-left">
					

					<div class="row row-mt-15em">
						<div class="col-md-7 mt-text animate-box" data-animate-effect="fadeInUp">
							<span class="intro-text-small">Welcome to *School Name*</span>
							<h1>"A Healthy Mind resides in a Healthy Body"</h1>
						</div>
						<div class="col-md-4 col-md-push-1 animate-box" data-animate-effect="fadeInRight">
							<div class="form-wrap">
								<div class="tab">
									<ul class="tab-menu">
										<li class="active gtco-first"><a href="#" data-tab="login_student">Student/Parent Login</a></li>
										<li class="gtco-second"><a href="#" data-tab="login_teacher">Teacher Login</a></li>
									</ul>
									<div class="tab-content">
										<div class="tab-content-inner active" data-content="login_student">
											<form action="<?php echo $_SERVER['PHP_SELF'] ?>" method="POST">
												<div class="row form-group">
													<div class="col-md-12">
														<label for="name">Name</label>
														<input  name="student_name" type="text" class="form-control" id="username">
													</div>
												</div>
												<div class="row form-group">
													<div class="col-md-12">
														<label for="user_id">User Id</label>
														<input type="text" name="student_user_id" class="form-control" id="password">
													</div>
												</div>
												<div class="row form-group">
													<div class="col-md-12">
														<label for="password">Password</label>
														<input type="password" name="student_password" class="form-control" id="password2">
													</div>
												</div>

												<div class="row form-group">
													<div class="col-md-12">
														<input name="login_student" type="submit" class="btn btn-primary" value="Login">
													</div>
												</div>
											</form>
										</div>
										<div class="tab-content-inner " data-content="login_teacher">
											<form action="<?php echo $_SERVER['PHP_SELF'] ?>" method="POST">
												<div class="row form-group">
													<div class="col-md-12">
														<label for="name">Name</label>
														<input type="text" class="form-control" name="name" id="username">
													</div>
												</div>
                                                <div class="row form-group">
                                                    <div class="col-md-12">
                                                        <label for="teacher_id">Teacher Id</label>
                                                        <input type="text" class="form-control" name="user_id" id="username">
                                                    </div>
                                                </div>
												<div class="row form-group">
													<div class="col-md-12">
														<label for="password">Password</label>
														<input type="password" class="form-control" name="password" id="password">
													</div>
												</div>

												<div class="row form-group">
													<div class="col-md-12">
														<input name="login_teacher" type="submit" class="btn btn-primary" value="Login">
													</div>
                                            </form>
												</div>
										</div>

									</div>
								</div>
							</div>
						</div>
					</div>
							
					
				</div>
			</div>
		</div>
	</header>


        <div id="gtco-counter" class="gtco-section">
            <div class="gtco-container">

                <div class="row">
                    <div class="col-md-8 col-md-offset-2 text-center gtco-heading animate-box">
                        <h2>HEALTH REPORT</h2>
                        <p>Presenting our digital report about the progress and improvement in the health of our school students and introduction of new health projects</p>
                    </div>
                </div>

                <div class="row">

                    <div class="col-md-3 col-sm-6 animate-box" data-animate-effect="fadeInLeft">
                        <div class="feature-center">
						<span class="icon">
							<i class="ti-settings"></i>
						</span>
                            <span class="counter js-counter" data-from="0" data-to="2207" data-speed="5000" data-refresh-interval="50">1</span>
                            <span class="counter-label">Students enrolled</span>

                        </div>
                    </div>
                    <div class="col-md-3 col-sm-6 animate-box" data-animate-effect="fadeInLeft">
                        <div class="feature-center">
						<span class="icon">
							<i class="ti-face-smile"></i>
						</span>
                            <span class="counter js-counter" data-from="0" data-to="900" data-speed="5000" data-refresh-interval="50">1</span>
                            <span class="counter-label">Happy Students</span>
                        </div>
                    </div>
                    <div class="col-md-3 col-sm-6 animate-box" data-animate-effect="fadeInLeft">
                        <div class="feature-center">
						<span class="icon">
							<i class="ti-briefcase"></i>
						</span>
                            <span class="counter js-counter" data-from="0" data-to="40" data-speed="5000" data-refresh-interval="50">1</span>
                            <span class="counter-label">Projects Introduced</span>
                        </div>
                    </div>
                    <div class="col-md-3 col-sm-6 animate-box" data-animate-effect="fadeInLeft">
                        <div class="feature-center">
						<span class="icon">
							<i class="ti-time"></i>
						</span>
                            <span class="counter js-counter" data-from="0" data-to="21202" data-speed="5000" data-refresh-interval="50">1</span>
                            <span class="counter-label">Hours Spent</span>

                        </div>
                    </div>

                </div>
            </div>
        </div>

        <div id="gtco-products">
            <div class="gtco-container">
                <div class="row">
                    <div class="col-md-8 col-md-offset-2 text-center gtco-heading">
                        <h2>AWARDS GALLERY</h2>
                        <p>Presenting glimpse of award ceremony of previous best maintained profiles.YOU NEVER KNOW MAYBE YOUR KID WILL BE IN NEXT UPDATED GALLERY</p>
                    </div>
                </div>
                <div class="row">
                    <div class="owl-carousel owl-carousel-carousel">
                        <div class="item">
                            <a href="#"><img src="images/index1.jpeg" alt="Prize" height="160px"></a>
                        </div>
                        <div class="item">
                            <a href="#"><img src="images/index2.jpeg" alt="Prize" height="160px"></a>
                        </div>
                        <div class="item">
                            <a href="#"><img src="images/index3.jpeg" alt="Prize" height="160px"></a>
                        </div>
                        <div class="item">
                            <a href="#"><img src="images/index4.jpeg" alt="Prize" height="160px"></a>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <div id="gtco-features" class="border-bottom">
            <div class="gtco-container">
                <div class="row">
                    <div class="col-md-8 col-md-offset-2 text-center gtco-heading animate-box">
                        <h2>FEATURES</h2>
                        <p>Presenting the salient features of our portal.</p></p>
                    </div>
                </div>
                <div class="row">
                    <div class="col-md-3 col-sm-6">
                        <div class="feature-center animate-box" data-animate-effect="fadeIn">
						<span class="icon">
							<i class="ti-vector"></i>
						</span>
                            <h3>KNOW BETTER</h3>
                            <p>Profile maintained for each student, which will make you know better about their physical and mental health.</p>
                        </div>
                    </div>
                    <div class="col-md-3 col-sm-6">
                        <div class="feature-center animate-box" data-animate-effect="fadeIn">
						<span class="icon">
							<i class="ti-tablet"></i>
						</span>
                            <h3>FULLY RESPONSIVE</h3>
                            <p>Our portal will be available 24*7 and will be always upfront for your queries related to health issues.</p>
                        </div>
                    </div>
                    <div class="col-md-3 col-sm-6">
                        <div class="feature-center animate-box" data-animate-effect="fadeIn">
						<span class="icon">
							<i class="ti-settings"></i>
						</span>
                            <h3>CHART VIEWS</h3>
                            <p>Chart representation to understand students growth and % contentment of nutrition in each of them.</p>
                        </div>
                    </div>
                    <div class="col-md-3 col-sm-6">
                        <div class="feature-center animate-box" data-animate-effect="fadeIn">
						<span class="icon">
							<i class="ti-ruler-pencil"></i>
						</span>
                            <h3>SUGGESTIONS</h3>
                            <p>Special recommendations in diet plans or any further check-up will be suggested on our portal.</p>
                        </div>
                    </div>



                </div>
            </div>
        </div>

	</div>
    <?php include 'core/footer.php';?>

	</div>

	<div class="gototop js-top">
		<a href="#" class="js-gotop"><i class="icon-arrow-up"></i></a>
	</div>
	
	<!-- jQuery -->
	<script src="js/jquery.min.js"></script>
	<!-- jQuery Easing -->
	<script src="js/jquery.easing.1.3.js"></script>
	<!-- Bootstrap -->
	<script src="js/bootstrap.min.js"></script>
	<!-- Waypoints -->
	<script src="js/jquery.waypoints.min.js"></script>
	<!-- Carousel -->
	<script src="js/owl.carousel.min.js"></script>
	<!-- countTo -->
	<script src="js/jquery.countTo.js"></script>
	<!-- Magnific Popup -->
	<script src="js/jquery.magnific-popup.min.js"></script>
	<script src="js/magnific-popup-options.js"></script>
	<!-- Main -->
	<script src="js/main.js"></script>

	</body>
</html>

