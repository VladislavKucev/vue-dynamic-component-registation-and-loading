# vue-dynamic-component-registation-and-loading
Just an example how to dynamically look for a component even if it's not registered

If you aren't a fan of Node.js like me, you can use https://play.vuejs.org/ to compile the .vue files into .js ones (ES modules). Or you can use https://template-explorer.vuejs.org/ in case you need only the render function in order to replace the { template: ... } with { render(...) }.


//============== EDIT ================//
1.html didn't handle slots correctly (I tried many different ways). If you intend to use slots then 2.html seems to handle them correctly (or at least I failed to bug them).
