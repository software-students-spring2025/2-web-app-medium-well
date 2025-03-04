# Web Application Exercise

A little exercise to build a web application following an agile development process. See the [instructions](instructions.md) for more detail.

## Product vision statement

Our product is a study platform that allows students to search, create, edit, and practice questions through quizzes and flashcards to enhance learning and retention.

## User stories

[Link to user stories](https://github.com/software-students-spring2025/2-web-app-medium-well/issues) 

## Steps necessary to run the software
Before setting up the project, make sure you have the following installed:

1. [**Python (3.8+)**](https://www.python.org/downloads/)
   ```sh
   python3 --version
   ```
2. [**pip**](https://pip.pypa.io/en/stable/)
   ```sh
   pip3 --version
   ```
3. [**Git**](https://git-scm.com/)
   ```sh
   git --version
   ```
---

### **Installation**

#### **1. Clone the Repository**

```sh
git clone https://github.com/software-students-spring2025/2-web-app-medium-well.git
cd 2-web-app-medium-well
```

#### **2. Create a `.env` file **
-  An example file named `env.example` is given. Copy this into a file named `.env`.
-  Go to discord chat channel `team-mediumwell`, find values of `MONGO_DBNAME`, `MONGO_URI`, and `SECRET_KEY`
-  Edit these three values in `.env` while leaving the remaining values unchanged.

#### **3. Set up a Python virtual environment**
- Install `pipenv` using `pip`:
```
pip3 install pipenv
```

- Activate it:

```
pipenv shell
```
- To install the dependencies into the currently-active virtual environment:
```
pip3 install -r requirements.txt
```

#### **4. Run the app**
```
python3 main.py
```
#### **5. View the App**
- Running the app will output an address at which the app is running locally. Visit that address in a web browser.


## Task boards

[Link to task board](https://github.com/orgs/software-students-spring2025/projects/115)
