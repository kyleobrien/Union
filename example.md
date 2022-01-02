<pre>
---
Charter: Explore new feature with product documentation to discover discrepancies between the two.
Tester(s): Kyle O'Brien
Work Item: 16807
Tags: initial, nonfunctional, accessibility, ui
Start: 2018-01-31 15:00
Stop: 2018-01-31 15:45
ID: f83254cf-9c16-4caf-9363-d58c756418ac
---

# [New Accessibility Feature for Users with Visual Impairment](http://link.to.the/system_under_test/in/tracker/123)

## Notes

-   Brief review of the existing functionality. Created a mind map of the UI based on my current mental model and hypothesized some potential transitions that may not exist.
    -   [Mind Map of New Feature](./link_to_mind_map.ext)
-   Did some setup work for the tests to follow.
    -   Configure environment.
    -   Create data.
    -   Enable accessibility option and smoke test major functionality.
-   Proceed through the new user signup flow as a regular user would.
    -   Seems ok.
-   Turn the accessibility option on, which should introduce some additional buttons into the UI.
-   Use the Leapfrog heuristic.
    -   **[(2018-01-31 15:23) It let me skip a required step when I pressed a button that appeared disabled.][17005]**
    -   Pinpoint: Was that an existing bug, or is it only because I enabled the new functionality?
        -   After experimenting, it's only in the new functionality.
    -   If that didn't work as expected, maybe the sign-in process will behave in a similar way?
        -   No, that was fine.
    -   How about referring a friend? That has the same type of flow. Let's see what happens.
        -   *(2018-01-31 15:27) This functionality doesn't work how I thought it would. Investigate later, maybe as part of another session. Might need a discussion with a project manager to help fill the gaps in my knowledge.*
-   Backtrack and try a different path through new user signup.
    -   There's a few menu options I haven't explored. Try one at a time.
        -   Option 1 is good.
        -   **2018-01-31 15:36) Option 2 crashes the application after displaying an error message.**
            -   ![Screenshot: The error message.](./option_2_error_message.jpg)
        -   Option 3 is good.
-   Based on this session, getting through the rest of the new functionality will take at least two additional sessions of equal or greater length.
-   The provided documentation is often deficient or confusing. Talk to the test lead about getting this improved, or consider inviting a developer to the next test session so they can answer questions as they arise.

## Debrief

-   Talked with both Liam and Finn, as well as our Test Manager Tara.
-   She thinks it would be wise to revisit other accesibility features that were done in the past, but had minimal testing due to a lack of resources at the time.
-   I'm going ask Liam to perform at least one of the other sessions for this functionality. His fresh eyes might notice some bugs I missed.

[456]: http://link.to.the/bug/in/tracker/456
</pre>
