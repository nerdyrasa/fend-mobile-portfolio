## Website Performance Optimization portfolio project

### Resources

[resource minification and text compression with GZip](https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/optimize-encoding-and-transfer#minification-preprocessing--context-specific-optimizations)
[HTTP caching](https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/http-caching)

[Unblocking CSS With Media Queries](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/render-blocking-css)

[async attributr]()
[window.onload event](https://developer.mozilla.org/en-US/docs/Web/API/GlobalEventHandlers/onload)
[defer attribute](https://hacks.mozilla.org/2009/06/defer/)
[parser blocking vs. asynchronous JS](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/adding-interactivity-with-javascript#parser-blocking-vs-asynchronous-javascript)
[How to deliver a page that can be rendered in one second or less](https://developers.google.com/speed/docs/insights/mobile)
[Optimize Critical Rendering Path](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/optimizing-critical-rendering-path)

### General Strategies 

1. Minify, compress, cache (HTML, CSS, JS)
2. Minimize use of render blocking resources (CSS): Use media queries on <link> to unblock rendering and inline css.
3. Minimize use of parser blocking resources (JS): Defer JS execution and use asyn attribute on <script>

[List of course resource for Udacity Website Performance Optimization Course](https://www.udacity.com/wiki/ud884#!#course-resources)

### Browser Rendering Optimization

1. The Critical Rendering Path
2. App Lifecycles
3. Weapons of Jank Destruction
4. JavaScript
5. Styles and Layout
6. Compositing and Painting