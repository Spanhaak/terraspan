# Terraspan 
## Introduction
<p>This repo is to automate the creation of the following:</p>
<ul>
<li>Create a Google Group in the organisation</li>
<li>Create a number of Google Roles</li>
<li>Configure the roles with permissions</li>
<li>Assign users to roles</li>
</ul>

### Step 1: Create a Service Account with Permissions
You need to create a service account which has the proper permissions.
The following Google Cloud IAM roles will do the trick:\
:heavy_check_mark: Service Usage Consumer: ```roles/serviceusage.serviceUsageConsumer``` on the billing project\
:heavy_check_mark: Organization Viewer: ```roles/resourcemanager.organizationViewer``` if using domain instead of customer_id\
