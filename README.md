# Open Hardware Documentation Template
An easy use folder structure and instructions for setting up a repository for open-source hardware

In this repository, we present a template, short instructions, and a folder structure for a repository for describing relatively small hardware projects.  
The main goal of this work is to simplify starting such a repository at an early stage of the project and motivate team members to regularly update their documents in a structured way. 
To keep it agile, filling in the necessary information for the first version repository should not take more than 10 minutes. 

_Instructions to fill in this file are put in italic. Remove these when you are filling descriptions relevant to your project._

_The introduction paragraph, right under the title, should explain the context of the project as well as why has it been initiated._

## Main features
_This subsection is a very brief introduction to the context and key features of your project that could be interesting for a user in search of a solution_

The most important file in the repository is the README.md in the root folder of the reposity.
The headers used in the current README file are the most essential to present. 
Some optional headers are suggested in curly brackets (...). 
Try to present only the main information for the viewer to get started. 
Detailed updates or build instructions are better suited for the subfolders such as `./Docs` or `./Results`.

Next to the README file, a basic folder structure is also presented in this repository. 
Each subfolder contains a `_readme.md` file that explains the conventions and purpose of that folder for the (future) collaborators to keep it tidy.

This template is adjusted to the typical needs of a hardware project made for research or education. 

```
.
|--- Build 
|--- Docs
|--- Results
|--- Software
| LICENSE
| README.md

```

The purpose of each subfolder is explained below:
+ Build: Contains all the (binary) design files that are needed for the hardware. Use subfolder for more complex assemblies.
+ Docs: Contains the documentation of the project: background information, sources, warnings, and build instructions. 
+ Results: For measurement or functional devices, it is good to report some results as a benchmark for others who try to replicate the project.
+ Software: For hardware projects that have an operating software or firmware, it is a good versioning practice to separate the software code from build instructions.

## Build instructions
_Guide the reader with the order of browsing your project repository for an optimum building experience_
 
When you want to start a new repository, it is better that you copy this repository to your project repository and start by changing all the description.
All instructions and (sub)headers are suggestions. You can change the style, order, or composition as you see necessary. 

It would be kind if you put a shortcut to your Bill of Materials file.
This template can be copied free of charge. 

## Outcomes
_Here you can list the outcomes of the project that you would like to hightlight. It does not need to be an exhaustive list_

We will list some best practices and good examples from projects that have used this template for their documentation.

## Team
_Even though platforms such as github show a list of user accounts for contributors for a project or repository, the past contributors or external collaborators also deserve a place here_

+ Project initiator: Sanli Faez @sanlifaez
+ Contributors:
	+ _add a list of main contributors_


## Get involved
_Especially for open source projects, it is benefitial to motivate the potential users of the project to contribute back or share their feedback. Make it easy for them._

Comments and suggestions on this folder structure are always welcome. Please create an issue to share your feedback or question, or if you prefer send a pull request. 

Better structured projects can explain a number of options for contributors such as: 
+ (where to start)
+ (issue template)
+ (direct contact)
+ (pull requests)

## License
_After the README, A LICENSE is the most important file in the project documentation. Without a license, there is too much uncertainty to try building anything on top of the original project._

This project is released under CC0 1.0 Universal. 
You can modify an reuse as you like.
The project team appreciates your suggestions or examples for enhancing the repository, but your consistent documentation of your project is the best gift to the world. Hopefully, this template could make that a bit easier for you. 

### (How to cite:)
_Additionally, you can specify how other can cite your project._

## (Funding)
_Be kind to your funders and mention their support visibly and consistently. They also need to show their resources are wisely spent._

![LPL sharing image](./Docs/Images/lpl_sharing.jpg)
