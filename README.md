<!DOCTYPE html>
<html>
    <head>
        <title>Personal Details</title>
    </head>
    <body>
        <label for="country">Salutation</label><br>
        <select>
            <option value="Alien">Non </option>
            <option value="NGR">Nigeria</option>
            <option value="GHN">Ghanian</option>
        </select><br>
        <br><label for="firstname">First name:</label>
        <input type="text" id="firstname" name="firstname"><br>
        <br>
        <label for="lastname">Last name: </label>
        <input type="text" id="lastname" name="lastname"><br>
        <br>
        <form>
            <label for="gender">Gender: </label>
            <input type="radio" id="male" name="gender" value="male">
            <label for="male">Male </label>
            <input type="radio" id="female" name="gender" value="female"
            <label for="female">Female </label><br>
            <br>
            <label for="email">Email: </label>
            <input type="text" id="email" name="email"><br>
            <br>
            <label for="dateofbirth">Date of Birth: </label>
            <input type="date" id="dateofbirth" name="dateofbirth"><br>
            <br>
            <label for="freeform">Address: </label><br>
            <textarea id="freeform" name="freeform" rows="5" cols="40">enter your adress in less than 50 word-----</textarea><br>
            <br>
            <button type="submit">Submit</button>
            
        </form>
    </body>
</html>
