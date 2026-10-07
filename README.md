# labtask
form fill up


<!DOCTYPE html>
<html lang="en">
<head>
    <title>Student Rgistration From.html file</title>
</head>

<body>
        <h1>Student Registration Form</h1>
        <form>
            <label for="fullname">Full Name:</label>
        <input type="text" id="fullname" name="fullname"
               placeholder="Enter your full name" required><br><br>

            <label for="email">Email:</label>
        <input type="email" id="email" name="email"
               placeholder="Enter your email" required><br><br>

<label for="password">Password:</label>
     <input type="password" id="password" name="password" required><br><br>

    <label for="age">Age:</label>
<input type="number" id="age" name="age"><br><br>

            <label>Date of Birth:</label>
        <input type="date" name="dob"><br><br>

        <label>Gender:</label>
        <input type="radio" id="male" name="gender" value="Male">
        <label for="male">Male</label>

        <input type="radio" id="female" name="gender" value="Female">
        <label for="female">Female</label>

        <input type="radio" id="other" name="gender" value="Other">
            
        <label for="other">Other</label>
<br><br>
<label for="city">City:</label>
        <select id="city" name="city">
            <option value="Dhaka">Dhaka</option>
            <option value="Khulna">Khulna</option>
            <option value="Rajshahi">Rajshahi</option>
            <option value="Sylhet">Sylhet</option>
        </select>
        <br><br>
        <label>About Yourself:</label><br>
 <textarea name="about" rows="4" cols="40"></textarea>
 <br><br>
<input type="submit" value="Register">
 <input type="reset" value="clear">

        </form>

</body>
</html>