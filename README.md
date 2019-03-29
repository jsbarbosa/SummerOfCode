# SummerOfCode

## [CERN-HSF*](https://summerofcode.withgoogle.com/organizations/4639943769456640/)
In order to apply to CERN-HSF, please visit the following website:

http://hepsoftwarefoundation.org/activities/gsoc.html

There you will find a list of proposals for each project, their description and the contact information of their mentors. To see a list of all the project proposals sorted in alphabetical order, please visit:

http://hepsoftwarefoundation.org/gsoc/2019/summary.html

Once you have chosen one or more proposals that you like, please contact the corresponding mentors and they will guide you through the next steps.

Mentors will typically ask you to complete a technical test to evaluate if you have the skills required for the project. Please note that the vast majority of our GSoC projects do not require any physics knowledge; in case of doubt, ask the mentors.

If you do well in the tests, mentors will usually ask you to write a description for your project and help you with the submission.

## [OSGeo](https://summerofcode.withgoogle.com/organizations/6304079978954752/)
The Open Source Geospatial Foundation, OSGeo is a non-profit organization serving as an umbrella organization for the Open Source Geospatial community in general and several code projects in particular

## [Read the Docs*](https://summerofcode.withgoogle.com/organizations/6158414290354176/)
Documentation Simplified. Read the Docs simplifies software documentation by automating building, versioning, and hosting of your docs for you. Think of it as Continuous Documentation.

We are an OSS project written in Python & Django, and host documentation for over 100,000 open source projects.

## [Software and Computational Systems Lab at LMU Munich*](https://summerofcode.withgoogle.com/organizations/4780274102042624/)
Students wishing to participate in Summer of Code must realise that this is an important professional opportunity. You will be required to produce code for an award-winning tool chain or parts of its infra structure. Therefore, we seek students who are committed to helping our tools long-term and are willing to both do quality work, and be proactive in communication with their mentors.

You don't have to be a proven developer - in fact, this whole program is meant to facilitate joining our group and take a look at open source communities. However, experience in coding is welcome and should be mentioned in your proposal.

You should take a look at the tools that you plan to work on before the start date. The timeline from Google reserves a lot of time for bonding periods; use that time wisely. Good communication is important. The group members are available via mail (or in person, if needed). You should communicate with your mentor, and formally report progress and plans weekly.

### Recommended steps
- Join the mailing list of a project of your choice, introduce yourself, and meet your fellow developers
- Read Google's instructions for participating and the GSoC Student Manual
- Take a look at the list of ideas
- Come up with project that you're interested in
- Write a first draft proposal and get someone to review it
- Submit your proposal using Google's web interface ahead of the deadline
- Further instructions are avaliable on our website.

### Integrating SymPy into CPAchecker for Invariant Generation
### Checking Equivalence of Program Semantics Automatically


## [OpenCV](https://summerofcode.withgoogle.com/organizations/5654472617885696/)
OpenCV, the Open Source Computer Vision Library includes state of the art computer vision and deep learning algorithms (including running deep networks) and apps. It is professionally coded and optimized. It can be used in C++, Python, javascipt, Cuda, OpenCL and Matlab. It runs on: Android, iOS, Windows, Linux and MacOS and many embedded implementations such as Raspberry Pi.

- You must already know how to program fluently in C++ (or Python if applicable). See https://github.com/opencv/opencv/wiki/GSoC_2019#for-students-interested-in-applying for details.
- Ask to join the opencv-gsoc mailing list https://groups.google.com/forum/#!forum/opencv-gsoc-2019
- Discuss project ideas from https://github.com/opencv/opencv/wiki/GSoC_2019#opencv-project-ideas-list or your own ideas with OpenCV mentors on the list.
- Proposals must follow: https://google.github.io/gsocguides/mentor/defining-a-project-ideas-list
- Sign up with GSoC and with OpenCV
- When OpenCV is told how many slots we will get and you've signed up for a project with us, Then:

We will weigh the students and projects against the mentors we gather and the mentor's interests and choose which students/project to pursue.
- Accepted students will be posted on the GSoC site and we will notify the accepted students ourselves afterwards.
- Please only propose projects that you already know how to do.

## [LibreOffice](https://summerofcode.withgoogle.com/organizations/5557591040589824/)
First, please present yourself. Since we don't know you we want to know some bits like your name, education, email address and nickname on the #libreoffice-dev IRC channel at freenode.net. Please subscribe to the LibreOffice developer list and write an email to the list.

We will require students to complete one of the easy programming tasks on the Easy Hacks page (or part of one if that EasyHack is a selection of separate tasks), though the dead-line for this isn't hard but needs to be somewhere before the end of the selection process. This means that each student who wants to have chances to be picked for a LibreOffice project will need to build the whole application, fix a bug and submit the patch to the development mailing list.

