# Knowledge Base

I created this as a compilation of all the self-learning I'm doing in order to provide recruiters or other CS students with an overview of my areas of competence and also as a To-Do list that gives me an clear view of the concepts or skills I plan to learn in the near future.

Every item in the list links to the resources I used to understand it, and most of them also link to the notes and flashcards that I wrote for the item. If applicable, my implementations or related projects are linked too.

<h2>Philosophy</h2>

<details>
<summary></summary> <br>
I believe that in order to solve problems efficiently, precise and detailed knowledge of the techniques and technologies available for a given propblem space is required. In the case of computer science, it means knowing both the fundamentals of software building (SOLID Principles, datastructures and algorithms, how to do good testing, design patterns...) and having an in-depth knowledge of the nitty-gritty of the syntax and the frameworks to be used. <br>
This represents a lot of informations that needs not only to be acquired and understood, but retained over time in order to easily be able to apply them to concrete problems. This is why I dedicate time everyday to reading on and practising new skills, and also why I use modern tools (most notably <a href="https://medium.com/@gautier.blandin/remnote-takes-notes-and-remember-them-b2f386aa8f2c"> RemNote</a>) to keep remembering what I learn over time. <br>

</details>

<h2> How I learn in practice </h2>

<details>
 <summary></summary> <br>
I learn a lot doing practical projects, which can be work projects, school projects, or personal projects. When I solve a problem using a method that I find to be interesting, or that taught me some new syntax, I make a note about it. This is how I build my knowledge about <a href="https://www.remnote.com/a/latex/61f2966db459e30016442492">LaTeX</a> over time, or how I learn to use programming languages such as <a href="https://www.remnote.com/a/javascript/61f296c37613f00016bf958c">Javascript</a> or <a href="https://www.remnote.com/a/python-/61e68c024a52720016f38972">Python</a>. That approach has two benefits : 
<ul>
 <li> I only learn things that I actually use, because I learn them as I go</li>
 <li> I remember the skill when I need it again, so I don't have to relearn over and over again </li>
 </ul><br>

