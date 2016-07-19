## Combined Details (CDET)

| Test ID | Test Description  | executed | result |
|:-----   |:---------------   |  :---:   |:----   |
| CDET 110 | manually defined combined details on '%', definition, correct propagation and display as chart | | |
| CDET 150 | manually defined combined details on '%', changed definitions correctly applied | | |
| CDET 170 | manually defined combined details on '%', definitions removed | | |
| CDET 110 | manually defined combined details on 's', definition, correct propagation and display as chart | | |
| CDET 150 | manually defined combined details on 's', changed definitions correctly applied | | |
| CDET 170 | manually defined combined details on 's', definitions removed | | |
| CDET 310 | group based combined details on [E], definition, correct propagation and display as chart | | |
| CDET 320 | group based combined details on [E], calculation and combined graphical representation | | |
| CDET 330 | group based combined details on [E], successfully opened in new window | | |
| CDET 330 | group based combined details on [E], fixed as favorite and displayed correctly | | |
| CDET 350 | group based combined details on [E], successfully changed and applied | | |
| CDET 370 | group based combined details on [E], successfully removed | | |

## Retention Time Settings (RTIM)

| Test ID | Test Description  | executed | result |
|:-----   |:---------------   |  :---:   |:----   |
| RTIM 100 | manually defined retention time, exactly defined, definition | | |
| RTIM 110 | manually defined retention time, exactly defined, effectively working | | |
| RTIM 130 | manually defined retention time, exactly defined, changed and applied successfully | | |
| RTIM 150 | manually defined retention time, exactly defined, removed successful | | |
| RTIM 210 | domain-based auto-retention time, definition | | |
| RTIM 220 | domain-based auto-retention time, effectively working | | |
| RTIM 240 | domain-based auto-retention time, changed definition successfully applied | | |
| RTIM 260 | domain-based auto-retention time, successfully removed | | |
| RTIM 310 | group-based auto-retention time: group privileges and full access to all group auto retention time definitions | | |
| RTIM 320 | group-based auto-retention time: group privileges and group restrictions are working correctly | | |
| RTIM 330 | group-based auto-retention time: group privileges are correctly restricted | | |
| RTIM 340 | group-based auto-retention time: group privileges are applied correctly | | |
| RTIM 340 | group-based auto-retention time: correct operation, "Woodlark" values are kept for the specified non-default time interval | | |
| RTIM 350 | group-based auto-retention time, correct operation, "ULS" values are kept only for the default time interval | | |
| RTIM 360 | group-based auto-retention time, successfully changed and applied | | |
| RTIM 360 | group-based auto-retention time, successfully removed | | |

## Special Values (SVAL)

## Notifications (NTFY)

NTFY 0100: notifications based on group auto limits, the last two values are compared by the function differ, each eligible value combination must fire a notification


| Test ID | Test Description  | executed | result |
|:-----   |:---------------   |  :---:   |:----   |
| NTFY 0100 | group auto limits properly defined | | |
| NTFY 0110 | group-auto-limit, differ, numeric, correct propagation | | |
| NTFY 0120 | group-auto-limit, differ, numeric,  group auto limit notifications fired | | |
| NTFY 0130 | group-auto-limit, differ, numeric, group auto limit changed | | |
| NTFY 0140 | group-auto-limit, differ, numeric, change of group auto limit correctly propagated | | |
| NTFY 0150 | group-auto-limit, differ, numeric, message of changed group auto limit correctly sent | | |
| NTFY 0160 | group-auto-limit, differ, numeric, group auto limits notifications disabled | | |
| NTFY 0170 | group-auto-limit, differ, numeric, group auto limits specifications removed | | |

NTFY 0200: notifications based on domain related auto limits, the average of the last 10 values is calculated, a warn notification is fired, when the calculated average is greater than or equal to 95, the first eligible value combination must fire a notification, no notifications for the following 12 hours.


| Test ID | Test Description  | executed | result |
|:-----   |:---------------   |  :---:   |:----   |
| NTFY 0200 | domain based auto limits, greater equal, 12h, definition and propagation | | |
| NTFY 0210 | domain based auto limits, greater equal, 12h, notifications fired | | |
| NTFY 0220 | domain based auto limits, greater equal, 12h, average calculation for limits approved | | |
| NTFY 0230 | domain based auto limits, greater equal, 12h, correct calculations in notification message | | |
| NTFY 0240 | domain based auto limits, greater equal, 12h, specifications changed and correctly applied | | |
| NTFY 0250 | domain based auto limits, greater equal, 12h, deactivation properly propagated | | |
| NTFY 0260 | domain based auto limits, greater equal, 12h, notifications disabled correctly | | |
| NTFY 0270 | domain based auto limits, greater equal, 12h, notifications removed correctly | | |
| NTFY 0300 | manually defined limits, regexp, collect, defined read-only rights on domain ULS do work | | |
| NTFY 0320 | manually defined limits, regexp, collect, notifications properly fired | | |
| NTFY 0330 | manually defined limits, regexp, collect, specifications changed and applied correctly | | |
| NTFY 0330 | manually defined limits, regexp, collect, specifications correctly deactivated | | |
| NTFY 0340 | manually defined limits, regexp, collect, successful removal of specifications | | |
| NTFY 0420 | manually defined limit, substring, collect, notifications properly fired | | |
| NTFY 0430 | manually defined limit, substring, collect, notifications correctly changed and applied | | |
| NTFY 0440 | manually defined limit, substring, collect, deactivation during defined days of month works | | |
| NTFY 0450 | manually defined limit, substring, collect, active outside defined days of month works | | |
| NTFY 0460 | manually defined limit, substring, collect, active outside defined days of month works | | |
| NTFY 0470 | manually defined limit, substring, collect, removal successful | | |
