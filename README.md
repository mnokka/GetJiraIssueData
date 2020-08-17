#GetIssueData

POC example, fetch given issue data (raw data using Python library)    
  
Same operation can be done using REST API via browser  
(https://JIRASERVER.fi/rest/api/2/issue/ISSUE-ID/)


** Usage: **

  -h, --help            show this help message and exit      
  -v                    Show version&author and exit  
  -w password           <JIRA password>    
  -u user               <JIRA user account>    
  -s server_address     <JIRA service>    
  -i jira_issue         <JIRA issue    

  


  ** EXAMPLES: **
  
    
     ChangeField.py  -u MYUSERNAME -w MYPASSWORD -s https://MYOWNJIRA.fi/  -i JIRAISSUE-ID  