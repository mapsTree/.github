![MapsTreeLogo](/profile/alone_name2.png)
# MapsTree

<h3>Description</h3>
<p>
  MapsTree lets you map events, issues and share activities in real time maps.
  The MapsTree has node express backend and react frontend.
  </p>

<h3>Scope of the Project</h3>
<p>Allows user to login and create events and mark issues on the map. Add a description about the event or issue.
</p>

<h4>Backend</h4>
<p>For authentication using oauth 2.0 google.<h5> I came across the question about how to protect the application from cyber attacks? Should the application not have a strong authentication? </h5>
There are two ways to authenticate the application which is using express-session or cookie-session.
As the express-session uses the backend server side storage for the user session this is not safe for production level application. For this we have to create a redits storage but that is not good as can affect the performace of the application. It can make the backend slow and also affect in terms of load balancing of the application.
</p>
<h5>The solution</h5>
<p>There are two ways to authenticate the application which is using express-session or cookie-session. One way is using the express s</p>

  
  <h4>Image Registry:</h4></br>
  [accountsService] (https://hub.docker.com/repository/docker/aditya7sinha/account-servicemain-api_service)</br>
  [inventoryservice] (https://hub.docker.com/repository/docker/aditya7sinha/inventory-service-inventory_service)

<h4>The UI/UX of the mapsTree using Figma:</h4>
<p>https://www.figma.com/file/XIImDb8eiKwMvKc9RiTe0H/MapSeed-Desktop?node-id=120%3A24&t=avmHFa5YRMwBGfyC-1</p>


<h4>Components of Architecture:</h4>
<ul>
  <li>Accounts Microservice</li>
  <li>Inventory Microservice</li>
  <li>Service Discovery</li>
  <li>API Gateway</li>
  <li>React FrontEnd</li>
  <li>Rabbit MQ</li>
  </ul>


<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
