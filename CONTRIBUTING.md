## NUIverse Contribution Guide
I'd like to contribute something to the NUIverse? Here's how you can help!

There are several ways to contribute to the NUIverse, is reviewing our code, reporting problems, suggesting new ideas, reporting bugs, and more. The following is our guidelines so that you can help us. By dedicating some time to read our guidelines, we understand that you respect and project developers all the time dedicated to NUIverse. This helps us to have a better communication, organize our repository and creates a good connection with those who want to help in any way, given that we will be returning that same respect to address your suggestion or problem :-).

### Using issuetracker
If you have found an error or bug, please use the issue tracker. It is the preferred medium for this type of contact, however we ask you to use it, please observe the following restrictions:

- Please do not use the issue tracker to personal support requests. Stack Overflow, Slack or IRC are best places for help.
- Please don't invade problems and isn't a troll. Keep the discussion on topic and respect the opinions of others.
- Please do not post comments consisting only in "+1" or " -1". Use of "reactions" from GitHub. We reserve the right to delete comments that violate this rule.
- Please do not use words of low slang or offend people and also do not use images or content of sexual nature.

### Issues and labels
In our bug tracker we use several labels to help organize and identify problems. Here's what they stand for and how we use them:

- **Browser bug** - problems that are reported to us, but are actually the result of a specific browser bug. They are diagnosed with - reduced test cases and result in a problem open in own browser's bug tracker.
- **Confirmed** - problems that were confirmed with a reduced test case and identify a bug in NUIverse.
- **CSS** - problems arising from our compiled CSS or Sass source files.
- **Doc** - problems to improve or update our documentation.
- **Examples** - problems involving the sample templates included in our documents.
- **Feature** - Trouble requesting a new feature is added or an existing be extended or modified.
- **Helpcommunity** -problems that we need or would like to help the community to solve.

### Bug reports
A bug is a demonstrable problem caused by our code repository, to verify clearly what is taking place, there is a need to complete reports and well informative, below is an example of how to create a good report:

1. Validate and submit your code-validate and check your HTML to ensure that the problem is not caused by a single error in your own code.
2. Use HTML5.
3. Use the GitHub issues search-check if the problem has already been reported.
4. Check if the problem has been corrected-try to play it using the mastermais recent branch or repository development.
Isolate the problem-ideally, create a test case and a live example, use sites such as [`JS Bin`](http://jsbin.com/?html,output) or [`jsfiddle`](https://jsfiddle.net/).
5. Notify important details such as: operating system, browser version, version of the NUIverse, notify your environment, notify the steps will reproduce the problem, share other information that you think useful to help us solve the problem.

### Pull requests
Good pull requests, patches, enhancements, new features are a fantastic help and allows the NUIverse go ahead and reach a new level. They must remain focused in scope and avoid contain unrelated commits below good practice of how to pull requests:

1. Please, before you write any code or do anything else, ask first before embarking on any significant pull request (for example, implement features, code refactoring, porting to a different language), this avoids the risk of spending a lot of time working on something that project developers may not want to merge in your project.
2. Make new requests to the current development project, requests for earlier versions that have been completed will be rejected.
3. Do not edit nuiverse.css directly. These files are automatically generated. You must edit the source files `/nuiverse/scss/` instead.
4. If you want to contribute to the documentation, you must edit the files to `/nuiverse/current version/scss`. We also ask that you focus your efforts on the current versions in development that will be launched soon, the old versions and finalizasen will be in maintenance stage in some cases only.

### Troubleshooting or bugs:
1. Fork our repository.
2. Clone the repository that you forked running:
3. `$ git clone https://github.com/SEU-USERNAME/nuiverse.git`
4. Prepare your development environment for working with SASS.
5. Edit the files of scss/folder, for example, if you are fixing a problem on the form edit the scss file/form. and add your changes scss.
6. Include a title goal.
7. Wait until someone review the request and merge your extraction extraction request.

### Licence
By contributing your code, you agree to license your contribution under the [BSD Clause 3](https://opensource.org/licenses/BSD-3-Clause).
By contributing to the documentation, you agree to license your contribution under the **Creative Commons Attribution 3.0 Unported License**.
