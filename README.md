# JiraAutomations
Scripts for Jira Script Runner facilitating the use of the tool with practical automations

## scriptJiraCalculateTotalTimeSpentBySubTasks
A script to add on Jira Script Runner "Script Listener" with method "Worklog Created" and "Worklog Updated" to set on a custom field like "Total Time Spent" the total time calculated automatically by time spent registered on subtasks.

## scriptJiraCalculateTotalTimeSpentByFields
A script to add on Jira Script Runner "Script Listener" with method "Issue Updated" to set on a custom field like "Total Time Spent" the total time calculated automatically  by specific custom fields of your issue (task).

## scriptJiraCreateSubTaks
A script to add on Jira Script Runner "Script Listener" with method "Issue Created" to automatically create each subtask required for the task after it creation.

## scriptJiraCopyIssueToOtherProject
A script to add on Jira Script Runner "Script Listener" with method "Issue Updated" to create automatically an issue with same summary (name) and type when it reaches specific status on project.

## scriptJiraSendCommentForSlack
A script to add on Jira Script Runner "Script Listener" with method "Comment Created" to send automatically a message on Slack when a comment is made on task with the comment author and content to user with identifier on task label 


/**Gabriel Tessarini**/
