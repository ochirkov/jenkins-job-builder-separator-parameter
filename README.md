separator
====================

jenkins-job-builder separator parameter.

Installation
---

Install separator parameter by running the following command:

        pip install jenkins-job-builder-separator-parameter

Or from source code:

        python setup.py install

Usage
---

        - job:
            name: test_job
            project-type: freestyle

            parameters:
              - separator
