<html lang="en">

    <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1">

        <title>POP UP BOX</title>
        <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js"
            integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo"
            crossorigin="anonymous"></script>

        <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.0.0/dist/css/bootstrap.min.css"
            integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
        <link rel="stylesheet" href="style.css">
        <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.7.2/font/bootstrap-icons.css">

    </head>

    <body>
        <div class="text-center mt-5">
            <button class="clicks">
                Click Me
            </button>
        </div>
        <div id="box" class="container mt-5">
            <div class="one">
                <h3 class="pt-3 text-center">
                    Enter Details
                    <button type="button" class="btn btn-link "><span class="bi bi-x  submission" style="color:red; font-size:x-large; position:relative;
                        left:230px; top:-2px;"></span></button>
                </h3>
                <form action="#">
                    <div class="form-group">
                        <label for="username">
                            Username
                        </label>
                        <input type="text" name="" class="form-control">

                    </div>
                    <div class="form-group">
                        <label for="email">
                            Email
                        </label>
                        <input type="email" name="" class="form-control">

                    </div>
                    <input type="button" value="Submit" class="btn btn-primary submission">

                </form>
            </div>
        </div>
        <script src="https://code.jquery.com/jquery-3.6.0.js"
            integrity="sha256-H+K7U5CnXl1h5ywQfKtSj8PCmoN9aaq30gDh27Xc0jk=" crossorigin="anonymous"></script>

        <script src="script.js"></script>
    </body>

</html>
