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

```javascript
let age = 30;
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

## <div align="center">**Q8 - Explain type coercion, using examples from the JavaScript programming language**</div>

Type coercion involves the automatic or implicit conversion of values between different data types. This conversion occurs when various operators are applied to values, such as converting from numbers to strings, strings to numbers, or booleans to numbers. JavaScript is recognised for its relaxed or implicit data typing, which implies that it will try to execute operations even when the data types being operated upon are different. This can occasionally result in code behaving unexpectedly or not as intended [19].
The below code shows an example with loose equality and with strict equality.

**Loose Equality ('==') Comparison**

```javascript
let num = 18;
let str = "18";

if (num == str) {
	console.log("Loosely Equal");
} else {
	console.log("Not Loosely Equal");
}
```

In this code, type coercion occurs due to the loose equality operator (`==`). JavaScript converts the number `18` to a string to match the data type of `str`. Both values are now strings, and they are considered equal, resulting in "Loosely Equal" being printed.

**Strict Equality ('===') Comparison**

```javascript
let num = 18;
let str = "18";

if (num === str) {
	console.log("Strictly Equal");
} else {
	console.log("Not Strictly Equal");
}
```

In this example, the strict equality operator (`===`) is used, so there is no type coercion. JavaScript checks both the value and data type. Since `num` is a number and `str` is a string with different data types, the condition evaluates to false, and "Not Strictly Equal" is printed.

**Arithmetic Operation with Type Coercion**

```javascript
let num = 7;
let str = "15";

let result = num + str;

console.log(result);
// Output: "715"
```

In this code, type coercion occurs during the addition operation (`+`). JavaScript converts the number `7` into a string to perform string concatenation with `str`. The result is the string "715" because both operands are treated as strings.

**Boolean Type Coercion**

```javascript
let string = "Hello world";

if (string) {
	console.log("String is truthy");
} else {
	console.log("String is falsy");
}
```

In this example, type coercion happens when evaluating the `string` variable in a boolean context. Any non-empty string is considered truthy in JavaScript, so type coercion occurs, treating the string as a boolean value. "String is truthy" is printed because `string` is non-empty and therefore considered truthy.

</br>

## <div align="center">**Q9 - Explain data types, using examples from the JavaScript programming language**</div>

In programming, data types refer to the sort of information that a variable is capable of storing or representing. Each data type has distinct attributes and functions connected to it. In JavaScript, there are 8 data types [20]:

1. String
2. Number
3. BigInt
4. Boolean
5. Undefined
6. Null
7. Symbol
8. Object

9. **String**:
   Strings are sequences of characters enclosed in either single or double quotes.

    ```javascript
    let single = "Luke";
    let double = "Hello, world!";
    ```

10. **Number**:
    Numbers represent numeric values, which can be integers or floating-point numbers.

    ```javascript
    let integerNum = 30; // Integer
    let floatingNum = 19.99; // Floating-point number
    ```

11. **BigInt**:
    BigInt is used to represent large integers beyond the range of regular numbers.

    ```javascript
    let bigInt = 34857348349683482632393435729742432n;
    ```

12. **Boolean**:
    Booleans have only two possible values, `true` or `false`.

    ```javascript
    let isTrue = true;
    let isNotTrue = false;
    ```

13. **Undefined**:
    Variables declared but not assigned a value are `undefined`.

    ```javascript
    let name;
    ```

14. **Null**:
    `null` represents the intentional absence of any value.

    ```javascript
    let nullValue = null;
    ```

15. **Symbol**:
    Symbols are unique and immutable values.

    ```javascript
    const symbolDataType = Symbol("description");
    ```

16. **Object**:
    Objects are collections of key-value pairs.

    ```javascript
    let person = {
    	firstName: "John",
    	lastName: "Doe",
    	age: 30,
    };
    ```

 </br>

## <div align="center">**Q10 - Explain how arrays can be manipulated in JavaScript, using examples from the JavaScript programming language**</div>

Arrays in JavaScript can be modified through various operations referred to as methods. These methods provide the means to perform actions such as adding, removing, modifying, and performing various other operations on arrays [21].

**Adding Elements to an Array ('push')**:

```javascript
let colours = ["red", "blue", "green"];
colours.push("yellow"); // Add 'yellow' to the end of the array
// colours is now ['red', 'blue', 'green', 'yellow']
```

The `push` method adds an element, "yellow," to the end of the `colours` array, expanding its length.

**Removing Elements from an Array ('pop' and 'shift')**:

```javascript
let fruits = ["apple", "banana", "mango"];
fruits.pop(); // Remove the last element
// fruits is now ['apple', 'banana']

