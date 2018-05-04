# CSS3-blog

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

.clearfix:after {
    content: "";
    display: table;
    clear: both;
}

body {
    font-family: Calibri;
    font-size: 15px;
}

h1, h2 {
color: #178b7e;
}

h1 {
    font-size: 35;
    margin-bottom: 25;
}

h2 {
    font-size: 25;
}

.main-text {
    text-align: justify;
    margin-bottom: 20;
}

.author-text {
    font-size: 25;
    float: left;
    margin-top: 30px;
    margin-left: 10px;
}


.container {
    width: 1140px;
    margin: 20px auto 0 auto;
}

.blog-post {
    width: 75%;
    float: left;
    padding-right: 30px;
    position: relative;
}

.other-post {
    width: 25%;
    float: left;
}

.author-box {
    padding-top: 10px;
    border-top: 2px solid rgb(86, 90, 85);
}

.other {
    margin-bottom: 40px;
}

.author-box img {
    height: 100px;
    width: 100px;
    border-radius: 50%;
    float: left;
}

.blog-post img {
    height: 150px;
    width: auto;
}

.date {
    position: absolute;
    top: 0;
    right: 30px;
}
