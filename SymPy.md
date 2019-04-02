## Title

Please use a succinct title that describes your proposal. Do not include the words "GSoC", "2019", or your name in the proposal title on Google's website.

### The person
- Full name: Juan Sebastian Barbosa
- University: Universidad de los Andes, Colombia
- Email: juansebastian.coy@gmail.com
- GitHub: jsbarbosa

I am a last year physics and chemistry undergraduate student, with experience on C and Python, as open-source tools for the development of knowledge. Among my passions are: physical computing (code that physically interacts with surroundings e.g: microcontrollers, Raspberry), popular science in which I love to use computer simulations to show that there is plenty of phenomena that can be studied within a computer, software development to simplify everyday tasks and physics itself.

### The programmer

I have been programming for quite a while now. I first started with a Lego Mindstorm, then I moved to Microsoft Excel Macros (VB) at the end of my high school. Later, at college, I used Java during my first semester, and then I met Python throughout my second semester and it was love at first sight. At that very moment, I moved from Windows to Ubuntu and I have not stopped using it ever since; now it's been more than 4 years since then. Afterwards, during my 6th semester in college, I was introduced to C, and although it is not as easy to use or straight forward as Python, it's beauty is found in its power and speed. After that, I became Junior Teacher Assistant for the [Computational Methods class](https://github.com/ComputoCienciasUniandes/MetodosComputacionales) for two years. Computational Methods is a course where we study numerical methods to solve ODEs, PDEs, integrals, derivatives and how to find solutions to equation systems. Most (if not all) of my coding is freely available in [GitHub](http://www.github.com/jsbarbosa).

I think Python is the dream language, it is easy to use, and it is as readable as if it was pseudocode. Python is supported by a huge community -that I have found to be really friendly and ready to help-. Furthermore, it has literally hundred of thousands of modules and libraries that make it the perfect definition of a General Purpose Language. Python is as powerful for statistics as R, it only takes an `import pandas as pd`. With numerical calculations NumPy, and SciPy make it hard for MatLab to take any advantage. And off course symbolic calculations are not unique to Mathematica, thanks to the highly advanced SymPy module, from which many people around the world are thankful of. And best of all, Python does all of these for free, opening a universe of endless possibilities for which anyone, can code anywhere.

When it comes to scripting, my favorite IDE is Atom, as it is highly customizable, supports almost every programming language, and has a nice GUI (I have also used Spyder and Geany). However, for exploration and results presentation, Jupyter notebooks are the best.

I have used SymPy to find solution to equation systems, process mathematical expressions (e.g. integrate, gradients, simplify) and export results with `sympy.latex()`. SymPy has become one of my favorite tools, as it helped me on multiple classes, such as Solid State Physics, Quantum Mechanics and Classical Mechanics throughout my career. As a result of my Classical Mechanics and Computational Methods classes, I implemented a demonstration project, for which I used SymPy to obtain the equations of motion for a [double pendulum](https://github.com/ComputoCienciasUniandes/Demonstrations/tree/master/DoublePendulum) with Lagrangian formalism, which were then solved numerically and resulted in an animation of the position in time, which in turn was generated using the Matplotlibs animation module. Each step to obtain the equations of movement was detailed and explained in the code, but mathematical expressions were generated inline by SymPy. Also, analogous demonstrations were made for single springs pendulums, projectiles (with force drag) and a model of the solar system (ten bodies, with information from Horizons). Besides, a Nlog(N) algorithm (Barnes and Hut) for gravitational systems with its visualization module was written by me on 2017 by the name of [astrohut](https://jsbarbosa.github.io/astrohut/) in C, with Python binders for the heavy duty functions. Lastly, for PDEs, a module called [rippleTank](https://jsbarbosa.github.io/rippleTank/) was written in the same year in order to simplify the studies of wave interactions in ripple tanks.  

### You and your project

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
