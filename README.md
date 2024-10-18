<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Application Form</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            padding: 20px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        h2 {
            color: #333;
        }
        label {
            display: block;
            margin: 10px 0 5px;
        }
        input, textarea {
            width: 100%;
            padding: 8px;
            margin-bottom: 10px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        .checkbox-group {
            margin-bottom: 10px;
        }
    </style>
</head>
<body>

    <h2>Personal Information Form</h2>
   
    <form>

        <!-- Personal Details -->
        <fieldset>
            <legend>Personal Details</legend>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>

            <label for="name">Address:</label>
            <input type="text" id="address" name="address" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="phone">Phone Number:</label>
            <input type="tel" id="phone" name="phone" required>

            <label for="phone">gender:</label>
            <label><input type="checkbox" name="interest" value="Reading">MALE</label>
            <label><input type="checkbox" name="interest" value="Reading">FEMALE</label>
            <label><input type="checkbox" name="interest" value="Reading">OTHERS</label>
        </fieldset>

        <!-- Checklist -->
        <fieldset>
            <legend>Check All That Apply</legend>
            <div class="checkbox-group">
                <label><input type="checkbox" name="interest" value="Reading"> i have tattoo and piercings</label>
                <label><input type="checkbox" name="interest" value="Traveling"> I am more than 2 years older than my daughter</label>
                <label><input type="checkbox" name="interest" value="Sports"> I own a panel van or V8 ute</label>
                <label><input type="checkbox" name="interest" value="Music"> i work full time</label>
                <label><input type="checkbox" name="interest" value="Art"> My parents are rich</label>
                <label><input type="checkbox" name="interest" value="Art"> is the date at a well lit public location</label>
            </div>
        </fieldset>

        <!-- Essay Section -->
        <fieldset>
            <legend>Essay Section</legend>
            <label for="essay">In 50 words or more explain ehy you want to date my daughter:</label>
            <textarea id="essay" name="essay" rows="10" required></textarea>
        </fieldset>


        <!-- Reference Section -->
        <fieldset>
            <legend>Reference</legend>
            <label for="reference">Plese upload contact detail for 2 reference:</label>
            <input type="text" id="reference" name="reference" required>
        </fieldset>

        <input type="submit" value="Submit">

    </form>

</body>
</html>
