# External Communitiy Contribution Guidelines for selected Project - Part one

### 🤝 Contributor Covenant Code of Conduct

This Contributor Covenant sets out the rules for how everyone in our community should behave. We promise to make the community a welcoming and respectful place for everyone, no matter who they are. Good behavior includes being understanding, respecting different opinions, and taking feedback well. Bad behavior includes things like bullying, using inappropriate language, or sharing someone's private information without their permission. Community leaders will make sure these rules are followed and might give warnings or ban people who don't follow them. These rules apply everywhere in the community, and they're based on similar rules used by other groups. You can find more details and translations if needed.

### 🤝 Contribution guidelines

Contributing to Storybook is welcomed and encouraged, with various avenues available for participation. Whether through proposing new features via the RFC process, submitting code for bug fixes and enhancements, integrating Storybook with new frameworks, improving documentation, providing examples, or developing addons, there are numerous ways to get involved. If you're unsure where to start, consider exploring existing issues and pull requests, joining community discussions, seeking guidance from project maintainers, and familiarizing with the project's guidelines is recommended. 

### 🤝 Step by Step Procedure to contribute

1. Node Version Management - Ensure you have a compatible Node version installed. Storybook specifies the Node version in the .nvmrc file. It's recommended to use fnm as the Node version manager and configure it with specific parameters using the fnm env command.

2. Running the Local Development Environment:
   * If using Windows, it's recommended to use Windows Subsystem for Linux (WSL).
   * Run yarn start in the root directory to start a basic test Storybook "sandbox."
   * If encounter any errors, try rerunning yarn start a second time.

3. Handling Issues - If there is any specific issues, follow the provided instructions for resolving them, such as running specific commands to identify and potentially remove unintentional local changes.

4. Forked Repositories - If the repository is forked, disable GitHub Actions for repo to prevent potential failures due to lack of proper authorization.

5. Running against Different Sandbox Templates - One can choose a specific template to use for your sandbox to select the desired template and task.

6. Making Code Changes - If there is need to make code changes to Storybook packages while running a sandbox, follow the provided steps.

7. Contributing to Storybook - For further guidance on contributing, refer to the NEW contributing guide on the Storybook website.

### References

🔗 Contributor Covenant Code of Conduct - https://github.com/storybookjs/storybook?tab=coc-ov-file#readme

🔗 Readme.md - https://github.com/storybookjs/storybook?tab=readme-ov-file#contributing

🔗 Contribution.md - https://github.com/storybookjs/storybook/blob/next/CONTRIBUTING.md

🔗 Contribution guidelines - https://storybook.js.org/docs/contribute

----
----

# Community Code Contribution Information - Part one

## Project - [Storybook](https://github.com/storybookjs/storybook?tab=readme-ov-file)

### 📘 About Storybook

 Storybook is like a workshop for frontend developers where they can build, test, and showcase individual pieces of a website or app (called UI components) without needing to put them together in the entire project. It helps developers work on these pieces faster and more easily, making sure they look and behave as intended before putting them into the final project.  Storybook boasts an active and vibrant community of developers who contribute to its development, share knowledge, and provide support through platforms like GitHub Discussions, Discord, blogging, and social media channels. Storybook receives support from sponsors and backers who contribute financially to the project's development and maintenance. It also operates under the MIT license, allowing for widespread adoption and usage.

Supported Frameworks of Storybook which supports multiple frontend frameworks are React, Angular, Vue.js, Svelte, Ember, Preact, and others. It also extends support to mobile development frameworks like React Native and native mobile platforms like Android, iOS, and Flutter.

## 🤝 Contribution Details

### Forked Repository link - [Storybook](https://github.com/BasranS/storybook/tree/compodoc_info)

### Choosen Issue - [More clarity on what including compodoc does?](https://github.com/storybookjs/storybook/issues/24944)

#### *Issue Labels*

* angular
* CLI
* documentation
* good first issue
* help wanted

### 🔍 Detailed Explanation of Issue  

The problem described in the issue is related to the lack of clear documentation regarding the usage of Compodoc within a Command Line Interface (CLI). When users encounter this prompt within the CLI, asking if they want to use Compodoc, they express a need for more detailed information on what Compodoc does and how it integrates with the project workflow as, this is an angular project.

