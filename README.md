#NOTE
This site is undergoing a redesign!  You can try the [beta site](http://dev.modern.ie/platform/status) and continue to file issues here. It's our goal to continue to allow contributions to the site and its data through GitHub. But while we migrate to our new design, we'll only be taking Pull Requests for [ie-features.json](https://github.com/MicrosoftEdge/Status/blob/production/app/static/ie-status.json) for the time being.  We hope to complete this migration and open up PRs broadly for the site soon!

#Status
This project contains the source code and data for [status.modern.IE](https://status.modern.IE), a portal for the latest implementation status and future roadmap for interoperable web platform features in Microsoft Edge and other browsers, including Internet Explorer.

##Using Status Data
Status.Modern.IE provides valuable data on the implementation status and future plans for web platform features in Microsoft Edge. This data is encouraged to be used for other purposes as licensed by the [Creative Commons Attribution 2.5 License](https://creativecommons.org/licenses/by/2.5/legalcode). This data is provided as a JSON document, served at https://status.modern.IE/features. This data is sent with an "Access-Control-Allow-Origin: *" header, so it may be requested cross-domain.

##Building the Project
### Prequisites
1. Install Node.JS, NPM
2. npm install -g bower
3. npm install -g yo
4. npm install -g grunt-cli

### Build, run, and debug
From the project's root directory

1. npm install
2. bower install
3. grunt build
4. node app.js debug

A Node server will start at http://localhost:9000

## Contributing
Want to contribute to this project? We'd love to have your help!  Take a look at the [Contributing Guidelines](https://github.com/InternetExplorer/Status.IE/blob/production/CONTRIBUTING.md) before you dive in. For many features, support data for browsers other than IE & Edge comes from the [Chromium Dashboard](https://www.chromestatus.com) and bugs against that data can be filed [here](https://github.com/GoogleChrome/chromium-dashboard/issues).

Note that this GitHub project is *not* for making feature requests for or reporting bugs in Internet Explorer or Microsoft Edge. Browser feedback can be provided at [Microsoft Connect](https://connect.microsoft.com/ie).

## Additional Attributions
Portions of the content in this page from chromestatus.com, used under [Creative Commons Attribution 2.5 License](https://creativecommons.org/licenses/by/2.5/legalcode)

HTML5 Logo and related Technology Class iconography by W3C, used under [Creative Commons Attribution 3.0 License](https://creativecommons.org/licenses/by/3.0/legalcode)

JS Logo used under the [MIT License](https://github.com/voodootikigod/logo.js/blob/master/LICENSE)

No trademark licenses or rights are provided. All trademarks are the property of their respective owners.
