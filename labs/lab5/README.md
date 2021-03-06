# Lab 10

## References

https://v4-alpha.getbootstrap.com/components/carousel/
http://stackoverflow.com/questions/30382423/my-bootstrap-carousel-code-doesnt-work
https://bl.ocks.org/mbostock/4063269
https://bl.ocks.org/mbostock/4060606
https://bl.ocks.org/mbostock/3883245
https://github.com/d3/d3-selection
https://www.dashingd3js.com/svg-basic-shapes-and-d3js
http://stackoverflow.com/questions/19215586/get-an-specific-value-of-css-class-using-d3js
https://jrue.github.io/coding/2014/exercises/basicbubblepackchart/
https://bl.ocks.org/john-guerra/0d81ccfd24578d5d563c55e785b3b40a
http://stackoverflow.com/questions/39368919/d3-bubble-chart-bubble-nodes-not-a-function
https://jsfiddle.net/r24e8xd7/9/


# Lab 9

## How to install

1. Install NodeJS.
2. Open a terminal at the project directory.
3. `npm install`
4. `npm start`
5. Navigate to localhost:3000.

## References

https://v4-alpha.getbootstrap.com/components/modal/
http://stackoverflow.com/questions/18153234/center-a-column-using-twitter-bootstrap-3
https://bootswatch.com/darkly/


# Lab 7

## References
https://docs.angularjs.org/api/ng/type/$rootScope.Scope#$watchGroup
http://mongoosejs.com/docs/guide.html#strict
http://stackoverflow.com/questions/15670067/mongoose-not-removing-objects-from-collections
http://stackoverflow.com/questions/20858299/model-find-toarray-claiming-to-not-have-toarray-method
https://docs.angularjs.org/api/ng/directive/ngChange

## Observations
See Lab 6 observations.
I liked both this and the previous lab for teaching us to manage technical debt, i.e. teaching us not to screw our future selves over by making hacky shortcuts.
My Bootstrap alert timeout assumes around 2.5 seconds in between each button click.

My 'additional styling' on tweets is changing the displayed format every time the dropdown changes.


# Lab 6

It's a better practice to place the CSV conversion code within the Node server, as the task relates more closely to interacting with the filesystem than showing changes to the user.

## References
http://stackoverflow.com/questions/24193102/node-js-express-making-post-request-without-redirecting-from-current-page
http://stackoverflow.com/questions/12304728/how-can-i-tell-angularjs-to-refresh
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise/then

## Observations
I'm glad we're allowed to reuse our Lab 5 code for this lab!
We should totally cover Promises in a lecture/lab.


# Lab 5

## References
https://dev.twitter.com/oauth/application-only
http://stackoverflow.com/questions/6182315/how-to-do-base64-encoding-in-node-js
https://nodejs.org/api/http.html
https://nodejs.org/api/https.html
http://stackoverflow.com/questions/29511076/oauth-twitter-statuscode-403-ssl-is-required-c-sharp
http://stackoverflow.com/questions/37913936/twitter-api-returning-empty-body-with-node-js

## Observations
I didn't want to use jQuery, so I used NodeJS' HTTPS module.
It's difficult to find simple examples of using the Twitter Streaming API online.
NodeJS's request module proved to be easier to use than its Twitter module.

## Questions
How could I have returned a Promise in the callback of res.on('data')? This would've allowed getTweets to be placed in a then() call in the 'main' function (app.post()).
