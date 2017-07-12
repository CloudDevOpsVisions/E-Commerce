<h1 align="center">
	<br>
	<img src="http://devopsthoughts.spera.systems/DevOpsThoughtsLogo.png" alt="DevOpsThoughts Logo">
	<br>
</h1>

# DevOpsThoughts
<strong>DevOpsThoughts</strong> is a community initiative aims to teach the best practices in DevOps through a multi-platform application which targets variety of technologies. 
DevOps is one of the most emerging topics of software development today as it improves the whole software development process, but unfortunately, there is no clear, detailed and explicit model to teach the best DevOps & Software Engineering practices on real world projects, this was the main problem that lead to DevOpsThoughts community establishment.

DevOpsThoughts teaches the best practices on a series of real world e-commerce projects, each of which is 
<ul>
<li> Named after an animal name (We love animals, who doesn't?) </li>
<li> Built with a specific set of technologies </li>
<li> Is a branch in the DevOpsThoughts E-Commerce repository </li>
</ul>

### DevOpsThoughts Architecture
Visualization is the best way to understand DevOpsThoughts architecture, below is a list of useful diagrams to explain this.

<ul>
<li><strong><a href="#ad">Architecture Diagram</a></strong>: which is a graphical representation of concepts, elements and their usage within the application</li>
<li><strong><a href="#ucd">Use Case Diagram</a></strong>: a representation for all interractions within the solution.</li>
<li><strong><a href="#pl">Project Explorer View</a></strong>: A screenshot from Visual Studio for the whole solution.</li>
</ul>

### Quick Start

Run the following commands and replace the BranchName with the name of the branch you want to clone.

```
git clone https://github.com/DevOpsThoughts/E-Commerce.git  -b BranchName
cd E-Commerce
```





# DevOpsThoughts Rabbit

DevOpsThoughts Rabbit is the first project in DevOpsThoughts Series. It's an e-commerce website built with the following technologies:
<ul>
<li>ASP.NET MVC 5</li>
<li>Microsoft SQL Server 2014</li>
<li>Modern UI Tools & Frameworks, Like Twitter Bootstrap & Font-Awesome</li>
</ul>

Below is the homepage for DevOpsThoughts Rabbit
<h1 align="center">
	<br>
	<img width="880" height="1556" src="http://devopsthoughts.spera.systems/DevOpsThoughtsDesignWithNoValidContent.png" alt="Homepage Design">
	<br>
</h1>


# Development Steps
As we're developing a model for learning, we had to make a precise plan for the whole development process, using Scrum, user stories and behavior driven development (BDD) we can simply but the plan into this list:

## User Stories & Product Backlog Items (PBIs)

<ul>
<li><strong>User Story</strong> is a description of a specific functionality from an end-user perspective.</li>
<li><strong>Product Backlog Item</strong>is a single unit of work, here we mapped each user story to a PBI, so a PBI is a user story plus acceptance criteria, priority and tags.</li>
</ul>
For each user story, we develop a Product Backlog Item (PBI), assign proper tags to it based on publicity (Public/Private), main actor (Visitor/Member/Vendor/Admin) and work flow type (Basic/Advanced), then we add its <strong>Acceptance Criteria.</strong>
<strong>Each Acceptance Criteria Consists of two main parts:</strong>
<ul>
<li><strong>Action Criteria: </strong>Is the options available for use and system respond to it.</li>
<li><strong>Input Validation Criteria: </strong>Used only when there is an input forms being used to clarify each input type, boundaries and importance.</li>
</ul>
All PBIs are made on two levels
<ul>
<li><strong>Initial PBIs</strong>: Contains each PBI's Title, Order, Tag and description (Description is the user story).</li>
<li><strong>Detailed PBIs</strong>: Contains the initial PBIs content with enhancements to maintain consistency, plus the acceptance criteria.</li>
</ul>
All BWF PBIs are added to the source control in plain text format, so we can quickly trace any changes to it.

Below is the sample for Vendor's login <strong>Initial PBI</strong>.

<h1 align="center">
	<br>
	<img width="957" height="238" src="http://devopsthoughts.spera.systems/IPBISample.png" alt="Vendor Login Initial">
	<br>
</h1>

Another sample for Vendor's login <strong>Detailed PBI</strong>.

<h1 align="center">
	<br>
	<img width="957" height="575" src="http://devopsthoughts.spera.systems/PBISample.png" alt="Vendor Login Detailed">
	<br>
</h1>


<strong>You can click <a href="#PBIsList">here</a> to view the complete list of all Basic Work Flow PBIs</strong>

----
## Test Cases
Test Cases are very important for Behavior driven development, In DevOpsThoughts, we have test cases written on three levels
<ul>
<li>Conceptual Test Cases</li>
<li>Functional Test Cases</li>
<li>Usability & Functional Test Cases</li>
</ul>

### Conceptual Test Cases
Conceptual Test Cases are the most abstract form of test cases made with conceptual input only for purpose of conceptualizing the flow itself.
### Functional Test Cases
Functional Test Cases made for testing the application functionality without discussing UI elements or UX, just making sure the application outputs the suitable output when some input is provided.
### Usability & Functional Test Cases
Usability & Functional Test Cases are the most detailed test cases, it cares not only for functionality as functional test cases, but also for the way application responds to user actions from user experience (UX) and user interface (UI) perspective.

----
## Use Case Scenarios
Use Case Scenario is a list of user actions and system response to it. In DevOpsThoughts, we map each PBI to a single use case scenario. Each scenario has the following:
<ul>
<li><strong>Related PBI</strong>: The related PBI name & Id.</li>
<li><strong>Main Actors List</strong>: A list of all actors involved in the specified use case.</li>
<li><strong>Pre-conditions</strong>: A list of all conditions that must be met before the use case starts in order for the use case to be valid, example: <i>Vendor has been logged in to his account</i>.</li>
<li><strong>Basic Flow</strong>: or what we call sometimes <strong>Happy Path</strong> is the normal expected flow for the use case with the default system settings, where the use case is expected to succeed as per main actors expectations.</li>
<li><strong>Alternative Flows</strong>: If available, alternative flows of a use case are the flows where main actors expectations are not met yet.</li>
<li><strong>Post-conditions</strong>: A list of all conditions that must be met after the use case ends in order for the use case to be valid, example: <i>Order was saved in the application</i>.</li>
</ul>
Also as in PBIs, use case scenarios are divided into <strong>Initial</strong> and <strong>Detailed</strong> use case scenarios.
<ul>
<li><strong>Initial Use Cases</strong>: Have the above structure, but with more abstraction level, so not much attention was giving to the details, but to make simple process outlining.</li>
<li><strong>Detailed Use Cases</strong>: Have the same structure as the initial use cases, but with more details, like the input/output information and user controls available.</li>
</ul>


Below is the sample for Display Products List <strong>Initial Use Case Scenario</strong>.

<h1 align="center">
	<br>
	<img width="957" height="439" src="http://devopsthoughts.spera.systems/InitialUseCaseScenarioExample.png" alt="Use Case Initial">
	<br>
</h1>

Another sample for Display Products List <strong>Detailed Use Case Scenario</strong>.
<h1 align="center">
	<br>
	<img width="957" height="520" src="http://devopsthoughts.spera.systems/DetailedUseCaseScenarioExample.png" alt="Use Case Detailed">
	<br>
</h1>

----

## Basic Mockups
Mockups are very basic UI representation used to deliver an abstract format of the expected to UI design to a UI developer from end-user or product owner perspective.
### Making Mockups
Mockups are usually made using a basic photo edition application like MS Paint or Paint.NET.
### Level of Details
Mockups usually represents only an abstract view of a webpage, Only spaces occupied and by which elements, doesn't include icons, content nor colors.

----
## PhotoShop Designs (PSDs)
Based on Test Cases, Basic Mockups and PBIs, the final PSDs are made for the Project, A PSD file is a Photoshop Design file which can be edited later, PSD files are kept up-to-date with any modifications made to the UI.
### Level of Details
PSD Designs are made while keeping attention to details. We can - from logical point of view - look to the Basic Mockups as <strong>initial designs</strong>, while the PSDs are the <strong>detailed designs</strong>.

Below is a sample for the Final PSD Design for the homepage, and it's identical with the screenshot for the homepage at the very beginning of this readme file.

<h1 align="center">
	<br>
	<img width="957" height="1431" src="http://devopsthoughts.spera.systems/PSD.png" alt="PSD">
	<br>
</h1>


----
## Website Components (HTML, CSS and JavaScript)
Website components are simply the source code for UI, alongside with any elements used in the UI such as images, icons and libraries.
The Website components isn't only used for Rabbit, but the same are used for other versions of the project which is using web as a presentation layer.
Developing the website components uses PSDs as an input, each PSD is converted - as it is - to be a separate web page.
We gave much importance to utilize and minify all of UI source files.
After each PSD is converted, it is reviewed on two levels
<ol>
<li><strong>External</strong>: Which is making sure that the web page matches 100% the provided PSD.</li>
<li><strong>Internal</strong>: Which is checking for source code quality, readability and if the code is minified.</li>
</ol>



----
## Storyboarding
A Storyboarding is an illustration for a user interaction with application story, not to be confused with user stories, in storyboarding we use visual images arrayed together for user interaction with the application to represent.
Storyboards are easier to be remembered than other written Test Cases, as it shows the real UX, not just some text about it.
In DevOpsThoughts we use Microsoft Office's PowerPoint, which allows develops to make an animated representation of User interaction with application UI quickly with higher quality.
If we look to the PSDs and Basic Mockups as a User Interface representation, we should consider Storyboarding to be the <strong>User Experience Representation</strong>.

----
## Products Data

To give the application some reality, we have added more than 400 Products, and we're still adding more frequently.
For each product, the following information is added
<ul>
<li><strong>Code</strong>: A unique alphanumerical code used to identify each product.</li>
<li><strong>Title</strong>: The main title for the product itself.</li>
<li><strong>Description</strong>: A detailed description about the product in text, used to promote the product but not for the technical specs, is it's described in another part.</li>
<li><strong>Category Id</strong>: The Id for category where product is assigned too, but this isn't being displayed explicitly to application users, But it's the actual way a product is linked to category.</li>
<li><strong>Category Name</strong>: this is what vendors see when they add the product, and members/visitors see when they search for products of a specific category.</li>
<li><strong>Brand</strong>: This is the manufacturer brand, example: Microsoft, HP, Nokia.</li>
<li><strong>Reward Points</strong>: Points which is added to each user so he can receive rewards after making purchases with a specific amount.</li>
<li><strong>Price</strong>: The Original Price for the product.</li>
<li><strong>Discount</strong>: The discount amount on the product, if any.</li>
<li><strong>Specification</strong>: A Key, Value map of all technical specification for a product, key value maps are used to give flexibility with different kinds of products.</li>
<li><strong>Key Features</strong>: Text representation of product Key features.</li>
<li><strong>Image</strong>: A URL for the product image.</li>

</ul>


----
## Pages List Grouped By User Roles
<ul>
<li>
Visitor
<ul>
<li>Home page</li>
<li>Product List Page</li>
<li>Product Details Page</li>
<li>Shopping Cart (Check Out) Cascading Menu Sub Page</li>
<li>Shopping Cart (Check Out) Page</li>
<li>Login Page</li>
<li>Add/Edit Delivery Address Page</li>
<li>Order Complete Page</li>
<li>Order Confirmation email</li>
<li>Registration Page</li>
</ul>
</li>
<li>
Member
<ul>
<li>Forget the Password</li>
<li>Display/Edit Account Info</li>
<li>Order List Page</li>
<li>Addresses List Page</li>
<li>Payment Page (Note#6)</li>
<li>Dashboard (Member Home page)</li>
</ul>
</li>
<li>
Vendor/Admin
<ul>
<li>Order List Page</li>
<li>Order Details Page</li>
<li>Edit Order Page</li>
<li>Add/Edit Product</li>
<li>Dashboard (Control Panel Home page)</li>
</ul>
</li>
<li>
Miscellaneous
<ul>
<li>Confirmation Message (Sub Page)</li>
<li>Loading (Sub Page or image)</li>
<li>Notification, Error, Warning</li>
</ul>
</li>
</ul>

<p id="ad"></p>

----

## Architecture Diagram
Architecture diagram is  a graphical representation of System components and how thery're (components) are groupped together. The UML Architecture Diagram gives use a general overview of how the system works and its principles.

<h1 align="center">
	<br>
	<img width="957" height="595" src="http://devopsthoughts.spera.systems/ArchDiagram.png" alt="Architecture Diagram">
	<br>
</h1>

<p id="ucd"></p>

----

## Use Case Diagram
Use Case Diagram is UML Diagram used to represent different interactions with the system. The Use Case Diagram also acts as an input for making PBIs and User Stories.

Below is the Use Case Diagram we have in DevOpsThoughts.

<h1 align="center">
	<br>
	<img width="957" height="869" src="http://devopsthoughts.spera.systems/UseCaseDiagram.png" alt="Use Case Diagram">
	<br>
</h1>

<p id="pl"></p>

----

## Project Layers
Below a screenshot from Microsoft Visual Studio's Solution Explorer for the different layers used in DevOpsThoughts.

<h1 align="center">
	<br>
	<img width="360" height="597" src="http://devopsthoughts.spera.systems/ProjectsList.png" alt="Use Case Diagram">
	<br>
</h1>



----
<div id="PBIsList"></div>

## List of Basic Work Flow Product Backlog Items (PBIs)

This is the complete list of BWF PBIs:

<ol>
<li>Display special offer products in a slider</li>
<li>Display top featured products in a slider</li>
<li>Display top new arrival products in a slider</li>
<li>Display top hot sale products in a slider</li>
<li>Display top best selling products in a slider</li>
<li>Display random products in a slider</li>
<li>Display all main and sub categories of products</li>
<li>Display products of a selected category</li>
<li>Provide paging for product lists</li>
<li>Access shopping cart from the home page</li>
<li>Display product detailed information</li>
<li>Add product to the shopping cart</li>
<li>Remove product from shopping cart</li>
<li>Review products in shopping cart</li>
<li>Add delivery address for the order</li>
<li>Review order before checkout</li>
<li>Place order after review as member</li>
<li>Place order after review as guest</li>
<li>Display all order made by visitors and members</li>
<li>Update completed order</li>
<li>Display orders history for members</li>
<li>Provide membership for visitors</li>
<li>Login to the member site</li>
<li>Login to the vendor panel</li>
<li>Login to the admin panel</li>
<li>Add product to the store</li>
<li>Display all added products</li>
<li>Update product data</li>
<li>Display all orders made by all users for all vendors</li>
<li>Update order status</li>
<li>Display order detailed information</li>
<li>Recover forgotten password</li>
<li>Change password</li>
</ol>


### About The Founder

<strong>Mohamed Radwan</strong> is an MVP (Microsoft Most Valuable Professional) in the Visual Studio ALM (Application Lifecycle Management) for 5 consecutive years and a DevOps Practice Lead. He focuses on providing solutions for the various roles involved in software development and delivery process to enable them to build better software through Agile Methodologies and utilization of Microsoft Visual Studio ALM/DevOps Tools and Technologies.<br/>
Mohamed has been working in software development industry for more than 17 years, starting as a classic ASP.NET developer in the year 2000 them moving to different roles as a senior developer, team leader, lead architect. For the last 7 years he has been passionate and focused about DevOps practices and automation. <br/>
Mohamed also worked in several countries in different regions, including United Kingdom where he works now, Sweden, Denmark, Egypt, Saudi Arabia, Kuwait, Oman, Libya. <br/>
Through his journey, he got the opportunity to work and help hundreds of companies to improve their software delivery practices.
He also issued a lot of guides for TFS (Team Foundation Server), developed many extensions for Visual Studio, made many open source libraries and projects on GitHub and authored many tutorials on YouTube, his blog and other communities.
He is also a regular speaker and participated in many local and regional conferences and events in all countries where He worked  in.<br/>
<ul>
<li><a href="https://mohamedradwan.com">Personal Blog</a></li>
<li><a href="https://www.youtube.com/user/MRadwanMSF">Youtube Channel</a></li>
</ul>
