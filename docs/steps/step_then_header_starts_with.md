
Then header "{header}" starts with {value}
=============================================================================================================

Usage example
-------------

```
Feature: zato-apitest docs

Scenario: Then header "{header}" starts with {value}

    Given address "http://apitest-demo.zato.io"
    Given URL path "/demo/json"

    When the URL is invoked

    Then header "Connection" starts with "keep-"
```

Discussion
----------

(None)