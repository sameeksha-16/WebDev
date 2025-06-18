### code
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @media (max-width: 540px) {
              
            .card {
                background-color:white ;
                
                margin: auto;
            }
            .item{
                background-color: pink;
            }
        }
    </style>
</head>
<body class="bg-[#FFFBDE] min-h-screen w-full">
    <div class="grid w-full h-screen gap-x-[50px] gap-y-[50px]" style="grid-template-columns:1.2fr 2fr 2fr; grid-template-rows:0.3fr 1fr 0.5fr 1.3fr;">

        <div class="col-span-3 flex justify-center items-center bg-[#096B68] text-[#FFFBDE] font-['Lucida_Sans'] text-[4em]">
            <h1>PROFILE</h1>
        </div>

        <div class="row-start-2 row-end-5 bg-[#096B68] text-[#FFFBDE] font-[Verdana] flex flex-col items-center pt-[250px]">
            <img src="profile.jpg" alt="hi" class="h-[900px] p-[200px] rounded-[35%]">
            <p class="text-center text-[5em] mt-4">SAMEEKSHA BAJORIA</p>
            <ul class="text-[4em] mt-4">
                <li>AGE:18</li>
                <li>Qualifications:Student</li>
                <li>Institution:Manipal Institute Of Tech</li>
            </ul>
            <p class="mt-4 text-[4em]">Developer</p>
        </div>

        <div class="col-start-2 col-end-4 row-start-2 row-end-3 flex items-center justify-center text-center px-[250px] bg-[#90D1CA] font-[Verdana] text-[4em]">
            <p>Hi, I'm Sameeksha — an aspiring developer with a passion for coding and continuous learning. I love building things that solve real problems, and I'm always eager to explore new technologies and improve my skills. Beyond the code, I enjoy interacting with people, exchanging ideas, and learning from every conversation. Whether it's through collaboration or curiosity, I'm driven by the excitement of what's possible when technology and creativity come together.</p>
        </div>

        <div class="col-start-2 col-end-4 row-start-3 row-end-4 flex items-center justify-center gap-[80px] bg-[#90D1CA]">
            <p class="text-[4em]">Say Hello</p>
            <a href="https://www.instagram.com/sameeksha_.16">
                <img src="insta.jpg" alt="Instagram" class="w-[200px]">
            </a>
            <a href="https://www.linkedin.com/in/">
                <img src="link.jpg" alt="LinkedIn" class="w-[200px]">
            </a>
        </div>

        <div class="bg-[#90D1CA] p-[30px] font-[Verdana] text-[4em]">
            <p class="font-bold">SKILLS</p>
            <p class="mt-2">I’m comfortable with core programming languages like Python, Java, C++, JavaScript, and SQL that help me build logic and solve real-world problems.
            I’ve explored development by building web projects using HTML, CSS, JavaScript, and version control tools like Git.
            I’ve also started learning AI and machine learning, using Python libraries to build basic models and analyze data.</p>
        </div>

        <div class="bg-[#90D1CA] p-[30px] font-[Verdana] text-[4em]">
            <p class="font-bold">PROJECTS</p>
            <p class="mt-2">Portfolio Website - Built using HTML, CSS, and JavaScript to showcase skills, projects, and contact details with a responsive and user-friendly design.</p>
            <p class="mt-2">Spam Message Classifier - Developed using Python and scikit-learn to classify messages as spam or not by applying basic natural language processing and machine learning techniques.</p>
        </div>

    </div>
</body>
</html>
```
![my](finalpng)
