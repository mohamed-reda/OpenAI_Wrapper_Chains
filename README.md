**OpenAI Wrapper Chains**

Welcome to the OpenAI Wrapper Chains repository! This repository hosts a Python library that provides a convenient
wrapper around OpenAI's powerful language models, allowing you to seamlessly integrate them into your projects.

## Overview

LangChain has built a Wrapper around OpenAI APIs, enabling access to all the services provided by OpenAI. This wrapper
simplifies the integration process, making it easier for developers to leverage OpenAI's capabilities in their
applications.

## Features

- Import specific classes from the LangChain library for easy access.
- Initialize the ChatOpenAI object with customizable parameters.
- Conduct structured chats with the Chat-GPT model for various conversational scenarios.
- Utilize the wrapper to build chatbots and other conversational AI applications.

## Usage

1. Import the required classes and initialize the ChatOpenAI object.
2. Structure your conversation scenarios using SystemMessage, HumanMessage, and AIMessage.
3. Utilize the wrapper to engage in conversational interactions with the Chat-GPT model.

## Contribution

Contributions to this repository are welcome! If you have any suggestions, bug fixes, or feature requests, feel free to
open an issue or submit a pull request.



---

Feel free to explore the repository and start integrating OpenAI's language models into your projects with ease! If you have any questions or need further assistance, don't hesitate to reach out. Happy coding!
------------

**Running Jupyter Notebook:**

To launch the Jupyter Notebook server, use the following command:

```bash
jupyter notebook
```

(Note: Use Control-C to stop the server)

---

**Installing Dependencies:**

Ensure that the required dependencies are installed by running the following commands:

```bash
pip install -r requirements.txt
python -m pip install jupyter
```

---

**Memory Profiling:**

To profile the memory usage, decorate your Python script with `@memory_profiler.profile` and run the following command:

```bash
python -m memory_profiler main.py
```

---

**Line Profiling:**

For line-level profiling, use the `line_profiler_pycharm` package. Decorate your Python script with `@profile` and
execute the following command:

```bash
python -m line_profiler main.py.lprof > results.txt
```

Make sure to replace `main.py` with the appropriate filename.