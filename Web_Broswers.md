# Key Components & Functions of Web Browsers

## **How do browsers load, display, and interact with websites?**
- Loading:
    - The browsers converts URLs into IP addresses using DNS (Domain Name System).
    - The browser then sends a HTTP(S) request to the website's host server to retrieve the required resources.
- Rendering
    - The browser uses a rendering engine to process HTML, CSS, and JavaScript on a website.
    - The browser creates a DOM (Document Object Model), which represents the pages structure in a way the browser can manipulate.
    - A CSSOM (CSS Object Model) is generated to handle styles.
    - The browser uses a compositor to combine the layers into a visible page.
- Displaying
    - After all of the processing and rendering the browser displays the web page to the screen.
- Interacting
    - JavaScript engines handle dynamic content and interactivity, like clicks, form submissions, or scrolling.
    - UI components allow user interaction, and real-time communication technology allows for dynamic content interaction without reloading the page.

## **How do browsers use protocols like HTTP or HTTPS to access websites?**
- Browsers use HTTP (Hypertext Transfer Protocol) to communicate with and access web servers and websites.
- HTTPS (HTTP Secure) is a more secure version of HTTP.
- Browsers send an HTTP/HTTPS request to the server, which includes metadata like browser type and personal preferences.
- HTTPS has an extra step: establishing a secure connection using SSL (Secure Sockets Layer)/TLS encryption (Transport Layer Security).
    - SSL is an older encryption protocol that is less secure and largely outdated in the modern day.
    - TLS is the newer/modern version of SSL that is more secure and widely used in the modern day.
- When a HTTP(S) request is processed the server will respond with the requested resource.

## **How do browsers help fix internet performance issues like slow-loading pages or big images?**
- Storing copies of frequently accessed resources locally, in a process called caching. This reduces the need to redownload said resources on every visit, speeding up website load time.
- Browsers will compress resources sent by the server, reducing the size and download times.
- Browsers will only load critical content (like on screen images) when needed, in a process called lazy loading.
- Browsers minimize bandwidth usage by using content optimizers, which decrease the size of an image while retaining its quality.

## **What role do browsers play when working with web servers? (e.g. running scripts)**
- Browsers are interpreters 
- Requesting Content; HTTP/HTTPS for specific resources (HTML, CSS, JavaScript)
- Rendering Content; making the DOM file and applying all the starter script on the page
- Running Scripts: JavaScripts, APIs, security contexts
- Handling Server Communication: allow scripts to make asynchronous requests to servers to update parts of a page without reloading
- Storing Data
- Enforcing security
- Error handling
- client/servers

## **How might IoT devices use browsers to manage or show data**
- IoT devices use browsers to create accessible, user-friendly interfaces that make managing and understanding complex systems simple and intuitive.
- Web-based Dashboards
- Data visualization: EX: fitness tracker: bar graphs
- Device Control (send command through IoT device to change thermostat settings)
- Local Network management (can hose local web server and give IP address ) EX: using printer from a website