Get Users By Group
================================

This plugin provides you the ability to get all users in a specific group.

Adding to Artifactory
----------------------
This plugin need to be added to the $ARTIFACTORY_HOME/etc/plugins directory.

Executing
---------

To execute this plugin:

curl -X GET -u{admin_user}:{password} "http://{ARTIFACTORY_URL}:{PORT}/artifactory/api/plugins/execute/findIncludedUsers?params=group={group_name}" 