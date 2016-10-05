---
permalink: available-checks-for-rackspace-monitoring/
audit_date: '2016-01-22'
title: Available checks for Rackspace Monitoring
type: article
created_date: '2013-08-19'
created_by: Jim Culbreath
last_modified_date: '2016-01-22'
last_modified_by: Constanze Kratel
product: Rackspace Monitoring
product_url: rackspace-monitoring
---

In the Cloud Control Panel, you can choose to set monitoring checks on your servers. This article explains most common check and the options that you can set for them on Cloud Control Panel. For information about setting up one of these monitoring checks, see [Create a monitoring check using the Cloud Control Panel](/how-to/creating-a-monitoring-check-using-the-cloud-control-panel).

For configuration of all the supported checks and plugin checks, suppressions, notification plans, please see [Rackspace Intelligence documentation](https://support.rackspace.com/how-to/getting-started-with-rackspace-intelligence-for-the-cloud/).

For API check definitions, see the [Rackspace Monitoring developer documentation](https://developer.rackspace.com/docs/cloud-monitoring/v1/developer-guide/#document-tech-ref-info/check-type-reference).

Monitoring checks and alarms are located in the Cloud Servers section of the Cloud Control Panel.

- You can create a check by clicking the gear icon next to your individual server name and selecting **Create Check**.
- To edit a check, click on the server name and scroll to the **Monitoring Checks** section of the server details page. From there, you can click a check name and make changes to it.

### Available monitoring checks
This section lists each check that you can create for your server, the options that you can set when you create the check, and the options that you can edit for an existing check.

### HTTP
When you create an HTTP check, you can set the URL and specific body context with regular expressions allowed. Click **Advanced Options** to open a **Body Match** text box in which you can provide more syntax.

You can edit the following options for an existing HTTP check:

- **Target**: Specify the server IP address or a specified host name.
- **Details**: Specify the exact URL and body content to use. Regular expressions are allowed.
- **Parameters**: Set how often the check runs and when it will time out, as well as which regions the check uses.
- **Alarms**: Edit existing alarms or click **Create Alarm** to add an alarm

### TCP
When you create a TCP check, you can set the port that you want to monitor for connectivity. Provide the following information:

- Port number
- Target IP address or target host name

You can edit the following options for an existing TCP check:

- **Target**: Specify the server IP address or a specified host name.
- **Details**: Specify the port to be monitored.
- **Parameters**: Set how often the check will run and when it will time out.
- **Alarms**: Edit existing alarms or click **Create Alarm** to add an alarm.

### Ping

When you create a Ping check, you can select a name and select the target type as IP address or host name.

You can edit the following options for an existing Ping check:

- **Details**: Set the packet count and the number of packets that are sent at one time.
- **Parameters**: Set how often the check runs and when it will time out, as well as which regions the check will use.
- **Alarms**: Edit existing alarms or click **Create Alarm** to add an alarm.

### Memory

There are no special settings when you create a Memory check.

You can edit the following options for an existing Memory check:

- **Parameters**: Set how often the check will run and when it will time out.
- **Alarms**: Edit existing alarms or click **Create Alarm** to add an alarm.

### CPU

There are no special settings with you create a CPU check.

You can edit the following options for an existing CPU check:

- **Parameters**: Set how often the check runs and when it will time out.
- **Alarms**: Edit existing alarms or click **Create Alarm** to add an alarm.

### Load Average

There are no special settings when you create a Load Average check.

You can edit the following options for an existing Load Average check:

- **Parameters**: Set how often the check runs and when it will time out.
- **Alarms**: Edit existing alarms or click **Create Alarm** to add an alarm.

### Filesystem

When you create a Filesystem check, you can specify the disk for which you want to monitor space.

You can edit the following options for an existing Filesystem check:

- **Parameters**: Set how often the check runs and when it will time out.
- **Alarms**: Edit existing alarms or click **Create Alarm** to add an alarm.

### Network
When you create a Network check, you set the following options:

- Select which network interface to use (typically eth0 or eth1).
- Set the receive rate alert for warning and critical states.
- Set the transmit rate alert for warning and critical states. (For more information, see [Rackspace Monitoring Checks and Alarms](/how-to/rackspace-monitoring-checks-and-alarms).)

You can edit the following options for an existing Network check:

- **Parameters**: Set how often the check runs and when it will time out.
- **Alarms**: Edit existing alarms or click **Create Alarm** to add an alarm.

## Data graphs for monitoring

 You can view graphical information about resource use on the server details page. In the **Monitoring Data** section of the page, you can view historical check data. This viewing option is available for all checks and does not require the monitoring agent to be installed. Use the drop-down menu to select the monitoring check that you want to view.

<p><img alt="" height="317" src="{% asset_path rackspace-monitoring/available-checks-for-rackspace-monitoring/Monitoring-Data.png %}" width="742" /></p>
