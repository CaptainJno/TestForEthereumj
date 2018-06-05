# TestForEthereumj

This is a test project to show the clash when i use ethereumj and web3j at the same time.

According to https://github.com/ethereum/ethereumj/issues/1079#event-1662709142,

The solution is adding following settings to android section of your app build.gradle :

    packagingOptions {
        merge "version.properties"
    }
    
 Thandks for @zilm13 's help.
