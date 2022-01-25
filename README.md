# neeraj00x.github.io
<html>
 
<head>
    <title>
        My Resume-GI Project
    </title>
    <style>
        #resumeBody {
            background-image: url(bg.svg) ;
        }
        #resumeNameDivision {
            margin: 2px;
            width: 40%;
        }
        
        #resumeNameHeading {
            font-size: 30px;
            font-weight: bold;
        }
        
        #resumeEmailDivision {
            text-align: right;
            margin: 2px;
            width: 40%;
        }
 
        #headingDivision {
            display: flex;
            flex-direction: row;
            justify-content: space-between;
            
        }

        .avatar {
            vertical-align: middle;
            width: 80px;
            height: 80px;
            border-radius: 50%;
            margin: 5px;
        }

        .heading {
            border: 1px solid black;
        }
 
        .body {
            border-left: 1px solid black;
            border-right: 1px solid black;
            text-align: center;
        }
 
        .bodyBottom {
            border-bottom: 2px solid black;
        }
 
        #educationalQualifications {
            width: 100%;
            margin-top: 5px;
            margin-bottom: 2px;
        }
 
        .contentHeading {
            text-align: left;
            font-weight: bold;
            font-size: 20px;
            text-decoration: underline;
        }
 
        .contentSubheading {
            text-align: left;
            font-size: 15px; 
        }
 
        .contentLocation {
            text-align: right;
            font-size: 12px;
        }
 
        .contentTime {
            text-align: right;
            font-size: 12px;
        }
 
        .contentText {
            text-align: left;
            margin-left: 5px;
        }
 
        #bottomDivision {
            display: flex;
            flex-direction: row;
            justify-content: space-evenly;
        }
        
        #leftDivision{
            margin-right: 25px;
            width: 50%;
        }
        #rightDivision{
            margin-left: 25px;
            width: 50%;
        }
        
        .sectionHeading {
            border-bottom: 3px solid black;
            border-left: 5px red;
            font-size: 25px;
            font-weight: bold;
            margin-bottom: 3px;
            background-color: lightgray;
            padding: 2px;
        }
 
    </style>
</head>
 
