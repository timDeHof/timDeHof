<div id="header" align="center">
  <img src="https://media.giphy.com/media/jdPMeyv9rn0hZHh8n9/giphy.gif" width="100">

<div id="badges" align="center">
  <a href="https://www.linkedin.com/in/timothy-dehof/">
    <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
  </a>
  <a href="https://twitter.com/timdehof">
    <img src="https://img.shields.io/badge/Twitter-blue?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter Badge"/>
  </a>
  <a href="https://codepen.io/timdehof">
        <img src="https://img.shields.io/badge/codepen-gray?style=for-the-badge&logo=codepen&logoColor=white" alt="Codepen Badge"/></a>
  <a href="https://www.polywork.com/timdehof">
    <img src="https://img.shields.io/badge/Polywork-blue?style=for-the-badge&logo=polywork&logoColor=white" alt="Polywork Badge"/>
  </a>
</div>
<div id="badges" >
  <img src="https://komarev.com/ghpvc/?username=timDeHof&style=flat-square&color=blue" alt=""/>
  <h1>
    Hi there 
    <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="30"/>
  </h1> 
</div>
  <a href="https://app.daily.dev/timdehof"><img src="https://github.com/timDeHof/timDeHof/blob/main/devcard.svg" width="300" alt="tim DeHof's Dev Card"/></a>
  </div>  
  
***

