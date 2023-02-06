# [React and Next.js is DEAD — Something New is (Finally) Replacing It (For Good)](https://javascript.plainenglish.io/react-and-next-js-is-dead-something-new-is-finally-replacing-it-for-good-c792c48806f6)
# Summary & Thoughts

The paradox of web development is discussed in this article, where more JavaScript is needed for features, but less is needed for a fast-loading site. Somnath Singh claims that current web frameworks are flawed and that the web development situation is a mess. The problem with typical web applications is that they have to start from scratch each time they load, leading to increased start-up time. Lazy loading has been used as a solution. Still, it fails to solve the problem of hydration, a process of the browser reading the JavaScript parts of a web page, determining which sections of the code belong where, and attaching event listeners to the page.

Singh introduces Qwik, a solution that only resolves a specific component when interacting with and recognizes dependencies between components. Qwik results in zero JavaScript on the initial page load. It's interesting to see how Qwik represents the concept of "less is more" in web development and how it aims to tackle the issues faced by current web frameworks by offering a more efficient and streamlined solution.

# David Chen's Comments
There is definitely many interesting components about this article. I think the author has a very structured approach in discussing the problems with Javscript and how to solve them and how qwik offers many solutions. 