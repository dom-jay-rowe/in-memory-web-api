## Intro

In this post, we are going to look at how we can use a tool from the official Angular repo called the `In Memory Web Api`. This can be used to intercept HTTP calls and receive mock data in return. Why would we do this, over simply using the backend put in place by the back-end development team? Well, a common situation that occurs is that this backend simply isn't there by the time the front end team comes to create and use the service. This API allows both sides of the development team to work in union rather than tailing each other.


## The In-Memory Web API

So, the In-Memory API is slight more intense than using simple packages, such as the `json-server` package available on npm. With the json-server package as an example, which is effectively just opening a glorified json file on a different port and making calls to it, this package grabs `Http` and `HttpClient` requests to a remote server, and diverts them to an in-memory store.

The Angular team which developed this package have stated - and rightly so - that this API is experimental, always changing, and should not be used for production sites. So if it can't be used on a live site, then what? Well, it can be good for several concepts; spinning-up prototypes, end-to-end testing and demo applications.

## Install the API

The easiest step here, would be actually installing the thing! Let's get the ball rolling with a simple `npm i angular-in-memory-web-api` for npm, or `yarn add angular-in-memory-web-api` for yarn.

# Notes

1. Set up service through cli
1. Brief explanation into a service - possible new post?
2. Can i used -f tag with this to show what is being created
3. Code example of service
4. We can do GET, PUT, DELETE, POST with this...how?


## Resources

[Github Repo](https://github.com/angular/in-memory-web-api)
[npm Package](https://www.npmjs.com/package/angular-in-memory-web-api)
[Angular Tutorial](https://angular.io/tutorial/toh-pt6)
[json-server](https://www.npmjs.com/package/json-server)
[Mocking with Angular](https://medium.com/@amcdnl/mocking-with-angular-more-than-just-unit-testing-cbb7908c9fcc)