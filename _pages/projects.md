---
layout: archive
title: "Projects"
author_profile: true
redirect_from: 
  - /projects/
  - /projects.html
---

## A list of my current and past projects, including school and personal projects.

<img src="../../images/Screenshot 2025-02-16 191902.png">
**[MapLapse](https://gteref.github.io/maplapse-js/)** | _JavaScript, D3.js, Plotly, Mapbox_
* Developed an interactive web application using Plotly.js and Mapbox-gl that enables dynamic visualization of geographic data,
allowing users to animate changes across various datasets spanning multiple years and regions using a slider.
* Engineered data pipeline from US Census and Statistics Indonesia APIs to achieve fast and efficient fetching of geospatial data
* Architected feature that allows users to view detailed population and statistical information for each geographic unit in datasets.

**Semantic Text Analysis with Deep Learning** | _Python, PyTorch, GLoVe, NLTK, scikit-learn_
* Implemented Siamese neural network with convolutional layers to measure semantic similarity between text passages, achieving 80%+
correlation with human judgments
* Engineered custom structured similarity computation layer combining multiple pooling strategies to capture different aspects of semantic
meaning
* Integrated pretrained GloVe embeddings and implemented fine-tuning procedures to optimize model performance for specific semantic tasks
* Built end-to-end training pipeline including data preprocessing, model architecture, and evaluation metrics using PyTorch

<img src="../../images/Screenshot 2025-02-16 214429.png">

**Tranquil Mind** | _JavaScript, React.js, Gemini_
* Designed and deployed a Chrome extension using React and Google’s Gemini API, leveraging generative AI for on-demand virtual therapy.
* Developed adaptive user profiling with generative AI capabilities, enhancing chatbot responsiveness by 40% and enabling personalized
interactions based on user history and preferences.
* Enhanced user experience by implementing an AI-driven chatbox interface for prompt and contextually aware responses to user queries.

**Stack Overflow Clone** | _JavaScript, React.js, MongoDB, Express.js, Node.js, Axios_
* Engineered a full-stack clone of Stack Overflow, implementing key functionalities such as user authentication, content management, and a
comprehensive user reputation system.
* Designed to efficiently thousands of monthly and concurrent active users; includes real-time question, answer and comment updates,
sophisticated searching of questions by text and tags, and robust account management functionalities.
* Designed RESTful API using Express.js and Node.js, with Axios for seamless front-to-back integration; utilized MongoDB for efficient data
querying, supporting 10,000+ posts.

**Parallel Build System** | _C, Linux, GDB, Valgrind_
* Implemented a Make-like dependency resolution system in C that analyzes dependency graphs and executes tasks in parallel, utilizing Linux
system calls and signal handling for process orchestration.
* Developed a work queue for scheduling dependent tasks across multiple processes; implemented Unix pipeline functionality with I/O
redirection and comprehensive error handling.
* Ensured build system reliability through GDB-based debugging of concurrent execution paths, Valgrind memory analysis, and thread-safe
access to shared dependency states.

**Private Branch Exchange Server** | _C, Linux, POSIX Threads, Networking, GDB_
* Built a multi-threaded phone exchange server using POSIX threads and Unix sockets to handle concurrent client connections and manage call
states.
* Implemented thread synchronization using mutexes and semaphores to prevent race conditions, with ordered locking to avoid deadlocks
during call routing.
* Designed thread-safe reference counting with mutex protection and condition variables to manage shared resources and coordinate graceful
shutdown

**Decaf Compiler** | _Python, PLY_
* Developed a complete compiler front-end for Decaf (Java-like language) including lexical analysis, parsing, and abstract syntax tree
construction
* Implemented a type checker with support for inheritance hierarchies, method overloading, and static/instance member resolution
* Built intermediate code generator targeting a register-based abstract machine, supporting object creation, method calls, and control flow

**Community Services App** | _Kotlin, Android Studio_
* Developed an Android application in Kotlin that assists users in locating nearby community services like food banks and shelters.
* Integrated dynamic mapping and database queries using Google Play Services and OkHttp3, enhancing location accuracy and reducing
response time by 30%.
* Employed OkHttp3 library to handle thousands of JSON requests efficiently, providing reliable access to service information.