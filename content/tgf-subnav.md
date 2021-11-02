# Tanzu GemFire Documentation

*   [About Tanzu GemFire for VMs](./index.html)
    *   [Product Snapshot and Version Compatibility](./product-snapshot.html)
    *   [Tanzu GemFire for VMs and Other Services](./on-demand-services.html)
    *   [Tanzu GemFire for VMs Architecture](./architecture.html)
    *   [Recommended Usage and Limitations](./usage.html)
    *   [Security](./security.html)
*   [Operator Guide](./operator.html)
    *   [Preparing for Installation](./prepare-for-installation.html)
        *   [Networking for On-Demand Services](./on-demand-networking.html)
        *   [Preparing for Transport Layer Security (TLS)](./prepare-TLS.html)
        *   [Create a User Account and Authentication (UAA) Client](./create-UAA-client.html)
    *   [Installing and Configuring Tanzu GemFire for VMs](./install-configure.html)
    *   [VM Memory Allocation](./memory-allocation.html)
    *   [Configuring User Account and Authentication (UAA) Roles](./UAA-config.html)
    *   [Setting Service Instance Quotas](./set-quotas.html)
    *   [Upgrading Tanzu GemFire for VMs](./upgrade.html)
    *   [Updating Tanzu GemFire for VMs Plans](./update-plan.html)
    *   [Uninstalling Tanzu GemFire for VMs](./uninstall.html)
    *   [Backing Up and Restoring Service Instances](./backupandrestore.html)
    *   [Configuring a Service Gateway](./configure-service-gateway.html)
    *   [Enabling Service-Instance Sharing](./op-instance-sharing.html)
    *   [Rotating Certificates](./rotating-ca.html)
    *   [Restoring a WAN Connection](./WAN-bi-reconnect.html)
*   [Working with Service Instances](./working-with-SI.html)
    *   [View Available Plans](./view-plans.html)
    *   [Create or Delete a Service Instance](./create-instance.html)
    *   [Upgrade a Single Service Instance](./dev-upgrade.html)
    *   [Updating a Tanzu GemFire for VMs Service Instance](./update-instance.html)
    *   [Monitoring Tanzu GemFire for VMs Service Instances](./monitoring.html)
    *   [Using a Service Gateway](./service-gateway.html)
    *   [Service-Instance Sharing](./dev-instance-sharing.html)
    *   [Set Up Service Instances Across a Wide Area Network (WAN)](./WAN-setup.html)
        *   [Establishing Mutually Trusted TLS Credentials](./WAN-mutual-credentials.html)
        *   [Set Up a Bidirectional System](./WAN-bi-TLS-setup.html)
        *   [Set Up a Unidirectional System](./WAN-uni-TLS-setup.html)
        *   [Set Up an Additional Bidirectional Interaction](./WAN-addl-bi-TLS-setup.html)
        *   [Set Up an Additional Unidirectional Interaction](./WAN-addl-uni-TLS-setup.html)
    *   [Accessing a Service Instance](./accessing-instance.html)
    *   [Using gfsh](./using-pcc.html)
    *   [Setting Up Servers for an Inline Cache](./inline-setup.html)
    *   [Connecting a Spring Boot App to Tanzu GemFire for VMs with Session State Caching](./Spring-SessionState.html)
    *   [Creating Continuous Queries Using Spring Data GemFire](./Spring-CQs.html)
    *   [Visual Statistics Display (VSD)](./vsd/overview.html)
        *   [VSD System Requirements](./vsd/vsd_system_requirements.html)
        *   [Installing and Running VSD](./vsd/running_vsd.html)
        *   [Viewing Statistics in VSD](./vsd/viewing_stats_in_vsd.html)
        *   [Quick Guide to Useful Statistics](./vsd/vsd_useful_statistics.html)
*   [Application Development](./app-development.html)
    *   [Design Patterns](./design-patterns.html)
    *   [Region Design](./region-design.html)
    *   [Handling Events](./events.html)
    *   [Example Applications](./example-applications.html)
        *   [An Example Java App](./use-sample-app.html)
        *   [An Example Spring Boot App](./SBapp1.html)
    *   [Running an App](./running-app.html)
    *   [Developing an App Under Transport Layer Security (TLS)](./tls-enabled-app.html)
    *   [Tomcat Session State Caching](./session-caching.html)
    *   [Spring Session Caching](./spring-session.html)
*   [Troubleshooting](./troubleshooting.html)
*   [Release Notes](./release-notes.html)