Although practical knowledge is both important and necessary (what good is knowledge if you can't apply it?), I do believe that theory also has its place, as in a lot of situations, what you can do in practice will be limited by your knowledge about what your possibilites are. For example, you could spend your whole life writing cumbersome for-loops in javascript when you could use simpler methods such as array.map, simply because you've never read about them. This is why I spend at least one hour everyday reading material on theoretical knowledge, on a variety of subjects, such as software building fundamentals, mathematics, frameworks documentation and concepts, etc. I take notes in the form of questions/answers that enter my knowledge base and let me remember the key ideas that I've read.  <br>

</details>

# Overview

### Computer Science

<details>
 <summary><a href="#programming_principles">Programming Principles</a></summary>

  <ul>
    <li><a href="#solid"> SOLID Principles</a></li>
    <li><a href="#dry"> DRY / AHA</a></li>
    <li><a href="#desgin_patterns"> Design Patterns</a></li>
  </ul>

</details>

<details>
 <summary><a href="#time_space_complexity">Time & Space Complexities</a></summary>
  
  <ul>
    <li><a href="#big_o"> Big O</a></li>
    <li><a href="#amortized_analysis"> Amortized cost</a></li>
  </ul>
  
</details>

<details>
 <summary><a href="#datastructures">Datastructures</a></summary>
  
  <ul>
    <li><a href="#arrays"> Arrays</a></li>
    <li><a href="#linked_lists"> Linked Lists</a></li>
    <li><a href="#stacks_and_queues"> Stacks & Queues</a></li>
    <li><a href="#hash_tables"> Hash Tables</a></li>
    <li><a href="#heaps_priority_queues"> Heaps & Priority Queue</a></li>
    <li><a href="#binary_trees"> Binary Trees</a></li>
  </ul>

</details>

<details>
 
 <summary><a href="#algorithms">Algorithms</a></summary>
  
  <ul>
    <li><a href="#binary_search">Binary Search </a></li>
    <li><a href="#knuth_shuffle">Knuth Shuffle </a></li>
    <li><a href="#selection_sort">Selection Sort </a></li>
    <li><a href="#insertion_sort">Insertion Sort </a></li>
    <li><a href="#merge_sort">Merge Sort </a></li>
    <li><a href="#quick_sort">Quick Sort </a></li>
  </ul>

 </details>

<details>
 <summary><a href="#graph_theory">Graph Theory</a></summary>
  
  <ul>
    <li><a href="graph_theory_introduction">General Concepts </a></li>
    <li><a href="graph_theory_common_problems">Common Problems</a></li>
    <li><a href="graph_theory_algorithms">Breadth-first search </a></li>
    <li><a href="graph_theory_algorithms">Depth-first search </a></li>
  </ul>
  
</details>

<!--
<details>
 <summary><a href="dynamic_programming">Dynamic programming</a></summary>
  
  <ul>
    <li><a href="">Optimal sub-structure </a></li>
    <li><a href="">Overlapping sub-problems </a></li>
  </ul>
  
</details>
-->

 <details>
 <summary><a href="#programming_techniques">Programming Techniques</a></summary>
  
  <ul>
    <li><a href="#memoization"> Memoization</a></li>
    <li><a href="#fluent_interface"> Fluent interfaces</a></li>
  </ul>
  
</details>

### Mathematics
  
  <details>
  <summary><a href="#probabilities_statistics"> Probabilities & Statistics </a></summary>

  <ul>
    <li><a href="#sample_space_probability"> Sample Space & Probability</a></li>
    <li><a href="#discrete_random_variables">Discrete Random Variables</a></li>
    <li><a href="#general_random_variables">General Random Variables</a></li>
  </ul>

  </details>
  
 ### Web Development 

<details>
 <summary><a href="front_end">Front-end development</a></summary>
  
  <ul>
    <li><a href="#css">CSS</a></li>
    <li><a href="#design">Design</a></li>
    <li><a href="#react">React</a></li>
    <li><a href="#next_js">Next</a></li>
  </ul>
  
</details>

<details>
 <summary><a href="back_end">Back-end development</a></summary>
  
  <ul>
    <li><a href="#nest">Nest</a></li>
    <li><a href="#type_orm">TypeORM</a></li>
    <li><a href="#express">Express</a></li>
  </ul>
  
</details>

<details>
 <summary><a href="node_js">NodeJs</a></summary>
  
  <ul>
    <li><a href="#npm_write_packages">How to write and publish NPM packages </a></li>
    <li><a href="#axios">Axios</a></li>
    <li><a href="#dotenv">Dotenv</a></li>
  </ul>
  
</details>

### Web Standards
  
  * HTTP
  * OAuth 2.0


<!--

### DevOps

  * CI/CD
  * Docker
  * Ansible

-->

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

### <span id="programming_principles"/>Programming Principles

<h5 id="solid"> SOLID Principles </h5>

- <a href="https://www.remnote.com/a/solid-design-principles/61e68e64849524001676e093"> Flashcards & Notes </a>
- [Single Responsibility Principle](https://en.wikipedia.org/wiki/Single-responsibility_principle)
- [Open-Closed Principle](https://en.wikipedia.org/wiki/Open%E2%80%93closed_principle)
- [Liskov Substitution Principle](https://en.wikipedia.org/wiki/Liskov_substitution_principle)
- [Interface Segregation Principle](https://en.wikipedia.org/wiki/Interface_segregation_principle)
- [Dependency Inversion Principle](https://en.wikipedia.org/wiki/Dependency_inversion_principle)

<h5 id="dry"> DRY / AHA </h5>

- [Don't Repeat Yourself, but Avoid Hasty Abstractions](https://en.wikipedia.org/wiki/Don%27t_repeat_yourself)

<h5 id="design_patterns"> Design Patterns </h5>

- [Original GoF book](https://en.wikipedia.org/wiki/Design_Patterns)
- [Modern approach : refactoring.guru](https://refactoring.guru/design-patterns)
- Flashcards  & Notes :
  - [Introduction & key concepts](https://www.remnote.com/a/introduction-key-concepts-and-definitions/61a5530bb61d3100160b9c78)
  - [Creational Patterns](https://www.remnote.com/a/creational-patterns/61e697d1178e620016e1d3bb)
  - [Structural Patterns](https://www.remnote.com/a/structural-patterns/61a5530bffeb1400164cb357)
  - [Behavioral Patterns](https://www.remnote.com/a/behavioral-patterns/61e6947f4a52720016f389f7)

<h3 id="time_space_complexity"> Times & Space Complexity </h3>

- [Flashcards & Notes](https://www.remnote.com/a/time-space-complexity/61e69f27849524001676e1de)
- <span id="big_o"/>[Big O](https://en.wikipedia.org/wiki/Big_O_notation)
- <span id="amortized_analysis"> Amortized Analysis :
  - [Coursera (free)](https://www.coursera.org/learn/data-structures/lecture/hzlEI/amortized-analysis-aggregate-method)
  - Wiki : https://en.wikipedia.org/wiki/Amortized_analysis
 
 <h3 id="datastructures"> Datastructures </h3>

 - [Flashcards & Notes](https://www.remnote.com/a/hash-tables/61f2a07753bfe900160ea37c)
 - <span id="arrays"/>[Arrays](https://www.remnote.com/a/arrays/61f2a077021aff0016fe3ce5)
   - [My implementation (C++ Dynamic Arrays)](https://github.com/GautierLearnsProgramming/Datastructures/tree/main/Vector)
   - [Coursera lecture](https://www.coursera.org/lecture/data-structures/arrays-OsBSF)
 - <span id="linked_lists">[Linked Lists](https://www.remnote.com/a/linked-lists/61f2a077021aff0016fe3ce8)
   - [My implementation (C++ Doubly Linked List)](https://github.com/GautierLearnsProgramming/Datastructures/tree/main/LinkedLists)
   - [Coursera lecture on singly linked lists](https://www.coursera.org/lecture/data-structures/singly-linked-lists-kHhgK)
   - [Coursera lecture on doubly linked lists](https://www.coursera.org/lecture/data-structures/doubly-linked-lists-jpGKD)
   - [Why you should avoid linked lists](https://www.youtube.com/watch?v=YQs6IC-vgmo)
 - <span id="stacks_and_queues"/>[Stacks & Queues](https://www.remnote.com/a/stacks-and-queues/61f2a077b459e30016442569)
   - [My implementation (C++ Static and Dynamic queue based on circular buffer)](https://github.com/GautierLearnsProgramming/Datastructures/tree/main/Queues)
   - [Coursera Lecture on Stacks](https://www.coursera.org/learn/data-structures/lecture/UdKzQ/stacks)
   - [Coursera Lecture on Queues](https://www.coursera.org/learn/data-structures/lecture/EShpq/queues)
   - [Circular Buffer on wikipedia](https://en.wikipedia.org/wiki/Circular_buffer)
 - <span id="hash_tables"/>[Hash Tables](https://www.remnote.com/a/hash-tables/61f2a07753bfe900160ea37c)
   - [My implementation (C++ Hashmap with string keys, polynomial rolling hash and linear probing)](https://github.com/GautierLearnsProgramming/Datastructures/tree/main/HashTables)
   - [Coursera Lecture on Hash Tables](https://www.coursera.org/learn/data-structures/lecture/5e8QH/hash-tables)
   - [Direct adressing method, coursera lecture](https://www.coursera.org/learn/data-structures/lecture/fYKm7/direct-addressing)
   - [Hash functions, coursera lecture](https://www.coursera.org/learn/data-structures/lecture/1EeyX/hash-functions)
   - [Chaining method, coursera lecture](https://www.coursera.org/learn/data-structures/lecture/2yY2h/chaining-scheme)
   - [Linear probing on wikipedia (preferred method)](https://en.wikipedia.org/wiki/Linear_probing)
 - <span id="heaps_priority_queues"/>[Heaps & Priority Queues](https://www.remnote.com/a/priority-queues-and-heaps/61f2a077b459e3001644256c)
   - [My implementation : Max heap & heap sort](https://github.com/GautierLearnsProgramming/Datastructures/tree/main/Heaps)
   - [Heap and Heap Sort from MIT Open Courseware](https://www.youtube.com/watch?v=B7hVxCmfPtM)
 - <span id="binary_trees"/>[Binary Search Trees](https://www.remnote.com/a/trees/61f2a077021aff0016fe3ce2)
   - [My implementation : Simple binary search tree (not AVL or red/black)](https://github.com/GautierLearnsProgramming/Datastructures/tree/main/BinaryTrees)
   - [Binary search trees from MIT Open Courseware](https://www.youtube.com/watch?v=76dhtgZt38A)
   - [AVL Trees from MIT Open Courseware](https://www.youtube.com/watch?v=U1JYwHcFfso)
 
 <h3 id="algorithms"> Algorithms </h3>
 
 - [Flashcards & Notes](https://www.remnote.com/a/algorithms/61f3e7a6e0a450001690eadb)
 - <span id="binary_search"/> [Binary Search](https://www.remnote.com/a/binary-search/61f3e7a603feef001634a45b)
   - [My implementation : Binary search on a sorted array, C++](https://github.com/GautierLearnsProgramming/Datastructures/tree/main/Algorithms)
   - [Binary search on wikipedia](https://github.com/GautierLearnsProgramming/Datastructures/tree/main/Algorithms)
 - <span id="knuth_shuffle"/> [Knuth Shuffle](https://www.remnote.com/a/shuffles/61f3e7a603feef001634a458)
   - [My implementation : Knuth Shuffle of a generic array, C++](https://github.com/GautierLearnsProgramming/Datastructures/tree/main/Algorithms)
   - [Shuffling algorithm by Sedgewick](https://www.coursera.org/learn/algorithms-part1/lecture/12vcF/shuffling)
 
 <h4 id="sorting_algorithms"> Sorting Algorithms </h4>
 
 - [Important characteristics](https://www.remnote.com/w/614f49b8425a7800161dc50b/Z7qZ8SqNassAAjr6g)
 - <span id="selection_sort"/> [Selection Sort](https://www.remnote.com/a/selection-sort/61f3e7b9e0a450001690eaea)
   - [My implementation : Selection sort of an array of integers, C++](https://github.com/GautierLearnsProgramming/Datastructures/tree/main/Algorithms)
   - [Selection sort by Sedgewick](https://www.coursera.org/learn/algorithms-part1/lecture/VE0sv/selection-sort)
 - <span id="insertion_sort"/> [Insertion Sort](https://www.remnote.com/a/insertion-sort/61f3e7b96fa8cd0016ee3ded)
   - [My implementation: Insertion sort of an array of integers, C++](https://github.com/GautierLearnsProgramming/Datastructures/tree/main/Algorithms)
   - [Insertion sort by Sedgewick](https://www.coursera.org/learn/algorithms-part1/lecture/1hYlN/insertion-sort)
 - <span id="merge_sort"/> [Merge Sort](https://www.remnote.com/a/merge-sort/61f3e7b9e1e55c00168bf04c)
   - [My implementation : Merge sort of an array of integers, C++](https://github.com/GautierLearnsProgramming/Datastructures/tree/main/Algorithms)
   - [Merge sort by Sedgewick](https://www.coursera.org/learn/algorithms-part1/lecture/ARWDq/mergesort)
 - <span id="quick_sort"/> [Quick Sort](https://www.remnote.com/a/quick-sort/61f3e7b96fa8cd0016ee3de7)
   - [My implementation : Quick sort of an array of integers, C++](https://github.com/GautierLearnsProgramming/Datastructures/tree/main/Algorithms)
   - [Quick sort by Sedgewick](https://www.coursera.org/learn/algorithms-part1/lecture/vjvnC/quicksort)
 
 <h3 id="graph_theory"> Graph Theory </h3>
 
 Unfortunately, the main resources that I used to learn this section is a <b> paid </b> one, so I cannot link free resources as I do in most other sections. It is an excellent [Udemy Course](https://www.udemy.com/course/graph-theory-algorithms/) by William Fiset, and I can only recommend it.
 
 - [Flashcards & Notes](https://www.remnote.com/a/graph-theory/61f3ea88e0a450001690eb2b)
 - <span id="graph_theory_introduction"/> [Introduction :](https://www.remnote.com/a/introduction/61f3ea886fa8cd0016ee3e12)
   - Graph definition
   - Graph representations
   - Types of graphs
 - <span id="graph_theory_common_problems"/> [Common problems :](https://www.remnote.com/a/common-problems-in-graph-theory/61f3ea88e0a450001690eb2e)
   - Shortest path problem
   - Connectivity
   - Negative Cycles
   - Strongly Connected Components
   - Traveling Salesman Problem
   - Briges and articulation points
   - Minimum spanning tree
   - Network max flow
 - <span id="graph_theory_algorithms"> [Algorithms :](https://www.remnote.com/a/algorithms/61f3ea8803feef001634a470)
   - Breadth-First Search
   - Depth-First Search
 
 ### <span id="programming_techniques"/>Programming Techniques

<h5 id="memoization"> Memoization </h4>

- [Flashcard](https://www.remnote.com/a/memoization/61e69bb6849524001676e1c9)
- [Wikipedia](https://en.wikipedia.org/wiki/Memoization)

<h5 id="fluent_interface"><a href="https://en.wikipedia.org/wiki/Fluent_interface"> Fluent Interface </a></h4>

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
 
 ## <span id="front_end"/>Front-End Development
  
 - <span id="css"/> CSS
   - [Flashcards & Notes](https://www.remnote.com/a/css/61f3f92c6fa8cd0016ee3f01)
   - [The Box Model](https://www.remnote.com/w/614f49b8425a7800161dc50b/Qrcquktpt9ocFkcMm)
   - [Flexbox](https://www.remnote.com/a/61f3f92c264dbc00162a434b)
     - [CSS Trick's excellent guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
   - [Text](https://www.remnote.com/w/614f49b8425a7800161dc50b/usp5qokX8sSaD83pB)
   - [Animations](https://www.remnote.com/a/animations/61f3f92ce0a450001690eda5)
   - [Transforms](https://www.remnote.com/w/614f49b8425a7800161dc50b/zomNM49iJgEwinD3D)
   - [Borders](https://www.remnote.com/w/614f49b8425a7800161dc50b/kC38g3veq5hYnyZCB)
   - [Selectors](https://www.remnote.com/w/614f49b8425a7800161dc50b/2tYrTenJw4vLDm5X8)
   - [Shapes](https://www.remnote.com/w/614f49b8425a7800161dc50b/G27DChupG8WhhgbZL)
   - [Shadows](https://www.remnote.com/w/614f49b8425a7800161dc50b/WB2aJqM2s7TPrKmph)
 - <span id="design"/>Design
   - Great (paid) [Udemy course](https://www.udemy.com/course/freelance-web-design-from-design-to-development-to-making-money) on design using Figma by Vako Svhili
   - [Flashcards & Notes about design guidelines](https://www.remnote.com/a/design/61f3f46e264dbc00162a42d7)
   - [My design exercises done throughout the course](https://github.com/GautierLearnsProgramming/WebDesign)
 - <span id="react"/>React
   - [Flashcards & Notes](https://www.remnote.com/w/614f49b8425a7800161dc50b/xGmEEdmEBh5Qb6pgh)
   - [React Documentation](https://reactjs.org/docs/getting-started.html)
   - [Context API Flashcards](https://www.remnote.com/a/context/61f3f552e1e55c00168bf12d)
   - [Hooks Flashcards](https://www.remnote.com/a/hooks/61f3f552e1e55c00168bf12c)
 - <span id="next_js"/>NextJs
   - [Flashcards & Notes](https://www.remnote.com/a/next-js/61f3f5c503feef001634a56a)
   - [Navigation](https://www.remnote.com/a/navigation/61f3f5c503feef001634a567)
   - Font import in a NextJs project
 - <span id="material_ui"/>Material UI
   - [Flashcards & Notes](https://www.remnote.com/w/614f49b8425a7800161dc50b/dHo5AosACz4d5Rfs9)
   - [Styling](https://www.remnote.com/w/614f49b8425a7800161dc50b/adKHw7Qz9EbuoZ2Sc)
   - [Spacing](https://www.remnote.com/w/614f49b8425a7800161dc50b/cXRfpRHLWYrYMG8Yn)
   - [Theming](https://www.remnote.com/w/614f49b8425a7800161dc50b/b53SwafaECP6K5mB5)
 
 ## <span id="back_end"/>Back-End Development
 
 - <span id = "nest"/> Nest
   - [Official documentation, excellent ressource for the framework and for understanding more about programming](https://docs.nestjs.com/)
   - [Flashcards & Notes](https://www.remnote.com/a/nestjs/61f422e5e0a450001690f2b1). They include :
     - CLI
     - Controllers
     - Providers
     - Modules
     - Middleware
     - Validation
     - TypeORM Integration
   
 - <span id = "type_orm"/> TypeORM
   - [Documentation](https://typeorm.io/)
   - [Flashcards & Notes](https://www.remnote.com/a/typeorm/61f42449e0a450001690f2c4). They include :
     - Configuration
     - Connection object
     - Repository object and usage
 
 - Express
   - [Documentation](https://expressjs.com/en/api.html)
   - [Flashcards & Notes](https://www.remnote.com/w/614f49b8425a7800161dc50b/exZnNhQea3RsNgMFT). They include :
     - The App object (get, post, use, listen...)
     - The Request object
     - The Response object
     - Middlewares

## <span id="node_js"/> NodeJs
 - <span id="npm_write_packages"/>[How to write and publish NPM packages (Flashcards & Notes)](https://www.remnote.com/a/writing-npm-packages-/61f4257fe0a450001690f306)
 - <span id="axios"/>Axios
   - [Documentation](https://axios-http.com/docs/intro)
   - [Flashcards & Notes](https://www.remnote.com/a/axios/61f4257f6fa8cd0016ee4170). They include :
     - Configuration of the Axios Instance
     - Request configuration
     - Response object
     - Interceptors configuration
 - <span id="dotenv">Dotenv
   - [Documentation](https://www.npmjs.com/package/dotenv)
   - [Flashcards & Notes (very short)](https://www.remnote.com/a/axios/61f4257f6fa8cd0016ee4170). They include :
     - Basic Usage
 
