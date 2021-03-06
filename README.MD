﻿<p align="center">
  <a href="https://www.powershellgallery.com/packages/PSWindocumentation.O365"><img src="https://img.shields.io/powershellgallery/v/PSWindocumentation.O365.svg"></a>
  <a href="https://www.powershellgallery.com/packages/PSWindocumentation.O365"><img src="https://img.shields.io/powershellgallery/vpre/PSWindocumentation.O365.svg?label=powershell%20gallery%20preview&colorB=yellow"></a>
  <a href="https://github.com/EvotecIT/PSWindocumentation.O365"><img src="https://img.shields.io/github/license/EvotecIT/PSWindocumentation.O365.svg"></a>
</p>

<p align="center">
  <a href="https://www.powershellgallery.com/packages/PSWindocumentation.O365"><img src="https://img.shields.io/powershellgallery/p/PSWindocumentation.O365.svg"></a>
  <a href="https://github.com/EvotecIT/PSWindocumentation.O365"><img src="https://img.shields.io/github/languages/top/evotecit/PSWindocumentation.O365.svg"></a>
  <a href="https://github.com/EvotecIT/PSWindocumentation.O365"><img src="https://img.shields.io/github/languages/code-size/evotecit/PSWindocumentation.O365.svg"></a>
  <a href="https://github.com/EvotecIT/PSWindocumentation.O365"><img src="https://img.shields.io/powershellgallery/dt/PSWindocumentation.O365.svg"></a>
</p>

<p align="center">
  <a href="https://twitter.com/PrzemyslawKlys"><img src="https://img.shields.io/twitter/follow/PrzemyslawKlys.svg?label=Twitter%20%40PrzemyslawKlys&style=social"></a>
  <a href="https://evotec.xyz/hub"><img src="https://img.shields.io/badge/Blog-evotec.xyz-2A6496.svg"></a>
  <a href="https://www.linkedin.com/in/pklys"><img src="https://img.shields.io/badge/LinkedIn-pklys-0077B5.svg?logo=LinkedIn"></a>
</p>


# PSWinDocumentation.O365 - PowerShell Module



## Features covered with their usage in Examples

| Category | Dashimo (HTML) | Documentimo (Word) | Excelimo (Excel) | Type                                           |
| -------- | -------------- | ------------------ | ---------------- | ---------------------------------------------- |
| Azure    |                |                    |                  | AzureADGroupMembers                            |
| Azure    | Yes            |                    |                  | AzureADGuests                                  |
| Azure    | Yes            |                    |                  | AzureADUsers                                   |
| Azure    |                |                    |                  | AzureADUsersMFA                                |
| Azure    |                |                    |                  | AzureADUsersStatisticsByCity                   |
| Azure    |                |                    |                  | AzureADUsersStatisticsByCountry                |
| Azure    |                |                    |                  | AzureADUsersStatisticsByCountryCity            |
| Azure    | Yes            | Yes                |                  | AzureLicensing                                 |
| Azure    |                |                    |                  | AzureRoles                                     |
| Azure    | Yes            | Yes                |                  | AzureRolesActiveOnly                           |
| Azure    | Yes            | Yes                |                  | AzureRolesMembers                              |
| Azure    |                |                    |                  | AzureSubscription                              |
| Azure    | Yes            |                    |                  | AzureTenantDomains                             |
|          |                |                    |                  |                                                |
| Exchange | Yes            |                    |                  | ExchangeAcceptedDomains                        |
| Exchange | Yes            | Partially          |                  | ExchangeConnectorsInbound                      |
| Exchange | Yes            | Partially          |                  | ExchangeConnectorsOutbound                     |
| Exchange |                |                    |                  | ExchangeDistributionGroups                     |
| Exchange |                |                    |                  | ExchangeDistributionGroupsMembers              |
| Exchange |                |                    |                  | ExchangeMailboxes                              |
| Exchange |                |                    |                  | ExchangeMailboxesStatistics                    |
| Exchange |                |                    |                  | ExchangeMailboxesStatisticsArchive             |
| Exchange |                |                    |                  | ExchangeMailboxesPermissions                   |
| Exchange |                |                    |                  | ExchangeMailboxesPermissionsIncludingInherited |
| Exchange |                |                    |                  | ExchangeMailboxesInboxRulesForwarding          |
| Exchange |                |                    |                  | ExchangeUnifiedGroups                          |
| Exchange |                |                    |                  | ExchangeUnifiedGroupsMembers                   |
| Exchange | Yes            | Yes                |                  | ExchangeTransportConfig                        |
| Teams    | Yes            | Yes                |                  | TeamsSettings                                  |
| Teams    | Yes            | Yes                |                  | TeamsSettingsBroadcasting                      |
| Teams    | Yes            | Yes                |                  | TeamsSettingsCalling                           |
| Teams    | Yes            | Yes                |                  | TeamsSettingsChannels                          |
| Teams    | Yes            | Yes                |                  | TeamsSettingsEducationAppPolicy                |
| Teams    | Yes            | Yes                |                  | TeamsSettingsFileSharing                       |
| Teams    | Yes            | Yes                |                  | TeamsSettingsGuests                            |
| Teams    | Yes            | Yes                |                  | TeamsSettingsMeetings                          |
| Teams    | Yes            | Yes                |                  | TeamsSettingsMeetingsTechnical                 |
| Teams    | Yes            | Yes                |                  | TeamsSettingsUpgrade                           |
| Teams    | Yes            | Yes                |                  | TeamsSettingsUsers                             |
|          |                |                    |                  |                                                |
| Overall  |                |                    |                  | UAzureADContacts                               |
| Overall  |                |                    |                  | UAzureADGroups                                 |
| Overall  |                |                    |                  | UAzureADUsers                                  |
| Overall  |                |                    |                  | UAzureADUsersDeleted                           |
| Overall  |                |                    |                  | UAzureLicensing                                |
| Overall  |                |                    |                  | UAzureSubscription                             |
| Overall  |                |                    |                  | UAzureTenantDomains                            |
| Overall  |                |                    |                  | UExchangeContacts                              |
| Overall  |                |                    |                  | UExchangeContactsMail                          |
| Overall  |                |                    |                  | UExchangeEquipmentCalendarProcessing           |
| Overall  |                |                    |                  | UExchangeGroupsDistribution                    |
| Overall  |                |                    |                  | UExchangeGroupsDistributionDynamic             |
| Overall  |                |                    |                  | UExchangeGroupsDistributionMembers             |
| Overall  |                |                    |                  | UExchangeMailBoxes                             |
| Overall  |                |                    |                  | UExchangeMailboxesEquipment                    |
| Overall  |                |                    |                  | UExchangeMailboxesInboxRules                   |
| Overall  |                |                    |                  | UExchangeMailboxesJunk                         |
| Overall  |                |                    |                  | UExchangeMailboxesPermissions                  |
| Overall  |                |                    |                  | UExchangeMailboxesRooms                        |
| Overall  |                |                    |                  | UExchangeMailUsers                             |
| Overall  |                |                    |                  | UExchangeRecipients                            |
| Overall  |                |                    |                  | UExchangeRecipientsPermissions                 |
| Overall  |                |                    |                  | UExchangeRoomsCalendarProcessing               |
| Overall  |                |                    |                  | UExchangeUnifiedGroups                         |
| Overall  |                |                    |                  | UExchangeUsers                                 |
| Overall  |                |                    |                  | UTeamsConfiguration                            |
| Overall  |                |                    |                  | UTeamsVideoInteropService                      |