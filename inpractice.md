# SCRUM in practice

The page provides a step-by-step guide to using SCRUM in your team.

## The product backlog

At the heart of your SCRUM development cycle is the [product backlog](glossary.md#product-backlog). The backlog contains a list of all user stories, bug reports and other tasks that need to be carried out as part of developing your product. 

It is worth spending some time to make sure all feature requests and user stories are logged properly in the backlog. Ideally, each item should have a detailed description and acceptance critera that define when this item is done. 

User stories should be broken down into subtasks, especially if they refer to quite a substantial feature. Items in the backlog can be linked to indicate how they related, eg one item requires another item to be completed before it can be implemented.

## Prioritising the backlog

It is essential that the backlog be well priortised. This is the job of the product owner, although they can take input from the development team. Each user story in the backlog should be allocated a number of story points to indicate its complexity. Items should also be given a priority level (eg blocker, criticial, high, medium, low) to indicate how their completion or lack thereof will affect project progress. Priorities can change as the project progresses, story points should not.

## Using sprints

A [sprint](glossary.md#sprint) is a single unit of the development cycle. All sprints should be same length, typically one or two weeks, although longer or shorter sprints are possible. Each sprint starts with a planning meeting, where the tasks to be completed in the sprint are identified. Each sprint finishes with a sprint review and retrospective meeting, where the outcomes of the sprint, both in terms of process and in terms of the product, are reviewed by the development team.


## Sprint planning

Each sprint starts with a [sprint planning](glossary.md#sprint-planning) session. The session is facilitated by the scrum master. During the sprint planning, the top priority items from the backlog are moved into the sprint, up to the value of story points that previous experience (supported by evidence velocity, burn-up and burn-down reports) suggests can be achieved in one sprint. Dev team availability (eg planned leave, training courses etc) should be factored in here. 

Tickets can be assigned to team members during the sprint or, in a truy agile team, picked up by whoever is available based on priority during the course of the sprint. 

## Daily stand-ups

The development team should have a daily stand-up of about 10-15 minutes, ideally either at the beginning or the end of the day. During the stand-up, each team member very briefly reports on their progress during the previous day and their plan for the next working day, identifying any immediate blockers or impediments to their work.

The daily stand-up allows the team to know what everyone else is working on, quickly identifying bottle necks and blockers. If necessary, resources and efforts can be redeployed to address any impediments to achieving the sprint goal.

## Retrospective

At the end of the sprint, the team has a sprint review and retrospective session. During this session, the team identifies what went well during the sprint, what didn't go well, any impediments and how they can be mitigated in the next iteration. Concrete action items for improvements should be agreed for the next sprint. 

The product is also reviewed in the sprint meeting. Any features that could not be completed should be flagged and returned to the backlog or put straight into the next sprint.


## Increment

The goal of most sprints is generally the release of an incremental improvement to the product. This can be a new feature or the refinement of an existing feature. While it is not absolutely necessary to have a releasable product at the end of every sprint, it should be the aim of most sprints. Releases don't have to be production ready but should be deployable into a beta state. 

<div id="disqus_thread"></div>
<script>

/**
*  RECOMMENDED CONFIGURATION VARIABLES: EDIT AND UNCOMMENT THE SECTION BELOW TO INSERT DYNAMIC VALUES FROM YOUR PLATFORM OR CMS.
*  LEARN WHY DEFINING THESE VARIABLES IS IMPORTANT: https://disqus.com/admin/universalcode/#configuration-variables*/
/*
var disqus_config = function () {
this.page.url = PAGE_URL;  // Replace PAGE_URL with your page's canonical URL variable
this.page.identifier = PAGE_IDENTIFIER; // Replace PAGE_IDENTIFIER with your page's unique identifier variable
};
*/
(function() { // DON'T EDIT BELOW THIS LINE
var d = document, s = d.createElement('script');
s.src = 'https://scrum101.disqus.com/embed.js';
s.setAttribute('data-timestamp', +new Date());
(d.head || d.body).appendChild(s);
})();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>
                            
