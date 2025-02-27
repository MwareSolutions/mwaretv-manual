# Customer can't log in

{% stepper %}
{% step %}
### Make sure the customer enters valid credentials


{% endstep %}

{% step %}
### [Check the error log in Application](../tvms-administration/application/app-builder/error-logs.md)

It will indicate the problem type and give more details
{% endstep %}

{% step %}
### Make sure it's not blocked and not expired


{% endstep %}

{% step %}
### Make sure the customer have not reached the maximum number of devices


{% endstep %}

{% step %}
### If you use an App ID, make sure it's valid


{% endstep %}

{% step %}
### Make sure you don't have any restrictions based on a geoposition, device, IP range

You can check it in the subscription details
{% endstep %}

{% step %}
### Try to log in with his credentials

Note that you have to ask for a password since they are hashed and aren't exposed
{% endstep %}

{% step %}
### Try to recover the password and try to log in


{% endstep %}

{% step %}
### Clear the cache or reinstall the app


{% endstep %}

{% step %}
### Contact the Mware support team


{% endstep %}
{% endstepper %}

