---
external help file: Microsoft.TeamsCmdlets.PowerShell.Custom.dll-Help.xml
Module Name: MicrosoftTeams
applicable: Microsoft Teams
title: Add-TeamUser
online version: 
schema: 2.0.0
author: kenwith
ms.author: kenwith
ms.reviewer:
---

# Add-TeamUser

## SYNOPSIS
Note: This cmdlet is currently in Beta.

Adds an owner or member to the team, and to the unified group which backs the team. 

Note: the command will return immediately, but the Teams application will not reflect the update immediately. 
The Teams application may need to be open for up to an hour before changes are reflected.

By default, when you run this cmdlet to add an owner, you will not add it as a member. You must run this cmdlet again to add the owner as a member as well.

## SYNTAX

```
Add-TeamUser -GroupId <String> -User <String> [-Role <String>]
```

## DESCRIPTION

## EXAMPLES

### --------------------------  Example 1  --------------------------
```
Add-TeamUser -GroupId 31f1ff6c-d48c-4f8a-b2e1-abca7fd399df -User dmx@example.com
```

Add user dmx@example.com to group.

## PARAMETERS

### -GroupId
GroupId of the team.

```yaml
Type: String
Parameter Sets: (All)
Aliases:
Applicable: Microsoft Teams

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -User
User's UPN (user principal name - e.g. johndoe@example.com).

```yaml
Type: String
Parameter Sets: (All)
Aliases:
Applicable: Microsoft Teams

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -Role
Member or Owner.

```yaml
Type: String
Parameter Sets: (All)
Aliases:
Applicable: Microsoft Teams

Required: False
Position: Named
Default value: Member
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

## INPUTS

### GroupId, User, Role

## OUTPUTS

## NOTES

## RELATED LINKS

