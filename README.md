# Knowledge Base

### Introduction

I created this as a compilation of all the self-learning I'm doing in order to provide recruiters or other CS students with an overview of my areas of competence and also as a To-Do list that gives me an clear view of the concepts or skills I plan to learn in the near future.

Every item in the list links to the resources I used to understand it, and most of them also link to the notes and flashcards that I wrote for the item. If applicable, my implementations or related projects are linked too. ~items~ styled with strikethrough are items that I do not know yet but plan to learn. 

### Philosophy

I believe that in order to solve problems efficiently, precise and detailed knowledge of the techniques and technologies available for that propblem space is required. In the case of computer science, it means knowing both the fundamentals of software building (SOLID Principles, datastructures and algorithms, how to do good testing, design patterns...) and having an in-depth knowledge of the nitty-gritty of the syntax and the frameworks we use. <br>
This represents a lot of knowledge that needs not only to be acquired and understood, but retained over time in order to easily be able to apply it to concrete problems. This is why I dedicate time everyday to reading and practising new skills, and also why I use modern tools (most notably [RemNote](https://medium.com/@gautier.blandin/remnote-takes-notes-and-remember-them-b2f386aa8f2c)) to keep remembering what I learn over time. <br>

### How I learn in practice

I learn a lot doing practical projects, which can be work projects, school projects, and personal projects. When I solve a problem using a method that I find to be interesting, or that taught me some new syntax, I make a note about it. This is how I build my knowledge about [LaTeX](https://www.remnote.com/a/latex/61f2966db459e30016442492) over time, or how I learn to use programming languages such as [Javascript](https://www.remnote.com/a/javascript/61f296c37613f00016bf958c) or [Python](https://www.remnote.com/a/python-/61e68c024a52720016f38972). That approach has two benefits : 
 - I only learn things that I actually use, because I learn them when I need them
 - I remember the skill when I need it again, so I don't have to relearn over and over again <br>

Although practical knowledge is both important and necessary (what good is knowledge if you can't apply it?), I do believe that theory also has its place, as in a lot of situations, what you can do in practice will be limited by your knowledge about what your possibilites are. For example, you could spend your whole life writing cumbersome for-loops in javascript when you could use simple methods such as array.map, simply because you've never read about them. This is why I spend at least one hour everyday on theorical knowledge, on a variety of subjects, such as software building fundamentals, project managements methods, mathematics, frameworks documentation and concepts, etc. I take notes in the form of questions/answers that enter my knowledge base and let me remember the key ideas from what I've read.  <br>

The below knowledge base is a compilation of both practical skills and theoretical ideas and concepts that I've learned over time.

# Overview

### Computer Science

<details>
  <summary>Programming Principles</summary>

  <ul>
    <li><a href="#solid"> SOLID Principles</a></li>
    <li><a href="#dry"> DRY / AHA</a></li>
    <li><a href="#desgin_patterns"> Design Patterns</a></li>
    <li><a href="#twelve_factors"> Twelve Factor App</a></li>
  </ul>

</details>

<details>
  <summary>Programming Techniques</summary>
  
  <ul>
    <li><a href="#memoization"> Memoization</a></li>
    <li><a href="#fluent_interface"> Fluent interfaces</a></li>
  </ul>

</details>

<details>
  <summary>Time & Space Complexities</summary>
  
  <ul>
    <li><a href="#big_o"> Big O</a></li>
    <li><a href="#amortized_analysis"> Amortized cost</a></li>
  </ul>
  
</details>

<details>
  <summary>Datastructures</summary>
  
  <ul>
    <li><a href""> Arrays</a></li>
    <li><a href""> Linked Lists</a></li>
    <li><a href""> Stacks and Queues</a></li>
    <li><a href""> Binary Trees</a></li>
    <li><a href""> Hash Tables</a></li>
    <li><a href""> Heaps</a></li>
  </ul>

</details>

<details>
  <summary>Algorithms</summary>
  
  <ul>
    <li><a href="">Binary Search </a></li>
    <li><a href="">Knuth Shuffle </a></li>
    <li><a href="">Selection Sort </a></li>
    <li><a href="">Insertion Sort </a></li>
    <li><a href="">Merge Sort </a></li>
    <li><a href="">Quick Sort </a></li>
  </ul>
  
</details>

<details>
  <summary>Graph Theory</summary>
  
  <ul>
    <li><a href="">General Concepts </a></li>
    <li><a href="">Breadth-first search </a></li>
    <li><a href="">Depth-first search </a></li>
  </ul>
  
</details>

<details>
  <summary>Dynamic programming</summary>
  
  <ul>
    <li><a href="">Optimal sub-structure </a></li>
    <li><a href="">Overlapping sub-problems </a></li>
  </ul>
  
</details>

### Mathematics
  
  <details>
  <summary><a href = "#probabilities_statistics"> Probabilities & Statistics </a></summary>

  <ul>
    <li><a href="#sample_space_probability"> Sample Space & Probability</a></li>
    <li><a href="#discrete_random_variables">Discrete Random Variables</a></li>
    <li><a href="#general_random_variables">General Random Variables</a></li>
  </ul>

</details>

  * ~Real analysis~
  * ~Linear Algebra~
  * ~Analytic Geometry~

### Web Standards
  
  * HTTP
  * OAuth 2.0
 
### Front-end development
  
  * Design principles
  * HTML
  * CSS
  * React
  * Next

### Back-end development
  
  * Express
  * Nest
  * TypeORM

### DevOps

  * CI/CD
  * Docker
  * Ansible

### Programming languages
  
<details>
  <summary>Javascript</summary>
  
  * Arrays
  * Strings
  * Objects
  * LocalStorage
  * Optional Chaining
  * Classes
  
</details>

<details>
  <summary>Typescript</summary>
  
  * Type annotations
  * Interfaces inheritance
  
</details>

<details>
  <summary>Python</summary>
  
  * Iterables
  * Generator expressions
  * Lists
  * Strings
  * Type hinting
  * Classes
  
</details>

### Markup Languages

  * YAML
  * JSON
  * LaTeX
  * PlantUML

--- 

# Details

## Computer Science

<h4 id="solid"> SOLID Principles </h4>

- <a href="https://www.remnote.com/a/solid-design-principles/61e68e64849524001676e093"> Flashcards & Notes </a>
- [Single Responsibility Principle](https://en.wikipedia.org/wiki/Single-responsibility_principle)
- [Open-Closed Principle](https://en.wikipedia.org/wiki/Open%E2%80%93closed_principle)
- [Liskov Substitution Principle](https://en.wikipedia.org/wiki/Liskov_substitution_principle)
- [Interface Segregation Principle](https://en.wikipedia.org/wiki/Interface_segregation_principle)
- [Dependency Inversion Principle](https://en.wikipedia.org/wiki/Dependency_inversion_principle)

<h4 id="dry"> DRY / AHA </h4>

- [Don't Repeat Yourself, but Avoid Hasty Abstractions](https://en.wikipedia.org/wiki/Don%27t_repeat_yourself)

<h4 id="design_patterns"> Design Patterns </h4>

- [Original GoF book](https://en.wikipedia.org/wiki/Design_Patterns)
- [Modern approach : refactoring.guru](https://refactoring.guru/design-patterns)
- Flashcards  & Notes :
  - [Introduction & key concepts](https://www.remnote.com/a/introduction-key-concepts-and-definitions/61a5530bb61d3100160b9c78)
  - [Creational Patterns](https://www.remnote.com/a/creational-patterns/61e697d1178e620016e1d3bb)
  - [Structural Patterns](https://www.remnote.com/a/structural-patterns/61a5530bffeb1400164cb357)
  - [Behavioral Patterns](https://www.remnote.com/a/behavioral-patterns/61e6947f4a52720016f389f7)

<h4 id="twelve_factors"> <a href="https://12factor.net/"> Twelve-Factor App </a></h4>

<h4 id="memoization"> Memoization </h4>

- [Flashcard](https://www.remnote.com/a/memoization/61e69bb6849524001676e1c9)
- [Wikipedia](https://en.wikipedia.org/wiki/Memoization)

<h4 id="fluent_interface"><a href="https://en.wikipedia.org/wiki/Fluent_interface"> Fluent Interface </a></h4>

<h4 id="time_space_complexity"> Times & Space Complexity </h4>

- [Flashcards & Notes](https://www.remnote.com/a/time-space-complexity/61e69f27849524001676e1de)
- <span id="big_o"/>[Big O](https://en.wikipedia.org/wiki/Big_O_notation)
- <span id="amortized_analysis"> Amortized Analysis :
  - [Coursera (free)](https://www.coursera.org/learn/data-structures/lecture/hzlEI/amortized-analysis-aggregate-method)
  - Wiki : https://en.wikipedia.org/wiki/Amortized_analysis

## Mathematics

<h4 id="probabilities_statistics"> Probabilities & Statistics </h4>

The only resource used for this section is the excellent book <b>Introduction to Probability</b> by D. Bertsekas and K. Tsitsiklis which is available <a href = "https://www.amazon.com/Introduction-Probability-2nd-Dimitri-Bertsekas/dp/188652923X">here</a>. Because of that, only my notes and flashcards are going to be linked.

- <span id = sample_space_probability></span>[Sample Space and Probability](https://www.remnote.com/a/sample-space-and-probability/61eac608388024001602b7c2)
  - [Sets](https://www.remnote.com/a/sets/61e80f38268d0a0035d34b18)
  - [Probabilitic Model](https://www.remnote.com/a/probabilistic-model/61e6f07461d80e00160246b6)
  - [Conditional Probabilities](https://www.remnote.com/a/conditional-probabilities/61e806aef72a3c00160c2521)
  - [Bernoulli trials](https://www.remnote.com/a/bernoulli-trials-/61eac608fe181600161c93e3)
  - [Counting](https://www.remnote.com/a/counting/61eac608fe181600161c93e0)
- <span id = discrete_random_variables></span>[Discrete Random Variables](https://www.remnote.com/a/discrete-random-variables/61eac6ffc9c6ed00168fb9ee)
  - [Basic Concepts](https://www.remnote.com/a/basic-concepts/61eac6ff5e4cec001681a8db)
  - [Common Discrete Random Variables](https://www.remnote.com/a/common-discrete-random-variables/61eac6ff5e4cec001681a8d8)
  - [Expectation, Mean and Variance](https://www.remnote.com/a/expectation-mean-and-variance/61eac6ff388024001602b7d0)
  - [Functions of Random Variables](https://www.remnote.com/a/functions-of-random-variables/61eac6fff52a450016cc4e58)
  - [Joint PMFs](https://www.remnote.com/a/joint-pmfs/61ed2f64d4562d0016d72545)
  - [Conditional PMFs](https://www.remnote.com/a/conditional-pmfs/61ed2f64d4562d0016d72542)
- <span id = general_random_variables></span>[General Random Variables](https://www.remnote.com/a/general-random-variables/61edcdab424b8d0016622134)
  - [Continuous Random Variables](https://www.remnote.com/a/continuous-random-variables-pdfs/61edcf8733d01f00161d6b87)
  - [Expectation and Variance](https://www.remnote.com/a/expectation-and-variance/61edcf8733d01f00161d6b88)
  - [Common Continuous Random Variables](https://www.remnote.com/a/common-continuous-random-variables/61edcf8716a9290016b4cc0e)
  - [Normal Random Variable](https://www.remnote.com/a/normal-random-variable/61edcf86424b8d001662214d)
  - [Cumulative Distribution Functions](https://www.remnote.com/a/cumulative-distribution-functions/61edcf8616a9290016b4cc0b)