let numbers = [1, 2, 3, 4, 5];
numbers.shift(); // Remove the first element
// numbers is now [2, 3, 4, 5]
```

-   The `pop` method removes the last element from the `fruits` array, reducing its length.
-   The `shift` method removes the first element from the `numbers` array, shifting the remaining elements.

**Modifying Elements in an Array ('[]')**:

```javascript
let animals = ["lion", "tiger", "bear"];
animals[1] = "cheetah"; // Modify the second element
// animals is now ['lion', 'cheetah', 'bear']
```

square brackets `[]` are used to directly modify the second element of the `animals` array from "tiger" to "cheetah."

**Adding Elements to the Beginning of an Array ('unshift')**:

```javascript
let fruits = ["apple", "banana", "pear"];
fruits.unshift("mango"); // Add 'mango' to the beginning of the array
// fruits is now ['mango', 'apple', 'banana', 'pear']
```

The `unshift` method adds "mango" to the beginning of the `fruits` array, shifting existing elements to higher indices.

**Concatenating Arrays ('concat')**:

```javascript
let fruits1 = ["apple", "banana"];
let fruits2 = ["cherry", "pear"];
let combinedFruits = fruits1.concat(fruits2); // Concatenate arrays
// combinedFruits is ['apple', 'banana', 'cherry', 'pear']
```

The `concat` method combines `fruits1` and `fruits2` arrays into a new array, `combinedFruits`, containing all elements.

**Splicing an Array ('splice')**:

```javascript
let colours = ["red", "blue", "green", "yellow"];

// Insert 'purple' at index 2 and remove 2 elements
colours.splice(2, 2, "purple");

