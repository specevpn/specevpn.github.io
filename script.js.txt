 General Styles 
body {
    font-family Arial, sans-serif;
    margin 0;
    padding 0;
    box-sizing border-box;
}

.container {
    width 80%;
    margin 0 auto;
}

a {
    text-decoration none;
}

h1, h2, h3, h4, p {
    margin 0;
    padding 0;
}

 Header 
header {
    background-color #0a74da;
    padding 20px 0;
    color white;
}

header .logo h1 {
    display inline-block;
    margin 0;
}

header nav ul {
    list-style none;
    display inline-block;
    float right;
}

header nav ul li {
    display inline-block;
    margin-left 20px;
}

header nav ul li a {
    color white;
    font-weight bold;
}

 Hero Section 
.hero {
    background-image url('httpsexample.comhero-image.jpg');  Replace with your image 
    background-size cover;
    background-position center;
    color white;
    text-align center;
    padding 100px 0;
}

.hero h2 {
    font-size 48px;
    margin-bottom 20px;
}

.hero p {
    font-size 24px;
    margin-bottom 30px;
}

.cta-button {
    background-color #0a74da;
    color white;
    padding 15px 30px;
    border-radius 5px;
    font-size 18px;
}

 Features Section 
.features {
    padding 60px 0;
    background-color #f5f5f5;
    text-align center;
}

.feature-grid {
    display flex;
    justify-content space-between;
    margin-top 40px;
}

.feature-item {
    width 30%;
}

 Pricing Section 
.pricing {
    padding 60px 0;
    text-align center;
}

.pricing-grid {
    display flex;
    justify-content space-between;
    margin-top 40px;
}

.pricing-item {
    width 30%;
    padding 20px;
    border 1px solid #ddd;
    border-radius 10px;
}

 Footer 
footer {
    background-color #0a74da;
    color white;
    text-align center;
    padding 20px 0;
    margin-top 40px;
}
