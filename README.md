<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Student Registration Form</title>

<style>
    body{
        margin:0;
        padding:0;
        background:#f8dddd;
        font-family: Georgia, serif;
    }

    .container{
        width: 900px;
        margin: 20px auto;
        padding: 20px 40px;
    }

    h1{
        text-align:center;
        font-size:55px;
        margin-bottom:40px;
        font-weight:bold;
    }

    table{
        width:100%;
    }

    td{
        padding:12px 10px;
        vertical-align:middle;
        font-size:22px;
    }

    label{
        font-size:22px;
    }

    input[type="text"],
    input[type="email"],
    input[type="password"],
    textarea,
    select{
        border:1px solid #bdbdbd;
        padding:8px;
        font-size:18px;
        background:white;
    }

    .long{
        width:550px;
    }

    .small{
        width:90px;
    }

    .name{
        width:250px;
    }

    .mobile-code{
        width:60px;
    }

    textarea{
        width:540px;
        height:120px;
        resize:none;
    }

    .radio-group,
    .check-group{
        font-size:22px;
    }

    .submit-btn{
        text-align:center;
        margin-top:20px;
    }

    button{
        padding:6px 20px;
        font-size:20px;
        cursor:pointer;
    }
</style>
</head>

<body>

<div class="container">

    <h1>Student Registration Form</h1>

    <form>

        <table>

            <tr>
                <td><label>Roll no. :</label></td>
                <td><input type="text" class="long"></td>
            </tr>

            <tr>
                <td><label>Student name :</label></td>
                <td>
                    <input type="text" class="name" placeholder="First Name">
                    -
                    <input type="text" class="name" placeholder="Last Name">
                </td>
            </tr>

            <tr>
                <td><label>Father's name :</label></td>
                <td><input type="text" class="long"></td>
            </tr>

            <tr>
                <td><label>Date of birth :</label></td>
                <td>
                    <input type="text" class="small" placeholder="Day">
                    -
                    <input type="text" class="small" placeholder="Month">
                    -
                    <input type="text" class="small" placeholder="Year">
                    <b>(DD-MM-YYYY)</b>
                </td>
            </tr>

            <tr>
                <td><label>Mobile no. :</label></td>
                <td>
                    <input type="text" class="mobile-code" value="+91">
                    -
                    <input type="text" style="width:460px;">
                </td>
            </tr>

            <tr>
                <td><label>Email id :</label></td>
                <td><input type="email" class="long"></td>
            </tr>

            <tr>
                <td><label>Password :</label></td>
                <td><input type="password" class="long"></td>
            </tr>

            <tr>
                <td><label>Gender :</label></td>
                <td class="radio-group">
                    <input type="radio" name="gender"> Male
                    <input type="radio" name="gender"> Female
                </td>
            </tr>

            <tr>
                <td><label>Department :</label></td>
                <td class="check-group">
                    <input type="checkbox"> CSE
                    <input type="checkbox"> IT
                    <input type="checkbox"> ECE
                    <input type="checkbox"> Civil
                    <input type="checkbox"> Mech
                </td>
            </tr>

            <tr>
                <td><label>Course :</label></td>
                <td>
                    <select class="long">
                        <option>---------------- Select Current Course's ----------------</option>
                        <option>B.Sc</option>
                        <option>BBA</option>
                        <option>BCA</option>
                        <option>B.Tech</option>
                    </select>
                </td>
            </tr>

            <tr>
                <td><label>Student photo :</label></td>
                <td>
                    <input type="file">
                </td>
            </tr>

            <tr>
                <td><label>City :</label></td>
                <td><input type="text" class="long"></td>
            </tr>

            <tr>
                <td><label>Address :</label></td>
                <td>
                    <textarea></textarea>
                </td>
            </tr>

        </table>

        <div class="submit-btn">
            <button type="submit">Register</button>
        </div>

    </form>

</div>

</body>
</html>