<body id="resumeBody">
    <div id="headingDivision">
        <div id="resumeNameDivision">
            <div id="resumeNameHeading">Neeraj Pratap Singh <br /></div>
            Junior Undergraduate <br />
            Department of Civil Engineering <br />
            IIT Kanpur <br />
        </div>
        <div>
            <img src="avatar.png" alt="Avatar" class="avatar">
        </div>
 
        <div id="resumeEmailDivision">
            nprataps@iitk.ac.in<br />
            +91-6394716665<br />
            linkedin.com/in/neeraj00x<br />
            github.com/neeraj00x<br />
        </div>
    </div>
    <div id="educationalQualifications">
        <table id="educationalQualificationsTable" width="100%" cellspacing="0">
            <thead>
                <tr style="background-color: rgb(202, 202, 202);" >
                    <th class="heading">Year</th>
                    <th class="heading">Degree</th>
                    <th class="heading">Institution (Board)</th>
                    <th class="heading">CGPA/%</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td class="body">2019-Present</td>
                    <td class="body">B. Tech, CE</td>
                    <td class="body">Indian Institute of Technology, Kanpur</td>
                    <td class="body">---/10.0</td>
                </tr>
                <tr>
                    <td class="body">2018</td>
                    <td class="body">XII</td>
                    <td class="body">MAVM VMV Kasia Kushinagar (UP Board) </td>
                    <td class="body">86.8%</td>
                </tr>
                <tr>
                    <td class="body bodyBottom">2016</td>
                    <td class="body bodyBottom">X</td>
                    <td class="body bodyBottom">MAVM VMV Kasia Kushinagar (UP Board )</td>
                    <td class="body bodyBottom">94.2%</td>
                </tr>
            </tbody>
        </table>
    </div>
    <div id="bottomDivision">
        <div id="leftDivision">
            <div class="bottomContent">

                <div class="sectionHeading">Projects</div>
                <div class="contentHeading">Ardupilot</div> 
                <div class="contentSubheading">Organized by SnT Council, IITK</div>
                <div class="contentTime">Summer 2020</div>
                <div class="contentText">
                    <ul>
                    <li>Learnt about Ardupilot Software used in building autonomous drones and aircrafts.</li>
                    <li>Used Cygwin and MAVProxy software as a ground control station to create virtual simulation.</li>
                    <li>Successfully Planned a mission for quadcopter in Mission Planner.</li>
                    <li>Simulated the mission by running <b>SITL</b> simulator in Mission Planner.</li>
                    </ul>
                </div>
            </div>
            
            <div class="bottomContent">

                <div class="contentHeading">Stock Price Prediction Using ANN</div>
                <div class="contentSubheading">Course Project under Prof. Somesh Kumar Mathur</div>
                <div class="contentTime">Even sem 2021</div>
                <div class="contentText">
                    <ul>
                        <li>Course project of course HSO201A.</li>
                        <li>Applied PCA on collected multi-dimensional raw data of 5 companies to reduce the dimensionality.</li>
                        <li>Successfully created an Artificial Neural Network(ANN) model using Deep Learning toolbox in MATLAB.</li>
                        <li>Trained it with the pre-processed data and determined values of hyperparameters(hidden layer, learning rate).</li>
                        <li>Successfully predicted the next day closing prices with minimized error using this ANN model.</li>
                    </ul>
                </div>
            </div>
            

            <div class="bottomContent">

                <div class="contentHeading">Swarm Robotics</div>
                <div class="contentSubheading">Organized by SnT Council, IITK</div>
                <div class="contentTime">Summer 2021</div>
                <div class="contentText">
                    <ul>
                        <li>Learnt about Unity3D for simulation and used C# for scripting.</li>
                        <li>Successfully created a virtual environment having obstacle in Unity3D and implemented various Obstacle Avoidance Algorithms (Navmesh Agent, Raycast, artificial Potential Field Method</li>
                    </ul>
                </div>
            </div>
            
            
        </div>
        <div id="rightDivision">
            <div class="bottomContent">
                <div class="sectionHeading">Positions of Responsibilities</div>
                <div class="contentHeading">Academic Mentor</div> 
                <div class="contentSubheading">Counselling Service, IIT Kanpur</div>
                <div class="contentText">
                    <ul>
                    <li>Conducted Academic Classes of over 100 students and many Doubt Clearing Sessions.</li>
                    <li>Mentored about 50+ students (2 on one-to-one basis) and helped them to do well in academics.</li>
                    </ul>
                </div>
            </div>
            <div class="bottomContent">
                <div class="contentHeading">Secretary</div> 
                <div class="contentSubheading">Aeromodelling Club, IIT Kanpur</div>
                <div class="contentText">
                    <ul>
                    <li>Prepared interesting articles for the club throughout the year.</li>
                    <li>Organised a quiz competition ‘Airiddle’ as a part of SnT code during Techweek.</li>
                    <li>Planned workshop, quizzes, and activities to engage freshers.</li>
                    </ul>
                </div>
            </div>
            <div class="bottomContent">
                <div class="contentHeading">Senior Executive</div> 
                <div class="contentSubheading">Take-off, Techkriti’21</div>
                <div class="contentText">
                    <ul>
                    <li>Organised event Take-off event under Techkriti’21 with a team of 3 Senior Executives and 2 Managers.</li>
                    <li>Managed to attract 100+ teams in 2 competitions with Rs 25000 total prize.</li>
                    </ul>
                </div>
            </div>
            <div class="bottomContent">
                <div class="contentHeading">Senior Executive</div> 
                <div class="contentSubheading">Hospitality, Techkriti’21</div>
                <div class="contentText">
                    <ul>
                    <li>Worked with a team of 30+ members for smooth conduction on the events</li>
                    <li>Were responsible for attracting participants for competitions and workshops.</li>
                    </ul>
                </div>
            </div>
         
         
        </div>

    </div>
    <div id="bottomDivision">
        <div id="leftDivision">
            <div class="sectionHeading">Relevant Courses</div>
            <div>
                <ul>
                <li>Fundamentals of Computing</li>
                <li>Mathematics I, Mathematics II (Linear Algebra and ODEs)</li>
                <li>Applied Probability and Statistics</li>
                <li>Computational methods in engineering</li>
                <li>Geoinformatics</li>
                </ul>
            </div>
        </div>
        <div id="rightDivision">
            <div class="sectionHeading">Online Course</div>
            <div>
                <h4>Global Navigation Satellite System</h4>
                <ul>
                <li>Introduction to GPS, GNSS & IRNSS</li>
                <li>GPS receivers, processing methods, errors, and accuracy</li>
                <li>Satellite Based Augmentation System & GPS Aided and Geo Augmented Navigation (GAGAN)</li>
                <li>GPS Signal Characteristics and Data formats</li>
                </ul>
            </div>
        </div>
    </div>
</body>

</html>
