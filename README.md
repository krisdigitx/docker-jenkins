docker-jenkins
==============

Jenkins in a Docker container; based on Ubuntu 13.10. It comes with the
following plugins:

 * hipchat.hpi
 * greenballs.hpi
 * credentials.hpi
 * ssh-credentials.hpi
 * ssh-agent.hpi
 * git-client.hpi
 * git.hpi
 * github.hpi
 * github-api.hpi
 * ghprb.hpi
 * github-oauth.hpi
 * scm-api.hpi
 * postbuild-task.hpi
 * aws-java-sdk.hpi
 * ant.hpi
 * codedeploy.hpi
 * bitbucket.hpi
 * bitbucket-pullrequest-builder.hpi
 * build-pipeline-plugin.hpi
 * chucknorris.hpi
 * conditional-buildstep.hpi
 * copyartifact.hpi
 * credentials.hpi
 * docker-commons.hpi
 * docker-build-step.hpi
 * envinject.hpi
 * javadoc.hpi
 * junit.hpi
 * mailer.hpi
 * matrix-auth.hpi
 * mesos.hpi
 * parameterized-trigger.hpi
 * pipeline-build-step.hpi
 * r.hpi
 * role-strategy.hpi
 * run-condition.hpi
 * sbt.hpi
 * slack.hpi
 * docker-build-publish.hpi
 * docker-custom-build-environment.hpi
 * dockerhub-notification.hpi
 * docker-workflow.hpi
 * docker-traceability.hpi


Usage
-----

    docker run -d -t -p 8080:8080 -v ${PWD}/jenkins:/var/lib/jenkins zaiste/jenkins

Building
--------

Grab Dockerfile from this repository on Github

    docker build github.com/zaiste/docker-jenkins

Get a Docker image from Docker index

    docker pull zaiste/jenkins

Testing
-------

Install [docker-test](https://github.com/wblankenship/docker-test)

From within the clone repo

    docker-test
