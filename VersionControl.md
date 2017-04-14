#Version Control#
##Keeping Track of Things##
###In The Animal Kingdom###
Charles Darwin was one of the greatest documenters of version control that biologists have ever seen. Understanding and documenting animals evolve over time and being one of the first to document changes between species is one of the most popular examples of documenting version control. There are finite reasons – for the most part – why animals evolve the way they do, such as switching bipedal in order to run farther, and in the case of the flying squirrel, growing loose skin helps it glide from tree to tree. Plants have also evolved over time, from being able to take in more or less water, to changes in size, plants also evolve for ensuing survival.

###Banks###
Banks need to have a version control system, as they deal with our money on a daily basis, and who has how much money. We all would not be happy if our banks could not determine how much cash we have in our accounts and how many accounts we have. Bank ledgers handle the transaction history, let the bank and user know how much money the users have, and when each transaction was made. Banks can measure a person’s wealth dependent on the time the money changes hands. Ledgers also help users claim fraud, as the user can say “No, I was not in Anchorage, AL this morning and then traveled back to Bloomington, IN two hours later.” This helps the user know when and where charges were charged to them, and with more and more digital records, this is done in nearly real-time.

###Hospitals###
Health Care is one of the most sued industries in the current market. Health Care professionals need version control, seemingly more than anyone else, in order to know to blame. Did someone err in the medication dosage, did someone kill a patient, or did some just participate in malpractice? Malpractice cases are about who was in error, and for that, the hospitals need accurate and detailed records of what medical professional did what to which patient. This way the patient, or their legal representative, will not sue the hospital itself but sue the doctor/nurse who was in error.


##3 Pieces: Who? What? When?##
###What was changed? ###
The main purpose of a changelog, a version control variant, it to see what was changed and the previous versions of the item that were changed. This could be something as simple as previous versions of a Word Document, previous versions of a file on Box or GitHub, or something more complex like medication dosage (which cannot be reverted back). Blueprints are great examples of this in the physical world, as we can see throughout time what aspects of the structure in question were changed and when they were changed. 

###When it was changed?###
Knowing when something was changed can affect the outcome of a project. If eBay takes off even one penny from every order it processes it, the time it has taken since implementation, will affect the scale of the loss for eBay. The longer the error is in place, the more money eBay will lose. They can see when they started making less and less money and cross-examine that when changes in their financial code were made to see exactly what change caused the error. The sooner an error is found, the less of an impact the party faces.

###Who changed it?###
In order to cover our own behinds, we must associate a person to the error itself. This may be one person, or a group of induvial, but in most circumstances there is always a person to blame. Even if someone is to blamed, this not always be a bad thing, as minor errors will more than likely not result in many repercussions for the erred party. If a doctor gives a patient too much / too little of a drug, or the wrong drug altogether, the hospital needs to know which doctor was in err. This way the hospital can prepare for either a lawsuit – for malpractice – or hand down consequences for the doctor.



##Risks##
Risks come from changes that occur within a system or within a protocol that people undergo. These changes occur with anyone working on a project or manager tasks or even stakeholders. Changes of any kind have the potential to be positive or negative. No matter what change that is being implemented, big or small, it causes risky situations in terms of negative or positive potential. When attempting to implement a change, it is always good practice to keep track of everything that you change and everything that happens due to the change. Although some risks are unavoidable, keeping track of more can mitigate some risks in the long term. For example, many organizations keep many different versions of past and present policies and precedures to allow their workers to know what changes were made to previous policies. This allows the workers to know exactly what was changed, how it was changed, and how this change differs from previous policy in other versions

## Real-World Examples of Version Control  ##
Indiana University use version control to mitigate many issues. One of these ways is through Bulletins such as IU Bulletins. The Bulletins help students keep track of the requirements for their degrees based on matriculation. Another examples is the Gradebook within Canvas that stores grades of assignments based on earliest due date. A third are papers written using Google Sheets or stored in a cloud storage service like Box keeps a history of each version. 

## Software (Code) ## 
Another way version control is used is for coding. Many organizations "have their open source projects on GitHub, including Google, Facebook, Twitter, and even Microsoft" (Ariel Zambelich). Smaller organzations also host their own projects on GitHub. 
__[Wired] (https://www.wired.com/2015/03/github-conquered-google-microsoft-everyone-else/)__

## History of Version Control ##
### Pre-Software ###
Before the invention of version control software, people maintained physical file systems containing carbon copies to record previous versions. Versioning is the process of accomplishment through creating a better draft of it. A common example is with textbooks which have numerous versions. Another is the Guisness Book of World Records which gets updated yearly. Through version control, one can see the changes made throughout history. 

## Manual Versioning (60s) ##
In the 1960s, organizations had Source Control Departments (SCD) to manage version control. A person would bring his code to the SCD and they would manually record versions of the code; They controlled the merging of code as well. The resources used by the SCD were neccessary but draining to organizations. 

## Source Control Management (SCM) ##
SCM was an important topic of conversation for people in the computer industry because they needed a more efficient method for tracking files when programming. Two developments of this were in 1972 when Source Code Control System (SCCS) released. Later in 1982, The Revision Control System (RCS) was released. The function of these programs were to record the most updated versions of files and any changes (deltas) made to the files. This utilitized storage much more effectively because firms were not required to store full versions with SCM only the deltas. Concurrent Versions Systems (CVS) in 1990 was able to manage multiple versions of a project. This was augmented through the use of servers. An issue with CVS was that it could track files singularly but not as part of a larger directory. CVS in 1994 accepted Transition Control Protocol (TCP) / Internet Protocol (IP) providing people the ability to telecommute. This allowed for one computer to access the files stored on another system. 

## Distributed Concurrent Version Systems (DCVS) ##
The release of Subversion in 2000 provided users the ability to fully track their commits. People could now submit changes to multiple files within the file system at one time marking the end of SCM. This introduced users to local repositories as well with fully operational branching and merging. Bitkeeper was also released publicly in 2000. Initially, it was considered proprietary software with some opportunity for free usage. There conflict with Linux eventually lead to their downfall and the creation of Git. Premiering in 2005, Git allowed distributed version control for all of its developers. 

##Git vs GitHub and Best Practices##
Git is the control system that users are in contact with when making changes to git code.  GitHub uses Git as the background software for the repositories to store a lot of information about software code.  GitHub is the location where the Git files are stored and shared among people throughout the world, companies, groups, or individuals. Some best practices with GitHub include: working at small tasks at a time, committing often to show significant changes to code, to provide useful comments when making commits to the repo, and to not panic when making the changes.  Another good practice when using GitHub is to be mindful of the files that are uploaded to GitHub.  In class there was discussion about using a gitignore file to stop the upload of certain files to be uploaded to GitHub.  These gitignore files can ignore certain files so they will not be uploaded to GitHub, which can be useful such as when creating C files that are being compiled and there are a lot of *.o files in the file folder. Some other good practices on GitHub include making sure the correct files are uploaded, callaborating among group members, and making sure that all the Git files are useful.

##References##
https://www.wired.com/2015/03/github-conquered-google-microsoft-everyone-else/
http://stackoverflow.com/questions/8527597/how-do-i-ignore-files-in-a-directory-in-git
https://git-scm.com/docs/gitignore


