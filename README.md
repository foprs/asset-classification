# asset-classification
A repo with a classification for Asset Administration Shells

There is currently no standardized (from IDTA specified) way of classification of assets. See also https://github.com/foprs/submodel-template-proposals/issues/2

This repository lists classes for the Asset Administration Shell that can be used. Please open an issue in order to propose further classes.
In your AAS please model the class as specificAssetId with name="assetClass", value=[assetClassName] and externelSubjectId=[assetClassId]

| assetClassName / status | assetClassId / description                                                  | 
| -------------- | --------------------------------------------------------------------------- | 
| workStation    | urn:aas:assetclass:workstation:1:0:bffba008-3087-4eee-881a-d6000031f7be     |
| active         |single work station that is fully automated or where manual work is been done by one or more employees    
| serviceRequest | urn:aas:assetclass:servicerequest:1:0:bffba008-3087-4eee-881a-d6000031f7be  |
| active         |request to perform an service task on an asset    
| material | urn:aas:assetclass:material:1:0:bffba008-3087-4eee-881a-d6000031f7be  |
| active         |material and components that are part of a product that can be sold 
