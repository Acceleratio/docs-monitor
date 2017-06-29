---
Title: Monitor Citrix Published Applications
Author: Andrea Budisa
Description:This article explains how to adjust SysKit Monitor for the Citrix Published Applications monitoring.
Date: 29/06/17
---
This feature provides __Citrix XenApp 5__, __XenApp 6__, __XenApp 6.5__, __XenApp 7__ and __XenApp 7.5__ Published Applications monitoring. In order for the Published Applications to appear in the SysKit Monitor reports, it is necessary to enable this feature.

1. Navigate to the __File__, select __Configuration__ from the left navigation bar and click on the __Options__ button.
1. Select the [General](#internal/how-to/citrix-xenapp/monitor-citrix-published-applications/options) tab, navigate to __Citrix Options__ and the following options will be available:
  * __Resolve Published Applications Name__ – enable this option to use Published Application display name instead of a FullName.
  * __Reset Gather Mode__ – re-detect Published Application data gathering mode.
1. Check in the __Gather Published Applications__ option. Click __Save__ to finish.

### Published Applications gathering limitations

1. If you decide to gather Published Applications and configured SysKit Monitor to do so, you won’t be able to view Application Performance reports.
1. It is not possible to detect different instances of the same Published Application for one specific user on the specific computer.

See [Configure SysKit for Citrix XenApp 5 Published Application monitoring](#internal/how-to/citrix-xenapp/monitor-citrix-published-applications/configure-syskit-for-citrix-xenapp-5-published-application-monitoring) article to learn more.

See [Configure SysKit for Citrix XenApp 6.0/6.5 Published Application monitoring](#internal/how-to/citrix-xenapp/monitor-citrix-published-applications/configure-syskit-for-citrix-xenapp-6.0-6.5-published-application-monitoring) article to learn more.