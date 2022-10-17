# Benchmark name

[![Page Badge](https://badgen.net/badge/icon/Benchmark?label=Page)](https://benchmark.webots.cloud/run?version=R2022b&url=https://github.com/Jean-Eudes-le-retour/own-pendulum-benchmark/blob/main/worlds/inverted_pendulum.wbt&type=benchmark)

## Description

Write here a short description of your benchmark.

<p align="center">
  <img src="./preview/thumbnail.jpg">
</p>

## Information

- Difficulty: 1 to 5
- Robot: robot name
- Language: programming language of controller template
- Commitment: Amount of time needed to program controller

Info from information.txt, shown on webots.cloud. Does it need to be here too? Automatic sync?

## Organizer setup

TODO: add all the steps needed to organize one's own benchmark



## How to participate

### Create your own entry repository from the template

[Click here](../../generate) to create your own repository or do it manually by clicking on the green "Use this template" button.

Fill the "Repository name" field with a name for your controller.
Choose the visibility of your controller, keep it "Public" if you don't care about people looking at your controller code otherwise set it to "Private".
Finally, click on the green "Create repository from template".

### Add the organizer as collaborator if you set your repository as private

Go to your personal repository page (https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME) and go to the "Settings" tab.

Under "Access" click on the "Collaborators" section.
You will then need to confirm the access by re-entering your GitHub password.

When this is done you should see a "Manage access" box where you will see the current collaborators of the repo.
Click on the "Add people" and search for "Jean-Eudes-le-retour". When you found the organizer, add them to the repository.

### Submit your entry by using posting an issue using the provided template

After you added the organizer as a collaborator, go back to the main page of your repository and copy your full repository URL.

Come back to this page and [click here](../../issues/new?assignees=&labels=registration&template=registration_form.yml&title=Registration+to+benchmark) to start your registration. If it doesn't work, you can do it manually by going to the "Issues" tab, creating a new issue and choosing the "Registration to benchmark" template.

Paste your repository URL in the URL field and click the "Submit new issue" button.

A series of automated actions will take place. If everything went well, you should get a message saying that you are successfully registered to the benchmark.

### Modify the template controller and/or create your own one

Everything should be good to go, you can modify the files in the controllers folder.

The supervisor controller is a special controller that is used to evaluate your controller's performance.

Webots supports multiple programming languages, see the [Webots documentation](https://www.cyberbotics.com/doc/guide/language-setup) if you are interested.
Be sure to name your main controller like the default controller (except for the file extension) for it to be used in the leaderboard evaluation.