### 👨‍💻 About Me :
I am a Full Stack Developer <img src="https://media.giphy.com/media/WUlplcMpOCEmTGBtBW/giphy.gif" width="30"> from Florida.
- 😄 Pronouns: (he/him)
- 🔭 I’m currently looking for job opportunities and continuing my education in tech.
- 👯 I’m looking to collaborate on Projects.
- 🌱 I’m currently learning the PERN tech stack,redux, and typescript.
- ⚡ When I am not coding, I enjoy anime, video games, and reading tech articles.
- :mailbox: How to reach me: [![Linkedin Badge](https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/timothy-dehof/) [![Gmail Badge](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ttdehof@gmail.com)
***
### 📙 Blog Posts

<!--START_SECTION:feed-->
#### [Unleash the Power of Java: A JavaScript Developer&#39;s Guide to Best Practices in Java Development](https:&#x2F;&#x2F;blog.timdehof.dev&#x2F;unleash-the-power-of-java-a-javascript-developers-guide-to-best-practices-in-java-development) 
*As a JavaScript developer diving into the world of Java, I&#39;ve observed several keys differences in best practices and conventions. In this post, I&#39;ll share my insights on object-oriented programming, code style and formatting, and exception handling in Java.
Object-Oriented Programming
Java is an object-oriented language, where entities and their properties are represented as objects. It also follows the SOLID principles, a set of five guidelines for creating maintainable and scalable software. In contrast, JavaScript is a prototype-based language that uses objects as blueprints for creating new objects.
public class Dog {
    private String name;
    private int age;

    public Dog(String name, int age) {
        this.name &#x3D; name;
        this.age &#x3D; age;
    }

    public String getName() {
        return name;
    }

    public int getAge() {
        return age;
    }
}

class Dog {
    constructor(name, age) {
        this.name &#x3D; name;
        this.age &#x3D; age;
    }

    getName() {
        return this.name;
    }

    getAge() {
        return this.age;
    }
}

A few key differences between Java and JavaScript include:
Class Declaration: Java classes are declared with the class keyword, while JavaScript classes use the class keyword from ECMAScript 2015 (ES6).
Constructors: Java constructors are declared with the public keyword, followed by the class name and constructor arguments. In JavaScript, constructors are declared with the constructor keyword and constructor arguments.
Access Modifiers: Java has access modifiers, such as private, to control the visibility of class members. JavaScript doesn&#39;t have access modifiers, but the _ (underscore) prefix is often used to indicate private properties.
Methods: Both Java and JavaScript use the function keyword to declare methods. In Java, methods are declared inside the class, while in JavaScript, methods are declared inside the class using the methodName() syntax.
It&#39;s essential for a JavaScript developer transitioning to Java to understand these differences in class declaration, constructors, access modifiers, and method declaration.
Code Style and Formatting
The Java Community Process defines a well-established coding standard for Java, which includes format, naming conventions, and other coding principles. Adhering to this standard ensures readable, manageable, and consistent code. Java also requires Javadoc comments, concise documentation for classes, methods, and variable definitions.
In comparison, JavaScript doesn&#39;t have a strict coding standard, although it does have widely accepted code style guides like the Airbnb JavaScript Style Guide and the JavaScript Standard Style. These guides provide recommendations for code formatting and naming conventions, but they are not as strictly enforced as the Java coding standard.
By following a strict coding standard and focusing on code readability and maintainability, Java development prioritizes high-quality, well-organized code. This is especially important for large projects where code maintenance and updates are crucial.
Exception Handling
Java has a robust exception handling mechanism to handle errors and exceptions in a program. In contrast, JavaScript relies on try-catch blocks or custom error objects to handle errors, which can become complex in larger projects with multiple errors. Java provides a range of built-in exceptions and encourages developers to catch and handle exceptions as early as possible.
Here&#39;s an example of Java&#39;s built-in exceptions:
public class ExceptionExample {
  public static void main(String[] args) {
    try {
      int result &#x3D; divide(10, 0);
      System.out.println(result);
    } catch (ArithmeticException e) {
      System.out.println(&quot;Cannot divide by zero!&quot;);
    }
  }

  private static int divide(int a, int b) {
    return a &#x2F; b;
  }
}

In this example, the divide method checks if the denominator &#x60;b&#x60; is equal to zero, and if so, it throws an ArithmeticException when the divisor b is zero. The exception is then caught in the main method using a try-catch block. The catch block handles the exception by printing a user-friendly error message, that includes the exception message that was thrown in the divide method.
And here&#39;s an example of error handling in JavaScript:
function divide(a, b) {
  if (b &#x3D;&#x3D;&#x3D; 0) {
    throw new Error(&quot;Cannot divide by zero!&quot;);
  }
  return a &#x2F; b;
}

try {
  let result &#x3D; divide(10, 0);
  console.log(result);
} catch (error) {
  console.error(error.message);
}

In this example, the divide() function will throw a custom error when the divisor b is zero. The try-catch block will catch this error and print the error message.
I hope these examples give you a better understanding of the differences between Java and JavaScript&#39;s exception handling mechanisms.
Learning Resources
Learning a new programming language can be an exciting, but challenging experience. Here are a few resources that can help you on your journey to learning Java:
Official Java Documentation: The official Java documentation is a comprehensive resource that covers all aspects of the language, from the basics to advanced topics. It&#39;s a great place to start for anyone new to Java.
Online Courses: Online platforms such as Udemy, Coursera, and edX offer a wide range of Java courses, both paid and free, that can help you get up to speed quickly.
Books: There are many excellent books available on Java, ranging from beginner-friendly introductions to more advanced topics. Some popular options include &quot;Head First Java&quot; and &quot;Effective Java&quot;, Which can be found on Amazon.
Java Community: The Java community is large and vibrant, with many forums and resources available to help you learn and troubleshoot. Consider joining online communities, such as Stack Overflow, for additional support.
These resources can help you get started on your journey to learning Java, but the most important thing is to keep practicing and building your skills. Good luck!
Conclusion
To summarize, Java and JavaScript are both influential and commonly utilized programming languages, yet they possess significant distinctions in terms of programming methods, code style and formatting, exception handling and type systems. Java boasts a strong and standardized development environment that prioritizes code comprehensibility, upkeep and stability, while JavaScript affords a more adaptable and dynamic ecosystem that enables more imaginative and pioneering development. As a JavaScript developer moving to Java, it is crucial to comprehend these differences and familiarize oneself with the standard practices and conventions applied in Java development.
In conclusion, embrace the learning process of transitioning from JavaScript to Java and experience the benefits of Java&#39;s robust and standardized development environment. Start your journey today!&quot;*
#### [Dev Retro 2022: From Mechanical Design Engineer to Fullstack Developer: My Journey and Lessons Learned](https:&#x2F;&#x2F;blog.timdehof.dev&#x2F;dev-retro-2022-from-mechanical-design-engineer-to-fullstack-developer-my-journey-and-lessons-learned) 
*From the Halls of Mechanical Design to the Fields of Full-stack Development


via GIPHY
I spent many years in the halls of mechanical design, learning the ins and outs of 3D modeling, 3D printing, and product development. But when I decided to make a career change and become a full-stack developer, I faced a whole new set of challenges and opportunities.
Seeking the One True Coding Bootcamp
I set out on a quest to find the one true coding bootcamp that would guide me on my journey to becoming a full-stack developer. I spent many long hours scouring the land, researching different options and seeking the counsel of wise mentors. Finally, I found the path that seemed right for me and I enrolled in the program, determined to master the skills and technologies I needed to succeed. The road ahead was steep and challenging, but I was resolute in my purpose and I threw myself into the program with all my might. Through hard work and determination, I began to develop the skills I needed to embark on my new career.
Mastering the Technologies of Web Development


via GIPHY
During my time at the coding bootcamp, I set out on a quest to master the various languages and technologies involved in full-stack development. Through diligent study and practice, I was able to quickly get up to speed on HTML, CSS, and JavaScript, the essential front-end technologies that are used to build the user interface of a web application.
But my journey did not end there. I also delved into the deeper mysteries of server-side development, learning about powerful technologies such as Express.js and Node.js. These languages required a deeper understanding of concepts such as databases and APIs, but with the guidance of my instructors and the aid of my fellow travelers, I was able to master them as well.
Along the way, I encountered many useful tools and frameworks that helped me on my journey. One such tool was React.js, a powerful library for building user interfaces. With its help, I was able to create dynamic and interactive web applications that truly impressed my peers.
Overall, I feel that the coding bootcamp was a great adventure that helped me master the technologies and skills needed to be a successful full-stack developer. I am confident that the knowledge and experience I gained will serve me well as I continue my journey through the tech industry.
Project Work in the Coding Bootcamp


via GIPHY
During the coding bootcamp, I had the opportunity to undertake a great quest: the creation of a full-stack e-commerce website project, which we called Galactic Pawn. This project was a group capstone, designed to test our skills and simulate a remote team environment. We used the web development and full-stack technologies we had learned in the program to build the website, wielding powerful tools such as React, NodeJS, Express, and PostgreSQL. Later, I successfully deployed the website to Render.com and the database to Bit.io, using the magic of Prisma and JWT.
The website included a login and registration page, as well as a main store page that allowed users to create an account and add items to their cart. One of the challenges of the project was integrating all of the different routes and technologies to create a cohesive and functional website. However, with the help of our wise instructors and by working effectively as a team, we were able to overcome this challenge and complete the project to the satisfaction of all.
If you&#39;d like to see the results of our labors, you can check out the live demo here or view the Git repo here. This group capstone project was a great opportunity for us to apply the skills and knowledge we had gained during the coding bootcamp and work collaboratively with our fellow classmates. I am proud of what we were able to accomplish together and grateful for the experience.
The Search for the Full-Stack Developer Role


via GIPHY
Upon graduating from the coding bootcamp, I set out on a quest to find a full-stack developer role. I knew this would be no easy feat, as I was new to the field and would face many challenges along the way.
I began by updating my resume and LinkedIn profile, polishing them like a shining sword for the battles ahead. I also reached out to my connections in the tech industry, seeking any leads or guidance that might aid me on my journey.
I applied for a variety of roles, from entry-level positions to more experienced developer roles. The job search process can be a treacherous path, but I was determined to find the right opportunity.
One thing that helped me stand out to potential employers was my background as a mechanical design engineer. Many companies are seeking developers with a diverse skill set, and my experience in product development and 3D modeling was a unique selling point for me.
I also made sure to highlight the skills I learned at the coding bootcamp, including my proficiency in front-end and server-side technologies, as well as my ability to work effectively in a team. I included specific examples of projects I worked on and problems I solved during the program, which helped to demonstrate my abilities and potential value to a company.
Despite my efforts, I have yet to find a full-stack developer role. But I remain persistent and proactive in my search, continuing to network and build connections in the tech industry. I believe the right opportunity will come to me in due time. I encourage other aspiring full-stack developers to stay the course and make the most of any networking opportunities that come their way. The journey may be long and arduous, but the reward will be worth it.
Sharpening Valuable Soft Skills
As I journeyed from the halls of mechanical design to the fields of full-stack development, I sharpened a number of valuable soft skills that are essential for success in the tech industry. These include effective communication, collaboration, and problem-solving abilities. With these skills honed to a fine edge, combined with my expertise in 3D modeling and product development, I am confident that I will be a valuable asset to any team.


via GIPHY
Looking back on my journey, I have learned a few key lessons. First, it is important to be proactive and seek out opportunities to learn and grow, like a warrior seeking to hone their skills. Second, networking and building connections are essential, like forging alliances with powerful allies. And finally, it is important to stay positive and persistent, even when the job search is challenging, like a steadfast hero on a quest.
The Road Ahead
As we gaze into the horizon and plan our next journey, it is clear that transitioning from a mechanical design engineer to a full-stack developer is no simple task. However, with the right skills, connections, and knowledge of industry trends, we can conquer this challenge and reap the rewards of a successful career in the tech industry.


via GIPHY
Let us embrace the road ahead, stay vigilant and sharp, and never lose sight of our goals. For it is through hard work, determination, and the forging of new connections that we will find our path to victory in this brave new world of full-stack development.*
#### [The Power of a Growth Mindset in Software Development: How to Embrace Challenges and Advance Your Career](https:&#x2F;&#x2F;blog.timdehof.dev&#x2F;the-power-of-a-growth-mindset-in-software-development-how-to-embrace-challenges-and-advance-your-career) 
*In today&#39;s fast-paced world of technology, having a growth mindset is a crucial aspect of success in the field of software development. A growth mindset focuses on the belief that intelligence and abilities can be developed through effort and learning, allowing individuals to embrace challenges and continuously improve their skills. In this blog post, we will explore the benefits of having a growth mindset for learning and career advancement in software development, and provide tips for developing and maintaining this mindset.
What is a growth mindset?
A growth mindset is the belief that intelligence and abilities can be developed through effort and learning. This mindset focuses on growth and improvement, rather than viewing challenges and failures as setbacks. In contrast, a fixed mindset sees intelligence and abilities as fixed and unchangeable.

&quot;A growth mindset is needed for #4IR Shift the negative to positive 💡 #entrepreneur #DigitalTransformation #startup #innovation #fintech #insurtech #thinkbigsundaywithmarsha Cc @Clagett @SpirosMargaris @kimgarst @psb_dc @leimer @Paula_Piccard @&quot; by Paula Piccard is marked with CC0 1.0.
How a growth mindset can improve learning and career advancement in software development
Having a growth mindset is a powerful tool for learning and success in the field of software development. It allows individuals to embrace challenges and failures as opportunities for growth and learning, rather than viewing them as setbacks. This mindset also encourages seeking out new knowledge and skills in order to improve and advance in the field. Additionally, having a growth mindset fosters a collaborative and supportive learning environment within a team, allowing team members to support and encourage each other in their growth and success. Overall, a growth mindset is a crucial tool for success in the ever-changing world of software development.
Developing and maintaining a growth mindset
Developing and maintaining a growth mindset takes time and effort, but it is a crucial aspect of success in the field of software development. Here are some strategies for cultivating a growth mindset:
Practice self-reflection and self-assessment to identify areas for growth and improvement
Seek out feedback from others and use it to guide your learning and development
Take on challenges and new experiences, even if they may be difficult or uncomfortable
Surround yourself with supportive and growth-minded individuals who can inspire and motivate you

&quot;Design A Better Business Workshop @ Zoku Amsterdam&quot; by Sebastiaan ter Burg is licensed under CC BY 2.0.
Maintaining a growth mindset can also be challenging, especially when faced with setbacks and failures. Here are some tips for maintaining a growth mindset in the face of challenges:
Reframe failures as opportunities for growth and learning
Celebrate small victories and progress along the way
Keep a positive attitude and stay motivated by setting goals and tracking your progress
Seek support and guidance from others who can help you stay on track and maintain a growth mindset.
In conclusion, having a growth mindset is a crucial aspect of success in the field of software development. It allows individuals to embrace challenges and continuously improve their skills, leading to success and career advancement. By developing and maintaining a growth mindset, individuals can foster a collaborative and supportive learning environment and achieve their full potential in the field of software development.

&quot;Successful and happy business team&quot; by Rawpixel Ltd is licensed under CC BY 2.0.
To start cultivating a growth mindset and advance your career in software development, try implementing the strategies and tips outlined in this post. Surround yourself with supportive and growth-minded individuals, take on new challenges, and practice self-reflection and self-assessment. With a growth mindset, you can unlock your full potential and succeed in the exciting world of software development.*
#### [A Roadmap for Transferring Skills from Mechanical Design Engineering to Fullstack Development](https:&#x2F;&#x2F;blog.timdehof.dev&#x2F;a-roadmap-for-transferring-skills-from-mechanical-design-engineering-to-fullstack-development) 
*As a mechanical design engineer, you have developed a wealth of knowledge and expertise that can be applied to a career in fullstack development. By following this roadmap, you can successfully transfer your skills and achieve success in this exciting and rapidly-growing field.
Step 1: Analyze your existing skills and knowledge, and identify which ones are most relevant to fullstack development. Some transferable skills include:
Problem-solving and critical thinking
Technical skills, such as proficiency in CAD software
Attention to detail and accuracy
Ability to work independently and as part of a team
Strong communication and collaboration skills.
Step 2: Develop any additional knowledge or skills that may be required for fullstack development, such as programming languages or web development frameworks. There are many resources available to help you learn these skills, such as online courses, workshops, and conferences. Invest in your education and professional development to continue growing and excelling as a fullstack developer.
Step 3: Apply your skills to real-world projects. This may involve working on personal projects, participating in hackathons, or contributing to open-source projects. Some examples of real-world projects to showcase your skills include:
Building a personal website or blog
Developing a web application for a local business or organization
Contributing to an open-source project on GitHub
Step 4: Continuously learn and grow in your career as a fullstack developer. The field of fullstack development is constantly evolving, so it is important to stay up-to-date with the latest technologies and best practices.
By following this roadmap and transferring your skills from mechanical design engineering to fullstack development, you can achieve success and advance your career. Start your journey today and take the first step towards a rewarding career as a fullstack developer.*
#### [Becoming a Self-Learner: Tips and Strategies for Personal and Professional Growth](https:&#x2F;&#x2F;blog.timdehof.dev&#x2F;becoming-a-self-learner-tips-and-strategies-for-personal-and-professional-growth) 
*Are you looking to grow and develop your skills, but feeling stuck or unsure of how to make progress? One key to unlocking your potential as a learner is to make the choice to be a self-learner. Here are a few strategies to help you get started:
Set specific, challenging goals that push you to improve and provide a clear roadmap for your learning journey. For example, aim to improve by at least 1% each day and track your progress over time.
Identify when you are most productive and give yourself dedicated time to study during those times. For instance, if you find that you are most focused and energized in the morning, set aside a dedicated block of time for learning first thing each day.
Adopt a growth mindset and reframe obstacles as opportunities for growth and learning. Instead of seeing failures as setbacks, view them as valuable learning experiences that bring you closer to your goals.
Take advantage of available resources, such as online courses, books, podcasts, and mentors, to supplement your learning and gain new perspectives.
Practice self-reflection and regularly evaluate your progress to identify areas for improvement and adjust your approach as needed.
By implementing these strategies and making the choice to be a self-learner, you can unlock your potential and achieve your goals. So, what are you waiting for? Take the first step towards becoming a self-learner and start shifting your focus to long-term learning today. With the right mindset and approach, the sky&#39;s the limit for your personal and professional growth!*
<!--END_SECTION:feed-->

## :zap: Recent Activity

<!--START_SECTION:activity-->
1. 🎉 Merged PR [#2](https://github.com/timDeHof/timDeHof/pull/2) in [timDeHof/timDeHof](https://github.com/timDeHof/timDeHof)
2. ❌ Reopened PR [#2486](https://github.com/EddieHubCommunity/hacktoberfest-practice/pull/2486) in [EddieHubCommunity/hacktoberfest-practice](https://github.com/EddieHubCommunity/hacktoberfest-practice)
3. ❌ Closed PR [#2486](https://github.com/EddieHubCommunity/hacktoberfest-practice/pull/2486) in [EddieHubCommunity/hacktoberfest-practice](https://github.com/EddieHubCommunity/hacktoberfest-practice)
4. 💪 Opened PR [#2486](https://github.com/EddieHubCommunity/hacktoberfest-practice/pull/2486) in [EddieHubCommunity/hacktoberfest-practice](https://github.com/EddieHubCommunity/hacktoberfest-practice)
5. 🎉 Merged PR [#1](https://github.com/timDeHof/timDeHof/pull/1) in [timDeHof/timDeHof](https://github.com/timDeHof/timDeHof)
<!--END_SECTION:activity-->

***
## :book: Education:
![Zero to Mastery](https://img.shields.io/badge/zero_to_mastery-2B283A?style=for-the-badge&logo=zero_to_mastery&logoColor=white)
- [Complete Web Developer in 2023: Zero to Mastery](https://academy.zerotomastery.io/courses/697434/certificate)

![Fullstack Academy](https://img.shields.io/badge/fullstack_academy-2B283A?style=for-the-badge&logo=fullstack_academy&logoColor=white)
- [Fullstack Academy Web Development Coding Bootcamp](https:www.fullstackacademy.com)

![Scrimba](https://img.shields.io/badge/scrimba-2B283A?style=for-the-badge&logo=scrimba&logoColor=white)
- [The Frontend Developer Career Path](https://www.codecademy.com/learn/paths/front-end-engineer-career-path) (Completion: 43%)
- [Learn CSS Grid for free](https://scrimba.com/learn/cssgrid) (Completion: 25%)

![SoloLearn](https://img.shields.io/badge/sololearn-2B283A?style=for-the-badge&logo=sololearn&logoColor=white)
- [React & Redux](https://www.sololearn.com/certificates/CT-3DICCPQQ)

![Kaggle](https://img.shields.io/badge/kaggle-2B283A?style=for-the-badge&logo=kaggle&logoColor=white)
- [Python](https://www.kaggle.com/learn/certification/timdehof/python) 

![FreeCodeCamp](https://img.shields.io/badge/Freecodecamp-2B283A?style=for-the-badge&logo=freecodecamp&logoColor=white)
- [Responsive Web Design](https://www.freecodecamp.org/certification/tdehof/responsive-web-design)
### :hammer_and_wrench: Languages and Tools :
#### 📋 Languages:
[![My Skills](https://skillicons.dev/icons?i=react,js,html,css,md)](https://skillicons.dev)
#### 🗄️ Databases:
[![My Skills](https://skillicons.dev/icons?i=postgres,prisma)](https://skillicons.dev)
#### 📚 Frameworks:
[![My Skills](https://skillicons.dev/icons?i=nodejs,express)](https://skillicons.dev)
#### :hammer: Tools:
[![My Skills](https://skillicons.dev/icons?i=git,github,heroku,netlify,vscode,webpack)](https://skillicons.dev)
#### :art: Design:
[![My Skills](https://skillicons.dev/icons?i=figma)](https://skillicons.dev)

***

### :fire: My Stats :
![timDeHof's GitHub stats](https://github-readme-stats.vercel.app/api?username=timDeHof&theme=monokai&show_icons=true)
<!--
**timDeHof/timDeHof** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
