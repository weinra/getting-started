# getting-started
The world's most approachable open source project. This repository is a guide to contributing to this repository. A repository (or repo) is what we call a project on Github. You can think of a repository as just a folder with files in it. In this guide, you will be adding a file (your file!) to the [`contributors`](/contributors) folder in this repository. Don't be scared! You can do this! Follow these instructions to make your first open source contribution!

## Create a Github Account

If you already have a Github account, you may skip this section, otherwise, if reading this, your screen probably looks something like this:

![Initial Repo Appearance](/images/initial-repo-appearance.png)

The first thing to do is create an account. Click the `Sign Up` button in the middle of the screen (if it is there) or click the `Sign Up` link in the top right of the screen.

Fill in some basic information to join github:

![Join Github](/images/join-github.png)

You can continue to complete your account on the following screens. We recommend selecting the free plan (to start) and skipping the `Step 3: Tailor your experience` screen for now:

![Choose Github Plan](/images/choose-github-plan.png)

The most important part in creating your Github account is verifying your email address. Go to your email inbox (the one you used to sign up for github) and you should have received an email from Github:

![Github Email](/images/github-email.png)

Click the `Verify email address` link in the Github Email:

![Github Verification Email](/images/github-verification-email.png)

You should see a confirmation screen telling you the email was verified:

![Github Email Confirmation](/images/email-verification-confirmation.png)

You have created your Github account! You are well on your way to contributing to your first open source project!

## Make a Contribution (Pull Request)

There are a handful of ways to contribute to open source projects, one of the most popular ways to contribute is with a Pull Request. This section will show you how to make your first Pull Request.

A Pull Request is a change you are suggesting this repository should make. Here, you will suggest that this repository should add a file with your name on it to the [`contributors`](/contributors) folder.

Return to [https://github.com/approachable-io/getting-started](https://github.com/approachable-io/getting-started) 

![Approachable Getting Started Link](/images/approachable-getting-started-link.png)

Click the link to the [`contributors`](/contributors) folder. This is where we will be making our contribution!

![Approachable Getting Started](/images/approachable-getting-started.png)

Once you are in the [`contributors`](/contributors) folder, click the `Create New File` button.

![Create New File](/images/create-new-file.png)

> Note: It's really important that you create the new file when you are in the [`contributors`](/contributors) folder and not another part of the project.

With most open source projects, you can't make changes to someone else's project without their permission. Instead, you will create a copy of their project (called a `Fork`), make the changes to your copy, and then ask them nicely if they will add the changes you made in your project to their project (a `Pull Request`). Let's step through that. First, let's make a copy of the project by clicking the big green button that says `Fork this repository and propose changes`.

![Fork Repository Screen](/images/fork-repository-screen.png)

Nice! Now we are going to create our file! In the top box, we need to name our file. Let's give it a name of your first name and your last name like `first-last.md`. My file was `luke-schlangen.md`, Grace Hopper's file would be `grace-hopper.md`. A few notes:

- If you have the same name as someone else who has already contributed to the project, you may need to add a middle name or initial. John Smith might have to name his file `john-henry-smith.md`
- Please follow the "All lowercase" and "No spaces" rules here. When contributing to open source, following the conventions of the project is really important.
- The file we're going to be adding is a "Markdown" file. Your file must end in `.md`. Like a normal folder, we can add almost any type of file `.doc`, `.js`, `.ppt`, but here, we are adding a Markdown file.

> Fun Fact: The naming we're using here is called `kabob-case` because it kind of looks like the `letters-are-on-a-kabob-stick`. ![Photo by pan xiaozhen on Unsplash](/images/pan-xiaozhen-kabob.jpg)

Now add some content to your markdown file. When you are editing the file, it will appear as plain text, but the symbols like `-` and `*` and `#` can change the appearance of the final product thanks to Markdown. Put a `#` in front of the first line to make it appear larger. For the formatting to work properly, there needs to be a space after the `#`. Here is an example of what it might look like:

```Markdown
# Your name

A fun little fact about yourself that doesn't give away sensitive information.
```

![Example New Contributor File](/images/new-contributor-example.png)

Once you are happy with a short description of yourself, scroll to the bottom of the page and click the `Commit changes` button. Please remember this is public on the web, so do not put sensitive or private information here.

![Github Commit Changes](/images/commit-changes.png)

After you commit your changes, you will be asked to compare your changes. I'll explain what's going on here, but you don't need to stress yourself out about these details, because by default, everything should be set up correctly. When you are comparing changes, there are four dropdowns.

1. The first dropdown (the `base fork`) should be the repository to which you would like to contribute. Selecting `approachable-io/getting-started` says you would like to contribute back to the original repository (where you cloned from when you started). 
2. The second dropdown is the `base` branch to which we would like to contribute. Selecting `master` is selecting the main branch for the entire project. This can be pretty confusing, so know that we only have one branch and it is `master`, so you're doing it right.
3. The third dropdown (the `head fork`) is your copy of the original project. This will look something like `my-github-username/getting-started`.
4.  The fourth dropdown (the `compare branch`) is the name of your branch where you have made your changes. This will likely be something like `patch-42` or `patch-379`. 

Again, all of the other dropdowns should be correct, so there shouldn't be any need to change these values.

![Comparing Changes](/images/comparing-changes.png)

When you are ready, click the `Create pull request` button. The next page is where you can add a description and more details to your Pull Request. It's also a chance to make sure your changes won't "conflict" or interfere with anyone else's contributions. As long as it says, "Able to merge" you should be all set to click the `Create pull request` button.

> Note: If it doesn't say "Able to merge" then you may have a conflict. This can happen if you have created a file with the same name as someone else - maybe they made their file at the same time you made yours and they were a minute faster! If that happens, the easiest thing to do is to go back to the [`contributors`](/contributors) folder and create a new file with a different name from your first one.

![Open Pull Request](/images/open-pull-request.png)

## Waiting for approval

Nice work! You made a Pull Request! Now, your contributions won't be a part of the original project until a `collaborator` (someone on the project team) approves your Pull Request. When your changes are approved and merged, they will be added to the project! If you are interested in the approval process, we wrote about it here: [Pull Request Approval Process](/pull-request-approval-process.md). When your pull request is approved, you will see your new file in the [`contributors`](/contributors) folder. It would look something like this:

![New Contributor File](/images/new-contributor-file.png)

Until then, you can keep an eye on your pull request. When it is merged into the project, the Pull Request will look something like this after it is approved:

![Approved Pull Request](/images/approved-pull-request.png)

And if you click on it, you should see the end result is a beautifully rendered markdown file:

![Rendered Markdown File](/images/rendered-markdown-file.png)



## You did it!

You have contributed to an open source project, and this `getting-started` project is better for it! This did simplify some of the process for most of the more complicated Open Source projects, but the fundamentals - making a copy of the code, making changes, and asking for the original - will apply accross almost all projects.

## Next up!

If you enjoyed this tutorial, you should try your hand at other [Approachable Open Source](https://github.com/approachable-io)
