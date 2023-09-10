# <div align="center">**T3A1 - Workbook**</div>

#### Luke Wheldale

</br>
</br>
</br>

## <div align="center">**Q1 - Provide an overview and description of a standard source control process for a large project**</div>

Source control, is a component of software development, particularly for large projects. It is the practice of managing and tracking changes to code. It plays a crucial role in overseeing modifications to the project's source code, documentation, and digital resources. Its main purpose is to facilitate seamless collaboration among multiple team members while upholding the integrity of the codebase and preserving a comprehensive history of changes [1]. Source code allows you to create a copy of a repository which you can then use to work on code independently from the stable version of the codebase [1].
Below is a description of the process of using source control for a large project.

1. **Version Control System selection:**
   Firstly, one must choose a suitable version control system to use for their project.
   Options include Git, Mercurial, and CVS, among many others.
   The preferred option for most modern projects is Git.
   This is due to Git's widespread adoption, fast performance, cross-platform functionality and robust nature [2].

2. **Repository Setup:** Next, a respository must be created. A repository is a centralised digital storage for users to create and manage changes to a project's source code. The repository stores assets and the project's source code.
   The repository is often hosted on platforms such as GitHub, Bitbucket, GitLab or may be self-hosted [3].

3. **Branching Strategy:** A branching strategy is a method utilised by software development teams when they create, combine, and introduce code while using a version control system. Essentially, it consists of a set of guidelines that developers adhere to, defining their interactions with a shared code repository [4].
   To effectively stick to a project's requirements, a suitable branching strategy must be chosen. The strategy should include the following elements:

-   A main branch, storing code that is production-ready.
-   Feature branches, dedicated to implementing new features or modifications.
-   Release branches, designated for the preparation and stabilisation of upcoming releases.\*
-   Specialized branches for quickly addressing critical production issues via hotfixes [4].

5. **Code Review:**
   When it comes to large projects. Code reviews are important.
   Code reviews typically take place before code is merged to the main branch.
   The review involves approving or declining code, depending if it adheres to code quality and standards.

6. **Continuous Integration:** Continuous integration (CI) is a fundamental practice in software development. It involves developers frequently integrating their code changes into a central repository. Following this integration, automated processes like builds and tests are triggered. CI primarily focuses on the build and integration phases of the software release process. It involves both an automation aspect, which includes tools like CI or build services, and a cultural aspect, which emphasises the importance of regular integration [5].
   The primary goal of CI is to swiftly detect and resolve bugs, enhance the overall quality of software, and shorten the duration required for validating and launching new software updates [5].

</br>

## <div align="center">**Q2 - What are the most important aspects of quality software?**</div>

Quality software is important for ensuring applications run reliably and meet expectations of the user. Six important aspects of quality software include Reliablity, Functionality, Usability, Maintainability, Efficiency, and Security.

**Reliability** - Software reliability is the likelihood of a computer program operating without failures within a specific timeframe and under defined conditions. It represents a user-orientated aspect of software quality, focusing on the program's performance rather than its design, making it a dynamic metric rather than a static one. It assesses how frequently defects lead to issues, making it crucial for software managers, engineers, and product managers dealing with software-integrated products, as well as end-users. Reliability denotes the software's capacity to consistently execute its functions without glitches or crashes, therefore providing confidence that it will perform correctly over an extended duration [6].

For examaple, In the case of an e-commerce website, it should consistently and without interruption handle order processing, secure payment transactions, and maintain system stability, even during periods of high user traffic.

**Functionality** - Functionality, within the realm of software quality, includes all the required and defined capabilities of a system. Superior quality is attained in this situation when the executed functionality aligns precisely with the specifications.
Functionality includes the capacity to execute the tasks it was intended for, ensuring that all features and functions operate accurately and in accordance with expectations [7].
For example, in the case of word processing software, it should effectively manage activities such as text formatting, spell checking, and document saving.

**Usability** - Usability refers to how easy and pleasant it is for people to use things like websites, software, gadgets, or apps. It's about making sure the software works well, are efficient, and satifies users.
Usability focuses on making it simple for users to use the software. Things like easy-to-use menus, clear instructions, and logical layouts make software more usable.
For example, a mobile app should have a clear and easy-to-use design with straightforward buttons and menus, so users can easily do what they want without getting confused [8].

