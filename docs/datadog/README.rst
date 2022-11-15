How to send Cowrie output to Datadog
####################################

This guide describes how to configure and send cowrie outputs to Datadog.

Datadog output module Prerequisites
***********************************

* Working Cowrie installation
* Existing Datadog account.

Cowrie Configuration for Datadog output module
**********************************************

* Modify ``cowrie.cfg`` to enable the ``[output_datadog]`` section.
* Add an API Key. You may generate one for your organisation from `here <https://app.datadoghq.com/organization-settings/api-keys>`_.
* Optionally customize ``ddsource``, ``ddtags`` and ``service``. Otherwise, defaults are respectively ``cowrie``, ``env:prod`` and ``honeypot``.

Datadog Configuration
*********************

JSON logs are handled without further configuration in Datadog.