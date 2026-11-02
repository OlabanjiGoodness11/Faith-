

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Personal CV Website</title>

    <!-- Link to external CSS -->
    <link rel="stylesheet" href="style.css">
</head>

<body>

    <header>
        <h1>Olabanji Goodness</h1>
        <h3>Residential Address: Your Address</h3>
        <h3>Email: abosede001@email.com</h3>
        <h3>Phone:08060107992</h3>
    </header>

    <main>

        <section>
            <h2>Personal Information</h2>
            <p><strong>Date of Birth:</strong> 11/01/2013</p>
            <p><strong>Gender:</strong>Male</p>
            <p><strong>Nationality:</strong> Nigerian</p>
            <p><strong>State of Origin:</strong> Kwara State</p>
        </section>

        <section>
            <h2>Career Objective</h2>
            <p>
                I am a hardworking, responsible and determined student
                who is willing to learn new skills, gain knowledge and
                contribute positively to society. I hope to develop my
                abilities and achieve academic and career success.
            </p>
        </section>

        <section>
            <h2>Educational Background</h2>

            <h3>Primary Education</h3>
            <p>School: Federal College of Education Staff School School</p>
            <p>Years Attended: 2016 - 2022</p>

            <h3>Secondary Education</h3>
            <p>School: Federal College of Education Model Secondary School</p>
            <p>Years Attended: 2022 - Present</p>
        </section>

        <section>
            <h2>Skills</h2>
            <ul>
                <li>Communication skills</li>
                <li>Computer skills</li>
                <li>Teamwork</li>
                <li>Problem-solving</li>
                <li>Creativity</li>
            </ul>
        </section>

        <section>
            <h2>Hobbies and Interests</h2>
            <ul>
                <li>Reading</li>
                <li>Learning new things</li>
                <li>Playing games</li>
                <li>Listening to music</li>
                <li>Travelling</li>
            </ul>
        </section>

        <section>
            <h2>Achievements</h2>
            <ul>
                <li>Participated in school competitions.</li>
                <li>Received recognition for good conduct.</li>
                <li>Participated in academic activities.</li>
            </ul>
        </section>

        <section>
            <h2>Referees</h2>

            <h3>Referee 1</h3>
            <p>Name: Mr Hassan</p>
            <p>Occupation: Teacher</p>
            <p>Phone:0904867979</p>

            <h3>Referee 2</h3>
            <p>Name:Mrs Abosede Olajumoke Olabanji</p>
            <p>Occupation:Lecturer</p>
            <p>Phone:08060107992</p>

            <h3>Referee 3</h3>
            <p>Name:Dr Olabanji Samuel</p>
            <p>Occupation: Lecturer</p>
            <p>Phone:08025326010</p>
        </section>

    </main>

    <footer>
        <p>&copy; 2026 Olabanji Goodness. All Rights Reserved.</p>
        <p>My Personal CV Website</p>
    </footer>

</body>
</html>
CSS

/* General page styling */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f0f4f8;
    color: #333;
    line-height: 1.7;
}

/* Header styling */
header {
    background-color: #123456;
    color: white;
    text-align: center;
    padding: 35px 15px;
}

header h1 {
    font-size: 32px;
    margin-bottom: 15px;
}

header h3 {
    font-size: 15px;
    font-weight: normal;
}

/* Main content */
main {
    width: 85%;
    max-width: 900px;
    margin: 25px auto;
}

/* Section styling */
section {
    background-color: white;
    margin-bottom: 20px;
    padding: 22px;
    border-radius: 8px;
    box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
}

section h2 {
    color: #123456;
    border-bottom: 2px solid #123456;
    padding-bottom: 8px;
    margin-bottom: 15px;
}

section h3 {
    color: #2874a6;
    margin-top: 12px;
}

section p {
    margin: 5px 0;
    
}

section ul {
    padding-left: 25px;
}

/* Footer styling */
footer {
    background-color: #123456;
    color: white;
    text-align: center;
    padding: 20px;
    margin-top: 30px;
}

/* Mobile phone styling */
@media screen and (max-width: 600px) {
    main {
        width: 95%;
    }

    header h1 {
        font-size: 25px;
    }

    section {
        padding: 15px;
    }
}
