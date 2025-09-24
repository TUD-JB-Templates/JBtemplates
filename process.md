# The creation and publication process

After the [consideration before starting utilizing Jupyter Books](./start.md), the following steps are to be taken to get a Jupyter Book published on the TU Delft Open Courseware or Open Interactive Textbooks platform.

## Intake

The first step in the publication process is the intake phase where you will reach out to the library's ILM team [some link](). During this phase, the project team will gather all necessary information about the Jupyter Book project, including its goals, target audience, content structure and desired support. This information will be used to create a project plan and timeline. 

```{note} some thoughts
A intake form could be created to streamline this process.
```

During the intake, you will be updated on the options with regard to support in creating the ILM, open access publishing, copyright and plagiarism checks, and the publication platforms.

## Starting your project
For a head start of your project, we offer different templates. We will discuss these templates in one of the [next chapter](./which.md).

Occasionally, we will have meetings to discuss the progress of your project. During these meetings, we will address any questions or concerns you may have and provide guidance on best practices for creating and publishing your Jupyter Book.

## Finalizing and publishing your Jupyter Book
Once your Jupyter Book is complete, we will conduct a copyright check and plagiarism scan to ensure that all content is original and properly cited. At that stage, the source files will be mirrored to the TU Delft Gitlab from where it will be hosted by the TUD. We will perform an online check behind SSO on the OIT OCW platform to ensure that your Jupyter Book is properly formatted and meets all technical requirements for publication. The materials will be available but use an url with a prefix `dev` (https://ocw.tudelft.nl/dev/...) to indicate that it is not yet publicly accessible.

After the review and all checks, you are ready to publish your Jupyter Book. The latest version on the GitLab will be tagged with a release version (e.g., 1.0) to indicate its readiness for publication. We will work with you to ensure that your Jupyter Book is properly indexed and discoverable on the TU Delft OCW and OIT platforms, as well as other relevant platforms (when published open access). The final step is to announce the publication of your Jupyter Book through various channels, including social media, email newsletters, and academic networks. This will help to increase the visibility and impact of your work.

## After publication
After publication, you ought to maintain your Jupyter Book by fixing any errors, and responding to feedback from readers. Small revisions are possible, but major changes should be done in a new version of the Jupyter Book. We advise to make use of the `dev` branch for small changes and *{abbr}`squash merge (a Git operation that allows you to take all the changes from one branch and squash them into a single commit on top of the branch)`* this into the `main` branch with a proper summary of all changes made. 


```{warning} revisions
Revisions to your published work are possible, but should be limited to minor changes. Major changes - such as the inclusions of new chapters or significant reorganization - should be done in a new version of the Jupyter Book. The creation of a new version will be discussed upon request. Note that any inclusion of text and images should be properly cited and checked for copyright compliance.
```

