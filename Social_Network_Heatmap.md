# Social Network Heatmap
  
The purpose of the social network heatmap is to:
1. Demonstrate visually how employees are connected to one another in the organizational network.
2. Display the unique characteristics of employees, as derived from the orginizational network.
  
This visualization and accompanying data-sets are derived solely from Mod1 of the Kojuba Workplace Survey. This means that the insights demonstrated here only required 15 min of employee time.  
  
### Application Login
To login, go here: https://demo1.kojuba.com/  
If you have any questions, email: questions@kojuba.com  
  
### Performance Tips
1. Chrome is the preferred browser for Kojuba apps. Other browsers may produce a different experience. 
2. The smoothness of the visualization will depend on the RAM your computer has available. So if you have a thousand tabs open in Chrome, it will hurt the performance of the visualization.
2. Your browser window may need to be increased or decreased for optimal experience. On PCs, this is done using Ctrl+"+" or Ctrl+"-". On Macs, use Cmd+"+" or Cmd+"-" to tune the size.

### Functionality / Features
- Hover over a node to see the employee's name. (Demo network is simulated with fake names.)
- Pan and Zoom the frame to focus on certain parts of the orginizational network.
- Search for a person using the search box, with first or last name.
- Drag nodes around to better understand the network.

### Interpreting HeatMap Colors & Values
The colors of the heatmap represents the degree to which a person exhibits a characteristic. This is based on the "Relative-Refference Score" that an employee has for a given variable or dimension. For example, when "INFO" is selected, the large, bright-GREEN circles represent the people who are HIGHLY referenced as being sources of information by other people in the network. 
  
In contrast, if you see a large RED circle, this represents a significant absense of refference for this dimension. It would mean that while a person is very integrated into the company, they are not relied opon for information. It is likely that they contribute to the company in other ways. 
  
This highlights an important point. By nature, some people will be VERY integrated in an organization and others may barely have a presense. This difference is influenced by at least 5 factors:  
1. an employee's time in the company
1. how may hours a person works per week
1. a person's level of authority
1. the size of the team they are asigned to
1. how extroverted a person is
  
If we want to understand the unique characteristics of individual employees in a way where we can compare them to each other, (and not penalize a person for factors outside thier control), we must extract the effect of overall social integration from the scoring system. Therefore, Relative Refference Scores can be viewed as the difference between a person's expected degree of reference and actual degree of reference for a particular variable.
  
### Settings
The default settings use the "Proximity Network" as the mode and the "Information" attribute as the nodal property. There are 2 different networks types that can be visualized and 13 different attributes that can be displayed over the network. The different variables are described in below.  
  
### Network Types (Mode Drop-Down)
```
PROXIMITY NETWORK
    This visualization is great for analyzing the TEAMS of a company.
    Displays the links between people where there is strong social proximity.
    This means that 2 people are connected if they interact with eachother often.
    Possible Questions:
        What teams does your company consist of? 
        Who are the central members of these teams?
        Who are the people that connect teams?
        How are teams connected to one another or separated from one another? 
	Who are the centers of information within a team?
	Who are the centers of positivity within a team?
	Who are the "hidden assets" (HIDD) of an organization?
	Where are those people located?
    
AUTHORITY NETWORK
    This visualization is great for analyzing the LEADERS of a company. 
    Displays the links between people where there is a strong authority relationship.
    This requires high proximity between people AND a major difference in authority.
    These are the estimated direct-reporting relationships.
    Possible Questions: 
    	How many people report to each leader?
	Does informal leadership (LEAD) align whith the formal authority structure?
	Among those with minimal authority, who is seen as a potential good leader?  
	Are certain leaders known for thier positivity and some for thier negativity?
	Which leaders are "informational leaders" and which are "relational leaders"? 
	Should certain leaders be more open to recieving feedback from others?
```	


### Variable Types (Property Drop-Down)  
```
INFO - Information:   How often is a person relied on for information from others?  
CONV - Conversation:  How easy is it to have informal conversations with a person?  
INNO - Innovation:    Is a person regarded as a source of new and creative ideas?  
PROT - Protection:    How likely is a person to defend another who is being treated unfairly?  
COLA - Collaboration: How often do people collaborate with this person to solve problems?  
CONF - Confidant:     How safe do people feel sharing sensitive information with this person?  
INSP - Inspiration:   Is this person seen as a source of inspiration to employees of the company?  
LONE - Lone Wolf:     Should this person be more open to recieving feedback and help from others?  
HIDD - Hidden Asset:  Is this person undervalued relative to thier total contributions to the company?  
ACES - Access Needed: Do employees need more access to this person to do thier work?  
POSI - Positivity:    Does this person contribute to the positive experience of others in the company?  
NEGA - Negativity:    Does this person contribute to the negative experience of others in the company?  
LEAD - Leadership:    Is this person likely to be viewed as a good leader, regardless of authority?  
```
  
  
  
[END]
