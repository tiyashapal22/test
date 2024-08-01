# Reports
**Table of Content**
- [Backup Executive Summary](#backup-executive-summary--99)
- [Job Status Summary](#job-status-summary--100)
- [Job Summary](#job-summary--150)
- [Job Volume Summary](#job-volume-summary--200)
- [Job Type Count](#job-type-count--210)
- [Job Error Code](#job-error-code--220)
- [Job Duration](#job-duration--300)
- [Error Log Summary by Server](#error-log-summary-by-server--400)
- [Error Log Summary](#error-log-summary--410)
- [Error Log Summary by Policy](#error-log-summary-by-policy--420)
- [Consecutive Errors](#consecutive-errors--500)
- [Largest Backup Volume](#largest-backup-volume--550)
- [Monthly Backup Summary](#monthly-backup-summary--700)
- [Job Summary by Server](#job-summary-by-server--800)
- [Running and Queued Job Summary](#running-and-queued-job-summary--900)
- [HP DP Session Summary](#hp-dp-session-summary--901)
- [Data Domain Backup Summary](#data-domain-backup-summary--905)
- [NetBackup SLP Status](#netbackup-slp-status--906)
- [Data Domain File Compression Summary](#data-domain-file-compression-summary--907)
- [Data Domain File Compression Detail](#data-domain-file-compression-detail--908)
- [AWS EC2 Snapshot](#aws-ec2-snapshot--909)
- [AWS EC2 Snapshot Detail](#aws-ec2-snapshot-detail--910)
- [Job Summary By Source](#job-summary-by-source--911)
- [Job Duration By Source](#job-duration-by-source--912)
- [Primary Server Job Throughput](#primary-server-job-throughput--913)
- [NetBackup Media Server Job Throughput](#netbackup-media-server-job-throughput--914)
- [Source Backup Count Summary](#source-backup-count-summary--915)
- [NetBackup SLP Status by SLP](#netbackup-slp-status-by-slp--916)
- [NBU AIR Replication Import Jobs](#nbu-air-replication-import-jobs--917)
- [NetBackup Deduplication to MSDP Savings - By Clients](#netbackup-deduplication-to-msdp-savings---by-clients--918)
- [NetBackup Deduplication to MSDP Savings - By Primary Servers](#netbackup-deduplication-to-msdp-savings---by-primary-servers--919)
- [NetBackup Deduplication to MSDP Savings - By Policy Type](#netbackup-deduplication-to-msdp-savings---by-policy-type--920)
- [NetBackup Deduplication to MSDP Savings Trend Over Time](#netbackup-deduplication-to-msdp-savings-trend-over-time--921)
- [Job Throughput by Client](#job-throughput-by-client--922)
- [Anomalies Summary](#anomalies-summary--925)
- [NetBackup SLP Status by Client](#netbackup-slp-status-by-client--929)
- [NetBackup SLP Status by Image Copy](#netbackup-slp-status-by-image-copy--930)
- [Job Status Summary by Client](#job-status-summary-by-client--931)
- [Ransomware Risk Assessment Dashboard](#ransomware-risk-assessment-dashboard--1000)
- [Operations Dashboard](#operations-dashboard--1001)
- [Alerts Dashboard](#alerts-dashboard--1002)
- [Storage Optimization Dashboard](#storage-optimization-dashboard--1003)
- [Backup Server Performance Dashboard](#backup-server-performance-dashboard--1004)
- [NetBackup Deduplication to MSDP Savings Dashboard ](#netbackup-deduplication-to-msdp-savings-dashboard---1006)
- [Azure Cloud Cost Spend Dashboard](#azure-cloud-cost-spend-dashboard--1007)
- [Command Center Dashboard](#command-center-dashboard--1101)
- [Data Protection Dashboard](#data-protection-dashboard--1201)
- [Mission Control - Backup](#mission-control---backup--1301)
- [IBM Spectrum Protect (TSM) Storage Pools Dashboard](#ibm-spectrum-protect-tsm-storage-pools-dashboard--1501)
- [Job Histogram](#job-histogram--1601)
- [NetBackup Audit Report](#netbackup-audit-report--1602)
- [NetBackup Event Notification Summary - CRITICAL](#netbackup-event-notification-summary---critical--1603)
- [Avamar Grid Capacity Dashboard](#avamar-grid-capacity-dashboard--1610)
- [Data Domain Replication History](#data-domain-replication-history--1620)
- [Data Domain Snapshot History](#data-domain-snapshot-history--1630)
## Backup Executive Summary (99)
### Report Short Description
`View a client and job overview by backup window.`
### Information 
    Last Updaated  : 29 April, 2024
    Avg Execution Time(recent) : 00 Hours: 00 Minutes: 09 Seconds
    Max Execution Time(recent) : 00 Hours: 03 Minutes: 18 Seconds
### Report Long Description
	- This report provides an Executive Summary overview of the status of backup jobs within defined backup windows.
	- Select a backup window to narrow the scope of the report.
	- This report is equivalent to the following NetBackup OpsCenter report(s): Job Count within Backup Window.## Job Status Summary (100)
### Report Short Description
`Aggregates jobs that succeed, fail, or produce warning messages for each time period.`
### Information 
    Last Updaated  : 29 April, 2024
    Avg Execution Time(recent) : 00 Hours: 00 Minutes: 14 Seconds
    Max Execution Time(recent) : 00 Hours: 05 Minutes: 30 Seconds
### Report Long Description
	- Provides drill-down access to the Job Summary report, where you'll find specific status messages and scheduling information.
	- When you generate this report, several scoping options enable you to narrow the report and also to define how the data is displayed.
	- This report is equivalent to the following NetBackup OpsCenter report(s): Failed Job Count, Job Status, Partially Successful Job Count, Successful Job Count## Job Summary (150)
### Report Short Description
`View details related to the data represented in the bars shown in the Job Status Summary chart.`
### Information 
    Last Updaated  : 29 April, 2024
    Avg Execution Time(recent) : 00 Hours: 00 Minutes: 38 Seconds
    Max Execution Time(recent) : 01 Hours: 00 Minutes: 07 Seconds
### Report Long Description
	- When you generate this report, several options enable you to narrow the scope of the report and also to define how the data will be displayed.
	- This report is equivalent to the following NetBackup OpsCenter report(s): All Failed Backups, Backup Window Failures, Client Restore, Job Details, Job Size, Partially Successful Job Details, Restore Job Details## Job Volume Summary (200)
### Report Short Description
`Represents "how much" data has been backed up each day. You can use the information to ascertain problematic time periods, consumption trends, and scheduling peaks.`
### Information 
    Last Updaated  : 29 April, 2024
    Avg Execution Time(recent) : 00 Hours: 00 Minutes: 13 Seconds
    Max Execution Time(recent) : 00 Hours: 05 Minutes: 50 Seconds
### Report Long Description
	- The report shows the number of files and amount of data (in KB) backed up for a specified time period.
	-  This helps to determine if your scheduling is balanced.## Job Type Count (210)
### Report Short Description
`This donut chart represents the count of each job type, with drilldowns to the Job Summary.`
### Information 
    Last Updaated  : 29 April, 2024
    Avg Execution Time(recent) : 00 Hours: 00 Minutes: 02 Seconds
    Max Execution Time(recent) : 00 Hours: 00 Minutes: 05 Seconds
### Report Long Description
	- Use this chart for a high-level view of backup jobs, with access to the relevant details.
	- This report is equivalent to the following NetBackup OpsCenter report(s): Job Count, Restore Job Attempt Summary by Job Count, Restore Job Attempt Summary by Volume Restored.## Job Error Code (220)
### Report Short Description
`Use this chart for a high-level view of backup errors by error code. Click a sector to view the Job Summary report for a specific error code.`
### Information 
    Last Updaated  : 29 April, 2024
    Avg Execution Time(recent) : No Data Available
    Max Execution Time(recent) : No Data Available
### Report Long Description
	- Each donut sector represents an error code with the number of error occurrences shown in a tooltip in the following format.
	- The total count of all errors is displayed in the center of the donut.## Job Duration (300)
### Report Short Description
`Represent job duration for backup and restore jobs.`
### Information 
    Last Updaated  : 29 April, 2024
    Avg Execution Time(recent) : 00 Hours: 00 Minutes: 02 Seconds
    Max Execution Time(recent) : 00 Hours: 00 Minutes: 03 Seconds
### Report Long Description
	- The report combines into one view, information about both backup and restore duration.
	- If, on a specific day, there were two backup events that completed after one hour and three hours respectively, and one restore completed after .5 hours, the bar reports a duration of 4.5 hours. You can also report on a single event type: * All Backup Events * Full Backups * Incremental Backups *Restores## Error Log Summary by Server (400)
### Report Short Description
`View a tabular report that lists backup failure details gleaned from backup error logs.`
### Information 
    Last Updaated  : 29 April, 2024
    Avg Execution Time(recent) : 00 Hours: 00 Minutes: 07 Seconds
    Max Execution Time(recent) : 00 Hours: 00 Minutes: 22 Seconds
### Report Long Description
	- Use this report in conjunction with the Consecutive Errors By Client report to mitigate future problems by determining which types of errors occurred with the greatest frequency. You can also run Error Log Summary or Error Log Summary by Policy for similar data grouped on different attributes.## Error Log Summary (410)
### Report Short Description
`View a tabular report that lists backup failure details gleaned from backup error logs.`
### Information 
    Last Updaated  : 29 April, 2024
    Avg Execution Time(recent) : 00 Hours: 00 Minutes: 04 Seconds
    Max Execution Time(recent) : 00 Hours: 00 Minutes: 04 Seconds
### Report Long Description
	- Use this report in conjunction with the Consecutive Errors report to mitigate future problems by determining which types of errors occurred with the greatest frequency. You can also run Error Log Summary by Server or Error Log Summary by Policy for similar data grouped on different attributes.## Error Log Summary by Policy (420)
### Report Short Description
`View a tabular report that lists backup failure details gleaned from backup error logs.`
### Information 
    Last Updaated  : 29 April, 2024
    Avg Execution Time(recent) : No Data Available
    Max Execution Time(recent) : No Data Available
### Report Long Description
	- Use this report in conjunction with the Consecutive Errors report to mitigate future problems by determining which types of errors occurred with the greatest frequency. You can also run Error Log Summary by Server or Error Log Summary for similar data grouped on different attributes.## Consecutive Errors (500)
### Report Short Description
`Lists consecutive backup errors for consecutive days.`
### Information 
    Last Updaated  : 29 April, 2024
    Avg Execution Time(recent) : 00 Hours: 00 Minutes: 49 Seconds
    Max Execution Time(recent) : 01 Hours: 00 Minutes: 40 Seconds
### Report Long Description
	- Use this report to proactively manage clients and servers.
	- Consecutive errors may portend hardware reliability issues.
	- Using this report you can identify not only consecutive errors, but also the number of consecutive days that the errors persisted.
	- The default order for this listing is descending order, with the clients having the most consecutive errors listed first.
	- Correlate the number of consecutive errors with the number of consecutive days so that you can disregard errors that appear to be intermittent.
	- This report is equivalent to the following NetBackup OpsCenter report(s): Consecutives Failures Report.## Largest Backup Volume (550)
### Report Short Description
`Displays a pie chart representing a snapshot of the largest server backup consumers.`
### Information 
    Last Updaated  : 29 April, 2024
    Avg Execution Time(recent) : 00 Hours: 00 Minutes: 30 Seconds
    Max Execution Time(recent) : 00 Hours: 04 Minutes: 37 Seconds
### Report Long Description
	- Use this report to identify consumers of your most utilized backup volume.
	- A pie chart graphically represents the usage that also is listed in the legend.
	- This report will help you identify greedy hosts or applications.
	- This report is equivalent to the following NetBackup OpsCenter report(s): Top 10 Policies Using most Server Space.## Monthly Backup Summary (700)
### Report Short Description
`Displays the monthly summary for backup.`
### Information 
    Last Updaated  : 29 April, 2024
    Avg Execution Time(recent) : 00 Hours: 00 Minutes: 05 Seconds
    Max Execution Time(recent) : 00 Hours: 00 Minutes: 58 Seconds
### Report Long Description
	- When selecting the scope for this report, choose Include Primary Servers.
	- If you run the report on the Primary Servers instead of clients, you can avoid having duplicate jobs in the list, if a client is backed up by two Primary Servers.## Job Summary by Server (800)
### Report Short Description
`Provides the number of backup jobs and their status: running, queued, warnings, errors.`
### Information 
    Last Updaated  : 29 April, 2024
    Avg Execution Time(recent) : 00 Hours: 00 Minutes: 04 Seconds
    Max Execution Time(recent) : 00 Hours: 00 Minutes: 08 Seconds
### Report Long Description
	- This report displays the number of jobs and their status, for jobs started during the time period that you specified for the report. Only Veritas NetBackup, EMC NetWorker and CommVault Simpana jobs are listed in this report.
	- Correlate the data in this report with the information in the Real Time Library and Drive Status to determine if there are problems with the server. For example, if the Job Summary by Server shows jobs in the queue and the Real Time Library and Drive Status shows available drives, something is preventing the queued jobs from getting to running status.## Running and Queued Job Summary (900)
### Report Short Description
`Displays any job that was running or queued at the time the management servers were polled.`
### Information 
    Last Updaated  : 29 April, 2024
    Avg Execution Time(recent) : 00 Hours: 01 Minutes: 03 Seconds
    Max Execution Time(recent) : 00 Hours: 03 Minutes: 24 Seconds
### Report Long Description
	- Only Veritas NetBackup and EMC NetWorker jobs will be listed in this report.
	- For NetWorker, this report is titled, Running Save Sets Summary.
	- Jobs that require attention (long-running, stalled, or slow jobs) will be highlighted in red and moved to the top of the running and queued jobs list so that they are quickly noted by administrators and handled appropriately.
	- Each of these flagged jobs will be accompanied by one or more icons to indicate the type of potential problem.## HP DP Session Summary (901)
### Report Short Description
`Displays an HP Data Protector backup/restore session summary.`
### Information 
    Last Updaated  : 29 April, 2024
    Avg Execution Time(recent) : 00 Hours: 00 Minutes: 06 Seconds
    Max Execution Time(recent) : 00 Hours: 00 Minutes: 24 Seconds
### Report Long Description
	- This report lists HP Data Protector sessions, with drilldown access to session details.
	- A list of tapes provides drilldown access to the Tape Media Detail report.## Data Domain Backup Summary (905)
### Report Short Description
`Lists the NetBackup systems that have client backup data.`
### Information 
    Last Updaated  : 29 April, 2024
    Avg Execution Time(recent) : 00 Hours: 00 Minutes: 29 Seconds
    Max Execution Time(recent) : 00 Hours: 02 Minutes: 19 Seconds
### Report Long Description
	- The Data Domain system acts as an external disk pool.
	- Note that LSU (logical storage unit) data is collected every six hours.## NetBackup SLP Status (906)
### Report Short Description
`Lists the Storage Lifecycle Policy (SLP) status for NetBackup jobs, which can be used as an
overview of the health of the SLPs for each NetBackup primary server.`
### Information 
    Last Updaated  : 29 April, 2024
    Avg Execution Time(recent) : 00 Hours: 00 Minutes: 22 Seconds
    Max Execution Time(recent) : 00 Hours: 03 Minutes: 31 Seconds
### Report Long Description
	- Using this report's completion statistics, you can determine if the SLP is performing according to schedule, if additional copies have been made, and also if the backlog is increasing.
	- These statistics enable you to identify issues associated with the processing of SLPs.
	- This report is equivalent to the following NetBackup OpsCenter report(s): SLP Status.## Data Domain File Compression Summary (907)
### Report Short Description
`View Data Domain file pre and post compression values summarized for a client, with aggregated rates.`
### Information 
    Last Updaated  : 29 April, 2024
    Avg Execution Time(recent) : 00 Hours: 00 Minutes: 21 Seconds
    Max Execution Time(recent) : 00 Hours: 05 Minutes: 23 Seconds
### Report Long Description
	- This information can be instrumental in determining efficient storage strategies and identifying storage that can be reclaimed, thereby reducing archive storage expenses.
	- This data can be used to identify clients within efficient de-duplication ratios, highlighting where de-deduplication is not an effective approach for certain backed-up files.
	- For example, some clients may be running database applications that are constantly producing unique bits of data.
	- These clients can consume much of the expensive Data Domain storage.
	- Data Domain collection now can identify the largest offenders, which can then be moved to less expensive storage to avoid paying premium rates for de-duplication.
	- Configure EMC Data Domain collection to capture image-level compression rates.
	- Aggregated global and local compression rates for all backup images can be collected for all active Data Domain Server MTrees connected (via DDBOOST) to Primary Servers.## Data Domain File Compression Detail (908)
### Report Short Description
`View Data Domain file values both pre and post compression.`
### Information 
    Last Updaated  : 29 April, 2024
    Avg Execution Time(recent) : 00 Hours: 03 Minutes: 06 Seconds
    Max Execution Time(recent) : 00 Hours: 40 Minutes: 29 Seconds
### Report Long Description
	- This information can be instrumental in determining efficient storage strategies and identifying storage that can be reclaimed, thereby reducing archive storage expenses.
	- This data can be used to identify clients with inefficient de-duplication ratios, highlighting where de-deduplication is not an effective approach for certain backed-up files.
	- For example, some clients may be running database applications that are constantly producing unique bits of data.
	- These clients can consume much of the expensive Data Domain storage.
	- Data Domain collection now can identify the largest offenders, which can then be moved to less expensive storage to avoid paying premium rates for de-duplication.
	- Configure EMC Data Domain collection to capture image-level compression rates.
	- Aggregated global and local compression rates for all backup images can be collected for all active Data Domain Server MTrees connected (via DDBOOST) to Primary Servers.## AWS EC2 Snapshot (909)
### Report Short Description
`Displays Amazon Web Services (AWS) EC2 instances with the status of snapshot backups`
### Information 
    Last Updaated  : 29 April, 2024
    Avg Execution Time(recent) : No Data Available
    Max Execution Time(recent) : No Data Available
### Report Long Description
	- Displays Amazon Web Services (AWS) EC2 instances with color coded statuses, dates and sizes of snapshot backups allowing for a quick assessment.
	- Drill down to AWS EC2 Snapshot Detail from the Total Snaps value.## AWS EC2 Snapshot Detail (910)
### Report Short Description
`Displays Amazon Web Services (AWS) EC2 instance snapshot backup details including volume info, snapshot dates and sizes.`
### Information 
    Last Updaated  : 29 April, 2024
    Avg Execution Time(recent) : No Data Available
    Max Execution Time(recent) : No Data Available
### Report Long Description
	- Displays Amazon Web Services (AWS) EC2 instance snapshot backup details including volume info, snapshot dates and sizes.
	- This is available from the menu directly and as a drill down in the AWS EC2 Snapshot report.## Job Summary By Source (911)
### Report Short Description
`This report shows the job summary with the rate of success by source.`
### Information 
    Last Updaated  : 29 April, 2024
    Avg Execution Time(recent) : No Data Available
    Max Execution Time(recent) : No Data Available
### Report Long Description
	- Shows totals for successful, partially successful, and failed jobs for each source.
	- Drilldown on sources, hosts and objects to show details.
	- This report is equivalent to the following NetBackup OpsCenter report(s): Advanced Success Rate, Success Rate - All Attempts, Success Rate - All Jobs, Success Rate Line.## Job Duration By Source (912)
### Report Short Description
`Use this report to view the total duration of backup and restore jobs sorted by Source for a specific period of time.`
### Information 
    Last Updaated  : 29 April, 2024
    Avg Execution Time(recent) : No Data Available
    Max Execution Time(recent) : No Data Available
### Report Long Description
	- This report can also be filtered on vendor job types and backup/restore event types.## Primary Server Job Throughput (913)
### Report Short Description
`Use this report as a tool to compare performance of various primary servers.`
### Information 
    Last Updaated  : 29 April, 2024
    Avg Execution Time(recent) : No Data Available
    Max Execution Time(recent) : No Data Available
### Report Long Description
	- Use this report as a tool to compare performance of various primary servers.
	- This report displays throughput and job success information for each primary server.
	- It shows job count and job success rate, and enables you to compare throughputs of different servers to identify any poorly performing servers.
	- This report is equivalent to the following NetBackup OpsCenter report(s): Master Server Job Throughput.## NetBackup Media Server Job Throughput (914)
### Report Short Description
`Provides details of data that is backed up by NetBackup media servers and shows server throughput.`
### Information 
    Last Updaated  : 29 April, 2024
    Avg Execution Time(recent) : 00 Hours: 00 Minutes: 06 Seconds
    Max Execution Time(recent) : 00 Hours: 00 Minutes: 06 Seconds
### Report Long Description
	- Provides details of data that is backed up by NetBackup media servers and shows server throughput.
	- The report is a useful tool to compare performance of the media servers that are present in your Veritas NetBackup environment.
	- This report is equivalent to the following NetBackup OpsCenter report(s): Media Server Job Throughput.## Source Backup Count Summary (915)
### Report Short Description
`This report provides a count of the backup sources (clients/objects) across products.`
### Information 
    Last Updaated  : 29 April, 2024
    Avg Execution Time(recent) : 00 Hours: 00 Minutes: 05 Seconds
    Max Execution Time(recent) : 00 Hours: 00 Minutes: 05 Seconds
### Report Long Description
	- This report provides a counts of backup source (client/object) counts across products.
	- It displays how many clients/objects are actually being backed up.## NetBackup SLP Status by SLP (916)
### Report Short Description
`Lists the Storage Lifecycle Policy (SLP) status for NetBackup jobs by SLP, which can be used as an overview of the health of the SLPs for each NetBackup primary server.`
### Information 
    Last Updaated  : 29 April, 2024
    Avg Execution Time(recent) : 00 Hours: 00 Minutes: 03 Seconds
    Max Execution Time(recent) : 00 Hours: 00 Minutes: 03 Seconds
### Report Long Description
	- Using this report's completion statistics, you can determine if the SLP is performing according to schedule, if additional copies have been made, and also if the backlog is increasing.
	- These statistics enable you to identify issues associated with the processing of SLPs.
	- This report is equivalent to the following NetBackup OpsCenter report(s): SLP Status.## NBU AIR Replication Import Jobs (917)
### Report Short Description
`Provides details about NBU AIR Replication Import Jobs`
### Information 
    Last Updaated  : 29 April, 2024
    Avg Execution Time(recent) : No Data Available
    Max Execution Time(recent) : No Data Available
### Report Long Description
	- This report lists Source Primary Server, Destination Primary Server, Client, Policy Name, Policy Type, Lifecycle Policy and many other details about the NBU AIR Replication Import Jobs## NetBackup Deduplication to MSDP Savings - By Clients (918)
### Report Short Description
`Provides details about NetBackup Deduplication to MSDP Savings - By Clients`
### Information 
    Last Updaated  : 29 April, 2024
    Avg Execution Time(recent) : 00 Hours: 00 Minutes: 21 Seconds
    Max Execution Time(recent) : 00 Hours: 02 Minutes: 35 Seconds
### Report Long Description
	- This report lists Client, Primary Server, Total Deduplication Job Count, Total Data Scanned Before Deduplication, Total Data Protected after Deduplication and provides the Total Deduplication Savings Percentage by Clients## NetBackup Deduplication to MSDP Savings - By Primary Servers (919)
### Report Short Description
`Provides details about NetBackup Deduplication to MSDP Savings - By Primary Servers`
### Information 
    Last Updaated  : 29 April, 2024
    Avg Execution Time(recent) : 00 Hours: 00 Minutes: 21 Seconds
    Max Execution Time(recent) : 00 Hours: 02 Minutes: 03 Seconds
### Report Long Description
	- This report lists Primary Server, Primary IP, Total Deduplication Job Count, Total Data Scanned Before Deduplication, Total Data Protected after Deduplication and provides the Total Deduplication Savings Percentage by Primary Servers.
	- This report is equivalent to the following NetBackup OpsCenter report(s): Deduplication Rates by Master Server.## NetBackup Deduplication to MSDP Savings - By Policy Type (920)
### Report Short Description
`Provides details about NetBackup Deduplication to MSDP Savings - By Policy Type`
### Information 
    Last Updaated  : 29 April, 2024
    Avg Execution Time(recent) : 00 Hours: 00 Minutes: 18 Seconds
    Max Execution Time(recent) : 00 Hours: 01 Minutes: 49 Seconds
### Report Long Description
	- This report lists Policy Type, Total Deduplication Job Count, Total Data Scanned Before Deduplication, Total Data Protected after Deduplication and provides the Total Deduplication Savings Percentage by Policy Type.
	- This report is equivalent to the following NetBackup OpsCenter report(s): Deduplication Rates by Policy Type.## NetBackup Deduplication to MSDP Savings Trend Over Time (921)
### Report Short Description
`Provides NetBackup Deduplication to MSDP Trend Over Time`
### Information 
    Last Updaated  : 29 April, 2024
    Avg Execution Time(recent) : 00 Hours: 00 Minutes: 18 Seconds
    Max Execution Time(recent) : 00 Hours: 01 Minutes: 39 Seconds
### Report Long Description
	- This Bar Chart report lists Deduplication Trend Over Time.
	- This report is equivalent to the following NetBackup OpsCenter report(s): Pre vs.
	- Post Deduplication Size.## Job Throughput by Client (922)
### Report Short Description
`Job Throughput `
### Information 
    Last Updaated  : 29 April, 2024
    Avg Execution Time(recent) : 00 Hours: 01 Minutes: 01 Seconds
    Max Execution Time(recent) : 00 Hours: 02 Minutes: 43 Seconds
### Report Long Description
	- This report shows a line chart for job throughput by client.
	-  It can be used to determine if there are performance issues on this host or appliance.
	- It will show the top 20 clients.
	-  It should be run for only one Server## Anomalies Summary (925)
### Report Short Description
`Provides details of the jobs with anomalies.`
### Information 
    Last Updaated  : 29 April, 2024
    Avg Execution Time(recent) : 00 Hours: 00 Minutes: 04 Seconds
    Max Execution Time(recent) : 00 Hours: 00 Minutes: 28 Seconds
### Report Long Description
	- Drilldown on Anomaly score to see more details on the associated anomalies.## NetBackup SLP Status by Client (929)
### Report Short Description
`Lists the Storage Lifecycle Policy (SLP) status for NetBackup jobs by Client, which can be used as an overview of the health of the SLPs for each NetBackup primary server.`
### Information 
    Last Updaated  : 29 April, 2024
    Avg Execution Time(recent) : 00 Hours: 00 Minutes: 02 Seconds
    Max Execution Time(recent) : 00 Hours: 00 Minutes: 02 Seconds
### Report Long Description
	- Using this report's completion statistics, you can determine if the SLP is performing according to schedule, if additional copies have been made, and also if the backlog is increasing.
	- These statistics enable you to identify issues associated with the processing of SLPs.## NetBackup SLP Status by Image Copy (930)
### Report Short Description
`Lists the Storage Lifecycle Policy (SLP) status for NetBackup jobs by Image Copy, which can be used as an overview of the health of the SLPs for each NetBackup primary server.`
### Information 
    Last Updaated  : 29 April, 2024
    Avg Execution Time(recent) : 00 Hours: 00 Minutes: 16 Seconds
    Max Execution Time(recent) : 00 Hours: 00 Minutes: 18 Seconds
### Report Long Description
	- Using this report's completion statistics, you can determine if the SLP is performing according to schedule, if additional copies have been made, and also if the backlog is increasing.
	- These statistics enable you to identify issues associated with the processing of SLPs.## Job Status Summary by Client (931)
### Report Short Description
`This report shows a status summary of backup jobs for the selected clients. The table shows totals for successful, partially successful, and failed jobs for each client that is in scope.`
### Information 
    Last Updaated  : 29 April, 2024
    Avg Execution Time(recent) : 00 Hours: 00 Minutes: 01 Seconds
    Max Execution Time(recent) : 00 Hours: 00 Minutes: 01 Seconds
### Report Long Description
	- This report shows a status summary of backup jobs for the selected clients.
	- The table shows totals for successful, partially successful, and failed jobs for each client that is in scope.
	-  When clicking on one of the totals, this will open a drill-down report to see the details of the selected jobs.
	-  It is recommended to run this report on specific groups of clients by modifying the scope selector.
	- This report is equivalent to the following NetBackup OpsCenter report(s): Job Success by Client## Ransomware Risk Assessment Dashboard (1000)
### Report Short Description
`Dashboard to highlight the risk of under-protected assets which if exposed to a Ransomware threat may become unavailable and may even incur financial loss to the enterprise. It also highlights any presence of files with well-known ransomware extensions across your environment`
### Information 
    Last Updaated  : No Data Available
    Avg Execution Time(recent) : No Data Available
    Max Execution Time(recent) : No Data Available
### Report Long Description
	- This dashboard contains multiple reports to highlight and visualize the risk in your environment which enables you to ascertain your readiness in terms of data protection in the event of a Ransomware infection.
	- A well protected landscape would mean that data can be recovered with confidence.
	- The dashboard is divided up into sections and each section represents a report.
	- The Risk Mitigation Analysis report in the dashboard describes the risk associated with several key aspects of your protection environment.
	- The report lists servers which are divided across risk categories .
	- For example, the "Sources with No Recent Backups" category lists all servers which have not been backed up in the recent past.
	- The "Suspect Backup by Job Size" category indicates servers whose backup job resulted in a very small size backup which indicates some misconfiguration.  The "Sources Consecutive Failure" category describes the risk of backup jobs failing for certain servers and that means some servers may not be adequately protected.
	- You can click on the donut section of your choice in the chart to get a detailed view of the servers and sources under consideration for that selection.
	- This drill down capability provides deeper insight and helps identify the sources of risk quickly and easily.
	- In order to choose your categories to display, please hover your mouse over the top right part of the report to display icons that let you "edit scope".
	- These rules and categories are also described in Admin ->Solutions->Risk Mitigation.
	- Here you can choose to double click on any rule to customize it for your requirements.
	- You can choose to view multiple categories at the same time or select the categories by clicking on the category legend without changing the scope of the report for quick view and analyze situations.
	- The Risk Mitigation trend report describes the same risk categories spread across time.
	- This report gives you a sense of how your protection risk has been changing over time.  This helps you create a baseline and work towards keeping your risk levels per category below this baseline.
	- The Alerts Summary report describes specific instances when things have not worked as expected with respect to data protection.
	- A NBU primary server connection failure, out of storage condition on the NBU primary server or an incomplete backup job may indicate risk in the environment that needs addressing.
	- The alert summary chart can be used to drill down on any of the alert types to get deeper insight into the source of alert.
	- This helps in mitigating any potential risk in the environment and consequently reducing a potential negative impact of a Ransomware infection.
	- The report scope can be edited by hovering over the top right hand corner of the report and choosing the "Edit Scope" option and choosing which Alert category to see in the report.
	- The alerts can be configured in detail using the top level Alerts tab.
	- The Alert trend report describes the alert occurrences over time.
	- This provides a good way of determining a baseline and staying below the baseline as a goal to mitigate any risk.
	- The "Ransomware File types " report describes the risk associated with the presence of files across the enterprise which have well known ransomware extension names.  This helps to zoom in on servers which have files with potential ransomware infection.
	- This visibility is crucial in identifying the spread of Ransomware infection across the environment.
	- This report provides the summary view of the number of the such file extensions found.
	- You can click on the export icon to download a CSV file which would contain a list of all file paths along with their server locations to help drill down into the source of the infection.
	- This report is available with the "Complete" license pack for NetBackup IT Analytics software.
	- ## Operations Dashboard (1001)
### Report Short Description
`Displays a dashboard view of Job Status Summary, Current Media Summary, Largest Backup Volume, and Storage Unit Summary.`
### Information 
    Last Updaated  : 29 April, 2024
    Avg Execution Time(recent) : 00 Hours: 00 Minutes: 10 Seconds
    Max Execution Time(recent) : 00 Hours: 00 Minutes: 32 Seconds
### Report Long Description
	- The reports displayed in this dashboard are dependent on the type of backup system selected in the report scope.
	- For example, the Storage Unit Summary is relevant only for NetBackup servers.
	- Note that in the Storage Unit Summary, used and free values of "Unknown" indicate the Discovery module has not been configured to probe the media servers' file systems for their physical characteristics.## Alerts Dashboard (1002)
### Report Short Description
`NetBackup IT Analytics can continuously monitor for issues in your environment. The Alerts Dashboard provides an overview of detected issues that require attention.`
### Information 
    Last Updaated  : No Data Available
    Avg Execution Time(recent) : No Data Available
    Max Execution Time(recent) : No Data Available
### Report Long Description
	- The Alerts Dashboard allows you to see a high-level view of current and historical alert conditions, and also manage these alerts by drilling down into more detailed views where you can actively manage the alerts.  A prerequisite to utilize this dashboard is to set up Alerts from Alerts -> Alerts Policy Administration.
	- Once Alert rules have been configured, NetBackup IT Analytics will continuously monitor your environment and generate an alert when a monitored condition is triggered.
	- One of the following actions should typically be taken on each alert:  The condition that triggered the alert is rectified (e.g.
	- datastore that was filling up was expanded) If the alert is a false positive, the alert rule is refined to prevent future alerts If the alert is valid, but can be ignored, the alert can be suppressed.
	- Alerts can be suppressed either indefinitely or for a configurable period of time. With the above practices, the alerts dashboard will minimize false positives and ultimately highlight only issues that require intervention, helping you to pro-actively avoid issues in your environment.## Storage Optimization Dashboard (1003)
### Report Short Description
`View charts of storage showing opportunities to optimize storage reclamation, by tier, infrastructure category, in summary and as a trend`
### Information 
    Last Updaated  : No Data Available
    Avg Execution Time(recent) : No Data Available
    Max Execution Time(recent) : No Data Available
### Report Long Description
	- Storage optimization starts with a one-off analysis, but should be reviewed regularly to maintain efficient storage use.
	- This dashboard presents point-in-time charts that summarize storage usage and show different detailed views.
	- A trend report shows usage over time by storage category.
	- Chart sectors can be clicked to drill down into additional details for particular infrastructure categories such as Undiscovered LUNs, Powered-off VMs, Over-provisioned Hosts, etc.
	- Storage Tiers and Reclaimable/Non-reclaimable storage can also be seen in detail.## Backup Server Performance Dashboard (1004)
### Report Short Description
`Backup Server Performance Dashboard`
### Information 
    Last Updaated  : No Data Available
    Avg Execution Time(recent) : No Data Available
    Max Execution Time(recent) : No Data Available
### Report Long Description
	- This dashboard combines Job Throughput metrics with Host Resource / Performance utilization charts## NetBackup Deduplication to MSDP Savings Dashboard  (1006)
### Report Short Description
`The Dashboard provides details about Deduplication to MSDP Savings`
### Information 
    Last Updaated  : No Data Available
    Avg Execution Time(recent) : No Data Available
    Max Execution Time(recent) : No Data Available
### Report Long Description
	- The Dashboard provides Deduplication to MSDP Savings by Primary Server, by Policy Type, by Clients.
	- Displays pre, post Deduplication Trend and Deduplication Savings Trend## Azure Cloud Cost Spend Dashboard (1007)
### Report Short Description
`Dashboard to highlight the cost spent on Azure subscriptions`
### Information 
    Last Updaated  : No Data Available
    Avg Execution Time(recent) : No Data Available
    Max Execution Time(recent) : No Data Available
### Report Long Description
	- This dashboard contains multiple reports to show the cost spent on Azure cloud subscriptions. This dashboard also shows different cost visualizations based on Subscription, Region, Service, and Tag in a stacked bar chart and tile format. Cost spend last month - This shows the overall spend last month. Cost spend so far this month - This shows the cost spend until the current date. Projected cost spend this month - This shows the projected cost for the month based on calculation as (Cost/no of days as of current date) * (Total no of days in the month)). All the above 3 reports are for all the subscriptions for which billing data is collected. Cost history by Subscription ( Top N ) - This shows the week-wise cost history for the top 10 high-spending subscriptions for last 90 days. Cost history by Region ( Top N ) - This shows the week-wise cost history for the top 10 high-spending regions for last 90 days. Cost history by Service ( Top N ) - This shows the week-wise cost history for top 10 high-spending services for last 90 days. Cost history by Tag - This shows week-wise cost history for values under the tags for last 90 days.
	- The default value of the tag for this report under this dashboard is always the first value in the drop-down list. All history reports allow the drill-down facility to see more granular data for the default values. Note - Cost history by Tag report can be empty if the resource usage data is not available for the default tag.## Command Center Dashboard (1101)
### Report Short Description
`Use the multi-portlet Command Center Dashboard to get a real-time view of your backup environment.`
### Information 
    Last Updaated  : 29 April, 2024
    Avg Execution Time(recent) : 00 Hours: 00 Minutes: 32 Seconds
    Max Execution Time(recent) : 00 Hours: 00 Minutes: 58 Seconds
### Report Long Description
	- This dashboard view includes several reports: Real Time Job Summary, Real Time Library and Drive Status, Real Time Storage Unit Utilization, and Running and Queued Jobs Summary.
	- This dashboard is relevant for Veritas NetBackup and EMC Networker jobs.## Data Protection Dashboard (1201)
### Report Short Description
`Displays a dashboard view of several reports: Message of the Day, Job Status Summary, Mission Control report, and Monthly Backup Summary.`
### Information 
    Last Updaated  : 29 April, 2024
    Avg Execution Time(recent) : 00 Hours: 00 Minutes: 39 Seconds
    Max Execution Time(recent) : 00 Hours: 01 Minutes: 51 Seconds
### Report Long Description
	- In the scope selector, in addition to specifying a time period, you also can choose to omit backup retries.## Mission Control - Backup (1301)
### Report Short Description
`Provides a snapshot of backup/restore event status, with easily identifiable indicators of success/failure and drilldowns to details.`
### Information 
    Last Updaated  : 29 April, 2024
    Avg Execution Time(recent) : 00 Hours: 01 Minutes: 44 Seconds
    Max Execution Time(recent) : 00 Hours: 15 Minutes: 19 Seconds
### Report Long Description
	- Using this report, you can easily identify hosts that have not had backups or failed backups.
	- Drilldown to ascertain the root cause of unsuccessful backups.
	- Organizations use this report to ensure Sarbanes-Oxley compliance, as it shows ultimate backup success over time.## IBM Spectrum Protect (TSM) Storage Pools Dashboard (1501)
### Report Short Description
`View a dashboard report that displays a real-time view into capacity and process status information for the selected list of IBM Spectrum Protect (TSM) Storage Pools.`
### Information 
    Last Updaated  : 29 April, 2024
    Avg Execution Time(recent) : 00 Hours: 00 Minutes: 56 Seconds
    Max Execution Time(recent) : 00 Hours: 00 Minutes: 56 Seconds
### Report Long Description
	- In a single pane, you quickly can analyze capacity and process status information for each of the Storage Pools.
	- The Storage Pool Capacity pie chart displays the percentage and GBytes used and available for the Storage Pool.
	- The GBytes Used is calculated by multiplying the percentage used by the estimated capacity of the Storage Pool.## Job Histogram (1601)
### Report Short Description
`Displays either Job Throughput or Job Activity based on your preference.`
### Information 
    Last Updaated  : 29 April, 2024
    Avg Execution Time(recent) : 00 Hours: 00 Minutes: 01 Seconds
    Max Execution Time(recent) : 00 Hours: 00 Minutes: 02 Seconds
### Report Long Description
	- Use these reports to identify bottlenecks.
	- The Job Throughput Histogram provides colored visual cues for quickly determining the backup throughput trends for clients that had backup jobs within the previous 24 hours.
	- This report shows completed jobs that started within the selected time period.
	- The Job Activity Histogram lists clients that had backup jobs within the previous 24 hours.
	- The colored cells enable you to quickly determine the activity per client.
	- The report shows the number of completed jobs that started within the selected time period.
	- This report is equivalent to the following NetBackup OpsCenter report(s): Job Throughput Workload Analyzer.## NetBackup Audit Report (1602)
### Report Short Description
`View NetBackup object and configuration changes`
### Information 
    Last Updaated  : 29 April, 2024
    Avg Execution Time(recent) : 00 Hours: 01 Minutes: 35 Seconds
    Max Execution Time(recent) : 00 Hours: 01 Minutes: 51 Seconds
### Report Long Description
	- When auditing is configured for a NetBackup environment, the following user-initiated actions from NetBackup are recorded and available to view in an audit report: Actions that change the NetBackup configuration.
	- Examples are policy creation, deletion, and modification, and changing the audit settings.
	- Actions that change NetBackup run-time objects.
	- These actions include initiating a restore job and starting or stopping the audit service.## NetBackup Event Notification Summary - CRITICAL (1603)
### Report Short Description
`A report which displays the summary of server name, severity , priority and count of critical event notifications.`
### Information 
    Last Updaated  : 29 April, 2024
    Avg Execution Time(recent) : No Data Available
    Max Execution Time(recent) : No Data Available
### Report Long Description
	- The report displays summarized view of server name, notification severity an d priority and its corresponding count of the critical events notification.
	- Click Server Name hyperlink vlue to view Host Details report for corresponding Server Name.
	- Click Number of Notifications column hyperlink value to view its details on basis of server name, corresponding notification priority and severity.
	- This report can generated with provided scopes and filters.## Avamar Grid Capacity Dashboard (1610)
### Report Short Description
`Displays a unified historical view of the storage and de-duplication trends of the Avamar grids.`
### Information 
    Last Updaated  : 29 April, 2024
    Avg Execution Time(recent) : 00 Hours: 00 Minutes: 02 Seconds
    Max Execution Time(recent) : 00 Hours: 00 Minutes: 13 Seconds
### Report Long Description
	- The graph represents the total usage and capacity for all disks on the host for the point in time.
	- The Capacity Utilization and Forecast report is derived from the node disk utilization.## Data Domain Replication History (1620)
### Report Short Description
`Use this report to determine which destinations are being replicated.`
### Information 
    Last Updaated  : 29 April, 2024
    Avg Execution Time(recent) : 00 Hours: 00 Minutes: 10 Seconds
    Max Execution Time(recent) : 00 Hours: 00 Minutes: 45 Seconds
### Report Long Description
	- The values shown in the report are derived from cumulative statistics since the replication context was created.
	- The remaining pre-compression (pre-comp) value, relevant for directory replication only, represents the sum of the sizes of the files yet to be replicated.
	- Note that this value includes the entire logical size of the current file that is being replicated.
	- For very large files, this may take some time and the remaining pre-comp value will only update once the current file replication completes.
	- The compression factor is derived from replicated pre-comp divided by replicated post-comp.## Data Domain Snapshot History (1630)
### Report Short Description
`Lists Data Domain Snapshots with relevant retention details.`
### Information 
    Last Updaated  : 29 April, 2024
    Avg Execution Time(recent) : 00 Hours: 00 Minutes: 09 Seconds
    Max Execution Time(recent) : 00 Hours: 00 Minutes: 09 Seconds
### Report Long Description
	- Snapshots listed for each Data Domain system provide insight into retention policies.
	- Note that expired snapshots remain available until the next file system clean operation.