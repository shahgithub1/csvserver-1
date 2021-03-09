# The csvserver assignment for senior SRE

This assignment is for engineers applying for the senior SRE role. Complete all the parts from the [README.md](README.md) and then continue with the following tasks.

## Part IV
  It's time to add some alerts to the setup.

  0. Stop any containers running from last part.
  1. Add an alerting rule to Prometheus. The alert should fire when:
     - There are more than 20 requests per second over 2 minutes.
     - The value of requests per second remains greater than 20 for 5 minutes.
     - Use the `requests_total` metric for the calculations.
  2. Write a script or use a tool to generate requests to the csvserver, so that the above alert gets triggered.
  3. Go to Alerts section of the Prometheus interface.

The Alerts section of the Prometheus interface should show the alert, and it should be in pending or firing state.

> **NOTE**: It is not required to setup Alertmanager for this part to work.

### Save the solution
  - Update the required files from the `solution` directory.
  - Add any other newly created files to the `solution` directory.
  - Commit and push the changes to your repository on GitHub.

## Submitting the solution
Follow the instructions given [here](README.md#submitting-the-solution).
