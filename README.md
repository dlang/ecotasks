# Ecosystem Task List
An ongoing challenge in the D Programming Language ecosystem is finding the resources (manpower, money, time) to complete all of the tasks in need of completion. In the code D repositories and those of myriad third-party projects, there are issues large and small, complex and simple, waiting for the right person to come along with a pull request to close them. The large and complex issues often require a specific skill set and knowledge level in addition to a significant investment of time, but anyone can take care of the smaller and simpler ones. Unfortunately, many of those are not the sort of issues that motivate volunteers to take action.

Solving the big issues might be accomplished by raising money, but how can we direct manpower toward solving all the small issues that no one wants to work on?

## Sharing Manpower
In the first Quarterly D Language Foundation meeting in December, 2018, representatives from companies using D in production were asked to consider a new idea: would the companies be willing to periodically designate one employee to spend a day or two of company time working on D ecosystem issues that are not necessarily in the company's interests?

Companies using D commercially often contribute to the community in different ways. They have open sourced some of their projects, reported and fixed bugs, donated money, supported DConf, provided jobs, and so on. We all appreciate their efforts and D would not be where it is today without them. But just as volunteers tend to work on problems in which they are most interested in solving, commercial D shops tend to work on issues from which they derive some benefit. Motivating volunteers to work on issues in which they have no interest is a problem we have yet to solve, but the idea of companies donating manpower seemed like something within the realm of possibility.

Before the second Quarterly D Language Foundation meeting in March, 2019, [a proposal was drafted](https://gist.github.com/mdparker/7e2894bef3e44daa1d1fac934a2c1aad) presenting two options for approaching the initiative: a monthly rotation where a different company takes a turn each month, or a quarterly schedule where each company agrees to donate time each quarter at their leisure. The companies were asked to consider the proposal and provide a response at the March meeting.

In the end, the quarterly option was the agreed upon approach. Not all of the companies could commit to sparing any manpower initially. Some were just starting up and others were short on manpower already. However, all agreed to support the initiative in principle as circumstances allow. One company committed to starting the initiative immediately, and one did so conditionally. Those who could not provide manpower at the moment offered to provide funding instead (and that sparked a separate initiative).

## The Task List
[This repository houses the list](./ecotasks.md) from which companies currently sharing manpower will select tasks to complete. Anyone in the community is welcome to tasks to add to the list, but the following guidelines should be considered when doing so:

* no task should be estimated to take longer than a single working day to complete; asking companies to maintain continuity between a single day each quarter and quite probably different developers is a bridge too far.
* generic task groupings are preferable to specific tasks, e.g. "Close as many issues as possible on Project Foo".
* any project in the D ecosystem is fair game

Pull requests are welcome for corrections in the list, but task suggestions should be reported as issues. The list will be roughly sorted according to what the D Language Foundation considers a priority, i.e. items higher on the list will be of higher priority than those lower on the list. Ultimately, it will be up to each worker a company makes available to decide which tasks to complete.

## Volunteers
We don't want to put the burden of sharing manpower solely on the companies using D in production. Anyone interested in helping improve the D ecosystem is welcome to work on items from the task list. In fact, if you have a little time on your hands, closing even a trivial issue from this list will be a tremendous help. Even better, challenge yourself to close one issue a month from the list!

If you do decide to pitch in, please remember to submit an issue detailing which task(s) you are currently working on and close the issue at the end of your work session so that we can minimize the risk of duplicate work.

## Avoiding Duplication
Given that we're asking the whole community to contribute, it's important that we have a mechanism to avoid duplication. As such, 
when anyone begins a session of manpower sharing, we ask that person to submit an issue indicating which task(s) he or she is currently working on and to close the issue at the end of the day.

For example, when starting a session, open an issue with a note like the following:

> I'm working on the dub registry issues right now. Specifically, I plan to tackle issues #I, #J, and #K.

Update the issue as needed if more specific tasks are taken on. At the end of the seesion, the issue should be closed with a note indicating what was accomplished.

