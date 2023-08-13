| Month    | Savings |
| -------- | ------- |
| January  | $250    |
| February | $80     |
| March    | $420    |

# User stories
| User story ID | Priority | Type               | As a <type of user>          | I want to <perform some task>                                | So that I can <achieve some goal>                       | Final story |
|---------------|----------|--------------------|------------------------------|--------------------------------------------------------------|---------------------------------------------------------|-------------|
| 1             | High     | Home Page          | First-time visitor           | Quickly understand what Docker-UI offers                     | Decide if the application is relevant to me.            | Yes         |
| 2             | High     | Documentation Page | Unexperienced user           | User-friendly documentation page                             | Easily learn what features the website offers.          | Yes         |
| 3             | High     | Login/Signup Page  | Returning user or new member | Seamlessly load previous sessions' content                   | Be satisfied and make decisions based on previous data. | Yes         |
| 4             | High     | Dashboard Page     | Registered user              | Centralized dashboard to interact with a container’s actions | Manage created containers during their execution.       | Yes         |
| 5             | High     | Logger's Page      | Experienced user             | See logging messages within the browser                      | Easily debug running containers.                        | Yes         |
| 6             | Medium   | Docker Hub         | Product owner                | Simply distribute Docker UI                                  | Dispense the application quickly to interested users.   | Yes         |

## Design tasks
| ID | Type               | Design Steps                                                                                                                                                                                                                                                                                                             |
|----|--------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1  | Home Page          | Display a clear and catchy headline that describes our value proposition.<br />  Include a captivating hero image or illustration that resonates with our brand.<br />  Add a login button that guides users to explore further.<br />                                                                                   |
| 2  | Documentation Page | Setup and host documentation pages via Github Pages.<br />  Organize the documentation in an easily understandable format.<br />  Provide comprehensive information on how the website is organized.<br />                                                                                                               |
| 3  | Login/Signup Page  | Offer a clear login and registration form with fields for email and password.<br />  Allow users to sign up using social media accounts for convenience.<br />  Provide password recovery options and ensure a secure login process.<br />                                                                               |
| 4  | Dashboard Page     | Design a clean and organized dashboard layout.<br />  Display account information and settings through intuitive and easy to use icons and widgets.<br />  Ensure easy navigation between different sections or features.<br />                                                                                          |
| 5  | Logger's Page      | Redirect container logging messages to the browser to easily read them.<br />  Create an intuitive interface that allows users to easily navigate across the available features of the logging page.<br />  Decide on the technologies necessary to setup the real time interaction between the client and server.<br /> |
| 6  | Docker Hub         | Gain the technical expertise needed to setup a Docker Hub release through existing examples.<br />  Setup dependent containers that need to be installed along-side Docker-UI.<br />  Exhaustive tests on multiple machines to ensure that the release works consistently across different Operating Systems.<br />      |
