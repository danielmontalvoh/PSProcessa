---
external help file: PSProcessa-help.xml
online version: 
schema: 2.0.0
---

# Get-PGPKeyStore

## SYNOPSIS
Obtiene la configuración de llaves de cifrado PGP.

## SYNTAX

```powershell
Get-PGPKeyStore [[-Name] <String>]
```

## DESCRIPTION
Obtiene la configuración de llaves de cifrado PGP.

## EXAMPLES

### -------------------------- EXAMPLE 1 --------------------------
```powershell
Get-PGPKeyStore
```

Obtiene la configuración de todas las llaves de cifrado registradas.

### -------------------------- EXAMPLE 2 --------------------------
```powershell
Get-PGPKeyStore -Name MyName'
```

Obtiene la configuración de la llave de cifrado almacenada con el nombre MyName.

## PARAMETERS

### -Name
Nombre que se indicó al registrar la configuración. Para obtener todas las configuraciones disponibles, omita el valor de este parámetro.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: 1
Default value: *
Accept pipeline input: False
Accept wildcard characters: True
```

## INPUTS

None.

## OUTPUTS

Processa.Management.Automation.PSProcessa.PGPKeyStoreInfo

## NOTES
Autor: Atorres

## RELATED LINKS
[Set-PGPKeyStore](Set-PGPKeyStore.md)

[Remove-PGPKeyStore](Remove-PGPKeyStore.md)

[Test-PGPKeyStore](Test-PGPKeyStore.md)
