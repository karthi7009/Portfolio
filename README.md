<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Resume - Karthi</title>
    <style>
        body {
            font-family: "Times New Roman", Times, serif;
            background-color: #f4ede4;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 150vh;
            margin: 0;
        }
        .resume {
            width: 500px;
            background-color: #ffffff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
            text-align: center;
           
        }
        .header {

            align-items: center;
        }
        #profile-pic{
            width: 100px;
            height:100px;
            border-radius: 50%;
           margin-right: 20px;
        }
        ul {
            padding-left: 20px;
        }

        h1 {
            margin: 10px 0;
            font-size: 24px;
            color: #8b5e3c;
        }
        .section {
            margin-top: 15px;
        }
        .section h2 {
            font-size: 18px;
            color: #8b5e3c;
            border-bottom: 1px solid #8b5e3c;
            padding-bottom: 5px;
        }
        .section p, .section ul {
            font-size: 14px;
            color: #5a4631;
        }
        ul {
            list-style: none;
            padding: 0;
        }
        ul li {
            margin: 5px 0;
        }
    </style>
</head>
<body>
    <div class="resume">
        <div class="header">
        <input type="file" id="imageUpload" accept="image/*">
        <img id="profile-pic" src="" alt="Profile Picture" style="display:none;">
        
        <div>
           <h1>KARTHI A</h1>
            <p>Bachelor of Science in Computer Science</p>
<p>📞 8438446052 </p> 
<p>📍 48L housing unit mettupalayam 641305</p>
<p>✉ K31141826@gmail.com/p>
</div>
</div>
        <div class="section">
            <h2>About Me</h2>
            <p>Highly motivated Computer Science Graduate with a passion for developing innovative software solutions. </p>
        </div>
        <div class="section">
            <h2>Study</h2>
            <ul>
                <li> Government higher secondary school , mettupalayam</li>
            </ul>
        </div>
        <div class="section">
            <h2>Skills</h2>
            <ul>
                <li>Java</li>
                <li>C Programming</li>
                <li>Strong Communication</li>
                <li>Master English</li>
                <li>Public Speaking</li>
            </ul>
        </div>
        <div class="section">
            <h2>Favorite</h2>
            <ul>
                <li>Painting</li>
                <li>Photography</li>
                <li>Travelling</li>
            </ul>
        </div>
        <div class="section">
            <h2>Languages</h2>
            <ul>
                <li>Tamil</li>
                <li>English</li>
            </ul>
        </div>
<div class="section certifications">
            <h2>Certifications</h2>
            <ul>
                <li>TNSDC-FEWD &Cloud</li>
                </ul>
        </div>
    </div>
<script>
        document.getElementById('imageUpload').addEventListener('change', function(event) {
            const file = event.target.files[0];
            if (file) {
                const reader = new FileReader();
                reader.onload = function(e) {
                    const img = document.getElementById('profile-pic');
                    img.src = e.target.result;
                    img.style.display = 'block';
                }
                reader.readAsDataURL(file);
            }
        });
    </script>

</body>
</html>
