<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <header>
        <h1>Tyler Bennett</h1>
        <p></p>
    </header>
    <nav>
        <ul>
            <li><a href="#assessment">Self Assessment</a></li>
            <li><a href="#SWE">Software Engineering and Design</a></li>
            <li><a href="#DSA">Algorithms and Data Structures</a></li>
            <li><a href="#DB">Databases</a></li>
            <li><a href="review">Code Review</a></li>
        </ul>
    </nav>
    <section id="assessment">
        <h2>Introduction</h2>
        <p>Hello, my name is Tyler Bennett. I began my Journey at SNHU in January of 2018 with a major in Graphic Design. As part of that degree program I had to take an HTML/CSS course where I started to realize I wanted to work on the backend of things. This led me to change my major to Computer Science in January of 2019. This portfolio highlights my growth and abilities. This program has taught me a lot about myself and my abilities. The three most important things I’ve learned would be: 
          <ul>
            <li>Sometimes you must step away from a problem for a while in order to solve it </li>
            <li>Breaking things down into smaller tasks makes the project as a whole much less daunting</li>
            <li>Mapping out your idea and following coding standards will increase your chances for success while lessening the struggle.</li>
          </ul>
</p>
    </section>
        <h2>Self Assessment</h2>
       <p>
         	Completing a degree in Computer Science has been a transformative journey that has equipped me with a diverse set of technical skills, problem-solving abilities, and an understanding of technology's role in solving real-world challenges. This assessment reflects on my academic experience, professional development, and readiness to contribute effectively to the tech industry. While this isn’t an ell encompassing reflection of my time at Southern New Hampshire University, this ePortfolio is a reflection of my knowledge in three categories: Software Design and Engineering, Algorithms and Data Structures, and Databases. 
	The first project highlights my knowledge of Software Design and Engineering. I have taken a simple c++ app and transformed it into a functional python script. I used this transformed python script in combination with a crud python script to create my second project. My second project that highlights my Data Structure and Algorithm abilities, takes these two python scripts and connects them to a mongoDB allowing the Admin to create a new user, read the data in the database, update a user, and finally delete a user. Finally, my project three deliverable meets the Database requirements. For this deliverable I continued with the theme and created a web interface for the previously worked on application. This web interface uses HTML, CSS, python, and flask to allow for a more seamless use of the backend code. These projects showcase my ability to take an unpolished application, rewrite it in a new language and from there create a functioning web interface that follows secure coding best practices. 
	Although this ePortfolio only showcases part of what I’ve learned over the years at SNHU, it is a great base indication of what I’m capable of doing and contributing. Outside of learning various languages such as Java, C++, C, SQL, Python and HTML/CSS, I’ve also learned about topics like Object Oriented Programming and Data Structures and Algorithms. These classes are at the backbone of every Computer Science degree program. Through my Computer Science program, I have developed a comprehensive understanding of key areas, including teamwork, stakeholder communication, and security. These classes are what I believe sets SNHU grads apart from other grads. I have participated in numerous team-based projects, such as those in CS-310, where I contributed to activities like maintaining changelogs and conducting code reviews. These experiences enhanced my collaboration and planning abilities in software development. I also honed my skills in stakeholder communication by engaging in courses and assignments focused on delivering well-rounded software solutions. My studies in the Software Development Lifecycle provided me with insights into various team roles, including QA, product ownership, project management, and development.
Security was another vital component of my education. I completed multiple courses, such as Secure Coding, Reverse Software Engineering, and Client-Server Development, that deepened my understanding of secure software practices. Particularly in Secure Coding, I learned about creating security policies and addressing software vulnerabilities effectively. 
As you review my projects you can look for the following outcomes:
         <ul>
           <li>Course Outcome 1: Employ strategies for building collaborative environments that enable diverse audiences to support organizational decision making in the field of computer science.
</li>
           <li>Course Outcome 2: Design, develop, and deliver professional-quality oral, written, and visual communications that are coherent, technically sound, and appropriately adapted to specific audiences and contexts
</li>
           <li>Course Outcome 3: Design and evaluate computing solutions that solve a given problem using algorithmic principles and computer science practices and standards appropriate to its solution, while managing the trade-offs involved in design choices
