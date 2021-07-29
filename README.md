# connectwise-manage-dashboards
A collection of Grafana dashboards and their SQL queries we have used to create a live operations dashboard for our ConnectWise Manage instance
![image](https://user-images.githubusercontent.com/36752644/127422514-2a93354a-1f28-434c-9738-bb0c91bc5ccf.png)

# Requirements
1. Various variables are used to personalise it to your MSP, see the first few lines of the JSONs for info
2. The Service Desk Unassigned tickets Urgency is based on the ticket urgency names being:
      * Priority 0 - MSP 
      * Priority 1 - Critical 
      * Priority 2 - High 
      * Priority 3 - Medium 
      * Priority 4 - Low 
      * Priority 5 - No SLA \
  As it bases the formatting off of the constant position of the number - you may need to adpat this SQL query for your own urgency names.
  3. Board names used are "Triage" and "Support", these will need to be changed manually in the queries if this does not match the names of boards you use.
