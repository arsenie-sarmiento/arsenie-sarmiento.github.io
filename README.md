<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Arsenie S.</title>
    <!-- BOOTSTRAP -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <!-- CUSTOM CSS -->
    <link rel="stylesheet" href="css/mouse_animation.css">
    <!-- <link rel="stylesheet" href="css/main_stylesheet.css"> -->
    <link href="/css/head.css" rel="stylesheet">
    <link href="/css/main.css" rel="stylesheet">
    <link href="/css/nav.css" rel="stylesheet">
    <!-- WEB FONT -->
    <link href="https://fonts.googleapis.com/css2?family=Albert+Sans:ital,wght@0,100..900;1,100..900&display=swap" rel="stylesheet">
    <!-- <link href="https://fonts.googleapis.com/css2?family=Albert+Sans:ital,wght@0,100..900;1,100..900&display=swap" rel="stylesheet"> -->
</head>
<body>
    <nav class="navbar d-flex justify-content-center">
        <ul class="navbar-nav">
            <!-- HOVER EXPAND -->
            <li class="nav-item nav-link-logo"><a href="#scrollSpy-head" class="link-logo">
                <span>
                    <img alt="arsenie-sarmiento-signature" src="/media/sign.png">
                     <!-- <p>Arsenie</p> -->
                    <!-- <a href="#">
                    </a> -->
                </span>
            </a></li>       
            <!-- APPS & WEBSITES -->
            <li class="nav-item"><a href="#scrollSpy-development" class="nav-link">
                <span>
                    <svg 
                        xmlns="http://www.w3.org/2000/svg"
                        viewBox="0 0 512 512"
                        class="svg-inline--fa fa-solid fa-palette fa-w-16 fa-2x">
                    >
                    <g class="fa-group"></g>
                    <path
                        fill="currentColor"
                        d="M156.6 384.9L125.7 354c-8.5-8.5-11.5-20.8-7.7-32.2c3-8.9 7-20.5 11.8-33.8L24 288c-8.6 0-16.6-4.6-20.9-12.1s-4.2-16.7 .2-24.1l52.5-88.5c13-21.9 36.5-35.3 61.9-35.3l82.3 0c2.4-4 4.8-7.7 7.2-11.3C289.1-4.1 411.1-8.1 483.9 5.3c11.6 2.1 20.6 11.2 22.8 22.8c13.4 72.9 9.3 194.8-111.4 276.7c-3.5 2.4-7.3 4.8-11.3 7.2l0 82.3c0 25.4-13.4 49-35.3 61.9l-88.5 52.5c-7.4 4.4-16.6 4.5-24.1 .2s-12.1-12.2-12.1-20.9l0-107.2c-14.1 4.9-26.4 8.9-35.7 11.9c-11.2 3.6-23.4 .5-31.8-7.8zM384 168a40 40 0 1 0 0-80 40 40 0 1 0 0 80z"
                        class="fa-primary">
                    </path></svg></span>
                <span class="link-text">Projects</span>
            </a></li>
            <!-- WIP -->
            <li class="nav-item"><a href="#scrollSpy-wip" class="nav-link">
                <span>
                    <svg 
                        xmlns="http://www.w3.org/2000/svg"
                        viewBox="0 0 512 512"
                        class="svg-inline--fa fa-solid fa-palette fa-w-16 fa-2x">
                    <g class="fa-group"></g>
                    <path
                        fill="currentColor"
                        d="M240.8 4.8C250.3 10.6 256 20.9 256 32l0 72 89 0c3.6-13.8 16.1-24 31-24l88 0c26.5 0 48 21.5 48 48s-21.5 48-48 48l-88 0c-14.9 0-27.4-10.2-31-24l-89 0 0 72c0 11.1-5.7 21.4-15.2 27.2s-21.2 6.4-31.1 1.4l-192-96C6.8 151.2 0 140.1 0 128s6.8-23.2 17.7-28.6l192-96c9.9-5 21.7-4.4 31.1 1.4zM288 256c0-17.7 14.3-32 32-32l160 0c17.7 0 32 14.3 32 32l0 64c0 17.7-14.3 32-32 32l-160 0c-17.7 0-32-14.3-32-32l0-64zM32 384l96 0c17.7 0 32 14.3 32 32l0 64c0 17.7-14.3 32-32 32l-96 0c-17.7 0-32-14.3-32-32l0-64c0-17.7 14.3-32 32-32zm192 0l256 0c17.7 0 32 14.3 32 32l0 64c0 17.7-14.3 32-32 32l-256 0c-17.7 0-32-14.3-32-32l0-64c0-17.7 14.3-32 32-32z"
                        class="fa-primary"></path>
                    </svg></span>
                <span class="link-text">Work-In-Progress</span>
            </a></li>
            <!-- ARTWORKS -->
            <li class="nav-item"><a href="#scrollSpy-arts" class="nav-link">
                <span>
                    <svg 
                        xmlns="http://www.w3.org/2000/svg"
                        viewBox="0 0 512 512"
                        class="svg-inline--fa fa-solid fa-palette fa-w-16 fa-2x">
                    <g class="fa-group"></g>
                    <path
                        fill="currentColor"
                        d="M512 256c0 .9 0 1.8 0 2.7c-.4 36.5-33.6 61.3-70.1 61.3L344 320c-26.5 0-48 21.5-48 48c0 3.4 .4 6.7 1 9.9c2.1 10.2 6.5 20 10.8 29.9c6.1 13.8 12.1 27.5 12.1 42c0 31.8-21.6 60.7-53.4 62c-3.5 .1-7 .2-10.6 .2C114.6 512 0 397.4 0 256S114.6 0 256 0S512 114.6 512 256zM128 288a32 32 0 1 0 -64 0 32 32 0 1 0 64 0zm0-96a32 32 0 1 0 0-64 32 32 0 1 0 0 64zM288 96a32 32 0 1 0 -64 0 32 32 0 1 0 64 0zm96 96a32 32 0 1 0 0-64 32 32 0 1 0 0 64z"
                        class="fa-primary"></path>
                    </svg></span>
                    <span class="link-text">Artworks</span>
            </a></li>    
            <li class="nav-item"><a href="#scrollSpy-about" class="nav-link">
                <span>
                    <svg 
                        xmlns="http://www.w3.org/2000/svg"
                        viewBox="0 0 610 610"
                        class="svg-inline--fa fa-solid fa-palette fa-w-16 fa-2x">
                    <g class="fa-group"></g>
                    <path
                        fill="currentColor"
                        d="M64 32C28.7 32 0 60.7 0 96L0 416c0 35.3 28.7 64 64 64l448 0c35.3 0 64-28.7 64-64l0-320c0-35.3-28.7-64-64-64L64 32zm80 256l64 0c44.2 0 80 35.8 80 80c0 8.8-7.2 16-16 16L80 384c-8.8 0-16-7.2-16-16c0-44.2 35.8-80 80-80zm-32-96a64 64 0 1 1 128 0 64 64 0 1 1 -128 0zm256-32l128 0c8.8 0 16 7.2 16 16s-7.2 16-16 16l-128 0c-8.8 0-16-7.2-16-16s7.2-16 16-16zm0 64l128 0c8.8 0 16 7.2 16 16s-7.2 16-16 16l-128 0c-8.8 0-16-7.2-16-16s7.2-16 16-16zm0 64l128 0c8.8 0 16 7.2 16 16s-7.2 16-16 16l-128 0c-8.8 0-16-7.2-16-16s7.2-16 16-16z"
                        class="fa-primary"></path>
                    </svg></span>
                    <span class="link-text">About Me</span>
            </a></li>
        </ul>
    </nav>
    <div data-bs-spy="scroll" data-bs-target=".navbar" data-bs-root-margin="0px 0px -30%" data-bs-smooth-scroll="true" class="content-container" tabindex="0">
        <header class="row d-flex justify-content-center align-middle" id="scrollSpy-head">
            <!-- <div class="col-sm-9 container-fluid" id="profile-home"> -->
            <img src="media/profile.png" alt="Art Profile Image" class="img-fluid rounded col-sm-8 container-fluid" id="profile-home">
            <!-- </div> -->
            <div class="col-sm-4" id="profile-text">
                <h4 class="text-center">Hi, I'm</h4>
                <h1 class="text-center">Arsenie</h1>
            </div>
        </header>
        <aside>
            <center>
                <hr>
                <a href="#scrollSpy-development">View works</a>
            <!-- <center>
                <a href="projects.html">Get to know through my <strong>works</strong>!</a>
            </center> -->
            <!-- https://codepen.io/2xsamurai/pen/WwmjKQ -->
            <div class="scroll-downs">
                <div class="mousey">
                  <div class="scroller"></div>
                </div>
              </div>
            </center>
            <div id="scrollSpy-about" class="container-fluid portfolio-section">
                <h2>About Me</h2>
                <!-- <p>"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."</p> -->
                <!-- BADGES -->
                <p class="badge badge-light">Animator</p>
                <p class="badge badge-light">Coder</p>
                <p class="badge badge-light">Cinephile</p>
                <p class="badge badge-light">Cyclist</p>
                <p class="badge badge-light">Casual Fragment Writer</p>
                <p class="badge badge-light">Theatre Kid</p>
                
                <!-- Education -->
                <!-- <span>
                    <svg 
                        xmlns="http://www.w3.org/2000/svg"
                        viewBox="0 0 512 512"
                        class="svg-inline--fa fa-solid fa-palette fa-w-16 fa-2x">
                    >
                    <g class="fa-group"></g>
                    <path
                        fill="currentColor"
                        d="M156.6 384.9L125.7 354c-8.5-8.5-11.5-20.8-7.7-32.2c3-8.9 7-20.5 11.8-33.8L24 288c-8.6 0-16.6-4.6-20.9-12.1s-4.2-16.7 .2-24.1l52.5-88.5c13-21.9 36.5-35.3 61.9-35.3l82.3 0c2.4-4 4.8-7.7 7.2-11.3C289.1-4.1 411.1-8.1 483.9 5.3c11.6 2.1 20.6 11.2 22.8 22.8c13.4 72.9 9.3 194.8-111.4 276.7c-3.5 2.4-7.3 4.8-11.3 7.2l0 82.3c0 25.4-13.4 49-35.3 61.9l-88.5 52.5c-7.4 4.4-16.6 4.5-24.1 .2s-12.1-12.2-12.1-20.9l0-107.2c-14.1 4.9-26.4 8.9-35.7 11.9c-11.2 3.6-23.4 .5-31.8-7.8zM384 168a40 40 0 1 0 0-80 40 40 0 1 0 0 80z"
                        class="fa-primary portfolio-icons">
                    </path></svg></span> -->
                <hr>
                <span>Year 2 BICT Software Engineering Student</span>
                <hr>
                
                <h5> Language and Tools </h5>
                <div class="d-flex w-50">
                    <p dir="auto">
                        <a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/7a982fd7ff2590bd9c4c0c804d36ec84f4b6a54ce4a062e939b1455f619bf975/68747470733a2f2f63646e2e6a7364656c6976722e6e65742f67682f64657669636f6e732f64657669636f6e2f69636f6e732f68746d6c352f68746d6c352d706c61696e2e737667">
                       <img align="left" alt="HTML" width="30px" src="https://camo.githubusercontent.com/7a982fd7ff2590bd9c4c0c804d36ec84f4b6a54ce4a062e939b1455f619bf975/68747470733a2f2f63646e2e6a7364656c6976722e6e65742f67682f64657669636f6e732f64657669636f6e2f69636f6e732f68746d6c352f68746d6c352d706c61696e2e737667" data-canonical-src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-plain.svg" style="max-width: 100%;"></a>
                    </p>
                    <p dir="auto">
                        <a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/3902a23a4ee524225c3626a76a19391fe4a457e9c70e331e7d51abdfa1d76dbf/68747470733a2f2f63646e2e6a7364656c6976722e6e65742f67682f64657669636f6e732f64657669636f6e2f69636f6e732f637373332f637373332d706c61696e2e737667">
                       <img align="left" alt="CSS" width="30px" src="https://camo.githubusercontent.com/3902a23a4ee524225c3626a76a19391fe4a457e9c70e331e7d51abdfa1d76dbf/68747470733a2f2f63646e2e6a7364656c6976722e6e65742f67682f64657669636f6e732f64657669636f6e2f69636f6e732f637373332f637373332d706c61696e2e737667" data-canonical-src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-plain.svg" style="max-width: 100%;"></a>
                    </p>
                    <p dir="auto">
                        <a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/3d0ddeed2c709ed1cbce62a9c624d0f719d5ed695567a2eef03d61a70c7ff336/68747470733a2f2f63646e2e6a7364656c6976722e6e65742f67682f64657669636f6e732f64657669636f6e2f69636f6e732f6a6176617363726970742f6a6176617363726970742d706c61696e2e737667">
                       <img align="left" alt="JavaScript" width="30px" src="https://camo.githubusercontent.com/3d0ddeed2c709ed1cbce62a9c624d0f719d5ed695567a2eef03d61a70c7ff336/68747470733a2f2f63646e2e6a7364656c6976722e6e65742f67682f64657669636f6e732f64657669636f6e2f69636f6e732f6a6176617363726970742f6a6176617363726970742d706c61696e2e737667" data-canonical-src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-plain.svg" style="max-width: 100%;"></a>
                    </p>
                    <p dir="auto">
                        <a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/ac2c78e8df70559d7d499277c0e6c195c7768920d51b9b99dd4c98d4ff540123/68747470733a2f2f63646e2e6a7364656c6976722e6e65742f67682f64657669636f6e732f64657669636f6e2f69636f6e732f747970657363726970742f747970657363726970742d706c61696e2e737667">
                       <img align="left" alt="TypeScript" width="30px" src="https://camo.githubusercontent.com/ac2c78e8df70559d7d499277c0e6c195c7768920d51b9b99dd4c98d4ff540123/68747470733a2f2f63646e2e6a7364656c6976722e6e65742f67682f64657669636f6e732f64657669636f6e2f69636f6e732f747970657363726970742f747970657363726970742d706c61696e2e737667" data-canonical-src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-plain.svg" style="max-width: 100%;"></a>
                    </p>
                    <p dir="auto">
                        <a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/5b2a8527be6ce73521cdb521a1033b92ff7b1860f79585f66ec30ea75ab253e4/68747470733a2f2f63646e2e6a7364656c6976722e6e65742f67682f64657669636f6e732f64657669636f6e2f69636f6e732f6c696e75782f6c696e75782d6f726967696e616c2e737667">
                       <img align="left" alt="Linux" width="30px" src="https://camo.githubusercontent.com/5b2a8527be6ce73521cdb521a1033b92ff7b1860f79585f66ec30ea75ab253e4/68747470733a2f2f63646e2e6a7364656c6976722e6e65742f67682f64657669636f6e732f64657669636f6e2f69636f6e732f6c696e75782f6c696e75782d6f726967696e616c2e737667" data-canonical-src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" style="max-width: 100%;"></a>
                    </p>
                    <p dir="auto">
                        <a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/aed5f69c00ea3fd8c8bc70b89d236efae340eb3024526fd11bcba51c80c4aa40/68747470733a2f2f63646e2e6a7364656c6976722e6e65742f67682f64657669636f6e732f64657669636f6e2f69636f6e732f72656163742f72656163742d6f726967696e616c2e737667">
                       <img align="left" alt="React" width="30px" src="https://camo.githubusercontent.com/aed5f69c00ea3fd8c8bc70b89d236efae340eb3024526fd11bcba51c80c4aa40/68747470733a2f2f63646e2e6a7364656c6976722e6e65742f67682f64657669636f6e732f64657669636f6e2f69636f6e732f72656163742f72656163742d6f726967696e616c2e737667" data-canonical-src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" style="max-width: 100%;"></a>
                    </p>
                    <p dir="auto">
                        <a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/2cde166000bd4271614ef8c0a7e435af8a087c05f4d5a36f1945663d363bd463/68747470733a2f2f63646e2e6a7364656c6976722e6e65742f67682f64657669636f6e732f64657669636f6e2f69636f6e732f6e6f64656a732f6e6f64656a732d6f726967696e616c2e737667">
                       <img align="left" alt="NodeJS" width="30px" src="https://camo.githubusercontent.com/2cde166000bd4271614ef8c0a7e435af8a087c05f4d5a36f1945663d363bd463/68747470733a2f2f63646e2e6a7364656c6976722e6e65742f67682f64657669636f6e732f64657669636f6e2f69636f6e732f6e6f64656a732f6e6f64656a732d6f726967696e616c2e737667" data-canonical-src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" style="max-width: 100%;"></a>
                    </p>
                    <p dir="auto">
                        <a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/0d5534dd6a655164d3127c270557a5e39450dec8c22f71a9830359b6bd8e749b/68747470733a2f2f63646e2e6a7364656c6976722e6e65742f67682f64657669636f6e732f64657669636f6e2f69636f6e732f707974686f6e2f707974686f6e2d706c61696e2e737667">
                       <img align="left" alt="Python" width="30px" src="https://camo.githubusercontent.com/0d5534dd6a655164d3127c270557a5e39450dec8c22f71a9830359b6bd8e749b/68747470733a2f2f63646e2e6a7364656c6976722e6e65742f67682f64657669636f6e732f64657669636f6e2f69636f6e732f707974686f6e2f707974686f6e2d706c61696e2e737667" data-canonical-src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-plain.svg" style="max-width: 100%;"></a>
                    </p>
                    <p dir="auto">
                        <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" fill="currentColor" class="bi bi-bootstrap" viewBox="0 0 16 16">
                            <path d="M5.062 12h3.475c1.804 0 2.888-.908 2.888-2.396 0-1.102-.761-1.916-1.904-2.034v-.1c.832-.14 1.482-.93 1.482-1.816 0-1.3-.955-2.11-2.542-2.11H5.062zm1.313-4.875V4.658h1.78c.973 0 1.542.457 1.542 1.237 0 .802-.604 1.23-1.764 1.23zm0 3.762V8.162h1.822c1.236 0 1.887.463 1.887 1.348 0 .896-.627 1.377-1.811 1.377z"/>
                            <path d="M0 4a4 4 0 0 1 4-4h8a4 4 0 0 1 4 4v8a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4zm4-3a3 3 0 0 0-3 3v8a3 3 0 0 0 3 3h8a3 3 0 0 0 3-3V4a3 3 0 0 0-3-3z"/>
                          </svg>
                    </p>
                </div>
            </div>
            <!-- <div>
                <hr>
                <a href="nav.html">See my works</a>
            </div> -->
        </aside>
        <main>
            <div id="scrollSpy-development" class="container-fluid portfolio-section">
                <div>
                    <h2>Apps & Websites</h2>
                    <p>Here are some of the projects I've made for school portfolio.</p>
                </div>
                <div class="d-flex justify-content-center row project-thumbnails my-5">
                    <div class="hover hover-projects text-white rounded mx-5 my-2 p-5 col-md-4">
                        <img src="/media/works/django.PNG" alt="Music Catalogue website thumbnail">
                        <div class="hover-overlay"></div>
                        <div class="project-content">
                            <a href ="https://django-portfolio.arseniesarmiento.link" class="project-description text-uppercase font-weight-bold mb-0">Music Catalogue, 2024</a>
                        </div>
                    </div>
                    <div class="hover hover-projects text-white rounded mx-5 my-2 p-5 col-md-4">
                        <img src="/media/works/wordpress.PNG" alt="Wordpress website thumbnail">
                        <div class="hover-overlay"></div>
                        <div class="project-content">
                            <a href ="https://wordpress-portfolio.arseniesarmiento.link" class="project-description text-uppercase font-weight-bold mb-0">WordPress E-Commerce, 2024</a>
                        </div>
                    </div>
                    <div class="hover hover-projects text-white rounded mx-5 my-2 p-5 col-md-4">
                        <img src="/media/works/bootstrap.PNG" alt="Nikau Jansen bootstrap website thumbnail">
                        <div class="hover-overlay"></div>
                        <div class="project-content">
                            <a href ="https://bootstrap-portfolio.arseniesarmiento.link" class="project-description text-uppercase font-weight-bold mb-0">Bootstrap Portfolio, 2024</a>
                        </div>
                    </div>
                    <div class="hover hover-projects text-white rounded mx-5 my-2 p-5 col-md-4">
                        <img src="/media/works/oarbit.PNG" alt="Nikau Jansen bootstrap website thumbnail">
                        <div class="hover-overlay"></div>
                        <div class="project-content">
                            <a href ="https://oarbit.arseniesarmiento.link" class="project-description text-uppercase font-weight-bold mb-0">OarBit Pulse, 2024</a>
                        </div>
                    </div>
                </div>
            </div>
            <div id="scrollSpy-wip" class="container-fluid portfolio-section">
                <h2>Work In Progress</h2>
                <div>
                    <img src="/media/works/upcoming-shiftsync.PNG" alt="Music editor console grayscaled" class="wip-img rounded">
                </div>
                <div class="container-fluid mt-3">
                    <h4>ShiftSync</h4>
                    <p>[  ]</p>
                    <!-- <hr> -->
                    <!-- <p class="m-0">An project of music inspired by Nikau's travels around Aotearoa is coming soon.</p> -->
                </div>
            </div>
            <div id="scrollSpy-arts" class="container-fluid portfolio-section">
                <h2>Artworks</h2>
                <hr>
                <p>During my spare time, I also create digital paintings and stop-animation, accidentally filling almost 6 sketchbooks throughout the years!</p>
                <!-- <div class="container-fluid mt-3 d-flex flex-column col-md-6 align-middle justify-content-center">
                </div> -->
                <div id="demo" class="carousel slide" data-bs-ride="carousel">
                    <!-- Indicators/dots -->
                    <div class="carousel-indicators">
                        <button type="button" data-bs-target="#demo" title="slide-1" data-bs-slide-to="0" class="active"></button>
                        <button type="button" data-bs-target="#demo" title="slide-2" data-bs-slide-to="1"></button>
                        <button type="button" data-bs-target="#demo" title="slide-3" data-bs-slide-to="2"></button>
                        <button type="button" data-bs-target="#demo" title="slide-4" data-bs-slide-to="3"></button>
                        <button type="button" data-bs-target="#demo" title="slide-4" data-bs-slide-to="4"></button>
                        <button type="button" data-bs-target="#demo" title="slide-5" data-bs-slide-to="5"></button>
                    </div>
                    
                    <!-- The slideshow/carousel -->
                    <div class="carousel-inner">
                        <div class="carousel-item c-item active">
                            <img src="/media/arts/lovers.PNG" alt="Neon-lit stage with two guitarists" class="d-block w-100 caro-img-arts rounded">
                            <div class="carousel-caption">
                                <h5>The Lovers</h5>
                                <p>2022</p>
                            </div>
                        </div>
                        <div class="carousel-item c-item">
                            <img src="/media/arts/midnight.png" alt="An onstage guitarist in white tank top" class="d-block w-100 caro-img-arts rounded">
                            <div class="carousel-caption">
                                <h5>Midnight</h5>
                                <p>2014</p>
                            </div> 
                        </div>
                        <div class="carousel-item c-item">
                            <img src="/media/arts/Tarot.PNG" alt="Fireworks display on concert night" class="d-block w-100 caro-img-arts rounded">
                            <div class="carousel-caption">
                                <h5>Tarot</h5>
                                <p>2024</p>
                            </div>
                        </div>
                        <div class="carousel-item c-item">
                            <img src="/media/arts/inktober22.png" alt="Fireworks display on concert night" class="d-block w-100 caro-img-arts rounded">
                            <div class="carousel-caption">
                                <h5>King of Crows</h5>
                                <p>Inktober 2021</p>
                            </div>
                        </div>
                        <div class="carousel-item c-item">
                            <img src="/media/arts/knaves.PNG" alt="Fireworks display on concert night" class="d-block w-100 caro-img-arts rounded">
                            <div class="carousel-caption">
                                <h5>Red Knaves</h5>
                                <p>2021</p>
                            </div>
                        </div>                    
                        <div class="carousel-item c-item">
                            <img src="media/arts/encanto.PNG" alt="Fireworks display on concert night" class="d-block w-100 caro-img-arts rounded">
                            <div class="carousel-caption">
                                <h5>Hiwaga</h5>
                                <p>2019</p>
                            </div>
                        </div>
                    </div>
                    
                    <!-- Left and right controls/icons -->
                    <button class="carousel-control-prev" type="button" data-bs-target="#demo" title="previous-button" data-bs-slide="prev">
                        <span class="carousel-control-prev-icon"></span>
                    </button>
                    <button class="carousel-control-next" type="button" data-bs-target="#demo" title="next-button" data-bs-slide="next">
                        <span class="carousel-control-next-icon"></span>
                    </button>
                </div>
            </div>
        </main>
        <footer class="mt-5 p-4">
            <div class="d-flex justify-content-between">
                <h5>Contact Me </h5>
                <div class="d-flex">
                    <div>
                        <a href="https://www.linkedin.com/in/arsenie-sarmiento" rel="noreferrer noopener" target="_blank">
                            <i class="fa fa-linkedin soc-med-icons"></i>
                            <!-- <img src="https://cdn1.umg3.net/161-cdn/assets/images/icons/apple.svg" alt="LinkedIn logo"> -->
                        </a>
                    </div>
                    <div>
                        <a href="mailto:arsenie.sarmiento@outlook.com" rel="noreferrer noopener" target="_blank">
                            <i class="fa fa-envelope soc-med-icons"></i>
                            <!-- <img src="https://cdn1.umg3.net/161-cdn/assets/images/icons/facebook.svg" alt="Outlook logo"> -->
                        </a>
                    </div>
                    <div>
                        <a href="https://github.com/arsenie-sarmiento" rel="noreferrer noopener" target="_blank">
                            <i class="fa fa-github soc-med-icons"></i>
                        </a>
                    </div>
                </div>
            </div>
            <hr>
            <p>&copy;Arsenie Sarmiento, 2024</p>
        </footer>
    </div>
</body>
</html>
