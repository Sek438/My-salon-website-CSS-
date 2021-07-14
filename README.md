External Style Sheet

/*----body-----*/
body {font-family: arial, sans-serif; background: #34ebae;}

/*----container----*/
div#wrapper {width: 960px; background: white; margin-left: auto; margin-right: auto;}

/*------header------*/
div#header {
    padding:10px;
    background-image:url(logo.jpg);
    height: 120px;
}

div #header h3 {
    color:green;
    margin-top:75px;
    margin-left: 70px;
}
/*---------------------Navigation bar------------------*/
ul#navlist li{list-style-type: none; display: inline; padding-right: 30px; margin-right:50px;}
ul#navlist {background-color: green; margin-top: -5px; padding: 5px 5px 5px 20px; text-align:center;}
ul#navlist li a {color: white; text-decoration: none; font-size: .85em;}
ul#navlist li a:hover {background: red;}


/*--main content area---*/
div#main {width: 960px;height:auto; margin-top:-10px;}

/*-------footer------*/
div#footer {background-color:green; height: 50px; clear: both; text-align:center; padding-top: 20px;}

/*---------------for the forms---------------*/
label.name {float:left; width:150px; text-align:right; margin-right:10px;}
label.phone {float:left; width:150px; text-align:right; margin-right:10px;}
label.email {float:left; width:150px; text-align:right; margin-right:10px;}
label.address {float:left; width:150px; text-align:right; margin-right:10px;}
label.city {float:left; width:150px; text-align:right; margin-right:10px;}
label.zip {float:left; width:150px; text-align:right; margin-right:10px;}

/*------------------------style rules for service page----------------------------*/
p.errorMsg {display: none;color: red; size;5px;}

/* styel sheet for the table on the home page */

table {
   border-collapse: collapse;
   border-spacing: 0;
}

a:link, a:visited {
   text-decoration: none;
   color: inherit;
}

a:hover {
   text-decoration: none;
   color: inherit;
}

a:active {
   text-decoration: none;
   color: inherit;
}

article h2 {
   font-size: 1.2em;
   font-weight: bold;
   width: 182px;
   text-align: center;
   padding: 10px 5px 0;
}

article p {
   margin-bottom: 6px;
   line-height: 1.2em;
}

article table {
   width: 100%;
   text-align: center;
   table-layout: fixed;
}

article table caption {
   padding: 5px;
   width: 182px;
}

article tr td:first-child, article tr td:last-child {
   background: green;
}

article th, article td {
   border: 1px solid black;
   border-collapse: collapse;
   padding: 5px;
   width: 14.2857%;
}

article tr td:first-of-type, article tr th:first-of-type {
   border-left: 0;
}

article tr td:last-of-type, article tr th:last-of-type {
   border-right: 0;
}

article th {
   font-weight: 700;
   background: yellow;
}

article td p:first-of-type {
   font-weight: 900;
   text-align: right;
}

