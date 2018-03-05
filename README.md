# Hypo

Demo video link: https://youtu.be/WZh6M_jEC2c 

The platform's web user interface has three main parts:
*1. Reporting:* victims can report their experience and hsare with others. This reports are aggregated and later used to provide overall scores for organizations. Organizations can be companies, universities, etc. 

*2. Sharing/ Mentoring/finding helpful voice:* After reporting the victims can choose to share their detailed expereince with others, he or she can choose to select members of their own organizations only or to everyone. The default is only among their same organizations/ members who identify to be from teh same organizations.

*3. A details/ researched aggregated overview dashboard:* The system collects the anonymized data from the reports and create an overall aggregated dashboard to give people an overall picture of our work ment, when it comes to gender-based misconduct and sexual harassment. The dashboard has several components:

 ## Top: All Organizations-wide (Industry/Campus) overall trend: ##
 
- A stat in a pie chart showing who is usually responsible for the miscondust or harassment. This helps people/organization to understand where to focus their energy when it comes to mitigate the problem. 
- A tag cloud showing the most common words appearing in teh reports/stories.
- A bar chart shwoing if the HR/ authority is helpful enough to the victims. A score of 1 means not helpful 7 means very helpful. 

## Bottom: Grouped by organizations: ##
- Next we show all the reports grouped by different organizations. We have used random names for imaginary organizations. 
- A timeline view shows when the reports were filed, so we can at least see the accumulation of the reports, we also see that there is a pause of reports, may be at that time there were some social anti-harassment movement was hoing on and harassers were more cautious.
- We also show a total reports by each organizations. 

This visualizations can truly paint the big pictures while keeping the victims anonymous. We think this dashboard view should be accessible to all.

## GOAL ##
Many people do not even know their rights when it comes to speak up against harassment. We also nourish a culture of victim blaming and slut shaming. Some people feel ashamed, uncomfortable or may not even know if they are being used. We want to provide an environment where people can discuss and know their rights, knwo the concept of 'consent', that NO means NO, be vocal, be strong.  People would be able to share resources in this platform that are geared towards helping victims, may it be for legal purpose, metal health counselling, or mentoring. This way employees and students will know before hand about the situation of their work/study place, whom to contact in case of harassing incidents, how to find support groups, and support each other. The organizations will also be able to knwo from each other, how to create a beeetr environemnt for all .The organizations will be more careful in supporting the victims rather than saving the culprits if they have a public score and space that reveals their pattern. The better organizatiosn will get better employees and studnets. 

The menu has three options:
![alt text](https://github.com/awalin/hypo-master/blob/master/Screen%20Shot%202018-03-04%20at%204.06.11%20PM.png)

*Security/Privacy: Combined stat available for all, detailed comment only for the reporter. If the reporter seeks guidance he/she can choose to share their story with others from teh same organiztion. We did not implement the full access control for the hackathon, but the idea is it will be a safe space for people, they will get mental support, advice, learn about others' experience, and get string.*

## The Reporting Form: ##
  ![alt text](https://github.com/awalin/hypo-master/blob/master/input.png)
  
  ![alt text](https://github.com/awalin/hypo-master/blob/master/menu.png)

## The Stat page: ##
  ![alt text](https://github.com/awalin/hypo-master/blob/master/viz.png)
  
## The Comment/Sharing page: ##

 ![alt text](https://github.com/awalin/hypo-master/blob/master/comments.png)
 
 
 ## Technology ## 
 - D3 (for visualization), jQuery, Bootstrap, JS6 
 
  ## Form question for organizational safety: ##
	
  **  Did/ Do you feel unsafe in organization?If so, who is/was responsible for making you feel unsafe? (check all that apply)**
  
  - male peer
  - female peer
  - teacher/upper management
  - other
  	
  
  **Did you receive any of the following behaviors from any person in your organization? Check as many as applies to you.  Leave blank if none of them applies.**	
  
  - vulgar, explicit, harassing words against you in person, 
  - harassing comments regarding your physical appearance and clothing
  - vulgar, explicit, or threatening message in social media/online platform/cyber-space/email, 
  - encountered unwelcome displaying of sexual objects, pictures or other images, 
  - being cat-called by any campus-mate / eve-teasing by any campus-mate or someone from the organization
  - vulgar, explicit, or threatening message in text message
  
  **If you ever felt harassed by a person in your organization, who was the harasser?**
  
  - male peer
  - female peer
  - teacher/upper management
  - senior
  - other
  
  **Have you ever experienced any of the following harassments? Check all that apply. Leave blank if none of them applies.**
  
  -- sexual assault
  -- dating violence
  -- sexual exploitation
  -- rape
  -- Unwanted touch from any campus-mate of opposite sex
  -- other
  
 **Have you ever received telephone calls, voice messages, emails, texts, letters, notes, gifts, or any other communications that were undesired? And even after you told them not to they did not stop doing so?**	
  
 **Have you ever faced unwanted (and sometimes repeated even after being confronted) sexual advances from any of the following?**
 
  -- female peer/student
  -- male peer/student
  -- female teacher
  -- male teacher
  -- female boss/manager
  -- male boss/manager
  
 **If you chose any option in the previous question, did you seek any form of mental health counseling?**	
  
 **Did you or anyone you know ever complained to the authority about any harrasment?**
  
 **If so, how supportive and active were they regarding the complaint? 7 being very supportive and 1 being very unsupportive.**	
  
 **Do you know who to contact/complain within your organization if such a problem occurs?**	
  
 **If such a problem occurs who do you go to ask for help at first?**						
