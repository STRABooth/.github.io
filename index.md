<html>

<head>
	<meta charset="UTF-8" />
	<meta name="viewport" content="width=device-width, initial-scale=1.0" />
	<meta http-equiv="X-UA-Compatible" content="ie=edge" />
	<link rel="stylesheet" href="bootstrap-5.3.2-dist/css/bootstrap.min.css" /> 
	<script src="bootstrap-5.3.2-dist/js/bootstrap.min.js"></script>
	<link href="css/templatemo-style.css" rel="stylesheet" />
	<link href="css/new-style.css" rel="stylesheet" />
	<link href="css/two_style.css" rel="stylesheet" />

</head>

<body> 
	<div class="container">
		<div class="placeholder">
			<div class="placeholder-content">
				<div class="tm-site-text-box">
					<h1 class="tm-site-title">STRABooth</h1>
					<h6 class="tm-site-description"> Spatial-Temporal Representation Alignment for Customzied Video Generation.</h6>
				</div>
			</div>
		</div>
		<main>
			<header class="row tm-welcome-section">
			<h2 class="col-12 text-center tm-section-title">DreamVideo: Composing Your Dream Videos with Customized Subject and Motion</h2>
				<h2 class="col-12 text-center tm-section-title"><b>Under review on Siggraph Asia 2025</b></h2>
		<p class="col-12 text-center author-section">
		<a class="author-section-a" href="#">ANONYMOUS AUTHOR(S)</a>
		<p class="col-12 text-center abstract-section" style="word-break:break-all;word-wrap:break-word">
					Customized video generation aims to produce videos that faithfully preserve the subject's appearance from reference images while maintaining temporally consistent motion from reference videos. Existing methods primarily rely on reconstruction losses, which capture local details but lack high-level control over subject identity and motion dynamics. To address this limitation, we propose STRABooth, a framework that imposes explicit spatial and temporal supervision during training to steer the representation learning of diffusion-based video generation. For spatial enhancement, we
incorporate semantic features from a self-supervised vision encoder (e.g., DINO) to supervise spatial representation learning, enabling the model to perceive the subject's global structure and semantic consistency beyond low-level textures. For temporal supervision, we leverage optical flow representations extracted from pretrained models, which capture object-level motion trajectories that are structurally coherent and disentangled from appearance. Together, these high-level supervisory signals provide holistic guidance over both appearance and motion during training, significantly enhancing subject fidelity and motion controllability. To further improve the integration of subject and motion information, we introduce a staged injection strategy that aligns with the coarse-to-fine nature of diffusion generation, applying motion guidance in early steps and appearance refinement in later ones. Extensive experiments show that STRABooth achieves state of-the-art performance in subject and motion customization, demonstrating
its effectiveness for controllable text-to-video generation.
			</p>
			</header>
			<div class="gray_div font-serif rw-r-container">
				<div class="text-2xl lg:text-4xl leading-none pb-2 text-center"> Overview: <i>Summary of the Generated Videos</i>
				</div>
				<video class="video-center" width="896" height="504" controls>
  <source src="assets/mp4/overview.mp4" type="video/mp4">
  Your browser does not support the video tag.
				</video>
				<div class="block_bottom">
				</div>
			</div>
			<div class="font-serif rw-r-container">
				<div class="text-2xl lg:text-4xl leading-none pb-2 text-center">
					Video Customization with <i>both</i> Subjects and Motions
				</div>
				<div class="text-base lg:text-lg pb-2 text-center ">
					You can generate videos flexibly with any subject and any motion.
				</div>
				<!-- Gallery row 1 -->
				<div class="row tm-gallery subject-container">
					<div id="tm-gallery-page-pizza" class="tm-gallery-page subject">
						<!-- Subject 1: dog -->
						<article class="col-md-4 tm-gallery-item">
							<figure>
								<div class="subject_img" style="display: flex">
									<img src="assets/images/subject/dog1.jpg" />
									<img src="assets/images/subject/dog2.jpg" />
									<img src="assets/images/subject/dog3.jpg" />
									<img src="assets/images/subject/dog4.jpg" />
								</div>
								<figcaption>
									<h4 class="tm-gallery-title text-center">dog</h4>
								</figcaption>
							</figure>
						</article>
						<!-- Subject 2: sloth -->
						<article class="col-md-4 tm-gallery-item">
							<figure>
								<div class="subject_img" style="display: flex">
									<img src="assets/images/subject/sloth1.jpg" />
									<img src="assets/images/subject/sloth2.jpg" />
									<img src="assets/images/subject/sloth3.jpg" />
									<img src="assets/images/subject/sloth4.jpg" />
								</div>
								<figcaption>
									<h4 class="tm-gallery-title text-center">sloth</h4>
								</figcaption>
							</figure>
						</article>
						<!-- Subject 3: monster -->
						<article class="col-md-4 tm-gallery-item">
							<figure>
								<div class="subject_img" style="display: flex">
									<img src="assets/images/subject/monster1.jpg" />
									<img src="assets/images/subject/monster2.jpg" />
									<img src="assets/images/subject/monster3.jpg" />
									<img src="assets/images/subject/monster4.jpg" />
								</div>
								<figcaption>
									<h4 class="tm-gallery-title text-center">monster</h4>
								</figcaption>
							</figure>
						</article>
					</div>
				</div><!-- gallery row 1 -->
			</div>
			
			
				    
