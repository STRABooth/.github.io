<!DOCTYPE html>
<html>

<head>
	<meta charset="UTF-8" />
	<meta name="viewport" content="width=device-width, initial-scale=1.0" />
	<meta http-equiv="X-UA-Compatible" content="ie=edge" />
	<title>STRABooth</title>
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
			ANONYMOUS AUTHOR(S)
			<p class="col-12 text-center abstract-section" style="word-break:break-all;word-wrap:break-word">
				Customized generation using diffusion models has made impressive progress in image generation, but remains unsatisfactory in the challenging video generation task, as it requires the controllability of both subjects and motions.
				To that end, we present DreamVideo, a novel approach to generating personalized videos from a few static images of the desired subject and a few videos of target motion.
				DreamVideo decouples this task into two stages, subject learning and motion learning, by leveraging a pre-trained video diffusion model.
				The subject learning aims to accurately capture the fine appearance of the subject from provided images, which is achieved by combining textual inversion and fine-tuning of our carefully designed identity adapter.
				In motion learning, we architect a motion adapter and fine-tune it on the given videos to effectively model the target motion pattern.
				Combining these two lightweight and efficient adapters allows for flexible customization of any subject with any motion.
				Extensive experimental results demonstrate the superior performance of our DreamVideo over the state-of-the-art methods for customized video generation.
				We have now made the source code and models publicly available.
			</p>
</body>
</html>