The provided links offer additional context by directing to a [Stack Overflow](https://stackoverflow.com/questions/77519750/using-compodoc-for-storybook-documentation) question discussing the utilization of Compodoc for Storybook documentation. This implies that the users seek clarity on how Compodoc can be utilized in conjunction with Storybook.

### ✅ Work Done 

To contribute to an open-source project of community code part 1:

* I Forked and cloned the project to my machine.
* After that, I establish a new branch with name compodoc_info to work upon the issue.
* Did research about compodoc documentation for angular projects which provided as references.
* Then after, I create a file with name ["compodoc_readme.md"](https://github.com/BasranS/storybook/blob/compodoc_info/Compodoc_readme.md) and add everything relevant to the topic.
* Also, I made a contribution file under name ["compodoc_contribtuion.md"](https://github.com/BasranS/storybook/blob/compodoc_info/Compodoc_contribution.md) to describe my contribution for this work.
* Then I commit and push all the content to GitHub.

### Code Review and Outcome

The documentation got reviewed by Baljit Singh, and he told me to add a section in my readme which describes some "Real-world examples" 
who uses compodoc documentation for the Angular projects which , I added now.

### Reflection on Success

Upon successful completion of this issue, I gained some useful knowledge regarding a completely new topic Although, this is a documentation issue but, this needs a lot of research as, this topic is completely new to me and requires time to work upon. Also, I learned the importance of clear documentation. This experience emphasized the significance of seeking clarification, and advocating for change to drive positive outcomes and enhance the user experience.

### Next Steps

As I gain knowledge on this topic, my curiosity drives me to seek further understanding through additional research. Furthermore, I aim to put it into practice to observe its practical outcomes firsthand.


### Project Contribution Links

🔗 Project link  - [Storybook](https://github.com/storybookjs/storybook)

🔗 Forked Repository - [Storybook](https://github.com/BasranS/storybook/tree/compodoc_info)

🔗 Issue - [More clarity on what including compodoc does?](https://github.com/storybookjs/storybook/issues/24944)


-----
-----

# Community Code Contribution Information - Part two

## Project - [Pattern Library](https://github.com/nic-dgl104-winter-2024/pattern-library)

###  📘 About Pattern Library

The "DGL 104 Pattern Library," which includes implementing common software design patterns and describing architecture patterns in various programming languages. Contributions must adhere to open-source project standards, including pull request submissions and issue management for students to contribute and learn.

### Selected Issue 1 - [Add React Native Implementation for Singleton Pattern #8](https://github.com/nic-dgl104-winter-2024/pattern-library/issues/8)

### ✨ About selected Issue 1 

For this issue, I need to integrate the Singleton pattern into our React Native app. This pattern ensures that only one instance of a specific class exists in the entire application, which is beneficial for managing shared resources efficiently. By implementing the Singleton pattern, we can guarantee consistency and prevent resource wastage in our app.

### Contributors 

* Baljit Singh
* Anjitha Karuthara Balakrishnan
* Sandhya Basran

### Work Done

1. I choose this issue, by filtering with some labels and then, fork and clone it into my machine.
2. After that, I create a branch with name react_native_development.
3. For this issue , I submit two pull request, one is my individual work
4. The second pull request is our group work as we are three working together on this issue

### ✨ Old pull request outcome

The provided outcome is given by Sandhya Basran as an outcome for the initial pull request under file name "Mysingleton.js" along with a descriptive file which was "contribution.md" to specify everything about react- native and singleton.

```javascript
class MySingleton {
  static instance;

  constructor() {
    if (MySingleton.instance) {
      throw new Error("Singleton instance already exists. Use getInstance method.");
    }

    this.myProperty = "Initial Value";

    MySingleton.instance = this;
    Object.freeze(MySingleton.instance);
  }

  static getInstance() {
    if (!MySingleton.instance) {
      MySingleton.instance = new MySingleton();
    }
    return MySingleton.instance;
  }

  myMethod() {
    console.log('Singleton method has been called.');
  }

  anotherMethod() {
    console.log('Another method of the Singleton has been called.');
  }
}

// Usage in a React Native component
import React, { Component } from 'react';
import { View, Text, Button } from 'react-native';

export default class MyComponent extends Component {
  constructor(props) {
    super(props);

    // Get the singleton instance
    this.singletonInstance = MySingleton.getInstance();
  }

  handleButtonClick = () => {
    // Call methods of the singleton instance
    this.singletonInstance.myMethod();
    this.singletonInstance.anotherMethod();
  };

  render() {
    return (
      <View>
        <Text>React Native Singleton Example</Text>
        <Button title="Call Singleton Methods" onPress={this.handleButtonClick} />
      </View>
    );
  }
}
```

----
----

### Code Review and Outcomes

Sumit Joshi did my code review for 


### Reflection on success


### Next steps 

-----
-----

## Selected Issue 2 - [Write definition of Template pattern in README.md](https://github.com/nic-dgl104-winter-2024/pattern-library/issues/66)

### ✨ About selected Issue 2

For the issue "Write definition of Strategy pattern in README.md," I need to add a section to the README.md file of the "DGL 104 Pattern Library" project. This section should provide a clear and concise definition of the Strategy pattern, including its purpose, benefits, how it works, implementation guidelines, and example use cases. Ensure that the information is easy to understand and relevant for other developers using the library. Once added, commit the changes to the repository.

### ✨ Work Done


----
----

To contribute to an open-source project of community code part 2:

### Code Review and Outcomes


### Reflection on success


### Next steps 
