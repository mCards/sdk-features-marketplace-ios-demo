# mCards iOS Features Marketplace SDK Demo App

The mCards iOS Features Marketplace SDK encapsulates the following functionality:

A) Feature meta operations:
1. view active and available features
2. add features to a card
3. accept feature T&Cs
4. reoder features
5. deactivate features

B) Secure web features

C) Native features: 
1. Transfer funds to another user (send mCard)
2. Card controls 
3. Convert points 
4. Locations & offers
5. Gifts

# Importing
The SDK can be imported via SPM (Swift Package Manager).

- In XCode, go to: File -> Add Package Dependencies
- In the search bar enter: `https://github.com/Wantsa/sdk-features-marketplace-ios-framework`
- Choose a dependency rule (e.g. `Up to Next Major` with `1.0.0`
- Click `Add Package`

# Usage
Implementing apps must take additional steps if using the SDK and Auth0 as a token provider. In Xcode:
- Go to the info tab of your app target settings
- In the `URL Types` section, click the `+` button to add a new entry
- Enter `auth0` into the `Identifier` field and `$(PRODUCT_BUNDLE_IDENTIFIER)` in the `URL Schemes` field. Leave other fields blank

# Documentation
[Documentation site](https://mcards.readme.io/)

[SDKs conceptual documentation](https://mcards.readme.io/docs/mcards-sdk-overview)
