# Ch 2. Take Care of the Team

During one part of my career, I worked on a team with a particularly active on-call rotation. By "active," I mean
an on-call rotation where the FireFigher could get paged twenty times on a bad weekend. This situation was compounded
by a short rotation consisting of six engineers. As a result, every engineer "held the pager" every six weeks for an
entire week. The root cause of the active on-call was a flaky third-party integration that was critical to the company.
Multiple engineers on the team had raised this problem to the manager, letting them know the company ran the risk
of burning out the entire team.

A new teammate, an intern turned Full-Time, Sammy, had joined the team a few months ago. Given Sammy's experience and
the need for more people to join the on-call, Sammy was enlisted in the rotation. Although Sammy was new, she was
dedicated to executing on her tasks and producing results.

During one weekend, Sammy received thirty pages on a Saturday. As the Tech Lead, I had checked in our `#on-call` Slack
Channel every few hours given that Sammy was new to the rotation - to see how they were doing. To my dismay, I
observed the high number of pages that must've been ruining Sammy's day. I sent a Direct Message to Sammy
around 10 PM on Saturday:

::: {.conversation}
    Me: Hi Sammy - I've seen the number of pages fired today. How are you doing?

    Sammy: I'm OK. Yes, it's been a rough day.

    Me: You must be exhausted. Please let me take over the page now and you can
     pick it back up on Monday morning. Please get some rest on Sunday.

    Sammy: OK - thank you!
:::

After I concluded the message with Sammy, I sent an email to my manager:

::: {.conversation}
    Dear Bill -

    Sammy received thirty pages today. All of the incidents appear to be related to
     our flaky integration. I've been in her shoes and know how nerve-wracking and
     unpleasant a thirty-page day is. I think it's fair that Sammy be granted
     an additional day of Paid Time Off (PTO) given that her entire Saturday was consumed
     by answering PagerDuty. Can you please approve of that?

    I know the team has kicked around a few ideas on how to apply a band-aid fix
     to this problem -in the name of improving the on-call experience of an Engineer.
     I personally think our team will burn out given the frequency of pages,
     as well as the demoralizing effect of not being able to address the root cause.

    I set up a meeting on Monday to discuss a few solutions to improve this
     dire situation, please.

    Thanks,
    Kevin
:::

\newpage