<!DOCTYPE html>
<html lang="en">
<style>
    body {
        font-family: Arial, sans-serif;
        /* display: flex; */
        width: 1349px;
        justify-content: center;
        align-items: center;
        height: 100vh;
        margin: 0;
        background-color: #f5f5f5;
        padding: 80px;
    }

    .main-testi {
        width: 48%;
        float: left;
    }

    .main-testi3 {
        width: 100%;
        float: left;
    }

    .testimonial {
        background-color: #000;
        color: #fff;
        padding: 20px;
        border-radius: 25px;
        /* width: 48%; */
        text-align: left;
        position: relative;
        margin-right: 20px;
    }

    .testimonial::after {
        content: '';
        position: absolute;
        bottom: -20px;
        left: 10%;
        transform: translateX(-50%);
        border-width: 10px;
        border-style: solid;
        border-color: #000 transparent transparent transparent;
    }

    .testimonial1 {
        padding: 20px;
        border-radius: 25px;
        width: 48%;
        text-align: left;
        position: relative;
        margin-left: 20px;
        border: 1px solid;
        float: left;
    }

    .testimonial4 {
        padding: 40px 60px;
        border-radius: 25px;
        width: 100%;
        text-align: center;
        position: relative;
        margin-left: 20px;
        border: 1px solid;
        float: left;
        font-size: 18px;
        margin-bottom: 40px;
    }


    .profile {
        display: flex;
        align-items: center;
        margin-top: 20px;
        margin-left: 10px;
    }

    .profile img {
        border-radius: 50%;
        width: 50px;
        height: 50px;
        margin-right: 10px;
    }

    .profile-info {
        text-align: left;
    }

    .profile-info h4 {
        margin: 0;
        font-size: 16px;
        color: #000;
    }

    .profile-info p {
        margin: 0;
        font-size: 14px;
        color: #666;
    }

    .main-testi3 {
        width: 100%;
        float: left;
        margin: 50px 0px;
    }

    .profile3 {
        width: 31%;
        float: left;
    }

    .testimonial3 {
        width: 69%;
        float: left;
        background: #000;
        color: white;
        padding: 45px 40px;
        border-radius: 25px;
    }

    .profile-info3 h4 {
        margin: 0;
        font-size: 33px;
        color: #fff;
    }

    .profile-info3 p {
        font-size: 14px;
        color: #666;
        margin: 10px 0;
    }

    .profile3 img {
        vertical-align: middle;
        border-radius: 24px;
        width: 341px;
        height: 317px;
    }

    .profile4 {

        align-items: center;
        margin-top: 50px;
        margin-left: 18px;
    }

    .profile4 img {
        border-radius: 50%;

        margin: 1px 0 15px 15px;
    }

    .profile-info4 {
        text-align: center;
    }

    .checked {
        color: orange;
    }

    span.fa.fa-star.checked {
        font-size: 34px;
        margin-bottom: 18px;
    }
</style>

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Temstimonial Cards</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <!-- Latest compiled and minified CSS -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
    <!-- jQuery library -->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.7.1/jquery.min.js"></script>
    <!-- Latest compiled JavaScript -->
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>
</head>

<body>
    <div class="main-testi">
        <div class="testimonial">
            <p>
                I have been solving all the project ideas on roadmap.sh and I am surprised how far I have come from
                where I
                started.
            </p>
            <p>
                Highly recommended!
            </p>

        </div>
        <div class="profile">
            <img alt="Profile picture of Artem Jones" height="50"
                src="https://storage.googleapis.com/a1aa/image/dejGwbJKqP2DOiHnWZPtQ0zkOESO4fBLzHeulTsqoPBc7E4nA.jpg"
                width="50" />
            <div class="profile-info">
                <h4>
                    Artem Jones
                </h4>
                <p>
                    Junior Frontend Developer
                </p>
            </div>
        </div>
    </div>
    <div class="testimonial1">
        <p>
            I have been solving all the project ideas on roadmap.sh and I am surprised how far I have come from
            where I
            started.
        </p>
        <p>
            Highly recommended!
        </p>
        <div class="profile">
            <img alt="Profile picture of Artem Jones" height="50"
                src="https://storage.googleapis.com/a1aa/image/dejGwbJKqP2DOiHnWZPtQ0zkOESO4fBLzHeulTsqoPBc7E4nA.jpg"
                width="50" />

            <div class="profile-info">
                <h4>
                    Artem Jones
                </h4>
                <p>
                    Junior Frontend Developer
                </p>
            </div>
        </div>
    </div>
    <div class="main-testi3">

        <div class="profile3">
            <img alt="Profile picture of Artem Jones" height="250"
                src="https://storage.googleapis.com/a1aa/image/dejGwbJKqP2DOiHnWZPtQ0zkOESO4fBLzHeulTsqoPBc7E4nA.jpg"
                width="250" />
        </div>
        <div class="testimonial3">
            <div class="star">
                <span class="fa fa-star checked"></span>
                <span class="fa fa-star checked"></span>
                <span class="fa fa-star checked"></span>
                <span class="fa fa-star checked"></span>
                <span class="fa fa-star checked"></span>
            </div>
            <div class="profile-info3">
                <h4>
                    Smith Jones
                </h4>
                <p>
                    Engineerer Manager
                </p>
            </div>
            <p style="font-size: 19px;">
                I have been solving all the project ideas on roadmap.sh and I am surprised how far I have come from
                where I
                started.
            </p>
            <p style="font-size: 19px;">
                Highly recommended!
            </p>

        </div>
    </div>
    <div class="testimonial4">
        <p>
            I have been solving all the project ideas on roadmap.sh and I am surprised how far I have come from
            where I started.I have been solving all the project ideas on roadmap.sh and I am surprised how far I have
            come from
            where I started.
        </p>
        <p>
            Highly recommended!
        </p>
        <div class="profile4">
            <img alt="Profile picture of Artem Jones" height="40"
                src="https://storage.googleapis.com/a1aa/image/dejGwbJKqP2DOiHnWZPtQ0zkOESO4fBLzHeulTsqoPBc7E4nA.jpg"
                width="40" style="opacity: 35%;" />
            <img alt="Profile picture of Artem Jones" height="60"
                src="https://storage.googleapis.com/a1aa/image/dejGwbJKqP2DOiHnWZPtQ0zkOESO4fBLzHeulTsqoPBc7E4nA.jpg"
                width="60" />
            <img alt="Profile picture of Artem Jones" height="40"
                src="https://storage.googleapis.com/a1aa/image/dejGwbJKqP2DOiHnWZPtQ0zkOESO4fBLzHeulTsqoPBc7E4nA.jpg"
                width="40" style="opacity: 35%;" />
            <div class="profile-info4">
                <h4>
                    Testimonial 1
                </h4>

            </div>
        </div>
    </div>

</body>

</html>
https://roadmap.sh/projects/testimonial-cards
