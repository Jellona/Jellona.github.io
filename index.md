<!DOCTYPE html>
<html>
<head>
    <title>Courses</title>
    <meta charset="utf-8" />
    <link href="coursesStyle.css" rel="stylesheet" />
    
</head>
<body>
    <!-- The title on the page of the website -->
    <div id ="page_title">
        <h1>Course management website</h1>
    </div id="page_title">
    
    <!-- The first container -->
    <div id="content_one">
        <!-- Available courses shown to user -->
        <div id="course_container">

        </div id="course_container">

        <!-- Selected courses container -->
        <div id="selected_courses">
            <h2>Selected courses:</h2>
        </div id="selected_courses">
        
    </div id="content_one">
    
    <!-- Adding new courses container -->
    <div id="adding_courses">
        <p>Add new course:</p>
            Course Name:<input type="text" id="inputName" /> <br />
            Credits:<input type="number" id="inputCredits" /> <br />
            Timing:<input type="text" id="inputTiming" /> <br />
            Language:<input type="text" id="inputLanguage" /> <br />
            Type:<input type="text" id="inputType" /> <br />
            <button onclick="addCourseToContainer();">Add course to website</button>
    </div id="adding_courses">
    
    
    <!-- Running JavaScript -->
    <script src="courseJavaScript.js"></script>
</body>

</html>
