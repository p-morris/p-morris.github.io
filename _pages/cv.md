---
layout: page
title: CV
permalink: /cv/
navigable: true
scss: cv
---
<div class="cv-header">
    <div>
        <p class="name">Pete Morris</p>
        <p class="city">London, UK</p>
        <p class="degree">BSc (Hons) Computing, Open University</p>
    </div>
    <ul class="say-hello">
        {% for contact in site.contact %}
        {% if contact.name != "WhatsApp" %}
        <li><a href="{{contact.link}}"><ion-icon name="{{contact.icon}}"></ion-icon> {{contact.name}}</a></li>
        {% endif %}
        {% endfor %}
    </ul>
</div>

<div>
    <p class="intro">I love making apps that are testable, easy to build upon, and delightful to use.</p>
</div>

> {: .job-title}
> ## Lead iOS Engineer
> <cite>Thread, June 2022 - Present</cite>

[Thread](https://www.thesun.co.uk/sun-selects/17809393/thread-review/) was an AI-driven clothing retailer and personal styling service, recently acquired by [Marks and Spencer](https://corporate.marksandspencer.com/media/press-releases/ms-acquires-thread-ip-accelerate-its-personalisation-plans).   

{: .work-list}
* Moved CI pipelines to Xcode Cloud reducing costs >80%
* Created build tools for finding and fixing code style problems automatically
* Implemented content-driven features for users to find info about brands, style tips, and outfit suggestions
* Introduced developer documentation for the iOS code base
* Added use of SwiftUI state management APIs, simplifying propagation of state through the view hierarchy
* Implemented a new design system, providing developer-friendly access to standardised typography, and colours
* Developed a prototype to assess the use of Kotlin Multiplatform to share business logic between iOS and Android
* Joined a hackday project to propose a feature for recommending clothing sizes based on past purchases

{: .tag-list}
* `MVVM`
* `SwiftUI`
* `Combine`
* `Xcode Cloud`

> {: .job-title}
> ## Senior iOS Developer
> <cite>Napster, Dec 2021 - Present</cite>

{: .work-list}
* Built new in app purchase flow and business logic for company's upcoming app refresh

> {: .job-title}
> ## Senior iOS Developer
> <cite>Triller, Mar 2020 - Nov 2021</cite>

[Triller](https://apps.apple.com/us/app/triller-social-video-platform/id994905763) has been a number 1 App Store app in 50 countries.

{: .work-list}
* Built a new camera interface from the ground up for arranging "takes" via drag and drop
* Refactored the architecture for the camera use case, vastly improving unit test coverage
* Rebuilt the projects screen from the ground up, improving time to load from 10+ seconds to milliseconds
* Built a "feature highlight" capability for promoting new app features
* Built a new video player for previewing and scrubbing through recordings in the camera
* Collaborated on proof of concept for modularising the project
* Proof of concept for moving authentication layer into a module, while maintaining compatibility with legacy code
* Built a new login/registration flow from the ground up
* Collaborated on moving a squad to an agile dev process

{: .tag-list}
* `MVVM-C`
* `AVFoundation`
* `Texture`
* `SOLID`

> {: .job-title}
> ## Senior iOS Developer
> <cite>Florence, Feb 2019 - Mar 2020</cite>

Created the [Florence](https://apps.apple.com/gb/app/florence-nurse-carer-shifts/id1481958477) iOS app; allowing nurses and carers to book care home shifts on the move, and get paid.

{: .work-list}
* Built the Florence iOS app from the ground up, adopting a `Clean` architecture.
* Full test coverage.
* Learned `Ruby/Rails` and worked on the entire stack; implementing restful API features, and the app notifications strategy on the company's `Rails` back end.
* Implemented an iPad app used to clock nurses in at a shift, using an `MVVM` architecture.
* Set up CI using Bitrise, and established git and release procedures.
* Worked closely with the Head of UX to iterate on prototypes.
* Interaction design for the Florence nurse app.

{: .tag-list}
* `Full Stack`
* `Clean`
* `SOLID`
* `Dependancy Inversion`
* `MVVM`
* `Swift`
* `Rails`
* `Ruby`
* `BitRise`

> {: .job-title}
> ## iOS Developer
> <cite>Raffler, Mar 2016 - Aug 2018</cite>

Created the [Raffler](https://www.telegraph.co.uk/men/thinking-man/raffler-introducing-the-app-that-could-win-you-1000-with-the-tou/) iOS app; a number one Lifestyle app in the UK and US.

{: .work-list}
* Built the app from the ground up, adopting a `VIPER` based architecture.
* Developed an open-source framework for [waterfalling ad requests](https://github.com/p-morris/WaterfallKit), achieving a 100% advertising fill-rate.
* Built a "Snapchat Stories" type feature, in which videos, interactive games, and other widgets could be embedded in a full-screen newsfeed.
* Developed and optimised an adaptive sales funnel within the app, which became the company's biggest source of revenue.
* Headed a project to improve user metrics. Achieved 90% install to registration, 85% day zero to day one retention, and doubled lifetime retention duration.
* Implemented an adaptive onboarding experience to provide relevant onboarding to varying user segments.
* Maintained the existing Android app.

{: .tag-list}
* `VIPER`
* `iOS`
* `Android`
* `Swift`
* `Java`
* `XCTest`
* `CoreAnimation`
* `AVFoundation`
* `Mixpanel` 
* `Firebase`

> {: .job-title}
> ## iOS Developer
> <cite>Mumsnet, Sep 2014 - Jan 2016</cite>

Developed [Mumsnet Talk](https://apps.apple.com/gb/app/mumsnet-talk/id437769914); an app for accessing a social discussion forum with ten million users.

{: .work-list}
* Built the app from the ground up, selecting `MVVM` as the architecture.
* Created a framework which could be integrated into any app to access forum data. Integrated this into the [Mumsnet Baby Bundle](https://www.thisismoney.co.uk/money/smallbusiness/article-3308545/Parenting-support-website-Mumsnet-unveils-new-baby-monitoring-app.html) and [Mumsnet Pregnancy Tracker](https://apps.apple.com/gb/app/mumsnet-pregnancy-tracker/id1037887244) apps.
* Developed a framework for dynamic processing and rendering of Mumsnet’s custom markdown in text containers.
* Successful relaunch of Talk app; the new app improved Mumsnet’s app rating to 4.5 stars.
* Apple gave a press launch for the app in their Regent Street store.

{: .tag-list}
* `MVVM`
* `Swift`
* `Objective-C`
* `XCTest`
* `CoreData`

> {: .job-title}
> ## Contract iOS Developer
> <cite>Mindtools, 2013 - 2014</cite>

Created and relaunched [MindTools](https://apps.apple.com/gb/app/mind-tools/id420985422); a universal app which acts as a library of business-related training articles, videos and learning tools.

{: .tag-list}
* `Objective-C`
* `CoreData` 

> {: .job-title}
> ## Contract iOS Developer
> <cite>Intellisense.io, 2012 - 2013</cite>

Created BRAINS; an enterprise iPad app used to provide analytics and visualise SAP sales data for the manufacturing industry.

{: .tag-list}
* `Objective-C` 
* `CoreData` 
* `CoreAnimation` 
* `CoreLocation` 

> {: .job-title}
> ## Contract iOS Developer
> <cite>Mubaloo, 2011</cite>

Developed SalesConnect; an enterprise iPad app featured in the [Financial Times](/assets/schroders-sales-connect.pdf). SalesConnect is used to manage, view and curate presentations from Microsoft Sharepoint documents, and was developed for the internal use of the investment bank Schroders.

* Nominated for "Best Developer of an Enterprise App" at the 2012 Mobile Entertainment Awards.

{: .tag-list}
* `Objective-C`
* `AVFoundation`
* `CoreAnimation` 
* `CoreData` 