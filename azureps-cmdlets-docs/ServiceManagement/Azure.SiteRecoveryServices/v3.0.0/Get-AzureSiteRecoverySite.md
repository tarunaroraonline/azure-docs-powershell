---
external help file: Microsoft.Azure.Commands.RecoveryServicesRdfe.dll-Help.xml
online version: 
schema: 2.0.0
ms.assetid: 1135F4D4-C7A4-4ECB-BF4D-EECC8C32EDE4
---

# Get-AzureSiteRecoverySite

## SYNOPSIS
Gets the Hyper-V sites from a Site Recovery vault.

## SYNTAX

```
Get-AzureSiteRecoverySite [-Vault <ASRVault>] [-Profile <AzureSMProfile>] [<CommonParameters>]
```

## DESCRIPTION
The **Get-AzureSiteRecoverySite** cmdlet gets the Hyper-V sites in an Azure Site Recovery vault.

## EXAMPLES

### Example 1: Get recovery sites
```
PS C:\>Get-AzureSiteRecoverySite
Type                                    Name                                    ID
----                                    ----                                    --
HyperVSite                              RecoverySite07                          f16829b4-5b01-4209-a6cf-8e0aff1fe328
```

This command gets the recovery sites for the current vault.

## PARAMETERS

### -Vault
Specifies a vault for which to get sites.
To obtain an **ASRVault** object, use the Get-AzureSiteRecoveryVault cmdlet.

```yaml
Type: ASRVault
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Profile
Specifies the Azure profile from which this cmdlet reads.
If you do not specify a profile, this cmdlet reads from the local default profile.

```yaml
Type: AzureSMProfile
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

[Get-AzureSiteRecoveryVault](./Get-AzureSiteRecoveryVault.md)

[New-AzureSiteRecoverySite](./New-AzureSiteRecoverySite.md)