**Maintainability** - Maintainability involves how simple it is to fix, enhance, and understand software code. It comes into effect once the software has been deployed, as part of the ongoing software development cycle.

To ensure maintainability, developers continuously update the software to accommodate new customer needs and resolve issues experienced by users. This encompasses tasks like fixing errors, enhancing existing functions, and adjusting the code to prevent future problems. The software's long-term viability relies on a developer's capacity to sustain these updates.

Maintainability demonstrates how effortless it is to make updates, changes, or fixes to the software. Well-organised code, clear documentation, and adherence to coding rules all contribute to maintainability.

For example, in an open-source project, having comprehensive documentation and adhering to coding guidelines is essential, as it simplifies the process for new contributors to understand and contribute to the codebase [9].

**Efficiency** - Efficiency in software refers to how quickly it can complete tasks while using as little system resources as possible. Efficient software makes effective use of the available computer resources.
For example, a video editing program should be able to export videos quickly without putting excessive strain on the computer's CPU or memory.

Efficiency testing measures the number of test cases executed within a specific time frame, usually in hours. It assesses how efficiently an application performs a particular function by considering the amount of code and testing resources required [10].

**Security** - Secure software development is the method through which developers create and test code with protection against both internal and external risks. It involves recognising potential vulnerabilities in software and understanding how threats can exploit them. The most effective software security is achieved when it is carefully planned and consistently managed throughout the entire software development life cycle (SDLC), especially in applications that handle sensitive data or perform critical functions.

Security is crucial for protecting software and its data from unauthorised access, vulnerabilities, and cyber threats. Software should incorporate best security practices to protect confidential information.

For example, an online banking application should utilise encryption to protect user data and should have built-in methods to prevent unauthorised access to user accounts [11].

</br>

## <div align="center">**Q3 - Outline a standard high level structure for a MERN stack application and explain the components**</div>

High level structure for a MERN stack includes several components.

1.**Frontend(React.js)** - React is the The highest layer of the MERN stack. React is a declarative JavaScript framework designed for crafting dynamic client-side applications within HTML. React enables developers to construct interfaces using straightforward components, link them to data on the backend server, and finally render them as HTML.

The frontend relies on React.js, which is organised into components to enhance code structure and promote reusability. Furthermore, React facilitates client-side routing by integrating with libraries like React Router to enable navigation within the application.

React excels in managing stateful, data-driven interfaces with minimal code and complexity, offering a comprehensive range of features that one would expect from a modern web framework. This includes robust support for tasks such as form handling, error management, event handling, and list management [12,13].

2.**Backend(Node.js and Express.js)** - One level deeper in the stack, we have the Express.js framework operating within a Node.js server environment. Express.js is described as a "swift, flexible, and minimalistic web framework for Node.js". Express.js includes strong mechanisms for URL routing, which involves matching incoming URLs with server functions, as well as for managing HTTP requests and responses.

To establish a connection between the React.js frontend, whether through XML HTTP Requests (XHRs) or GET and POST requests, you can link up with Express.js functions that drive your application's functionality. These functions, in turn, use MongoDB's Node.js drivers, utilising either callbacks or promises, to access and modify data within the MongoDB database [12,14].

-   The server aspect is handled by Node.js, serving as the runtime for the server-side operations.
-   API Routes are employed to outline specific routes and controllers responsible for processing HTTP requests and delivering data to the frontend, constituting the core of the application's business logic.
-   Functions are implemented to execute various tasks such as authentication, validation, and error handling, enhancing the application's robustness.
-   For seamless database integration, a library like Mongoose is used to establish a connection with MongoDB, thereby enabling efficient interaction with the database
    [12,14].

**Database(MongoDB)** - MongoDB serves as a NoSQL database aimed for the storage of organised data within collections. The design of the database schema should align closely with the specific data requirements of the application.
If your application involves the storage of any form of data, such as user profiles, content, comments, uploads, events, and more, it's important to employ a database that aligns seamlessly with the ease of use provided by React, Express, and Node.js.
MongoDB excels at this. JSON documents originating from your React.js frontend can be transmitted to the Express.js server, where they undergo processing and are subsequently stored directly within MongoDB for subsequent retrieval [12,15].

</br>

## <div align="center">**Q4 - A team is about to engage in a project, developing a website for a small business. What knowledge and skills would they need in order to develop the project?**</div>

