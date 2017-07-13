KRSP GitHub Guidelines

Introduction

Hi, welcome to the Kluane Red Squirrel Project GitHub page! This is a place for us all to share and improve each other’s code (primarily R, but perhaps other things as well), as well as document who did what and therefore who should get credit.
This little document is just to set out how we hope this resource is used. It includes general instructions for use, a very simple style guide and then recommendations for the use and attribution of code. This is meant to be a fluid document, so if there is anything you think should be changed, open a pull request (see the GitHub tutorial if you haven’t already) and then we can put it into action.
If you have not already, we highly recommend you take the quick GitHub tutorial. This will get you familiar with repositories, pull requests and other elements of this platform. We appreciate that this may feel like yet another thing one needs to learn to conduct science, alongside R, referencing software, statistics, etc.. But practically this can simply serve as a place to deposit all the KRSP R code, without any more in depth involvement required. It should be better than DropBox or Google Drive for this kind of thing as its explicitly designed for this purpose, and won’t eat up your precious storage space.

Instructions for use

At the moment the KRSP repository is arranged into a series of repositories or projects. These will (as they get populated) fit into three broad categories.
1.	Specific people’s project code. These repositories will be uploaded by individuals, clearly titled to include their name, and contain various pieces of code that they are using towards a particular goal.
2.	Example analyses. These repositories will serve as guidelines for how to conduct a certain analysis. For instance, if you wish to assess the level of genetic variance in a trait, you can open up the “Animal model  in MCMCglmm” file. 
3.	Useful pieces of code. This is a more general repository for various pieces of code not necessarily relate to any analyses in squirrels. Code placed here may instead show how to do use certain packages, plot particular types of data, access certain online resources etc.

Each of these categories can be handled in roughly the same way. You can open any of them, see the code and copy it for your own use. You do NOT directly edit any of the files unless you authored it.
If you wish to edit a code file, or adapt an existing one to a different purpose, you instead submit a pull request. This creates the edits in a new file, branching off the original (the “master”). You will briefly describe the edits you have made in the appropriate places on GitHub. The author of the code can then look at your pull request. They may accept it, in which case your edits are merged with the master code, and the branch is removed. Alternatively, they may leave your edits as a branch off the master code. We envisage this will be common. The code with then be represented as “ABC wrote this to do X, DEF edited it in this way to do Y”. This keeps it clear who did what, when and why.

We hope that everyone will be happy to upload their code to GitHub, and to start using the existing code of others for their own projects. We should be more efficient this way by avoiding the duplication of effort, as well as opening up new possibilities based on the application of code between different fields.

Style Guide

At the moment we have no strong suggestions for how code files should look. 
They should be clearly titled and labelled so that the author and the purpose of the code are obvious. 
Within the code, subheadings are encouraged, and annotations are essential.
Code is generally more legible 
if it does not extend over 30
characters per line  #although obviously exceptions exist

Hopefully by using each other’s code we will converge on a shared style. Expect to see this section updated over time as we start to use each other’s code, and differences in style become more apparent.

Attribution, acknowledgement and authorship

Thanks to the way code is placed and edited on GitHub, we should be able to attribute ownership quite easily to the originator, and edits to the editor. 
At the least, if you use someone else’s code for an analysis that ends up in a publication, they should feature in the acknowledgements. However, if their contribution meant some element of the paper happened that would otherwise not have happened, then perhaps this should grant the contributor authorship on the paper.
Note this does not necessarily mean that using anyone’s code to streamline your own, or get you started in a particular area, grants them authorship rights. Ideally, it should be clear due to a dialogue that lead to the developing of the code for a particular purpose that the coder contributed intellectually to the body of work, and so authorship is appropriate. We think it very unlikely that someone will qualify for authorship if they have not been in email contact during the analysis and write-up stages, as this suggests they were not involved in the project to any great degree.
If you wish to add your own stipulations about what using your code means when you upload it, feel free to do so, although it would probably be better if the same framework was used by all.






