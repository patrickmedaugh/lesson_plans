---
title: Self-Directed Project
length: 2
tags:
type: project
---

## Project Description

The goal of this project is to create a successful web application from a project idea. You will create an app that will authenticate with a third-party service, consume an api, and solve an actual problem.

The project requirements are listed below:

* [Learning Goals](#learning-goals)
* [Setup](#setup)
* [Technical Expectations](#technical-expectations)
* [Project Concepts](#project-concepts)
* [Evaluation](#evaluation)

## <a name="learning-goals"></a> Learning Goals

* Learning how to build a full Rails app from idea to delivery
* Revisiting previous concepts such as APIs and OAuth
* Finding the strengths and gaps in your knowledge of Ruby, Rails, and organizing
a project.

## <a name="setup"></a> Setup

## <a name="technical-expectations"> Technical Expectations

Every project will be a bit different, but they need to share some
common technical characteristics:

* You must use an external OAuth provider to authenticate users
* You must consume an external API
* You must implement a production quality user interface
* You must optimize your application optimizing your database, implementing caching, using background workers, and sending AJAX requests

### Project Scope

A good project idea should:

* Break down into logical iterations so that you can deliver a strong product on  every checkin
* Be something that real people would want to use to solve a problem
* Have enough *technical* challenge to be worth your time (as opposed to a *content* challenge)

### APIs

Your application **must make good use of one external dataset or API**. Some examples include:

#### Government Data

* [Data.gov](https://www.data.gov/)
* [Sunlight Foundation](http://sunlightfoundation.com/)
* [ProPublica](http://www.propublica.org/tools/)
* [NASA](http://data.nasa.gov/api-info/)
* [US Census](http://www.census.gov/data/developers/data-sets.html)
* [Socrata Listings](https://opendata.socrata.com/dataset/Socrata-Customer-Spotlights/6wk3-4ija)
* [Bureau of Labor & Statistics](http://www.bls.gov/developers/api_ruby.htm)
* [United Nations](https://www.undata-api.org/) (3rd party API)
* [Google's Directory of Public Data](http://www.google.com/publicdata/directory)
* [OpenColorado](http://data.opencolorado.org/)
* [Denver Regional Council of Governments](https://drcog.org/services-and-resources/data-maps-and-modeling)

#### Corporate Data

* [Twitter](https://dev.twitter.com)
* [Facebook](https://developers.facebook.com)
* [Instagram](https://instagram.com/developer)
* [Github](https://developer.github.com/v3)
* [FitBit](https://dev.fitbit.com)
* [Spotify](https://developer.spotify.com/web-api)
* [Strava](https://www.strava.com/developers)
* [Uber](https://developer.uber.com)
* [Google Maps](https://developers.google.com/maps)

However, the list is not limited to these. You can choose to integrate with a service of your choosing, as long as it is approved by your client.

## <a name="project-concepts"></a> Project Concepts

A week prior to the Self-Directed Project kickoff, each cohort member needs to generate at least **three project ideas**. The ideas must solve a real problem. To put your ideas into project proposals follow the template below. Each idea should have one project proposal.

Once the project proposals are in place, each cohort member will pick an idea, and put the remaining two ideas into the shared ideas. The entire cohort will then vote on the ideas it wants to see built. Finally, the cohort members will have an opportunity to exchange their idea for one of the shared ones, or keep their original idea.

### Project Template

```markdown
### [Project Title]

### Pitch

1 sentence that explains the value proposition of the application. How would you explain it to a potential business partner, team member, or investor?

### Problem

1-3 sentences describing the problem that you are trying to solve.

### Solution

1-3 sentences describing how your application will solve that problem.

### Target Audience

1-3 sentences describing what type of user your app would be applicable to.

### Integrations

* Which APIs will you use?
* Which OAuth integration are you planning to use?
```

## <a name="evaluation"></a> Evaluation

You'll be graded on each of the criteria below with a score of (1) well below expectations, (2) below expectations, (3) as expected, (4) better than expected.

### Feature Delivery

**1. Completion**

* 4: Developer completed all the user stories and requirements set by the client in timely manner.
* 3: Developer completed all the user stories and requirements set by the client.
* 2: Developer completed most of the user stories and requirements set by the client.
* 1: Developer completed the user stories and requirements partially.

**2. Organization**

* 4: Developer used a project management tool and updated their progress in real-time.
* 3: Developer used a project management tool to keep their project organized.
* 2: Developer used a project management tool but didn't update the progress frequently.
* 1: Developer failed to use a project management tool to track its progress.

### Technical Quality

**1. Test-Driven Development**

* 4: Project shows exceptional use of testing at different layers (above 95% coverage).
* 3: Project shows adequate testing (90% - 95% coverage).
* 2: Project shows gaps in test usage/coverage/design (85 - 90% coverage).
* 1: Project lacks sufficient testing (under 85% coverage).

**2. Code Quality**

* 4: Project demonstrates exceptionally well factored code.
* 3: Project demonstrates solid code quality and MVC principles.
* 2: Project demonstrates some gaps in code quality and/or application of MVC principles.
* 1: Project demonstrates poor factoring and/or understanding of MVC.

### Product Experience

**1. User Experience**

* 4: Project exhibits a production-ready and polished UX.
* 3: Project exhibits a production-ready user experience.
* 2: Project exhibits some gaps in the UX.
* 1: Project exhibits inattention to the user experience.

**2. Performance**

* 4: Project pages load on average under 300 milliseconds.
* 3: Project pages load on average under 400 milliseconds.
* 2: Project pages load on average under 500 milliseconds.
* 1: Project pages load on average over 500 milliseconds.
