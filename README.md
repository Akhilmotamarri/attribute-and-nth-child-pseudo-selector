# attribute-and-nth-child-pseudo-selector
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>attribute and nth child pseudo selector</title>
    <style>
        .container {
            width: 234px;
            margin: auto;
            display: block;
        }

        input {
            display: block;
        }

        input[type='text'] {
            padding: 23px;
            border: 2px solid red;
        }

        input[type='password'] {
            padding: 23px;
            border: 2px solid rgb(24, 119, 243);
        }

        input[type='submit'] {
            padding: 23px;
            display: block;
            margin: auto;
            border: 2px solid rgb(201, 250, 68);
        }

        a[target] {
            font-size: 34px;
            color: blueviolet;
            display: inline-block;
            margin: auto;
            margin-left: 12px;
        }

        a[target='_blank'] {
            font-size: 34px;
            color: rgb(45, 48, 2);
            display: inline-block;
            margin: auto;
            margin-left: 12px;
        }

        a[target='_self'] {
            font-size: 34px;
            color: rgb(24, 231, 117);
            display: inline-block;
            margin: auto;
            margin-left: 12px;
        }

        li:nth-child(even) {
            color: blueviolet;
        }

        li:nth-child(odd) {
            color: rgb(13, 35, 235);
        }

        li:nth-child(3n+0) {
            color: rgb(43, 153, 226);
        }
    </style>
</head>

<body>
    <div class="container">
        <h1> <a href="https://www.google.com/" target="_blank">Go to google</a> </h1>
        <h1> <a href="https://www.facebook.com/" target="_self">Go to facebook</a> </h1>
        <form action="noac.php">
            <input type="text" placeholder="enter your name">
            <input type="password" placeholder="enter your password">
            <input type="submit" value="submit">
        </form>
        <ul>
            <li id="item-1">item1</li>
            <li id="item-2">item2</li>
            <li id="item-3">item-3</li>
            <li id="item-4">item-4</li>
            <li id="item-5">item-5</li>
            <li id="item-6">item-6</li>
            <li id="item-7">item-7</li>
            <li id="item-8">item-8</li>
            <li id="item-9">item-9</li>
            <li id="item-10">item-10</li>
        </ul>
    </div>

</body>

</html>
