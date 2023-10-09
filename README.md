# website

<!DOCTYPE html>
<html lang="en">
<head>
    <title>Student_FORM</title>
</head>
<body>

     <form action="Assigmentmsg.html">

    <fieldset>
        <legend><h1>Student Information Form</h1></legend>
        
        <label for="Name of the Student"><b>Name</b></label>
        <input type="name" required placeholder="your answer" id="name" name="name">
        <br> <br>
        
        <label for="USN"><b>usn</b></label>
        <input type="usn" required placeholder="your answer" id="usn" name="usn">
        <br> <br>

        <label for="Contact"><b>Contact</b></label>
        <input type="text" required placeholder="your answer" id="contact" pattern="[6-9][0-9]{9}">
        <br> <br>

        <label for="Department"><b>Department</b></label>
        <input type="Department" required placeholder="your answer" id="dpt" name="dpt">
        <br> <br>

        <label for="Semester"><b>Semester</b></label>
        <input type="sem" required placeholder="your answer" id="sem" name="sem" pattern="[1-8]">
        <br> <br>
    </fieldset>
    <input type="Submit">
    </form>
</body>
</html>
