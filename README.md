# ing-ideal-connectors-net
Opensource tools and API to connect webshops and merchants to ING using iDeal

[![AppVeyor Build status](https://ci.appveyor.com/api/projects/status/asev7lip46v816eo?svg=true)](https://ci.appveyor.com/project/checkout/checkout-sdk-net-74764)

## Checkout.com related notes

This is a spike to port [iDealAdvancedConnector](iDealAdvancedConnector) to .NET Standard 2.0. All the XML related classes compile, [](iDealAdvancedConnector/Connector.cs) needs some more attention. Most notably in the following areas.

- Configuration
- Certificate loading
- HTTP requests (we want to use HttpClient)
