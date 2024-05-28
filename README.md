# Lab8-Starter
Ekin Celik

[lab8](https://e-celik.github.io/Lab8-Starter/)

Service workers are a tool we can use to implement graceful degradation. In order to have G.D., we must be able to have the application function even when we are stripped of resources that may seem helpful, or even vital. For example, it may seem as though a webpage would not be able to load at all if the browser is not connected to the internet. However, as we saw in this lab, by using event workers, and their associated cache, we can intercept requests for data, and deliver them to the browser, without even having to access the internet. In this sense, since we are missing a connection, yet we are still delivering content to the user, we are practitcing graceful degradation.