The knowledge and skills required to effectively develop a web project in a team include Web development skills, design skills, and team collaboration, among other skills.

**Web Development Skills** - The team needs to have a thorough understanding and skillset in web development in particularly Front end, back-end, database, version controll and web security.

**Design skills** - User Experience (UX) is concerned with creating an emotional response from users by combining a website's ease of use with the integration of interactive and dynamic elements, ultimately creating a pleasant browsing experience.
UX Design involves crafting the website's visual components, layout, and overall user journey, utilising tools like Adobe XD, Sketch, Figma, or Adobe Photoshop.
Responsive Design ensures that the website functions effectively and appears appealing on various devices and screen dimensions, including smartphones, tablets, and desktop computers.
Usability Testing entails the process of gathering user feedback through testing, allowing for improvements based on user behavior and preferences [16].

**Team Collaboration** - Collaboration offers numerous advantages in web design and development. Here are some of the benefits of working together:

1. Enhanced Problem-Solving: When a team of experts with diverse skill sets collaborates, they can swiftly and efficiently identify and resolve issues. Collaboration allows for the consideration of multiple viewpoints, resulting in superior problem-solving.

2. Improved Communication: Collaboration nurtures communication among team members. As each member shares their ideas and expertise, the team can collectively formulate a unified vision for the website.

3. Elevated Work Quality: Through teamwork, a group can produce work of higher quality compared to an individual working in isolation. Each team member brings their unique strengths to the project, resulting in a visually appealing, functional, and user-friendly website.

4. Accelerated Project Delivery: Collaboration can expedite the development process. When a team collaborates, they can break down the project into smaller tasks and work on them simultaneously, leading to a quicker project delivery.

In summary, effective teamwork, communication, and collaborative skills are indispensable for the successful execution of a project [17].

</br>

## <div align="center">**Q5 - With reference to one of your own projects, discuss what knowledge or skills were required to complete your project, and to overcome challenges**</div>

In reference to my Rock, Paper Scissors, terminal project I made in term 2, the knowledge and skills required for me to complete this project included Python programming, randomisation, input handling, conditional statements, file handling (CSV), external libraries, error handling, testing and debugging, project management, and documentation.

1. **Python Programming** - Proficiency in Python is essential to write the code for the game. You need to understand Python syntax, data structures, and control flow.

2. **Randomisation** - Knowledge of Python's 'random' module is necessary for generating random choices for the computer player.

3. **Input Handling** - Skills in handling user input is crucial for getting the player's choice and ensuring that the input is valid. For example, The use of a 'try...except' block for error handling.

4. **Conditional Statements** - Understanding conditional statements ('if', 'elif', 'else') is important for determining the game's outcome based on player and computer choices.

5. **File Handling (CSV)** - Knowledge of file operations in Python, such as opening, reading, and writing to CSV files, is needed to store and retrieve game scores.

6. **External Libraries** - Familiarity with external libraries like 'colored' and 'art' for text formatting and styling, as well as 'emoji' for adding emojis to the output, enhances the game's user experience.

7. **Error Handling** - Implementing error handling to address potential issues, like file-related errors, enhances the robustness of the program.

8. **Testing and Debugging** - Skills in testing and debugging are vital to ensure that the game functions correctly and that any issues are resolved effectively.

9. **Project Management** - Managing the project as a whole required skills in project planning, task allocation, and version control (Git).

10. **Documentation** - Writing clear and concise comments within the code helps future developers understand the logic and purpose of each section.

To overcome challenges, project management skills, problem-solving abilities, and a willingness to research and learn new concepts or libraries as needed are valuable. Furthermore, seeking help from online communities or forums such as stack overflow when encountering specific coding challenges can be beneficial.

</br>

## <div align="center">**Q6 - With reference to one of your own projects, evaluate how effective your knowledge and skills were for this project, and suggest changes or improvements for future projects of a similar nature**</div>

