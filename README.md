Thomas Nghiem <br>

1. Within a Github action whenever code is pushed. This is because this helps with incremental development, always checking if new code meets the standard requirements by passing these automated tests.
2. No, checking correctness of functions would be more in unit testing, while end to end testing would focus more on user actions.
3. Navigation mode is checking performance metrics for loading the page, while snapshot mode checks the metrics at the current state of the page, which is useful to check how metrics change after different interaction and states.
4. The lighthouse results show that there are possible optimizations with image sizes and formatting. Also, including a `<meta name="viewport">` tag with width or initial-scale would be useful in decreasing delay and making this more accessible for mobile devices. A third point of optimization is with the lang attribute for `<html>` element for accessibility for different readers.





