---
type: rule
archivedreason: 
title: Do you know the right way to create your Angular project?
guid: bc2dd342-6109-461f-8e9b-cd6b3e5aaa4e
uri: do-you-know-the-right-way-to-create-your-angular-project
created: 2016-10-27T21:33:46.0000000Z
authors:
- id: 1
  title: Adam Cogan
- id: 24
  title: Adam Stephensen
- id: 34
  title: Brendan Richards
- id: 69
  title: Jean Thirion
related: []

---

[Angular.io](http://angular.io/) is a great place to get started learning Angular, and since the Angular CLI is now an official Angular project, these docs now include using the CLI from the beginning.

<!--endintro-->

The [Quick Start](https://angular.io/docs/ts/latest/quickstart.html) and [Tour of Heros Tutorial](https://angular.io/docs/ts/latest/tutorial/) will teach you lots about Angular.

For an enterprise real-world project you should also consider:

1. **Whether your application will require the redux pattern** 
See [Do you know to use ngrx on complex applications?](/_layouts/15/FIXUPREDIRECT.ASPX?WebId=3dfc0e07-e23a-4cbb-aac2-e778b71166a2&TermSetId=07da3ddf-0924-4cd2-a6d4-a4809ae20160&TermId=e4d1e090-bee8-4a86-9a46-fa46aa7f8058)
2. **Do you need a UI framework?** 
See [Do you know the best UI framework for Angular?](/_layouts/15/FIXUPREDIRECT.ASPX?WebId=3dfc0e07-e23a-4cbb-aac2-e778b71166a2&TermSetId=07da3ddf-0924-4cd2-a6d4-a4809ae20160&TermId=1c35f4c4-7f94-4c88-8bbf-a81dfc77f5d7)




There are also several well-used templates that incorporate Angular and server-side tooling.
While these starters often include advanced functionality, we prefer to implement pure Angular CLI projects where possible because Angular updates frequently.. and when you are using someone else's template that incorporates Angular you are left with the options of waiting for them to update their template to the latest version of Angular, or working out how to do it yourself. This can often leave you with large amounts of work or be being several months behind the latest versions.

To learn how to build  **enterprise Angular applications** check out [FireBootCamp](http://firebootcamp.com/angular2)
<dl class="goodImage">&lt;dt&gt; <img alt="create-angular-good.png" src="create-angular-good.png"> &lt;/dt&gt;<dd>Figure: Good Example: The Angular CLI will create you a new Angular project with a single command, and that project will be set up with production build, unit testing, and end-to-end testing all configured. If you have very specific build requirements, the CLI also supports custom web pack builds. <br></dd></dl>