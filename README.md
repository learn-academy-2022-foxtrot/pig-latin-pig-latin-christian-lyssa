# 🐷 Pig Latin Activity

[Oday ouyay eakspay igpay atinlay?](http://www.wikihow.com/Speak-Pig-Latin)

In this activity we're going to create an application that translates regular English words into Pig Latin.

### 💬 Rules of Pig Latin

- For words beginning with a vowel, add "way" to the end.
- For words beginning with one or more consonants, move all of the first consecutive consonants to the end, and add "ay".
- If the first consonants include "qu", move the "u" along with the "q". Don't forget about words like "squeal" where "qu" doesn't come first!
- "y" is treated like a vowel in appropriate circumstances.

There are many [examples](http://funtranslations.com/pig-latin) of Pig Latin translators out there on the internet to give you inspiration.

### ▶️ Getting started

This is a very difficult problem to solve. Take the time to plan your approach and brainstorm with your team.

This project is going to utilize React for the UI and the JavaScript logic. There is already some code inside the React application that will provide a UI for the Pig Latin project. Your job is to create the logic. All the code you'll need to write for this app is going to be inside one function in the `/src/App.js` file.

After you accept the assignment from GitHub Classroom, you'll want to install all the necessary dependencies.

```bash
$ cd pig-latin-challenge
$ yarn
```

Then you are ready to start a server to run the application.

```bash
$ yarn start
```

Now you're ready to code!

To get started, find the `myPigLatinCodeHere` function, and write your code. Every time you save your updated file, the browser window displaying your app will reload.

---

### 🐽 Pig Latin Challenge

Oday ouyay eakspay igpay atinlay? If you are scratching your head at that statement, we at LEARN Academy have you covered. Our development team has been tasked with creating a Pig Latin translator application. This app will take regular English words and covert them to Pig Latin. With this application you will eakspay igpay atinlay uentlyflay in no time!

**Story 1: In order to see English words converted to Pig Latin, as the user of the application, I need to see words beginning with a vowel translated to add "way" the end.**

**Branch:** vowel-functionality

**Acceptance Criteria**

- Can type any word that begins with a vowel in the text input (e.g. apple)
- Can hit the submit button
- Can see the words that begin with a vowel translated to Pig Latin and rendered to the page (e.g. appleway)

**Story 2: In order to see English words converted to Pig Latin, as the user of the application, I need to see words that have "qu" in the first syllable translated by moving all the consonant and the "u" to the end and add "ay".**

**Branch:** qu-functionality

**Acceptance Criteria**

- Can type any word that has a "qu" in the first syllable in the text input (e.g. squeal)
- Can hit the submit button
- Can see the words that have a "qu" in the first syllable translated to Pig Latin and rendered to the page (e.g. ealsquay)

**Story 3: In order to see English words converted to Pig Latin, as the user of the application, I need to see words that have no vowels other than "y" translated by moving all the consonant to the end and add "ay".**

**Branch:** y-functionality

**Acceptance Criteria**

- Can type any word that has no vowels other than "y" in the text input (e.g. fry)
- Can hit the submit button
- Can see the words that have no vowels other than "y" translated to Pig Latin and rendered to the page (e.g. yfray)

**Story 4: In order to see English words converted to Pig Latin, as the user of the application, I need to see words that have one or more consonants translated by moving all the consonant to the end and add "ay".**

**Branch:** consonant-functionality

**Acceptance Criteria**

- Can type any word that starts with one or more consonants in the text input (e.g. through)
- Can hit the submit button
- Can see the words that start with one or more consonants translated to Pig Latin and rendered to the page (e.g. oughthray)

### 🏔 Stretch Challenges

- As a user, I can see pleasant stylings on the application.
- As a user, I can input a sentence that includes punctuation.
- As a user, I can input a sentence that includes lower and upper case words.
- As a user, I can see a message if I am not using the application correctly.

### 👩‍💻 Developer Stretch Challenges

- As a developer, I have a well commented application.
- As a developer, I have well written README file with instructions on how to access my repository.
- As a developer, my variables are all named semantically.
- As a developer, I have refactored and efficient code.
- As a developer, I have my application [deployed as a live website](https://render.com/docs/deploy-create-react-app).
