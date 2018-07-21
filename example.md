<pre>
# [New Accessibility Feature for Users with Visual Impairment](http://link.to.the/system_under_test/in/tracker/16092)

## Session Metadata

-   Charter: Explore new feature with product documentation to discover discrepancies between the two.
-   Testers: Kyle O'Brien
-   Product Backlog Item #: 16807
-   Tags: initial, nonfunctional, accessibility, ui
-   Start: 2018-01-31 15:00
-   Stop: 2018-01-31 16:30

## Session Notes

-   Brief review of the existing functionality. Created a mind map of the UI based on my current mental model and hypothesized some potential transitions that may not exist.
    -   [Mind Map of New Feature](./link_to_mind_map.ext)
-   Did some setup work for the tests to follow.
    -   Configure environment.
    -   Create data.
    -   Enable accessibility option and smoke test major functionality.
-   Proceed through the new user signup flow as a regular user would.
    -   Seems ok.
-   Use the Leapfrog heuristic.
    -   __[(2018-01-31 15:23) It let me skip a required step when I pressed a button out of the order that was intended.][17005]__
    -   Pinpoint: Was that an existing bug, or is it only because I enabled the new functionality?
        -   Only in the new functionality...
    -   If that didn't work as expected, maybe the sign-in process will behave in a similar way?
        -   No, that was fine.
    -   How about referring a fried? That has the same type of flow. Let's see what happens.
        -   _(2018-01-31 15:27) Huh. I don't know what to think of this behavior. Investigate later, maybe as part of another session. Might need a discussion with the developer or project manager._
-   Backtrack and try something different.
    -   There's a few menu options. Try one at a time.
        -   Option 1 is good.
        -   __(2018-01-31 15:36) Option 2 crashes the application after displaying an error message.__
            -   ![Screenshot: The error message.](./option_2_error_message.jpg)
        -   Option 3 is good.

## Other Notes

-   Based on this session, getting through the rest of the new functionality will take at least two additional sessions of equal or greater length.
-   The provided documentation is often deficient or confusing. Talk to test lead about getting this improved, or consider a test session to focus on just the documentation. 

## Debrief

-   Talked with both Liam and Finn, as well as our Test Manager Tara.
-   She thinks it would be wise to revisit other accesibility features that were done in the past, but had minimal testing due to a lack of resources at the time.
-   I'm going ask Liam to perform at least one of the other sessions for this functionality. His fresh eyes might notice some bugs I missed.

[17005]: http://link.to.the/bug/in/tracker/17005
</pre>
