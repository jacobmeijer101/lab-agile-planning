# lab-agile-planning
Training and lab.
Need a service that has a counter	As a user, I need a service that has a counter so that I can keep track of how many times something has been done.	- A single counter can be created. - The counter value increases by 1 when triggered. - Counter value is displayed to the user.
Must allow multiple counters	As a user, I need to have multiple counters so that I can keep track of several counts at once.	- User can create multiple named counters. - Each counter maintains its own count independently. - User can view all counters in a list.
Must persist counter across restarts	As a service provider, I need the service to persist the last known count so that users don’t lose track after the service is restarted.	- Counter values are saved to storage automatically. - When service restarts, counters restore to last saved values.
Counters can be reset	As a system administrator, I need the ability to reset the counter so that I can redo counting from the start.	- Reset button or command is available for each counter. - Reset sets counter value to zero without deleting the counter.
Deploy service to the cloud	As a developer, I need the service deployed to the cloud so that it’s accessible from anywhere.	- The service runs on a public cloud platform (AWS, Azure, GCP, etc.). - The URL or endpoint is accessible publicly.
Need the ability to remove a counter	As a user, I need the ability to remove a counter so that I can delete counters I no longer need.	- User can delete a counter by name or ID. - Deleted counters are removed from storage permanently