Explain what you want to achieve. Provide detailed informations on the project you want to work on and the use cases. The more precise your description is, the more it will show us that you investigated the area and though about it properly before submitting. The best is to base your project on one of our Ideas that come complete with friendly mentors to help you. You may have some nice project ideas, but make sure that someone will be able to mentor your project and knows that part of the code well enough.

Problems that can not be resolved on our public developer mailing list or problems containing privacy relevant topics can also be sent to our mentoring@documentfoundation.org address.

## [aimacode*](https://summerofcode.withgoogle.com/organizations/5431334980288512/)
The aimacode project has applied for the Google Summer of Code. We're looking for a few student interns to help write code. We expect the following skills for all projects (individual project ideas list additional skills):
- Very strong coding ability. Give us a link to some projects you've done.
- Very clear coding, commenting, and documentation writing skills. Your code not only has to be correct, it also has to be easy top understand, and easy to see the connection between your code and the description of the algorithms in the textbook.
- Enthusiasm for helping other people by explaining things well. Show us some examples of your work in this area.
- Some experience, or familiarity, or willingness to learn about artificial intelligence and machine learning.

## [SymPy*](https://summerofcode.withgoogle.com/organizations/5755458304868352/)
SymPy is a Python library for symbolic mathematics. It aims to become a full-featured computer algebra system (CAS) while keeping the code as simple as possible in order to be comprehensible and easily extensible. SymPy is written entirely in Python.

### Classical Mechanics: Implement an O(N) Equation of Motions Method*
Roy Featherstone, Abhi Jain, and others developed recursive methods of forming the right hand side of the differential equations for complex multibody systems that have an evaluation time of O(N) instead of O(N^3). This project would be dedicated to implementing a symbolic O(N) method to compliment the LagrangesMethod and KanesMethod classes. This would give a significant speed boost in numerical evaluation for systems with bodies greater than 20 or so.

### Classical Mechanics: Efficient Equation of Motion Generation with Python**
Currently we have basic equation of motion generation with automated Kane's and Lagrange's methods. These methods work well but can take many minutes to complete for hard problems. The algorithms that derive these equations of motion can be improved in both speed of computation and the resulting simplification of the equations of motion. This project would involve cleaning up the code base, profiling to find the slow functions, and digging into the SymPy codebase for trigonometric simpification and other relevant function calls to speed up the EoM generation. Utilizatin of SymEngine as a backend can also be explored. These modification will help speed up both the entire SymPy codebase and the Mechanics package.

## [Python Software Foundation*](https://summerofcode.withgoogle.com/organizations/6017901476184064/)
An ideal application will contain 5 things:
### SciPy (fundamental routines for scientific computing)
- A descriptive title including the name of the sub-org you want to work with (if this is missing, your application may be rejected!)
- Information about you, including contact information.
- Link to a code contribution you have made to your organization. (Usually this is a link to a pull request.)
- Information about your proposed project. This should be fairly detailed and include a timeline.
- Information about other commitments that might affect your ability to work during the GSoC period. (exams, classes, holidays, other jobs, weddings, etc.) We can work around a lot of things, but it helps to know in advance.

Example: A longer version of this template can be found at https://github.com/python-gsoc/python-gsoc.github.io/blob/master/application2019.md

### Sub-org name: The thing I want to do this summer
#### About me
- Name (and nicknames like your github and irc usernames)
- University / program / year / expected graduation date
- Contact info (email, phone, etc.)
- Time zone
#### Code contribution
- Link to pull request goes here
#### Project information
- Sub-org name
- Project Abstract
- Detailed description
- Weekly timeline
#### Other commitments
List of any things that might affect your ability to work this summer

## [Open Astronomy]()
OpenAstronomy is a collaboration between open source astronomy and astrophysics projects that are used by researchers and engineers around the world to study our univershttps://summerofcode.withgoogle.com/organizations/4793907066437632/ either by analysing the data obtained from amazing instruments like the Hubble Space Telescope, the Square Kilometer Array or the Solar Dynamic Observatory, developing very sophisticated numerical models (eg. FLASH) or designing interplanetary trajectories for human-made spacecraft. The analysis of such data helps multiple types of research from being able to forecast a solar storms to detect planets in other stars, from understanding how galaxies are formed to explain the expansion and the origin of the universe.

Do you want to participate with OpenAstronomy as part of the GSoC? First, read carefully the student application guidelines and other guides available. Pay close attention to the requirements, as without them we won't consider your application. Learn from previous successful students (available in the sub-orgs wikis), and create your own with enough time to get feedback before the deadline.

- Name:
- Organisation:
## Details
### Personal Information
- Time zone
- Realtime chat handle@protocol:
- github id:
- Blog:
- RSS feed:
- Link(s) to sample code as pull requests:
### Education
Tell us about your background

### Interest in Open Astronomy
Why do you want to work with us?

### Application
#### Title
#### Summary
Explain why this project is attractive to you and why you think you can do it.
#### Description/timeline
Break your project in blocks, what do you expect you will do each week?

#### Schedule availability
Tell us about your plans for holidays during the time of the programme.
