This is a fork of https://github.com/jenkinsci/build-blocker-plugin. The only difference is that this fork waits for any matching job in the queue instead of just the buildable ones.

build-blocker-plugin
====================

Jenkins build blocker plugin

This plugin uses a QueueTaskDispatcher to block scheduled jobs from starting as long as configured other jobs are running.

These other jobs can be configured in a textarea where each line represents a regular expression of the job names that should block this job from starting.
