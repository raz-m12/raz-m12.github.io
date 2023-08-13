| Month    | Savings |
| -------- | ------- |
| January  | $250    |
| February | $80     |
| March    | $420    |

# User stories
<table>
    <tr>
        <td>User story ID</td>
        <td>Priority</td>
        <td>Type</td>
        <td>As a &lt;type of user&gt;</td>
        <td>I want to &lt;perform some task&gt;</td>
        <td>So that I can &lt;achieve some goal&gt;</td>
        <td>Final story</td>
    </tr>
    <tr>
        <td>1</td>
        <td>High</td>
        <td>Home Page</td>
        <td>First-time visitor</td>
        <td>Quickly understand what Docker-UI offers</td>
        <td>Decide if the application is relevant to me.</td>
        <td>Yes</td>
    </tr>
    <tr>
        <td>2</td>
        <td>High</td>
        <td>Documentation Page</td>
        <td>Unexperienced user</td>
        <td>User-friendly documentation page</td>
        <td>Easily learn what features the website offers.</td>
        <td>Yes</td>
    </tr>
    <tr>
        <td>3</td>
        <td>High</td>
        <td>Login/Signup Page</td>
        <td>Returning user or new member</td>
        <td>Seamlessly load previous sessions&#39; content</td>
        <td>Be satisfied and make decisions based on previous data.</td>
        <td>Yes</td>
    </tr>
    <tr>
        <td>4</td>
        <td>High</td>
        <td>Dashboard Page</td>
        <td>Registered user</td>
        <td>Centralized dashboard to interact with a container’s actions</td>
        <td>Manage created containers during their execution.</td>
        <td>Yes</td>
    </tr>
    <tr>
        <td>5</td>
        <td>High</td>
        <td>Logger&#39;s Page</td>
        <td>Experienced user</td>
        <td>See logging messages within the browser</td>
        <td>Easily debug running containers.</td>
        <td>Yes</td>
    </tr>
    <tr>
        <td>6</td>
        <td>Medium</td>
        <td>Docker Hub</td>
        <td>Product owner</td>
        <td>Simply distribute Docker UI</td>
        <td>Dispense the application quickly to interested users.</td>
        <td>Yes</td>
    </tr>
</table>

## Design tasks
| ID | Type               | Design Steps                                                                                                                                                                                                                                                                                                             |
|----|--------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1  | Home Page          | Display a clear and catchy headline that describes our value proposition.<br />  Include a captivating hero image or illustration that resonates with our brand.<br />  Add a login button that guides users to explore further.<br />                                                                                   |
| 2  | Documentation Page | Setup and host documentation pages via Github Pages.<br />  Organize the documentation in an easily understandable format.<br />  Provide comprehensive information on how the website is organized.<br />                                                                                                               |
| 3  | Login/Signup Page  | Offer a clear login and registration form with fields for email and password.<br />  Allow users to sign up using social media accounts for convenience.<br />  Provide password recovery options and ensure a secure login process.<br />                                                                               |
| 4  | Dashboard Page     | Design a clean and organized dashboard layout.<br />  Display account information and settings through intuitive and easy to use icons and widgets.<br />  Ensure easy navigation between different sections or features.<br />                                                                                          |
| 5  | Logger's Page      | Redirect container logging messages to the browser to easily read them.<br />  Create an intuitive interface that allows users to easily navigate across the available features of the logging page.<br />  Decide on the technologies necessary to setup the real time interaction between the client and server.<br /> |
| 6  | Docker Hub         | Gain the technical expertise needed to setup a Docker Hub release through existing examples.<br />  Setup dependent containers that need to be installed along-side Docker-UI.<br />  Exhaustive tests on multiple machines to ensure that the release works consistently across different Operating Systems.<br />      |
