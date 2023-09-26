**What is Emmet?**
Emmet is the abbreviation we used in our code. VS Code will automatically generate the abbreviation into full code.

**Crossorigin In Script Tag**
The crossorigin attribute sets the mode of the request to an HTTP CORS Request. Web pages often make requests to load resources on other servers. Here is where CORS comes in. A cross-origin request is a request for a resource (e.g. style sheets, iframes, images, fonts, or scripts) from another domain.

**Difference between a Library and Framework?**
To summarize, the key difference between a library and a framework is that a library provides specific functionality that the developer can use as needed, while a framework provides a complete structure for building an application, with the developer's code called by the framework. In other words, a library is something that you use to solve a specific problem, while a framework is something that you use to solve a broader set of problems, such as building an entire application.

**What is CDN? Why do we use it?**
*basically static content is cached in the content cache*
CDN stands for Content Delivery Network. It is a distributed network of servers that are strategically placed around the world to deliver content to users more quickly and efficiently. When you access a website or application that uses a CDN, the CDN will determine which server is geographically closest to you and serve the content from that server. This results in faster load times and a better user experience.

CDNs are used to improve the performance and reliability of websites, mobile applications, and other internet-based services. They can handle large amounts of traffic and help to reduce the load on the origin server. Additionally, CDNs can provide other benefits such as improved security, scalability, and availability.

CDNs are especially useful for websites and applications that have a global audience or experience high levels of traffic. By using a CDN, these sites can ensure that their content is delivered quickly and reliably to users around the world.

**Why is React known as React?**


**What is diference between React and ReactDOM**

**What is difference between react.development.js and react.production.js files via CDN?**
In development, it is common to use a CDN (Content Delivery Network) that serves the React code directly from the web without any optimizations. This allows developers to quickly and easily access the React library and other related resources needed for development purposes, without having to worry about optimizing or bundling the code.

On the other hand, in production, it is important to optimize the React code to reduce load times and improve the user experience. This typically involves bundling the code and minimizing its size by removing any unnecessary code and dependencies. This optimized version of the code is then served from a CDN that is specifically designed for production use, with features like caching and edge caching to further improve load times.

Additionally, in production, it is common to use a build tool like Webpack or Rollup to compile the React code and other assets into a single bundle that can be easily delivered to the user. This bundle can be uploaded to a CDN, and the CDN will serve the optimized version of the bundle to the user.

Overall, the main difference between using a React CDN for development versus production is that in development, the focus is on ease of use and accessibility, while in production, the focus is on performance and optimization.

**What is async and defer? - see my Youtube video ;)**
It is used in script tags it is basically a bollean attribute that is passed in script tag.
In normal script tag "<script src=''>" => Browser parse html and when it encounters a script tag it fetches the script from network and then executes it and then again start parsing if any.
If async attribute in script "<script src='' async >" => Browser parse html and when it encounters a script tag it fetches the script from network asyncronusly and keeps parsing until script is completely fetched once it fetched it stops parsing and executes the script after completely executing the script then again start parsing. Order of execution of script may vary.
In defer attribute in script tag "<script src='' defer >" => Browser parse html if it encounters a script tag it fetches the script from network asyncronusly and then completes parsing then after completely parsing it executes the script.It maintains the order of the script.
