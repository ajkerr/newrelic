# newrelic cookbook CHANGELOG

This file is used to list changes made in each version (>= 2.11.0) of the newrelic cookbook.

## v2.12.2 (2015-06-01)

- Bugfix: illegal to set resource values during the provider execution

## v2.12.1 (2015-06-01)

- Bugfix: fixed detection of the java_agent execute_agent_action node attribute

## v2.11.2 (2015-04-18)

- Bugfix: ssl attribute in server monitor, see issue #179
- General: 2.11.x cleanup

## v2.11.1 (2015-04-17)

- Bugfix: attribute that was previously potentially a TrueClass or FalseClass must be of type String, see issue #175

## v2.11.0 (2015-04-17)

- Refactoring: convert php agent and server monitor to lwrp
- Housekeeping: copyright
