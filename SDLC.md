# Software Development Life Cycles #

## What is an SDLC? ##
The acronym SDLC stands for Software Development Life Cycle or Systems Development Life Cycle. It is a representation of how a piece of software comes into fruition and how to sustain the software. There is no one correct methodology or process for a SDLC. However, aspects included in most SDLCs are requirements analysis, design, development, quality assurance, and release. 

## Requirements Analysis ##
This aspect involves gathering the specifications, parameters, or necessary features of the system. Basically, this means what will the system have to accomplish, how the system should accomplish these tasks and all the parts involved in completing a task. An understanding of the domain (industry) is needed to specify the requirements for that domain. 

### Steps of Requirement Analysis ###
The three parts of requirements analysis are Eliciting Requirements, Analyzing Requirements, and Recording Requirements.

### How to Gather them ###
Understanding the domain (industry) that the IS will be operating in is crucial to gathering the correct requirements of the IS. Using focus groups, surveys, informal chats, interviews, or observations are potential ways to gather such information. 

### Types of Requirements ###
#### Functional Requirements ####
An aspect of the the Requirements Analysis, the functional requirements are the necessary features collected. Functional Requirements do not specify how a task will be completed, rather it specifies the function, basic details about that function, and why the function is necessary. Each functional requirement is a distinct task that the Information System (IS) must be able to perform. 

#### Non-Functional Requirements ####
Another aspect of Requirements Analysis are the Non-Functional Requirements which explain how the system should perform a task. An example of this would be that the login which is a functional requirement must be done using password encryption which is the Non-Functional part. Non-Functional Requirements are also referred to as technical or operational requirements. 

#### Transitional Requirements ####
The third part of Functional Requirements involves the questions answered to prepare an IS for usage. These questions include who does it, how long it will take, do we need to perform data cleanup first, and how much training is needed. 

##Process of Requirements Analysis##

Requirements analysis can be an iterative process that can be broken down into three big steps. The first step includes eliciting requirements through means of interviewing, workshops, focus groups, brainstorming, observation, and surveys/questionnaires that focus on the needs and wants of stakeholders. Gathering requirements can become more complicated when you are not familiar with the domain, so the easiest way of gathering requirements is just to know what conditions to meet. The second step is analyzing requirements, which includes analyzing all of the information gathered from step one, and determining what needs and conditions need to be met within the new or altered product. The final step is recording all the requirements that the new product design will consider. Following this process right and thoroughly will save you a huge amount of time, stress, and a potential loss of respect. 
Embedding yourself in the organization or team can be beneficial in the process of gathering requirements, and you may come up with new questions that you would not have thought about before. Observing a team or organization, can also be beneficial to the requirement elicitation process, but you may have to dedicate more time and resources in doing so. 
Tacit knowledge is knowledge that is difficult to communicate to another person by means of writing it down or verbalizing it and therefore, it is not easily transferrable. Embedding yourself into a team or organization is a good tactic of accumulating tacit knowledge. This knowledge is important in the requirement elicitation process because really useful systems find ways to automate seemingly tacit tasks for their users, and this knowledge can be very useful in the future when making decisions about a system and how it will work. 

##SDLC Methodlolgys#
There are many different types of SDLC Methods, which are based into three categories: Linear, Iterative, and Combination. 

###Waterfall Method###
This is a very simple method, which is traditionally very methodical and step wise. The Waterfall Method goes from one step to another, and in 1970 Royce added an iterative feedback loop. This feedback loop allowed for teams to make corrections easier, usually jumping back one step; eventaully larger jumps back were introducted. Waterfall is great for low level or mission critical systems such as databses, security applications, and small projects. There is however, a high degree of risk for the Waterfall method which is why many orginizations do not use it for large projects. (March 21 Lecture)

##B-Model##
The B-Model is based off of the Waterfall Method, but it added a Maintenance Cycle. The B-Model is a bit more flexible when compared to Waterfall as the Maintenance Cycle allows for constant improvement while still piggy-backing off of the Waterfall method.

<p align="center">
 <img src = "https://www.researchgate.net/profile/Nayan_Ruparelia/publication/220631422/figure/fig2/AS:393982631792675@1470944187494/Figure-2-The-b-model-extends-the-waterfall-model-In-a-sense-the-b-model-was-an-attempt.png" width= "500" height = "500"/>
</p>

##V-Model##
The V-Model shaped the Waterfall Method in a different way, in the shape of a V, to illustrate procces change. On the Left side, decomposition and definition are shown. Whereas the Right side show integration and verification. The testing of the system can be planned in the left side and implemented in the right side of the model. This is better for large projects with many stakeholders and contributers. 

<p align="center">
<img src = "https://melsatar.files.wordpress.com/2012/03/v-shaped.png?w=584" width= "500" height = "500"/>
</p>

##Spiral Model##
The motto of the Spiral Model is "Start Small and Think Big", and for good reason. In the Spiral Model, the devolopers move around a center point and work "iterativly" towards a final project. Each lap of the spiral builds a prototype and moves fowards. This Model is very incremental and a large portion of repsonsibility is on the deisgner to identify and mitigate risks around each loop.

<p align="center">
 <img src = "https://www.automationlearn.com/s/cc_images/cache_4510850.png?t=1405454916" width= "500" height = "500"/>
</p>

#Agile#
Although not an SDLC, one should introduce Agile whenever talking about SDLCs. Agile is simply a set of principle that give an alternative to SDLC. Evolution of requirements and solutions, as the project moves along are the key to the Agile Method. In Agile, adaptive planning, ecolutionaly development, early delivery, and continious improvemts are a neccisity for a successful launch ([https://www.agilealliance.org/agile101/][Agile Alliance]).
When experts came together to create the Agile mthod, twelve principoles were discovered which would help the development of a project.
There twelve principles are:
		1. Early and Continuous Delivery
		2. Welcome changing requirements
		3. Deliver frequently/short timeframe
		4. Cross-functional team (Daily)
		5. Motivated individuals and supported teams
		6. Face-to-face conversations
		7. Working software is the only measure of success
		8. Maintain a constant pace indefinitely
		9. Attention to detail is important
		10. Simplicity
		11. Best things come from self-organizing teams
		12. Regular adjustments based on reflections
	
#References#
https://www.researchgate.net/profile/Nayan_Ruparelia/publication/220631422/figure/fig2/AS:393982631792675@1470944187494/Figure-2-The-b-model-extends-the-waterfall-model-In-a-sense-the-b-model-was-an-attempt.png

https://melsatar.files.wordpress.com/2012/03/v-shaped.png?w=584

https://www.automationlearn.com/s/cc_images/cache_4510850.png?t=1405454916

"What Is Agile Software Development?" Agile Alliance. N.p., 06 Feb. 2017. Web. 31 Mar. 2017. <https://www.agilealliance.org/agile101/>.
