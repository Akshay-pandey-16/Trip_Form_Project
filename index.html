<?php
$insert = false;
if (isset($_POST['name'])) {

    $server = "localhost";
    $username = "root";
    $password = "";

    // Create a database connection
    $con = mysqli_connect($server, $username, $password);

    // Check for connection success
    if (!$con) {
        die("Connection to this database failed due to " . mysqli_connect_error());
    }

    // Collect post variables
    $name = $_POST['name'];
    $gender = $_POST['gender'];
    $age = $_POST['age'];
    $m_number = $_POST['m_number'];
    $email = $_POST['email'];
    $desc = $_POST['desc'];

    $sql = "INSERT INTO `trip`.`trip` (`name`, `age`, `m_number`, `email`, `gender`, `other`, `dt`) 
            VALUES ('$name', '$age', '$m_number', '$email', '$gender', '$desc', current_timestamp());";

    // Execute the query
    if ($con->query($sql) == true) {
        $insert = true;
    } else {
        echo "ERROR: $sql <br> $con->error";
    }

    // Close the database connection
    $con->close();
}
?>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Travel Form</title>
    <link rel="stylesheet" href="styke.css">
</head>
<body>
    <img class="bgimage" src="images/IES_College_of_Technology,_Bhopal_Main_Building.jpg" alt="IES College of Technology">
    <div class="container">
        <h3>Welcome to IES College of Technology Travel Form</h3>
        <p>Enter your details and submit this form to confirm your participation in the trip</p>
        <?php
        if ($insert == true) {
            echo "<p class='submitmsg'>Thanks for submitting your form. We are happy to see you joining the trip.</p>";
        }
        ?>
        <form action="index.php" method="post">
            <input type="text" name="name" id="name" placeholder="Enter your name:">
            <input type="text" name="age" id="age" placeholder="Enter your age:">
            <input type="number" name="m_number" id="m_number" placeholder="Enter your mobile number">
            <input type="email" name="email" id="email" placeholder="Enter your Email:">
            <input type="text" name="gender" id="gender" placeholder="Enter your gender:">
            <textarea name="desc" id="desc" cols="30" rows="10" placeholder="Enter any other information here:"></textarea>
            <button class="btn">Submit</button>
            <!-- <button class="btn">Reset</button> -->
        </form>
    </div>
    <script src="index.js"></script>
</body>
</html>
