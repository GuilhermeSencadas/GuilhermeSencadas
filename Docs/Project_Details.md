# Study Center

## 1. What is it?

I came up with this project when I remembered how it used to be hard to study and challenge myself. I saw some people create their own Question Cards with the answers in the back, but I didn't like the idea of 'wasting' all that paper and putting all the time to create those.

Therefore, I wanted to try to create a Hub to allow any student/ teacher to create their own tests.

---

## 2. Modules

The app I want to achieve at the momment has the following modules:

* **SPA** - Single Page Application using Angular to dynamically render new contents as the UI.
* **Logistics** - Contains all questionnaire related content.

---

## 3. Tasks

### 3.1. **US101** - Create a Subject

A Subject must have the following contents:
    
* Code - A 5 letter code that the user chooses.
* Description - Describes the given subject (Max. 50 chars). 

### 3.2. **US102** - Create a Category

A Category must have the following contents:

* Name - The name of the module
* Description - Describes the given category (Max. 50 chars)


### 3.3. **US103** - Create a Question

A Question must have the following contents:

* Number - A number to identify each question of a given test;
* Text - The questions content;
* Type - Free-text, Single-Choice, etc.
* Subject - The subject code whose the question belongs to.
* Category - The category code whose the question belongs to. 

**Example:**

* Single-Choice question: 
    1. How much is 2+2?<br>
        a) 4.<br>
        b) 3. <br>
        c) 5.<br>

* Free-Text question:
    2. How was your day?<br>

---

## 4. Requirements

For the application I have some requirements I want to meet.

* Create a RESTful API;
* Follow the Onion Architecture;
* Follow the SOLID principles;