How to send Cowrie output to Datadog
####################################

This guide describes how to configure and send cowrie outputs to Datadog.

Prerequisites
*************

* Working Cowrie installation
* Existing Datadog Organization. `You can sign up for free Datadog trial for 14 days <https://www.datadoghq.com/free-datadog-trial/>`_

Cowrie Configuration
********************

* `Copy API Key <https://app.datadoghq.com/organization-settings/api-keys>`_ for later use
* Modify ``cowrie.cfg`` to enable the ``[output_datadog]`` section
* Add the API Key you copied in the previous step
* Optionally enable ddsource, ddtags, service settings. Module implements fallback with "cowrie", "env:prod" and "honeypot" respectively.

Datadog Configuration
*********************

JSON logs are handled without further configuration in Datadog.