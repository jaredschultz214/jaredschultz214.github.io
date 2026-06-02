---
layout: default
title: Resume
---

<style>
.resume-container {
    max-width: 1000px;
    margin: auto;
    padding: 20px;
    line-height: 1.5;
}

.resume-header {
    text-align: center;
    margin-bottom: 30px;
}

.resume-header h1 {
    margin-bottom: 5px;
}

.contact {
    font-size: 0.95em;
}

.section {
    margin-top: 30px;
}

.section h2 {
    border-bottom: 2px solid #ccc;
    padding-bottom: 5px;
    margin-bottom: 15px;
}

.entry {
    margin-bottom: 20px;
}

.entry-header {
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
    font-weight: bold;
}

.entry-subheader {
    font-style: italic;
    margin-bottom: 5px;
}

.skills-table {
    width: 100%;
    border-collapse: collapse;
}

.skills-table td {
    padding: 4px 8px;
    vertical-align: top;
}

.skills-table td:first-child {
    font-weight: bold;
    width: 140px;
}

ul {
    margin-top: 5px;
}

@media (max-width: 700px) {
    .entry-header {
        flex-direction: column;
    }
}
</style>

<div class="resume-container">

<div class="resume-header">
    <h1>Jared J. Schultz</h1>
    <div class="contact">
        <a href="mailto:schu4422@umn.edu">schu4422@umn.edu</a> |
        <a href="mailto:jaredschultz214@gmail.com">jaredschultz214@gmail.com</a> |
        763-732-2783
        <br>
        <a href="media/Jared Schultz 1 page resume.pdf" target="_blank">
            <i class="fa fa-file-pdf-o" aria-hidden="true"></i>
            One Page Resume PDF 
        </a>
         | 
        <a href="media/Jared Schultz 2 page resume.pdf" target="_blank">
            <i class="fa fa-file-pdf-o" aria-hidden="true"></i>
            Two Page Resume PDF
        </a>
    </div>
</div>

<div class="section">
    <h2>Education</h2>
    <div class="entry">
        <div class="entry-header">
            <span>University of Minnesota – Twin Cities</span>
            <span>Sep 2024 – May 2026</span>
        </div>
        <div class="entry-subheader">
            M.S. Robotics, Minor in Mechanical Engineering
        </div>
        GPA: 4.00
    </div>
    <div class="entry">
        <div class="entry-header">
            <span>University of Minnesota – Twin Cities</span>
            <span>Sep 2020 – May 2024</span>
        </div>
        <div class="entry-subheader">
            B.S. Computer Engineering
        </div>
        GPA: 3.52
    </div>
</div>

<div class="section">
    <h2>Technical Skills</h2>
    <table class="skills-table">
        <tr>
            <td>Robotics</td>
            <td>Computer Vision, Machine Learning, AI, Path Planning, Kalman Filtering, Feedback Control, Force Feedback</td>
        </tr>
        <tr>
            <td>Programming</td>
            <td>C, C++, Java, Python, ROS, Bash, MATLAB, Verilog</td>
        </tr>
        <tr>
            <td>Mechanical</td>
            <td>SolidWorks, RoboDK, SLA/FDM 3D Printing, Mill, Lathe, Waterjet (Maxiem)</td>
        </tr>
        <tr>
            <td>Electrical</td>
            <td>Circuit Analysis, Altium Designer, Vivado FPGA</td>
        </tr>
        <tr>
            <td>Tools and Platforms</td>
            <td>Git, Jira, Confluence, Linux, NumPy, PyTorch, TensorFlow</td>
        </tr>
    </table>
</div>

<div class="section">
    <h2>Experience</h2>
    <div class="entry">
        <div class="entry-header">
            <span>University of Minnesota & Medtronic Inc.</span>
            <span>Jun 2025 – May 2026</span>
        </div>
        <div class="entry-subheader">
            Mechatronic Lead – Autonomous Telerobotic Surgical Stroke Robot
        </div>
        <ul>
            <li>Collaborated with neurosurgeons, engineering faculty, and Medtronic leadership to define system requirements for a cost-efficient robot able to perform remote thrombectomy.</li>
            <li>Integrated mechanical, embedded, and AI-driven subsystems into a unified robotic architecture for remote guidewire navigation. Live Demo: 
            <a href="https://telebot.cse.umn.edu">
                telebot.cse.umn.edu 
            </a></li>
            <li> Built an automated test platform using an ATI Nano17 6-DOF force/torque sensor and a stepper-actuated test rig to characterize prototype performance, accelerate wear, and identify failure modes to promote device longevity.</li>
            <li>Designed, manufactured, and validated multiple robot prototypes using custom SLA printed gears, hypoid transmissions, and differential mechanisms, using experimental results to drive design improvements.</li>
            <li>Designed and implemented a motor control architecture that decouples degrees of freedom and enables precise speed and position control of the 3-DOF rolling contact mechanism.</li>
        </ul>
    </div>
    <div class="entry">
        <div class="entry-header">
            <span>General Dynamics Mission Systems</span>
            <span>May 2022 – Aug 2022</span>
        </div>
        <div class="entry-subheader">
            Software Engineering Intern
        </div>
        <ul>
            <li>Translated the existing test environment from Bash into Python to improve readability and package support.</li>
            <li>Traced bugs through layers of code and wrote tickets for unresolved issues with detailed reproduction steps.</li>
            <li>Anticipated future requirements and implemented features into the test environment to promote code longevity.</li>
            <li>Determined software requirements and developed system tests to validate the state of the project.</li>
            <li>Contributed to professional documentation through Confluence, understood team workflow through Jira, and streamlined version control through GitLab.</li>
        </ul>
    </div>
