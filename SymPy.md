## Title

Please use a succinct title that describes your proposal. Do not include the words "GSoC", "2019", or your name in the proposal title on Google's website.

### The person
- Full name: Juan Sebastian Barbosa
- University: Universidad de los Andes, Colombia
- Email: juansebastian.coy@gmail.com
- GitHub: jsbarbosa

I am a last year physics and chemistry undergraduate student, with experience on C and Python, as open-source tools for the development of knowledge. Among my passions are: physical computing (code that physically interacts with surroundings e.g: microcontrollers, Raspberry), popular science in which I love to use computer simulations to show that there is plenty of phenomena that can be studied within a computer, software development to simplify everyday tasks and physics itself.

### The programmer

I have been programming for quite a while now. I first started with a Lego Mindstorm, later I moved to Microsoft Excel Macros (VB) at the end of my high school. At college I used Java in my first semester, in second I met Python and it was love at first sight, I have not stopped using it ever since. At that very moment I moved from Windows to Ubuntu. At 6th semester I was introduced to C, and although is not as easy to use / straight forward as Python, its beauty is found in its power and speed. After that I became Junior Teacher Assistant for the [Computational Methods class](https://github.com/ComputoCienciasUniandes/MetodosComputacionales) for two straight years, a course where we study numerical methods to solve ODEs, PDEs, integrals, derivatives and to find the solutions to systems of equations. Most (if not all) of my coding is freely available in [GitHub](http://www.github.com/jsbarbosa).

I think Python is the dream language, it is easy to use, and is as readable as pseudocode. Python is supported by a huge community -that I have found to be really friendly and ready to help-, it has literally hundred of thousands of modules and libraries that make it the perfect definition of a General Purpose Language. Python is as powerful for statistics as R, it only takes a `import pandas as pd`, and with numerical calculations NumPy, and SciPy make it hard for MatLab to take any advantage. Off course symbolic calculations are not unique to Mathematica, thanks to the highly advanced SymPy module, for which many people around the world are thankful for. And best of all, Python does all of these for free, opening a universe of endless possibilities for which anyone, anywhere can code.

When it comes to scripting, my favorite IDE is Atom, as it is highly customizable, supports almost every programming language, and has a nice GUI (I have also used Spyder and Geany). For exploration and presentation of results, Jupyter notebooks are the best.

I have used SymPy to find solutions to systems of equations, to process mathematical expressions (e.g. integrate, gradients, simplify) and export the result with `sympy.latex()`. SymPy has helped me on multiple classes such as Solid State Physics, Quantum Mechanics and Classical Mechanics. As a result of my classical mechanics and Computational Methods classes and I implemented a demonstration project, in which I used SymPy to obtain the equations of movement for a [double pendulum](https://github.com/ComputoCienciasUniandes/Demonstrations/tree/master/DoublePendulum) (Lagrangian formalism), equations are then solved numerically, and an animation of the position in time is generated using Matplotlibs animation module. Each step to obtain the equations of movement is detailed and explained but mathematical expressions are generated inline by SymPy. Analogous demonstrations were made for single springs pendulums, projectiles and a model of the solar system (ten bodies, with information from Horizons). A $N log N$ algorithm (Barnes and Hut) for gravitational systems with its visualization module was written by me on 2017 by the name of [astrohut](https://jsbarbosa.github.io/astrohut/) in C with Python binders for the heavy duty functions. For ODEs a module called [rippleTank](https://jsbarbosa.github.io/rippleTank/) was written the same year with the objective of simplifying the studies of wave interactions in ripple tanks.  

You and your project

Answer the following questions in your proposal:

    What do you want to achieve?

    What excites you about this project? Why did you choose it?

    What qualifications do you have to implement your idea? For example, if you are implementing solvers for partial differential equations, what courses have you taken or books have you read on PDEs? Why are you suited to work on this project?

    What have other people done on this idea? Has it been implemented before? (hint: it probably has) Are there any papers or blog posts about it?

    How much time do you plan to invest in the project before, during, and after the Summer of Code? (we expect full time 40h/week during GSoC, but better make this explicit) If you plan to take any vacations over the summer, let us know about it here.

    Please provide a schedule of how this time will be spent on sub-tasks of the project over the period of the summer. While this is only preliminary, we will use it to help monitor your progress throughout the program. Also understand that during the project you will issue weekly progress reports against that plan on your blog.

    In planning your project, it is good to note where along the way you could formulate a pull request. These would be points where you can have a self contained and well documented and tested piece of functionality. Doing this at several points during the summer helps to keep branch merges reasonable and code reviews manageable. A big code dump at the end of the summer will likely be hard to review and merge before the project deadline.

    Please do not verbatim copy text from the ideas page, or from other people's discussions about your project, but rewrite it in your own words. If you include any significant text or code from another source in your application, it must be accompanied with a proper citation. All papers or references that you use or plan to use must also be cited. Put all this in a "References" section at the bottom of your application. Copying text without citation is plagiarism and will result in your application being rejected.

You do not need to format your application as a question/answer format for the above questions, but we expect to see all of the above questions answered in your application somewhere.
Patch requirement
