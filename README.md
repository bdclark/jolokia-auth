# jolokia-auth

[![Build Status](https://travis-ci.org/bdclark/jolokia-auth.svg?branch=master)](https://travis-ci.org/bdclark/jolokia-auth)

[Jolokia][1] war agent with basic authentication enabled.

The role `Jolokia` has full access to all resources. This role must be
referenced outside the agent WAR within the servlet container, e.g. for Tomcat
the role definition can be found in `$TOMCAT/config/tomcat-users.xml`.

[1]: https://jolokia.org/