1. **Python Programming Skills**

    - **Effectiveness** My proficiency in Python allowed me to write clean and functional code for the game.

    - **Improvement** Continually expanding my knowledge of Python and staying updated with the latest language features and best practices can help me write more efficient and maintainable code in the future.

    ```python
    player_choice = input(
        f"\n{fg('yellow')}Choose 🪨  rock, 📄 paper, or ✂️ scissors - or type 'end' to quit: \n\n").lower()
    if player_choice == "end":
        print(emoji.emojize(
            f'\n{fg(5)}Goodbye, thank you for playing! 😊'))
        exit()
    elif player_choice not in ['rock', 'paper', 'scissors']:
        raise ValueError(f'{fg(28)} {player_choice} is not a valid choice, please choose again.')
    ```

2. **Randomisation**

    - **Effectiveness** I successfully used the `random` module to generate computer choices randomly.

    - **Improvement** I should consider customizing the randomisation logic to make the game more challenging. For example, I can adjust the probability of the computer choosing certain options. Here's an example of customizing the computer choice:

    ```python
    def get_computer_choice():
        try:
            computer_choices = ['rock', 'paper', 'scissors', 'scissors', 'scissors']
            computer_choice = random.choice(computer_choices)
            return computer_choice
        except IndexError:
            print('Element not present in list, or list is empty.')
            return None
        except Exception as e:
            print(f'An error occurred: {e}')
            return None
    ```

3. **Input Handling**

    - **Effectiveness** My input handling with error checking worked well.

    - **Improvement** I should enhance user input validation with additional error messages or allow flexible input formats. For instance, I can accept single-letter inputs for choices ('r' for 'rock'). Here's an example of flexible input handling:

    ```python
    while True:
        player_choice = input(
            f"\n{fg('yellow')}Choose 🪨  rock, 📄 paper, or ✂️ scissors - or type 'end' to quit: \n\n").lower()
        if player_choice == "end":
            print(emoji.emojize)(
                f'\n{fg(5)}Goodbye, thank you for playing! 😊')
            exit()
        elif player_choice not in ['rock', 'paper', 'scissors', 'r', 'p', 's']:
            print(f'{fg(28)} Invalid choice, please choose again.')
    ```

4. **Conditional Statements**

    - **Effectiveness** My conditional statements correctly determined game outcomes.

    - **Improvement** I should streamline the conditional logic or make it more scalable for future game expansions (e.g., adding more choices). I can use a dictionary to map player and computer choices to outcomes, making the code more concise and maintainable.

Here's an example of using a dictionary to map outcomes:

```python
outcomes = {
    ('rock', 'scissors'): 'player',
    ('paper', 'rock'): 'player',
    ('scissors', 'paper'): 'player',
    ('scissors', 'rock'): 'computer',
    ('rock', 'paper'): 'computer',
    ('paper', 'scissors'): 'computer',
}

def play_round(player_choice, computer_choice):
    if player_choice == computer_choice:
        return 'draw'
    else:
        return outcomes.get((player_choice, computer_choice), 'computer')
```

By implementing these improvements, I can further enhance my coding skills and create a more robust and flexible Rock, Paper, Scissors game.

</br>

## <div align="center">**Q7 - Explain control flow, using an example from the JavaScript programming language**</div>

Control flow refers to the sequence in which instructions or statements are executed within a program. It provides the capability to manage your code, enabling you to make choices, repeat actions, and navigate to various segments of the code based on specific conditions. The concept of control flow is fundamental when it comes to creating programs that are both adaptable and capable of responding dynamically [18].

Code usually runs in a linear path from the first line to the last line, unless there are structures, such as conditionals and loops, which are commonly encountered and serve to alter the course of control flow.

For example, we can use conditional structures like '"if, else" statements to make decisions in our code. We can execute different blocks of code depending on whether certain conditons are true or false.

```let age = 30;
if (age < 18) {
    console.log("You are too young to enter.");
} else if (age >= 18) {
    console.log("you may enter.");
}
```

In this code, the control flow is determined by the value of the `age` variable.

1. `let age = 30;`: This line declares a variable named `age` and assigns it a value of 30.

2. The first `if` statement checks if the `age` is less than 18: `if (age < 18)`. If this condition is true, it means the person is younger than 18, and the code inside the first block is executed:

    ```javascript
    console.log("You are too young to enter.");
    ```

    However, in this case, the condition (`age < 18`) is not true because the age is 30.

3. The `else if` statement checks if the `age` is greater than or equal to 18: `else if (age >= 18)`. If the previous condition (age < 18) is not true, this condition is checked. Since the age is 30, this condition is true, and the code inside the second block is executed:

    ```javascript
    console.log("You may enter.");
    ```

    This message indicates that the person is old enough to enter.

