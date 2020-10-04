# Automate Androide Depreciated-API(1st Research Paper)
_____
_____
_____
					(Usage Update by learning from single updated Example)
____
## Authors: A.Haryno,Ferdian Thung,Hong Jin Kang, Lucas Serrano,Gilles Muller,Jullia Lawal,David Lo,Lingxiao Jiang.

link: 
[Visit to Webpage](https://conf.researchr.org/details/icpc-2020/icpc-2020-era/7/Automatic-Android-Deprecated-API-Usage-Update-by-Learning-from-Single-Updated-Example)


# __Introduction and Motivation__ :
When we need to update we need to preserve backward compitibility when updating 
android applicationsto make sure that all applications are working under deprecation for this problem such approach we require an automate update in depricated API.

## _Research Methodology_: 

For this Purpose we will used Appevolve to automated android API update before and after-Updateand creating generic patches in this example some limitations in requires before and after update.API require manuall configuration for update .In the target file to be updated similar syntax,So due to two reasons so theywill decide to robust automated coccinelle and symantic patch for readable transformation coccinelle 4j recent java part for coccinelle j4 and programme matching for transformation tool that is used to add in their revolution to scanning coccevolve used to code normalization coccievolve requires single after update example.
#### Evalute the performance of coccievolve 
### __Experiment and App Evolve__: 
	The Evalution on 112 target files with 10 different API is accquired from github.

## _Results_:
The Aim of the Coccievolve which overcome the limitations of appevolve and code normalization mitigate syntatic differences,And requires a single after update.
for denormalization to remove the temporary variables. 
____
____
____
# Testing Of Mobile Application(2nd Research paper)
___
### Authors: Gemma Catoline,Filomena ferrcu Andrea de Luia,Fabio Palomba.
_______

# Introduction and Motivation:
_____
The millions of mobile apps on popular market places such as playstore and Apple Store so developing and delivering the apps to moving on strict process of requirements for developers to
maintain the staiblity in market success,So while research community has been focusing on testing but 
the solution is available but in for conducte the testing activity manually.
____
## Research Methodology:
For this purpose A Large Scale emperical study on the prominance quality and 
effectiveness so tests manually on a dataset of 1780 open source Android Applications.
### 1st step:
	Count the number of test classes and test methods.

### 2nd step:
	Classifying the tests according to their granularity.
## Results:
## 1st step:
	Test Suits 		Test Cases
	    0			    0
	   294			   3587
	   726			   5230
	    2			    4
	   2019			   21183
test suits 5292
Not tested App's:59%
## 2nd Step:
	500 test Classes
	Kr:0.92
	4795 test classes
	
# --> unit integration system
	Absolute 		Relation
	 3872			  73%
	 1273			  24%
	 147			   3%
_____
______
______
# Cheating Death(3rd Research Paper)
	(A statical survival analysis of publicaly available python projects)


## Authors: Rao Hamza Ali,Chelsea Parletpellipriti,Erik Linstead
Links:[Visit to Webpage](chrome-extension://oemmndcbldboiebfnladdacbdfmadadm/http://www1.chapman.edu/~linstead/aliMSR2020.pdf)

# _Introduction and Motivation_ :
For the analyzing software development process using everything from traditional statistics to deeplearning.Every healthy project needs a team of dedicated developers and a set line of goals and achievements,These projects alsi need to be popular enough to gain intrest from potential volunteers when developersare excited about the project and the end goals.
### Goals:
How it is possible to see a project has performed overtime the health of project could be computed the number of contribution.
How frequently big targets met by the developers?
How focused the team is on making the software ready for distribution?
## __Research Methodology__:
Developers work on this project as an volunteers.They wants to ensure their contributions do not go into a project that might endup inactive.

* Vc's(Version Control System) They used to host their projects.

* Having a project on multiple Vc's or repositories like PYPI and Debian Highlights.

* Survival analysis,Commonly used in medical studies to predict treatment efficiancy to find the probability of survival of popular open source projects overtime using kaplan-Meier survival analysis,and quantity the effects of these variables.

# _Results_:
following attributes of a project as estimators of survivalrate over time:
* MajorReleaseswhether:  releases  were  published  by  theproject developers
* HostTypetype of hosting service used for the project repos-itory
* AuthorCounttotal: unique developers that have committeda revision to the repository
* multipleRepositorieswhether: the project is hosted onmultiple version control systemsWe now discuss the results of running K-M curves and fittingCox Proporitional-Hazard models on the data