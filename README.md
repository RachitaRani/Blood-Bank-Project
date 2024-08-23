
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Blood Bank Application</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        .container {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background-color: #fff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
        }
        h1 {
            text-align: center;
            color: #333;
        }
        h2 {
            color: #333;
        }
        p {
            line-height: 1.6;
            color: #555;
        }
    </style>
</head>
    <div class="container">
        <h1>Blood Bank Application</h1>
        
        <h2>Registration Page</h2>
        <p>
            Different registration pages for hospitals and receivers. Capture receiver's blood group during registration.
        </p>
        
        <h2>Login Page</h2>
        <p>
            Single/Different login pages for hospitals and receivers.
        </p>
        
        <h2>Hospital 'Add Blood Info' Page</h2>
        <p>
            A hospital, once logged in, should be able to add details of available blood samples (along with type) to their bank. Access to this page should be restricted only to hospitals.
        </p>
        
        <h2>'Available Blood Sample' Page</h2>
        <p>
            There should be a page that displays all the available blood samples along with which hospitals have them and a 'Request Sample' button. This page should be accessible to everyone, irrespective of whether the user is logged in or not.
        </p>
        
        <h2>Expected Functionality</h2>
        <p>
            On click of the 'Request Sample' button:
            Only receivers should be able to request for blood samples by clicking the 'Request Sample' button. Make sure that only those receivers who are eligible for the blood sample are allowed to click the button. If the user is not logged in, then he/she should be redirected to the login page. If the user is logged in as a hospital, then the user should not be allowed to request a Blood Sample.
        </p>
        
        <h2>Hospital 'View Requests' Page</h2>
        <p>
            Hospitals should be able to see the list of all the receivers who have requested a particular blood group from its blood bank.
        </p>
    </div>