So, in terms of control flow:

-   If the `age` is less than 18, it prints "You are too young to enter."
-   If the `age` is 18 or older, it prints "You may enter."

The `age` variable is only checked against two conditions, and the flow of control is determined by these conditions.

</br>

<div style="page-break-after: always; visibility: hidden">
\pagebreak
</div>

# <div align="center">**References**</div>

[1] [https://aws.amazon.com/devops/source-control](https://aws.amazon.com/devops/source-control/)

[2] [https://www.softwaretestinghelp.com/version-control-software/](https://www.softwaretestinghelp.com/version-control-software/)

[3] [https://aws.amazon.com/what-is/repo/](https://aws.amazon.com/what-is/repo/#:~:text=A%20repository%2C%20or%20repo%2C%20is,of%20documents%20when%20developing%20software.)

[4] [https://www.abtasty.com/blog/git-branching-strategies/](https://www.abtasty.com/blog/git-branching-strategies/#:~:text=A%20branching%20strategy%2C%20therefore%2C%20is,interact%20with%20a%20shared%20codebase.)

[5] [https://aws.amazon.com/devops/continuous-integration/](https://aws.amazon.com/devops/continuous-integration/#:~:text=Continuous%20integration%20refers%20to%20the,for%20a%20release%20to%20production.)

[6] [https://www.sciencedirect.com/science/article/abs/pii/](https://www.sciencedirect.com/science/article/abs/pii/S0065245808602995#:~:text=Software%20reliability%20is%20the%20probability,is%20dynamic%20rather%20than%20static.)

[7] [https://www.caktusgroup.com/blog/2018/03/14/what-software-quality-assurance/](https://www.caktusgroup.com/blog/2018/03/14/what-software-quality-assurance/#:~:text=assessed%20for%20each.-,Functionality,as%20described%20in%20the%20specifications.)

[8] [https://www.usability.gov/what-and-why/usability-evaluation.](https://www.usability.gov/what-and-why/usability-evaluation.html#:~:text=Usability%20refers%20to%20the%20quality,overall%20satisfaction%20of%20the%20user.)

[9] [https://www.sealights.io/software-quality/software-maintainability-what-it-means-to-build-maintainable-software/](https://www.sealights.io/software-quality/software-maintainability-what-it-means-to-build-maintainable-software/#:~:text=Maintainability%20refers%20to%20the%20ease,customer%20has%20received%20the%20product.)

[10] [https://www.softwaretestinghelp.com/efficiency-testing/](https://www.softwaretestinghelp.com/efficiency-testing/)

[11] [https://www.parkside-interactive.com/software-security/](https://www.parkside-interactive.com/software-security/#:~:text=What%20is%20secure%20software%20development%3F,and%20how%20threats%20are%20exploited.)

[12] [https://www.mongodb.com/mern-stack](https://www.mongodb.com/mern-stack)

[13] [https://www.w3schools.com/REACT/DEFAULT.ASP](https://www.w3schools.com/REACT/DEFAULT.ASP)

[14] [https://expressjs.com/en/5x/api.html](https://expressjs.com/en/5x/api.html)

[15] [https://www.techtarget.com/searchdatamanagement/definition/MongoDB](https://www.techtarget.com/searchdatamanagement/definition/MongoDB)

[16] [https://webflow.com/blog/web-designer-skills?](https://webflow.com/blog/web-designer-skills?utm_source=google&utm_medium=search&utm_campaign=SS-GoogleSearch-Nonbrand-DynamicSearchAds-Core&utm_term=aud-936979375321:dsa-45211625058___491754501325__&gclid=CjwKCAjwr_CnBhA0EiwAci5siupegDc0579nqKO-ndQOsAqm1EMLRNKykQveF2nhVx2-VCtDdjvEIBoC6zYQAvD_BwE)

[17] [https://www.linkedin.com/pulse/role-teamwork-collaboration-web-design-development/](https://www.linkedin.com/pulse/role-teamwork-collaboration-web-design-development-onviqa/)

[18] [https://developer.mozilla.org/en-US/docs/Glossary/Control_flow](https://developer.mozilla.org/en-US/docs/Glossary/Control_flow)
