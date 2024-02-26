## Escape Rules Contribution Guidelines
This guide provides a collection of instructions to assist you throughout the contribution process. We warmly invite contributions from anyone interested to improve/add new rules to this project. 
No contribution is too small 🤗

## 1. Take a look at existing rules

Please, take a look at the existing Escape Rules and Rules in GutHub Issues or Pull Requests before creating a new one. Don't invest your energy in duplicate work 😉
Take a look [at the documentation](https://docs.escape.tech/custom-tests) on how the Rules work.

The structure of the project is simple:
- Business-logic
  - These tests are agnostic to the underlying technology, and leverage the inference engine of Escape to detect the type of data manipulated.
  - You can find inspiration for your business-related API features here, and check that the proper validations and steps are in place.
- Technologies
  - These tests are more specific to a particular framework or library, with misconfigurations or dangerous versions.
- Vulnerabilities
  - These tests are closer to [common CWE patterns](https://cwe.mitre.org/index.html) and validate implementation flaws.

## 2. Fork the project
Fork this repository. This will create a local copy of this repository on your Github Profile. Keep a reference to the original project in upstream remote.

## 3. Create your template branch
Create a new branch. Use its name to identify the issue you are addressing.

## 4. Create Rule and Commit
- Create your template, use [the available template](./rule_template.yaml)
- Add all the files/folders needed.
- After you've made changes or completed rule creation, add changes to the branch you've just created.
- Don't forget to give a descriptive message to clearly explain to the reviewer the main purpose of your rule.

Multiple templates for same technology can be grouped into single Pull Request.

## 5. Push Your Changes
Now you can push your template to the forked repository.

## 6. Pull Request
Open your browser and head to your GitHub repository. Next, access the Pull requests tab and click on the New pull request button. Please, offer a clear title and description for your pull request, outlining the rule's purpose.
Congratulations 🍾 Your Pull Request has been sent. Our team will review and merge it if it meets project standards. Otherwise, we'll provide you feedback for improvement.

## Need extra help?
Check out our documentation or reach out to project maintainers or your peers in the channel #custom-rules in our [Slack Community.](https://slack.escape.tech)

