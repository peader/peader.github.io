---
layout: post
title: Loggly with AspNetCore and nlog!
---

First you'll need a loggly account. If you don't already have one you can sign up for their free tier [here](https://www.loggly.com/signup/).

Once you're signed up you'll need to head over to "Source Setup" > "Customer Tokens" and copy the customer token from the list. We'll use this token a little bit later.

![_config.yml]({{ site.baseurl }}/images/loggly-token.png)

Next we want to make an ASP .NET 2.0 Web API. Note: ensure you have VS 2017 and the relevant NET Core 2.0 SDK installed.

Open Visual Studio

Go to "File" > "New" > "Project" and select "ASP .NET Core Web Application".

![_config.yml]({{ site.baseurl }}/images/vs-new-project.png)

Then select "Web API" and click "ok".

![_config.yml]({{ site.baseurl }}/images/vs-web-api.png)