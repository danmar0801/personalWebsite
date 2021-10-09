# this is my personal website


# layout 
1. there is going to be 5 main section at the moment
2. Sections:
    a. landing
        I. I am a front-end developer and software engineer...
        II. Socials Such as:
            1. github
            2. linkedIn
            3. medium
            4. maybe others too
        III. maybe put a profile picture
    b. about
        ...
    c. skills
        I. WebDev
            1. HTML
            2. CSS
            3. JS
        II. iOS
            1. XCODE
            2. SWIFT
        III. Other
            1. GitHub
            2. GIT
            3. Adobe XD
            4. Unity
    d. projects
        ...
    e. contact
        1. put email
        2. linkedIn





        <h2 class="section_title">Skills</h2>
        <div class="container_1">
                <h2 class="title_2">Technical Skills</h2>
                <div class="container_2">
                    <h4 class="title_4">Web Development:</h4>
                        <p>HTML</p>
                        <p>CSS</p>
                        <p>JS</p>
                </div>
                <div class="container_2" id="skills-left-push">
                    <h4 class="title_4">Mobile Development:</h4>
                        <p>Xcode</p> 
                        <p>Swift</p> 
                </div>
                <div class="container_2">
                    <h4 class="title_4">Others:</h4>
                        <p>Git/GitHub</p>
                        <p>AdobeXD</p>
                        <p>Unity Engine</p>
                </div>
            <div class="container_2">
                <h2 class="title_2">Soft Skills</h2>
                    <p>Team Work</p>
                    <p>Problem Solving</p>
                    <p>Strong Organizational & Time Management</p>
                    <p>Open-mindedness and adaptability</p>
                    <p>Communication</p>
            </div>
        </div>




        .section_title {
    font-size: 40px;
    margin: 10px 5px 20px 5px;
}

.title_2{
    font-size: 25px;
    margin: 10px 0;
    text-align: center;
}
.title_4 {
    font-size: 20px;
    margin: 5px 0;
}
.container_1{
    width: 75%;
    padding: 0 10px;
}
.container_2{
    display: flex;
    flex-direction: column;
    justify-content: center;
    height: 200px;
}