12:docs-book-cloud-cache$ clear 13:docs-book-cloud-cache$ cat master\_middleman/source/subnavs/cloudcache\_subnav.erb

Doc Index

*   [About Tanzu GemFire for VMs](./index.html)
    *   [Product Snapshot and Version Compatibility](./product-snapshot.html)
    *   [Tanzu GemFire for VMs and Other Services](./on-demand-services.html)
    *   [Tanzu GemFire for VMs Architecture](./architecture.html)
    *   [Recommended Usage and Limitations](./usage.html)
    *   [Security](./security.html)
*   [Operator Guide](./operator.html)
    *   [Preparing for Installation](./prepare-for-installation.html)
        *   [Networking for On-Demand Services](./on-demand-networking.html)
        *   [Preparing for Transport Layer Security (TLS)](./prepare-TLS.html)
        *   [Create a User Account and Authentication (UAA) Client](./create-UAA-client.html)
    *   [Installing and Configuring Tanzu GemFire for VMs](./install-configure.html)
    *   [VM Memory Allocation](./memory-allocation.html)
    *   [Configuring User Account and Authentication (UAA) Roles](./UAA-config.html)
    *   [Setting Service Instance Quotas](./set-quotas.html)
    *   [Upgrading Tanzu GemFire for VMs](./upgrade.html)
    *   [Updating Tanzu GemFire for VMs Plans](./update-plan.html)
    *   [Uninstalling Tanzu GemFire for VMs](./uninstall.html)
    *   [Backing Up and Restoring Service Instances](./backupandrestore.html)
    *   [Configuring a Service Gateway](./configure-service-gateway.html)
    *   [Enabling Service-Instance Sharing](./op-instance-sharing.html)
    *   [Rotating Certificates](./rotating-ca.html)
    *   [Restoring a WAN Connection](./WAN-bi-reconnect.html)
*   [Working with Service Instances](./working-with-SI.html)
    *   [View Available Plans](./view-plans.html)
    *   [Create or Delete a Service Instance](./create-instance.html)
    *   [Upgrade a Single Service Instance](./dev-upgrade.html)
    *   [Updating a Tanzu GemFire for VMs Service Instance](./update-instance.html)
    *   [Monitoring Tanzu GemFire for VMs Service Instances](./monitoring.html)
    *   [Using a Service Gateway](./service-gateway.html)
    *   [Service-Instance Sharing](./dev-instance-sharing.html)
    *   [Set Up Service Instances Across a Wide Area Network (WAN)](./WAN-setup.html)
        *   [Establishing Mutually Trusted TLS Credentials](./WAN-mutual-credentials.html)
        *   [Set Up a Bidirectional System](./WAN-bi-TLS-setup.html)
        *   [Set Up a Unidirectional System](./WAN-uni-TLS-setup.html)
        *   [Set Up an Additional Bidirectional Interaction](./WAN-addl-bi-TLS-setup.html)
        *   [Set Up an Additional Unidirectional Interaction](./WAN-addl-uni-TLS-setup.html)
    *   [Accessing a Service Instance](./accessing-instance.html)
    *   [Using gfsh](./using-pcc.html)
    *   [Setting Up Servers for an Inline Cache](./inline-setup.html)
    *   [Connecting a Spring Boot App to Tanzu GemFire for VMs with Session State Caching](./Spring-SessionState.html)
    *   [Creating Continuous Queries Using Spring Data GemFire](./Spring-CQs.html)
    *   [Visual Statistics Display (VSD)](./vsd/overview.html)
        *   [VSD System Requirements](./vsd/vsd_system_requirements.html)
        *   [Installing and Running VSD](./vsd/running_vsd.html)
        *   [Viewing Statistics in VSD](./vsd/viewing_stats_in_vsd.html)
        *   [Quick Guide to Useful Statistics](./vsd/vsd_useful_statistics.html)
*   [Application Development](./app-development.html)
    *   [Design Patterns](./design-patterns.html)
    *   [Region Design](./region-design.html)
    *   [Handling Events](./events.html)
    *   [Example Applications](./example-applications.html)
        *   [An Example Java App](./use-sample-app.html)
        *   [An Example Spring Boot App](./SBapp1.html)
    *   [Running an App](./running-app.html)
    *   [Developing an App Under Transport Layer Security (TLS)](./tls-enabled-app.html)
    *   [Tomcat Session State Caching](./session-caching.html)
    *   [Spring Session Caching](./spring-session.html)
*   [Troubleshooting](./troubleshooting.html)
*   [Release Notes](./release-notes.html)