This file documents files collected in disk inspection manifests used by Microsoft Azure support.  Any data collected by Microsoft using this tooling is done according to the policy outlined in the [Azure Trust Center](https://azure.microsoft.com/en-us/support/trust-center/).

* [freebsd](#freebsd)
* [linux](#linux)
* [windows](#windows)
## freebsd 
File Path | Manifest 
------------- | ------------- 
/etc/rc.conf | agents, diagnostic, genspec, normal 
/etc/dhclient.conf | agents, diagnostic 
/var/log/dmesg\* | agents, diagnostic, normal 
/var/lib/waagent/GoalState.\*.xml | agents, diagnostic 
/etc/resolv.conf | diagnostic 
/var/lib/waagent/provisioned | genspec 
/var/lib/waagent/ExtensionsConfig.\*.xml | agents, diagnostic 
/etc/ssh/sshd_config | diagnostic, normal 
/var/log/waagent\* | agents, diagnostic, normal 
/etc/fstab | diagnostic, normal 
/var/log/messages\* | diagnostic, normal 
/var/lib/waagent/\*/config/\*.settings | agents, diagnostic 
/var/log/azure/\*/\*/\* | agents, diagnostic 
/etc/networks | diagnostic 
/boot/loader.conf | diagnostic, normal 
/var/log/secure\* | diagnostic 
/var/lib/waagent/\*.xml | agents 
/var/log/auth\* | agents, diagnostic, normal 
/var/log/boot\* | normal 
/etc/nsswitch.conf | diagnostic 
/etc/syslog.conf | diagnostic 
/var/lib/waagent/\*/status/\*.status | agents, diagnostic 
/var/lib/waagent/Microsoft.OSTCExtensions.CustomScriptForLinux.\*.manifest.xml | agents, diagnostic 
/etc/\*-release | agents 
/var/lib/waagent/HostingEnvironmentConfig.xml | agents, diagnostic 
/var/lib/waagent/SharedConfig.xml | agents, diagnostic 
/etc/waagent.conf | agents, diagnostic 
/var/lib/waagent/Prod.\*.manifest.xml | agents, diagnostic 
/etc/ssh/ssh_host\*key\* | genspec 
## linux 
File Path | Manifest 
------------- | ------------- 
/etc/resolv.conf | diagnostic 
/var/lib/waagent/GoalState.\*.xml | agents, diagnostic 
/boot/grub\*/menu.lst | diagnostic 
/var/log/kern\* | diagnostic, normal 
/var/lib/waagent/provisioned | diagnostic, genspec 
/var/lib/waagent/Microsoft.\*LinuxDiagnostic\*/xmlCfg.xml | lad 
/var/log/waagent\* | agents, diagnostic, lad, normal 
/etc/network/interfaces.d/\*.cfg | diagnostic 
/var/lib/waagent/\*.xml | agents 
/var/lib/waagent/Microsoft.\*LinuxDiagnostic\*/status/\*.status | lad 
/var/log/messages\* | diagnostic, normal 
/etc/HOSTNAME | agents, diagnostic, lad 
/var/log/boot\* | diagnostic, normal 
/etc/nsswitch.conf | diagnostic 
/etc/\*-release | agents, diagnostic 
/var/lib/waagent/HostingEnvironmentConfig.xml | agents, diagnostic 
/var/lib/dhcp/dhclient.eth0.leases | diagnostic 
/etc/sysconfig/iptables | diagnostic 
/var/lib/waagent/SharedConfig.xml | agents, diagnostic 
/var/log/azure/\*/\*/\* | agents, diagnostic 
/var/log/dmesg\* | agents, diagnostic, normal 
/etc/hostname | agents, diagnostic, genspec, lad 
/var/log/yum\* | diagnostic, normal 
/etc/sysconfig/network-scripts/ifcfg-eth\* | diagnostic 
/var/log/sa/sar\* | performance 
/etc/sysconfig/SuSEfirewall2 | diagnostic 
/var/lib/waagent/ExtensionsConfig.\*.xml | agents, diagnostic, lad 
/etc/sysconfig/network | diagnostic 
/etc/ssh/sshd_config | diagnostic, normal 
/var/opt/microsoft/omsagent/LAD/log/\* | lad 
/var/log/secure\* | diagnostic, normal 
/etc/fstab | diagnostic, normal 
/var/log/dpkg\* | diagnostic, normal 
/etc/sysconfig/network-scripts/route-eth\* | diagnostic 
/var/lib/waagent/\*/config/\*.settings | agents, diagnostic 
/etc/waagent.conf | agents, diagnostic 
/var/log/syslog\* | diagnostic, lad, normal 
/etc/network/interfaces | diagnostic 
/var/log/azure/Microsoft.\*LinuxDiagnostic/\*/\* | lad 
/etc/sysconfig/network/ifcfg-eth\* | diagnostic 
/var/log/auth\* | agents, diagnostic, normal 
/var/log/rsyslog\* | diagnostic, lad, normal 
/var/lib/waagent/\*/status/\*.status | agents, diagnostic 
/var/lib/waagent/Microsoft.OSTCExtensions.CustomScriptForLinux.\*.manifest.xml | agents, diagnostic 
/var/lib/waagent/Microsoft.\*LinuxDiagnostic\*/config/\*.settings | lad 
/boot/grub\*/grub.c\* | diagnostic 
/etc/sysconfig/network/routes | diagnostic 
/etc/opt/microsoft/omsagent/LAD/conf/omsagent.d/\* | lad 
/var/lib/waagent/Prod.\*.manifest.xml | agents, diagnostic 
/etc/ufw/ufw.conf | diagnostic 
/var/log/cloud-init\* | diagnostic, normal 
## windows 
File Path | Manifest 
------------- | ------------- 
/WindowsAzure/Logs/Plugins/Microsoft.Azure.NetworkWatcher.NetworkWatcherAgentWindows/<br>\*/\*.log | agents, diagnostic, normal 
/Packages/Plugins/\*/\*/PackageInformation.txt | agents, diagnostic, normal 
/WindowsAzure/Logs/Plugins/\*/\*/Install.log | agents, diagnostic, normal 
/Windows/System32/Sysprep/Panther/setupact.log | diagnostic, normal 
/Packages/Plugins/Microsoft.Powershell.DSC/\*/DSCWork/HotfixInstallInProgress.dsc | agents, diagnostic, normal 
/Windows/Panther/unattend.xml | diagnostic, normal 
/Windows/System32/Sysprep/Panther/IE/setuperr.log | diagnostic, normal 
/Packages/Plugins/Microsoft.Azure.Diagnostics.IaaSDiagnostics/\*/StatusMonitor/Applic<br>ationInsightsPackagesVersion.json | agents, diagnostic, normal 
/WindowsAzure/Logs/Plugins/Microsoft.SqlServer.Management.SqlIaaSAgent/\*/CommandExec<br>ution\*.log | sql-iaas 
/Windows/System32/winevt/Logs/Microsoft-Windows-TerminalServices-RDPClient%4Operation<br>al.evtx | diagnostic 
/Windows/System32/winevt/Logs/Microsoft-Windows-Kernel-PnP%4Configuration.evtx | agents, diagnostic 
/Windows/System32/winevt/Logs/Microsoft-Windows-WindowsUpdateClient%4Operational.evtx | diagnostic 
/Packages/Plugins/Microsoft.Azure.Security.Monitoring/\*/Microsoft.WindowsAzure.Stora<br>ge.xml | agents, diagnostic, normal 
/Packages/Plugins/Microsoft.Azure.Security.Monitoring/\*/Monitoring/agent/initconfig/<br>\*/Standard/AntiMalwareEvents.xml | agents, diagnostic, normal 
/Windows/System32/winevt/Logs/Microsoft-Windows-RemoteDesktopServices-RemoteDesktopSe<br>ssionManager%4Admin.evtx | diagnostic 
/Windows/System32/winevt/Logs/Microsoft-WindowsAzure-Diagnostics%4Runtime.evtx | agents, diagnostic 
/Packages/Plugins/\*/\*/HandlerManifest.json | agents, diagnostic, normal 
/Packages/Plugins/Microsoft.Azure.Security.Monitoring/\*/MonitoringAgentCertThumbprin<br>ts.txt | agents, diagnostic, normal 
/WindowsAzure/Logs/Plugins/Microsoft.Compute.VMAccessAgent/\*/JsonVMAccessExtension.l<br>og | agents, diagnostic, normal 
/Windows/System32/config/SOFTWARE | diagnostic 
/WindowsAzure/Logs/Plugins/Microsoft.Azure.NetworkWatcher.NetworkWatcherAgentWindows/<br>\*/\*.txt | agents, diagnostic, normal 
/Packages/Plugins/Microsoft.SqlServer.Management.SqlIaaSAgent/\*/config.txt | sql-iaas 
/Packages/Plugins/Microsoft.SqlServer.Management.SqlIaaSAgent/\*/Status/HeartBeat.Jso<br>n | sql-iaas 
/Windows/System32/winevt/Logs/Microsoft-WindowsAzure-Status%4Plugins.evtx | agents, diagnostic 
/Windows/Panther/WaSetup.log | diagnostic, normal 
/Windows/System32/Sysprep/ActionFiles/Generalize.xml | diagnostic, normal 
/WindowsAzure/Logs/AggregateStatus/aggregatestatus\*.json | agents, diagnostic, normal 
/Packages/Plugins/Microsoft.Azure.Diagnostics.IaaSDiagnostics/\*/Logs/\*DiagnosticsPl<br>ugin\*.log | agents, diagnostic, normal 
/WindowsAzure/Logs/Plugins/Microsoft.Compute.JsonADDomainExtension/\*/ADDomainExtensi<br>on.log | agents, diagnostic, normal 
/Windows/System32/winevt/Logs/Microsoft-Windows-NetworkProvider%4Operational.evtx | agents, diagnostic 
/Windows/System32/winevt/Logs/Microsoft-ServiceFabric-Lease%4Operational.evtx | diagnostic, normal 
/WindowsAzure/Logs/Plugins/Microsoft.Azure.Diagnostics.IaaSDiagnostics/\*/Diagnostics<br>Plugin.log | agents, diagnostic, normal 
/Windows/System32/winevt/Logs/MicrosoftAzureRecoveryServices-Replication.evtx | diagnostic 
/WindowsAzure/Logs/Plugins/Symantec.SymantecEndpointProtection/\*/sepManagedAzure.txt | agents, diagnostic, normal 
/Windows/System32/winevt/Logs/Microsoft-Windows-ServerManager%4Operational.evtx | diagnostic 
/Windows/System32/winevt/Logs/Microsoft-WindowsAzure-Diagnostics%4Heartbeat.evtx | agents, diagnostic 
/Packages/Plugins/Microsoft.Powershell.DSC/\*/DSCWork/PreInstallDone.dsc | agents, diagnostic, normal 
/Windows/System32/winevt/Logs/Microsoft-Windows-CAPI2%4Operational.evtx | agents, diagnostic 
/WindowsAzure/Logs/Plugins/Microsoft.Azure.Diagnostics.IaaSDiagnostics/\*/\*/Configur<br>ation/Checkpoint.txt | agents, diagnostic, normal 
/Windows/debug/PASSWD.LOG | diagnostic, normal 
/Packages/Plugins/Microsoft.Azure.Security.Monitoring/\*/Monitoring/agent/initconfig/<br>\*/Standard/AgentStandardExtensions.xml | agents, diagnostic, normal 
/Packages/Plugins/Microsoft.Azure.Security.Monitoring/\*/Monitoring/agent/Extensions/<br>AzureSecurityPack/AsmScannerConfiguration.xml | agents, diagnostic, normal 
/WindowsAzure/Logs/AppAgentRuntime.log | agents, diagnostic, normal 
/Windows/Inf/setupapi.dev.log | diagnostic, normal 
/Packages/Plugins/Microsoft.Azure.Security.Monitoring/\*/Monitoring/agent/Extensions/<br>AzureSecurityPack/AsmScan.log | agents, diagnostic, normal 
/Packages/Plugins/Microsoft.Compute.BGInfo/\*/PluginManifest.xml | agents, diagnostic, normal 
/Windows/System32/Sysprep/ActionFiles/Specialize.xml | diagnostic, normal 
/Windows/Setup/State/state.ini | agents, normal 
/Windows/Panther/setuperr.log | diagnostic, normal 
/Packages/Plugins/Microsoft.Azure.Security.Monitoring/\*/Monitoring/agent/MonAgent-Pk<br>g-Manifest.xml | agents, diagnostic, normal 
/Windows/System32/winevt/Logs/Microsoft-Windows-TerminalServices-SessionBroker-Client<br>%4Admin.evtx | diagnostic 
/Packages/Plugins/Microsoft.Compute.BGInfo/\*/emptyConfig.bgi | agents, diagnostic, normal 
/Packages/Plugins/Microsoft.Azure.Diagnostics.IaaSDiagnostics/\*/schema/wad\*.json | agents, diagnostic, normal 
/WindowsAzure/Logs/Plugins/Microsoft.EnterpriseCloud.Monitoring.MicrosoftMonitoringAg<br>ent/\*/0.log | agents, diagnostic, normal 
/Windows/System32/Sysprep/Sysprep_succeeded.tag | diagnostic, normal 
/Windows/System32/winevt/Logs/Microsoft-WindowsAzure-Diagnostics%4GuestAgent.evtx | agents, diagnostic 
/Packages/Plugins/Microsoft.SqlServer.Management.SqlIaaSAgent/\*/HandlerManifest.json | sql-iaas 
/Windows/Panther/UnattendGC/setupact.log | diagnostic, normal 
/Packages/Plugins/Microsoft.Azure.ServiceFabric.ServiceFabricNode/\*/Service/current.<br>config | agents, diagnostic, normal 
/WindowsAzure/Logs/Plugins/Microsoft.Azure.Security.Monitoring/\*/AsmExtension.log | agents, diagnostic, normal 
/Windows/System32/winevt/Logs/Microsoft-Windows-TerminalServices-PnPDevices%4Admin.ev<br>tx | diagnostic 
/Windows/System32/winevt/Logs/Microsoft-Windows-TerminalServices-PnPDevices%4Operatio<br>nal.evtx | diagnostic 
/Windows/System32/winevt/Logs/Microsoft-Windows-SMBClient%4Operational.evtx | diagnostic 
/Packages/Plugins/Microsoft.Azure.ServiceFabric.ServiceFabricNode/\*/InstallUtil.Inst<br>allLog | agents, diagnostic, normal 
/Windows/System32/winevt/Logs/Microsoft-Windows-NdisImPlatform%4Operational.evtx | agents, diagnostic 
/Windows/System32/winevt/Logs/Application.evtx | agents, diagnostic, normal, sql-iaas 
/Packages/Plugins/Microsoft.Azure.Diagnostics.IaaSDiagnostics/\*/\*.config | agents, diagnostic, normal 
/Windows/System32/winevt/Logs/Security.evtx | diagnostic 
/Windows/System32/winevt/Logs/Microsoft-Windows-SMBServer%4Operational.evtx | diagnostic 
/Windows/System32/winevt/Logs/Microsoft-Windows-RemoteDesktopServices-RdpCoreTS%4Oper<br>ational.evtx | diagnostic 
/WindowsAzure/Logs/SqlServerLogs/\*.\* | sql-iaas 
/Windows/System32/winevt/Logs/Microsoft-Windows-TerminalServices-SessionBroker-Client<br>%4Operational.evtx | diagnostic 
/Packages/Plugins/\*/\*/Status/HeartBeat.Json | agents, diagnostic, normal 
/Packages/Plugins/Microsoft.Azure.Security.Monitoring/\*/MonitoringAgentScheduledServ<br>ice.txt | agents, diagnostic, normal 
/Packages/Plugins/Microsoft.Azure.Security.Monitoring/\*/Monitoring/agent/initconfig/<br>\*/Standard/SecurityStandardEvents3.xml | agents, diagnostic, normal 
/Packages/Plugins/Microsoft.Azure.ServiceFabric.ServiceFabricNode/\*/Service/Infrastr<br>uctureManifest.template.xml | agents, diagnostic, normal 
/Packages/Plugins/\*/\*/RuntimeSettings/\*.settings | agents, diagnostic, normal 
/Packages/Plugins/Microsoft.Azure.Security.Monitoring/\*/Monitoring/agent/initconfig/<br>\*/Standard/MonitoringStandardEvents.xml | agents, diagnostic, normal 
/Packages/Plugins/ESET.FileSecurity/\*/extension_version.txt | agents, diagnostic, normal 
/Packages/Plugins/Microsoft.Azure.Security.Monitoring/\*/Monitoring/agent/initconfig/<br>\*/Standard/MonitoringEwsRootEvents.xml | agents, diagnostic, normal 
/Windows/System32/winevt/Logs/Microsoft-Windows-RemoteDesktopServices-RdpCoreTS%4Admi<br>n.evtx | diagnostic 
/Windows/Panther/WaSetup.xml | agents, diagnostic, genspec, normal 
/Windows/System32/winevt/Logs/Microsoft-Windows-NetworkLocationWizard%4Operational.ev<br>tx | agents, diagnostic 
/Packages/Plugins/Microsoft.SqlServer.Management.SqlIaaSAgent/\*/Status/\*.status | sql-iaas 
/Packages/Plugins/Microsoft.Powershell.DSC/\*/DSCWork/\*.dsc | agents, diagnostic, normal 
/Windows/System32/winevt/Logs/Microsoft-Windows-RemoteDesktopServices-SessionServices<br>%4Operational.evtx | diagnostic 
/Windows/Inf/netcfg\*.\*etl | diagnostic, normal 
/Windows/System32/Sysprep/Panther/setuperr.log | diagnostic, normal 
/AzureData/CustomData.bin | agents, diagnostic, normal 
/WindowsAzure/Logs/WaAppAgent.log | agents, diagnostic, normal 
/WindowsAzure/Logs/MonitoringAgent.log | agents, diagnostic, normal 
/Windows/System32/config/SYSTEM | diagnostic 
/Packages/Plugins/Microsoft.Azure.Security.Monitoring/\*/Monitoring/agent/initconfig/<br>\*/Standard/MonitoringStandardEvents2.xml | agents, diagnostic, normal 
/Packages/Plugins/Microsoft.Azure.Security.Monitoring/\*/Monitoring/agent/Extensions/<br>AzureSecurityPack/SecurityScanLoggerManifest.man | agents, diagnostic, normal 
/Packages/Plugins/Microsoft.Azure.Security.Monitoring/\*/Monitoring/agent/initconfig/<br>\*/Standard/MonitoringStandardEvents3.xml | agents, diagnostic, normal 
/Windows/System32/winevt/Logs/Microsoft-ServiceFabric%4Operational.evtx | diagnostic, normal 
/Windows/System32/winevt/Logs/Microsoft-Windows-SMBServer%4Connectivity.evtx | diagnostic 
/Packages/Plugins/Microsoft.Powershell.DSC/\*/DSCVersion.xml | agents, diagnostic, normal 
/Windows/System32/winevt/Logs/Microsoft-Windows-TCPIP%4Operational.evtx | agents, diagnostic 
/Packages/Plugins/\*/\*/HandlerEnvironment.json | agents, diagnostic, normal 
/Windows/System32/winevt/Logs/Microsoft-Windows-Resource-Exhaustion-Detector%4Operati<br>onal.evtx | agents, diagnostic 
/Packages/Plugins/Microsoft.SqlServer.Management.SqlIaaSAgent/\*/RuntimeSettings/\*.s<br>ettings | sql-iaas 
/Windows/System32/winevt/Logs/Windows Azure.evtx | agents, diagnostic, normal 
/Windows/Panther/FastCleanup/setupact.log | diagnostic, normal 
/Packages/Plugins/Microsoft.Azure.Security.Monitoring/\*/Monitoring/agent/Extensions/<br>AzureSecurityPack/Azure.Common.scm.xml | agents, diagnostic, normal 
/Packages/Plugins/Microsoft.Azure.ServiceFabric.ServiceFabricNode/\*/Service/ServiceF<br>abricNodeBootstrapAgent.InstallLog | agents, diagnostic, normal 
/Windows/System32/winevt/Logs/Microsoft-Windows-DSC%4Operational.evtx | agents, diagnostic 
/Windows/debug/netlogon.log | diagnostic, normal 
/WindowsAzure/Logs/Plugins/Microsoft.Azure.Diagnostics.IaaSDiagnostics/\*/\*/Configur<br>ation/MonAgentHost.\*.log | agents, diagnostic, normal 
/Windows/debug/dcpromoui.log | diagnostic, normal 
/Packages/Plugins/Microsoft.Azure.Security.Monitoring/\*/Monitoring/agent/initconfig/<br>\*/Standard/MonitoringEwsEvents.xml | agents, diagnostic, normal 
/Packages/Plugins/Microsoft.SqlServer.Management.SqlIaaSAgent/\*/HandlerEnvironment.j<br>son | sql-iaas 
/Windows/debug/NetSetup.LOG | diagnostic, normal 
/Windows/System32/winevt/Logs/Microsoft-Windows-Kernel-PnPConfig%4Configuration.evtx | agents, diagnostic 
/Packages/Plugins/Microsoft.Azure.Security.Monitoring/\*/Monitoring/agent/initconfig/<br>\*/Standard/AgentStandardEvents.xml | agents, diagnostic, normal 
/WindowsAzure/Logs/Plugins/Microsoft.Azure.Diagnostics.IaaSDiagnostics/\*/\*/Configur<br>ation/MaConfig.xml | agents, diagnostic, normal 
/WindowsAzure/Logs/Plugins/Microsoft.Azure.Security.IaaSAntimalware/\*/AntimalwareCon<br>fig.log | agents, diagnostic, normal 
/Windows/System32/winevt/Logs/Microsoft-WindowsAzure-Status%4GuestAgent.evtx | agents, diagnostic 
/Packages/Plugins/Microsoft.Azure.RecoveryServices.VMSnapshot/\*/SeqNumber.txt | agents, diagnostic, normal 
/WindowsAzure/Logs/Plugins/\*/\*/Heartbeat.log | agents, diagnostic, normal 
/Packages/Plugins/Microsoft.Azure.Security.Monitoring/\*/Monitoring/agent/initconfig/<br>\*/Standard/MonitoringEwsEventsCore.xml | agents, diagnostic, normal 
/Windows/Panther/setupact.log | diagnostic, normal 
/Packages/Plugins/Microsoft.SqlServer.Management.SqlIaaSAgent/\*/PackageDefinition.xm<br>l | agents, diagnostic, normal, sql-iaas 
/Windows/Setup/State/State.ini | diagnostic, genspec 
/Packages/Plugins/Microsoft.Powershell.DSC/\*/DSCWork/\*.dpx | agents, diagnostic, normal 
/Windows/System32/winevt/Logs/Microsoft-WindowsAzure-Diagnostics%4Bootstrapper.evtx | agents, diagnostic 
/Packages/Plugins/\*/\*/config.txt | agents, diagnostic, normal 
/WindowsAzure/Logs/Plugins/Microsoft.Azure.NetworkWatcher.Edp.NetworkWatcherAgentWind<br>ows/\*/\*.log | agents, diagnostic, normal 
/Packages/Plugins/Microsoft.Azure.Security.Monitoring/\*/Monitoring/agent/AsmExtensio<br>nMonitoringConfig\*.xml | agents, diagnostic, normal 
/Packages/Plugins/\*/\*/Status/\*.status | agents, diagnostic, normal 
/Program Files/Microsoft SQL Server/\*/MSSQL/Log/\*.\* | sql-iaas 
/WindowsAzure/Logs/Plugins/\*/\*/CommandExecution.log | agents, diagnostic, normal 
/WindowsAzure/Logs/Plugins/Microsoft.Powershell.DSC/\*/DSCLOG\*.json | agents, diagnostic, normal 
/Windows/debug/DCPROMO.LOG | diagnostic, normal 
/unattend.xml | diagnostic, normal 
/Packages/Plugins/Microsoft.Azure.Diagnostics.IaaSDiagnostics/\*/AnalyzerConfigTempla<br>te.xml | agents, diagnostic, normal 
/Windows/System32/winevt/Logs/Microsoft-ServiceFabric-Lease%4Admin.evtx | diagnostic, normal 
/Packages/Plugins/Microsoft.Compute.BGInfo/\*/config.bgi | agents, diagnostic, normal 
/WindowsAzure/Logs/Plugins/Microsoft.Azure.NetworkWatcher.Edp.NetworkWatcherAgentWind<br>ows/\*/\*.txt | agents, diagnostic, normal 
/WindowsAzure/Logs/Plugins/Microsoft.Azure.ServiceFabric.ServiceFabricNode/\*/VCRunti<br>meInstall\*.log | agents, diagnostic, normal 
/Packages/Plugins/Microsoft.Azure.Security.Monitoring/\*/Monitoring/agent/Extensions/<br>AzureSecurityPack/AsmExtensionSecurityPackStartupConfig.xml | agents, diagnostic, normal 
/WindowsAzure/Logs/Plugins/Microsoft.Compute.BGInfo/\*/BGInfo\*.log | agents, diagnostic, normal 
/Windows/System32/winevt/Logs/Microsoft-Windows-SmbClient%4Connectivity.evtx | diagnostic 
/Packages/Plugins/Microsoft.Azure.Security.Monitoring/\*/Monitoring/agent/initconfig/<br>\*/Standard/SecurityStandardEvents2.xml | agents, diagnostic, normal 
/Windows/System32/winevt/Logs/Microsoft-Windows-Windows Firewall With Advanced Securi<br>ty%4ConnectionSecurity.evtx | agents, diagnostic 
/Packages/Plugins/Microsoft.Powershell.DSC/\*/DSCWork/\*.log | agents, diagnostic, normal 
/Windows/System32/Sysprep/ActionFiles/Respecialize.xml | diagnostic, normal 
/WindowsAzure/config/\*.xml | agents, diagnostic, normal 
/Packages/Plugins/Microsoft.Compute.BGInfo/\*/BGInfo.def.xml | agents, diagnostic, normal 
/Packages/Plugins/Microsoft.Azure.ServiceFabric.ServiceFabricNode/\*/Service/ServiceF<br>abricNodeBootstrapAgent.InstallState | agents, diagnostic, normal 
/WindowsAzure/Logs/Plugins/Microsoft.Azure.Diagnostics.IaaSDiagnostics/\*/Diagnostics<br>PluginLauncher.log | agents, diagnostic, normal 
/WindowsAzure/Logs/Plugins/\*/\*/Update.log | agents, diagnostic, normal 
/Packages/Plugins/Microsoft.Azure.Security.Monitoring/\*/Monitoring/agent/initconfig/<br>\*/Standard/SecurityStandardEvents.xml | agents, diagnostic, normal 
/WindowsAzure/Logs/Plugins/Microsoft.Azure.ServiceFabric.ServiceFabricNode/\*/TempClu<br>sterManifest.xml | agents, diagnostic, normal 
/WindowsAzure/Logs/Plugins/Microsoft.Powershell.DSC/\*/DscExtensionHandler\*.log | agents, diagnostic, normal 
/WindowsAzure/Logs/Plugins/TrendMicro.DeepSecurity.TrendMicroDSA/\*/\*.log | agents, diagnostic, normal 
/Windows/System32/Sysprep/Panther/IE/setupact.log | diagnostic, normal 
/WindowsAzure/Logs/Plugins/Microsoft.Azure.ServiceFabric.ServiceFabricNode/\*/Infrast<br>ructureManifest.xml | agents, diagnostic, normal 
/WindowsAzure/Logs/Plugins/Microsoft.Azure.ServiceFabric.ServiceFabricNode/\*/FabricM<br>SIInstall\*.log | agents, diagnostic, normal 
/Windows/System32/winevt/Logs/Microsoft-Windows-NetworkProfile%4Operational.evtx | agents, diagnostic 
/Windows/System32/winevt/Logs/Microsoft-Windows-TerminalServices-LocalSessionManager%<br>4Operational.evtx | diagnostic 
/WindowsAzure/Logs/Telemetry.log | agents, diagnostic, normal 
/Packages/Plugins/Microsoft.Azure.Security.Monitoring/\*/Monitoring/agent/initconfig/<br>\*/Standard/AgentStandardEventsMin.xml | agents, diagnostic, normal 
/Windows/System32/winevt/Logs/Microsoft-Windows-Windows Firewall With Advanced Securi<br>ty%4Firewall.evtx | agents, diagnostic 
/Windows/System32/winevt/Logs/Microsoft-ServiceFabric%4Admin.evtx | diagnostic, normal 
/Windows/System32/winevt/Logs/Microsoft-Windows-TerminalServices-RemoteConnectionMana<br>ger%4Admin.evtx | diagnostic 
/Windows/System32/winevt/Logs/Setup.evtx | diagnostic 
/WindowsAzure/Logs/TransparentInstaller.log | agents, diagnostic, normal 
/Windows/System32/winevt/Logs/Microsoft-Windows-UserPnp%4DeviceInstall.evtx | agents, diagnostic 
/Windows/System32/winevt/Logs/Microsoft-Windows-NlaSvc%4Operational.evtx | agents, diagnostic 
/Windows/System32/winevt/Logs/Microsoft-Windows-TerminalServices-RemoteConnectionMana<br>ger%4Operational.evtx | diagnostic 
/Windows/debug/mrt.log | diagnostic, normal 
/Windows/System32/winevt/Logs/System.evtx | agents, diagnostic, normal, sql-iaas 
/Packages/Plugins/Microsoft.Azure.Security.Monitoring/\*/Monitoring/agent/Extensions/<br>AzureSecurityPack/ASM.Azure.OSBaseline.xml | agents, diagnostic, normal 
/Windows/System32/winevt/Logs/Microsoft-Windows-TerminalServices-LocalSessionManager%<br>4Admin.evtx | diagnostic 
/Packages/Plugins/Microsoft.Azure.Security.Monitoring/\*/Monitoring/agent/Extensions/<br>AzureSecurityPack/SecurityPackStartup.log | agents, diagnostic, normal 
/Packages/Plugins/ESET.FileSecurity/\*/agent_version.txt | agents, diagnostic, normal 
/WindowsAzure/Logs/Plugins/Microsoft.Azure.RecoveryServices.VMSnapshot/\*/IaaSBcdrExt<br>ension\*.log | agents, diagnostic, normal 

*File was created by running [parse_manifest.py](../tools/parse_manifest.py) on `2017-06-22 14:24:02.183309`*