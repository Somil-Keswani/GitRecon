# GitRecon
GitRecon is a lightweight and portable github reconnaissance tool, it searches for sensitive information like Secret Keys, Private Keys, AD credentials etc. commited/pushed to the Github public repositories.

It accepts Target Company Domain, <a href="https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens" target="_blank">Github Access Token</a> and Prefilled Sensitive Info from dropdown box but it can also conduct repository scan optionally by accepting "Custom Keyword" making it powerfull tool having wider search coverage. The output contains the Repository path, URL and highlighted search keywords.

## Deployment
It can be easily deployable with minimal dependency i.e webserver like Python-SimpleHTTPServer.

Follow the below steps to deploy the GitRecon:
1. Clone the GitRecon repository.
2. Place the repository's files in the webserver.
3. Open the index.html to access the tool.

### GitRecon Page
![GR_Landing_Page](https://github.com/Somil-Keswani/GitRecon/assets/30586163/1c26b1ea-afc5-4a31-aa88-20044587a11c)

## Author
* [Somil Keswani](https://www.linkedin.com/in/somil-keswani/)

