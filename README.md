# Mycroft - QA System

Question answering system designed in individual modules and uses XML files to contain the information.

## Getting Started

Each part of the system is an individual module. For example, questionProcessing is a module that imports a module called classification which will call a function to classify a question.

### Prerequisites

What things you need to install the software and how to install them

```
lxml package
```
```
wikipedia package
```

Need a text file containing questions, 1 question per line. There is a sample file includeded.

### Installing

First you need to install lxml

```
pip install lxml
```

Then install wikipedia

```
pip install wikipedia
```

Make sure you download all the files, even if you are working with just one module. Since the main script calls are processes of the QA system, you need to download all the files.

## How to Run

...
python QA_System.py
...

Enter the name of the text file containing the questions when prompted.

You will be asked to enter file names for XML files; each question and it's deconstruction and answer will be stored into a seperate XML file. At the end there will be a file named 'answers.txt' which will list each question and the top 2 answers.

