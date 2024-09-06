# Introduction 

This repo contains the textbook PDF files and sources for a book and a set of lecture slides on business analytics.

**Download the [book](busi4720.book.pdf).**

**Download the [slides archive](busi4720.slides.tar.gz).**

The material was developed for the Business 4720 (Business Analytics) course in the undergraduate [Bachelor of Commerce (BComm)](https://www.mun.ca/business/undergraduate/undergraduate-programs/) degree at [Memorial University of Newfoundland](https://www.mun.ca/). The course is a practical introduction to the very broad area of business analytics, data science, big data analytics, machine learning and related disciplines. It is based on experiential learning and students are required to use a number of software packages for course assignments.

### License 

The material is available under a [CC-BY-NC 4.0 license](https://creativecommons.org/licenses/by-nc/4.0/), except where sources are used under license, with permission, or under fair dealing, as indicated.

### Feedback is Welcome

Please drop me a quick note by email to [jevermann@mun.ca](mailto:jevermann@mun.ca) if:
* You have adopted this book for a course
* You found an error or mistake
* You found the book helpful for your personal study
* You have suggestions for improvements

### Required Software

The examples and exercises in the book are mainly based on R and Python, but use a number of specific packages, as well as other software applications. See the [software requirements page](software.md) for details. 

# Why write a textbook?

I chose to develop my own textbook for this course as I could not find a single textbook that covers the set of materials required. Business 4720 is a core, required course for the Bachelor of Commerce program at Memorial University of Newfoundland, Canada. As students receive only a single course in business analytics, and this course is in the fourth and final year of the program, the material coverage is intentionally broad, and covers aspects that may be outside some narrower conceptions of analytics. Additionally, students taking the course generally have little to no exposure to computer applications or statistical software, necessitating a rather comprehensive approach that not only introduces computer and programming basics, such as data and data types that students may encounter in business analytics, but also covers introduction to R and Python as well as a brief coverage of relational and graph databases, that are typically not considered part of business analytics. On the other hand, this course also contains advanced topics, such as interpretable machine learning, analytics at industrial scale, reinforcement and MLOps, that are not usually found in a business analytics course. However, these topics are gaining importance and it is essential that students have at least some exposure to them. In summary, the book was written because no other single book offers the necessary broad perspective. 

The book is written from an applied perspective. I believe that students, even business students, should not only be able to talk about analytics, but must also be able to do analytics. This means that, together with the concepts, every chapter also contains R or Python code showing how the concepts can be applied. Looking at this from another perspective, I believe students must not rely solely on software tools and statistical libraries, but it is crucial that they understand, at least in principle and at an intuitive level, how these tools work. This is necessary to allow an informed use of tools, to be able to select the appropriate tool for a given situation, and to be aware of the shortcomings, drawbacks, boundary conditions, and other limitations of tools. In short, formulas in this book are to explain what happens ''behind the scenes'' of the code, and code is in this book to show how formulas can be applied; both are necessary.

# Why these tools?

The focus on R and Python, over commercially available tools, is due to multiple reasons. First, the use of open-source software makes the material more easily accessible to students, independent of the availability of campus-wide licenses, or the use of limited ''evaluation'' licenses for some commercial tools. A second reason is the cross-platform nature of these software tools. Computing hardware in practice, and in the classroom, is a heterogeneous mix of different chip sets (Intel, Apple/ARM) and different operating systems (Windows, MacOS, Linux, etc.) so that is essential to work with software tools that are available and interoperable across these hardware and operating system platforms. A third reason is that R and Python are widely used in production environments. They tend to be more flexible than commercial offerings, and are also at the forefront of new developments in the area of business analytics. New methods and techniques are typically implemented directly by their inventor in open-source libraries and packages for R or Python, before they mature and are included in commercial offerings. The focus on command line tools is to avoid the complexities of graphical user interfaces that tend to change more rapidly than application programming interfaces (APIs), it is focus on the essentials and not be distracted by graphical environments. Scripting with command line tools generally also leads to better replicability of analyses and easier integration into production environments. For example, while it is all well and good to explore customer purchasing predictions on a small data set using the desktop edition of SPSS (a commercial, graphical, statistics software application), implementing real-time dynamic pricing in the global web-based ordering system will require the model to be implemented and integrated with very different tools.

# Instructors: How to use this book?

For instructors, the book is written for a 24 class semester of 75 minutes each (the chapter on visualization should be covered in two classes), with two classes dedicated to mid-term exams. If time is short, some of the later, more advanced chapters could be omitted, for example, the two chapters on reinforcement learning, and/or the chapter on MLOps. A slide set for 22 classes is available, as is a question bank of multiple-choice questions for each chapter, e.g. for quizzes (upon request). Each chapter also contains a set of short hands-on exercises that can be used during class to keep students engaged or can form the basis for a computer lab setting. Also available to instructors is a set of example exam questions (upon request). Given the extensive set of online materials on programming in general, and data science and data analytics in particular, ranging from the traditional [Stack Overflow](https://stackoverflow.com/) site, to Google and YouTube, to the most recent ChatGPT or other LLMs, it is easy for students to complete any technical homework assignment or course project using such tools. Instructors should therefore focus on data and results interpretation and use new or unpublished data sets, if they wish to set such assessment or evaluation exercises at all. 

# Students: How to study?

For students, accompanying this book is a virtual machine with all required software installed and data sets provided. I recommend that students at least run the provided example code to get some ''hands-on'' with the tools. The best way to learn and understand is to experiment and modify the examples. See what happens when parameters or functions are changed. Ask yourself: Does the result match my expectation? Why or why not? Another way to work with the examples is to make sure you recognize the code elements in the formulas and vice versa. If the formula contains an X, where is this specified in the code or where does it appear in the output? Ensure that you can recognize and make the connection between the conceptual or mathematical level and the implementation in software.

Each chapter contains hands-on exercises. These are relatively simple exercises that build directly on the code presented in a section and require only minor changes or adaptations. These exercises invite experimentation with the code and trying different options. They are highly recommended to further your understanding.

Every chapter also contains a number of review questions. These are there to help check your own understanding. At least read and think about the questions, even if you do not write out any answers. 

Many chapters contain pointers to textbooks that formed the basis for the material in this book, and all contain links to online references. These are valuable in that they provide additional, deeper information. And because those resources are written by different authors, they may be easier to understand; at the very least they can provide a different and complementary perspective on the material in this book. Many textbooks that have been used to inform this book are popular or classic textbooks in their own right. Many could form the basis of a somewhat more narrowly conceived course on business analytics. In short, they make for excellent complementary reading and are highly recommended. The vast majority of them are also freely available on the internet.

Additionally, a wealth of information is available in various formats on the internet. This begins with Wikipedia pages, which provide a good introduction to many topics, and material from Wikimedia Commons has been used extensively in this book. Since all the tools used in this book are open-source tools, their web sites provide not only the code, but more importantly, also provide documentation in the form of tutorials, introductions, and detailed programming descriptions. These are all excellent resources. Many researchers and teachers in the area of machine learning have made their materials freely available, for example in their blogs or in YouTube videos and entire YouTube channels. Many of these researchers are active at the forefront of machine learning and are excellent teachers. These resources are valuable resources and provide more depth than offered in this book. At the same time, the current popularity of the topic has also led to some questionable material on the internet, and caution should be exercised when searching for material. Begin your internet search with a trusted source, for example Wikipedia, a well-known researcher, or material from a university instructor active in the field. 
