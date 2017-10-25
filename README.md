# Informaiton about compliance templates and examples

### On chain information
```
    "jurisdictions": ["US", "CA"], // Array of location where this template works
    "fixedFee": 100 POLY, // Fixed cost to use the template >= 0, can be edited by template creator 
    "royalties": 100POLY/1ETH, // Royalties ratio during ISO, can be changed by template creator
    "investorRestrictions": ["NK": true, "RU": true], // Jurisdictions excluded when using this template
    "investorAccreditationRequired": false, // Does this template require that investors be accredited 
    "title": "Reg D complaint security", // Descriptive title for template
    "hash": "A0FC", // Hash of the off-chain template document
    "creatorAddress": "F03AC.." // Ethereum address (multisig) of template creator
    "steps": 6 // The number of steps to complete
    "completed": [ // Array of information about completion process
        {
            docHash: "AEF42", // Hash of doc related to completed step
            completed: 1244555 // When was the step completed? Only the Compliance Officer can update this field  
        },
        {
            ....
        }
    ]
```