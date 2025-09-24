<!DOCTYPE html>
<html lang="en">
<hea
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width,initial-scale=1.0">
    <title>Breakpoints</title>
    <style>
        body {
            font-family: 'Courier New', Courier, monospace;
            text-align: center;
            padding:50px;
            transition: all 0.5s ease;
        }
        h1 {
            font-size: 20px;
                font-size: 22px;
                p {
                    font-size: 10px;
                }
            }
        @media (max-width: 767px) {
            body {
                background-color:yellow;
            }
            h1 {
                font-size: 22px;
                p {
                    font-size: 10px;
                }
            }
        }
        @media (max-width: 599px) {
            body {
                background-color:orange;
            }
            h1 {
                font-size: 22px;
                p {
                    font-size: 10px;
                }
            }
        }
    </style>
</head>
<body>
    <h1>Responsive Breakpoints</h1>
    <p>Resize the window for opening in mobile/tablet/desktop.</p>
</body>
</html>