// colours is now: ['red', 'blue', 'purple', 'yellow']
```

The `splice` method is used to insert "purple" at index 2 and remove 2 elements from the `colours` array.

**Slicing an Array ('slice')**:

```javascript
let fruits = ["apple", "banana", "cherry", "date"];
let slicedFruits = fruits.slice(1, 3); // Slice from index 1 to 2
// slicedFruits is ['banana', 'cherry']
```

The `slice` method extracts a portion of the `fruits` array from index 1 to 2 and stores it in `slicedFruits`.

**Iterating Over an Array ('forEach')**:

```javascript
let vegetables = ["carrot", "broccoli", "spinach"];
vegetables.forEach(function (veg) {
	console.log(veg);
});
// Output: carrot, broccoli, spinach
```

The `forEach` method iterates over each element in the `vegetables` array and executes a provided function, printing each vegetable to the console.

  </br>

## <div align="center">**Q11 - Explain how objects can be manipulated in JavaScript, using examples from the JavaScript programming languagee**</div>

JavaScript is built around a straightforward object-oriented model. An object in JavaScript consists of properties, where each property pairs a name (or key) with a value. When a property's value is a function, it is referred to as a method.
JavaScript regards objects as a core data structure enabling the grouping of data and operations. The manipulation of objects includes a range of actions, such as their creation, retrieval, modification, and removal of properties and methods [22].

Certainly, here are revised examples with different objects and properties:

1. **Creating Objects:**

    You can create objects using object literals, constructor functions, or the `class` syntax .

    ```javascript
    // Using object literal
    const car = {
    	make: "Toyota",
    	model: "Camry",
    	year: 2023,
    };

    // Using constructor function
    function Car(make, model, year) {
    	this.make = make;
    	this.model = model;
    	this.year = year;
    }
    const car1 = new Car("Ford", "Focus", 2022);

    // Using class (ES6)
    class Vehicle {
    	constructor(make, model, year) {
    		this.make = make;
    		this.model = model;
    		this.year = year;
    	}
    }
    const car2 = new Vehicle("Honda", "Civic", 2021);
    ```

2. **Accessing Properties:**

    You can access object properties using dot notation or bracket notation.

    ```javascript
    console.log(car.make); // Toyota
    console.log(car["model"]); // Camry
    ```

3. **Modifying Properties:**

    You can change the values of object properties after object creation.

    ```javascript
    car.year = 2024;
    car["model"] = "Corolla";
    ```

4. **Adding Properties:**

    You can add new properties to an object at any time.

    ```javascript
    car.color = "Blue";
    ```

5. **Deleting Properties:**

    You can remove properties from an object using the `delete` keyword.

    ```javascript
    delete car.year;
    ```

6. **Methods:**

    Objects can contain methods, which are functions defined as object properties.

    ```javascript
    const calculator = {
    	multiply: function (x, y) {
    		return x * y;
    	},
    	divide: function (x, y) {
    		return x / y;
    	},
    };

    console.log(calculator.multiply(5, 3)); // 15
    ```

7. **Object Iteration:**

    You can loop through an object's properties using `for in` or `Object.keys()`, `Object.values()`, and `Object.entries()`.

    ```javascript
    for (const key in car) {
    	console.log(key, car[key]);
    }

    const keys = Object.keys(car);
    const values = Object.values(car);
    const entries = Object.entries(car);
    ```

8. **Object Cloning:**

    You can clone an object using various methods like the spread operator or `Object.assign()`.

    ```javascript
    const clonedCar = { ...car };
    const clonedCar2 = Object.assign({}, car);
    ```

9. **Object Prototypes (Inheritance):**

    JavaScript objects are often linked to a prototype object, allowing for inheritance of properties and methods.

    ```javascript
    function Animal(name) {
    	this.name = name;
    }

    Animal.prototype.speak = function () {
    	console.log(`${this.name} makes a sound.`);
    };

    const dog = new Animal("Rex");
    dog.speak(); // Rex makes a sound.
    ```

</br>

## <div align="center">**Q12 - Explain how JSON can be manipulated in JavaScript, using examples from the JavaScript programming language**</div>

JavaScript Object Notation (JSON), is a standardized text-based structure for presenting organised data, drawing from JavaScript's object syntax. Its primary application lies in data transfer within web applications, such as conveying information from the server to the client for web page display and vice versa [23].

1. **Parsing JSON:**

    JSON strings can be transformed into a JavaScript object using the `JSON.parse()` method:

    ```javascript
    const jsonData = '{"product": "Laptop", "price": 1000}';
    const laptop = JSON.parse(jsonData);

    console.log(laptop.product); // Laptop
    console.log(laptop.price); // 1000
    ```

2. **Stringifying JSON:**

    To convert a JavaScript object into a JSON string, the `JSON.stringify()` method is used:

    ```javascript
    const smartphone = {
    	brand: "Samsung",
    	model: "Galaxy S21",
    	price: 800,
    };
    const jsonString = JSON.stringify(smartphone);

    console.log(jsonString); // '{"brand":"Samsung","model":"Galaxy S21","price":800}'
    ```

3. **Modifying JSON Data:**

    You can manipulate the properties of a JavaScript object like any other object and then convert it back to JSON when required:

    ```javascript
    const jsonData = '{"name": "Ella", "age": 28}';
    const person = JSON.parse(jsonData);

    person.age = 29; // Update the age property
    person.city = "San Francisco"; // Add a new property

    const updatedJsonData = JSON.stringify(person);

    console.log(updatedJsonData); // '{"name":"Ella","age":29,"city":"San Francisco"}'
    ```

4. **Nested JSON:**

    JSON can represent nested data structures. You can access nested properties using dot notation:

    ```javascript
    const jsonData =
    	'{"employee": {"name": "Alex", "department": {"name": "HR"}}}';
    const data = JSON.parse(jsonData);

    console.log(data.employee.name); // Alex
    console.log(data.employee.department.name); // HR
    ```

5. **Working with Arrays in JSON:**

    JSON can represent arrays of data. Manipulate JSON arrays in JavaScript similar to regular arrays:

    ```javascript
    const jsonArray = '[{"name": "Lisa"}, {"name": "Michael"}]';
    const employees = JSON.parse(jsonArray);

    employees.push({ name: "Olivia" }); // Add an object to the array
    employees[0].age = 30; // Modify an object in the array

    const updatedJsonArray = JSON.stringify(employees);

    console.log(updatedJsonArray); // '[{"name":"Lisa","age":30},{"name":"Michael"},{"name":"Olivia"}]'
    ```

6. **Error Handling:**

    When parsing JSON, handle errors using a `try...catch` block othereise invalid JSON can trigger exceptions:

    ```javascript
    const invalidJson = '{"name": "Incomplete}';

    try {
    	const data = JSON.parse(invalidJson);
    	console.log(data); // This won't be reached due to the error
    } catch (error) {
    	console.error("Invalid JSON:", error.message);
    }
    ```

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

[19] [https://www.geeksforgeeks.org/what-is-type-coercion-in-javascript/](https://www.geeksforgeeks.org/what-is-type-coercion-in-javascript/)

[20] [https://www.w3schools.com/js/js_datatypes.asp](https://www.w3schools.com/js/js_datatypes.asp)

[21] [https://www.freecodecamp.org/news/manipulating-arrays-in-javascript/](https://www.freecodecamp.org/news/manipulating-arrays-in-javascript/)

[22] [https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Working_with_objects](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Working_with_objects)

[23] [https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/JSON](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/JSON)
