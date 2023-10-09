# Async

Built on JS Promises

Can use `await` keyword to pause in the code for a process to finish/resolve a `promise`.

Use try-catch on API methods. Be sure to handle errors

Should `await` the services `get` request before continuing the controllers `get` method, so we can catch the error thrown. Generally `await` anything that has a `promise` returned.