</li>
           <li>Course Outcome 4: Demonstrate an ability to use well-founded and innovative techniques, skills, and tools in computing practices for the purpose of implementing computer solutions that deliver value and accomplish industry-specific goals
</li>
           <li>Course Outcome 5: Develop a security mindset that anticipates adversarial exploits in software architecture and designs to expose potential vulnerabilities, mitigate design flaws, and ensure privacy and enhanced security of data and resources
</li>
         </ul>
       </p>
    <section id="SWE">
        <h2>Software Engineering and Design</h2>
        <p> The artifact I have selected for category one is a .cpp file of a simple brokerage app. The .cpp file used a single hardcoded user password and had 3 menu options. I created this a few months ago as part of another class for my degree. I have taken the original file and transformed it into a python program with added features and security. I selected this artifact because I think it’s easy to identify the changes made and the improvements from the first .cpp file to the new .py file. While I am happy with its current progress, I will be adding more enhancements as part of category two and three for the final project. I want to show my abilities to take something simple and turn it into a functional program with a working database and interface. As of now, the artifact meets several of the course outcomes but will eventually meet all of them. 
	The process of modifying and enhancing the artifact was a fun one. While the python language is one I am familiar with having taken several classes using it, it’s been a while since I have actually used it. I used various internet resources to refresh my memory on syntax but after that it was relatively smooth sailing. Since this artifact was already programed in c++ I was able to transcribe it in python using a lot of the same concepts just in a different language. One of my focuses was on input validation as well as secure coding best practices. To visit the github repository please follow this <a href="https://github.com/tbennett94/category1.git">link.</a>
</p>
    </section>
    <section id="DSA">
        <h2>Data Structures and Algorithms</h2>
        <p>The enhancement I have for this category includes a crud.py script that was created in CS 340, Advanced Programming concepts. The original artifact was used to connect to a local mongoDB. For category two, I used coding best practices to implement this functionality into my python application from category one. I built upon what was previously completed and made several other enhancements to the original app. I implemented a login feature that searches our database to validate the username and password. To further enhance our crud functions security, I verified that the user logging in had the correct permissions assigned to their account to access various features. If the role is admin then they have access to the full menu, whereas the role of user only has the rights to see their own profile. Other enhancements and security features include, limiting the number of user login attempts to 3 and the inclusion of .env and .gitignore files to hide our database log in information.
	This category meets various course outcomes. It was developed using a security mindset that anticipates exploits and vulnerabilities. It ensures privacy and enhanced security of data and resources. Combining these two functions and apps also showcases my ability to evaluate computing solutions that solve a given problem. While the functionality here is not overly complex it allows for another developer to easily introduce other functionality through collaboration such as a more complex or efficient search algorithm. 
</p>
    </section>
  <section id="DB">
    <h2>Databases</h2>
    <p>The enhancement I have for this category includes a crud.py script that was created in CS 340, Advanced Programming concepts. The original artifact was used to connect to a local mongoDB. For category two, I used coding best practices to implement this functionality into my python application from category one. I built upon what was previously completed and made several other enhancements to the original app. I implemented a login feature that searches our database to validate the username and password. To further enhance our crud functions security, I verified that the user logging in had the correct permissions assigned to their account to access various features. If the role is admin then they have access to the full menu, whereas the role of user only has the rights to see their own profile. Other enhancements and security features include, limiting the number of user login attempts to 3 and the inclusion of .env and .gitignore files to hide our database log in information.
	This category meets various course outcomes. It was developed using a security mindset that anticipates exploits and vulnerabilities. It ensures privacy and enhanced security of data and resources. Combining these two functions and apps also showcases my ability to evaluate computing solutions that solve a given problem. While the functionality here is not overly complex it allows for another developer to easily introduce other functionality through collaboration such as a more complex or efficient search algorithm. 
</p>
  </section>
  <section id="review">
    <h2>Code Review</h2>
    <p>This <a href="https://youtu.be/MQM-w2J7z_c">link</a> will take you to a youtube code review for the provided artifacts</p>
  </section>
    <footer>
        <p>&copy; 2024 Tyler Bennett</p>
    </footer>
</body>
</html>
