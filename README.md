# asset-classification

Id of the classification = urn:aas-connect:assetclassification:1:0

A repo with a classification for Asset Administration Shells

There is currently no standardized (from IDTA specified) way of classification of assets. See also https://youtu.be/30zYmezDNcE. 

This repository lists classes for the Asset Administration Shell that can be used.  

<b>Please open an issue in order to propose further classes.</b>

In your AAS please model the class as specificAssetId with: 
  
semanticId=urn:aas-connect:assetclass:\<assetClassName\>:\<version\>:\<revision\>[:\<uuid\>]  
name="assetClass"  
value=\<assetClassName\>  
externalSubjectId="urn:aas-connect:assetclassification:1:0"



| assetClassName (status)     | assetClassId / description                                                  | 
| --------------------------- | --------------------------------------------------------------------------- | 
| workStation *active*        | single work station that is fully automated or where manual work is been done by one or more employees |
|                             | urn:aas-connect:assetclass:workstation:1:0    
| serviceRequest *active*     | request to perform a service task on an asset |
|                             | urn:aas-connect:assetclass:servicerequest:1:0   
| material *active*           | material, component or part that is part of a physical product that can be sold |
|                             | urn:aas-connect:assetclass:material:1:0
