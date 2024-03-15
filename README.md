# asset-classification

Id of the classification = urn:aas:assetclassification:aas-connect:1:0:bffba008-3087-4eee-881a-d6000031f7be

A repo with a classification for Asset Administration Shells

There is currently no standardized (from IDTA specified) way of classification of assets. See also https://youtu.be/30zYmezDNcE. 

This repository lists classes for the Asset Administration Shell that can be used. Please open an issue in order to propose further classes.

In your AAS please model the class as specificAssetId with: 
semanticId=urn:aas:assetclass:<assetClassName>:<version>:<revision>:<uuidId>  
name="assetClass"  
value=[assetClassName]  
externalSubjectId="urn:aas:assetclassification:aas-connect:1:0:bffba008-3087-4eee-881a-d6000031f7be"



| assetClassName (status)     | assetClassId / description                                                  | 
| --------------------------- | --------------------------------------------------------------------------- | 
| workStation *active*        | urn:aas:assetclass:workstation:1:0:bffba008-3087-4eee-881a-d6000031f7be     |
|                             |single work station that is fully automated or where manual work is been done by one or more employees    
| serviceRequest *active*     | urn:aas:assetclass:servicerequest:1:0:bffba008-3087-4eee-881a-d6000031f7be  |
|                             |request to perform a service task on an asset    
| material *active*           | urn:aas:assetclass:material:1:0:bffba008-3087-4eee-881a-d6000031f7be  |
|                             |material, component or part that is part of a physical product that can be sold 