</div>

<div class="section">
    <h2>Publications</h2>
    <div class="entry">
        <strong>Friction Characterization of a Roller-Drive Mechanism for Robotic Motion Control of Guidewires</strong><br>
        Jared Schultz, Pin-Hao Cheng, Matt Rajala, Timothy M. Kowalewski<br>
        Design of Medical Devices Conference (DMD 2026)
    </div>
    <div class="entry">
        <strong>Towards Remote Thrombectomy with Telerobotically-Driven Guidewires</strong><br>
        Pin-Hao Cheng*, Ronak Narkhede*, Matt Rajala*, Jared Schultz*, Nathan Harbinson, Samuel Fisher, Nitish Poojari, Sharva Khandagale, Alex Berg, Keara Berlin, Adam Imdieke, Michael Feldkamp, Scott Frushour, Kaustubh Patil, Mark Ashby, William Peine, Sean L. Moen, Andrew Grande, Karthik Desingh, Timothy M. Kowalewski.<br>
        * Contributed equally, listed alphabetically by last name<br>
        Design of Medical Devices Conference (DMD 2026)
    </div>
</div>

<div class="section">
    <h2>Selected Projects</h2>
    <div class="entry">
        <div class="entry-header">
            <span>Computer Vision & ML System for ARC Robotics</span>
            <span>2025</span>
        </div>
        <ul>
            <li>Created a custom neural stack that identifies, tracks, and predicts robot motion in a moving-camera, moving-target environment.</li>
            <li>Achieved 98% classification accuracy with a 3 ms loop time.</li>
            <li>Optimized deployment for NVIDIA Jetson Orin Nano hardware.</li>
        </ul>
    </div>
    <div class="entry">
        <div class="entry-header">
            <span>Intermediate Medical Robotics</span>
            <span>2024</span>
        </div>
        <ul>
            <li>Implemented kinematics, Jacobian inverse kinematics, path planning, and self-motion for hyper-redundant robots.</li>
            <li>Developed teleoperation and feedback-control systems for UR5 robotic platforms.</li>
        </ul>
    </div>
</div>

<div class="section">
    <h2>Leadership</h2>
    <div class="entry">
        <div class="entry-header">
            <span>Northstar Robotics</span>
            <span>2024 – Present</span>
        </div>
        <div class="entry-subheader">
            Founding Member & Mechanical Captain
        </div>
        <ul>
            <li>Coordinate CAD and machining workshops.</li>
            <li>Lead design reviews and competition compliance checks.</li>
            <li>Organize meetings and delegate technical responsibilities.</li>
        </ul>
    </div>
    <div class="entry">
        <div class="entry-header">
            <span>Triangle Fraternity MN Chapter</span>
            <span>2022 – 2026</span>
        </div>
        <div class="entry-subheader">
            Vice President of Internal Affairs, Project Manager, Ritual Keeper
        </div>
        <ul>
            <li>Worked directly with contractors and house inspectors to identify and prioritize necessary and feasible changes.</li>
            <li>Organized and carried out project work days for large house repairs and improvements.</li>
        </ul>
    </div>
    <div class="entry">
        <div class="entry-header">
            <span>FIRST Robotics</span>
            <span>2018 – 2020</span>
        </div>
        <div class="entry-subheader">
            Lead Programmer & Team Captain
        </div>
        <ul>
            <li>Managed software development and mentored new programmers.</li>
            <li>Developed subsystem software, testing procedures, and integration workflows.</li>
        </ul>
    </div>
    <div class="entry">
        <div class="entry-header">
            <span>Boy Scouts America</span>
            <span>2015 - 2018</span>
        </div>
        <div class="entry-subheader">
            Eagle Scout, Senior Patrol Leader, Troop Guide
        </div>
        <ul>
            <li>Managed multiple teams of over 30 volunteers. My Eagle project totaled over 300 hours of volunteer work. </li>
        </ul>
    </div>
</div>

</div>



