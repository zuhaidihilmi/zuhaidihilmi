<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Zuhaidi Hilmi</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }

        header {
            background: #333;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }

        nav a {
            color: #fff;
            padding: 10px;
            text-decoration: none;
        }

        main {
            padding: 20px;
        }

        section {
            margin-bottom: 30px;
        }

        h2 {
            color: #333;
            border-bottom: 2px solid #333;
            padding-bottom: 5px;
            margin-bottom: 15px;
        }

        .skills-container {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }

        .skill {
            display: flex;
            align-items: center;
            width: calc(50% - 20px); /* Adjusts skill width for two-column layout */
            margin-bottom: 10px;
        }

        .skill p {
            flex-basis: 30%;
            margin-right: 10px;
        }

        .skill progress {
            flex-grow: 1;
        }

        img {
            max-width: 100%;
            height: auto;
        }

        table {
            width: 100%;
            border-collapse: collapse;
        }

        table, th, td {
            border: 1px solid black;
        }

        th, td {
            padding: 8px;
            text-align: left;
        }

        ul {
            list-style-type: none;
        }
    </style>
</head>
<body>
    <header>
        <h1>Mohd Zuhaidi Hilmi Bin Ahmad</h1>
        <nav>
            <a href="#personal">Personal Details</a>
            <a href="#experience">Work Experience</a>
            <a href="#education">Education</a>
            <a href="#portfolio">Portfolio</a>
            <a href="#courses">Courses</a>
            <a href="#skills">Skills</a>
            <a href="#reference">Reference</a>
        </nav>
    </header>

    <main>
        <section id="personal">
            <h2>Personal Details</h2>
            <figure>
                <img src="editor.jpg" alt="Photo of Zuhaidi Hilmi">
            </figure>
            <p>Address: No 22, Jalan Seroja 15, Taman Seroja, Bandar Baru Salak Tinggi, 43900 Sepang, Selangor.</p>
            <p>Email: zuhaidi.hilmi@gmail.com</p>
            <p>Phone number: +6010-5757058</p>
        </section>

        <section id="experience">
            <h2>Work Experience</h2>
            <h3>Independent Aircraft Technical Consultant</h3>
            <ul>
                <li>Study Airworthiness Directive (AD)/Service Bulletin (SB) applicability.</li>
                <li>Ensure redelivered aircraft components meet documentation requirements.</li>
                <li>Monitor task progress at Maintenance Repair Overhaul (MRO) centers.</li>
                <li>Liaise with customer representatives to solve outstanding issues.</li>
            </ul>

            <h3>Technical Records cum Maintenance Operation Centre (MOC) Officer</h3>
            <h4>Airasia Berhad (Nov 2019-Jan 2020)</h4>
            <ul>
                <li>Create engineering process manual for checks and weekly process verification.</li>
                <li>Follow up on spare availability for deferred defect aircraft tasks.</li>
                <li>Monitor Deferred Defect Monitoring Log for due time.</li>
            </ul>

            <h3>Technical Records Consultant</h3>
            <h4>Pricewaterhouse Coopers, PWC (Mar 2019 – Oct 2019)</h4>
            <ul>
                <li>Retrieve all DFPs from check packages.</li>
                <li>Prepare Aircraft Dent & Buckle report mapping.</li>
                <li>Coordinate redelivery documentation with departments.</li>
            </ul>

            <h3>Lease Planning Officer</h3>
            <h4>Malaysia Airlines Berhad (Oct 2017 – Mar 2019)</h4>
            <ul>
                <li>Perform cost-benefit analysis (CBA) for lease extension studies.</li>
                <li>Prepare redelivery adjustments and maintenance forecasts.</li>
                <li>Act as a liaison and provide information on aircraft audits.</li>
            </ul>
        </section>

        <section id="education">
            <h2>Education</h2>
            <h3>Tertiary Education</h3>
            <p>Master in Business Administration (2024 - 2026)</p>
            <p>University of Technology MARA</p>
            
            <h3>Higher Education</h3>
            <p>Bachelor of Aerospace Engineering (2013 - 2017)</p>
            <p>International Islamic University Malaysia</p>

            <h3>Secondary Education</h3>
            <p>Pure Sciences (2006-2010)</p>
            <p>Sekolah Menengah Kebangsaan Agama Wataniah</p>
        </section>

        <section id="portfolio">
            <h2>Portfolio</h2>
            <table>
                <tr>
                    <th>No</th>
                    <th>Project Type</th>
                    <th>Consultant agency/Company</th>
                    <th>Lessor/Lessee</th>
                    <th>AC Type</th>
                    <th>MSN</th>
                    <th>Date</th>
                    <th>Workscope</th>
                    <th>Location</th>
                </tr>
                <tr>
                    <td>1</td>
                    <td>Pre-Purchase Inspection</td>
                    <td>Readu5</td>
                    <td>Singapore Airlines</td>
                    <td>B777</td>
                    <td>28521, 28525, 28526, 30870</td>
                    <td>2021 till date</td>
                    <td>Inspection, Package Prep, Redelivery Records</td>
                    <td>Airline House SIA/Remotely</td>
                </tr>
                <!-- Add more rows as needed -->
            </table>
        </section>

        <section id="courses">
            <h2>Courses & Certificates</h2>
            <p>Safety Management System (2018)</p>
            <p>Industrial Safety Briefing (2018)</p>
            <p>Air Legislation (2019)</p>
            <p>Introduction to HTML5 (2020)</p>
            <p>Applied Data Scientist (2022)</p>
        </section>

        <section id="skills">
            <h2>Skills</h2>
            <div class="skills-container">
                <div class="skill">
                    <p>Microsoft Office</p>
                    <progress value="95" max="100"></progress>
                </div>
                <div class="skill">
                    <p>AMOS</p>
                    <progress value="60" max="100"></progress>
                </div>
                <div class="skill">
                    <p>Business/Data Analysis</p>
                    <progress value="80" max="100"></progress>
                </div>
                <div class="skill">
                    <p>HTML 5</p>
                    <progress value="20" max="100"></progress>
                </div>
                <div class="skill">
                    <p>CSS</p>
                    <progress value="20" max="100"></progress>
                </div>
                <div class="skill">
                    <p>Strategic Marketing</p>
                    <progress value="70" max="100"></progress>
                </div>
                <div class="skill">
                    <p>myBOEINGfleet/AIRBUS World</p>
                    <progress value="90" max="100"></progress>
                </div>
            </div>
        </section>

        <section id="reference">
            <h2>Reference</h2>
            <table>
                <tr>
                    <th>No</th>
                    <th>Name</th>
                    <th>Relation</th>
                    <th>Current Position</th>
                    <th>Contact info</th>
                </tr>
                <tr>
                    <td>1</td>
                    <td>Nazaleq Zainuddin</td>
                    <td>Former Superior</td>
                    <td>Engineering Director, AAT Subang</td>
                    <td>nazaleq@pakaravia.com<br>+60196650732</td>
                </tr>
                <tr>
                    <td>2</td>
                    <td>Amirul Aimin Jumaat</td>
                    <td>Former Colleague</td>
                    <td>Independent Consultant</td>
                    <td>
                </tr>
