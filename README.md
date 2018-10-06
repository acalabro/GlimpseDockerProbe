GlimpseDockerProbe
====================

Information   | Value
------------- | --------
Package       | it.cnr.isti.labsedc.glimpse
Roadmap       | TBD
Language      | Java 11 LTS

# Summary
A probe for sending events to the Glimpse monitoring platform.
Easy deployable through docker.

# How it works?
Based on Publish Subscribe paradigm.
JMS messages through ActiveMQ.
Event correlation through Complex Event Processor by means of Drools Engine.

# Configuration
docker run GlimpseDockerProbe
To configure the probe before compiling it,
setup the parameter within the method Manager.createProbeSettingsPropertiesObject
