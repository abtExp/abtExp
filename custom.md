<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1" />
<meta charset="utf-8" />
<meta name="description" content="Anubhav Tiwari - Deep Learning Engineer . Aspiring Machine Learning Researcher">
<meta name="author" content="Anubhav Tiwari">
<title>
    Anubhav Tiwari
</title>
<link rel="stylesheet" href="./style.css" />
</head>
<body>
    <div id='banner'>
        <div id='top' class='sub_banner'>
            <h1 class='content' id='heading'>Anubhav Tiwari</h1>
            <div class='content' id='image'>
                <img src='./imgs/me.png' id='face' alt='my face' />
            </div>
            <h3 class='content' id='tagline'>Deep Learning Engineer . Aspiring Machine Learning Researcher</h1>
        </div>
        <div id='bottom' class='sub_banner'>
            <div id='sections' class='content'>
                <div class='clickable_neon_glow_card'>
                    <a href='https://drive.google.com/file/d/173OO2khxFVscL3880Rlipg8icywhW1nk/view?usp=sharing' target='_blank'>
                        <div class='section' id='resume'>
                            <div class='sub_section'>
                                <div class='section_elem'>
                                    Resume
                                </div>
                                <div class='section_elem'>
                                    <img src='./imgs/resume.png' alt='resume' class='section_img' />
                                </div>
                            </div>
                        </div>
                    </a>
                </div>
                <div class='clickable_neon_glow_card'>
                    <a href='https://github.com/abtExp' target='_blank'>
                        <div class='section' id='projects'>
                            <div class='sub_section'>
                                <div class='section_elem'>
                                    Projects
                                </div>
                                <div class='section_elem'>
                                    <img src='./imgs/projects.png' alt='projects' class='section_img' />
                                </div>
                            </div>
                        </div>
                    </a>
                </div>
                <div class='clickable_neon_glow_card'>
                    <a href='https://medium.com/expnotes' target='_blank'>
                        <div class='section' id='blogs'>
                            <div class='sub_section'>
                                <div class='section_elem'>
                                    Blogs
                                </div>
                                <div class='section_elem'>
                                    <img src='./imgs/blogs.png' alt='blogs' class='section_img' />
                                </div>
                            </div>
                        </div>
                    </a>
                </div>
                <div class='clickable_neon_glow_card'>
                    <a href='https://arxiv.org' target='_blank'>
                        <div class='section' id='research'>
                            <div class='sub_section'>
                                <div class='section_elem'>
                                    Research
                                </div>
                                <div class='section_elem'>
                                    <img src='./imgs/research.png' alt='research' class='section_img' />
                                </div>
                            </div>
                        </div>
                    </a>
                </div>
                <div class='clickable_neon_glow_card'>
                    <a href='https://linkedin.com/in/abtExp' target='_blank'>
                        <div class='section' id='contact'>
                            <div class='sub_section'>
                                <div class='section_elem'>
                                    Contact
                                </div>
                                <div class='section_elem'>
                                    <img src='./imgs/contact.png' alt='contact' class='section_img' />
                                </div>
                            </div>
                        </div>
                    </a>
                </div>
            </div>
        </div>
    </div>
    <style>
        * {
            box-sizing: border-box;
        }

        body {
            background: url('imgs/bg.jpg');
            background-size: cover;
            background-repeat: no-repeat;
            backdrop-filter: blur(2px);
            width: 100%;
            height: 100%;
            padding: 0px;
            margin: 0px;
            text-shadow: 0px 0px 5px #333;
            font-family: sans-serif;
        }

        #banner {
            margin: auto;
            text-align: center;
            display: flex;
            justify-content: center;
            flex-direction: column;
            border-radius: 0px 0px 10px 10px;
            background-color: rgba(0, 0, 0, 0.2);
            width: 60%;
            box-shadow: 0px 0px 400px 0px rgba(255, 255, 255, 0.479);
        }

        .sub_banner {
            flex: 1;
            display: flex;
            justify-content: center;
            flex-direction: column;
            padding: 25px;
        }

        .content {
            width: 100%;
            padding: 15px;
            margin: auto;
            flex: 1;
        }

        #image {
            width: 200px;
            height: 200px;
            border-radius: 200px;
            box-shadow: 0px 0px 5px 0px rgb(0, 0, 0);
            padding: 5px;
            background-color: #fff;
        }

        #image:hover {
            box-shadow: 0px 0px 40px 0px rgb(135, 250, 221);
        }

        #face {
            width: 200px;
            height: 200px;
            border-radius: 200px;
        }

        #sections {
            display: flex;
            flex-direction: row;
            justify-content: center;
        }

        .section {
            flex: 1;
            font-weight: bold;
            box-shadow: 0px 0px 5px 0px rgb(27, 24, 24);
            margin: 5px;
            padding: 15px;
            border-radius: 10px;
            width: 100%;
            background-color: rgba(0, 0, 0, 0.5);
        }

        .section_img {
            width: 50px;
            height: 50px;
            padding: 5px;
        }

        .sub_section {
            display: flex;
            flex-direction: column;
        }

        .section_elem {
            flex: 1;
        }

        a {
            text-decoration: none;
            color: #fff !important;
        }

        .clickable_neon_glow_card {
            width: 20%;
            margin: 5px;
        }

        .clickable_neon_glow_card a:hover {
            color: #fff !important;
            text-shadow: 0px 0px 20px #fff !important;
        }

        #resume:hover {
            background-color: rgb(255, 94, 115);
            box-shadow: 0px 0px 100px 0px rgb(241, 141, 154);
        }

        #projects:hover {
            background-color: rgb(94, 255, 161);
            box-shadow: 0px 0px 100px 0px rgb(141, 241, 154);
        }

        #blogs:hover {
            background-color: rgb(94, 137, 255);
            box-shadow: 0px 0px 100px 0px rgb(141, 154, 241);
        }

        #research:hover {
            background-color: rgb(250, 232, 70);
            box-shadow: 0px 0px 100px 0px rgb(241, 239, 141);
        }

        #contact:hover {
            background-color: rgb(255, 158, 94);
            box-shadow: 0px 0px 100px 0px rgb(241, 181, 141);
        }

        #heading {
            color: #fff;
            text-shadow: 0px 0px 5px #fff !important;
        }

        #tagline {
            color: #fff;
            margin: 15px;
            text-shadow: 0px 0px 5px #fff !important;
        }

        #content {
            display: flex;
            flex-direction: column;
        }

        @media (max-width:700px) {
            body {
                background-repeat: repeat;
            }
            #banner {
                width: 100%;
            }
            #sections {
                flex-direction: column;
            }
            .clickable_neon_glow_card {
                width: 60%;
                margin: 10px auto;
            }
        }
    </style>
</body>
</html>
