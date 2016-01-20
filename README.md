# synchronous-sofe-loader
synchronous-sofe-loader allows you to think of sofe services (which by definition are loaded at runtime in the browser) like any other dependency that you `import`. However, it comes with one major caviat -- you must ensure that you load all of the sofe services that you're going to use into the bootstrap phase of your application. In other words, you can't run the javascript that uses the sofe services before you have guaranteed that the sofe services have been loaded.
