# Assessment-1-Chapter-3

[HTML]
<html>
<head>
    <link type="text/css" rel="stylesheet" href="StyleSheet2.css"/>
    <img src="C:\Users\User\Pictures\339439_467422869936848_2076932625_o.jpg" style="width:250px;height:250px;border:0;" />
    <title></title>
</head>
<body>
    <div id="header">
        <p id="name">Joshua Marayag Macaballug</p>
    </div>
    <div class="left">
    </div>
    <div class="right">
        <h3>Curriculum Vitae</h3>
        <p>
            <ul>
                <li>Currently studying at BathSpa University.</li>
                <li>Learnt basic Photography, Film-making, and Editing.</li>
                <li>A hard-working, freelance student with a passion in making films.</li>
                <li>Average communication Skills and a good team worker.</li>
            </ul>
        </p>
        <h3>Professional Experience</h3>
        <p id="job-title"><strong>Freelance Film-maker</strong></p>
        <p id="job-responsibilities">Work commitments:</p>
        <p>
            <ul>
                <li>Listen to client's concept.</li>
                <li>Interact with client a lot to gain trust.</li>
                <li>Open for suggestions or ideas of clients.</li>
                <li>Interact with people to reduce discomfort of others.</li>
            </ul>
        </p>
        <h3 id="heading">Education</h3>
        <table>
            <tr>
                <td>Place of Education</td>
                <td>Degree</td>
                <td>Year</td>
            </tr>
            <tr>
                <td>21st Century Private Academy</td>
                <td>Elementary School Diploma</td>
                <td>2012-2015</td>
            </tr>
            <tr>
                <td>Philippine Emirates Private School/Homeschool Global Middle East</td>
                <td>High School Degree</td>
                <td>2015-2020</td>
            </tr>
        </table>
        <h3>Personal Information:</h3>
        <p>
            <ul>
                <li>
                    I am an average Film-maker and Photographer.
                <li>
                    <span id="course-name">Languages studied:</span>English, Filipino, Korea, Urdu.
                </li>
                <li>
                    <span id="course-name">Hobbies:</span>I love editing some of my random stock videos when I have free time and I also play video games to release my stress.
                </li>
            </ul>
        </p>
    </div>
</body>
</html>

[StyleSheet] 
div {
    border-radius: 5px;
}

#header {
    position: fixed;
    z-index: 1;
    height: 40px;
    width: 98%;
    background-color: #668284;
    margin-bottom: 10px
}

#name {
    float: left;
    margin-left: 20px;
    padding-bottom: 10px;
    font-size: 16px;
    font-family: Verdana, sans-serif;
    color: #ffffff;
}

.right {
    float: left;
    margin-top: 50px;
    padding-left: 5px;
    height: auto;
    width: 99%;
    background-color: #E3EDD8;
}

h3 {
    text-decoration: underline;
}

#job-responsibilities {
    padding: 1px;
}

.job-title {
    font-weight: bold;
}

table {
    border: 10px dashed black;
}

td {
    padding: 2px;
    border: 1px solid #E88741;
}

#job-title {
    height: 5px;
}

.job-duration {
    float: right;
}

#heading {
    font-weight: bold;
}

td, th {
    border: 1px solid black;
    text-align: left;
    padding: 8px;
}
