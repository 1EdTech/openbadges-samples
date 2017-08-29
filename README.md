# openbadges-samples
This respository is for sample code for Open Badge Assertions and related objects (BadgeClasses, Issuer Profiles). For each sample you wish to submit, please follow these steps.

1. Make sure you are looking at the master repository on IMSGlobal [openbadges-samples](https://github.com/imsglobal/openbadges-samples)
2. Create a new issue
3. Paste the json of the objects you would like to submit and a comment on the data they represent. Recommended: Post an Assertion, a BadgeClass, and Issuer Profile for completeness.
4. Add any additional comments to the issue.

Issues will be processed into data on the openbadges-sample server as appropriate or left open as discussion points while relevant.

## Test Server Usage:

This package includes a test server. You may clone it and use it for your local testing. Edit db.json to reflect the objects you want to serve.

Note the "id" properties are self referential. routes.json deals with this.

```
npm install
npm run server
```

Caveats:
* Assumes it runs on the default port localhost:3000 -- If you change this behavior, badge objects may not validate properly.
