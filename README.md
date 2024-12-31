This repository demonstrates a common error encountered when using catch-all routes (`*` or `/*`) in React Router v6.  The primary issue lies in the order and usage of these catch-all routes within the Route configuration.  The solution shows the correct implementation. The incorrect usage of `/*` causes a route matching conflict and results in an error during application initialization.