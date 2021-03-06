---
external help file: PSProcessa-help.xml
online version: 
schema: 2.0.0
---

# Get-CheckedSecret

## SYNOPSIS
Obtiene un objeto de tipo SecureString a partir de un texto ingresado por el usuario.

## SYNTAX

```
Get-CheckedSecret [[-Prompt] <String>] [[-ConfirmationPrompt] <String>]
```

## DESCRIPTION
Solicita dos veces al usuario el ingreso de un texto.

## EXAMPLES

### -------------------------- EXAMPLE 1 --------------------------
```
Get-CheckedSecret
```

### -------------------------- EXAMPLE 2 --------------------------
```
Get-CheckedSecret -Prompt 'Ingrese una clave' -ConfirmationPrompt 'Confirme la clave'
```

## PARAMETERS

### -Prompt
{{Fill Prompt Description}}

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: 1
Default value: $Script:Resx.GetCheckedSecretDefaultPromptText
Accept pipeline input: False
Accept wildcard characters: False
```

### -ConfirmationPrompt
{{Fill ConfirmationPrompt Description}}

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: 2
Default value: $Script:Resx.GetCheckedSecretDefaultConfirmationPromptText
Accept pipeline input: False
Accept wildcard characters: False
```

## INPUTS

### None.

## OUTPUTS

### System.Security.SecureString

## NOTES
Autor: Atorres

## RELATED LINKS

[[Get-CheckedCredential](Get-CheckedCredential.md)]()

