---
title: Module compute
---

<a href="../index.html">@pulumi/gcp</a> &gt; compute

<h2 class="pdoc-module-header">Index</h2>

* <a href="#Address">class Address</a>
* <a href="#Autoscalar">class Autoscalar</a>
* <a href="#BackendBucket">class BackendBucket</a>
* <a href="#BackendService">class BackendService</a>
* <a href="#Disk">class Disk</a>
* <a href="#Firewall">class Firewall</a>
* <a href="#ForwardingRule">class ForwardingRule</a>
* <a href="#GlobalAddress">class GlobalAddress</a>
* <a href="#GlobalForwardingRule">class GlobalForwardingRule</a>
* <a href="#HealthCheck">class HealthCheck</a>
* <a href="#HttpHealthCheck">class HttpHealthCheck</a>
* <a href="#HttpsHealthCheck">class HttpsHealthCheck</a>
* <a href="#Image">class Image</a>
* <a href="#Instance">class Instance</a>
* <a href="#InstanceFromTemplate">class InstanceFromTemplate</a>
* <a href="#InstanceGroup">class InstanceGroup</a>
* <a href="#InstanceGroupManager">class InstanceGroupManager</a>
* <a href="#InstanceTemplate">class InstanceTemplate</a>
* <a href="#Network">class Network</a>
* <a href="#NetworkPeering">class NetworkPeering</a>
* <a href="#ProjectMetadata">class ProjectMetadata</a>
* <a href="#ProjectMetadataItem">class ProjectMetadataItem</a>
* <a href="#RegionAutoscaler">class RegionAutoscaler</a>
* <a href="#RegionBackendService">class RegionBackendService</a>
* <a href="#RegionInstanceGroupManager">class RegionInstanceGroupManager</a>
* <a href="#Route">class Route</a>
* <a href="#Router">class Router</a>
* <a href="#RouterInterface">class RouterInterface</a>
* <a href="#RouterPeer">class RouterPeer</a>
* <a href="#SSLCertificate">class SSLCertificate</a>
* <a href="#SSLPolicy">class SSLPolicy</a>
* <a href="#SecurityPolicy">class SecurityPolicy</a>
* <a href="#SharedVPCHostProject">class SharedVPCHostProject</a>
* <a href="#SharedVPCServiceProject">class SharedVPCServiceProject</a>
* <a href="#Snapshot">class Snapshot</a>
* <a href="#Subnetwork">class Subnetwork</a>
* <a href="#SubnetworkIAMBinding">class SubnetworkIAMBinding</a>
* <a href="#SubnetworkIAMMember">class SubnetworkIAMMember</a>
* <a href="#SubnetworkIAMPolicy">class SubnetworkIAMPolicy</a>
* <a href="#TargetHttpProxy">class TargetHttpProxy</a>
* <a href="#TargetHttpsProxy">class TargetHttpsProxy</a>
* <a href="#TargetPool">class TargetPool</a>
* <a href="#TargetSSLProxy">class TargetSSLProxy</a>
* <a href="#TargetTCPProxy">class TargetTCPProxy</a>
* <a href="#URLMap">class URLMap</a>
* <a href="#VPNGateway">class VPNGateway</a>
* <a href="#VPNTunnel">class VPNTunnel</a>
* <a href="#getAddress">function getAddress</a>
* <a href="#getBackendService">function getBackendService</a>
* <a href="#getDefaultServiceAccount">function getDefaultServiceAccount</a>
* <a href="#getForwardingRule">function getForwardingRule</a>
* <a href="#getGlobalAddress">function getGlobalAddress</a>
* <a href="#getImage">function getImage</a>
* <a href="#getInstanceGroup">function getInstanceGroup</a>
* <a href="#getLBIPRanges">function getLBIPRanges</a>
* <a href="#getNetblockIPRanges">function getNetblockIPRanges</a>
* <a href="#getNetwork">function getNetwork</a>
* <a href="#getRegionInstanceGroup">function getRegionInstanceGroup</a>
* <a href="#getRegions">function getRegions</a>
* <a href="#getSSLPolicy">function getSSLPolicy</a>
* <a href="#getSubnetwork">function getSubnetwork</a>
* <a href="#getVPNGateway">function getVPNGateway</a>
* <a href="#getZones">function getZones</a>
* <a href="#AddressArgs">interface AddressArgs</a>
* <a href="#AddressState">interface AddressState</a>
* <a href="#AutoscalarArgs">interface AutoscalarArgs</a>
* <a href="#AutoscalarState">interface AutoscalarState</a>
* <a href="#BackendBucketArgs">interface BackendBucketArgs</a>
* <a href="#BackendBucketState">interface BackendBucketState</a>
* <a href="#BackendServiceArgs">interface BackendServiceArgs</a>
* <a href="#BackendServiceState">interface BackendServiceState</a>
* <a href="#DiskArgs">interface DiskArgs</a>
* <a href="#DiskState">interface DiskState</a>
* <a href="#FirewallArgs">interface FirewallArgs</a>
* <a href="#FirewallState">interface FirewallState</a>
* <a href="#ForwardingRuleArgs">interface ForwardingRuleArgs</a>
* <a href="#ForwardingRuleState">interface ForwardingRuleState</a>
* <a href="#GetAddressArgs">interface GetAddressArgs</a>
* <a href="#GetAddressResult">interface GetAddressResult</a>
* <a href="#GetBackendServiceArgs">interface GetBackendServiceArgs</a>
* <a href="#GetBackendServiceResult">interface GetBackendServiceResult</a>
* <a href="#GetDefaultServiceAccountArgs">interface GetDefaultServiceAccountArgs</a>
* <a href="#GetDefaultServiceAccountResult">interface GetDefaultServiceAccountResult</a>
* <a href="#GetForwardingRuleArgs">interface GetForwardingRuleArgs</a>
* <a href="#GetForwardingRuleResult">interface GetForwardingRuleResult</a>
* <a href="#GetGlobalAddressArgs">interface GetGlobalAddressArgs</a>
* <a href="#GetGlobalAddressResult">interface GetGlobalAddressResult</a>
* <a href="#GetImageArgs">interface GetImageArgs</a>
* <a href="#GetImageResult">interface GetImageResult</a>
* <a href="#GetInstanceGroupArgs">interface GetInstanceGroupArgs</a>
* <a href="#GetInstanceGroupResult">interface GetInstanceGroupResult</a>
* <a href="#GetLBIPRangesResult">interface GetLBIPRangesResult</a>
* <a href="#GetNetblockIPRangesResult">interface GetNetblockIPRangesResult</a>
* <a href="#GetNetworkArgs">interface GetNetworkArgs</a>
* <a href="#GetNetworkResult">interface GetNetworkResult</a>
* <a href="#GetRegionInstanceGroupArgs">interface GetRegionInstanceGroupArgs</a>
* <a href="#GetRegionInstanceGroupResult">interface GetRegionInstanceGroupResult</a>
* <a href="#GetRegionsArgs">interface GetRegionsArgs</a>
* <a href="#GetRegionsResult">interface GetRegionsResult</a>
* <a href="#GetSSLPolicyArgs">interface GetSSLPolicyArgs</a>
* <a href="#GetSSLPolicyResult">interface GetSSLPolicyResult</a>
* <a href="#GetSubnetworkArgs">interface GetSubnetworkArgs</a>
* <a href="#GetSubnetworkResult">interface GetSubnetworkResult</a>
* <a href="#GetVPNGatewayArgs">interface GetVPNGatewayArgs</a>
* <a href="#GetVPNGatewayResult">interface GetVPNGatewayResult</a>
* <a href="#GetZonesArgs">interface GetZonesArgs</a>
* <a href="#GetZonesResult">interface GetZonesResult</a>
* <a href="#GlobalAddressArgs">interface GlobalAddressArgs</a>
* <a href="#GlobalAddressState">interface GlobalAddressState</a>
* <a href="#GlobalForwardingRuleArgs">interface GlobalForwardingRuleArgs</a>
* <a href="#GlobalForwardingRuleState">interface GlobalForwardingRuleState</a>
* <a href="#HealthCheckArgs">interface HealthCheckArgs</a>
* <a href="#HealthCheckState">interface HealthCheckState</a>
* <a href="#HttpHealthCheckArgs">interface HttpHealthCheckArgs</a>
* <a href="#HttpHealthCheckState">interface HttpHealthCheckState</a>
* <a href="#HttpsHealthCheckArgs">interface HttpsHealthCheckArgs</a>
* <a href="#HttpsHealthCheckState">interface HttpsHealthCheckState</a>
* <a href="#ImageArgs">interface ImageArgs</a>
* <a href="#ImageState">interface ImageState</a>
* <a href="#InstanceArgs">interface InstanceArgs</a>
* <a href="#InstanceFromTemplateArgs">interface InstanceFromTemplateArgs</a>
* <a href="#InstanceFromTemplateState">interface InstanceFromTemplateState</a>
* <a href="#InstanceGroupArgs">interface InstanceGroupArgs</a>
* <a href="#InstanceGroupManagerArgs">interface InstanceGroupManagerArgs</a>
* <a href="#InstanceGroupManagerState">interface InstanceGroupManagerState</a>
* <a href="#InstanceGroupState">interface InstanceGroupState</a>
* <a href="#InstanceState">interface InstanceState</a>
* <a href="#InstanceTemplateArgs">interface InstanceTemplateArgs</a>
* <a href="#InstanceTemplateState">interface InstanceTemplateState</a>
* <a href="#NetworkArgs">interface NetworkArgs</a>
* <a href="#NetworkPeeringArgs">interface NetworkPeeringArgs</a>
* <a href="#NetworkPeeringState">interface NetworkPeeringState</a>
* <a href="#NetworkState">interface NetworkState</a>
* <a href="#ProjectMetadataArgs">interface ProjectMetadataArgs</a>
* <a href="#ProjectMetadataItemArgs">interface ProjectMetadataItemArgs</a>
* <a href="#ProjectMetadataItemState">interface ProjectMetadataItemState</a>
* <a href="#ProjectMetadataState">interface ProjectMetadataState</a>
* <a href="#RegionAutoscalerArgs">interface RegionAutoscalerArgs</a>
* <a href="#RegionAutoscalerState">interface RegionAutoscalerState</a>
* <a href="#RegionBackendServiceArgs">interface RegionBackendServiceArgs</a>
* <a href="#RegionBackendServiceState">interface RegionBackendServiceState</a>
* <a href="#RegionInstanceGroupManagerArgs">interface RegionInstanceGroupManagerArgs</a>
* <a href="#RegionInstanceGroupManagerState">interface RegionInstanceGroupManagerState</a>
* <a href="#RouteArgs">interface RouteArgs</a>
* <a href="#RouteState">interface RouteState</a>
* <a href="#RouterArgs">interface RouterArgs</a>
* <a href="#RouterInterfaceArgs">interface RouterInterfaceArgs</a>
* <a href="#RouterInterfaceState">interface RouterInterfaceState</a>
* <a href="#RouterPeerArgs">interface RouterPeerArgs</a>
* <a href="#RouterPeerState">interface RouterPeerState</a>
* <a href="#RouterState">interface RouterState</a>
* <a href="#SSLCertificateArgs">interface SSLCertificateArgs</a>
* <a href="#SSLCertificateState">interface SSLCertificateState</a>
* <a href="#SSLPolicyArgs">interface SSLPolicyArgs</a>
* <a href="#SSLPolicyState">interface SSLPolicyState</a>
* <a href="#SecurityPolicyArgs">interface SecurityPolicyArgs</a>
* <a href="#SecurityPolicyState">interface SecurityPolicyState</a>
* <a href="#SharedVPCHostProjectArgs">interface SharedVPCHostProjectArgs</a>
* <a href="#SharedVPCHostProjectState">interface SharedVPCHostProjectState</a>
* <a href="#SharedVPCServiceProjectArgs">interface SharedVPCServiceProjectArgs</a>
* <a href="#SharedVPCServiceProjectState">interface SharedVPCServiceProjectState</a>
* <a href="#SnapshotArgs">interface SnapshotArgs</a>
* <a href="#SnapshotState">interface SnapshotState</a>
* <a href="#SubnetworkArgs">interface SubnetworkArgs</a>
* <a href="#SubnetworkIAMBindingArgs">interface SubnetworkIAMBindingArgs</a>
* <a href="#SubnetworkIAMBindingState">interface SubnetworkIAMBindingState</a>
* <a href="#SubnetworkIAMMemberArgs">interface SubnetworkIAMMemberArgs</a>
* <a href="#SubnetworkIAMMemberState">interface SubnetworkIAMMemberState</a>
* <a href="#SubnetworkIAMPolicyArgs">interface SubnetworkIAMPolicyArgs</a>
* <a href="#SubnetworkIAMPolicyState">interface SubnetworkIAMPolicyState</a>
* <a href="#SubnetworkState">interface SubnetworkState</a>
* <a href="#TargetHttpProxyArgs">interface TargetHttpProxyArgs</a>
* <a href="#TargetHttpProxyState">interface TargetHttpProxyState</a>
* <a href="#TargetHttpsProxyArgs">interface TargetHttpsProxyArgs</a>
* <a href="#TargetHttpsProxyState">interface TargetHttpsProxyState</a>
* <a href="#TargetPoolArgs">interface TargetPoolArgs</a>
* <a href="#TargetPoolState">interface TargetPoolState</a>
* <a href="#TargetSSLProxyArgs">interface TargetSSLProxyArgs</a>
* <a href="#TargetSSLProxyState">interface TargetSSLProxyState</a>
* <a href="#TargetTCPProxyArgs">interface TargetTCPProxyArgs</a>
* <a href="#TargetTCPProxyState">interface TargetTCPProxyState</a>
* <a href="#URLMapArgs">interface URLMapArgs</a>
* <a href="#URLMapState">interface URLMapState</a>
* <a href="#VPNGatewayArgs">interface VPNGatewayArgs</a>
* <a href="#VPNGatewayState">interface VPNGatewayState</a>
* <a href="#VPNTunnelArgs">interface VPNTunnelArgs</a>
* <a href="#VPNTunnelState">interface VPNTunnelState</a>

<a href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/address.ts">compute/address.ts</a> <a href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/autoscalar.ts">compute/autoscalar.ts</a> <a href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendBucket.ts">compute/backendBucket.ts</a> <a href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendService.ts">compute/backendService.ts</a> <a href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/disk.ts">compute/disk.ts</a> <a href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/firewall.ts">compute/firewall.ts</a> <a href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/forwardingRule.ts">compute/forwardingRule.ts</a> <a href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getAddress.ts">compute/getAddress.ts</a> <a href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getBackendService.ts">compute/getBackendService.ts</a> <a href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getDefaultServiceAccount.ts">compute/getDefaultServiceAccount.ts</a> <a href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getForwardingRule.ts">compute/getForwardingRule.ts</a> <a href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getGlobalAddress.ts">compute/getGlobalAddress.ts</a> <a href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getImage.ts">compute/getImage.ts</a> <a href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getInstanceGroup.ts">compute/getInstanceGroup.ts</a> <a href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getLBIPRanges.ts">compute/getLBIPRanges.ts</a> <a href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getNetblockIPRanges.ts">compute/getNetblockIPRanges.ts</a> <a href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getNetwork.ts">compute/getNetwork.ts</a> <a href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getRegionInstanceGroup.ts">compute/getRegionInstanceGroup.ts</a> <a href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getRegions.ts">compute/getRegions.ts</a> <a href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getSSLPolicy.ts">compute/getSSLPolicy.ts</a> <a href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getSubnetwork.ts">compute/getSubnetwork.ts</a> <a href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getVPNGateway.ts">compute/getVPNGateway.ts</a> <a href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getZones.ts">compute/getZones.ts</a> <a href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/globalAddress.ts">compute/globalAddress.ts</a> <a href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/globalForwardingRule.ts">compute/globalForwardingRule.ts</a> <a href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/healthCheck.ts">compute/healthCheck.ts</a> <a href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpHealthCheck.ts">compute/httpHealthCheck.ts</a> <a href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpsHealthCheck.ts">compute/httpsHealthCheck.ts</a> <a href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/image.ts">compute/image.ts</a> <a href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts">compute/instance.ts</a> <a href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts">compute/instanceFromTemplate.ts</a> <a href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroup.ts">compute/instanceGroup.ts</a> <a href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroupManager.ts">compute/instanceGroupManager.ts</a> <a href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceTemplate.ts">compute/instanceTemplate.ts</a> <a href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/network.ts">compute/network.ts</a> <a href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/networkPeering.ts">compute/networkPeering.ts</a> <a href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/projectMetadata.ts">compute/projectMetadata.ts</a> <a href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/projectMetadataItem.ts">compute/projectMetadataItem.ts</a> <a href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionAutoscaler.ts">compute/regionAutoscaler.ts</a> <a href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionBackendService.ts">compute/regionBackendService.ts</a> <a href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionInstanceGroupManager.ts">compute/regionInstanceGroupManager.ts</a> <a href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/route.ts">compute/route.ts</a> <a href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/router.ts">compute/router.ts</a> <a href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/routerInterface.ts">compute/routerInterface.ts</a> <a href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/routerPeer.ts">compute/routerPeer.ts</a> <a href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sSLCertificate.ts">compute/sSLCertificate.ts</a> <a href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sSLPolicy.ts">compute/sSLPolicy.ts</a> <a href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/securityPolicy.ts">compute/securityPolicy.ts</a> <a href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sharedVPCHostProject.ts">compute/sharedVPCHostProject.ts</a> <a href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sharedVPCServiceProject.ts">compute/sharedVPCServiceProject.ts</a> <a href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/snapshot.ts">compute/snapshot.ts</a> <a href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetwork.ts">compute/subnetwork.ts</a> <a href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetworkIAMBinding.ts">compute/subnetworkIAMBinding.ts</a> <a href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetworkIAMMember.ts">compute/subnetworkIAMMember.ts</a> <a href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetworkIAMPolicy.ts">compute/subnetworkIAMPolicy.ts</a> <a href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetHttpProxy.ts">compute/targetHttpProxy.ts</a> <a href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetHttpsProxy.ts">compute/targetHttpsProxy.ts</a> <a href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetPool.ts">compute/targetPool.ts</a> <a href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetSSLProxy.ts">compute/targetSSLProxy.ts</a> <a href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetTCPProxy.ts">compute/targetTCPProxy.ts</a> <a href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/uRLMap.ts">compute/uRLMap.ts</a> <a href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNGateway.ts">compute/vPNGateway.ts</a> <a href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNTunnel.ts">compute/vPNTunnel.ts</a> 


<h2 class="pdoc-module-header" id="Address">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/address.ts#L6">class Address</a>
</h2>
<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/address.ts#L36">constructor</a>
</h3>

```typescript
new Address(name: string, args?: AddressArgs, opts?: pulumi.CustomResourceOptions)
```


Create a Address resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/address.ts#L15">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: AddressState): Address
```


Get an existing Address resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method getProvider</a>
</h3>

```typescript
getProvider(moduleMember: string): ProviderResource | undefined
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/address.ts#L19">property address</a>
</h3>

```typescript
public address: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/address.ts#L20">property addressType</a>
</h3>

```typescript
public addressType: pulumi.Output<string | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/address.ts#L21">property creationTimestamp</a>
</h3>

```typescript
public creationTimestamp: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/address.ts#L22">property description</a>
</h3>

```typescript
public description: pulumi.Output<string | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/address.ts#L23">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/address.ts#L24">property networkTier</a>
</h3>

```typescript
public networkTier: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/address.ts#L29">property project</a>
</h3>

```typescript
public project: pulumi.Output<string>;
```


The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/address.ts#L30">property region</a>
</h3>

```typescript
public region: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/address.ts#L34">property selfLink</a>
</h3>

```typescript
public selfLink: pulumi.Output<string>;
```


The URI of the created resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/address.ts#L35">property subnetwork</a>
</h3>

```typescript
public subnetwork: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/address.ts#L36">property users</a>
</h3>

```typescript
public users: pulumi.Output<string[]>;
```

<h2 class="pdoc-module-header" id="Autoscalar">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/autoscalar.ts#L6">class Autoscalar</a>
</h2>
<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/autoscalar.ts#L33">constructor</a>
</h3>

```typescript
new Autoscalar(name: string, args: AutoscalarArgs, opts?: pulumi.CustomResourceOptions)
```


Create a Autoscalar resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/autoscalar.ts#L15">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: AutoscalarState): Autoscalar
```


Get an existing Autoscalar resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method getProvider</a>
</h3>

```typescript
getProvider(moduleMember: string): ProviderResource | undefined
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/autoscalar.ts#L19">property autoscalingPolicy</a>
</h3>

```typescript
public autoscalingPolicy: pulumi.Output<{ ... }>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/autoscalar.ts#L20">property creationTimestamp</a>
</h3>

```typescript
public creationTimestamp: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/autoscalar.ts#L21">property description</a>
</h3>

```typescript
public description: pulumi.Output<string | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/autoscalar.ts#L22">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/autoscalar.ts#L27">property project</a>
</h3>

```typescript
public project: pulumi.Output<string>;
```


The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/autoscalar.ts#L31">property selfLink</a>
</h3>

```typescript
public selfLink: pulumi.Output<string>;
```


The URI of the created resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/autoscalar.ts#L32">property target</a>
</h3>

```typescript
public target: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/autoscalar.ts#L33">property zone</a>
</h3>

```typescript
public zone: pulumi.Output<string>;
```

<h2 class="pdoc-module-header" id="BackendBucket">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendBucket.ts#L6">class BackendBucket</a>
</h2>
<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendBucket.ts#L32">constructor</a>
</h3>

```typescript
new BackendBucket(name: string, args: BackendBucketArgs, opts?: pulumi.CustomResourceOptions)
```


Create a BackendBucket resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendBucket.ts#L15">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: BackendBucketState): BackendBucket
```


Get an existing BackendBucket resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method getProvider</a>
</h3>

```typescript
getProvider(moduleMember: string): ProviderResource | undefined
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendBucket.ts#L19">property bucketName</a>
</h3>

```typescript
public bucketName: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendBucket.ts#L20">property creationTimestamp</a>
</h3>

```typescript
public creationTimestamp: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendBucket.ts#L21">property description</a>
</h3>

```typescript
public description: pulumi.Output<string | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendBucket.ts#L22">property enableCdn</a>
</h3>

```typescript
public enableCdn: pulumi.Output<boolean | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendBucket.ts#L23">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendBucket.ts#L28">property project</a>
</h3>

```typescript
public project: pulumi.Output<string>;
```


The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendBucket.ts#L32">property selfLink</a>
</h3>

```typescript
public selfLink: pulumi.Output<string>;
```


The URI of the created resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h2 class="pdoc-module-header" id="BackendService">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendService.ts#L13">class BackendService</a>
</h2>

A Backend Service defines a group of virtual machines that will serve traffic for load balancing. For more information
see [the official documentation](https://cloud.google.com/compute/docs/load-balancing/http/backend-service)
and the [API](https://cloud.google.com/compute/docs/reference/latest/backendServices).

For internal load balancing, use a [google_compute_region_backend_service](/docs/providers/google/r/compute_region_backend_service.html).

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendService.ts#L104">constructor</a>
</h3>

```typescript
new BackendService(name: string, args: BackendServiceArgs, opts?: pulumi.CustomResourceOptions)
```


Create a BackendService resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendService.ts#L22">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: BackendServiceState): BackendService
```


Get an existing BackendService resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method getProvider</a>
</h3>

```typescript
getProvider(moduleMember: string): ProviderResource | undefined
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendService.ts#L29">property backends</a>
</h3>

```typescript
public backends: pulumi.Output<{ ... }[] | undefined>;
```


The list of backends that serve this BackendService. Structure is documented below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendService.ts#L33">property cdnPolicy</a>
</h3>

```typescript
public cdnPolicy: pulumi.Output<{ ... }>;
```


Cloud CDN configuration for this BackendService. Structure is documented below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendService.ts#L38">property connectionDrainingTimeoutSec</a>
</h3>

```typescript
public connectionDrainingTimeoutSec: pulumi.Output<number | undefined>;
```


Time for which instance will be drained (not accept new connections,
but still work to finish started ones). Defaults to `300`.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendService.ts#L43">property customRequestHeaders</a>
</h3>

```typescript
public customRequestHeaders: pulumi.Output<string[] | undefined>;
```


) Headers that the
HTTP/S load balancer should add to proxied requests. See [guide](https://cloud.google.com/compute/docs/load-balancing/http/backend-service#user-defined-request-headers) for details.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendService.ts#L47">property description</a>
</h3>

```typescript
public description: pulumi.Output<string | undefined>;
```


Textual description for the backend.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendService.ts#L51">property enableCdn</a>
</h3>

```typescript
public enableCdn: pulumi.Output<boolean | undefined>;
```


Whether or not to enable the Cloud CDN on the backend service.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendService.ts#L55">property fingerprint</a>
</h3>

```typescript
public fingerprint: pulumi.Output<string>;
```


The fingerprint of the backend service.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendService.ts#L61">property healthChecks</a>
</h3>

```typescript
public healthChecks: pulumi.Output<string>;
```


Specifies a list of HTTP/HTTPS health checks
for checking the health of the backend service. Currently at most one health
check can be specified, and a health check is required.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendService.ts#L65">property iap</a>
</h3>

```typescript
public iap: pulumi.Output<{ ... } | undefined>;
```


Specification for the Identity-Aware proxy. Disabled if not specified. Structure is documented below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendService.ts#L69">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```


The name of the backend service.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendService.ts#L74">property portName</a>
</h3>

```typescript
public portName: pulumi.Output<string>;
```


The name of a service that has been added to an
instance group in this backend. See [related docs](https://cloud.google.com/compute/docs/instance-groups/#specifying_service_endpoints) for details. Defaults to http.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendService.ts#L79">property project</a>
</h3>

```typescript
public project: pulumi.Output<string>;
```


The ID of the project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendService.ts#L84">property protocol</a>
</h3>

```typescript
public protocol: pulumi.Output<string>;
```


The protocol for incoming requests. Defaults to
`HTTP`.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendService.ts#L89">property securityPolicy</a>
</h3>

```typescript
public securityPolicy: pulumi.Output<string | undefined>;
```


) Name or URI of a
[security policy](https://cloud.google.com/armor/docs/security-policy-concepts) to add to the backend service.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendService.ts#L93">property selfLink</a>
</h3>

```typescript
public selfLink: pulumi.Output<string>;
```


The URI of the created resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendService.ts#L99">property sessionAffinity</a>
</h3>

```typescript
public sessionAffinity: pulumi.Output<string>;
```


How to distribute load. Options are `NONE` (no
affinity), `CLIENT_IP` (hash of the source/dest addresses / ports), and
`GENERATED_COOKIE` (distribute load using a generated session cookie).

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendService.ts#L104">property timeoutSec</a>
</h3>

```typescript
public timeoutSec: pulumi.Output<number>;
```


The number of secs to wait for a backend to respond
to a request before considering the request failed. Defaults to `30`.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h2 class="pdoc-module-header" id="Disk">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/disk.ts#L6">class Disk</a>
</h2>
<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/disk.ts#L47">constructor</a>
</h3>

```typescript
new Disk(name: string, args?: DiskArgs, opts?: pulumi.CustomResourceOptions)
```


Create a Disk resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/disk.ts#L15">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: DiskState): Disk
```


Get an existing Disk resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method getProvider</a>
</h3>

```typescript
getProvider(moduleMember: string): ProviderResource | undefined
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/disk.ts#L19">property creationTimestamp</a>
</h3>

```typescript
public creationTimestamp: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/disk.ts#L20">property description</a>
</h3>

```typescript
public description: pulumi.Output<string | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/disk.ts#L21">property diskEncryptionKey</a>
</h3>

```typescript
public diskEncryptionKey: pulumi.Output<{ ... } | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/disk.ts#L22">property diskEncryptionKeyRaw</a>
</h3>

```typescript
public diskEncryptionKeyRaw: pulumi.Output<string | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/disk.ts#L23">property diskEncryptionKeySha256</a>
</h3>

```typescript
public diskEncryptionKeySha256: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/disk.ts#L24">property image</a>
</h3>

```typescript
public image: pulumi.Output<string | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/disk.ts#L25">property labelFingerprint</a>
</h3>

```typescript
public labelFingerprint: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/disk.ts#L26">property labels</a>
</h3>

```typescript
public labels: pulumi.Output<{ ... } | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/disk.ts#L27">property lastAttachTimestamp</a>
</h3>

```typescript
public lastAttachTimestamp: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/disk.ts#L28">property lastDetachTimestamp</a>
</h3>

```typescript
public lastDetachTimestamp: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/disk.ts#L29">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/disk.ts#L34">property project</a>
</h3>

```typescript
public project: pulumi.Output<string>;
```


The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/disk.ts#L38">property selfLink</a>
</h3>

```typescript
public selfLink: pulumi.Output<string>;
```


The URI of the created resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/disk.ts#L39">property size</a>
</h3>

```typescript
public size: pulumi.Output<number>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/disk.ts#L40">property snapshot</a>
</h3>

```typescript
public snapshot: pulumi.Output<string | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/disk.ts#L41">property sourceImageEncryptionKey</a>
</h3>

```typescript
public sourceImageEncryptionKey: pulumi.Output<{ ... } | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/disk.ts#L42">property sourceImageId</a>
</h3>

```typescript
public sourceImageId: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/disk.ts#L43">property sourceSnapshotEncryptionKey</a>
</h3>

```typescript
public sourceSnapshotEncryptionKey: pulumi.Output<{ ... } | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/disk.ts#L44">property sourceSnapshotId</a>
</h3>

```typescript
public sourceSnapshotId: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/disk.ts#L45">property type</a>
</h3>

```typescript
public type: pulumi.Output<string | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/disk.ts#L46">property users</a>
</h3>

```typescript
public users: pulumi.Output<string[]>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/disk.ts#L47">property zone</a>
</h3>

```typescript
public zone: pulumi.Output<string>;
```

<h2 class="pdoc-module-header" id="Firewall">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/firewall.ts#L12">class Firewall</a>
</h2>

Manages a firewall resource within GCE. For more information see
[the official documentation](https://cloud.google.com/compute/docs/vpc/firewalls)
and
[API](https://cloud.google.com/compute/docs/reference/latest/firewalls).

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/firewall.ts#L110">constructor</a>
</h3>

```typescript
new Firewall(name: string, args: FirewallArgs, opts?: pulumi.CustomResourceOptions)
```


Create a Firewall resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/firewall.ts#L21">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: FirewallState): Firewall
```


Get an existing Firewall resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method getProvider</a>
</h3>

```typescript
getProvider(moduleMember: string): ProviderResource | undefined
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/firewall.ts#L29">property allows</a>
</h3>

```typescript
public allows: pulumi.Output<{ ... }[] | undefined>;
```


Can be specified multiple times for each allow
rule. Each allow block supports fields documented below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/firewall.ts#L35">property denies</a>
</h3>

```typescript
public denies: pulumi.Output<{ ... }[] | undefined>;
```


Can be specified multiple times for each deny
rule. Each deny block supports fields documented below. Can be specified
instead of allow.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/firewall.ts#L39">property description</a>
</h3>

```typescript
public description: pulumi.Output<string | undefined>;
```


Textual description field.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/firewall.ts#L44">property destinationRanges</a>
</h3>

```typescript
public destinationRanges: pulumi.Output<string[]>;
```


A list of destination CIDR ranges that this
firewall applies to. Can't be used for `INGRESS`.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/firewall.ts#L49">property direction</a>
</h3>

```typescript
public direction: pulumi.Output<string>;
```


Direction of traffic to which this firewall applies;
One of `INGRESS` or `EGRESS`. Defaults to `INGRESS`.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/firewall.ts#L54">property disabled</a>
</h3>

```typescript
public disabled: pulumi.Output<boolean | undefined>;
```


Denotes whether the firewall rule is disabled, i.e not applied to the network it is associated with.
When set to true, the firewall rule is not enforced and the network behaves as if it did not exist.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/firewall.ts#L59">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```


A unique name for the resource, required by GCE.
Changing this forces a new resource to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/firewall.ts#L63">property network</a>
</h3>

```typescript
public network: pulumi.Output<string>;
```


The name or self_link of the network to attach this firewall to.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/firewall.ts#L69">property priority</a>
</h3>

```typescript
public priority: pulumi.Output<number | undefined>;
```


The priority for this firewall. Ranges from 0-65535, inclusive. Defaults to 1000. Firewall
resources with lower priority values have higher precedence (e.g. a firewall resource with a priority value of 0
takes effect over all other firewall rules with a non-zero priority).

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/firewall.ts#L74">property project</a>
</h3>

```typescript
public project: pulumi.Output<string>;
```


The ID of the project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/firewall.ts#L78">property selfLink</a>
</h3>

```typescript
public selfLink: pulumi.Output<string>;
```


The URI of the created resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/firewall.ts#L83">property sourceRanges</a>
</h3>

```typescript
public sourceRanges: pulumi.Output<string[]>;
```


A list of source CIDR ranges that this
firewall applies to. Can't be used for `EGRESS`.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/firewall.ts#L94">property sourceServiceAccounts</a>
</h3>

```typescript
public sourceServiceAccounts: pulumi.Output<string | undefined>;
```


A list of service accounts such that
the firewall will apply only to traffic originating from an instance with a service account in this list.  Note that as of May 2018,
this list can contain only one item, due to a change in the way that these firewall rules are handled.  Source service accounts
cannot be used to control traffic to an instance's external IP address because service accounts are associated with an instance, not
an IP address. `source_ranges` can be set at the same time as `source_service_accounts`. If both are set, the firewall will apply to
traffic that has source IP address within `source_ranges` OR the source IP belongs to an instance with service account listed in
`source_service_accounts`. The connection does not need to match both properties for the firewall to apply. `source_service_accounts`
cannot be used at the same time as `source_tags` or `target_tags`.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/firewall.ts#L98">property sourceTags</a>
</h3>

```typescript
public sourceTags: pulumi.Output<string[] | undefined>;
```


A list of source tags for this firewall. Can't be used for `EGRESS`.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/firewall.ts#L106">property targetServiceAccounts</a>
</h3>

```typescript
public targetServiceAccounts: pulumi.Output<string | undefined>;
```


A list of service accounts indicating
sets of instances located in the network that may make network connections as specified in `allow`. `target_service_accounts` cannot
be used at the same time as `source_tags` or `target_tags`. If neither `target_service_accounts` nor `target_tags` are specified, the
firewall rule applies to all instances on the specified network.  Note that as of May 2018, this list can contain only one item, due
to a change in the way that these firewall rules are handled.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/firewall.ts#L110">property targetTags</a>
</h3>

```typescript
public targetTags: pulumi.Output<string[] | undefined>;
```


A list of target tags for this firewall.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h2 class="pdoc-module-header" id="ForwardingRule">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/forwardingRule.ts#L6">class ForwardingRule</a>
</h2>
<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/forwardingRule.ts#L46">constructor</a>
</h3>

```typescript
new ForwardingRule(name: string, args?: ForwardingRuleArgs, opts?: pulumi.CustomResourceOptions)
```


Create a ForwardingRule resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/forwardingRule.ts#L15">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: ForwardingRuleState): ForwardingRule
```


Get an existing ForwardingRule resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method getProvider</a>
</h3>

```typescript
getProvider(moduleMember: string): ProviderResource | undefined
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/forwardingRule.ts#L19">property backendService</a>
</h3>

```typescript
public backendService: pulumi.Output<string | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/forwardingRule.ts#L20">property creationTimestamp</a>
</h3>

```typescript
public creationTimestamp: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/forwardingRule.ts#L21">property description</a>
</h3>

```typescript
public description: pulumi.Output<string | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/forwardingRule.ts#L22">property ipAddress</a>
</h3>

```typescript
public ipAddress: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/forwardingRule.ts#L23">property ipProtocol</a>
</h3>

```typescript
public ipProtocol: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/forwardingRule.ts#L24">property ipVersion</a>
</h3>

```typescript
public ipVersion: pulumi.Output<string | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/forwardingRule.ts#L25">property labelFingerprint</a>
</h3>

```typescript
public labelFingerprint: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/forwardingRule.ts#L26">property labels</a>
</h3>

```typescript
public labels: pulumi.Output<{ ... } | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/forwardingRule.ts#L27">property loadBalancingScheme</a>
</h3>

```typescript
public loadBalancingScheme: pulumi.Output<string | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/forwardingRule.ts#L28">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/forwardingRule.ts#L29">property network</a>
</h3>

```typescript
public network: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/forwardingRule.ts#L30">property networkTier</a>
</h3>

```typescript
public networkTier: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/forwardingRule.ts#L31">property portRange</a>
</h3>

```typescript
public portRange: pulumi.Output<string | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/forwardingRule.ts#L32">property ports</a>
</h3>

```typescript
public ports: pulumi.Output<string[] | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/forwardingRule.ts#L37">property project</a>
</h3>

```typescript
public project: pulumi.Output<string>;
```


The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/forwardingRule.ts#L38">property region</a>
</h3>

```typescript
public region: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/forwardingRule.ts#L42">property selfLink</a>
</h3>

```typescript
public selfLink: pulumi.Output<string>;
```


The URI of the created resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/forwardingRule.ts#L43">property serviceLabel</a>
</h3>

```typescript
public serviceLabel: pulumi.Output<string | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/forwardingRule.ts#L44">property serviceName</a>
</h3>

```typescript
public serviceName: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/forwardingRule.ts#L45">property subnetwork</a>
</h3>

```typescript
public subnetwork: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/forwardingRule.ts#L46">property target</a>
</h3>

```typescript
public target: pulumi.Output<string | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h2 class="pdoc-module-header" id="GlobalAddress">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/globalAddress.ts#L6">class GlobalAddress</a>
</h2>
<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/globalAddress.ts#L32">constructor</a>
</h3>

```typescript
new GlobalAddress(name: string, args?: GlobalAddressArgs, opts?: pulumi.CustomResourceOptions)
```


Create a GlobalAddress resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/globalAddress.ts#L15">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: GlobalAddressState): GlobalAddress
```


Get an existing GlobalAddress resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method getProvider</a>
</h3>

```typescript
getProvider(moduleMember: string): ProviderResource | undefined
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/globalAddress.ts#L19">property address</a>
</h3>

```typescript
public address: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/globalAddress.ts#L20">property creationTimestamp</a>
</h3>

```typescript
public creationTimestamp: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/globalAddress.ts#L21">property description</a>
</h3>

```typescript
public description: pulumi.Output<string | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/globalAddress.ts#L22">property ipVersion</a>
</h3>

```typescript
public ipVersion: pulumi.Output<string | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/globalAddress.ts#L23">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/globalAddress.ts#L28">property project</a>
</h3>

```typescript
public project: pulumi.Output<string>;
```


The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/globalAddress.ts#L32">property selfLink</a>
</h3>

```typescript
public selfLink: pulumi.Output<string>;
```


The URI of the created resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h2 class="pdoc-module-header" id="GlobalForwardingRule">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/globalForwardingRule.ts#L12">class GlobalForwardingRule</a>
</h2>

Manages a Global Forwarding Rule within GCE. This binds an ip and port to a target HTTP(s) proxy. For more
information see [the official
documentation](https://cloud.google.com/compute/docs/load-balancing/http/global-forwarding-rules) and
[API](https://cloud.google.com/compute/docs/reference/latest/globalForwardingRules).

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/globalForwardingRule.ts#L84">constructor</a>
</h3>

```typescript
new GlobalForwardingRule(name: string, args: GlobalForwardingRuleArgs, opts?: pulumi.CustomResourceOptions)
```


Create a GlobalForwardingRule resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/globalForwardingRule.ts#L21">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: GlobalForwardingRuleState): GlobalForwardingRule
```


Get an existing GlobalForwardingRule resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method getProvider</a>
</h3>

```typescript
getProvider(moduleMember: string): ProviderResource | undefined
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/globalForwardingRule.ts#L28">property description</a>
</h3>

```typescript
public description: pulumi.Output<string | undefined>;
```


Textual description field.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/globalForwardingRule.ts#L35">property ipAddress</a>
</h3>

```typescript
public ipAddress: pulumi.Output<string>;
```


The static IP. (if not set, an ephemeral IP is
used). This should be the literal IP address to be used, not the `self_link`
to a `google_compute_global_address` resource. (If using a `google_compute_global_address`
resource, use the `address` property instead of the `self_link` property.)

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/globalForwardingRule.ts#L40">property ipProtocol</a>
</h3>

```typescript
public ipProtocol: pulumi.Output<string>;
```


The IP protocol to route, one of "TCP" "UDP" "AH"
"ESP" or "SCTP". (default "TCP").

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/globalForwardingRule.ts#L46">property ipVersion</a>
</h3>

```typescript
public ipVersion: pulumi.Output<string | undefined>;
```


The IP Version that will be used by this resource's address. One of `"IPV4"` or `"IPV6"`.
You cannot provide this and `ip_address`.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/globalForwardingRule.ts#L50">property labelFingerprint</a>
</h3>

```typescript
public labelFingerprint: pulumi.Output<string>;
```


([Beta](/docs/providers/google/index.html#beta-features)) The current label fingerprint.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/globalForwardingRule.ts#L55">property labels</a>
</h3>

```typescript
public labels: pulumi.Output<{ ... } | undefined>;
```


)
A set of key/value label pairs to assign to the resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/globalForwardingRule.ts#L60">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```


A unique name for the resource, required by GCE. Changing
this forces a new resource to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/globalForwardingRule.ts#L71">property portRange</a>
</h3>

```typescript
public portRange: pulumi.Output<string | undefined>;
```


A range e.g. "1024-2048" or a single port "1024"
(defaults to all ports!).
Some types of forwarding targets have constraints on the acceptable ports:
* Target HTTP proxy: 80, 8080
* Target HTTPS proxy: 443
* Target TCP proxy: 25, 43, 110, 143, 195, 443, 465, 587, 700, 993, 995, 1883, 5222
* Target SSL proxy: 25, 43, 110, 143, 195, 443, 465, 587, 700, 993, 995, 1883, 5222
* Target VPN gateway: 500, 4500

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/globalForwardingRule.ts#L76">property project</a>
</h3>

```typescript
public project: pulumi.Output<string>;
```


The ID of the project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/globalForwardingRule.ts#L80">property selfLink</a>
</h3>

```typescript
public selfLink: pulumi.Output<string>;
```


The URI of the created resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/globalForwardingRule.ts#L84">property target</a>
</h3>

```typescript
public target: pulumi.Output<string>;
```


URL of target HTTP or HTTPS proxy.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h2 class="pdoc-module-header" id="HealthCheck">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/healthCheck.ts#L14">class HealthCheck</a>
</h2>

Manages a health check within GCE. This is used to monitor instances
behind load balancers. Timeouts or HTTP errors cause the instance to be
removed from the pool. For more information, see [the official
documentation](https://cloud.google.com/compute/docs/load-balancing/health-checks)
and
[API](https://cloud.google.com/compute/docs/reference/latest/healthChecks).

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/healthCheck.ts#L82">constructor</a>
</h3>

```typescript
new HealthCheck(name: string, args?: HealthCheckArgs, opts?: pulumi.CustomResourceOptions)
```


Create a HealthCheck resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/healthCheck.ts#L23">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: HealthCheckState): HealthCheck
```


Get an existing HealthCheck resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method getProvider</a>
</h3>

```typescript
getProvider(moduleMember: string): ProviderResource | undefined
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/healthCheck.ts#L31">property checkIntervalSec</a>
</h3>

```typescript
public checkIntervalSec: pulumi.Output<number | undefined>;
```


The number of seconds between each poll of
the instance instance (default 5).

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/healthCheck.ts#L35">property description</a>
</h3>

```typescript
public description: pulumi.Output<string | undefined>;
```


Textual description field.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/healthCheck.ts#L39">property healthyThreshold</a>
</h3>

```typescript
public healthyThreshold: pulumi.Output<number | undefined>;
```


Consecutive successes required (default 2).

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/healthCheck.ts#L44">property httpHealthCheck</a>
</h3>

```typescript
public httpHealthCheck: pulumi.Output<{ ... } | undefined>;
```


An HTTP Health Check. Only one kind of Health Check can be added.
Structure is documented below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/healthCheck.ts#L49">property httpsHealthCheck</a>
</h3>

```typescript
public httpsHealthCheck: pulumi.Output<{ ... } | undefined>;
```


An HTTPS Health Check. Only one kind of Health Check can be added.
Structure is documented below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/healthCheck.ts#L54">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```


A unique name for the resource, required by GCE.
Changing this forces a new resource to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/healthCheck.ts#L59">property project</a>
</h3>

```typescript
public project: pulumi.Output<string>;
```


The project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/healthCheck.ts#L63">property selfLink</a>
</h3>

```typescript
public selfLink: pulumi.Output<string>;
```


The URI of the created resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/healthCheck.ts#L68">property sslHealthCheck</a>
</h3>

```typescript
public sslHealthCheck: pulumi.Output<{ ... } | undefined>;
```


An SSL Health Check. Only one kind of Health Check can be added.
Structure is documented below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/healthCheck.ts#L73">property tcpHealthCheck</a>
</h3>

```typescript
public tcpHealthCheck: pulumi.Output<{ ... } | undefined>;
```


A TCP Health Check. Only one kind of Health Check can be added.
Structure is documented below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/healthCheck.ts#L78">property timeoutSec</a>
</h3>

```typescript
public timeoutSec: pulumi.Output<number | undefined>;
```


The number of seconds to wait before declaring
failure (default 5).

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/healthCheck.ts#L82">property unhealthyThreshold</a>
</h3>

```typescript
public unhealthyThreshold: pulumi.Output<number | undefined>;
```


Consecutive failures required (default 2).

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h2 class="pdoc-module-header" id="HttpHealthCheck">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpHealthCheck.ts#L6">class HttpHealthCheck</a>
</h2>
<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpHealthCheck.ts#L37">constructor</a>
</h3>

```typescript
new HttpHealthCheck(name: string, args?: HttpHealthCheckArgs, opts?: pulumi.CustomResourceOptions)
```


Create a HttpHealthCheck resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpHealthCheck.ts#L15">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: HttpHealthCheckState): HttpHealthCheck
```


Get an existing HttpHealthCheck resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method getProvider</a>
</h3>

```typescript
getProvider(moduleMember: string): ProviderResource | undefined
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpHealthCheck.ts#L19">property checkIntervalSec</a>
</h3>

```typescript
public checkIntervalSec: pulumi.Output<number | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpHealthCheck.ts#L20">property creationTimestamp</a>
</h3>

```typescript
public creationTimestamp: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpHealthCheck.ts#L21">property description</a>
</h3>

```typescript
public description: pulumi.Output<string | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpHealthCheck.ts#L22">property healthyThreshold</a>
</h3>

```typescript
public healthyThreshold: pulumi.Output<number | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpHealthCheck.ts#L23">property host</a>
</h3>

```typescript
public host: pulumi.Output<string | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpHealthCheck.ts#L24">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpHealthCheck.ts#L25">property port</a>
</h3>

```typescript
public port: pulumi.Output<number | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpHealthCheck.ts#L30">property project</a>
</h3>

```typescript
public project: pulumi.Output<string>;
```


The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpHealthCheck.ts#L31">property requestPath</a>
</h3>

```typescript
public requestPath: pulumi.Output<string | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpHealthCheck.ts#L35">property selfLink</a>
</h3>

```typescript
public selfLink: pulumi.Output<string>;
```


The URI of the created resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpHealthCheck.ts#L36">property timeoutSec</a>
</h3>

```typescript
public timeoutSec: pulumi.Output<number | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpHealthCheck.ts#L37">property unhealthyThreshold</a>
</h3>

```typescript
public unhealthyThreshold: pulumi.Output<number | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h2 class="pdoc-module-header" id="HttpsHealthCheck">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpsHealthCheck.ts#L6">class HttpsHealthCheck</a>
</h2>
<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpsHealthCheck.ts#L37">constructor</a>
</h3>

```typescript
new HttpsHealthCheck(name: string, args?: HttpsHealthCheckArgs, opts?: pulumi.CustomResourceOptions)
```


Create a HttpsHealthCheck resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpsHealthCheck.ts#L15">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: HttpsHealthCheckState): HttpsHealthCheck
```


Get an existing HttpsHealthCheck resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method getProvider</a>
</h3>

```typescript
getProvider(moduleMember: string): ProviderResource | undefined
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpsHealthCheck.ts#L19">property checkIntervalSec</a>
</h3>

```typescript
public checkIntervalSec: pulumi.Output<number | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpsHealthCheck.ts#L20">property creationTimestamp</a>
</h3>

```typescript
public creationTimestamp: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpsHealthCheck.ts#L21">property description</a>
</h3>

```typescript
public description: pulumi.Output<string | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpsHealthCheck.ts#L22">property healthyThreshold</a>
</h3>

```typescript
public healthyThreshold: pulumi.Output<number | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpsHealthCheck.ts#L23">property host</a>
</h3>

```typescript
public host: pulumi.Output<string | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpsHealthCheck.ts#L24">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpsHealthCheck.ts#L25">property port</a>
</h3>

```typescript
public port: pulumi.Output<number | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpsHealthCheck.ts#L30">property project</a>
</h3>

```typescript
public project: pulumi.Output<string>;
```


The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpsHealthCheck.ts#L31">property requestPath</a>
</h3>

```typescript
public requestPath: pulumi.Output<string | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpsHealthCheck.ts#L35">property selfLink</a>
</h3>

```typescript
public selfLink: pulumi.Output<string>;
```


The URI of the created resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpsHealthCheck.ts#L36">property timeoutSec</a>
</h3>

```typescript
public timeoutSec: pulumi.Output<number | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpsHealthCheck.ts#L37">property unhealthyThreshold</a>
</h3>

```typescript
public unhealthyThreshold: pulumi.Output<number | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h2 class="pdoc-module-header" id="Image">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/image.ts#L12">class Image</a>
</h2>

Creates a bootable VM image resource for Google Compute Engine from an existing
tarball. For more information see [the official documentation](https://cloud.google.com/compute/docs/images) and
[API](https://cloud.google.com/compute/docs/reference/latest/images).

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/image.ts#L74">constructor</a>
</h3>

```typescript
new Image(name: string, args?: ImageArgs, opts?: pulumi.CustomResourceOptions)
```


Create a Image resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/image.ts#L21">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: ImageState): Image
```


Get an existing Image resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method getProvider</a>
</h3>

```typescript
getProvider(moduleMember: string): ProviderResource | undefined
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/image.ts#L28">property createTimeout</a>
</h3>

```typescript
public createTimeout: pulumi.Output<number | undefined>;
```


Configurable timeout in minutes for creating images. Default is 4 minutes.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/image.ts#L32">property description</a>
</h3>

```typescript
public description: pulumi.Output<string | undefined>;
```


The description of the image to be created

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/image.ts#L36">property family</a>
</h3>

```typescript
public family: pulumi.Output<string | undefined>;
```


The name of the image family to which this image belongs.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/image.ts#L40">property labelFingerprint</a>
</h3>

```typescript
public labelFingerprint: pulumi.Output<string>;
```


The fingerprint of the assigned labels.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/image.ts#L44">property labels</a>
</h3>

```typescript
public labels: pulumi.Output<{ ... } | undefined>;
```


A set of key/value label pairs to assign to the image.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/image.ts#L49">property licenses</a>
</h3>

```typescript
public licenses: pulumi.Output<string[]>;
```


A list of license URIs to apply to this image. Changing this
forces a new resource to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/image.ts#L54">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```


A unique name for the resource, required by GCE.
Changing this forces a new resource to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/image.ts#L59">property project</a>
</h3>

```typescript
public project: pulumi.Output<string>;
```


The ID of the project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/image.ts#L65">property rawDisk</a>
</h3>

```typescript
public rawDisk: pulumi.Output<{ ... } | undefined>;
```


The raw disk that will be used as the source of the image.
Changing this forces a new resource to be created. Structure is documented
below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/image.ts#L69">property selfLink</a>
</h3>

```typescript
public selfLink: pulumi.Output<string>;
```


The URI of the created resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/image.ts#L74">property sourceDisk</a>
</h3>

```typescript
public sourceDisk: pulumi.Output<string | undefined>;
```


The URL of a disk that will be used as the source of the
image. Changing this forces a new resource to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h2 class="pdoc-module-header" id="Instance">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L13">class Instance</a>
</h2>

Manages a VM instance resource within GCE. For more information see
[the official documentation](https://cloud.google.com/compute/docs/instances)
and
[API](https://cloud.google.com/compute/docs/reference/latest/instances).

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L154">constructor</a>
</h3>

```typescript
new Instance(name: string, args: InstanceArgs, opts?: pulumi.CustomResourceOptions)
```


Create a Instance resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L22">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: InstanceState): Instance
```


Get an existing Instance resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method getProvider</a>
</h3>

```typescript
getProvider(moduleMember: string): ProviderResource | undefined
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L30">property allowStoppingForUpdate</a>
</h3>

```typescript
public allowStoppingForUpdate: pulumi.Output<boolean | undefined>;
```


If true, allows Terraform to stop the instance to update its properties.
If you try to update a property that requires stopping the instance without setting this field, the update will fail.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L34">property attachedDisks</a>
</h3>

```typescript
public attachedDisks: pulumi.Output<{ ... }[] | undefined>;
```


List of disks to attach to the instance. Structure is documented below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L39">property bootDisk</a>
</h3>

```typescript
public bootDisk: pulumi.Output<{ ... }>;
```


The boot disk for the instance.
Structure is documented below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L45">property canIpForward</a>
</h3>

```typescript
public canIpForward: pulumi.Output<boolean | undefined>;
```


Whether to allow sending and receiving of
packets with non-matching source or destination IPs.
This defaults to false.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L49">property cpuPlatform</a>
</h3>

```typescript
public cpuPlatform: pulumi.Output<string>;
```


The CPU platform used by this instance.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L54">property createTimeout</a>
</h3>

```typescript
public createTimeout: pulumi.Output<number | undefined>;
```


Configurable timeout in minutes for creating instances. Default is 4 minutes.
Changing this forces a new resource to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L59">property deletionProtection</a>
</h3>

```typescript
public deletionProtection: pulumi.Output<boolean | undefined>;
```


Enable deletion protection on this instance. Defaults to false.
**Note:** you must disable deletion protection before removing the resource (e.g., via `terraform destroy`), or the instance cannot be deleted and the Terraform run will not complete successfully.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L63">property description</a>
</h3>

```typescript
public description: pulumi.Output<string | undefined>;
```


A brief description of this resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L68">property guestAccelerators</a>
</h3>

```typescript
public guestAccelerators: pulumi.Output<{ ... }[]>;
```


List of the type and count of accelerator cards attached to the instance. Structure documented below.
**Note:** GPU accelerators can only be used with [`on_host_maintenance`](#on_host_maintenance) option set to TERMINATE.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L72">property instanceId</a>
</h3>

```typescript
public instanceId: pulumi.Output<string>;
```


The server-assigned unique identifier of this instance.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L76">property labelFingerprint</a>
</h3>

```typescript
public labelFingerprint: pulumi.Output<string>;
```


The unique fingerprint of the labels.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L80">property labels</a>
</h3>

```typescript
public labels: pulumi.Output<{ ... } | undefined>;
```


A set of key/value label pairs to assign to the instance.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L84">property machineType</a>
</h3>

```typescript
public machineType: pulumi.Output<string>;
```


The machine type to create.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L89">property metadata</a>
</h3>

```typescript
public metadata: pulumi.Output<{ ... } | undefined>;
```


Metadata key/value pairs to make available from
within the instance.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L93">property metadataFingerprint</a>
</h3>

```typescript
public metadataFingerprint: pulumi.Output<string>;
```


The unique fingerprint of the metadata.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L101">property metadataStartupScript</a>
</h3>

```typescript
public metadataStartupScript: pulumi.Output<string | undefined>;
```


An alternative to using the
startup-script metadata key, except this one forces the instance to be
recreated (thus re-running the script) if it is changed. This replaces the
startup-script metadata key on the created instance and thus the two
mechanisms are not allowed to be used simultaneously.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L107">property minCpuPlatform</a>
</h3>

```typescript
public minCpuPlatform: pulumi.Output<string | undefined>;
```


Specifies a minimum CPU platform for the VM instance. Applicable values are the friendly names of CPU platforms, such as
`Intel Haswell` or `Intel Skylake`. See the complete list [here](https://cloud.google.com/compute/docs/instances/specify-min-cpu-platform).
**Note**: [`allow_stopping_for_update`](#allow_stopping_for_update) must be set to true in order to update this field.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L112">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```


A unique name for the resource, required by GCE.
Changing this forces a new resource to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L117">property networkInterfaces</a>
</h3>

```typescript
public networkInterfaces: pulumi.Output<{ ... }[]>;
```


Networks to attach to the instance. This can
be specified multiple times. Structure is documented below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L122">property project</a>
</h3>

```typescript
public project: pulumi.Output<string>;
```


The ID of the project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L127">property scheduling</a>
</h3>

```typescript
public scheduling: pulumi.Output<{ ... }>;
```


The scheduling strategy to use. More details about
this configuration option are detailed below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L132">property scratchDisks</a>
</h3>

```typescript
public scratchDisks: pulumi.Output<{ ... }[] | undefined>;
```


Scratch disks to attach to the instance. This can be
specified multiple times for multiple scratch disks. Structure is documented below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L136">property selfLink</a>
</h3>

```typescript
public selfLink: pulumi.Output<string>;
```


The URI of the created resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L142">property serviceAccount</a>
</h3>

```typescript
public serviceAccount: pulumi.Output<{ ... } | undefined>;
```


Service account to attach to the instance.
Structure is documented below.
**Note**: [`allow_stopping_for_update`](#allow_stopping_for_update) must be set to true in order to update this field.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L146">property tags</a>
</h3>

```typescript
public tags: pulumi.Output<string[] | undefined>;
```


A list of tags to attach to the instance.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L150">property tagsFingerprint</a>
</h3>

```typescript
public tagsFingerprint: pulumi.Output<string>;
```


The unique fingerprint of the tags.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L154">property zone</a>
</h3>

```typescript
public zone: pulumi.Output<string>;
```


The zone that the machine should be created in.

<h2 class="pdoc-module-header" id="InstanceFromTemplate">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L17">class InstanceFromTemplate</a>
</h2>

Manages a VM instance resource within GCE. For more information see
[the official documentation](https://cloud.google.com/compute/docs/instances)
and
[API](https://cloud.google.com/compute/docs/reference/latest/instances).

This resource is specifically to create a compute instance from a given
`source_instance_template`. To create an instance without a template, use the
`google_compute_instance` resource.


<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L68">constructor</a>
</h3>

```typescript
new InstanceFromTemplate(name: string, args: InstanceFromTemplateArgs, opts?: pulumi.CustomResourceOptions)
```


Create a InstanceFromTemplate resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L26">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: InstanceFromTemplateState): InstanceFromTemplate
```


Get an existing InstanceFromTemplate resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method getProvider</a>
</h3>

```typescript
getProvider(moduleMember: string): ProviderResource | undefined
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L30">property allowStoppingForUpdate</a>
</h3>

```typescript
public allowStoppingForUpdate: pulumi.Output<boolean>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L31">property attachedDisks</a>
</h3>

```typescript
public attachedDisks: pulumi.Output<{ ... }[]>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L32">property bootDisk</a>
</h3>

```typescript
public bootDisk: pulumi.Output<{ ... }>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L33">property canIpForward</a>
</h3>

```typescript
public canIpForward: pulumi.Output<boolean>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L34">property cpuPlatform</a>
</h3>

```typescript
public cpuPlatform: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L35">property deletionProtection</a>
</h3>

```typescript
public deletionProtection: pulumi.Output<boolean>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L36">property description</a>
</h3>

```typescript
public description: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L37">property guestAccelerators</a>
</h3>

```typescript
public guestAccelerators: pulumi.Output<{ ... }[]>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L38">property instanceId</a>
</h3>

```typescript
public instanceId: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L39">property labelFingerprint</a>
</h3>

```typescript
public labelFingerprint: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L40">property labels</a>
</h3>

```typescript
public labels: pulumi.Output<{ ... }>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L41">property machineType</a>
</h3>

```typescript
public machineType: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L42">property metadata</a>
</h3>

```typescript
public metadata: pulumi.Output<{ ... }>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L43">property metadataFingerprint</a>
</h3>

```typescript
public metadataFingerprint: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L44">property metadataStartupScript</a>
</h3>

```typescript
public metadataStartupScript: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L45">property minCpuPlatform</a>
</h3>

```typescript
public minCpuPlatform: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L50">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```


A unique name for the resource, required by GCE.
Changing this forces a new resource to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L51">property networkInterfaces</a>
</h3>

```typescript
public networkInterfaces: pulumi.Output<{ ... }[]>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L52">property project</a>
</h3>

```typescript
public project: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L53">property scheduling</a>
</h3>

```typescript
public scheduling: pulumi.Output<{ ... }>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L54">property scratchDisks</a>
</h3>

```typescript
public scratchDisks: pulumi.Output<{ ... }[]>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L55">property selfLink</a>
</h3>

```typescript
public selfLink: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L56">property serviceAccount</a>
</h3>

```typescript
public serviceAccount: pulumi.Output<{ ... }>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L61">property sourceInstanceTemplate</a>
</h3>

```typescript
public sourceInstanceTemplate: pulumi.Output<string>;
```


Name or self link of an instance
template to create the instance based on.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L62">property tags</a>
</h3>

```typescript
public tags: pulumi.Output<string[]>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L63">property tagsFingerprint</a>
</h3>

```typescript
public tagsFingerprint: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L68">property zone</a>
</h3>

```typescript
public zone: pulumi.Output<string>;
```


The zone that the machine should be created in. If not
set, the provider zone is used.

<h2 class="pdoc-module-header" id="InstanceGroup">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroup.ts#L11">class InstanceGroup</a>
</h2>

Creates a group of dissimilar Compute Engine virtual machine instances.
For more information, see [the official documentation](https://cloud.google.com/compute/docs/instance-groups/#unmanaged_instance_groups)
and [API](https://cloud.google.com/compute/docs/reference/latest/instanceGroups)

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroup.ts#L67">constructor</a>
</h3>

```typescript
new InstanceGroup(name: string, args?: InstanceGroupArgs, opts?: pulumi.CustomResourceOptions)
```


Create a InstanceGroup resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroup.ts#L20">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: InstanceGroupState): InstanceGroup
```


Get an existing InstanceGroup resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method getProvider</a>
</h3>

```typescript
getProvider(moduleMember: string): ProviderResource | undefined
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroup.ts#L28">property description</a>
</h3>

```typescript
public description: pulumi.Output<string | undefined>;
```


An optional textual description of the instance
group.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroup.ts#L34">property instances</a>
</h3>

```typescript
public instances: pulumi.Output<string[]>;
```


List of instances in the group. They should be given
as self_link URLs. When adding instances they must all be in the same
network and zone as the instance group.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroup.ts#L38">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```


The name which the port will be mapped to.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroup.ts#L43">property namedPorts</a>
</h3>

```typescript
public namedPorts: pulumi.Output<{ ... }[] | undefined>;
```


The named port configuration. See the section below
for details on configuration.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroup.ts#L50">property network</a>
</h3>

```typescript
public network: pulumi.Output<string>;
```


The URL of the network the instance group is in. If
this is different from the network where the instances are in, the creation
fails. Defaults to the network where the instances are in (if neither
`network` nor `instances` is specified, this field will be blank).

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroup.ts#L55">property project</a>
</h3>

```typescript
public project: pulumi.Output<string>;
```


The ID of the project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroup.ts#L59">property selfLink</a>
</h3>

```typescript
public selfLink: pulumi.Output<string>;
```


The URI of the created resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroup.ts#L63">property size</a>
</h3>

```typescript
public size: pulumi.Output<number>;
```


The number of instances in the group.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroup.ts#L67">property zone</a>
</h3>

```typescript
public zone: pulumi.Output<string>;
```


The zone that this instance group should be created in.

<h2 class="pdoc-module-header" id="InstanceGroupManager">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroupManager.ts#L14">class InstanceGroupManager</a>
</h2>

The Google Compute Engine Instance Group Manager API creates and manages pools
of homogeneous Compute Engine virtual machine instances from a common instance
template. For more information, see [the official documentation](https://cloud.google.com/compute/docs/instance-groups/manager)
and [API](https://cloud.google.com/compute/docs/reference/latest/instanceGroupManagers)

~> **Note:** Use [google_compute_region_instance_group_manager](/docs/providers/google/r/compute_region_instance_group_manager.html) to create a regional (multi-zone) instance group manager.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroupManager.ts#L118">constructor</a>
</h3>

```typescript
new InstanceGroupManager(name: string, args: InstanceGroupManagerArgs, opts?: pulumi.CustomResourceOptions)
```


Create a InstanceGroupManager resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroupManager.ts#L23">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: InstanceGroupManagerState): InstanceGroupManager
```


Get an existing InstanceGroupManager resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method getProvider</a>
</h3>

```typescript
getProvider(moduleMember: string): ProviderResource | undefined
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroupManager.ts#L31">property autoHealingPolicies</a>
</h3>

```typescript
public autoHealingPolicies: pulumi.Output<{ ... } | undefined>;
```


) The autohealing policies for this managed instance
group. You can specify only one value. Structure is documented below. For more information, see the [official documentation](https://cloud.google.com/compute/docs/instance-groups/creating-groups-of-managed-instances#monitoring_groups).

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroupManager.ts#L40">property baseInstanceName</a>
</h3>

```typescript
public baseInstanceName: pulumi.Output<string>;
```


The base instance name to use for
instances in this group. The value must be a valid
[RFC1035](https://www.ietf.org/rfc/rfc1035.txt) name. Supported characters
are lowercase letters, numbers, and hyphens (-). Instances are named by
appending a hyphen and a random four-character string to the base instance
name.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroupManager.ts#L45">property description</a>
</h3>

```typescript
public description: pulumi.Output<string | undefined>;
```


An optional textual description of the instance
group manager.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroupManager.ts#L49">property fingerprint</a>
</h3>

```typescript
public fingerprint: pulumi.Output<string>;
```


The fingerprint of the instance group manager.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroupManager.ts#L53">property instanceGroup</a>
</h3>

```typescript
public instanceGroup: pulumi.Output<string>;
```


The full URL of the instance group created by the manager.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroupManager.ts#L57">property instanceTemplate</a>
</h3>

```typescript
public instanceTemplate: pulumi.Output<string | undefined>;
```


- The full URL to an instance template from which all new instances of this version will be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroupManager.ts#L61">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```


- Version name.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroupManager.ts#L66">property namedPorts</a>
</h3>

```typescript
public namedPorts: pulumi.Output<{ ... }[] | undefined>;
```


The named port configuration. See the section below
for details on configuration.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroupManager.ts#L71">property project</a>
</h3>

```typescript
public project: pulumi.Output<string>;
```


The ID of the project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroupManager.ts#L76">property rollingUpdatePolicy</a>
</h3>

```typescript
public rollingUpdatePolicy: pulumi.Output<{ ... } | undefined>;
```


) The update policy for this managed instance group. Structure is documented below. For more information, see the [official documentation](https://cloud.google.com/compute/docs/instance-groups/updating-managed-instance-groups) and [API](https://cloud.google.com/compute/docs/reference/rest/beta/instanceGroupManagers/patch)
- - -

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroupManager.ts#L80">property selfLink</a>
</h3>

```typescript
public selfLink: pulumi.Output<string>;
```


The URL of the created resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroupManager.ts#L86">property targetPools</a>
</h3>

```typescript
public targetPools: pulumi.Output<string[] | undefined>;
```


The full URL of all target pools to which new
instances in the group are added. Updating the target pools attribute does
not affect existing instances.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroupManager.ts#L90">property targetSize</a>
</h3>

```typescript
public targetSize: pulumi.Output<number>;
```


- The number of instances calculated as a fixed number or a percentage depending on the settings. Structure is documented below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroupManager.ts#L98">property updateStrategy</a>
</h3>

```typescript
public updateStrategy: pulumi.Output<string | undefined>;
```


If the `instance_template`
resource is modified, a value of `"NONE"` will prevent any of the managed
instances from being restarted by Terraform. A value of `"RESTART"` will
restart all of the instances at once. `"ROLLING_UPDATE"` is supported as [Beta feature].
A value of `"ROLLING_UPDATE"` requires `rolling_update_policy` block to be set

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroupManager.ts#L107">property versions</a>
</h3>

```typescript
public versions: pulumi.Output<{ ... }[]>;
```


Application versions managed by this instance group. Each
version deals with a specific instance template, allowing canary release scenarios.
Conflicts with `instance_template`. Structure is documented below. Beware that
exactly one version must not specify a target size. It means that versions with
a target size will respect the setting, and the one without target size will
be applied to all remaining Instances (top level target_size - each version target_size).

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroupManager.ts#L113">property waitForInstances</a>
</h3>

```typescript
public waitForInstances: pulumi.Output<boolean | undefined>;
```


Whether to wait for all instances to be created/updated before
returning. Note that if this is set to true and the operation does not succeed, Terraform will
continue trying until it times out.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroupManager.ts#L118">property zone</a>
</h3>

```typescript
public zone: pulumi.Output<string>;
```


The zone that instances in this group should be created
in.

<h2 class="pdoc-module-header" id="InstanceTemplate">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceTemplate.ts#L13">class InstanceTemplate</a>
</h2>

Manages a VM instance template resource within GCE. For more information see
[the official documentation](https://cloud.google.com/compute/docs/instance-templates)
and
[API](https://cloud.google.com/compute/docs/reference/latest/instanceTemplates).

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceTemplate.ts#L130">constructor</a>
</h3>

```typescript
new InstanceTemplate(name: string, args: InstanceTemplateArgs, opts?: pulumi.CustomResourceOptions)
```


Create a InstanceTemplate resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceTemplate.ts#L22">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: InstanceTemplateState): InstanceTemplate
```


Get an existing InstanceTemplate resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method getProvider</a>
</h3>

```typescript
getProvider(moduleMember: string): ProviderResource | undefined
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceTemplate.ts#L30">property canIpForward</a>
</h3>

```typescript
public canIpForward: pulumi.Output<boolean | undefined>;
```


Whether to allow sending and receiving of
packets with non-matching source or destination IPs. This defaults to false.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceTemplate.ts#L34">property description</a>
</h3>

```typescript
public description: pulumi.Output<string | undefined>;
```


A brief description of this resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceTemplate.ts#L40">property disks</a>
</h3>

```typescript
public disks: pulumi.Output<{ ... }[]>;
```


Disks to attach to instances created from this template.
This can be specified multiple times for multiple disks. Structure is
documented below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceTemplate.ts#L44">property guestAccelerators</a>
</h3>

```typescript
public guestAccelerators: pulumi.Output<{ ... }[] | undefined>;
```


List of the type and count of accelerator cards attached to the instance. Structure documented below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceTemplate.ts#L49">property instanceDescription</a>
</h3>

```typescript
public instanceDescription: pulumi.Output<string | undefined>;
```


A brief description to use for instances
created from this template.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceTemplate.ts#L54">property labels</a>
</h3>

```typescript
public labels: pulumi.Output<{ ... } | undefined>;
```


A set of key/value label pairs to assign to instances
created from this template,

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceTemplate.ts#L58">property machineType</a>
</h3>

```typescript
public machineType: pulumi.Output<string>;
```


The machine type to create.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceTemplate.ts#L63">property metadata</a>
</h3>

```typescript
public metadata: pulumi.Output<{ ... } | undefined>;
```


Metadata key/value pairs to make available from
within instances created from this template.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceTemplate.ts#L67">property metadataFingerprint</a>
</h3>

```typescript
public metadataFingerprint: pulumi.Output<string>;
```


The unique fingerprint of the metadata.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceTemplate.ts#L74">property metadataStartupScript</a>
</h3>

```typescript
public metadataStartupScript: pulumi.Output<string | undefined>;
```


An alternative to using the
startup-script metadata key, mostly to match the compute_instance resource.
This replaces the startup-script metadata key on the created instance and
thus the two mechanisms are not allowed to be used simultaneously.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceTemplate.ts#L79">property minCpuPlatform</a>
</h3>

```typescript
public minCpuPlatform: pulumi.Output<string | undefined>;
```


Specifies a minimum CPU platform. Applicable values are the friendly names of CPU platforms, such as
`Intel Haswell` or `Intel Skylake`. See the complete list [here](https://cloud.google.com/compute/docs/instances/specify-min-cpu-platform).

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceTemplate.ts#L84">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```


The name of the instance template. If you leave
this blank, Terraform will auto-generate a unique name.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceTemplate.ts#L89">property namePrefix</a>
</h3>

```typescript
public namePrefix: pulumi.Output<string>;
```


Creates a unique name beginning with the specified
prefix. Conflicts with `name`.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceTemplate.ts#L95">property networkInterfaces</a>
</h3>

```typescript
public networkInterfaces: pulumi.Output<{ ... }[] | undefined>;
```


Networks to attach to instances created from
this template. This can be specified multiple times for multiple networks.
Structure is documented below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceTemplate.ts#L100">property project</a>
</h3>

```typescript
public project: pulumi.Output<string>;
```


The ID of the project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceTemplate.ts#L109">property region</a>
</h3>

```typescript
public region: pulumi.Output<string>;
```


An instance template is a global resource that is not
bound to a zone or a region. However, you can still specify some regional
resources in an instance template, which restricts the template to the
region where that resource resides. For example, a custom `subnetwork`
resource is tied to a specific region. Defaults to the region of the
Provider if no value is given.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceTemplate.ts#L114">property schedulings</a>
</h3>

```typescript
public schedulings: pulumi.Output<{ ... }[]>;
```


The scheduling strategy to use. More details about
this configuration option are detailed below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceTemplate.ts#L118">property selfLink</a>
</h3>

```typescript
public selfLink: pulumi.Output<string>;
```


The URI of the created resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceTemplate.ts#L122">property serviceAccount</a>
</h3>

```typescript
public serviceAccount: pulumi.Output<{ ... } | undefined>;
```


Service account to attach to the instance. Structure is documented below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceTemplate.ts#L126">property tags</a>
</h3>

```typescript
public tags: pulumi.Output<string[] | undefined>;
```


Tags to attach to the instance.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceTemplate.ts#L130">property tagsFingerprint</a>
</h3>

```typescript
public tagsFingerprint: pulumi.Output<string>;
```


The unique fingerprint of the tags.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h2 class="pdoc-module-header" id="Network">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/network.ts#L12">class Network</a>
</h2>

Manages a network within GCE. For more information see
[the official documentation](https://cloud.google.com/compute/docs/vpc)
and
[API](https://cloud.google.com/compute/docs/reference/latest/networks).

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/network.ts#L66">constructor</a>
</h3>

```typescript
new Network(name: string, args?: NetworkArgs, opts?: pulumi.CustomResourceOptions)
```


Create a Network resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/network.ts#L21">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: NetworkState): Network
```


Get an existing Network resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method getProvider</a>
</h3>

```typescript
getProvider(moduleMember: string): ProviderResource | undefined
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/network.ts#L31">property autoCreateSubnetworks</a>
</h3>

```typescript
public autoCreateSubnetworks: pulumi.Output<boolean | undefined>;
```


If set to true, this network will be
created in auto subnet mode, and Google will create a subnet for each region
automatically. If set to false, a custom subnetted network will be created that
can support `google_compute_subnetwork` resources. Defaults to true.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/network.ts#L35">property description</a>
</h3>

```typescript
public description: pulumi.Output<string | undefined>;
```


A brief description of this resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/network.ts#L39">property gatewayIpv4</a>
</h3>

```typescript
public gatewayIpv4: pulumi.Output<string>;
```


The IPv4 address of the gateway.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/network.ts#L45">property ipv4Range</a>
</h3>

```typescript
public ipv4Range: pulumi.Output<string | undefined>;
```


If set to a CIDR block, uses the legacy VPC API with the
specified range. This API is deprecated. If set, `auto_create_subnetworks` must be
explicitly set to false.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/network.ts#L50">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```


A unique name for the resource, required by GCE.
Changing this forces a new resource to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/network.ts#L55">property project</a>
</h3>

```typescript
public project: pulumi.Output<string>;
```


The ID of the project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/network.ts#L62">property routingMode</a>
</h3>

```typescript
public routingMode: pulumi.Output<string>;
```


Sets the network-wide routing mode for Cloud Routers
to use. Accepted values are `"GLOBAL"` or `"REGIONAL"`. Defaults to `"REGIONAL"`.
Refer to the [Cloud Router documentation](https://cloud.google.com/router/docs/concepts/overview#dynamic-routing-mode)
for more details.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/network.ts#L66">property selfLink</a>
</h3>

```typescript
public selfLink: pulumi.Output<string>;
```


The URI of the created resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h2 class="pdoc-module-header" id="NetworkPeering">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/networkPeering.ts#L16">class NetworkPeering</a>
</h2>

Manages a network peering within GCE. For more information see
[the official documentation](https://cloud.google.com/compute/docs/vpc/vpc-peering)
and
[API](https://cloud.google.com/compute/docs/reference/latest/networks).

~> **Note:** Both network must create a peering with each other for the peering to be functional.

~> **Note:** Subnets IP ranges across peered VPC networks cannot overlap.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/networkPeering.ts#L53">constructor</a>
</h3>

```typescript
new NetworkPeering(name: string, args: NetworkPeeringArgs, opts?: pulumi.CustomResourceOptions)
```


Create a NetworkPeering resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/networkPeering.ts#L25">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: NetworkPeeringState): NetworkPeering
```


Get an existing NetworkPeering resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method getProvider</a>
</h3>

```typescript
getProvider(moduleMember: string): ProviderResource | undefined
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/networkPeering.ts#L33">property autoCreateRoutes</a>
</h3>

```typescript
public autoCreateRoutes: pulumi.Output<boolean | undefined>;
```


If set to `true`, the routes between the two networks will
be created and managed automatically. Defaults to `true`.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/networkPeering.ts#L37">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```


Name of the peering.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/networkPeering.ts#L41">property network</a>
</h3>

```typescript
public network: pulumi.Output<string>;
```


Resource link of the network to add a peering to.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/networkPeering.ts#L45">property peerNetwork</a>
</h3>

```typescript
public peerNetwork: pulumi.Output<string>;
```


Resource link of the peer network.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/networkPeering.ts#L49">property state</a>
</h3>

```typescript
public state: pulumi.Output<string>;
```


State for the peering.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/networkPeering.ts#L53">property stateDetails</a>
</h3>

```typescript
public stateDetails: pulumi.Output<string>;
```


Details about the current state of the peering.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h2 class="pdoc-module-header" id="ProjectMetadata">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/projectMetadata.ts#L16">class ProjectMetadata</a>
</h2>

Manages metadata common to all instances for a project in GCE. For more information see
[the official documentation](https://cloud.google.com/compute/docs/storing-retrieving-metadata)
and
[API](https://cloud.google.com/compute/docs/reference/latest/projects/setCommonInstanceMetadata).

~> **Note:**  If you want to manage only single key/value pairs within the project metadata
rather than the entire set, then use
[google_compute_project_metadata_item](compute_project_metadata_item.html).

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/projectMetadata.ts#L38">constructor</a>
</h3>

```typescript
new ProjectMetadata(name: string, args: ProjectMetadataArgs, opts?: pulumi.CustomResourceOptions)
```


Create a ProjectMetadata resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/projectMetadata.ts#L25">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: ProjectMetadataState): ProjectMetadata
```


Get an existing ProjectMetadata resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method getProvider</a>
</h3>

```typescript
getProvider(moduleMember: string): ProviderResource | undefined
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/projectMetadata.ts#L33">property metadata</a>
</h3>

```typescript
public metadata: pulumi.Output<{ ... }>;
```


A series of key value pairs. Changing this resource
updates the GCE state.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/projectMetadata.ts#L38">property project</a>
</h3>

```typescript
public project: pulumi.Output<string>;
```


The ID of the project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h2 class="pdoc-module-header" id="ProjectMetadataItem">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/projectMetadataItem.ts#L12">class ProjectMetadataItem</a>
</h2>

Manages a single key/value pair on metadata common to all instances for
a project in GCE. Using `google_compute_project_metadata_item` lets you
manage a single key/value setting in Terraform rather than the entire
project metadata map.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/projectMetadataItem.ts#L37">constructor</a>
</h3>

```typescript
new ProjectMetadataItem(name: string, args: ProjectMetadataItemArgs, opts?: pulumi.CustomResourceOptions)
```


Create a ProjectMetadataItem resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/projectMetadataItem.ts#L21">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: ProjectMetadataItemState): ProjectMetadataItem
```


Get an existing ProjectMetadataItem resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method getProvider</a>
</h3>

```typescript
getProvider(moduleMember: string): ProviderResource | undefined
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/projectMetadataItem.ts#L28">property key</a>
</h3>

```typescript
public key: pulumi.Output<string>;
```


The metadata key to set.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/projectMetadataItem.ts#L33">property project</a>
</h3>

```typescript
public project: pulumi.Output<string>;
```


The ID of the project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/projectMetadataItem.ts#L37">property value</a>
</h3>

```typescript
public value: pulumi.Output<string>;
```


The value to set for the given metadata key.

<h2 class="pdoc-module-header" id="RegionAutoscaler">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionAutoscaler.ts#L6">class RegionAutoscaler</a>
</h2>
<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionAutoscaler.ts#L33">constructor</a>
</h3>

```typescript
new RegionAutoscaler(name: string, args: RegionAutoscalerArgs, opts?: pulumi.CustomResourceOptions)
```


Create a RegionAutoscaler resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionAutoscaler.ts#L15">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: RegionAutoscalerState): RegionAutoscaler
```


Get an existing RegionAutoscaler resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method getProvider</a>
</h3>

```typescript
getProvider(moduleMember: string): ProviderResource | undefined
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionAutoscaler.ts#L19">property autoscalingPolicy</a>
</h3>

```typescript
public autoscalingPolicy: pulumi.Output<{ ... }>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionAutoscaler.ts#L20">property creationTimestamp</a>
</h3>

```typescript
public creationTimestamp: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionAutoscaler.ts#L21">property description</a>
</h3>

```typescript
public description: pulumi.Output<string | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionAutoscaler.ts#L22">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionAutoscaler.ts#L27">property project</a>
</h3>

```typescript
public project: pulumi.Output<string>;
```


The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionAutoscaler.ts#L28">property region</a>
</h3>

```typescript
public region: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionAutoscaler.ts#L32">property selfLink</a>
</h3>

```typescript
public selfLink: pulumi.Output<string>;
```


The URI of the created resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionAutoscaler.ts#L33">property target</a>
</h3>

```typescript
public target: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h2 class="pdoc-module-header" id="RegionBackendService">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionBackendService.ts#L14">class RegionBackendService</a>
</h2>

A Region Backend Service defines a regionally-scoped group of virtual machines that will serve traffic for load balancing.
For more information see [the official documentation](https://cloud.google.com/compute/docs/load-balancing/internal/)
and [API](https://cloud.google.com/compute/docs/reference/latest/regionBackendServices).

~> **Note**: Region backend services can only be used when using internal load balancing. For external load balancing, use
  [`google_compute_backend_service`](compute_backend_service.html) instead.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionBackendService.ts#L84">constructor</a>
</h3>

```typescript
new RegionBackendService(name: string, args: RegionBackendServiceArgs, opts?: pulumi.CustomResourceOptions)
```


Create a RegionBackendService resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionBackendService.ts#L23">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: RegionBackendServiceState): RegionBackendService
```


Get an existing RegionBackendService resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method getProvider</a>
</h3>

```typescript
getProvider(moduleMember: string): ProviderResource | undefined
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionBackendService.ts#L31">property backends</a>
</h3>

```typescript
public backends: pulumi.Output<{ ... }[] | undefined>;
```


The list of backends that serve this BackendService.
Structure is documented below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionBackendService.ts#L36">property connectionDrainingTimeoutSec</a>
</h3>

```typescript
public connectionDrainingTimeoutSec: pulumi.Output<number | undefined>;
```


Time for which instance will be drained
(not accept new connections, but still work to finish started ones). Defaults to `0`.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionBackendService.ts#L40">property description</a>
</h3>

```typescript
public description: pulumi.Output<string | undefined>;
```


Textual description for the backend.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionBackendService.ts#L44">property fingerprint</a>
</h3>

```typescript
public fingerprint: pulumi.Output<string>;
```


The fingerprint of the backend service.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionBackendService.ts#L50">property healthChecks</a>
</h3>

```typescript
public healthChecks: pulumi.Output<string>;
```


Specifies a list of health checks
for checking the health of the backend service. Currently at most
one health check can be specified, and a health check is required.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionBackendService.ts#L54">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```


The name of the backend service.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionBackendService.ts#L59">property project</a>
</h3>

```typescript
public project: pulumi.Output<string>;
```


The ID of the project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionBackendService.ts#L64">property protocol</a>
</h3>

```typescript
public protocol: pulumi.Output<string>;
```


The protocol for incoming requests. Defaults to
`TCP`.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionBackendService.ts#L69">property region</a>
</h3>

```typescript
public region: pulumi.Output<string>;
```


The Region in which the created address should reside.
If it is not provided, the provider region is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionBackendService.ts#L73">property selfLink</a>
</h3>

```typescript
public selfLink: pulumi.Output<string>;
```


The URI of the created resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionBackendService.ts#L79">property sessionAffinity</a>
</h3>

```typescript
public sessionAffinity: pulumi.Output<string>;
```


How to distribute load. Options are `NONE` (no
affinity), `CLIENT_IP`, `CLIENT_IP_PROTO`, or `CLIENT_IP_PORT_PROTO`.
Defaults to `NONE`.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionBackendService.ts#L84">property timeoutSec</a>
</h3>

```typescript
public timeoutSec: pulumi.Output<number>;
```


The number of secs to wait for a backend to respond
to a request before considering the request failed. Defaults to `30`.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h2 class="pdoc-module-header" id="RegionInstanceGroupManager">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionInstanceGroupManager.ts#L14">class RegionInstanceGroupManager</a>
</h2>

The Google Compute Engine Regional Instance Group Manager API creates and manages pools
of homogeneous Compute Engine virtual machine instances from a common instance
template. For more information, see [the official documentation](https://cloud.google.com/compute/docs/instance-groups/distributing-instances-with-regional-instance-groups)
and [API](https://cloud.google.com/compute/docs/reference/latest/regionInstanceGroupManagers)

~> **Note:** Use [google_compute_instance_group_manager](/docs/providers/google/r/compute_instance_group_manager.html) to create a single-zone instance group manager.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionInstanceGroupManager.ts#L116">constructor</a>
</h3>

```typescript
new RegionInstanceGroupManager(name: string, args: RegionInstanceGroupManagerArgs, opts?: pulumi.CustomResourceOptions)
```


Create a RegionInstanceGroupManager resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionInstanceGroupManager.ts#L23">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: RegionInstanceGroupManagerState): RegionInstanceGroupManager
```


Get an existing RegionInstanceGroupManager resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method getProvider</a>
</h3>

```typescript
getProvider(moduleMember: string): ProviderResource | undefined
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionInstanceGroupManager.ts#L31">property autoHealingPolicies</a>
</h3>

```typescript
public autoHealingPolicies: pulumi.Output<{ ... } | undefined>;
```


) The autohealing policies for this managed instance
group. You can specify only one value. Structure is documented below. For more information, see the [official documentation](https://cloud.google.com/compute/docs/instance-groups/creating-groups-of-managed-instances#monitoring_groups).

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionInstanceGroupManager.ts#L40">property baseInstanceName</a>
</h3>

```typescript
public baseInstanceName: pulumi.Output<string>;
```


The base instance name to use for
instances in this group. The value must be a valid
[RFC1035](https://www.ietf.org/rfc/rfc1035.txt) name. Supported characters
are lowercase letters, numbers, and hyphens (-). Instances are named by
appending a hyphen and a random four-character string to the base instance
name.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionInstanceGroupManager.ts#L45">property description</a>
</h3>

```typescript
public description: pulumi.Output<string | undefined>;
```


An optional textual description of the instance
group manager.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionInstanceGroupManager.ts#L51">property distributionPolicyZones</a>
</h3>

```typescript
public distributionPolicyZones: pulumi.Output<string[]>;
```


) The distribution policy for this managed instance
group. You can specify one or more values. For more information, see the [official documentation](https://cloud.google.com/compute/docs/instance-groups/distributing-instances-with-regional-instance-groups#selectingzones).
- - -

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionInstanceGroupManager.ts#L55">property fingerprint</a>
</h3>

```typescript
public fingerprint: pulumi.Output<string>;
```


The fingerprint of the instance group manager.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionInstanceGroupManager.ts#L59">property instanceGroup</a>
</h3>

```typescript
public instanceGroup: pulumi.Output<string>;
```


The full URL of the instance group created by the manager.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionInstanceGroupManager.ts#L64">property instanceTemplate</a>
</h3>

```typescript
public instanceTemplate: pulumi.Output<string>;
```


The full URL to an instance template from
which all new instances will be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionInstanceGroupManager.ts#L68">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```


The name of the port.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionInstanceGroupManager.ts#L73">property namedPorts</a>
</h3>

```typescript
public namedPorts: pulumi.Output<{ ... }[] | undefined>;
```


The named port configuration. See the section below
for details on configuration.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionInstanceGroupManager.ts#L78">property project</a>
</h3>

```typescript
public project: pulumi.Output<string>;
```


The ID of the project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionInstanceGroupManager.ts#L82">property region</a>
</h3>

```typescript
public region: pulumi.Output<string>;
```


The region where the managed instance group resides.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionInstanceGroupManager.ts#L86">property rollingUpdatePolicy</a>
</h3>

```typescript
public rollingUpdatePolicy: pulumi.Output<{ ... } | undefined>;
```


) The update policy for this managed instance group. Structure is documented below. For more information, see the [official documentation](https://cloud.google.com/compute/docs/instance-groups/updating-managed-instance-groups) and [API](https://cloud.google.com/compute/docs/reference/rest/beta/regionInstanceGroupManagers/patch)

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionInstanceGroupManager.ts#L90">property selfLink</a>
</h3>

```typescript
public selfLink: pulumi.Output<string>;
```


The URL of the created resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionInstanceGroupManager.ts#L96">property targetPools</a>
</h3>

```typescript
public targetPools: pulumi.Output<string[] | undefined>;
```


The full URL of all target pools to which new
instances in the group are added. Updating the target pools attribute does
not affect existing instances.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionInstanceGroupManager.ts#L102">property targetSize</a>
</h3>

```typescript
public targetSize: pulumi.Output<number>;
```


The target number of running instances for this managed
instance group. This value should always be explicitly set unless this resource is attached to
an autoscaler, in which case it should never be set. Defaults to `0`.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionInstanceGroupManager.ts#L110">property updateStrategy</a>
</h3>

```typescript
public updateStrategy: pulumi.Output<string | undefined>;
```


If the `instance_template`
resource is modified, a value of `"NONE"` will prevent any of the managed
instances from being restarted by Terraform. A value of `"ROLLING_UPDATE"`
is supported as [Beta feature]. A value of `"ROLLING_UPDATE"` requires
`rolling_update_policy` block to be set

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionInstanceGroupManager.ts#L116">property waitForInstances</a>
</h3>

```typescript
public waitForInstances: pulumi.Output<boolean | undefined>;
```


Whether to wait for all instances to be created/updated before
returning. Note that if this is set to true and the operation does not succeed, Terraform will
continue trying until it times out.

<h2 class="pdoc-module-header" id="Route">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/route.ts#L6">class Route</a>
</h2>
<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/route.ts#L45">constructor</a>
</h3>

```typescript
new Route(name: string, args: RouteArgs, opts?: pulumi.CustomResourceOptions)
```


Create a Route resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/route.ts#L15">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: RouteState): Route
```


Get an existing Route resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method getProvider</a>
</h3>

```typescript
getProvider(moduleMember: string): ProviderResource | undefined
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/route.ts#L19">property description</a>
</h3>

```typescript
public description: pulumi.Output<string | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/route.ts#L20">property destRange</a>
</h3>

```typescript
public destRange: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/route.ts#L21">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/route.ts#L22">property network</a>
</h3>

```typescript
public network: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/route.ts#L23">property nextHopGateway</a>
</h3>

```typescript
public nextHopGateway: pulumi.Output<string | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/route.ts#L24">property nextHopInstance</a>
</h3>

```typescript
public nextHopInstance: pulumi.Output<string | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/route.ts#L31">property nextHopInstanceZone</a>
</h3>

```typescript
public nextHopInstanceZone: pulumi.Output<string | undefined>;
```


(Optional when `next_hop_instance` is
specified)  The zone of the instance specified in
`next_hop_instance`.  Omit if `next_hop_instance` is specified as
a URL.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/route.ts#L32">property nextHopIp</a>
</h3>

```typescript
public nextHopIp: pulumi.Output<string | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/route.ts#L33">property nextHopNetwork</a>
</h3>

```typescript
public nextHopNetwork: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/route.ts#L34">property nextHopVpnTunnel</a>
</h3>

```typescript
public nextHopVpnTunnel: pulumi.Output<string | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/route.ts#L35">property priority</a>
</h3>

```typescript
public priority: pulumi.Output<number | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/route.ts#L40">property project</a>
</h3>

```typescript
public project: pulumi.Output<string>;
```


The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/route.ts#L44">property selfLink</a>
</h3>

```typescript
public selfLink: pulumi.Output<string>;
```


The URI of the created resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/route.ts#L45">property tags</a>
</h3>

```typescript
public tags: pulumi.Output<string[] | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h2 class="pdoc-module-header" id="Router">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/router.ts#L6">class Router</a>
</h2>
<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/router.ts#L33">constructor</a>
</h3>

```typescript
new Router(name: string, args: RouterArgs, opts?: pulumi.CustomResourceOptions)
```


Create a Router resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/router.ts#L15">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: RouterState): Router
```


Get an existing Router resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method getProvider</a>
</h3>

```typescript
getProvider(moduleMember: string): ProviderResource | undefined
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/router.ts#L19">property bgp</a>
</h3>

```typescript
public bgp: pulumi.Output<{ ... } | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/router.ts#L20">property creationTimestamp</a>
</h3>

```typescript
public creationTimestamp: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/router.ts#L21">property description</a>
</h3>

```typescript
public description: pulumi.Output<string | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/router.ts#L22">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/router.ts#L23">property network</a>
</h3>

```typescript
public network: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/router.ts#L28">property project</a>
</h3>

```typescript
public project: pulumi.Output<string>;
```


The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/router.ts#L29">property region</a>
</h3>

```typescript
public region: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/router.ts#L33">property selfLink</a>
</h3>

```typescript
public selfLink: pulumi.Output<string>;
```


The URI of the created resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h2 class="pdoc-module-header" id="RouterInterface">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/routerInterface.ts#L12">class RouterInterface</a>
</h2>

Manages a Cloud Router interface. For more information see
[the official documentation](https://cloud.google.com/compute/docs/cloudrouter)
and
[API](https://cloud.google.com/compute/docs/reference/latest/routers).

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/routerInterface.ts#L55">constructor</a>
</h3>

```typescript
new RouterInterface(name: string, args: RouterInterfaceArgs, opts?: pulumi.CustomResourceOptions)
```


Create a RouterInterface resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/routerInterface.ts#L21">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: RouterInterfaceState): RouterInterface
```


Get an existing RouterInterface resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method getProvider</a>
</h3>

```typescript
getProvider(moduleMember: string): ProviderResource | undefined
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/routerInterface.ts#L29">property ipRange</a>
</h3>

```typescript
public ipRange: pulumi.Output<string | undefined>;
```


IP address and range of the interface. The IP range must be
in the RFC3927 link-local IP space. Changing this forces a new interface to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/routerInterface.ts#L34">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```


A unique name for the interface, required by GCE. Changing
this forces a new interface to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/routerInterface.ts#L39">property project</a>
</h3>

```typescript
public project: pulumi.Output<string>;
```


The ID of the project in which this interface's router belongs. If it
is not provided, the provider project is used. Changing this forces a new interface to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/routerInterface.ts#L45">property region</a>
</h3>

```typescript
public region: pulumi.Output<string>;
```


The region this interface's router sits in. If not specified,
the project region will be used. Changing this forces a new interface to be
created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/routerInterface.ts#L50">property router</a>
</h3>

```typescript
public router: pulumi.Output<string>;
```


The name of the router this interface will be attached to.
Changing this forces a new interface to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/routerInterface.ts#L55">property vpnTunnel</a>
</h3>

```typescript
public vpnTunnel: pulumi.Output<string>;
```


The name or resource link to the VPN tunnel this
interface will be linked to. Changing this forces a new interface to be created.

<h2 class="pdoc-module-header" id="RouterPeer">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/routerPeer.ts#L12">class RouterPeer</a>
</h2>

Manages a Cloud Router BGP peer. For more information see
[the official documentation](https://cloud.google.com/compute/docs/cloudrouter)
and
[API](https://cloud.google.com/compute/docs/reference/latest/routers).

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/routerPeer.ts#L69">constructor</a>
</h3>

```typescript
new RouterPeer(name: string, args: RouterPeerArgs, opts?: pulumi.CustomResourceOptions)
```


Create a RouterPeer resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/routerPeer.ts#L21">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: RouterPeerState): RouterPeer
```


Get an existing RouterPeer resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method getProvider</a>
</h3>

```typescript
getProvider(moduleMember: string): ProviderResource | undefined
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/routerPeer.ts#L29">property advertisedRoutePriority</a>
</h3>

```typescript
public advertisedRoutePriority: pulumi.Output<number | undefined>;
```


The priority of routes advertised to this BGP peer.
Changing this forces a new peer to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/routerPeer.ts#L34">property interface</a>
</h3>

```typescript
public interface: pulumi.Output<string>;
```


The name of the interface the BGP peer is associated with.
Changing this forces a new peer to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/routerPeer.ts#L38">property ipAddress</a>
</h3>

```typescript
public ipAddress: pulumi.Output<string>;
```


IP address of the interface inside Google Cloud Platform.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/routerPeer.ts#L43">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```


A unique name for BGP peer, required by GCE. Changing
this forces a new peer to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/routerPeer.ts#L48">property peerAsn</a>
</h3>

```typescript
public peerAsn: pulumi.Output<number>;
```


Peer BGP Autonomous System Number (ASN).
Changing this forces a new peer to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/routerPeer.ts#L53">property peerIpAddress</a>
</h3>

```typescript
public peerIpAddress: pulumi.Output<string | undefined>;
```


IP address of the BGP interface outside Google Cloud.
Changing this forces a new peer to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/routerPeer.ts#L58">property project</a>
</h3>

```typescript
public project: pulumi.Output<string>;
```


The ID of the project in which this peer's router belongs. If it
is not provided, the provider project is used. Changing this forces a new peer to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/routerPeer.ts#L64">property region</a>
</h3>

```typescript
public region: pulumi.Output<string>;
```


The region this peer's router sits in. If not specified,
the project region will be used. Changing this forces a new peer to be
created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/routerPeer.ts#L69">property router</a>
</h3>

```typescript
public router: pulumi.Output<string>;
```


The name of the router in which this BGP peer will be configured.
Changing this forces a new peer to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h2 class="pdoc-module-header" id="SSLCertificate">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sSLCertificate.ts#L13">class SSLCertificate</a>
</h2>

Creates an SSL certificate resource necessary for HTTPS load balancing in GCE.
For more information see
[the official documentation](https://cloud.google.com/compute/docs/load-balancing/http/ssl-certificates) and
[API](https://cloud.google.com/compute/docs/reference/latest/sslCertificates).

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sSLCertificate.ts#L64">constructor</a>
</h3>

```typescript
new SSLCertificate(name: string, args: SSLCertificateArgs, opts?: pulumi.CustomResourceOptions)
```


Create a SSLCertificate resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sSLCertificate.ts#L22">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: SSLCertificateState): SSLCertificate
```


Get an existing SSLCertificate resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method getProvider</a>
</h3>

```typescript
getProvider(moduleMember: string): ProviderResource | undefined
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sSLCertificate.ts#L31">property certificate</a>
</h3>

```typescript
public certificate: pulumi.Output<string>;
```


A local certificate file in PEM format. The chain
may be at most 5 certs long, and must include at least one intermediate
cert. Changing this forces a new resource to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sSLCertificate.ts#L35">property certificateId</a>
</h3>

```typescript
public certificateId: pulumi.Output<string>;
```


A unique ID for the certificate, assigned by GCE.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sSLCertificate.ts#L40">property description</a>
</h3>

```typescript
public description: pulumi.Output<string | undefined>;
```


An optional description of this resource.
Changing this forces a new resource to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sSLCertificate.ts#L45">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```


A unique name for the SSL certificate. If you leave
this blank, Terraform will auto-generate a unique name.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sSLCertificate.ts#L50">property namePrefix</a>
</h3>

```typescript
public namePrefix: pulumi.Output<string>;
```


Creates a unique name beginning with the specified
prefix. Conflicts with `name`.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sSLCertificate.ts#L55">property privateKey</a>
</h3>

```typescript
public privateKey: pulumi.Output<string>;
```


Write only private key in PEM format.
Changing this forces a new resource to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sSLCertificate.ts#L60">property project</a>
</h3>

```typescript
public project: pulumi.Output<string>;
```


The ID of the project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sSLCertificate.ts#L64">property selfLink</a>
</h3>

```typescript
public selfLink: pulumi.Output<string>;
```


The URI of the created resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h2 class="pdoc-module-header" id="SSLPolicy">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sSLPolicy.ts#L6">class SSLPolicy</a>
</h2>
<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sSLPolicy.ts#L35">constructor</a>
</h3>

```typescript
new SSLPolicy(name: string, args?: SSLPolicyArgs, opts?: pulumi.CustomResourceOptions)
```


Create a SSLPolicy resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sSLPolicy.ts#L15">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: SSLPolicyState): SSLPolicy
```


Get an existing SSLPolicy resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method getProvider</a>
</h3>

```typescript
getProvider(moduleMember: string): ProviderResource | undefined
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sSLPolicy.ts#L19">property creationTimestamp</a>
</h3>

```typescript
public creationTimestamp: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sSLPolicy.ts#L20">property customFeatures</a>
</h3>

```typescript
public customFeatures: pulumi.Output<string[] | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sSLPolicy.ts#L21">property description</a>
</h3>

```typescript
public description: pulumi.Output<string | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sSLPolicy.ts#L22">property enabledFeatures</a>
</h3>

```typescript
public enabledFeatures: pulumi.Output<string[]>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sSLPolicy.ts#L23">property fingerprint</a>
</h3>

```typescript
public fingerprint: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sSLPolicy.ts#L24">property minTlsVersion</a>
</h3>

```typescript
public minTlsVersion: pulumi.Output<string | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sSLPolicy.ts#L25">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sSLPolicy.ts#L26">property profile</a>
</h3>

```typescript
public profile: pulumi.Output<string | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sSLPolicy.ts#L31">property project</a>
</h3>

```typescript
public project: pulumi.Output<string>;
```


The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sSLPolicy.ts#L35">property selfLink</a>
</h3>

```typescript
public selfLink: pulumi.Output<string>;
```


The URI of the created resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h2 class="pdoc-module-header" id="SecurityPolicy">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/securityPolicy.ts#L13">class SecurityPolicy</a>
</h2>

A Security Policy defines an IP blacklist or whitelist that protects load balanced Google Cloud services by denying or permitting traffic from specified IP ranges. For more information
see the [official documentation](https://cloud.google.com/armor/docs/configure-security-policies)
and the [API](https://cloud.google.com/compute/docs/reference/rest/beta/securityPolicies).

~> **Note:** This entire resource is in [Beta](/docs/providers/google/index.html#beta-features)

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/securityPolicy.ts#L52">constructor</a>
</h3>

```typescript
new SecurityPolicy(name: string, args?: SecurityPolicyArgs, opts?: pulumi.CustomResourceOptions)
```


Create a SecurityPolicy resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/securityPolicy.ts#L22">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: SecurityPolicyState): SecurityPolicy
```


Get an existing SecurityPolicy resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method getProvider</a>
</h3>

```typescript
getProvider(moduleMember: string): ProviderResource | undefined
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/securityPolicy.ts#L29">property description</a>
</h3>

```typescript
public description: pulumi.Output<string | undefined>;
```


An optional description of this rule. Max size is 64.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/securityPolicy.ts#L33">property fingerprint</a>
</h3>

```typescript
public fingerprint: pulumi.Output<string>;
```


Fingerprint of this resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/securityPolicy.ts#L37">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```


The name of the security policy.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/securityPolicy.ts#L42">property project</a>
</h3>

```typescript
public project: pulumi.Output<string>;
```


The project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/securityPolicy.ts#L48">property rules</a>
</h3>

```typescript
public rules: pulumi.Output<{ ... }[]>;
```


The set of rules that belong to this policy. There must always be a default
rule (rule with priority 2147483647 and match "\*"). If no rules are provided when creating a
security policy, a default rule with action "allow" will be added. Structure is documented below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/securityPolicy.ts#L52">property selfLink</a>
</h3>

```typescript
public selfLink: pulumi.Output<string>;
```


The URI of the created resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h2 class="pdoc-module-header" id="SharedVPCHostProject">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sharedVPCHostProject.ts#L15">class SharedVPCHostProject</a>
</h2>

Enables the Google Compute Engine
[Shared VPC](https://cloud.google.com/compute/docs/shared-vpc)
feature for a project, assigning it as a Shared VPC host project.

For more information, see,
[the Project API documentation](https://cloud.google.com/compute/docs/reference/latest/projects),
where the Shared VPC feature is referred to by its former name "XPN".

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sharedVPCHostProject.ts#L31">constructor</a>
</h3>

```typescript
new SharedVPCHostProject(name: string, args: SharedVPCHostProjectArgs, opts?: pulumi.CustomResourceOptions)
```


Create a SharedVPCHostProject resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sharedVPCHostProject.ts#L24">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: SharedVPCHostProjectState): SharedVPCHostProject
```


Get an existing SharedVPCHostProject resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method getProvider</a>
</h3>

```typescript
getProvider(moduleMember: string): ProviderResource | undefined
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sharedVPCHostProject.ts#L31">property project</a>
</h3>

```typescript
public project: pulumi.Output<string>;
```


The ID of the project that will serve as a Shared VPC host project

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h2 class="pdoc-module-header" id="SharedVPCServiceProject">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sharedVPCServiceProject.ts#L16">class SharedVPCServiceProject</a>
</h2>

Enables the Google Compute Engine
[Shared VPC](https://cloud.google.com/compute/docs/shared-vpc)
feature for a project, assigning it as a Shared VPC service project associated
with a given host project.

For more information, see,
[the Project API documentation](https://cloud.google.com/compute/docs/reference/latest/projects),
where the Shared VPC feature is referred to by its former name "XPN".

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sharedVPCServiceProject.ts#L36">constructor</a>
</h3>

```typescript
new SharedVPCServiceProject(name: string, args: SharedVPCServiceProjectArgs, opts?: pulumi.CustomResourceOptions)
```


Create a SharedVPCServiceProject resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sharedVPCServiceProject.ts#L25">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: SharedVPCServiceProjectState): SharedVPCServiceProject
```


Get an existing SharedVPCServiceProject resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method getProvider</a>
</h3>

```typescript
getProvider(moduleMember: string): ProviderResource | undefined
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sharedVPCServiceProject.ts#L32">property hostProject</a>
</h3>

```typescript
public hostProject: pulumi.Output<string>;
```


The ID of a host project to associate.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sharedVPCServiceProject.ts#L36">property serviceProject</a>
</h3>

```typescript
public serviceProject: pulumi.Output<string>;
```


The ID of the project that will serve as a Shared VPC service project.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h2 class="pdoc-module-header" id="Snapshot">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/snapshot.ts#L12">class Snapshot</a>
</h2>

Creates a new snapshot of a disk within GCE. For more information see
[the official documentation](https://cloud.google.com/compute/docs/disks/create-snapshots)
and
[API](https://cloud.google.com/compute/docs/reference/latest/snapshots).

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/snapshot.ts#L86">constructor</a>
</h3>

```typescript
new Snapshot(name: string, args: SnapshotArgs, opts?: pulumi.CustomResourceOptions)
```


Create a Snapshot resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/snapshot.ts#L21">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: SnapshotState): Snapshot
```


Get an existing Snapshot resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method getProvider</a>
</h3>

```typescript
getProvider(moduleMember: string): ProviderResource | undefined
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/snapshot.ts#L28">property labelFingerprint</a>
</h3>

```typescript
public labelFingerprint: pulumi.Output<string>;
```


The unique fingerprint of the labels.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/snapshot.ts#L32">property labels</a>
</h3>

```typescript
public labels: pulumi.Output<{ ... } | undefined>;
```


A set of key/value label pairs to assign to the snapshot.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/snapshot.ts#L37">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```


A unique name for the resource, required by GCE.
Changing this forces a new resource to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/snapshot.ts#L42">property project</a>
</h3>

```typescript
public project: pulumi.Output<string>;
```


The ID of the project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/snapshot.ts#L46">property selfLink</a>
</h3>

```typescript
public selfLink: pulumi.Output<string>;
```


The URI of the created resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/snapshot.ts#L53">property snapshotEncryptionKeyRaw</a>
</h3>

```typescript
public snapshotEncryptionKeyRaw: pulumi.Output<string | undefined>;
```


A 256-bit [customer-supplied encryption key]
(https://cloud.google.com/compute/docs/disks/customer-supplied-encryption),
encoded in [RFC 4648 base64](https://tools.ietf.org/html/rfc4648#section-4)
to encrypt this snapshot.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/snapshot.ts#L60">property snapshotEncryptionKeySha256</a>
</h3>

```typescript
public snapshotEncryptionKeySha256: pulumi.Output<string>;
```


The [RFC 4648 base64]
(https://tools.ietf.org/html/rfc4648#section-4) encoded SHA-256 hash of the
[customer-supplied encryption key](https://cloud.google.com/compute/docs/disks/customer-supplied-encryption)
that protects this resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/snapshot.ts#L64">property sourceDisk</a>
</h3>

```typescript
public sourceDisk: pulumi.Output<string>;
```


The disk which will be used as the source of the snapshot.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/snapshot.ts#L71">property sourceDiskEncryptionKeyRaw</a>
</h3>

```typescript
public sourceDiskEncryptionKeyRaw: pulumi.Output<string | undefined>;
```


A 256-bit [customer-supplied encryption key]
(https://cloud.google.com/compute/docs/disks/customer-supplied-encryption),
encoded in [RFC 4648 base64](https://tools.ietf.org/html/rfc4648#section-4)
to decrypt the source disk.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/snapshot.ts#L78">property sourceDiskEncryptionKeySha256</a>
</h3>

```typescript
public sourceDiskEncryptionKeySha256: pulumi.Output<string>;
```


The [RFC 4648 base64]
(https://tools.ietf.org/html/rfc4648#section-4) encoded SHA-256 hash of the
[customer-supplied encryption key](https://cloud.google.com/compute/docs/disks/customer-supplied-encryption)
that protects the source disk.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/snapshot.ts#L82">property sourceDiskLink</a>
</h3>

```typescript
public sourceDiskLink: pulumi.Output<string>;
```


The URI of the source disk.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/snapshot.ts#L86">property zone</a>
</h3>

```typescript
public zone: pulumi.Output<string>;
```


The zone where the source disk is located.

<h2 class="pdoc-module-header" id="Subnetwork">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetwork.ts#L6">class Subnetwork</a>
</h2>
<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetwork.ts#L38">constructor</a>
</h3>

```typescript
new Subnetwork(name: string, args: SubnetworkArgs, opts?: pulumi.CustomResourceOptions)
```


Create a Subnetwork resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetwork.ts#L15">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: SubnetworkState): Subnetwork
```


Get an existing Subnetwork resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method getProvider</a>
</h3>

```typescript
getProvider(moduleMember: string): ProviderResource | undefined
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetwork.ts#L19">property creationTimestamp</a>
</h3>

```typescript
public creationTimestamp: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetwork.ts#L20">property description</a>
</h3>

```typescript
public description: pulumi.Output<string | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetwork.ts#L21">property enableFlowLogs</a>
</h3>

```typescript
public enableFlowLogs: pulumi.Output<boolean | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetwork.ts#L22">property fingerprint</a>
</h3>

```typescript
public fingerprint: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetwork.ts#L23">property gatewayAddress</a>
</h3>

```typescript
public gatewayAddress: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetwork.ts#L24">property ipCidrRange</a>
</h3>

```typescript
public ipCidrRange: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetwork.ts#L25">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetwork.ts#L26">property network</a>
</h3>

```typescript
public network: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetwork.ts#L27">property privateIpGoogleAccess</a>
</h3>

```typescript
public privateIpGoogleAccess: pulumi.Output<boolean | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetwork.ts#L32">property project</a>
</h3>

```typescript
public project: pulumi.Output<string>;
```


The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetwork.ts#L33">property region</a>
</h3>

```typescript
public region: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetwork.ts#L34">property secondaryIpRanges</a>
</h3>

```typescript
public secondaryIpRanges: pulumi.Output<{ ... }[]>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetwork.ts#L38">property selfLink</a>
</h3>

```typescript
public selfLink: pulumi.Output<string>;
```


The URI of the created resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h2 class="pdoc-module-header" id="SubnetworkIAMBinding">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetworkIAMBinding.ts#L19">class SubnetworkIAMBinding</a>
</h2>

Three different resources help you manage your IAM policy for GCE subnetwork. Each of these resources serves a different use case:

* `google_compute_subnetwork_iam_policy`: Authoritative. Sets the IAM policy for the subnetwork and replaces any existing policy already attached.
* `google_compute_subnetwork_iam_binding`: Authoritative for a given role. Updates the IAM policy to grant a role to a list of members. Other roles within the IAM policy for the subnetwork are preserved.
* `google_compute_subnetwork_iam_member`: Non-authoritative. Updates the IAM policy to grant a role to a new member. Other members for the role for the subnetwork are preserved.

~> **Note:** `google_compute_subnetwork_iam_policy` **cannot** be used in conjunction with `google_compute_subnetwork_iam_binding` and `google_compute_subnetwork_iam_member` or they will fight over what your policy should be.

~> **Note:** `google_compute_subnetwork_iam_binding` resources **can be** used in conjunction with `google_compute_subnetwork_iam_member` resources **only if** they do not grant privilege to the same role.

~> **Note:** These entire resources are in [Beta](/docs/providers/google/index.html#beta-features)

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetworkIAMBinding.ts#L56">constructor</a>
</h3>

```typescript
new SubnetworkIAMBinding(name: string, args: SubnetworkIAMBindingArgs, opts?: pulumi.CustomResourceOptions)
```


Create a SubnetworkIAMBinding resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetworkIAMBinding.ts#L28">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: SubnetworkIAMBindingState): SubnetworkIAMBinding
```


Get an existing SubnetworkIAMBinding resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method getProvider</a>
</h3>

```typescript
getProvider(moduleMember: string): ProviderResource | undefined
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetworkIAMBinding.ts#L35">property etag</a>
</h3>

```typescript
public etag: pulumi.Output<string>;
```


(Computed) The etag of the subnetwork's IAM policy.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetworkIAMBinding.ts#L36">property members</a>
</h3>

```typescript
public members: pulumi.Output<string[]>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetworkIAMBinding.ts#L41">property project</a>
</h3>

```typescript
public project: pulumi.Output<string>;
```


The ID of the project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetworkIAMBinding.ts#L46">property region</a>
</h3>

```typescript
public region: pulumi.Output<string>;
```


The region of the subnetwork. If
unspecified, this defaults to the region configured in the provider.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetworkIAMBinding.ts#L52">property role</a>
</h3>

```typescript
public role: pulumi.Output<string>;
```


The role that should be applied. Only one
`google_compute_subnetwork_iam_binding` can be used per role. Note that custom roles must be of the format
`[projects|organizations]/{parent-name}/roles/{role-name}`.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetworkIAMBinding.ts#L56">property subnetwork</a>
</h3>

```typescript
public subnetwork: pulumi.Output<string>;
```


The name of the subnetwork.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h2 class="pdoc-module-header" id="SubnetworkIAMMember">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetworkIAMMember.ts#L19">class SubnetworkIAMMember</a>
</h2>

Three different resources help you manage your IAM policy for GCE subnetwork. Each of these resources serves a different use case:

* `google_compute_subnetwork_iam_policy`: Authoritative. Sets the IAM policy for the subnetwork and replaces any existing policy already attached.
* `google_compute_subnetwork_iam_binding`: Authoritative for a given role. Updates the IAM policy to grant a role to a list of members. Other roles within the IAM policy for the subnetwork are preserved.
* `google_compute_subnetwork_iam_member`: Non-authoritative. Updates the IAM policy to grant a role to a new member. Other members for the role for the subnetwork are preserved.

~> **Note:** `google_compute_subnetwork_iam_policy` **cannot** be used in conjunction with `google_compute_subnetwork_iam_binding` and `google_compute_subnetwork_iam_member` or they will fight over what your policy should be.

~> **Note:** `google_compute_subnetwork_iam_binding` resources **can be** used in conjunction with `google_compute_subnetwork_iam_member` resources **only if** they do not grant privilege to the same role.

~> **Note:** These entire resources are in [Beta](/docs/providers/google/index.html#beta-features)

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetworkIAMMember.ts#L56">constructor</a>
</h3>

```typescript
new SubnetworkIAMMember(name: string, args: SubnetworkIAMMemberArgs, opts?: pulumi.CustomResourceOptions)
```


Create a SubnetworkIAMMember resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetworkIAMMember.ts#L28">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: SubnetworkIAMMemberState): SubnetworkIAMMember
```


Get an existing SubnetworkIAMMember resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method getProvider</a>
</h3>

```typescript
getProvider(moduleMember: string): ProviderResource | undefined
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetworkIAMMember.ts#L35">property etag</a>
</h3>

```typescript
public etag: pulumi.Output<string>;
```


(Computed) The etag of the subnetwork's IAM policy.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetworkIAMMember.ts#L36">property member</a>
</h3>

```typescript
public member: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetworkIAMMember.ts#L41">property project</a>
</h3>

```typescript
public project: pulumi.Output<string>;
```


The ID of the project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetworkIAMMember.ts#L46">property region</a>
</h3>

```typescript
public region: pulumi.Output<string>;
```


The region of the subnetwork. If
unspecified, this defaults to the region configured in the provider.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetworkIAMMember.ts#L52">property role</a>
</h3>

```typescript
public role: pulumi.Output<string>;
```


The role that should be applied. Only one
`google_compute_subnetwork_iam_binding` can be used per role. Note that custom roles must be of the format
`[projects|organizations]/{parent-name}/roles/{role-name}`.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetworkIAMMember.ts#L56">property subnetwork</a>
</h3>

```typescript
public subnetwork: pulumi.Output<string>;
```


The name of the subnetwork.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h2 class="pdoc-module-header" id="SubnetworkIAMPolicy">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetworkIAMPolicy.ts#L19">class SubnetworkIAMPolicy</a>
</h2>

Three different resources help you manage your IAM policy for GCE subnetwork. Each of these resources serves a different use case:

* `google_compute_subnetwork_iam_policy`: Authoritative. Sets the IAM policy for the subnetwork and replaces any existing policy already attached.
* `google_compute_subnetwork_iam_binding`: Authoritative for a given role. Updates the IAM policy to grant a role to a list of members. Other roles within the IAM policy for the subnetwork are preserved.
* `google_compute_subnetwork_iam_member`: Non-authoritative. Updates the IAM policy to grant a role to a new member. Other members for the role for the subnetwork are preserved.

~> **Note:** `google_compute_subnetwork_iam_policy` **cannot** be used in conjunction with `google_compute_subnetwork_iam_binding` and `google_compute_subnetwork_iam_member` or they will fight over what your policy should be.

~> **Note:** `google_compute_subnetwork_iam_binding` resources **can be** used in conjunction with `google_compute_subnetwork_iam_member` resources **only if** they do not grant privilege to the same role.

~> **Note:** These entire resources are in [Beta](/docs/providers/google/index.html#beta-features)

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetworkIAMPolicy.ts#L54">constructor</a>
</h3>

```typescript
new SubnetworkIAMPolicy(name: string, args: SubnetworkIAMPolicyArgs, opts?: pulumi.CustomResourceOptions)
```


Create a SubnetworkIAMPolicy resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetworkIAMPolicy.ts#L28">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: SubnetworkIAMPolicyState): SubnetworkIAMPolicy
```


Get an existing SubnetworkIAMPolicy resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method getProvider</a>
</h3>

```typescript
getProvider(moduleMember: string): ProviderResource | undefined
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetworkIAMPolicy.ts#L35">property etag</a>
</h3>

```typescript
public etag: pulumi.Output<string>;
```


(Computed) The etag of the subnetwork's IAM policy.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetworkIAMPolicy.ts#L40">property policyData</a>
</h3>

```typescript
public policyData: pulumi.Output<string>;
```


The policy data generated by
a `google_iam_policy` data source.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetworkIAMPolicy.ts#L45">property project</a>
</h3>

```typescript
public project: pulumi.Output<string>;
```


The ID of the project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetworkIAMPolicy.ts#L50">property region</a>
</h3>

```typescript
public region: pulumi.Output<string>;
```


The region of the subnetwork. If
unspecified, this defaults to the region configured in the provider.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetworkIAMPolicy.ts#L54">property subnetwork</a>
</h3>

```typescript
public subnetwork: pulumi.Output<string>;
```


The name of the subnetwork.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h2 class="pdoc-module-header" id="TargetHttpProxy">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetHttpProxy.ts#L6">class TargetHttpProxy</a>
</h2>
<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetHttpProxy.ts#L32">constructor</a>
</h3>

```typescript
new TargetHttpProxy(name: string, args: TargetHttpProxyArgs, opts?: pulumi.CustomResourceOptions)
```


Create a TargetHttpProxy resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetHttpProxy.ts#L15">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: TargetHttpProxyState): TargetHttpProxy
```


Get an existing TargetHttpProxy resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method getProvider</a>
</h3>

```typescript
getProvider(moduleMember: string): ProviderResource | undefined
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetHttpProxy.ts#L19">property creationTimestamp</a>
</h3>

```typescript
public creationTimestamp: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetHttpProxy.ts#L20">property description</a>
</h3>

```typescript
public description: pulumi.Output<string | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetHttpProxy.ts#L21">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetHttpProxy.ts#L26">property project</a>
</h3>

```typescript
public project: pulumi.Output<string>;
```


The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetHttpProxy.ts#L27">property proxyId</a>
</h3>

```typescript
public proxyId: pulumi.Output<number>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetHttpProxy.ts#L31">property selfLink</a>
</h3>

```typescript
public selfLink: pulumi.Output<string>;
```


The URI of the created resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetHttpProxy.ts#L32">property urlMap</a>
</h3>

```typescript
public urlMap: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h2 class="pdoc-module-header" id="TargetHttpsProxy">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetHttpsProxy.ts#L6">class TargetHttpsProxy</a>
</h2>
<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetHttpsProxy.ts#L35">constructor</a>
</h3>

```typescript
new TargetHttpsProxy(name: string, args: TargetHttpsProxyArgs, opts?: pulumi.CustomResourceOptions)
```


Create a TargetHttpsProxy resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetHttpsProxy.ts#L15">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: TargetHttpsProxyState): TargetHttpsProxy
```


Get an existing TargetHttpsProxy resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method getProvider</a>
</h3>

```typescript
getProvider(moduleMember: string): ProviderResource | undefined
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetHttpsProxy.ts#L19">property creationTimestamp</a>
</h3>

```typescript
public creationTimestamp: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetHttpsProxy.ts#L20">property description</a>
</h3>

```typescript
public description: pulumi.Output<string | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetHttpsProxy.ts#L21">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetHttpsProxy.ts#L26">property project</a>
</h3>

```typescript
public project: pulumi.Output<string>;
```


The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetHttpsProxy.ts#L27">property proxyId</a>
</h3>

```typescript
public proxyId: pulumi.Output<number>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetHttpsProxy.ts#L28">property quicOverride</a>
</h3>

```typescript
public quicOverride: pulumi.Output<string | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetHttpsProxy.ts#L32">property selfLink</a>
</h3>

```typescript
public selfLink: pulumi.Output<string>;
```


The URI of the created resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetHttpsProxy.ts#L33">property sslCertificates</a>
</h3>

```typescript
public sslCertificates: pulumi.Output<string[]>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetHttpsProxy.ts#L34">property sslPolicy</a>
</h3>

```typescript
public sslPolicy: pulumi.Output<string | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetHttpsProxy.ts#L35">property urlMap</a>
</h3>

```typescript
public urlMap: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h2 class="pdoc-module-header" id="TargetPool">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetPool.ts#L14">class TargetPool</a>
</h2>

Manages a Target Pool within GCE. This is a collection of instances used as
target of a network load balancer (Forwarding Rule). For more information see
[the official
documentation](https://cloud.google.com/compute/docs/load-balancing/network/target-pools)
and [API](https://cloud.google.com/compute/docs/reference/latest/targetPools).

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetPool.ts#L78">constructor</a>
</h3>

```typescript
new TargetPool(name: string, args?: TargetPoolArgs, opts?: pulumi.CustomResourceOptions)
```


Create a TargetPool resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetPool.ts#L23">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: TargetPoolState): TargetPool
```


Get an existing TargetPool resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method getProvider</a>
</h3>

```typescript
getProvider(moduleMember: string): ProviderResource | undefined
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetPool.ts#L31">property backupPool</a>
</h3>

```typescript
public backupPool: pulumi.Output<string | undefined>;
```


URL to the backup target pool. Must also set
failover\_ratio.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetPool.ts#L35">property description</a>
</h3>

```typescript
public description: pulumi.Output<string | undefined>;
```


Textual description field.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetPool.ts#L40">property failoverRatio</a>
</h3>

```typescript
public failoverRatio: pulumi.Output<number | undefined>;
```


Ratio (0 to 1) of failed nodes before using the
backup pool (which must also be set).

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetPool.ts#L45">property healthChecks</a>
</h3>

```typescript
public healthChecks: pulumi.Output<string | undefined>;
```


List of zero or one health check name or self_link. Only
legacy `google_compute_http_health_check` is supported.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetPool.ts#L53">property instances</a>
</h3>

```typescript
public instances: pulumi.Output<string[]>;
```


List of instances in the pool. They can be given as
URLs, or in the form of "zone/name". Note that the instances need not exist
at the time of target pool creation, so there is no need to use the
Terraform interpolators to create a dependency on the instances from the
target pool.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetPool.ts#L58">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```


A unique name for the resource, required by GCE. Changing
this forces a new resource to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetPool.ts#L63">property project</a>
</h3>

```typescript
public project: pulumi.Output<string>;
```


The ID of the project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetPool.ts#L68">property region</a>
</h3>

```typescript
public region: pulumi.Output<string>;
```


Where the target pool resides. Defaults to project
region.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetPool.ts#L72">property selfLink</a>
</h3>

```typescript
public selfLink: pulumi.Output<string>;
```


The URI of the created resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetPool.ts#L78">property sessionAffinity</a>
</h3>

```typescript
public sessionAffinity: pulumi.Output<string | undefined>;
```


How to distribute load. Options are "NONE" (no
affinity). "CLIENT\_IP" (hash of the source/dest addresses / ports), and
"CLIENT\_IP\_PROTO" also includes the protocol (default "NONE").

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h2 class="pdoc-module-header" id="TargetSSLProxy">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetSSLProxy.ts#L6">class TargetSSLProxy</a>
</h2>
<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetSSLProxy.ts#L35">constructor</a>
</h3>

```typescript
new TargetSSLProxy(name: string, args: TargetSSLProxyArgs, opts?: pulumi.CustomResourceOptions)
```


Create a TargetSSLProxy resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetSSLProxy.ts#L15">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: TargetSSLProxyState): TargetSSLProxy
```


Get an existing TargetSSLProxy resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method getProvider</a>
</h3>

```typescript
getProvider(moduleMember: string): ProviderResource | undefined
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetSSLProxy.ts#L19">property backendService</a>
</h3>

```typescript
public backendService: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetSSLProxy.ts#L20">property creationTimestamp</a>
</h3>

```typescript
public creationTimestamp: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetSSLProxy.ts#L21">property description</a>
</h3>

```typescript
public description: pulumi.Output<string | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetSSLProxy.ts#L22">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetSSLProxy.ts#L27">property project</a>
</h3>

```typescript
public project: pulumi.Output<string>;
```


The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetSSLProxy.ts#L28">property proxyHeader</a>
</h3>

```typescript
public proxyHeader: pulumi.Output<string | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetSSLProxy.ts#L29">property proxyId</a>
</h3>

```typescript
public proxyId: pulumi.Output<number>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetSSLProxy.ts#L33">property selfLink</a>
</h3>

```typescript
public selfLink: pulumi.Output<string>;
```


The URI of the created resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetSSLProxy.ts#L34">property sslCertificates</a>
</h3>

```typescript
public sslCertificates: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetSSLProxy.ts#L35">property sslPolicy</a>
</h3>

```typescript
public sslPolicy: pulumi.Output<string | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h2 class="pdoc-module-header" id="TargetTCPProxy">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetTCPProxy.ts#L6">class TargetTCPProxy</a>
</h2>
<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetTCPProxy.ts#L33">constructor</a>
</h3>

```typescript
new TargetTCPProxy(name: string, args: TargetTCPProxyArgs, opts?: pulumi.CustomResourceOptions)
```


Create a TargetTCPProxy resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetTCPProxy.ts#L15">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: TargetTCPProxyState): TargetTCPProxy
```


Get an existing TargetTCPProxy resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method getProvider</a>
</h3>

```typescript
getProvider(moduleMember: string): ProviderResource | undefined
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetTCPProxy.ts#L19">property backendService</a>
</h3>

```typescript
public backendService: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetTCPProxy.ts#L20">property creationTimestamp</a>
</h3>

```typescript
public creationTimestamp: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetTCPProxy.ts#L21">property description</a>
</h3>

```typescript
public description: pulumi.Output<string | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetTCPProxy.ts#L22">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetTCPProxy.ts#L27">property project</a>
</h3>

```typescript
public project: pulumi.Output<string>;
```


The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetTCPProxy.ts#L28">property proxyHeader</a>
</h3>

```typescript
public proxyHeader: pulumi.Output<string | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetTCPProxy.ts#L29">property proxyId</a>
</h3>

```typescript
public proxyId: pulumi.Output<number>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetTCPProxy.ts#L33">property selfLink</a>
</h3>

```typescript
public selfLink: pulumi.Output<string>;
```


The URI of the created resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h2 class="pdoc-module-header" id="URLMap">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/uRLMap.ts#L13">class URLMap</a>
</h2>

Manages a URL Map resource within GCE. For more information see
[the official documentation](https://cloud.google.com/compute/docs/load-balancing/http/url-map)
and
[API](https://cloud.google.com/compute/docs/reference/latest/urlMaps).

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/uRLMap.ts#L66">constructor</a>
</h3>

```typescript
new URLMap(name: string, args: URLMapArgs, opts?: pulumi.CustomResourceOptions)
```


Create a URLMap resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/uRLMap.ts#L22">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: URLMapState): URLMap
```


Get an existing URLMap resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method getProvider</a>
</h3>

```typescript
getProvider(moduleMember: string): ProviderResource | undefined
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/uRLMap.ts#L29">property defaultService</a>
</h3>

```typescript
public defaultService: pulumi.Output<string>;
```


The backend service or backend bucket to use if none of the given paths match.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/uRLMap.ts#L33">property description</a>
</h3>

```typescript
public description: pulumi.Output<string | undefined>;
```


An optional description of this test.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/uRLMap.ts#L37">property fingerprint</a>
</h3>

```typescript
public fingerprint: pulumi.Output<string>;
```


The unique fingerprint for this resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/uRLMap.ts#L41">property hostRules</a>
</h3>

```typescript
public hostRules: pulumi.Output<{ ... }[] | undefined>;
```


A list of host rules. Multiple blocks of this type are permitted. Structure is documented below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/uRLMap.ts#L45">property mapId</a>
</h3>

```typescript
public mapId: pulumi.Output<string>;
```


The GCE assigned ID of the resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/uRLMap.ts#L49">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```


The name of the `path_matcher` resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/uRLMap.ts#L53">property pathMatchers</a>
</h3>

```typescript
public pathMatchers: pulumi.Output<{ ... }[] | undefined>;
```


The name of the `path_matcher` to apply this host rule to.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/uRLMap.ts#L58">property project</a>
</h3>

```typescript
public project: pulumi.Output<string>;
```


The ID of the project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/uRLMap.ts#L62">property selfLink</a>
</h3>

```typescript
public selfLink: pulumi.Output<string>;
```


The URI of the created resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/uRLMap.ts#L66">property tests</a>
</h3>

```typescript
public tests: pulumi.Output<{ ... }[] | undefined>;
```


The test to perform.  Multiple blocks of this type are permitted. Structure is documented below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h2 class="pdoc-module-header" id="VPNGateway">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNGateway.ts#L6">class VPNGateway</a>
</h2>
<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNGateway.ts#L32">constructor</a>
</h3>

```typescript
new VPNGateway(name: string, args: VPNGatewayArgs, opts?: pulumi.CustomResourceOptions)
```


Create a VPNGateway resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNGateway.ts#L15">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: VPNGatewayState): VPNGateway
```


Get an existing VPNGateway resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method getProvider</a>
</h3>

```typescript
getProvider(moduleMember: string): ProviderResource | undefined
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNGateway.ts#L19">property creationTimestamp</a>
</h3>

```typescript
public creationTimestamp: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNGateway.ts#L20">property description</a>
</h3>

```typescript
public description: pulumi.Output<string | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNGateway.ts#L21">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNGateway.ts#L22">property network</a>
</h3>

```typescript
public network: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNGateway.ts#L27">property project</a>
</h3>

```typescript
public project: pulumi.Output<string>;
```


The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNGateway.ts#L28">property region</a>
</h3>

```typescript
public region: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNGateway.ts#L32">property selfLink</a>
</h3>

```typescript
public selfLink: pulumi.Output<string>;
```


The URI of the created resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h2 class="pdoc-module-header" id="VPNTunnel">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNTunnel.ts#L6">class VPNTunnel</a>
</h2>
<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNTunnel.ts#L42">constructor</a>
</h3>

```typescript
new VPNTunnel(name: string, args: VPNTunnelArgs, opts?: pulumi.CustomResourceOptions)
```


Create a VPNTunnel resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNTunnel.ts#L15">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: VPNTunnelState): VPNTunnel
```


Get an existing VPNTunnel resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method getProvider</a>
</h3>

```typescript
getProvider(moduleMember: string): ProviderResource | undefined
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNTunnel.ts#L19">property creationTimestamp</a>
</h3>

```typescript
public creationTimestamp: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNTunnel.ts#L20">property description</a>
</h3>

```typescript
public description: pulumi.Output<string | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNTunnel.ts#L21">property detailedStatus</a>
</h3>

```typescript
public detailedStatus: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNTunnel.ts#L22">property ikeVersion</a>
</h3>

```typescript
public ikeVersion: pulumi.Output<number | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNTunnel.ts#L23">property labelFingerprint</a>
</h3>

```typescript
public labelFingerprint: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNTunnel.ts#L24">property labels</a>
</h3>

```typescript
public labels: pulumi.Output<{ ... } | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNTunnel.ts#L25">property localTrafficSelectors</a>
</h3>

```typescript
public localTrafficSelectors: pulumi.Output<string[]>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNTunnel.ts#L26">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNTunnel.ts#L27">property peerIp</a>
</h3>

```typescript
public peerIp: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNTunnel.ts#L32">property project</a>
</h3>

```typescript
public project: pulumi.Output<string>;
```


The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNTunnel.ts#L33">property region</a>
</h3>

```typescript
public region: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNTunnel.ts#L34">property remoteTrafficSelectors</a>
</h3>

```typescript
public remoteTrafficSelectors: pulumi.Output<string[]>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNTunnel.ts#L35">property router</a>
</h3>

```typescript
public router: pulumi.Output<string | undefined>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNTunnel.ts#L39">property selfLink</a>
</h3>

```typescript
public selfLink: pulumi.Output<string>;
```


The URI of the created resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNTunnel.ts#L40">property sharedSecret</a>
</h3>

```typescript
public sharedSecret: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNTunnel.ts#L41">property sharedSecretHash</a>
</h3>

```typescript
public sharedSecretHash: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNTunnel.ts#L42">property targetVpnGateway</a>
</h3>

```typescript
public targetVpnGateway: pulumi.Output<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h2 class="pdoc-module-header" id="getAddress">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getAddress.ts#L10">function getAddress</a>
</h2>

```typescript
getAddress(args: GetAddressArgs, opts?: pulumi.InvokeOptions): Promise<GetAddressResult>
```


Get the IP address from a static address. For more information see
the official [API](https://cloud.google.com/compute/docs/reference/latest/addresses/get) documentation.

<h2 class="pdoc-module-header" id="getBackendService">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getBackendService.ts#L11">function getBackendService</a>
</h2>

```typescript
getBackendService(args: GetBackendServiceArgs, opts?: pulumi.InvokeOptions): Promise<GetBackendServiceResult>
```


Provide acces to a Backend Service's attribute. For more information
see [the official documentation](https://cloud.google.com/compute/docs/load-balancing/http/backend-service)
and the [API](https://cloud.google.com/compute/docs/reference/latest/backendServices).

<h2 class="pdoc-module-header" id="getDefaultServiceAccount">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getDefaultServiceAccount.ts#L9">function getDefaultServiceAccount</a>
</h2>

```typescript
getDefaultServiceAccount(args?: GetDefaultServiceAccountArgs, opts?: pulumi.InvokeOptions): Promise<GetDefaultServiceAccountResult>
```


Use this data source to retrieve default service account for this project

<h2 class="pdoc-module-header" id="getForwardingRule">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getForwardingRule.ts#L9">function getForwardingRule</a>
</h2>

```typescript
getForwardingRule(args: GetForwardingRuleArgs, opts?: pulumi.InvokeOptions): Promise<GetForwardingRuleResult>
```


Get a forwarding rule within GCE from its name.

<h2 class="pdoc-module-header" id="getGlobalAddress">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getGlobalAddress.ts#L10">function getGlobalAddress</a>
</h2>

```typescript
getGlobalAddress(args: GetGlobalAddressArgs, opts?: pulumi.InvokeOptions): Promise<GetGlobalAddressResult>
```


Get the IP address from a static address reserved for a Global Forwarding Rule which are only used for HTTP load balancing. For more information see
the official [API](https://cloud.google.com/compute/docs/reference/latest/globalAddresses) documentation.

<h2 class="pdoc-module-header" id="getImage">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getImage.ts#L10">function getImage</a>
</h2>

```typescript
getImage(args?: GetImageArgs, opts?: pulumi.InvokeOptions): Promise<GetImageResult>
```


Get information about a Google Compute Image. Check that your service account has the `compute.imageUser` role if you want to share [custom images](https://cloud.google.com/compute/docs/images/sharing-images-across-projects) from another project. If you want to use [public images][pubimg], do not forget to specify the dedicated project. For more information see
[the official documentation](https://cloud.google.com/compute/docs/images) and its [API](https://cloud.google.com/compute/docs/reference/latest/images).

<h2 class="pdoc-module-header" id="getInstanceGroup">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getInstanceGroup.ts#L18">function getInstanceGroup</a>
</h2>

```typescript
getInstanceGroup(args?: GetInstanceGroupArgs, opts?: pulumi.InvokeOptions): Promise<GetInstanceGroupResult>
```


Get a Compute Instance Group within GCE.
For more information, see [the official documentation](https://cloud.google.com/compute/docs/instance-groups/#unmanaged_instance_groups)
and [API](https://cloud.google.com/compute/docs/reference/latest/instanceGroups)

```
data "google_compute_instance_group" "all" {
	name = "instance-group-name"
	zone = "us-central1-a"
}
```

<h2 class="pdoc-module-header" id="getLBIPRanges">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getLBIPRanges.ts#L11">function getLBIPRanges</a>
</h2>

```typescript
getLBIPRanges(opts?: pulumi.InvokeOptions): Promise<GetLBIPRangesResult>
```


Use this data source to access IP ranges in your firewall rules.

https://cloud.google.com/compute/docs/load-balancing/health-checks#health_check_source_ips_and_firewall_rules

<h2 class="pdoc-module-header" id="getNetblockIPRanges">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getNetblockIPRanges.ts#L11">function getNetblockIPRanges</a>
</h2>

```typescript
getNetblockIPRanges(opts?: pulumi.InvokeOptions): Promise<GetNetblockIPRangesResult>
```


Use this data source to get the IP ranges from the sender policy framework (SPF) record of \_cloud-netblocks.googleusercontent

https://cloud.google.com/compute/docs/faq#where_can_i_find_product_name_short_ip_ranges

<h2 class="pdoc-module-header" id="getNetwork">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getNetwork.ts#L9">function getNetwork</a>
</h2>

```typescript
getNetwork(args: GetNetworkArgs, opts?: pulumi.InvokeOptions): Promise<GetNetworkResult>
```


Get a network within GCE from its name.

<h2 class="pdoc-module-header" id="getRegionInstanceGroup">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getRegionInstanceGroup.ts#L35">function getRegionInstanceGroup</a>
</h2>

```typescript
getRegionInstanceGroup(args?: GetRegionInstanceGroupArgs, opts?: pulumi.InvokeOptions): Promise<GetRegionInstanceGroupResult>
```


Get a Compute Region Instance Group within GCE.
For more information, see [the official documentation](https://cloud.google.com/compute/docs/instance-groups/distributing-instances-with-regional-instance-groups) and [API](https://cloud.google.com/compute/docs/reference/latest/regionInstanceGroups).

```
data "google_compute_region_instance_group" "group" {
	name = "instance-group-name"
}
```

The most common use of this datasource will be to fetch information about the instances inside regional managed instance groups, for instance:

```
resource "google_compute_region_instance_group_manager" "foo" {
	name = "some_name"
    ...
	base_instance_name = "foo"
    ...
	instance_template = "${google_compute_instance_template.foo.self_link}"
	target_pools = ["${google_compute_target_pool.foo.self_link}"]
    ...
}

data "google_compute_region_instance_group" "data_source" {
	self_link = "${google_compute_region_instance_group_manager.foo.instance_group}"
}

```

<h2 class="pdoc-module-header" id="getRegions">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getRegions.ts#L22">function getRegions</a>
</h2>

```typescript
getRegions(args?: GetRegionsArgs, opts?: pulumi.InvokeOptions): Promise<GetRegionsResult>
```


Provides access to available Google Compute regions for a given project.
See more about [regions and regions](https://cloud.google.com/compute/docs/regions-zones/) in the upstream docs.

```
data "google_compute_regions" "available" {}

resource "google_compute_subnetwork" "cluster" {
  count = "${length(data.google_compute_regions.available.names)}"
  name          = "my-network"
  ip_cidr_range = "10.36.${count.index}.0/24"
  network       = "my-network"
  region        = "${data.google_compute_regions.available.names[count.index]}"
}
```

<h2 class="pdoc-module-header" id="getSSLPolicy">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getSSLPolicy.ts#L10">function getSSLPolicy</a>
</h2>

```typescript
getSSLPolicy(args: GetSSLPolicyArgs, opts?: pulumi.InvokeOptions): Promise<GetSSLPolicyResult>
```


Gets an SSL Policy within GCE from its name, for use with Target HTTPS and Target SSL Proxies.
    For more information see [the official documentation](https://cloud.google.com/compute/docs/load-balancing/ssl-policies).

<h2 class="pdoc-module-header" id="getSubnetwork">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getSubnetwork.ts#L9">function getSubnetwork</a>
</h2>

```typescript
getSubnetwork(args: GetSubnetworkArgs, opts?: pulumi.InvokeOptions): Promise<GetSubnetworkResult>
```


Get a subnetwork within GCE from its name and region.

<h2 class="pdoc-module-header" id="getVPNGateway">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getVPNGateway.ts#L9">function getVPNGateway</a>
</h2>

```typescript
getVPNGateway(args: GetVPNGatewayArgs, opts?: pulumi.InvokeOptions): Promise<GetVPNGatewayResult>
```


Get a VPN gateway within GCE from its name.

<h2 class="pdoc-module-header" id="getZones">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getZones.ts#L24">function getZones</a>
</h2>

```typescript
getZones(args?: GetZonesArgs, opts?: pulumi.InvokeOptions): Promise<GetZonesResult>
```


Provides access to available Google Compute zones in a region for a given project.
See more about [regions and zones](https://cloud.google.com/compute/docs/regions-zones/regions-zones) in the upstream docs.

```
data "google_compute_zones" "available" {}

resource "google_compute_instance_group_manager" "foo" {
  count = "${length(data.google_compute_zones.available.names)}"

  name               = "terraform-test-${count.index}"
  instance_template  = "${google_compute_instance_template.foobar.self_link}"
  base_instance_name = "foobar-${count.index}"
  zone               = "${data.google_compute_zones.available.names[count.index]}"
  target_size        = 1
}
```

<h2 class="pdoc-module-header" id="AddressArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/address.ts#L106">interface AddressArgs</a>
</h2>

The set of arguments for constructing a Address resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/address.ts#L107">property address</a>
</h3>

```typescript
address?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/address.ts#L108">property addressType</a>
</h3>

```typescript
addressType?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/address.ts#L109">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/address.ts#L110">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/address.ts#L111">property networkTier</a>
</h3>

```typescript
networkTier?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/address.ts#L116">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/address.ts#L117">property region</a>
</h3>

```typescript
region?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/address.ts#L118">property subnetwork</a>
</h3>

```typescript
subnetwork?: pulumi.Input<string>;
```

<h2 class="pdoc-module-header" id="AddressState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/address.ts#L82">interface AddressState</a>
</h2>

Input properties used for looking up and filtering Address resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/address.ts#L83">property address</a>
</h3>

```typescript
address?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/address.ts#L84">property addressType</a>
</h3>

```typescript
addressType?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/address.ts#L85">property creationTimestamp</a>
</h3>

```typescript
creationTimestamp?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/address.ts#L86">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/address.ts#L87">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/address.ts#L88">property networkTier</a>
</h3>

```typescript
networkTier?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/address.ts#L93">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/address.ts#L94">property region</a>
</h3>

```typescript
region?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/address.ts#L98">property selfLink</a>
</h3>

```typescript
selfLink?: pulumi.Input<string>;
```


The URI of the created resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/address.ts#L99">property subnetwork</a>
</h3>

```typescript
subnetwork?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/address.ts#L100">property users</a>
</h3>

```typescript
users?: pulumi.Input<pulumi.Input<string>[]>;
```

<h2 class="pdoc-module-header" id="AutoscalarArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/autoscalar.ts#L100">interface AutoscalarArgs</a>
</h2>

The set of arguments for constructing a Autoscalar resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/autoscalar.ts#L101">property autoscalingPolicy</a>
</h3>

```typescript
autoscalingPolicy: pulumi.Input<{ ... }>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/autoscalar.ts#L102">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/autoscalar.ts#L103">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/autoscalar.ts#L108">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/autoscalar.ts#L109">property target</a>
</h3>

```typescript
target: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/autoscalar.ts#L110">property zone</a>
</h3>

```typescript
zone?: pulumi.Input<string>;
```

<h2 class="pdoc-module-header" id="AutoscalarState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/autoscalar.ts#L79">interface AutoscalarState</a>
</h2>

Input properties used for looking up and filtering Autoscalar resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/autoscalar.ts#L80">property autoscalingPolicy</a>
</h3>

```typescript
autoscalingPolicy?: pulumi.Input<{ ... }>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/autoscalar.ts#L81">property creationTimestamp</a>
</h3>

```typescript
creationTimestamp?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/autoscalar.ts#L82">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/autoscalar.ts#L83">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/autoscalar.ts#L88">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/autoscalar.ts#L92">property selfLink</a>
</h3>

```typescript
selfLink?: pulumi.Input<string>;
```


The URI of the created resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/autoscalar.ts#L93">property target</a>
</h3>

```typescript
target?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/autoscalar.ts#L94">property zone</a>
</h3>

```typescript
zone?: pulumi.Input<string>;
```

<h2 class="pdoc-module-header" id="BackendBucketArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendBucket.ts#L93">interface BackendBucketArgs</a>
</h2>

The set of arguments for constructing a BackendBucket resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendBucket.ts#L94">property bucketName</a>
</h3>

```typescript
bucketName: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendBucket.ts#L95">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendBucket.ts#L96">property enableCdn</a>
</h3>

```typescript
enableCdn?: pulumi.Input<boolean>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendBucket.ts#L97">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendBucket.ts#L102">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.

<h2 class="pdoc-module-header" id="BackendBucketState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendBucket.ts#L73">interface BackendBucketState</a>
</h2>

Input properties used for looking up and filtering BackendBucket resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendBucket.ts#L74">property bucketName</a>
</h3>

```typescript
bucketName?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendBucket.ts#L75">property creationTimestamp</a>
</h3>

```typescript
creationTimestamp?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendBucket.ts#L76">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendBucket.ts#L77">property enableCdn</a>
</h3>

```typescript
enableCdn?: pulumi.Input<boolean>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendBucket.ts#L78">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendBucket.ts#L83">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendBucket.ts#L87">property selfLink</a>
</h3>

```typescript
selfLink?: pulumi.Input<string>;
```


The URI of the created resource.

<h2 class="pdoc-module-header" id="BackendServiceArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendService.ts#L250">interface BackendServiceArgs</a>
</h2>

The set of arguments for constructing a BackendService resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendService.ts#L254">property backends</a>
</h3>

```typescript
backends?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```


The list of backends that serve this BackendService. Structure is documented below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendService.ts#L258">property cdnPolicy</a>
</h3>

```typescript
cdnPolicy?: pulumi.Input<{ ... }>;
```


Cloud CDN configuration for this BackendService. Structure is documented below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendService.ts#L263">property connectionDrainingTimeoutSec</a>
</h3>

```typescript
connectionDrainingTimeoutSec?: pulumi.Input<number>;
```


Time for which instance will be drained (not accept new connections,
but still work to finish started ones). Defaults to `300`.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendService.ts#L268">property customRequestHeaders</a>
</h3>

```typescript
customRequestHeaders?: pulumi.Input<pulumi.Input<string>[]>;
```


) Headers that the
HTTP/S load balancer should add to proxied requests. See [guide](https://cloud.google.com/compute/docs/load-balancing/http/backend-service#user-defined-request-headers) for details.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendService.ts#L272">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```


Textual description for the backend.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendService.ts#L276">property enableCdn</a>
</h3>

```typescript
enableCdn?: pulumi.Input<boolean>;
```


Whether or not to enable the Cloud CDN on the backend service.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendService.ts#L282">property healthChecks</a>
</h3>

```typescript
healthChecks: pulumi.Input<string>;
```


Specifies a list of HTTP/HTTPS health checks
for checking the health of the backend service. Currently at most one health
check can be specified, and a health check is required.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendService.ts#L286">property iap</a>
</h3>

```typescript
iap?: pulumi.Input<{ ... }>;
```


Specification for the Identity-Aware proxy. Disabled if not specified. Structure is documented below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendService.ts#L290">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


The name of the backend service.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendService.ts#L295">property portName</a>
</h3>

```typescript
portName?: pulumi.Input<string>;
```


The name of a service that has been added to an
instance group in this backend. See [related docs](https://cloud.google.com/compute/docs/instance-groups/#specifying_service_endpoints) for details. Defaults to http.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendService.ts#L300">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendService.ts#L305">property protocol</a>
</h3>

```typescript
protocol?: pulumi.Input<string>;
```


The protocol for incoming requests. Defaults to
`HTTP`.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendService.ts#L310">property securityPolicy</a>
</h3>

```typescript
securityPolicy?: pulumi.Input<string>;
```


) Name or URI of a
[security policy](https://cloud.google.com/armor/docs/security-policy-concepts) to add to the backend service.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendService.ts#L316">property sessionAffinity</a>
</h3>

```typescript
sessionAffinity?: pulumi.Input<string>;
```


How to distribute load. Options are `NONE` (no
affinity), `CLIENT_IP` (hash of the source/dest addresses / ports), and
`GENERATED_COOKIE` (distribute load using a generated session cookie).

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendService.ts#L321">property timeoutSec</a>
</h3>

```typescript
timeoutSec?: pulumi.Input<number>;
```


The number of secs to wait for a backend to respond
to a request before considering the request failed. Defaults to `30`.

<h2 class="pdoc-module-header" id="BackendServiceState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendService.ts#L165">interface BackendServiceState</a>
</h2>

Input properties used for looking up and filtering BackendService resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendService.ts#L169">property backends</a>
</h3>

```typescript
backends?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```


The list of backends that serve this BackendService. Structure is documented below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendService.ts#L173">property cdnPolicy</a>
</h3>

```typescript
cdnPolicy?: pulumi.Input<{ ... }>;
```


Cloud CDN configuration for this BackendService. Structure is documented below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendService.ts#L178">property connectionDrainingTimeoutSec</a>
</h3>

```typescript
connectionDrainingTimeoutSec?: pulumi.Input<number>;
```


Time for which instance will be drained (not accept new connections,
but still work to finish started ones). Defaults to `300`.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendService.ts#L183">property customRequestHeaders</a>
</h3>

```typescript
customRequestHeaders?: pulumi.Input<pulumi.Input<string>[]>;
```


) Headers that the
HTTP/S load balancer should add to proxied requests. See [guide](https://cloud.google.com/compute/docs/load-balancing/http/backend-service#user-defined-request-headers) for details.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendService.ts#L187">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```


Textual description for the backend.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendService.ts#L191">property enableCdn</a>
</h3>

```typescript
enableCdn?: pulumi.Input<boolean>;
```


Whether or not to enable the Cloud CDN on the backend service.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendService.ts#L195">property fingerprint</a>
</h3>

```typescript
fingerprint?: pulumi.Input<string>;
```


The fingerprint of the backend service.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendService.ts#L201">property healthChecks</a>
</h3>

```typescript
healthChecks?: pulumi.Input<string>;
```


Specifies a list of HTTP/HTTPS health checks
for checking the health of the backend service. Currently at most one health
check can be specified, and a health check is required.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendService.ts#L205">property iap</a>
</h3>

```typescript
iap?: pulumi.Input<{ ... }>;
```


Specification for the Identity-Aware proxy. Disabled if not specified. Structure is documented below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendService.ts#L209">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


The name of the backend service.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendService.ts#L214">property portName</a>
</h3>

```typescript
portName?: pulumi.Input<string>;
```


The name of a service that has been added to an
instance group in this backend. See [related docs](https://cloud.google.com/compute/docs/instance-groups/#specifying_service_endpoints) for details. Defaults to http.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendService.ts#L219">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendService.ts#L224">property protocol</a>
</h3>

```typescript
protocol?: pulumi.Input<string>;
```


The protocol for incoming requests. Defaults to
`HTTP`.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendService.ts#L229">property securityPolicy</a>
</h3>

```typescript
securityPolicy?: pulumi.Input<string>;
```


) Name or URI of a
[security policy](https://cloud.google.com/armor/docs/security-policy-concepts) to add to the backend service.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendService.ts#L233">property selfLink</a>
</h3>

```typescript
selfLink?: pulumi.Input<string>;
```


The URI of the created resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendService.ts#L239">property sessionAffinity</a>
</h3>

```typescript
sessionAffinity?: pulumi.Input<string>;
```


How to distribute load. Options are `NONE` (no
affinity), `CLIENT_IP` (hash of the source/dest addresses / ports), and
`GENERATED_COOKIE` (distribute load using a generated session cookie).

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/backendService.ts#L244">property timeoutSec</a>
</h3>

```typescript
timeoutSec?: pulumi.Input<number>;
```


The number of secs to wait for a backend to respond
to a request before considering the request failed. Defaults to `30`.

<h2 class="pdoc-module-header" id="DiskArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/disk.ts#L150">interface DiskArgs</a>
</h2>

The set of arguments for constructing a Disk resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/disk.ts#L151">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/disk.ts#L152">property diskEncryptionKey</a>
</h3>

```typescript
diskEncryptionKey?: pulumi.Input<{ ... }>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/disk.ts#L153">property diskEncryptionKeyRaw</a>
</h3>

```typescript
diskEncryptionKeyRaw?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/disk.ts#L154">property image</a>
</h3>

```typescript
image?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/disk.ts#L155">property labels</a>
</h3>

```typescript
labels?: pulumi.Input<{ ... }>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/disk.ts#L156">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/disk.ts#L161">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/disk.ts#L162">property size</a>
</h3>

```typescript
size?: pulumi.Input<number>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/disk.ts#L163">property snapshot</a>
</h3>

```typescript
snapshot?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/disk.ts#L164">property sourceImageEncryptionKey</a>
</h3>

```typescript
sourceImageEncryptionKey?: pulumi.Input<{ ... }>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/disk.ts#L165">property sourceSnapshotEncryptionKey</a>
</h3>

```typescript
sourceSnapshotEncryptionKey?: pulumi.Input<{ ... }>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/disk.ts#L166">property type</a>
</h3>

```typescript
type?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/disk.ts#L167">property zone</a>
</h3>

```typescript
zone?: pulumi.Input<string>;
```

<h2 class="pdoc-module-header" id="DiskState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/disk.ts#L115">interface DiskState</a>
</h2>

Input properties used for looking up and filtering Disk resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/disk.ts#L116">property creationTimestamp</a>
</h3>

```typescript
creationTimestamp?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/disk.ts#L117">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/disk.ts#L118">property diskEncryptionKey</a>
</h3>

```typescript
diskEncryptionKey?: pulumi.Input<{ ... }>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/disk.ts#L119">property diskEncryptionKeyRaw</a>
</h3>

```typescript
diskEncryptionKeyRaw?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/disk.ts#L120">property diskEncryptionKeySha256</a>
</h3>

```typescript
diskEncryptionKeySha256?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/disk.ts#L121">property image</a>
</h3>

```typescript
image?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/disk.ts#L122">property labelFingerprint</a>
</h3>

```typescript
labelFingerprint?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/disk.ts#L123">property labels</a>
</h3>

```typescript
labels?: pulumi.Input<{ ... }>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/disk.ts#L124">property lastAttachTimestamp</a>
</h3>

```typescript
lastAttachTimestamp?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/disk.ts#L125">property lastDetachTimestamp</a>
</h3>

```typescript
lastDetachTimestamp?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/disk.ts#L126">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/disk.ts#L131">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/disk.ts#L135">property selfLink</a>
</h3>

```typescript
selfLink?: pulumi.Input<string>;
```


The URI of the created resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/disk.ts#L136">property size</a>
</h3>

```typescript
size?: pulumi.Input<number>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/disk.ts#L137">property snapshot</a>
</h3>

```typescript
snapshot?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/disk.ts#L138">property sourceImageEncryptionKey</a>
</h3>

```typescript
sourceImageEncryptionKey?: pulumi.Input<{ ... }>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/disk.ts#L139">property sourceImageId</a>
</h3>

```typescript
sourceImageId?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/disk.ts#L140">property sourceSnapshotEncryptionKey</a>
</h3>

```typescript
sourceSnapshotEncryptionKey?: pulumi.Input<{ ... }>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/disk.ts#L141">property sourceSnapshotId</a>
</h3>

```typescript
sourceSnapshotId?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/disk.ts#L142">property type</a>
</h3>

```typescript
type?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/disk.ts#L143">property users</a>
</h3>

```typescript
users?: pulumi.Input<pulumi.Input<string>[]>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/disk.ts#L144">property zone</a>
</h3>

```typescript
zone?: pulumi.Input<string>;
```

<h2 class="pdoc-module-header" id="FirewallArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/firewall.ts#L261">interface FirewallArgs</a>
</h2>

The set of arguments for constructing a Firewall resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/firewall.ts#L266">property allows</a>
</h3>

```typescript
allows?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```


Can be specified multiple times for each allow
rule. Each allow block supports fields documented below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/firewall.ts#L272">property denies</a>
</h3>

```typescript
denies?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```


Can be specified multiple times for each deny
rule. Each deny block supports fields documented below. Can be specified
instead of allow.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/firewall.ts#L276">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```


Textual description field.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/firewall.ts#L281">property destinationRanges</a>
</h3>

```typescript
destinationRanges?: pulumi.Input<pulumi.Input<string>[]>;
```


A list of destination CIDR ranges that this
firewall applies to. Can't be used for `INGRESS`.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/firewall.ts#L286">property direction</a>
</h3>

```typescript
direction?: pulumi.Input<string>;
```


Direction of traffic to which this firewall applies;
One of `INGRESS` or `EGRESS`. Defaults to `INGRESS`.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/firewall.ts#L291">property disabled</a>
</h3>

```typescript
disabled?: pulumi.Input<boolean>;
```


Denotes whether the firewall rule is disabled, i.e not applied to the network it is associated with.
When set to true, the firewall rule is not enforced and the network behaves as if it did not exist.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/firewall.ts#L296">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


A unique name for the resource, required by GCE.
Changing this forces a new resource to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/firewall.ts#L300">property network</a>
</h3>

```typescript
network: pulumi.Input<string>;
```


The name or self_link of the network to attach this firewall to.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/firewall.ts#L306">property priority</a>
</h3>

```typescript
priority?: pulumi.Input<number>;
```


The priority for this firewall. Ranges from 0-65535, inclusive. Defaults to 1000. Firewall
resources with lower priority values have higher precedence (e.g. a firewall resource with a priority value of 0
takes effect over all other firewall rules with a non-zero priority).

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/firewall.ts#L311">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/firewall.ts#L316">property sourceRanges</a>
</h3>

```typescript
sourceRanges?: pulumi.Input<pulumi.Input<string>[]>;
```


A list of source CIDR ranges that this
firewall applies to. Can't be used for `EGRESS`.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/firewall.ts#L327">property sourceServiceAccounts</a>
</h3>

```typescript
sourceServiceAccounts?: pulumi.Input<string>;
```


A list of service accounts such that
the firewall will apply only to traffic originating from an instance with a service account in this list.  Note that as of May 2018,
this list can contain only one item, due to a change in the way that these firewall rules are handled.  Source service accounts
cannot be used to control traffic to an instance's external IP address because service accounts are associated with an instance, not
an IP address. `source_ranges` can be set at the same time as `source_service_accounts`. If both are set, the firewall will apply to
traffic that has source IP address within `source_ranges` OR the source IP belongs to an instance with service account listed in
`source_service_accounts`. The connection does not need to match both properties for the firewall to apply. `source_service_accounts`
cannot be used at the same time as `source_tags` or `target_tags`.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/firewall.ts#L331">property sourceTags</a>
</h3>

```typescript
sourceTags?: pulumi.Input<pulumi.Input<string>[]>;
```


A list of source tags for this firewall. Can't be used for `EGRESS`.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/firewall.ts#L339">property targetServiceAccounts</a>
</h3>

```typescript
targetServiceAccounts?: pulumi.Input<string>;
```


A list of service accounts indicating
sets of instances located in the network that may make network connections as specified in `allow`. `target_service_accounts` cannot
be used at the same time as `source_tags` or `target_tags`. If neither `target_service_accounts` nor `target_tags` are specified, the
firewall rule applies to all instances on the specified network.  Note that as of May 2018, this list can contain only one item, due
to a change in the way that these firewall rules are handled.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/firewall.ts#L343">property targetTags</a>
</h3>

```typescript
targetTags?: pulumi.Input<pulumi.Input<string>[]>;
```


A list of target tags for this firewall.

<h2 class="pdoc-module-header" id="FirewallState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/firewall.ts#L169">interface FirewallState</a>
</h2>

Input properties used for looking up and filtering Firewall resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/firewall.ts#L174">property allows</a>
</h3>

```typescript
allows?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```


Can be specified multiple times for each allow
rule. Each allow block supports fields documented below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/firewall.ts#L180">property denies</a>
</h3>

```typescript
denies?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```


Can be specified multiple times for each deny
rule. Each deny block supports fields documented below. Can be specified
instead of allow.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/firewall.ts#L184">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```


Textual description field.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/firewall.ts#L189">property destinationRanges</a>
</h3>

```typescript
destinationRanges?: pulumi.Input<pulumi.Input<string>[]>;
```


A list of destination CIDR ranges that this
firewall applies to. Can't be used for `INGRESS`.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/firewall.ts#L194">property direction</a>
</h3>

```typescript
direction?: pulumi.Input<string>;
```


Direction of traffic to which this firewall applies;
One of `INGRESS` or `EGRESS`. Defaults to `INGRESS`.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/firewall.ts#L199">property disabled</a>
</h3>

```typescript
disabled?: pulumi.Input<boolean>;
```


Denotes whether the firewall rule is disabled, i.e not applied to the network it is associated with.
When set to true, the firewall rule is not enforced and the network behaves as if it did not exist.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/firewall.ts#L204">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


A unique name for the resource, required by GCE.
Changing this forces a new resource to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/firewall.ts#L208">property network</a>
</h3>

```typescript
network?: pulumi.Input<string>;
```


The name or self_link of the network to attach this firewall to.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/firewall.ts#L214">property priority</a>
</h3>

```typescript
priority?: pulumi.Input<number>;
```


The priority for this firewall. Ranges from 0-65535, inclusive. Defaults to 1000. Firewall
resources with lower priority values have higher precedence (e.g. a firewall resource with a priority value of 0
takes effect over all other firewall rules with a non-zero priority).

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/firewall.ts#L219">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/firewall.ts#L223">property selfLink</a>
</h3>

```typescript
selfLink?: pulumi.Input<string>;
```


The URI of the created resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/firewall.ts#L228">property sourceRanges</a>
</h3>

```typescript
sourceRanges?: pulumi.Input<pulumi.Input<string>[]>;
```


A list of source CIDR ranges that this
firewall applies to. Can't be used for `EGRESS`.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/firewall.ts#L239">property sourceServiceAccounts</a>
</h3>

```typescript
sourceServiceAccounts?: pulumi.Input<string>;
```


A list of service accounts such that
the firewall will apply only to traffic originating from an instance with a service account in this list.  Note that as of May 2018,
this list can contain only one item, due to a change in the way that these firewall rules are handled.  Source service accounts
cannot be used to control traffic to an instance's external IP address because service accounts are associated with an instance, not
an IP address. `source_ranges` can be set at the same time as `source_service_accounts`. If both are set, the firewall will apply to
traffic that has source IP address within `source_ranges` OR the source IP belongs to an instance with service account listed in
`source_service_accounts`. The connection does not need to match both properties for the firewall to apply. `source_service_accounts`
cannot be used at the same time as `source_tags` or `target_tags`.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/firewall.ts#L243">property sourceTags</a>
</h3>

```typescript
sourceTags?: pulumi.Input<pulumi.Input<string>[]>;
```


A list of source tags for this firewall. Can't be used for `EGRESS`.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/firewall.ts#L251">property targetServiceAccounts</a>
</h3>

```typescript
targetServiceAccounts?: pulumi.Input<string>;
```


A list of service accounts indicating
sets of instances located in the network that may make network connections as specified in `allow`. `target_service_accounts` cannot
be used at the same time as `source_tags` or `target_tags`. If neither `target_service_accounts` nor `target_tags` are specified, the
firewall rule applies to all instances on the specified network.  Note that as of May 2018, this list can contain only one item, due
to a change in the way that these firewall rules are handled.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/firewall.ts#L255">property targetTags</a>
</h3>

```typescript
targetTags?: pulumi.Input<pulumi.Input<string>[]>;
```


A list of target tags for this firewall.

<h2 class="pdoc-module-header" id="ForwardingRuleArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/forwardingRule.ts#L146">interface ForwardingRuleArgs</a>
</h2>

The set of arguments for constructing a ForwardingRule resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/forwardingRule.ts#L147">property backendService</a>
</h3>

```typescript
backendService?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/forwardingRule.ts#L148">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/forwardingRule.ts#L149">property ipAddress</a>
</h3>

```typescript
ipAddress?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/forwardingRule.ts#L150">property ipProtocol</a>
</h3>

```typescript
ipProtocol?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/forwardingRule.ts#L151">property ipVersion</a>
</h3>

```typescript
ipVersion?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/forwardingRule.ts#L152">property labels</a>
</h3>

```typescript
labels?: pulumi.Input<{ ... }>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/forwardingRule.ts#L153">property loadBalancingScheme</a>
</h3>

```typescript
loadBalancingScheme?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/forwardingRule.ts#L154">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/forwardingRule.ts#L155">property network</a>
</h3>

```typescript
network?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/forwardingRule.ts#L156">property networkTier</a>
</h3>

```typescript
networkTier?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/forwardingRule.ts#L157">property portRange</a>
</h3>

```typescript
portRange?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/forwardingRule.ts#L158">property ports</a>
</h3>

```typescript
ports?: pulumi.Input<pulumi.Input<string>[]>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/forwardingRule.ts#L163">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/forwardingRule.ts#L164">property region</a>
</h3>

```typescript
region?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/forwardingRule.ts#L165">property serviceLabel</a>
</h3>

```typescript
serviceLabel?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/forwardingRule.ts#L166">property subnetwork</a>
</h3>

```typescript
subnetwork?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/forwardingRule.ts#L167">property target</a>
</h3>

```typescript
target?: pulumi.Input<string>;
```

<h2 class="pdoc-module-header" id="ForwardingRuleState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/forwardingRule.ts#L112">interface ForwardingRuleState</a>
</h2>

Input properties used for looking up and filtering ForwardingRule resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/forwardingRule.ts#L113">property backendService</a>
</h3>

```typescript
backendService?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/forwardingRule.ts#L114">property creationTimestamp</a>
</h3>

```typescript
creationTimestamp?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/forwardingRule.ts#L115">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/forwardingRule.ts#L116">property ipAddress</a>
</h3>

```typescript
ipAddress?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/forwardingRule.ts#L117">property ipProtocol</a>
</h3>

```typescript
ipProtocol?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/forwardingRule.ts#L118">property ipVersion</a>
</h3>

```typescript
ipVersion?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/forwardingRule.ts#L119">property labelFingerprint</a>
</h3>

```typescript
labelFingerprint?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/forwardingRule.ts#L120">property labels</a>
</h3>

```typescript
labels?: pulumi.Input<{ ... }>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/forwardingRule.ts#L121">property loadBalancingScheme</a>
</h3>

```typescript
loadBalancingScheme?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/forwardingRule.ts#L122">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/forwardingRule.ts#L123">property network</a>
</h3>

```typescript
network?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/forwardingRule.ts#L124">property networkTier</a>
</h3>

```typescript
networkTier?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/forwardingRule.ts#L125">property portRange</a>
</h3>

```typescript
portRange?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/forwardingRule.ts#L126">property ports</a>
</h3>

```typescript
ports?: pulumi.Input<pulumi.Input<string>[]>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/forwardingRule.ts#L131">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/forwardingRule.ts#L132">property region</a>
</h3>

```typescript
region?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/forwardingRule.ts#L136">property selfLink</a>
</h3>

```typescript
selfLink?: pulumi.Input<string>;
```


The URI of the created resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/forwardingRule.ts#L137">property serviceLabel</a>
</h3>

```typescript
serviceLabel?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/forwardingRule.ts#L138">property serviceName</a>
</h3>

```typescript
serviceName?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/forwardingRule.ts#L139">property subnetwork</a>
</h3>

```typescript
subnetwork?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/forwardingRule.ts#L140">property target</a>
</h3>

```typescript
target?: pulumi.Input<string>;
```

<h2 class="pdoc-module-header" id="GetAddressArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getAddress.ts#L21">interface GetAddressArgs</a>
</h2>

A collection of arguments for invoking getAddress.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getAddress.ts#L25">property name</a>
</h3>

```typescript
name: string;
```


A unique name for the resource, required by GCE.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getAddress.ts#L30">property project</a>
</h3>

```typescript
project?: string;
```


The project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getAddress.ts#L35">property region</a>
</h3>

```typescript
region?: string;
```


The Region in which the created address reside.
If it is not provided, the provider region is used.

<h2 class="pdoc-module-header" id="GetAddressResult">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getAddress.ts#L41">interface GetAddressResult</a>
</h2>

A collection of values returned by getAddress.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getAddress.ts#L45">property address</a>
</h3>

```typescript
address: string;
```


The IP of the created resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getAddress.ts#L59">property id</a>
</h3>

```typescript
id: string;
```


id is the provider-assigned unique ID for this managed resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getAddress.ts#L46">property project</a>
</h3>

```typescript
project: string;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getAddress.ts#L47">property region</a>
</h3>

```typescript
region: string;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getAddress.ts#L51">property selfLink</a>
</h3>

```typescript
selfLink: string;
```


The URI of the created resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getAddress.ts#L55">property status</a>
</h3>

```typescript
status: string;
```


Indicates if the address is used. Possible values are: RESERVED or IN_USE.

<h2 class="pdoc-module-header" id="GetBackendServiceArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getBackendService.ts#L21">interface GetBackendServiceArgs</a>
</h2>

A collection of arguments for invoking getBackendService.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getBackendService.ts#L25">property name</a>
</h3>

```typescript
name: string;
```


The name of the Backend Service.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getBackendService.ts#L29">property project</a>
</h3>

```typescript
project?: string;
```


The project in which the resource belongs. If it is not provided, the provider project is used.

<h2 class="pdoc-module-header" id="GetBackendServiceResult">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getBackendService.ts#L35">interface GetBackendServiceResult</a>
</h2>

A collection of values returned by getBackendService.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getBackendService.ts#L39">property backends</a>
</h3>

```typescript
backends: { ... }[];
```


The list of backends that serve this Backend Service.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getBackendService.ts#L40">property cdnPolicies</a>
</h3>

```typescript
cdnPolicies: { ... }[];
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getBackendService.ts#L44">property connectionDrainingTimeoutSec</a>
</h3>

```typescript
connectionDrainingTimeoutSec: number;
```


Time for which instance will be drained (not accept new connections, but still work to finish started ones).

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getBackendService.ts#L45">property customRequestHeaders</a>
</h3>

```typescript
customRequestHeaders: string[];
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getBackendService.ts#L49">property description</a>
</h3>

```typescript
description: string;
```


Textual description for the Backend Service.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getBackendService.ts#L53">property enableCdn</a>
</h3>

```typescript
enableCdn: boolean;
```


Whether or not Cloud CDN is enabled on the Backend Service.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getBackendService.ts#L57">property fingerprint</a>
</h3>

```typescript
fingerprint: string;
```


The fingerprint of the Backend Service.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getBackendService.ts#L61">property healthChecks</a>
</h3>

```typescript
healthChecks: string[];
```


The list of HTTP/HTTPS health checks used by the Backend Service.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getBackendService.ts#L62">property iaps</a>
</h3>

```typescript
iaps: { ... }[];
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getBackendService.ts#L88">property id</a>
</h3>

```typescript
id: string;
```


id is the provider-assigned unique ID for this managed resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getBackendService.ts#L66">property portName</a>
</h3>

```typescript
portName: string;
```


The name of a service that has been added to an instance group in this backend.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getBackendService.ts#L70">property protocol</a>
</h3>

```typescript
protocol: string;
```


The protocol for incoming requests.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getBackendService.ts#L71">property region</a>
</h3>

```typescript
region: string;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getBackendService.ts#L72">property securityPolicy</a>
</h3>

```typescript
securityPolicy: string;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getBackendService.ts#L76">property selfLink</a>
</h3>

```typescript
selfLink: string;
```


The URI of the Backend Service.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getBackendService.ts#L80">property sessionAffinity</a>
</h3>

```typescript
sessionAffinity: string;
```


The Backend Service session stickyness configuration.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getBackendService.ts#L84">property timeoutSec</a>
</h3>

```typescript
timeoutSec: number;
```


The number of seconds to wait for a backend to respond to a request before considering the request failed.

<h2 class="pdoc-module-header" id="GetDefaultServiceAccountArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getDefaultServiceAccount.ts#L19">interface GetDefaultServiceAccountArgs</a>
</h2>

A collection of arguments for invoking getDefaultServiceAccount.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getDefaultServiceAccount.ts#L23">property project</a>
</h3>

```typescript
project?: string;
```


The project ID. If it is not provided, the provider project is used.

<h2 class="pdoc-module-header" id="GetDefaultServiceAccountResult">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getDefaultServiceAccount.ts#L29">interface GetDefaultServiceAccountResult</a>
</h2>

A collection of values returned by getDefaultServiceAccount.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getDefaultServiceAccount.ts#L33">property email</a>
</h3>

```typescript
email: string;
```


Email address of the default service account used by VMs running in this project

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getDefaultServiceAccount.ts#L38">property id</a>
</h3>

```typescript
id: string;
```


id is the provider-assigned unique ID for this managed resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getDefaultServiceAccount.ts#L34">property project</a>
</h3>

```typescript
project: string;
```

<h2 class="pdoc-module-header" id="GetForwardingRuleArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getForwardingRule.ts#L20">interface GetForwardingRuleArgs</a>
</h2>

A collection of arguments for invoking getForwardingRule.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getForwardingRule.ts#L24">property name</a>
</h3>

```typescript
name: string;
```


The name of the forwarding rule.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getForwardingRule.ts#L29">property project</a>
</h3>

```typescript
project?: string;
```


The project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getForwardingRule.ts#L34">property region</a>
</h3>

```typescript
region?: string;
```


The region in which the resource belongs. If it
is not provided, the project region is used.

<h2 class="pdoc-module-header" id="GetForwardingRuleResult">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getForwardingRule.ts#L40">interface GetForwardingRuleResult</a>
</h2>

A collection of values returned by getForwardingRule.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getForwardingRule.ts#L44">property backendService</a>
</h3>

```typescript
backendService: string;
```


Backend service, if this forwarding rule has one.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getForwardingRule.ts#L48">property description</a>
</h3>

```typescript
description: string;
```


Description of this forwarding rule.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getForwardingRule.ts#L93">property id</a>
</h3>

```typescript
id: string;
```


id is the provider-assigned unique ID for this managed resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getForwardingRule.ts#L52">property ipAddress</a>
</h3>

```typescript
ipAddress: string;
```


IP address of this forwarding rule.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getForwardingRule.ts#L56">property ipProtocol</a>
</h3>

```typescript
ipProtocol: string;
```


IP protocol of this forwarding rule.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getForwardingRule.ts#L60">property loadBalancingScheme</a>
</h3>

```typescript
loadBalancingScheme: string;
```


Type of load balancing of this forwarding rule.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getForwardingRule.ts#L64">property network</a>
</h3>

```typescript
network: string;
```


Network of this forwarding rule.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getForwardingRule.ts#L68">property portRange</a>
</h3>

```typescript
portRange: string;
```


Port range, if this forwarding rule has one.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getForwardingRule.ts#L72">property ports</a>
</h3>

```typescript
ports: string[];
```


List of ports to use for internal load balancing, if this forwarding rule has any.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getForwardingRule.ts#L73">property project</a>
</h3>

```typescript
project: string;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getForwardingRule.ts#L77">property region</a>
</h3>

```typescript
region: string;
```


Region of this forwarding rule.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getForwardingRule.ts#L81">property selfLink</a>
</h3>

```typescript
selfLink: string;
```


The URI of the resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getForwardingRule.ts#L85">property subnetwork</a>
</h3>

```typescript
subnetwork: string;
```


Subnetwork of this forwarding rule.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getForwardingRule.ts#L89">property target</a>
</h3>

```typescript
target: string;
```


URL of the target pool, if this forwarding rule has one.

<h2 class="pdoc-module-header" id="GetGlobalAddressArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getGlobalAddress.ts#L20">interface GetGlobalAddressArgs</a>
</h2>

A collection of arguments for invoking getGlobalAddress.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getGlobalAddress.ts#L24">property name</a>
</h3>

```typescript
name: string;
```


A unique name for the resource, required by GCE.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getGlobalAddress.ts#L29">property project</a>
</h3>

```typescript
project?: string;
```


The project in which the resource belongs. If it
is not provided, the provider project is used.

<h2 class="pdoc-module-header" id="GetGlobalAddressResult">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getGlobalAddress.ts#L35">interface GetGlobalAddressResult</a>
</h2>

A collection of values returned by getGlobalAddress.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getGlobalAddress.ts#L39">property address</a>
</h3>

```typescript
address: string;
```


The IP of the created resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getGlobalAddress.ts#L52">property id</a>
</h3>

```typescript
id: string;
```


id is the provider-assigned unique ID for this managed resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getGlobalAddress.ts#L40">property project</a>
</h3>

```typescript
project: string;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getGlobalAddress.ts#L44">property selfLink</a>
</h3>

```typescript
selfLink: string;
```


The URI of the created resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getGlobalAddress.ts#L48">property status</a>
</h3>

```typescript
status: string;
```


Indicates if the address is used. Possible values are: RESERVED or IN_USE.

<h2 class="pdoc-module-header" id="GetImageArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getImage.ts#L22">interface GetImageArgs</a>
</h2>

A collection of arguments for invoking getImage.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getImage.ts#L23">property family</a>
</h3>

```typescript
family?: string;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getImage.ts#L24">property name</a>
</h3>

```typescript
name?: string;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getImage.ts#L30">property project</a>
</h3>

```typescript
project?: string;
```


The project in which the resource belongs. If it is not
provided, the provider project is used. If you are using a
[public base image][pubimg], be sure to specify the correct Image Project.

<h2 class="pdoc-module-header" id="GetImageResult">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getImage.ts#L36">interface GetImageResult</a>
</h2>

A collection of values returned by getImage.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getImage.ts#L40">property archiveSizeBytes</a>
</h3>

```typescript
archiveSizeBytes: number;
```


The size of the image tar.gz archive stored in Google Cloud Storage in bytes.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getImage.ts#L44">property creationTimestamp</a>
</h3>

```typescript
creationTimestamp: string;
```


The creation timestamp in RFC3339 text format.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getImage.ts#L48">property description</a>
</h3>

```typescript
description: string;
```


An optional description of this image.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getImage.ts#L52">property diskSizeGb</a>
</h3>

```typescript
diskSizeGb: number;
```


The size of the image when restored onto a persistent disk in gigabytes.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getImage.ts#L56">property family</a>
</h3>

```typescript
family: string;
```


The family name of the image.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getImage.ts#L113">property id</a>
</h3>

```typescript
id: string;
```


id is the provider-assigned unique ID for this managed resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getImage.ts#L62">property imageEncryptionKeySha256</a>
</h3>

```typescript
imageEncryptionKeySha256: string;
```


The [RFC 4648 base64](https://tools.ietf.org/html/rfc4648#section-4)
encoded SHA-256 hash of the [customer-supplied encryption key](https://cloud.google.com/compute/docs/disks/customer-supplied-encryption)
that protects this image.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getImage.ts#L66">property imageId</a>
</h3>

```typescript
imageId: string;
```


The unique identifier for the image.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getImage.ts#L70">property labelFingerprint</a>
</h3>

```typescript
labelFingerprint: string;
```


A fingerprint for the labels being applied to this image.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getImage.ts#L74">property labels</a>
</h3>

```typescript
labels: { ... };
```


A map of labels applied to this image.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getImage.ts#L78">property licenses</a>
</h3>

```typescript
licenses: string[];
```


A list of applicable license URI.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getImage.ts#L82">property name</a>
</h3>

```typescript
name: string;
```


The name of the image.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getImage.ts#L83">property project</a>
</h3>

```typescript
project: string;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getImage.ts#L87">property selfLink</a>
</h3>

```typescript
selfLink: string;
```


The URI of the image.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getImage.ts#L91">property sourceDisk</a>
</h3>

```typescript
sourceDisk: string;
```


The URL of the source disk used to create this image.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getImage.ts#L97">property sourceDiskEncryptionKeySha256</a>
</h3>

```typescript
sourceDiskEncryptionKeySha256: string;
```


The [RFC 4648 base64](https://tools.ietf.org/html/rfc4648#section-4)
encoded SHA-256 hash of the [customer-supplied encryption key](https://cloud.google.com/compute/docs/disks/customer-supplied-encryption)
that protects this image.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getImage.ts#L101">property sourceDiskId</a>
</h3>

```typescript
sourceDiskId: string;
```


The ID value of the disk used to create this image.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getImage.ts#L105">property sourceImageId</a>
</h3>

```typescript
sourceImageId: string;
```


The ID value of the image used to create this image.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getImage.ts#L109">property status</a>
</h3>

```typescript
status: string;
```


The status of the image. Possible values are **FAILED**, **PENDING**, or **READY**.

<h2 class="pdoc-module-header" id="GetInstanceGroupArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getInstanceGroup.ts#L31">interface GetInstanceGroupArgs</a>
</h2>

A collection of arguments for invoking getInstanceGroup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getInstanceGroup.ts#L35">property name</a>
</h3>

```typescript
name?: string;
```


The name of the instance group. Either `name` or `self_link` must be provided.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getInstanceGroup.ts#L40">property project</a>
</h3>

```typescript
project?: string;
```


The ID of the project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getInstanceGroup.ts#L44">property selfLink</a>
</h3>

```typescript
selfLink?: string;
```


The self link of the instance group. Either `name` or `self_link` must be provided.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getInstanceGroup.ts#L49">property zone</a>
</h3>

```typescript
zone?: string;
```


The zone of the instance group. If referencing the instance group by name
and `zone` is not provided, the provider zone is used.

<h2 class="pdoc-module-header" id="GetInstanceGroupResult">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getInstanceGroup.ts#L55">interface GetInstanceGroupResult</a>
</h2>

A collection of values returned by getInstanceGroup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getInstanceGroup.ts#L59">property description</a>
</h3>

```typescript
description: string;
```


Textual description of the instance group.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getInstanceGroup.ts#L85">property id</a>
</h3>

```typescript
id: string;
```


id is the provider-assigned unique ID for this managed resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getInstanceGroup.ts#L63">property instances</a>
</h3>

```typescript
instances: string[];
```


List of instances in the group.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getInstanceGroup.ts#L67">property namedPorts</a>
</h3>

```typescript
namedPorts: { ... }[];
```


List of named ports in the group.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getInstanceGroup.ts#L71">property network</a>
</h3>

```typescript
network: string;
```


The URL of the network the instance group is in.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getInstanceGroup.ts#L72">property project</a>
</h3>

```typescript
project: string;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getInstanceGroup.ts#L76">property selfLink</a>
</h3>

```typescript
selfLink: string;
```


The URI of the resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getInstanceGroup.ts#L80">property size</a>
</h3>

```typescript
size: number;
```


The number of instances in the group.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getInstanceGroup.ts#L81">property zone</a>
</h3>

```typescript
zone: string;
```

<h2 class="pdoc-module-header" id="GetLBIPRangesResult">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getLBIPRanges.ts#L19">interface GetLBIPRangesResult</a>
</h2>

A collection of values returned by getLBIPRanges.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getLBIPRanges.ts#L23">property httpSslTcpInternals</a>
</h3>

```typescript
httpSslTcpInternals: string[];
```


The IP ranges used for health checks when **HTTP(S), SSL proxy, TCP proxy, and Internal load balancing** is used

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getLBIPRanges.ts#L31">property id</a>
</h3>

```typescript
id: string;
```


id is the provider-assigned unique ID for this managed resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getLBIPRanges.ts#L27">property networks</a>
</h3>

```typescript
networks: string[];
```


The IP ranges used for health checks when **Network load balancing** is used

<h2 class="pdoc-module-header" id="GetNetblockIPRangesResult">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getNetblockIPRanges.ts#L19">interface GetNetblockIPRangesResult</a>
</h2>

A collection of values returned by getNetblockIPRanges.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getNetblockIPRanges.ts#L23">property cidrBlocks</a>
</h3>

```typescript
cidrBlocks: string[];
```


Retrieve list of all CIDR blocks.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getNetblockIPRanges.ts#L27">property cidrBlocksIpv4s</a>
</h3>

```typescript
cidrBlocksIpv4s: string[];
```


Retrieve list of the IP4 CIDR blocks

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getNetblockIPRanges.ts#L31">property cidrBlocksIpv6s</a>
</h3>

```typescript
cidrBlocksIpv6s: string[];
```


Retrieve list of the IP6 CIDR blocks.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getNetblockIPRanges.ts#L35">property id</a>
</h3>

```typescript
id: string;
```


id is the provider-assigned unique ID for this managed resource.

<h2 class="pdoc-module-header" id="GetNetworkArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getNetwork.ts#L19">interface GetNetworkArgs</a>
</h2>

A collection of arguments for invoking getNetwork.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getNetwork.ts#L23">property name</a>
</h3>

```typescript
name: string;
```


The name of the network.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getNetwork.ts#L28">property project</a>
</h3>

```typescript
project?: string;
```


The ID of the project in which the resource belongs. If it
is not provided, the provider project is used.

<h2 class="pdoc-module-header" id="GetNetworkResult">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getNetwork.ts#L34">interface GetNetworkResult</a>
</h2>

A collection of values returned by getNetwork.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getNetwork.ts#L38">property description</a>
</h3>

```typescript
description: string;
```


Description of this network.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getNetwork.ts#L42">property gatewayIpv4</a>
</h3>

```typescript
gatewayIpv4: string;
```


The IP address of the gateway.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getNetwork.ts#L54">property id</a>
</h3>

```typescript
id: string;
```


id is the provider-assigned unique ID for this managed resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getNetwork.ts#L46">property selfLink</a>
</h3>

```typescript
selfLink: string;
```


The URI of the resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getNetwork.ts#L50">property subnetworksSelfLinks</a>
</h3>

```typescript
subnetworksSelfLinks: string[];
```


the list of subnetworks which belong to the network

<h2 class="pdoc-module-header" id="GetRegionInstanceGroupArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getRegionInstanceGroup.ts#L48">interface GetRegionInstanceGroupArgs</a>
</h2>

A collection of arguments for invoking getRegionInstanceGroup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getRegionInstanceGroup.ts#L52">property name</a>
</h3>

```typescript
name?: string;
```


The name of the instance group.  One of `name` or `self_link` must be provided.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getRegionInstanceGroup.ts#L57">property project</a>
</h3>

```typescript
project?: string;
```


The project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getRegionInstanceGroup.ts#L63">property region</a>
</h3>

```typescript
region?: string;
```


The region in which the resource belongs.  If `self_link`
is provided, this value is ignored.  If neither `self_link` nor `region` are
provided, the provider region is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getRegionInstanceGroup.ts#L67">property selfLink</a>
</h3>

```typescript
selfLink?: string;
```


The link to the instance group.  One of `name` or `self_link` must be provided.

<h2 class="pdoc-module-header" id="GetRegionInstanceGroupResult">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getRegionInstanceGroup.ts#L73">interface GetRegionInstanceGroupResult</a>
</h2>

A collection of values returned by getRegionInstanceGroup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getRegionInstanceGroup.ts#L92">property id</a>
</h3>

```typescript
id: string;
```


id is the provider-assigned unique ID for this managed resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getRegionInstanceGroup.ts#L77">property instances</a>
</h3>

```typescript
instances: { ... }[];
```


List of instances in the group, as a list of resources, each containing:

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getRegionInstanceGroup.ts#L81">property name</a>
</h3>

```typescript
name: string;
```


String port name

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getRegionInstanceGroup.ts#L82">property project</a>
</h3>

```typescript
project: string;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getRegionInstanceGroup.ts#L83">property region</a>
</h3>

```typescript
region: string;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getRegionInstanceGroup.ts#L84">property selfLink</a>
</h3>

```typescript
selfLink: string;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getRegionInstanceGroup.ts#L88">property size</a>
</h3>

```typescript
size: number;
```


The number of instances in the group.

<h2 class="pdoc-module-header" id="GetRegionsArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getRegions.ts#L33">interface GetRegionsArgs</a>
</h2>

A collection of arguments for invoking getRegions.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getRegions.ts#L37">property project</a>
</h3>

```typescript
project?: string;
```


Project from which to list available regions. Defaults to project declared in the provider.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getRegions.ts#L42">property status</a>
</h3>

```typescript
status?: string;
```


Allows to filter list of regions based on their current status. Status can be either `UP` or `DOWN`.
Defaults to no filtering (all available regions - both `UP` and `DOWN`).

<h2 class="pdoc-module-header" id="GetRegionsResult">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getRegions.ts#L48">interface GetRegionsResult</a>
</h2>

A collection of values returned by getRegions.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getRegions.ts#L57">property id</a>
</h3>

```typescript
id: string;
```


id is the provider-assigned unique ID for this managed resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getRegions.ts#L52">property names</a>
</h3>

```typescript
names: string[];
```


A list of regions available in the given project

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getRegions.ts#L53">property project</a>
</h3>

```typescript
project: string;
```

<h2 class="pdoc-module-header" id="GetSSLPolicyArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getSSLPolicy.ts#L20">interface GetSSLPolicyArgs</a>
</h2>

A collection of arguments for invoking getSSLPolicy.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getSSLPolicy.ts#L24">property name</a>
</h3>

```typescript
name: string;
```


The name of the SSL Policy.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getSSLPolicy.ts#L29">property project</a>
</h3>

```typescript
project?: string;
```


The ID of the project in which the resource belongs. If it
is not provided, the provider project is used.

<h2 class="pdoc-module-header" id="GetSSLPolicyResult">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getSSLPolicy.ts#L35">interface GetSSLPolicyResult</a>
</h2>

A collection of values returned by getSSLPolicy.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getSSLPolicy.ts#L36">property creationTimestamp</a>
</h3>

```typescript
creationTimestamp: string;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getSSLPolicy.ts#L42">property customFeatures</a>
</h3>

```typescript
customFeatures: string[];
```


If the `profile` is `CUSTOM`, these are the custom encryption
ciphers supported by the profile. If the `profile` is *not* `CUSTOM`, this
attribute will be empty.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getSSLPolicy.ts#L46">property description</a>
</h3>

```typescript
description: string;
```


Description of this SSL Policy.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getSSLPolicy.ts#L50">property enabledFeatures</a>
</h3>

```typescript
enabledFeatures: string[];
```


The set of enabled encryption ciphers as a result of the policy config

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getSSLPolicy.ts#L54">property fingerprint</a>
</h3>

```typescript
fingerprint: string;
```


Fingerprint of this resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getSSLPolicy.ts#L70">property id</a>
</h3>

```typescript
id: string;
```


id is the provider-assigned unique ID for this managed resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getSSLPolicy.ts#L58">property minTlsVersion</a>
</h3>

```typescript
minTlsVersion: string;
```


The minimum supported TLS version of this policy.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getSSLPolicy.ts#L62">property profile</a>
</h3>

```typescript
profile: string;
```


The Google-curated or custom profile used by this policy.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getSSLPolicy.ts#L66">property selfLink</a>
</h3>

```typescript
selfLink: string;
```


The URI of the created resource.

<h2 class="pdoc-module-header" id="GetSubnetworkArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getSubnetwork.ts#L20">interface GetSubnetworkArgs</a>
</h2>

A collection of arguments for invoking getSubnetwork.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getSubnetwork.ts#L24">property name</a>
</h3>

```typescript
name: string;
```


The name of the subnetwork.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getSubnetwork.ts#L29">property project</a>
</h3>

```typescript
project?: string;
```


The ID of the project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getSubnetwork.ts#L34">property region</a>
</h3>

```typescript
region?: string;
```


The region this subnetwork has been created in. If
unspecified, this defaults to the region configured in the provider.

<h2 class="pdoc-module-header" id="GetSubnetworkResult">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getSubnetwork.ts#L40">interface GetSubnetworkResult</a>
</h2>

A collection of values returned by getSubnetwork.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getSubnetwork.ts#L44">property description</a>
</h3>

```typescript
description: string;
```


Description of this subnetwork.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getSubnetwork.ts#L48">property gatewayAddress</a>
</h3>

```typescript
gatewayAddress: string;
```


The IP address of the gateway.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getSubnetwork.ts#L79">property id</a>
</h3>

```typescript
id: string;
```


id is the provider-assigned unique ID for this managed resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getSubnetwork.ts#L53">property ipCidrRange</a>
</h3>

```typescript
ipCidrRange: string;
```


The range of IP addresses belonging to this subnetwork
secondary range.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getSubnetwork.ts#L58">property network</a>
</h3>

```typescript
network: string;
```


The network name or resource link to the parent
network of this subnetwork.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getSubnetwork.ts#L64">property privateIpGoogleAccess</a>
</h3>

```typescript
privateIpGoogleAccess: boolean;
```


Whether the VMs in this subnet
can access Google services without assigned external IP
addresses.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getSubnetwork.ts#L65">property project</a>
</h3>

```typescript
project: string;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getSubnetwork.ts#L66">property region</a>
</h3>

```typescript
region: string;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getSubnetwork.ts#L71">property secondaryIpRanges</a>
</h3>

```typescript
secondaryIpRanges: { ... }[];
```


An array of configurations for secondary IP ranges for
VM instances contained in this subnetwork. Structure is documented below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getSubnetwork.ts#L75">property selfLink</a>
</h3>

```typescript
selfLink: string;
```


The URI of the created resource.

<h2 class="pdoc-module-header" id="GetVPNGatewayArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getVPNGateway.ts#L20">interface GetVPNGatewayArgs</a>
</h2>

A collection of arguments for invoking getVPNGateway.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getVPNGateway.ts#L24">property name</a>
</h3>

```typescript
name: string;
```


The name of the VPN gateway.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getVPNGateway.ts#L29">property project</a>
</h3>

```typescript
project?: string;
```


The project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getVPNGateway.ts#L34">property region</a>
</h3>

```typescript
region?: string;
```


The region in which the resource belongs. If it
is not provided, the project region is used.

<h2 class="pdoc-module-header" id="GetVPNGatewayResult">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getVPNGateway.ts#L40">interface GetVPNGatewayResult</a>
</h2>

A collection of values returned by getVPNGateway.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getVPNGateway.ts#L44">property description</a>
</h3>

```typescript
description: string;
```


Description of this VPN gateway.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getVPNGateway.ts#L61">property id</a>
</h3>

```typescript
id: string;
```


id is the provider-assigned unique ID for this managed resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getVPNGateway.ts#L48">property network</a>
</h3>

```typescript
network: string;
```


The network of this VPN gateway.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getVPNGateway.ts#L49">property project</a>
</h3>

```typescript
project: string;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getVPNGateway.ts#L53">property region</a>
</h3>

```typescript
region: string;
```


Region of this VPN gateway.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getVPNGateway.ts#L57">property selfLink</a>
</h3>

```typescript
selfLink: string;
```


The URI of the resource.

<h2 class="pdoc-module-header" id="GetZonesArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getZones.ts#L36">interface GetZonesArgs</a>
</h2>

A collection of arguments for invoking getZones.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getZones.ts#L40">property project</a>
</h3>

```typescript
project?: string;
```


Project from which to list available zones. Defaults to project declared in the provider.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getZones.ts#L44">property region</a>
</h3>

```typescript
region?: string;
```


Region from which to list available zones. Defaults to region declared in the provider.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getZones.ts#L49">property status</a>
</h3>

```typescript
status?: string;
```


Allows to filter list of zones based on their current status. Status can be either `UP` or `DOWN`.
Defaults to no filtering (all available zones - both `UP` and `DOWN`).

<h2 class="pdoc-module-header" id="GetZonesResult">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getZones.ts#L55">interface GetZonesResult</a>
</h2>

A collection of values returned by getZones.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getZones.ts#L64">property id</a>
</h3>

```typescript
id: string;
```


id is the provider-assigned unique ID for this managed resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getZones.ts#L59">property names</a>
</h3>

```typescript
names: string[];
```


A list of zones available in the given region

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/getZones.ts#L60">property project</a>
</h3>

```typescript
project: string;
```

<h2 class="pdoc-module-header" id="GlobalAddressArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/globalAddress.ts#L90">interface GlobalAddressArgs</a>
</h2>

The set of arguments for constructing a GlobalAddress resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/globalAddress.ts#L91">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/globalAddress.ts#L92">property ipVersion</a>
</h3>

```typescript
ipVersion?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/globalAddress.ts#L93">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/globalAddress.ts#L98">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.

<h2 class="pdoc-module-header" id="GlobalAddressState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/globalAddress.ts#L70">interface GlobalAddressState</a>
</h2>

Input properties used for looking up and filtering GlobalAddress resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/globalAddress.ts#L71">property address</a>
</h3>

```typescript
address?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/globalAddress.ts#L72">property creationTimestamp</a>
</h3>

```typescript
creationTimestamp?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/globalAddress.ts#L73">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/globalAddress.ts#L74">property ipVersion</a>
</h3>

```typescript
ipVersion?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/globalAddress.ts#L75">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/globalAddress.ts#L80">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/globalAddress.ts#L84">property selfLink</a>
</h3>

```typescript
selfLink?: pulumi.Input<string>;
```


The URI of the created resource.

<h2 class="pdoc-module-header" id="GlobalForwardingRuleArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/globalForwardingRule.ts#L199">interface GlobalForwardingRuleArgs</a>
</h2>

The set of arguments for constructing a GlobalForwardingRule resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/globalForwardingRule.ts#L203">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```


Textual description field.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/globalForwardingRule.ts#L210">property ipAddress</a>
</h3>

```typescript
ipAddress?: pulumi.Input<string>;
```


The static IP. (if not set, an ephemeral IP is
used). This should be the literal IP address to be used, not the `self_link`
to a `google_compute_global_address` resource. (If using a `google_compute_global_address`
resource, use the `address` property instead of the `self_link` property.)

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/globalForwardingRule.ts#L215">property ipProtocol</a>
</h3>

```typescript
ipProtocol?: pulumi.Input<string>;
```


The IP protocol to route, one of "TCP" "UDP" "AH"
"ESP" or "SCTP". (default "TCP").

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/globalForwardingRule.ts#L221">property ipVersion</a>
</h3>

```typescript
ipVersion?: pulumi.Input<string>;
```


The IP Version that will be used by this resource's address. One of `"IPV4"` or `"IPV6"`.
You cannot provide this and `ip_address`.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/globalForwardingRule.ts#L226">property labels</a>
</h3>

```typescript
labels?: pulumi.Input<{ ... }>;
```


)
A set of key/value label pairs to assign to the resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/globalForwardingRule.ts#L231">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


A unique name for the resource, required by GCE. Changing
this forces a new resource to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/globalForwardingRule.ts#L242">property portRange</a>
</h3>

```typescript
portRange?: pulumi.Input<string>;
```


A range e.g. "1024-2048" or a single port "1024"
(defaults to all ports!).
Some types of forwarding targets have constraints on the acceptable ports:
* Target HTTP proxy: 80, 8080
* Target HTTPS proxy: 443
* Target TCP proxy: 25, 43, 110, 143, 195, 443, 465, 587, 700, 993, 995, 1883, 5222
* Target SSL proxy: 25, 43, 110, 143, 195, 443, 465, 587, 700, 993, 995, 1883, 5222
* Target VPN gateway: 500, 4500

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/globalForwardingRule.ts#L247">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/globalForwardingRule.ts#L251">property target</a>
</h3>

```typescript
target: pulumi.Input<string>;
```


URL of target HTTP or HTTPS proxy.

<h2 class="pdoc-module-header" id="GlobalForwardingRuleState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/globalForwardingRule.ts#L133">interface GlobalForwardingRuleState</a>
</h2>

Input properties used for looking up and filtering GlobalForwardingRule resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/globalForwardingRule.ts#L137">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```


Textual description field.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/globalForwardingRule.ts#L144">property ipAddress</a>
</h3>

```typescript
ipAddress?: pulumi.Input<string>;
```


The static IP. (if not set, an ephemeral IP is
used). This should be the literal IP address to be used, not the `self_link`
to a `google_compute_global_address` resource. (If using a `google_compute_global_address`
resource, use the `address` property instead of the `self_link` property.)

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/globalForwardingRule.ts#L149">property ipProtocol</a>
</h3>

```typescript
ipProtocol?: pulumi.Input<string>;
```


The IP protocol to route, one of "TCP" "UDP" "AH"
"ESP" or "SCTP". (default "TCP").

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/globalForwardingRule.ts#L155">property ipVersion</a>
</h3>

```typescript
ipVersion?: pulumi.Input<string>;
```


The IP Version that will be used by this resource's address. One of `"IPV4"` or `"IPV6"`.
You cannot provide this and `ip_address`.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/globalForwardingRule.ts#L159">property labelFingerprint</a>
</h3>

```typescript
labelFingerprint?: pulumi.Input<string>;
```


([Beta](/docs/providers/google/index.html#beta-features)) The current label fingerprint.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/globalForwardingRule.ts#L164">property labels</a>
</h3>

```typescript
labels?: pulumi.Input<{ ... }>;
```


)
A set of key/value label pairs to assign to the resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/globalForwardingRule.ts#L169">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


A unique name for the resource, required by GCE. Changing
this forces a new resource to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/globalForwardingRule.ts#L180">property portRange</a>
</h3>

```typescript
portRange?: pulumi.Input<string>;
```


A range e.g. "1024-2048" or a single port "1024"
(defaults to all ports!).
Some types of forwarding targets have constraints on the acceptable ports:
* Target HTTP proxy: 80, 8080
* Target HTTPS proxy: 443
* Target TCP proxy: 25, 43, 110, 143, 195, 443, 465, 587, 700, 993, 995, 1883, 5222
* Target SSL proxy: 25, 43, 110, 143, 195, 443, 465, 587, 700, 993, 995, 1883, 5222
* Target VPN gateway: 500, 4500

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/globalForwardingRule.ts#L185">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/globalForwardingRule.ts#L189">property selfLink</a>
</h3>

```typescript
selfLink?: pulumi.Input<string>;
```


The URI of the created resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/globalForwardingRule.ts#L193">property target</a>
</h3>

```typescript
target?: pulumi.Input<string>;
```


URL of target HTTP or HTTPS proxy.

<h2 class="pdoc-module-header" id="HealthCheckArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/healthCheck.ts#L192">interface HealthCheckArgs</a>
</h2>

The set of arguments for constructing a HealthCheck resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/healthCheck.ts#L197">property checkIntervalSec</a>
</h3>

```typescript
checkIntervalSec?: pulumi.Input<number>;
```


The number of seconds between each poll of
the instance instance (default 5).

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/healthCheck.ts#L201">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```


Textual description field.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/healthCheck.ts#L205">property healthyThreshold</a>
</h3>

```typescript
healthyThreshold?: pulumi.Input<number>;
```


Consecutive successes required (default 2).

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/healthCheck.ts#L210">property httpHealthCheck</a>
</h3>

```typescript
httpHealthCheck?: pulumi.Input<{ ... }>;
```


An HTTP Health Check. Only one kind of Health Check can be added.
Structure is documented below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/healthCheck.ts#L215">property httpsHealthCheck</a>
</h3>

```typescript
httpsHealthCheck?: pulumi.Input<{ ... }>;
```


An HTTPS Health Check. Only one kind of Health Check can be added.
Structure is documented below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/healthCheck.ts#L220">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


A unique name for the resource, required by GCE.
Changing this forces a new resource to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/healthCheck.ts#L225">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/healthCheck.ts#L230">property sslHealthCheck</a>
</h3>

```typescript
sslHealthCheck?: pulumi.Input<{ ... }>;
```


An SSL Health Check. Only one kind of Health Check can be added.
Structure is documented below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/healthCheck.ts#L235">property tcpHealthCheck</a>
</h3>

```typescript
tcpHealthCheck?: pulumi.Input<{ ... }>;
```


A TCP Health Check. Only one kind of Health Check can be added.
Structure is documented below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/healthCheck.ts#L240">property timeoutSec</a>
</h3>

```typescript
timeoutSec?: pulumi.Input<number>;
```


The number of seconds to wait before declaring
failure (default 5).

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/healthCheck.ts#L244">property unhealthyThreshold</a>
</h3>

```typescript
unhealthyThreshold?: pulumi.Input<number>;
```


Consecutive failures required (default 2).

<h2 class="pdoc-module-header" id="HealthCheckState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/healthCheck.ts#L130">interface HealthCheckState</a>
</h2>

Input properties used for looking up and filtering HealthCheck resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/healthCheck.ts#L135">property checkIntervalSec</a>
</h3>

```typescript
checkIntervalSec?: pulumi.Input<number>;
```


The number of seconds between each poll of
the instance instance (default 5).

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/healthCheck.ts#L139">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```


Textual description field.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/healthCheck.ts#L143">property healthyThreshold</a>
</h3>

```typescript
healthyThreshold?: pulumi.Input<number>;
```


Consecutive successes required (default 2).

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/healthCheck.ts#L148">property httpHealthCheck</a>
</h3>

```typescript
httpHealthCheck?: pulumi.Input<{ ... }>;
```


An HTTP Health Check. Only one kind of Health Check can be added.
Structure is documented below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/healthCheck.ts#L153">property httpsHealthCheck</a>
</h3>

```typescript
httpsHealthCheck?: pulumi.Input<{ ... }>;
```


An HTTPS Health Check. Only one kind of Health Check can be added.
Structure is documented below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/healthCheck.ts#L158">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


A unique name for the resource, required by GCE.
Changing this forces a new resource to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/healthCheck.ts#L163">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/healthCheck.ts#L167">property selfLink</a>
</h3>

```typescript
selfLink?: pulumi.Input<string>;
```


The URI of the created resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/healthCheck.ts#L172">property sslHealthCheck</a>
</h3>

```typescript
sslHealthCheck?: pulumi.Input<{ ... }>;
```


An SSL Health Check. Only one kind of Health Check can be added.
Structure is documented below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/healthCheck.ts#L177">property tcpHealthCheck</a>
</h3>

```typescript
tcpHealthCheck?: pulumi.Input<{ ... }>;
```


A TCP Health Check. Only one kind of Health Check can be added.
Structure is documented below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/healthCheck.ts#L182">property timeoutSec</a>
</h3>

```typescript
timeoutSec?: pulumi.Input<number>;
```


The number of seconds to wait before declaring
failure (default 5).

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/healthCheck.ts#L186">property unhealthyThreshold</a>
</h3>

```typescript
unhealthyThreshold?: pulumi.Input<number>;
```


Consecutive failures required (default 2).

<h2 class="pdoc-module-header" id="HttpHealthCheckArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpHealthCheck.ts#L110">interface HttpHealthCheckArgs</a>
</h2>

The set of arguments for constructing a HttpHealthCheck resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpHealthCheck.ts#L111">property checkIntervalSec</a>
</h3>

```typescript
checkIntervalSec?: pulumi.Input<number>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpHealthCheck.ts#L112">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpHealthCheck.ts#L113">property healthyThreshold</a>
</h3>

```typescript
healthyThreshold?: pulumi.Input<number>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpHealthCheck.ts#L114">property host</a>
</h3>

```typescript
host?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpHealthCheck.ts#L115">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpHealthCheck.ts#L116">property port</a>
</h3>

```typescript
port?: pulumi.Input<number>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpHealthCheck.ts#L121">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpHealthCheck.ts#L122">property requestPath</a>
</h3>

```typescript
requestPath?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpHealthCheck.ts#L123">property timeoutSec</a>
</h3>

```typescript
timeoutSec?: pulumi.Input<number>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpHealthCheck.ts#L124">property unhealthyThreshold</a>
</h3>

```typescript
unhealthyThreshold?: pulumi.Input<number>;
```

<h2 class="pdoc-module-header" id="HttpHealthCheckState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpHealthCheck.ts#L85">interface HttpHealthCheckState</a>
</h2>

Input properties used for looking up and filtering HttpHealthCheck resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpHealthCheck.ts#L86">property checkIntervalSec</a>
</h3>

```typescript
checkIntervalSec?: pulumi.Input<number>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpHealthCheck.ts#L87">property creationTimestamp</a>
</h3>

```typescript
creationTimestamp?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpHealthCheck.ts#L88">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpHealthCheck.ts#L89">property healthyThreshold</a>
</h3>

```typescript
healthyThreshold?: pulumi.Input<number>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpHealthCheck.ts#L90">property host</a>
</h3>

```typescript
host?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpHealthCheck.ts#L91">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpHealthCheck.ts#L92">property port</a>
</h3>

```typescript
port?: pulumi.Input<number>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpHealthCheck.ts#L97">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpHealthCheck.ts#L98">property requestPath</a>
</h3>

```typescript
requestPath?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpHealthCheck.ts#L102">property selfLink</a>
</h3>

```typescript
selfLink?: pulumi.Input<string>;
```


The URI of the created resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpHealthCheck.ts#L103">property timeoutSec</a>
</h3>

```typescript
timeoutSec?: pulumi.Input<number>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpHealthCheck.ts#L104">property unhealthyThreshold</a>
</h3>

```typescript
unhealthyThreshold?: pulumi.Input<number>;
```

<h2 class="pdoc-module-header" id="HttpsHealthCheckArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpsHealthCheck.ts#L110">interface HttpsHealthCheckArgs</a>
</h2>

The set of arguments for constructing a HttpsHealthCheck resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpsHealthCheck.ts#L111">property checkIntervalSec</a>
</h3>

```typescript
checkIntervalSec?: pulumi.Input<number>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpsHealthCheck.ts#L112">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpsHealthCheck.ts#L113">property healthyThreshold</a>
</h3>

```typescript
healthyThreshold?: pulumi.Input<number>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpsHealthCheck.ts#L114">property host</a>
</h3>

```typescript
host?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpsHealthCheck.ts#L115">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpsHealthCheck.ts#L116">property port</a>
</h3>

```typescript
port?: pulumi.Input<number>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpsHealthCheck.ts#L121">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpsHealthCheck.ts#L122">property requestPath</a>
</h3>

```typescript
requestPath?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpsHealthCheck.ts#L123">property timeoutSec</a>
</h3>

```typescript
timeoutSec?: pulumi.Input<number>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpsHealthCheck.ts#L124">property unhealthyThreshold</a>
</h3>

```typescript
unhealthyThreshold?: pulumi.Input<number>;
```

<h2 class="pdoc-module-header" id="HttpsHealthCheckState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpsHealthCheck.ts#L85">interface HttpsHealthCheckState</a>
</h2>

Input properties used for looking up and filtering HttpsHealthCheck resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpsHealthCheck.ts#L86">property checkIntervalSec</a>
</h3>

```typescript
checkIntervalSec?: pulumi.Input<number>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpsHealthCheck.ts#L87">property creationTimestamp</a>
</h3>

```typescript
creationTimestamp?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpsHealthCheck.ts#L88">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpsHealthCheck.ts#L89">property healthyThreshold</a>
</h3>

```typescript
healthyThreshold?: pulumi.Input<number>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpsHealthCheck.ts#L90">property host</a>
</h3>

```typescript
host?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpsHealthCheck.ts#L91">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpsHealthCheck.ts#L92">property port</a>
</h3>

```typescript
port?: pulumi.Input<number>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpsHealthCheck.ts#L97">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpsHealthCheck.ts#L98">property requestPath</a>
</h3>

```typescript
requestPath?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpsHealthCheck.ts#L102">property selfLink</a>
</h3>

```typescript
selfLink?: pulumi.Input<string>;
```


The URI of the created resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpsHealthCheck.ts#L103">property timeoutSec</a>
</h3>

```typescript
timeoutSec?: pulumi.Input<number>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/httpsHealthCheck.ts#L104">property unhealthyThreshold</a>
</h3>

```typescript
unhealthyThreshold?: pulumi.Input<number>;
```

<h2 class="pdoc-module-header" id="ImageArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/image.ts#L176">interface ImageArgs</a>
</h2>

The set of arguments for constructing a Image resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/image.ts#L180">property createTimeout</a>
</h3>

```typescript
createTimeout?: pulumi.Input<number>;
```


Configurable timeout in minutes for creating images. Default is 4 minutes.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/image.ts#L184">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```


The description of the image to be created

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/image.ts#L188">property family</a>
</h3>

```typescript
family?: pulumi.Input<string>;
```


The name of the image family to which this image belongs.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/image.ts#L192">property labels</a>
</h3>

```typescript
labels?: pulumi.Input<{ ... }>;
```


A set of key/value label pairs to assign to the image.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/image.ts#L197">property licenses</a>
</h3>

```typescript
licenses?: pulumi.Input<pulumi.Input<string>[]>;
```


A list of license URIs to apply to this image. Changing this
forces a new resource to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/image.ts#L202">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


A unique name for the resource, required by GCE.
Changing this forces a new resource to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/image.ts#L207">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/image.ts#L213">property rawDisk</a>
</h3>

```typescript
rawDisk?: pulumi.Input<{ ... }>;
```


The raw disk that will be used as the source of the image.
Changing this forces a new resource to be created. Structure is documented
below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/image.ts#L218">property sourceDisk</a>
</h3>

```typescript
sourceDisk?: pulumi.Input<string>;
```


The URL of a disk that will be used as the source of the
image. Changing this forces a new resource to be created.

<h2 class="pdoc-module-header" id="ImageState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/image.ts#L120">interface ImageState</a>
</h2>

Input properties used for looking up and filtering Image resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/image.ts#L124">property createTimeout</a>
</h3>

```typescript
createTimeout?: pulumi.Input<number>;
```


Configurable timeout in minutes for creating images. Default is 4 minutes.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/image.ts#L128">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```


The description of the image to be created

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/image.ts#L132">property family</a>
</h3>

```typescript
family?: pulumi.Input<string>;
```


The name of the image family to which this image belongs.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/image.ts#L136">property labelFingerprint</a>
</h3>

```typescript
labelFingerprint?: pulumi.Input<string>;
```


The fingerprint of the assigned labels.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/image.ts#L140">property labels</a>
</h3>

```typescript
labels?: pulumi.Input<{ ... }>;
```


A set of key/value label pairs to assign to the image.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/image.ts#L145">property licenses</a>
</h3>

```typescript
licenses?: pulumi.Input<pulumi.Input<string>[]>;
```


A list of license URIs to apply to this image. Changing this
forces a new resource to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/image.ts#L150">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


A unique name for the resource, required by GCE.
Changing this forces a new resource to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/image.ts#L155">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/image.ts#L161">property rawDisk</a>
</h3>

```typescript
rawDisk?: pulumi.Input<{ ... }>;
```


The raw disk that will be used as the source of the image.
Changing this forces a new resource to be created. Structure is documented
below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/image.ts#L165">property selfLink</a>
</h3>

```typescript
selfLink?: pulumi.Input<string>;
```


The URI of the created resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/image.ts#L170">property sourceDisk</a>
</h3>

```typescript
sourceDisk?: pulumi.Input<string>;
```


The URL of a disk that will be used as the source of the
image. Changing this forces a new resource to be created.

<h2 class="pdoc-module-header" id="InstanceArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L376">interface InstanceArgs</a>
</h2>

The set of arguments for constructing a Instance resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L381">property allowStoppingForUpdate</a>
</h3>

```typescript
allowStoppingForUpdate?: pulumi.Input<boolean>;
```


If true, allows Terraform to stop the instance to update its properties.
If you try to update a property that requires stopping the instance without setting this field, the update will fail.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L385">property attachedDisks</a>
</h3>

```typescript
attachedDisks?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```


List of disks to attach to the instance. Structure is documented below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L390">property bootDisk</a>
</h3>

```typescript
bootDisk: pulumi.Input<{ ... }>;
```


The boot disk for the instance.
Structure is documented below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L396">property canIpForward</a>
</h3>

```typescript
canIpForward?: pulumi.Input<boolean>;
```


Whether to allow sending and receiving of
packets with non-matching source or destination IPs.
This defaults to false.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L401">property createTimeout</a>
</h3>

```typescript
createTimeout?: pulumi.Input<number>;
```


Configurable timeout in minutes for creating instances. Default is 4 minutes.
Changing this forces a new resource to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L406">property deletionProtection</a>
</h3>

```typescript
deletionProtection?: pulumi.Input<boolean>;
```


Enable deletion protection on this instance. Defaults to false.
**Note:** you must disable deletion protection before removing the resource (e.g., via `terraform destroy`), or the instance cannot be deleted and the Terraform run will not complete successfully.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L410">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```


A brief description of this resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L415">property guestAccelerators</a>
</h3>

```typescript
guestAccelerators?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```


List of the type and count of accelerator cards attached to the instance. Structure documented below.
**Note:** GPU accelerators can only be used with [`on_host_maintenance`](#on_host_maintenance) option set to TERMINATE.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L419">property labels</a>
</h3>

```typescript
labels?: pulumi.Input<{ ... }>;
```


A set of key/value label pairs to assign to the instance.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L423">property machineType</a>
</h3>

```typescript
machineType: pulumi.Input<string>;
```


The machine type to create.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L428">property metadata</a>
</h3>

```typescript
metadata?: pulumi.Input<{ ... }>;
```


Metadata key/value pairs to make available from
within the instance.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L436">property metadataStartupScript</a>
</h3>

```typescript
metadataStartupScript?: pulumi.Input<string>;
```


An alternative to using the
startup-script metadata key, except this one forces the instance to be
recreated (thus re-running the script) if it is changed. This replaces the
startup-script metadata key on the created instance and thus the two
mechanisms are not allowed to be used simultaneously.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L442">property minCpuPlatform</a>
</h3>

```typescript
minCpuPlatform?: pulumi.Input<string>;
```


Specifies a minimum CPU platform for the VM instance. Applicable values are the friendly names of CPU platforms, such as
`Intel Haswell` or `Intel Skylake`. See the complete list [here](https://cloud.google.com/compute/docs/instances/specify-min-cpu-platform).
**Note**: [`allow_stopping_for_update`](#allow_stopping_for_update) must be set to true in order to update this field.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L447">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


A unique name for the resource, required by GCE.
Changing this forces a new resource to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L452">property networkInterfaces</a>
</h3>

```typescript
networkInterfaces: pulumi.Input<pulumi.Input<{ ... }>[]>;
```


Networks to attach to the instance. This can
be specified multiple times. Structure is documented below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L457">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L462">property scheduling</a>
</h3>

```typescript
scheduling?: pulumi.Input<{ ... }>;
```


The scheduling strategy to use. More details about
this configuration option are detailed below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L467">property scratchDisks</a>
</h3>

```typescript
scratchDisks?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```


Scratch disks to attach to the instance. This can be
specified multiple times for multiple scratch disks. Structure is documented below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L473">property serviceAccount</a>
</h3>

```typescript
serviceAccount?: pulumi.Input<{ ... }>;
```


Service account to attach to the instance.
Structure is documented below.
**Note**: [`allow_stopping_for_update`](#allow_stopping_for_update) must be set to true in order to update this field.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L477">property tags</a>
</h3>

```typescript
tags?: pulumi.Input<pulumi.Input<string>[]>;
```


A list of tags to attach to the instance.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L481">property zone</a>
</h3>

```typescript
zone?: pulumi.Input<string>;
```


The zone that the machine should be created in.

<h2 class="pdoc-module-header" id="InstanceFromTemplateArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L194">interface InstanceFromTemplateArgs</a>
</h2>

The set of arguments for constructing a InstanceFromTemplate resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L195">property allowStoppingForUpdate</a>
</h3>

```typescript
allowStoppingForUpdate?: pulumi.Input<boolean>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L196">property attachedDisks</a>
</h3>

```typescript
attachedDisks?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L197">property canIpForward</a>
</h3>

```typescript
canIpForward?: pulumi.Input<boolean>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L198">property deletionProtection</a>
</h3>

```typescript
deletionProtection?: pulumi.Input<boolean>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L199">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L200">property guestAccelerators</a>
</h3>

```typescript
guestAccelerators?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L201">property labels</a>
</h3>

```typescript
labels?: pulumi.Input<{ ... }>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L202">property metadata</a>
</h3>

```typescript
metadata?: pulumi.Input<{ ... }>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L203">property metadataStartupScript</a>
</h3>

```typescript
metadataStartupScript?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L204">property minCpuPlatform</a>
</h3>

```typescript
minCpuPlatform?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L209">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


A unique name for the resource, required by GCE.
Changing this forces a new resource to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L210">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L211">property scheduling</a>
</h3>

```typescript
scheduling?: pulumi.Input<{ ... }>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L212">property scratchDisks</a>
</h3>

```typescript
scratchDisks?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L213">property serviceAccount</a>
</h3>

```typescript
serviceAccount?: pulumi.Input<{ ... }>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L218">property sourceInstanceTemplate</a>
</h3>

```typescript
sourceInstanceTemplate: pulumi.Input<string>;
```


Name or self link of an instance
template to create the instance based on.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L219">property tags</a>
</h3>

```typescript
tags?: pulumi.Input<pulumi.Input<string>[]>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L224">property zone</a>
</h3>

```typescript
zone?: pulumi.Input<string>;
```


The zone that the machine should be created in. If not
set, the provider zone is used.

<h2 class="pdoc-module-header" id="InstanceFromTemplateState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L149">interface InstanceFromTemplateState</a>
</h2>

Input properties used for looking up and filtering InstanceFromTemplate resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L150">property allowStoppingForUpdate</a>
</h3>

```typescript
allowStoppingForUpdate?: pulumi.Input<boolean>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L151">property attachedDisks</a>
</h3>

```typescript
attachedDisks?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L152">property bootDisk</a>
</h3>

```typescript
bootDisk?: pulumi.Input<{ ... }>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L153">property canIpForward</a>
</h3>

```typescript
canIpForward?: pulumi.Input<boolean>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L154">property cpuPlatform</a>
</h3>

```typescript
cpuPlatform?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L155">property deletionProtection</a>
</h3>

```typescript
deletionProtection?: pulumi.Input<boolean>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L156">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L157">property guestAccelerators</a>
</h3>

```typescript
guestAccelerators?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L158">property instanceId</a>
</h3>

```typescript
instanceId?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L159">property labelFingerprint</a>
</h3>

```typescript
labelFingerprint?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L160">property labels</a>
</h3>

```typescript
labels?: pulumi.Input<{ ... }>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L161">property machineType</a>
</h3>

```typescript
machineType?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L162">property metadata</a>
</h3>

```typescript
metadata?: pulumi.Input<{ ... }>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L163">property metadataFingerprint</a>
</h3>

```typescript
metadataFingerprint?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L164">property metadataStartupScript</a>
</h3>

```typescript
metadataStartupScript?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L165">property minCpuPlatform</a>
</h3>

```typescript
minCpuPlatform?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L170">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


A unique name for the resource, required by GCE.
Changing this forces a new resource to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L171">property networkInterfaces</a>
</h3>

```typescript
networkInterfaces?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L172">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L173">property scheduling</a>
</h3>

```typescript
scheduling?: pulumi.Input<{ ... }>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L174">property scratchDisks</a>
</h3>

```typescript
scratchDisks?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L175">property selfLink</a>
</h3>

```typescript
selfLink?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L176">property serviceAccount</a>
</h3>

```typescript
serviceAccount?: pulumi.Input<{ ... }>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L181">property sourceInstanceTemplate</a>
</h3>

```typescript
sourceInstanceTemplate?: pulumi.Input<string>;
```


Name or self link of an instance
template to create the instance based on.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L182">property tags</a>
</h3>

```typescript
tags?: pulumi.Input<pulumi.Input<string>[]>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L183">property tagsFingerprint</a>
</h3>

```typescript
tagsFingerprint?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceFromTemplate.ts#L188">property zone</a>
</h3>

```typescript
zone?: pulumi.Input<string>;
```


The zone that the machine should be created in. If not
set, the provider zone is used.

<h2 class="pdoc-module-header" id="InstanceGroupArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroup.ts#L159">interface InstanceGroupArgs</a>
</h2>

The set of arguments for constructing a InstanceGroup resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroup.ts#L164">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```


An optional textual description of the instance
group.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroup.ts#L170">property instances</a>
</h3>

```typescript
instances?: pulumi.Input<pulumi.Input<string>[]>;
```


List of instances in the group. They should be given
as self_link URLs. When adding instances they must all be in the same
network and zone as the instance group.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroup.ts#L174">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


The name which the port will be mapped to.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroup.ts#L179">property namedPorts</a>
</h3>

```typescript
namedPorts?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```


The named port configuration. See the section below
for details on configuration.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroup.ts#L186">property network</a>
</h3>

```typescript
network?: pulumi.Input<string>;
```


The URL of the network the instance group is in. If
this is different from the network where the instances are in, the creation
fails. Defaults to the network where the instances are in (if neither
`network` nor `instances` is specified, this field will be blank).

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroup.ts#L191">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroup.ts#L195">property zone</a>
</h3>

```typescript
zone?: pulumi.Input<string>;
```


The zone that this instance group should be created in.

<h2 class="pdoc-module-header" id="InstanceGroupManagerArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroupManager.ts#L277">interface InstanceGroupManagerArgs</a>
</h2>

The set of arguments for constructing a InstanceGroupManager resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroupManager.ts#L282">property autoHealingPolicies</a>
</h3>

```typescript
autoHealingPolicies?: pulumi.Input<{ ... }>;
```


) The autohealing policies for this managed instance
group. You can specify only one value. Structure is documented below. For more information, see the [official documentation](https://cloud.google.com/compute/docs/instance-groups/creating-groups-of-managed-instances#monitoring_groups).

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroupManager.ts#L291">property baseInstanceName</a>
</h3>

```typescript
baseInstanceName: pulumi.Input<string>;
```


The base instance name to use for
instances in this group. The value must be a valid
[RFC1035](https://www.ietf.org/rfc/rfc1035.txt) name. Supported characters
are lowercase letters, numbers, and hyphens (-). Instances are named by
appending a hyphen and a random four-character string to the base instance
name.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroupManager.ts#L296">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```


An optional textual description of the instance
group manager.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroupManager.ts#L300">property instanceTemplate</a>
</h3>

```typescript
instanceTemplate?: pulumi.Input<string>;
```


- The full URL to an instance template from which all new instances of this version will be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroupManager.ts#L304">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


- Version name.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroupManager.ts#L309">property namedPorts</a>
</h3>

```typescript
namedPorts?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```


The named port configuration. See the section below
for details on configuration.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroupManager.ts#L314">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroupManager.ts#L319">property rollingUpdatePolicy</a>
</h3>

```typescript
rollingUpdatePolicy?: pulumi.Input<{ ... }>;
```


) The update policy for this managed instance group. Structure is documented below. For more information, see the [official documentation](https://cloud.google.com/compute/docs/instance-groups/updating-managed-instance-groups) and [API](https://cloud.google.com/compute/docs/reference/rest/beta/instanceGroupManagers/patch)
- - -

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroupManager.ts#L325">property targetPools</a>
</h3>

```typescript
targetPools?: pulumi.Input<pulumi.Input<string>[]>;
```


The full URL of all target pools to which new
instances in the group are added. Updating the target pools attribute does
not affect existing instances.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroupManager.ts#L329">property targetSize</a>
</h3>

```typescript
targetSize?: pulumi.Input<number>;
```


- The number of instances calculated as a fixed number or a percentage depending on the settings. Structure is documented below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroupManager.ts#L337">property updateStrategy</a>
</h3>

```typescript
updateStrategy?: pulumi.Input<string>;
```


If the `instance_template`
resource is modified, a value of `"NONE"` will prevent any of the managed
instances from being restarted by Terraform. A value of `"RESTART"` will
restart all of the instances at once. `"ROLLING_UPDATE"` is supported as [Beta feature].
A value of `"ROLLING_UPDATE"` requires `rolling_update_policy` block to be set

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroupManager.ts#L346">property versions</a>
</h3>

```typescript
versions?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```


Application versions managed by this instance group. Each
version deals with a specific instance template, allowing canary release scenarios.
Conflicts with `instance_template`. Structure is documented below. Beware that
exactly one version must not specify a target size. It means that versions with
a target size will respect the setting, and the one without target size will
be applied to all remaining Instances (top level target_size - each version target_size).

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroupManager.ts#L352">property waitForInstances</a>
</h3>

```typescript
waitForInstances?: pulumi.Input<boolean>;
```


Whether to wait for all instances to be created/updated before
returning. Note that if this is set to true and the operation does not succeed, Terraform will
continue trying until it times out.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroupManager.ts#L357">property zone</a>
</h3>

```typescript
zone?: pulumi.Input<string>;
```


The zone that instances in this group should be created
in.

<h2 class="pdoc-module-header" id="InstanceGroupManagerState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroupManager.ts#L179">interface InstanceGroupManagerState</a>
</h2>

Input properties used for looking up and filtering InstanceGroupManager resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroupManager.ts#L184">property autoHealingPolicies</a>
</h3>

```typescript
autoHealingPolicies?: pulumi.Input<{ ... }>;
```


) The autohealing policies for this managed instance
group. You can specify only one value. Structure is documented below. For more information, see the [official documentation](https://cloud.google.com/compute/docs/instance-groups/creating-groups-of-managed-instances#monitoring_groups).

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroupManager.ts#L193">property baseInstanceName</a>
</h3>

```typescript
baseInstanceName?: pulumi.Input<string>;
```


The base instance name to use for
instances in this group. The value must be a valid
[RFC1035](https://www.ietf.org/rfc/rfc1035.txt) name. Supported characters
are lowercase letters, numbers, and hyphens (-). Instances are named by
appending a hyphen and a random four-character string to the base instance
name.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroupManager.ts#L198">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```


An optional textual description of the instance
group manager.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroupManager.ts#L202">property fingerprint</a>
</h3>

```typescript
fingerprint?: pulumi.Input<string>;
```


The fingerprint of the instance group manager.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroupManager.ts#L206">property instanceGroup</a>
</h3>

```typescript
instanceGroup?: pulumi.Input<string>;
```


The full URL of the instance group created by the manager.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroupManager.ts#L210">property instanceTemplate</a>
</h3>

```typescript
instanceTemplate?: pulumi.Input<string>;
```


- The full URL to an instance template from which all new instances of this version will be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroupManager.ts#L214">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


- Version name.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroupManager.ts#L219">property namedPorts</a>
</h3>

```typescript
namedPorts?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```


The named port configuration. See the section below
for details on configuration.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroupManager.ts#L224">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroupManager.ts#L229">property rollingUpdatePolicy</a>
</h3>

```typescript
rollingUpdatePolicy?: pulumi.Input<{ ... }>;
```


) The update policy for this managed instance group. Structure is documented below. For more information, see the [official documentation](https://cloud.google.com/compute/docs/instance-groups/updating-managed-instance-groups) and [API](https://cloud.google.com/compute/docs/reference/rest/beta/instanceGroupManagers/patch)
- - -

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroupManager.ts#L233">property selfLink</a>
</h3>

```typescript
selfLink?: pulumi.Input<string>;
```


The URL of the created resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroupManager.ts#L239">property targetPools</a>
</h3>

```typescript
targetPools?: pulumi.Input<pulumi.Input<string>[]>;
```


The full URL of all target pools to which new
instances in the group are added. Updating the target pools attribute does
not affect existing instances.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroupManager.ts#L243">property targetSize</a>
</h3>

```typescript
targetSize?: pulumi.Input<number>;
```


- The number of instances calculated as a fixed number or a percentage depending on the settings. Structure is documented below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroupManager.ts#L251">property updateStrategy</a>
</h3>

```typescript
updateStrategy?: pulumi.Input<string>;
```


If the `instance_template`
resource is modified, a value of `"NONE"` will prevent any of the managed
instances from being restarted by Terraform. A value of `"RESTART"` will
restart all of the instances at once. `"ROLLING_UPDATE"` is supported as [Beta feature].
A value of `"ROLLING_UPDATE"` requires `rolling_update_policy` block to be set

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroupManager.ts#L260">property versions</a>
</h3>

```typescript
versions?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```


Application versions managed by this instance group. Each
version deals with a specific instance template, allowing canary release scenarios.
Conflicts with `instance_template`. Structure is documented below. Beware that
exactly one version must not specify a target size. It means that versions with
a target size will respect the setting, and the one without target size will
be applied to all remaining Instances (top level target_size - each version target_size).

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroupManager.ts#L266">property waitForInstances</a>
</h3>

```typescript
waitForInstances?: pulumi.Input<boolean>;
```


Whether to wait for all instances to be created/updated before
returning. Note that if this is set to true and the operation does not succeed, Terraform will
continue trying until it times out.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroupManager.ts#L271">property zone</a>
</h3>

```typescript
zone?: pulumi.Input<string>;
```


The zone that instances in this group should be created
in.

<h2 class="pdoc-module-header" id="InstanceGroupState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroup.ts#L109">interface InstanceGroupState</a>
</h2>

Input properties used for looking up and filtering InstanceGroup resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroup.ts#L114">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```


An optional textual description of the instance
group.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroup.ts#L120">property instances</a>
</h3>

```typescript
instances?: pulumi.Input<pulumi.Input<string>[]>;
```


List of instances in the group. They should be given
as self_link URLs. When adding instances they must all be in the same
network and zone as the instance group.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroup.ts#L124">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


The name which the port will be mapped to.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroup.ts#L129">property namedPorts</a>
</h3>

```typescript
namedPorts?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```


The named port configuration. See the section below
for details on configuration.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroup.ts#L136">property network</a>
</h3>

```typescript
network?: pulumi.Input<string>;
```


The URL of the network the instance group is in. If
this is different from the network where the instances are in, the creation
fails. Defaults to the network where the instances are in (if neither
`network` nor `instances` is specified, this field will be blank).

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroup.ts#L141">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroup.ts#L145">property selfLink</a>
</h3>

```typescript
selfLink?: pulumi.Input<string>;
```


The URI of the created resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroup.ts#L149">property size</a>
</h3>

```typescript
size?: pulumi.Input<number>;
```


The number of instances in the group.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceGroup.ts#L153">property zone</a>
</h3>

```typescript
zone?: pulumi.Input<string>;
```


The zone that this instance group should be created in.

<h2 class="pdoc-module-header" id="InstanceState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L241">interface InstanceState</a>
</h2>

Input properties used for looking up and filtering Instance resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L246">property allowStoppingForUpdate</a>
</h3>

```typescript
allowStoppingForUpdate?: pulumi.Input<boolean>;
```


If true, allows Terraform to stop the instance to update its properties.
If you try to update a property that requires stopping the instance without setting this field, the update will fail.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L250">property attachedDisks</a>
</h3>

```typescript
attachedDisks?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```


List of disks to attach to the instance. Structure is documented below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L255">property bootDisk</a>
</h3>

```typescript
bootDisk?: pulumi.Input<{ ... }>;
```


The boot disk for the instance.
Structure is documented below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L261">property canIpForward</a>
</h3>

```typescript
canIpForward?: pulumi.Input<boolean>;
```


Whether to allow sending and receiving of
packets with non-matching source or destination IPs.
This defaults to false.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L265">property cpuPlatform</a>
</h3>

```typescript
cpuPlatform?: pulumi.Input<string>;
```


The CPU platform used by this instance.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L270">property createTimeout</a>
</h3>

```typescript
createTimeout?: pulumi.Input<number>;
```


Configurable timeout in minutes for creating instances. Default is 4 minutes.
Changing this forces a new resource to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L275">property deletionProtection</a>
</h3>

```typescript
deletionProtection?: pulumi.Input<boolean>;
```


Enable deletion protection on this instance. Defaults to false.
**Note:** you must disable deletion protection before removing the resource (e.g., via `terraform destroy`), or the instance cannot be deleted and the Terraform run will not complete successfully.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L279">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```


A brief description of this resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L284">property guestAccelerators</a>
</h3>

```typescript
guestAccelerators?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```


List of the type and count of accelerator cards attached to the instance. Structure documented below.
**Note:** GPU accelerators can only be used with [`on_host_maintenance`](#on_host_maintenance) option set to TERMINATE.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L288">property instanceId</a>
</h3>

```typescript
instanceId?: pulumi.Input<string>;
```


The server-assigned unique identifier of this instance.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L292">property labelFingerprint</a>
</h3>

```typescript
labelFingerprint?: pulumi.Input<string>;
```


The unique fingerprint of the labels.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L296">property labels</a>
</h3>

```typescript
labels?: pulumi.Input<{ ... }>;
```


A set of key/value label pairs to assign to the instance.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L300">property machineType</a>
</h3>

```typescript
machineType?: pulumi.Input<string>;
```


The machine type to create.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L305">property metadata</a>
</h3>

```typescript
metadata?: pulumi.Input<{ ... }>;
```


Metadata key/value pairs to make available from
within the instance.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L309">property metadataFingerprint</a>
</h3>

```typescript
metadataFingerprint?: pulumi.Input<string>;
```


The unique fingerprint of the metadata.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L317">property metadataStartupScript</a>
</h3>

```typescript
metadataStartupScript?: pulumi.Input<string>;
```


An alternative to using the
startup-script metadata key, except this one forces the instance to be
recreated (thus re-running the script) if it is changed. This replaces the
startup-script metadata key on the created instance and thus the two
mechanisms are not allowed to be used simultaneously.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L323">property minCpuPlatform</a>
</h3>

```typescript
minCpuPlatform?: pulumi.Input<string>;
```


Specifies a minimum CPU platform for the VM instance. Applicable values are the friendly names of CPU platforms, such as
`Intel Haswell` or `Intel Skylake`. See the complete list [here](https://cloud.google.com/compute/docs/instances/specify-min-cpu-platform).
**Note**: [`allow_stopping_for_update`](#allow_stopping_for_update) must be set to true in order to update this field.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L328">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


A unique name for the resource, required by GCE.
Changing this forces a new resource to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L333">property networkInterfaces</a>
</h3>

```typescript
networkInterfaces?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```


Networks to attach to the instance. This can
be specified multiple times. Structure is documented below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L338">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L343">property scheduling</a>
</h3>

```typescript
scheduling?: pulumi.Input<{ ... }>;
```


The scheduling strategy to use. More details about
this configuration option are detailed below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L348">property scratchDisks</a>
</h3>

```typescript
scratchDisks?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```


Scratch disks to attach to the instance. This can be
specified multiple times for multiple scratch disks. Structure is documented below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L352">property selfLink</a>
</h3>

```typescript
selfLink?: pulumi.Input<string>;
```


The URI of the created resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L358">property serviceAccount</a>
</h3>

```typescript
serviceAccount?: pulumi.Input<{ ... }>;
```


Service account to attach to the instance.
Structure is documented below.
**Note**: [`allow_stopping_for_update`](#allow_stopping_for_update) must be set to true in order to update this field.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L362">property tags</a>
</h3>

```typescript
tags?: pulumi.Input<pulumi.Input<string>[]>;
```


A list of tags to attach to the instance.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L366">property tagsFingerprint</a>
</h3>

```typescript
tagsFingerprint?: pulumi.Input<string>;
```


The unique fingerprint of the tags.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instance.ts#L370">property zone</a>
</h3>

```typescript
zone?: pulumi.Input<string>;
```


The zone that the machine should be created in.

<h2 class="pdoc-module-header" id="InstanceTemplateArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceTemplate.ts#L313">interface InstanceTemplateArgs</a>
</h2>

The set of arguments for constructing a InstanceTemplate resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceTemplate.ts#L318">property canIpForward</a>
</h3>

```typescript
canIpForward?: pulumi.Input<boolean>;
```


Whether to allow sending and receiving of
packets with non-matching source or destination IPs. This defaults to false.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceTemplate.ts#L322">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```


A brief description of this resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceTemplate.ts#L328">property disks</a>
</h3>

```typescript
disks: pulumi.Input<pulumi.Input<{ ... }>[]>;
```


Disks to attach to instances created from this template.
This can be specified multiple times for multiple disks. Structure is
documented below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceTemplate.ts#L332">property guestAccelerators</a>
</h3>

```typescript
guestAccelerators?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```


List of the type and count of accelerator cards attached to the instance. Structure documented below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceTemplate.ts#L337">property instanceDescription</a>
</h3>

```typescript
instanceDescription?: pulumi.Input<string>;
```


A brief description to use for instances
created from this template.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceTemplate.ts#L342">property labels</a>
</h3>

```typescript
labels?: pulumi.Input<{ ... }>;
```


A set of key/value label pairs to assign to instances
created from this template,

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceTemplate.ts#L346">property machineType</a>
</h3>

```typescript
machineType: pulumi.Input<string>;
```


The machine type to create.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceTemplate.ts#L351">property metadata</a>
</h3>

```typescript
metadata?: pulumi.Input<{ ... }>;
```


Metadata key/value pairs to make available from
within instances created from this template.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceTemplate.ts#L358">property metadataStartupScript</a>
</h3>

```typescript
metadataStartupScript?: pulumi.Input<string>;
```


An alternative to using the
startup-script metadata key, mostly to match the compute_instance resource.
This replaces the startup-script metadata key on the created instance and
thus the two mechanisms are not allowed to be used simultaneously.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceTemplate.ts#L363">property minCpuPlatform</a>
</h3>

```typescript
minCpuPlatform?: pulumi.Input<string>;
```


Specifies a minimum CPU platform. Applicable values are the friendly names of CPU platforms, such as
`Intel Haswell` or `Intel Skylake`. See the complete list [here](https://cloud.google.com/compute/docs/instances/specify-min-cpu-platform).

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceTemplate.ts#L368">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


The name of the instance template. If you leave
this blank, Terraform will auto-generate a unique name.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceTemplate.ts#L373">property namePrefix</a>
</h3>

```typescript
namePrefix?: pulumi.Input<string>;
```


Creates a unique name beginning with the specified
prefix. Conflicts with `name`.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceTemplate.ts#L379">property networkInterfaces</a>
</h3>

```typescript
networkInterfaces?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```


Networks to attach to instances created from
this template. This can be specified multiple times for multiple networks.
Structure is documented below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceTemplate.ts#L384">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceTemplate.ts#L393">property region</a>
</h3>

```typescript
region?: pulumi.Input<string>;
```


An instance template is a global resource that is not
bound to a zone or a region. However, you can still specify some regional
resources in an instance template, which restricts the template to the
region where that resource resides. For example, a custom `subnetwork`
resource is tied to a specific region. Defaults to the region of the
Provider if no value is given.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceTemplate.ts#L398">property schedulings</a>
</h3>

```typescript
schedulings?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```


The scheduling strategy to use. More details about
this configuration option are detailed below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceTemplate.ts#L402">property serviceAccount</a>
</h3>

```typescript
serviceAccount?: pulumi.Input<{ ... }>;
```


Service account to attach to the instance. Structure is documented below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceTemplate.ts#L406">property tags</a>
</h3>

```typescript
tags?: pulumi.Input<pulumi.Input<string>[]>;
```


Tags to attach to the instance.

<h2 class="pdoc-module-header" id="InstanceTemplateState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceTemplate.ts#L202">interface InstanceTemplateState</a>
</h2>

Input properties used for looking up and filtering InstanceTemplate resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceTemplate.ts#L207">property canIpForward</a>
</h3>

```typescript
canIpForward?: pulumi.Input<boolean>;
```


Whether to allow sending and receiving of
packets with non-matching source or destination IPs. This defaults to false.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceTemplate.ts#L211">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```


A brief description of this resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceTemplate.ts#L217">property disks</a>
</h3>

```typescript
disks?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```


Disks to attach to instances created from this template.
This can be specified multiple times for multiple disks. Structure is
documented below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceTemplate.ts#L221">property guestAccelerators</a>
</h3>

```typescript
guestAccelerators?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```


List of the type and count of accelerator cards attached to the instance. Structure documented below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceTemplate.ts#L226">property instanceDescription</a>
</h3>

```typescript
instanceDescription?: pulumi.Input<string>;
```


A brief description to use for instances
created from this template.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceTemplate.ts#L231">property labels</a>
</h3>

```typescript
labels?: pulumi.Input<{ ... }>;
```


A set of key/value label pairs to assign to instances
created from this template,

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceTemplate.ts#L235">property machineType</a>
</h3>

```typescript
machineType?: pulumi.Input<string>;
```


The machine type to create.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceTemplate.ts#L240">property metadata</a>
</h3>

```typescript
metadata?: pulumi.Input<{ ... }>;
```


Metadata key/value pairs to make available from
within instances created from this template.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceTemplate.ts#L244">property metadataFingerprint</a>
</h3>

```typescript
metadataFingerprint?: pulumi.Input<string>;
```


The unique fingerprint of the metadata.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceTemplate.ts#L251">property metadataStartupScript</a>
</h3>

```typescript
metadataStartupScript?: pulumi.Input<string>;
```


An alternative to using the
startup-script metadata key, mostly to match the compute_instance resource.
This replaces the startup-script metadata key on the created instance and
thus the two mechanisms are not allowed to be used simultaneously.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceTemplate.ts#L256">property minCpuPlatform</a>
</h3>

```typescript
minCpuPlatform?: pulumi.Input<string>;
```


Specifies a minimum CPU platform. Applicable values are the friendly names of CPU platforms, such as
`Intel Haswell` or `Intel Skylake`. See the complete list [here](https://cloud.google.com/compute/docs/instances/specify-min-cpu-platform).

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceTemplate.ts#L261">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


The name of the instance template. If you leave
this blank, Terraform will auto-generate a unique name.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceTemplate.ts#L266">property namePrefix</a>
</h3>

```typescript
namePrefix?: pulumi.Input<string>;
```


Creates a unique name beginning with the specified
prefix. Conflicts with `name`.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceTemplate.ts#L272">property networkInterfaces</a>
</h3>

```typescript
networkInterfaces?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```


Networks to attach to instances created from
this template. This can be specified multiple times for multiple networks.
Structure is documented below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceTemplate.ts#L277">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceTemplate.ts#L286">property region</a>
</h3>

```typescript
region?: pulumi.Input<string>;
```


An instance template is a global resource that is not
bound to a zone or a region. However, you can still specify some regional
resources in an instance template, which restricts the template to the
region where that resource resides. For example, a custom `subnetwork`
resource is tied to a specific region. Defaults to the region of the
Provider if no value is given.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceTemplate.ts#L291">property schedulings</a>
</h3>

```typescript
schedulings?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```


The scheduling strategy to use. More details about
this configuration option are detailed below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceTemplate.ts#L295">property selfLink</a>
</h3>

```typescript
selfLink?: pulumi.Input<string>;
```


The URI of the created resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceTemplate.ts#L299">property serviceAccount</a>
</h3>

```typescript
serviceAccount?: pulumi.Input<{ ... }>;
```


Service account to attach to the instance. Structure is documented below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceTemplate.ts#L303">property tags</a>
</h3>

```typescript
tags?: pulumi.Input<pulumi.Input<string>[]>;
```


Tags to attach to the instance.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/instanceTemplate.ts#L307">property tagsFingerprint</a>
</h3>

```typescript
tagsFingerprint?: pulumi.Input<string>;
```


The unique fingerprint of the tags.

<h2 class="pdoc-module-header" id="NetworkArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/network.ts#L154">interface NetworkArgs</a>
</h2>

The set of arguments for constructing a Network resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/network.ts#L161">property autoCreateSubnetworks</a>
</h3>

```typescript
autoCreateSubnetworks?: pulumi.Input<boolean>;
```


If set to true, this network will be
created in auto subnet mode, and Google will create a subnet for each region
automatically. If set to false, a custom subnetted network will be created that
can support `google_compute_subnetwork` resources. Defaults to true.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/network.ts#L165">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```


A brief description of this resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/network.ts#L171">property ipv4Range</a>
</h3>

```typescript
ipv4Range?: pulumi.Input<string>;
```


If set to a CIDR block, uses the legacy VPC API with the
specified range. This API is deprecated. If set, `auto_create_subnetworks` must be
explicitly set to false.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/network.ts#L176">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


A unique name for the resource, required by GCE.
Changing this forces a new resource to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/network.ts#L181">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/network.ts#L188">property routingMode</a>
</h3>

```typescript
routingMode?: pulumi.Input<string>;
```


Sets the network-wide routing mode for Cloud Routers
to use. Accepted values are `"GLOBAL"` or `"REGIONAL"`. Defaults to `"REGIONAL"`.
Refer to the [Cloud Router documentation](https://cloud.google.com/router/docs/concepts/overview#dynamic-routing-mode)
for more details.

<h2 class="pdoc-module-header" id="NetworkPeeringArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/networkPeering.ts#L126">interface NetworkPeeringArgs</a>
</h2>

The set of arguments for constructing a NetworkPeering resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/networkPeering.ts#L131">property autoCreateRoutes</a>
</h3>

```typescript
autoCreateRoutes?: pulumi.Input<boolean>;
```


If set to `true`, the routes between the two networks will
be created and managed automatically. Defaults to `true`.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/networkPeering.ts#L135">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


Name of the peering.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/networkPeering.ts#L139">property network</a>
</h3>

```typescript
network: pulumi.Input<string>;
```


Resource link of the network to add a peering to.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/networkPeering.ts#L143">property peerNetwork</a>
</h3>

```typescript
peerNetwork: pulumi.Input<string>;
```


Resource link of the peer network.

<h2 class="pdoc-module-header" id="NetworkPeeringState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/networkPeering.ts#L95">interface NetworkPeeringState</a>
</h2>

Input properties used for looking up and filtering NetworkPeering resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/networkPeering.ts#L100">property autoCreateRoutes</a>
</h3>

```typescript
autoCreateRoutes?: pulumi.Input<boolean>;
```


If set to `true`, the routes between the two networks will
be created and managed automatically. Defaults to `true`.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/networkPeering.ts#L104">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


Name of the peering.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/networkPeering.ts#L108">property network</a>
</h3>

```typescript
network?: pulumi.Input<string>;
```


Resource link of the network to add a peering to.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/networkPeering.ts#L112">property peerNetwork</a>
</h3>

```typescript
peerNetwork?: pulumi.Input<string>;
```


Resource link of the peer network.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/networkPeering.ts#L116">property state</a>
</h3>

```typescript
state?: pulumi.Input<string>;
```


State for the peering.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/networkPeering.ts#L120">property stateDetails</a>
</h3>

```typescript
stateDetails?: pulumi.Input<string>;
```


Details about the current state of the peering.

<h2 class="pdoc-module-header" id="NetworkState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/network.ts#L106">interface NetworkState</a>
</h2>

Input properties used for looking up and filtering Network resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/network.ts#L113">property autoCreateSubnetworks</a>
</h3>

```typescript
autoCreateSubnetworks?: pulumi.Input<boolean>;
```


If set to true, this network will be
created in auto subnet mode, and Google will create a subnet for each region
automatically. If set to false, a custom subnetted network will be created that
can support `google_compute_subnetwork` resources. Defaults to true.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/network.ts#L117">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```


A brief description of this resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/network.ts#L121">property gatewayIpv4</a>
</h3>

```typescript
gatewayIpv4?: pulumi.Input<string>;
```


The IPv4 address of the gateway.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/network.ts#L127">property ipv4Range</a>
</h3>

```typescript
ipv4Range?: pulumi.Input<string>;
```


If set to a CIDR block, uses the legacy VPC API with the
specified range. This API is deprecated. If set, `auto_create_subnetworks` must be
explicitly set to false.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/network.ts#L132">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


A unique name for the resource, required by GCE.
Changing this forces a new resource to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/network.ts#L137">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/network.ts#L144">property routingMode</a>
</h3>

```typescript
routingMode?: pulumi.Input<string>;
```


Sets the network-wide routing mode for Cloud Routers
to use. Accepted values are `"GLOBAL"` or `"REGIONAL"`. Defaults to `"REGIONAL"`.
Refer to the [Cloud Router documentation](https://cloud.google.com/router/docs/concepts/overview#dynamic-routing-mode)
for more details.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/network.ts#L148">property selfLink</a>
</h3>

```typescript
selfLink?: pulumi.Input<string>;
```


The URI of the created resource.

<h2 class="pdoc-module-header" id="ProjectMetadataArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/projectMetadata.ts#L85">interface ProjectMetadataArgs</a>
</h2>

The set of arguments for constructing a ProjectMetadata resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/projectMetadata.ts#L90">property metadata</a>
</h3>

```typescript
metadata: pulumi.Input<{ ... }>;
```


A series of key value pairs. Changing this resource
updates the GCE state.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/projectMetadata.ts#L95">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs. If it
is not provided, the provider project is used.

<h2 class="pdoc-module-header" id="ProjectMetadataItemArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/projectMetadataItem.ts#L92">interface ProjectMetadataItemArgs</a>
</h2>

The set of arguments for constructing a ProjectMetadataItem resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/projectMetadataItem.ts#L96">property key</a>
</h3>

```typescript
key: pulumi.Input<string>;
```


The metadata key to set.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/projectMetadataItem.ts#L101">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/projectMetadataItem.ts#L105">property value</a>
</h3>

```typescript
value: pulumi.Input<string>;
```


The value to set for the given metadata key.

<h2 class="pdoc-module-header" id="ProjectMetadataItemState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/projectMetadataItem.ts#L73">interface ProjectMetadataItemState</a>
</h2>

Input properties used for looking up and filtering ProjectMetadataItem resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/projectMetadataItem.ts#L77">property key</a>
</h3>

```typescript
key?: pulumi.Input<string>;
```


The metadata key to set.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/projectMetadataItem.ts#L82">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/projectMetadataItem.ts#L86">property value</a>
</h3>

```typescript
value?: pulumi.Input<string>;
```


The value to set for the given metadata key.

<h2 class="pdoc-module-header" id="ProjectMetadataState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/projectMetadata.ts#L69">interface ProjectMetadataState</a>
</h2>

Input properties used for looking up and filtering ProjectMetadata resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/projectMetadata.ts#L74">property metadata</a>
</h3>

```typescript
metadata?: pulumi.Input<{ ... }>;
```


A series of key value pairs. Changing this resource
updates the GCE state.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/projectMetadata.ts#L79">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs. If it
is not provided, the provider project is used.

<h2 class="pdoc-module-header" id="RegionAutoscalerArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionAutoscaler.ts#L100">interface RegionAutoscalerArgs</a>
</h2>

The set of arguments for constructing a RegionAutoscaler resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionAutoscaler.ts#L101">property autoscalingPolicy</a>
</h3>

```typescript
autoscalingPolicy: pulumi.Input<{ ... }>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionAutoscaler.ts#L102">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionAutoscaler.ts#L103">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionAutoscaler.ts#L108">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionAutoscaler.ts#L109">property region</a>
</h3>

```typescript
region?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionAutoscaler.ts#L110">property target</a>
</h3>

```typescript
target: pulumi.Input<string>;
```

<h2 class="pdoc-module-header" id="RegionAutoscalerState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionAutoscaler.ts#L79">interface RegionAutoscalerState</a>
</h2>

Input properties used for looking up and filtering RegionAutoscaler resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionAutoscaler.ts#L80">property autoscalingPolicy</a>
</h3>

```typescript
autoscalingPolicy?: pulumi.Input<{ ... }>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionAutoscaler.ts#L81">property creationTimestamp</a>
</h3>

```typescript
creationTimestamp?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionAutoscaler.ts#L82">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionAutoscaler.ts#L83">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionAutoscaler.ts#L88">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionAutoscaler.ts#L89">property region</a>
</h3>

```typescript
region?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionAutoscaler.ts#L93">property selfLink</a>
</h3>

```typescript
selfLink?: pulumi.Input<string>;
```


The URI of the created resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionAutoscaler.ts#L94">property target</a>
</h3>

```typescript
target?: pulumi.Input<string>;
```

<h2 class="pdoc-module-header" id="RegionBackendServiceArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionBackendService.ts#L199">interface RegionBackendServiceArgs</a>
</h2>

The set of arguments for constructing a RegionBackendService resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionBackendService.ts#L204">property backends</a>
</h3>

```typescript
backends?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```


The list of backends that serve this BackendService.
Structure is documented below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionBackendService.ts#L209">property connectionDrainingTimeoutSec</a>
</h3>

```typescript
connectionDrainingTimeoutSec?: pulumi.Input<number>;
```


Time for which instance will be drained
(not accept new connections, but still work to finish started ones). Defaults to `0`.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionBackendService.ts#L213">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```


Textual description for the backend.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionBackendService.ts#L219">property healthChecks</a>
</h3>

```typescript
healthChecks: pulumi.Input<string>;
```


Specifies a list of health checks
for checking the health of the backend service. Currently at most
one health check can be specified, and a health check is required.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionBackendService.ts#L223">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


The name of the backend service.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionBackendService.ts#L228">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionBackendService.ts#L233">property protocol</a>
</h3>

```typescript
protocol?: pulumi.Input<string>;
```


The protocol for incoming requests. Defaults to
`TCP`.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionBackendService.ts#L238">property region</a>
</h3>

```typescript
region?: pulumi.Input<string>;
```


The Region in which the created address should reside.
If it is not provided, the provider region is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionBackendService.ts#L244">property sessionAffinity</a>
</h3>

```typescript
sessionAffinity?: pulumi.Input<string>;
```


How to distribute load. Options are `NONE` (no
affinity), `CLIENT_IP`, `CLIENT_IP_PROTO`, or `CLIENT_IP_PORT_PROTO`.
Defaults to `NONE`.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionBackendService.ts#L249">property timeoutSec</a>
</h3>

```typescript
timeoutSec?: pulumi.Input<number>;
```


The number of secs to wait for a backend to respond
to a request before considering the request failed. Defaults to `30`.

<h2 class="pdoc-module-header" id="RegionBackendServiceState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionBackendService.ts#L135">interface RegionBackendServiceState</a>
</h2>

Input properties used for looking up and filtering RegionBackendService resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionBackendService.ts#L140">property backends</a>
</h3>

```typescript
backends?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```


The list of backends that serve this BackendService.
Structure is documented below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionBackendService.ts#L145">property connectionDrainingTimeoutSec</a>
</h3>

```typescript
connectionDrainingTimeoutSec?: pulumi.Input<number>;
```


Time for which instance will be drained
(not accept new connections, but still work to finish started ones). Defaults to `0`.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionBackendService.ts#L149">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```


Textual description for the backend.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionBackendService.ts#L153">property fingerprint</a>
</h3>

```typescript
fingerprint?: pulumi.Input<string>;
```


The fingerprint of the backend service.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionBackendService.ts#L159">property healthChecks</a>
</h3>

```typescript
healthChecks?: pulumi.Input<string>;
```


Specifies a list of health checks
for checking the health of the backend service. Currently at most
one health check can be specified, and a health check is required.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionBackendService.ts#L163">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


The name of the backend service.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionBackendService.ts#L168">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionBackendService.ts#L173">property protocol</a>
</h3>

```typescript
protocol?: pulumi.Input<string>;
```


The protocol for incoming requests. Defaults to
`TCP`.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionBackendService.ts#L178">property region</a>
</h3>

```typescript
region?: pulumi.Input<string>;
```


The Region in which the created address should reside.
If it is not provided, the provider region is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionBackendService.ts#L182">property selfLink</a>
</h3>

```typescript
selfLink?: pulumi.Input<string>;
```


The URI of the created resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionBackendService.ts#L188">property sessionAffinity</a>
</h3>

```typescript
sessionAffinity?: pulumi.Input<string>;
```


How to distribute load. Options are `NONE` (no
affinity), `CLIENT_IP`, `CLIENT_IP_PROTO`, or `CLIENT_IP_PORT_PROTO`.
Defaults to `NONE`.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionBackendService.ts#L193">property timeoutSec</a>
</h3>

```typescript
timeoutSec?: pulumi.Input<number>;
```


The number of secs to wait for a backend to respond
to a request before considering the request failed. Defaults to `30`.

<h2 class="pdoc-module-header" id="RegionInstanceGroupManagerArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionInstanceGroupManager.ts#L279">interface RegionInstanceGroupManagerArgs</a>
</h2>

The set of arguments for constructing a RegionInstanceGroupManager resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionInstanceGroupManager.ts#L284">property autoHealingPolicies</a>
</h3>

```typescript
autoHealingPolicies?: pulumi.Input<{ ... }>;
```


) The autohealing policies for this managed instance
group. You can specify only one value. Structure is documented below. For more information, see the [official documentation](https://cloud.google.com/compute/docs/instance-groups/creating-groups-of-managed-instances#monitoring_groups).

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionInstanceGroupManager.ts#L293">property baseInstanceName</a>
</h3>

```typescript
baseInstanceName: pulumi.Input<string>;
```


The base instance name to use for
instances in this group. The value must be a valid
[RFC1035](https://www.ietf.org/rfc/rfc1035.txt) name. Supported characters
are lowercase letters, numbers, and hyphens (-). Instances are named by
appending a hyphen and a random four-character string to the base instance
name.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionInstanceGroupManager.ts#L298">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```


An optional textual description of the instance
group manager.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionInstanceGroupManager.ts#L304">property distributionPolicyZones</a>
</h3>

```typescript
distributionPolicyZones?: pulumi.Input<pulumi.Input<string>[]>;
```


) The distribution policy for this managed instance
group. You can specify one or more values. For more information, see the [official documentation](https://cloud.google.com/compute/docs/instance-groups/distributing-instances-with-regional-instance-groups#selectingzones).
- - -

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionInstanceGroupManager.ts#L309">property instanceTemplate</a>
</h3>

```typescript
instanceTemplate: pulumi.Input<string>;
```


The full URL to an instance template from
which all new instances will be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionInstanceGroupManager.ts#L313">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


The name of the port.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionInstanceGroupManager.ts#L318">property namedPorts</a>
</h3>

```typescript
namedPorts?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```


The named port configuration. See the section below
for details on configuration.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionInstanceGroupManager.ts#L323">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionInstanceGroupManager.ts#L327">property region</a>
</h3>

```typescript
region: pulumi.Input<string>;
```


The region where the managed instance group resides.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionInstanceGroupManager.ts#L331">property rollingUpdatePolicy</a>
</h3>

```typescript
rollingUpdatePolicy?: pulumi.Input<{ ... }>;
```


) The update policy for this managed instance group. Structure is documented below. For more information, see the [official documentation](https://cloud.google.com/compute/docs/instance-groups/updating-managed-instance-groups) and [API](https://cloud.google.com/compute/docs/reference/rest/beta/regionInstanceGroupManagers/patch)

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionInstanceGroupManager.ts#L337">property targetPools</a>
</h3>

```typescript
targetPools?: pulumi.Input<pulumi.Input<string>[]>;
```


The full URL of all target pools to which new
instances in the group are added. Updating the target pools attribute does
not affect existing instances.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionInstanceGroupManager.ts#L343">property targetSize</a>
</h3>

```typescript
targetSize?: pulumi.Input<number>;
```


The target number of running instances for this managed
instance group. This value should always be explicitly set unless this resource is attached to
an autoscaler, in which case it should never be set. Defaults to `0`.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionInstanceGroupManager.ts#L351">property updateStrategy</a>
</h3>

```typescript
updateStrategy?: pulumi.Input<string>;
```


If the `instance_template`
resource is modified, a value of `"NONE"` will prevent any of the managed
instances from being restarted by Terraform. A value of `"ROLLING_UPDATE"`
is supported as [Beta feature]. A value of `"ROLLING_UPDATE"` requires
`rolling_update_policy` block to be set

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionInstanceGroupManager.ts#L357">property waitForInstances</a>
</h3>

```typescript
waitForInstances?: pulumi.Input<boolean>;
```


Whether to wait for all instances to be created/updated before
returning. Note that if this is set to true and the operation does not succeed, Terraform will
continue trying until it times out.

<h2 class="pdoc-module-header" id="RegionInstanceGroupManagerState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionInstanceGroupManager.ts#L183">interface RegionInstanceGroupManagerState</a>
</h2>

Input properties used for looking up and filtering RegionInstanceGroupManager resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionInstanceGroupManager.ts#L188">property autoHealingPolicies</a>
</h3>

```typescript
autoHealingPolicies?: pulumi.Input<{ ... }>;
```


) The autohealing policies for this managed instance
group. You can specify only one value. Structure is documented below. For more information, see the [official documentation](https://cloud.google.com/compute/docs/instance-groups/creating-groups-of-managed-instances#monitoring_groups).

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionInstanceGroupManager.ts#L197">property baseInstanceName</a>
</h3>

```typescript
baseInstanceName?: pulumi.Input<string>;
```


The base instance name to use for
instances in this group. The value must be a valid
[RFC1035](https://www.ietf.org/rfc/rfc1035.txt) name. Supported characters
are lowercase letters, numbers, and hyphens (-). Instances are named by
appending a hyphen and a random four-character string to the base instance
name.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionInstanceGroupManager.ts#L202">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```


An optional textual description of the instance
group manager.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionInstanceGroupManager.ts#L208">property distributionPolicyZones</a>
</h3>

```typescript
distributionPolicyZones?: pulumi.Input<pulumi.Input<string>[]>;
```


) The distribution policy for this managed instance
group. You can specify one or more values. For more information, see the [official documentation](https://cloud.google.com/compute/docs/instance-groups/distributing-instances-with-regional-instance-groups#selectingzones).
- - -

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionInstanceGroupManager.ts#L212">property fingerprint</a>
</h3>

```typescript
fingerprint?: pulumi.Input<string>;
```


The fingerprint of the instance group manager.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionInstanceGroupManager.ts#L216">property instanceGroup</a>
</h3>

```typescript
instanceGroup?: pulumi.Input<string>;
```


The full URL of the instance group created by the manager.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionInstanceGroupManager.ts#L221">property instanceTemplate</a>
</h3>

```typescript
instanceTemplate?: pulumi.Input<string>;
```


The full URL to an instance template from
which all new instances will be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionInstanceGroupManager.ts#L225">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


The name of the port.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionInstanceGroupManager.ts#L230">property namedPorts</a>
</h3>

```typescript
namedPorts?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```


The named port configuration. See the section below
for details on configuration.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionInstanceGroupManager.ts#L235">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionInstanceGroupManager.ts#L239">property region</a>
</h3>

```typescript
region?: pulumi.Input<string>;
```


The region where the managed instance group resides.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionInstanceGroupManager.ts#L243">property rollingUpdatePolicy</a>
</h3>

```typescript
rollingUpdatePolicy?: pulumi.Input<{ ... }>;
```


) The update policy for this managed instance group. Structure is documented below. For more information, see the [official documentation](https://cloud.google.com/compute/docs/instance-groups/updating-managed-instance-groups) and [API](https://cloud.google.com/compute/docs/reference/rest/beta/regionInstanceGroupManagers/patch)

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionInstanceGroupManager.ts#L247">property selfLink</a>
</h3>

```typescript
selfLink?: pulumi.Input<string>;
```


The URL of the created resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionInstanceGroupManager.ts#L253">property targetPools</a>
</h3>

```typescript
targetPools?: pulumi.Input<pulumi.Input<string>[]>;
```


The full URL of all target pools to which new
instances in the group are added. Updating the target pools attribute does
not affect existing instances.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionInstanceGroupManager.ts#L259">property targetSize</a>
</h3>

```typescript
targetSize?: pulumi.Input<number>;
```


The target number of running instances for this managed
instance group. This value should always be explicitly set unless this resource is attached to
an autoscaler, in which case it should never be set. Defaults to `0`.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionInstanceGroupManager.ts#L267">property updateStrategy</a>
</h3>

```typescript
updateStrategy?: pulumi.Input<string>;
```


If the `instance_template`
resource is modified, a value of `"NONE"` will prevent any of the managed
instances from being restarted by Terraform. A value of `"ROLLING_UPDATE"`
is supported as [Beta feature]. A value of `"ROLLING_UPDATE"` requires
`rolling_update_policy` block to be set

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/regionInstanceGroupManager.ts#L273">property waitForInstances</a>
</h3>

```typescript
waitForInstances?: pulumi.Input<boolean>;
```


Whether to wait for all instances to be created/updated before
returning. Note that if this is set to true and the operation does not succeed, Terraform will
continue trying until it times out.

<h2 class="pdoc-module-header" id="RouteArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/route.ts#L136">interface RouteArgs</a>
</h2>

The set of arguments for constructing a Route resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/route.ts#L137">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/route.ts#L138">property destRange</a>
</h3>

```typescript
destRange: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/route.ts#L139">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/route.ts#L140">property network</a>
</h3>

```typescript
network: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/route.ts#L141">property nextHopGateway</a>
</h3>

```typescript
nextHopGateway?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/route.ts#L142">property nextHopInstance</a>
</h3>

```typescript
nextHopInstance?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/route.ts#L149">property nextHopInstanceZone</a>
</h3>

```typescript
nextHopInstanceZone?: pulumi.Input<string>;
```


(Optional when `next_hop_instance` is
specified)  The zone of the instance specified in
`next_hop_instance`.  Omit if `next_hop_instance` is specified as
a URL.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/route.ts#L150">property nextHopIp</a>
</h3>

```typescript
nextHopIp?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/route.ts#L151">property nextHopVpnTunnel</a>
</h3>

```typescript
nextHopVpnTunnel?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/route.ts#L152">property priority</a>
</h3>

```typescript
priority?: pulumi.Input<number>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/route.ts#L157">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/route.ts#L158">property tags</a>
</h3>

```typescript
tags?: pulumi.Input<pulumi.Input<string>[]>;
```

<h2 class="pdoc-module-header" id="RouteState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/route.ts#L103">interface RouteState</a>
</h2>

Input properties used for looking up and filtering Route resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/route.ts#L104">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/route.ts#L105">property destRange</a>
</h3>

```typescript
destRange?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/route.ts#L106">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/route.ts#L107">property network</a>
</h3>

```typescript
network?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/route.ts#L108">property nextHopGateway</a>
</h3>

```typescript
nextHopGateway?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/route.ts#L109">property nextHopInstance</a>
</h3>

```typescript
nextHopInstance?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/route.ts#L116">property nextHopInstanceZone</a>
</h3>

```typescript
nextHopInstanceZone?: pulumi.Input<string>;
```


(Optional when `next_hop_instance` is
specified)  The zone of the instance specified in
`next_hop_instance`.  Omit if `next_hop_instance` is specified as
a URL.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/route.ts#L117">property nextHopIp</a>
</h3>

```typescript
nextHopIp?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/route.ts#L118">property nextHopNetwork</a>
</h3>

```typescript
nextHopNetwork?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/route.ts#L119">property nextHopVpnTunnel</a>
</h3>

```typescript
nextHopVpnTunnel?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/route.ts#L120">property priority</a>
</h3>

```typescript
priority?: pulumi.Input<number>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/route.ts#L125">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/route.ts#L129">property selfLink</a>
</h3>

```typescript
selfLink?: pulumi.Input<string>;
```


The URI of the created resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/route.ts#L130">property tags</a>
</h3>

```typescript
tags?: pulumi.Input<pulumi.Input<string>[]>;
```

<h2 class="pdoc-module-header" id="RouterArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/router.ts#L97">interface RouterArgs</a>
</h2>

The set of arguments for constructing a Router resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/router.ts#L98">property bgp</a>
</h3>

```typescript
bgp?: pulumi.Input<{ ... }>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/router.ts#L99">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/router.ts#L100">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/router.ts#L101">property network</a>
</h3>

```typescript
network: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/router.ts#L106">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/router.ts#L107">property region</a>
</h3>

```typescript
region?: pulumi.Input<string>;
```

<h2 class="pdoc-module-header" id="RouterInterfaceArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/routerInterface.ts#L134">interface RouterInterfaceArgs</a>
</h2>

The set of arguments for constructing a RouterInterface resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/routerInterface.ts#L139">property ipRange</a>
</h3>

```typescript
ipRange?: pulumi.Input<string>;
```


IP address and range of the interface. The IP range must be
in the RFC3927 link-local IP space. Changing this forces a new interface to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/routerInterface.ts#L144">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


A unique name for the interface, required by GCE. Changing
this forces a new interface to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/routerInterface.ts#L149">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which this interface's router belongs. If it
is not provided, the provider project is used. Changing this forces a new interface to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/routerInterface.ts#L155">property region</a>
</h3>

```typescript
region?: pulumi.Input<string>;
```


The region this interface's router sits in. If not specified,
the project region will be used. Changing this forces a new interface to be
created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/routerInterface.ts#L160">property router</a>
</h3>

```typescript
router: pulumi.Input<string>;
```


The name of the router this interface will be attached to.
Changing this forces a new interface to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/routerInterface.ts#L165">property vpnTunnel</a>
</h3>

```typescript
vpnTunnel: pulumi.Input<string>;
```


The name or resource link to the VPN tunnel this
interface will be linked to. Changing this forces a new interface to be created.

<h2 class="pdoc-module-header" id="RouterInterfaceState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/routerInterface.ts#L97">interface RouterInterfaceState</a>
</h2>

Input properties used for looking up and filtering RouterInterface resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/routerInterface.ts#L102">property ipRange</a>
</h3>

```typescript
ipRange?: pulumi.Input<string>;
```


IP address and range of the interface. The IP range must be
in the RFC3927 link-local IP space. Changing this forces a new interface to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/routerInterface.ts#L107">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


A unique name for the interface, required by GCE. Changing
this forces a new interface to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/routerInterface.ts#L112">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which this interface's router belongs. If it
is not provided, the provider project is used. Changing this forces a new interface to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/routerInterface.ts#L118">property region</a>
</h3>

```typescript
region?: pulumi.Input<string>;
```


The region this interface's router sits in. If not specified,
the project region will be used. Changing this forces a new interface to be
created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/routerInterface.ts#L123">property router</a>
</h3>

```typescript
router?: pulumi.Input<string>;
```


The name of the router this interface will be attached to.
Changing this forces a new interface to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/routerInterface.ts#L128">property vpnTunnel</a>
</h3>

```typescript
vpnTunnel?: pulumi.Input<string>;
```


The name or resource link to the VPN tunnel this
interface will be linked to. Changing this forces a new interface to be created.

<h2 class="pdoc-module-header" id="RouterPeerArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/routerPeer.ts#L171">interface RouterPeerArgs</a>
</h2>

The set of arguments for constructing a RouterPeer resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/routerPeer.ts#L176">property advertisedRoutePriority</a>
</h3>

```typescript
advertisedRoutePriority?: pulumi.Input<number>;
```


The priority of routes advertised to this BGP peer.
Changing this forces a new peer to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/routerPeer.ts#L181">property interface</a>
</h3>

```typescript
interface: pulumi.Input<string>;
```


The name of the interface the BGP peer is associated with.
Changing this forces a new peer to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/routerPeer.ts#L186">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


A unique name for BGP peer, required by GCE. Changing
this forces a new peer to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/routerPeer.ts#L191">property peerAsn</a>
</h3>

```typescript
peerAsn: pulumi.Input<number>;
```


Peer BGP Autonomous System Number (ASN).
Changing this forces a new peer to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/routerPeer.ts#L196">property peerIpAddress</a>
</h3>

```typescript
peerIpAddress?: pulumi.Input<string>;
```


IP address of the BGP interface outside Google Cloud.
Changing this forces a new peer to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/routerPeer.ts#L201">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which this peer's router belongs. If it
is not provided, the provider project is used. Changing this forces a new peer to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/routerPeer.ts#L207">property region</a>
</h3>

```typescript
region?: pulumi.Input<string>;
```


The region this peer's router sits in. If not specified,
the project region will be used. Changing this forces a new peer to be
created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/routerPeer.ts#L212">property router</a>
</h3>

```typescript
router: pulumi.Input<string>;
```


The name of the router in which this BGP peer will be configured.
Changing this forces a new peer to be created.

<h2 class="pdoc-module-header" id="RouterPeerState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/routerPeer.ts#L120">interface RouterPeerState</a>
</h2>

Input properties used for looking up and filtering RouterPeer resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/routerPeer.ts#L125">property advertisedRoutePriority</a>
</h3>

```typescript
advertisedRoutePriority?: pulumi.Input<number>;
```


The priority of routes advertised to this BGP peer.
Changing this forces a new peer to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/routerPeer.ts#L130">property interface</a>
</h3>

```typescript
interface?: pulumi.Input<string>;
```


The name of the interface the BGP peer is associated with.
Changing this forces a new peer to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/routerPeer.ts#L134">property ipAddress</a>
</h3>

```typescript
ipAddress?: pulumi.Input<string>;
```


IP address of the interface inside Google Cloud Platform.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/routerPeer.ts#L139">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


A unique name for BGP peer, required by GCE. Changing
this forces a new peer to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/routerPeer.ts#L144">property peerAsn</a>
</h3>

```typescript
peerAsn?: pulumi.Input<number>;
```


Peer BGP Autonomous System Number (ASN).
Changing this forces a new peer to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/routerPeer.ts#L149">property peerIpAddress</a>
</h3>

```typescript
peerIpAddress?: pulumi.Input<string>;
```


IP address of the BGP interface outside Google Cloud.
Changing this forces a new peer to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/routerPeer.ts#L154">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which this peer's router belongs. If it
is not provided, the provider project is used. Changing this forces a new peer to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/routerPeer.ts#L160">property region</a>
</h3>

```typescript
region?: pulumi.Input<string>;
```


The region this peer's router sits in. If not specified,
the project region will be used. Changing this forces a new peer to be
created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/routerPeer.ts#L165">property router</a>
</h3>

```typescript
router?: pulumi.Input<string>;
```


The name of the router in which this BGP peer will be configured.
Changing this forces a new peer to be created.

<h2 class="pdoc-module-header" id="RouterState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/router.ts#L76">interface RouterState</a>
</h2>

Input properties used for looking up and filtering Router resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/router.ts#L77">property bgp</a>
</h3>

```typescript
bgp?: pulumi.Input<{ ... }>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/router.ts#L78">property creationTimestamp</a>
</h3>

```typescript
creationTimestamp?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/router.ts#L79">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/router.ts#L80">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/router.ts#L81">property network</a>
</h3>

```typescript
network?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/router.ts#L86">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/router.ts#L87">property region</a>
</h3>

```typescript
region?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/router.ts#L91">property selfLink</a>
</h3>

```typescript
selfLink?: pulumi.Input<string>;
```


The URI of the created resource.

<h2 class="pdoc-module-header" id="SSLCertificateArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sSLCertificate.ts#L155">interface SSLCertificateArgs</a>
</h2>

The set of arguments for constructing a SSLCertificate resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sSLCertificate.ts#L161">property certificate</a>
</h3>

```typescript
certificate: pulumi.Input<string>;
```


A local certificate file in PEM format. The chain
may be at most 5 certs long, and must include at least one intermediate
cert. Changing this forces a new resource to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sSLCertificate.ts#L166">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```


An optional description of this resource.
Changing this forces a new resource to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sSLCertificate.ts#L171">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


A unique name for the SSL certificate. If you leave
this blank, Terraform will auto-generate a unique name.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sSLCertificate.ts#L176">property namePrefix</a>
</h3>

```typescript
namePrefix?: pulumi.Input<string>;
```


Creates a unique name beginning with the specified
prefix. Conflicts with `name`.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sSLCertificate.ts#L181">property privateKey</a>
</h3>

```typescript
privateKey: pulumi.Input<string>;
```


Write only private key in PEM format.
Changing this forces a new resource to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sSLCertificate.ts#L186">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs. If it
is not provided, the provider project is used.

<h2 class="pdoc-module-header" id="SSLCertificateState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sSLCertificate.ts#L110">interface SSLCertificateState</a>
</h2>

Input properties used for looking up and filtering SSLCertificate resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sSLCertificate.ts#L116">property certificate</a>
</h3>

```typescript
certificate?: pulumi.Input<string>;
```


A local certificate file in PEM format. The chain
may be at most 5 certs long, and must include at least one intermediate
cert. Changing this forces a new resource to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sSLCertificate.ts#L120">property certificateId</a>
</h3>

```typescript
certificateId?: pulumi.Input<string>;
```


A unique ID for the certificate, assigned by GCE.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sSLCertificate.ts#L125">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```


An optional description of this resource.
Changing this forces a new resource to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sSLCertificate.ts#L130">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


A unique name for the SSL certificate. If you leave
this blank, Terraform will auto-generate a unique name.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sSLCertificate.ts#L135">property namePrefix</a>
</h3>

```typescript
namePrefix?: pulumi.Input<string>;
```


Creates a unique name beginning with the specified
prefix. Conflicts with `name`.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sSLCertificate.ts#L140">property privateKey</a>
</h3>

```typescript
privateKey?: pulumi.Input<string>;
```


Write only private key in PEM format.
Changing this forces a new resource to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sSLCertificate.ts#L145">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sSLCertificate.ts#L149">property selfLink</a>
</h3>

```typescript
selfLink?: pulumi.Input<string>;
```


The URI of the created resource.

<h2 class="pdoc-module-header" id="SSLPolicyArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sSLPolicy.ts#L102">interface SSLPolicyArgs</a>
</h2>

The set of arguments for constructing a SSLPolicy resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sSLPolicy.ts#L103">property customFeatures</a>
</h3>

```typescript
customFeatures?: pulumi.Input<pulumi.Input<string>[]>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sSLPolicy.ts#L104">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sSLPolicy.ts#L105">property minTlsVersion</a>
</h3>

```typescript
minTlsVersion?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sSLPolicy.ts#L106">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sSLPolicy.ts#L107">property profile</a>
</h3>

```typescript
profile?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sSLPolicy.ts#L112">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.

<h2 class="pdoc-module-header" id="SSLPolicyState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sSLPolicy.ts#L79">interface SSLPolicyState</a>
</h2>

Input properties used for looking up and filtering SSLPolicy resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sSLPolicy.ts#L80">property creationTimestamp</a>
</h3>

```typescript
creationTimestamp?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sSLPolicy.ts#L81">property customFeatures</a>
</h3>

```typescript
customFeatures?: pulumi.Input<pulumi.Input<string>[]>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sSLPolicy.ts#L82">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sSLPolicy.ts#L83">property enabledFeatures</a>
</h3>

```typescript
enabledFeatures?: pulumi.Input<pulumi.Input<string>[]>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sSLPolicy.ts#L84">property fingerprint</a>
</h3>

```typescript
fingerprint?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sSLPolicy.ts#L85">property minTlsVersion</a>
</h3>

```typescript
minTlsVersion?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sSLPolicy.ts#L86">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sSLPolicy.ts#L87">property profile</a>
</h3>

```typescript
profile?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sSLPolicy.ts#L92">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sSLPolicy.ts#L96">property selfLink</a>
</h3>

```typescript
selfLink?: pulumi.Input<string>;
```


The URI of the created resource.

<h2 class="pdoc-module-header" id="SecurityPolicyArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/securityPolicy.ts#L121">interface SecurityPolicyArgs</a>
</h2>

The set of arguments for constructing a SecurityPolicy resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/securityPolicy.ts#L125">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```


An optional description of this rule. Max size is 64.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/securityPolicy.ts#L129">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


The name of the security policy.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/securityPolicy.ts#L134">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/securityPolicy.ts#L140">property rules</a>
</h3>

```typescript
rules?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```


The set of rules that belong to this policy. There must always be a default
rule (rule with priority 2147483647 and match "\*"). If no rules are provided when creating a
security policy, a default rule with action "allow" will be added. Structure is documented below.

<h2 class="pdoc-module-header" id="SecurityPolicyState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/securityPolicy.ts#L88">interface SecurityPolicyState</a>
</h2>

Input properties used for looking up and filtering SecurityPolicy resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/securityPolicy.ts#L92">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```


An optional description of this rule. Max size is 64.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/securityPolicy.ts#L96">property fingerprint</a>
</h3>

```typescript
fingerprint?: pulumi.Input<string>;
```


Fingerprint of this resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/securityPolicy.ts#L100">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


The name of the security policy.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/securityPolicy.ts#L105">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/securityPolicy.ts#L111">property rules</a>
</h3>

```typescript
rules?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```


The set of rules that belong to this policy. There must always be a default
rule (rule with priority 2147483647 and match "\*"). If no rules are provided when creating a
security policy, a default rule with action "allow" will be added. Structure is documented below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/securityPolicy.ts#L115">property selfLink</a>
</h3>

```typescript
selfLink?: pulumi.Input<string>;
```


The URI of the created resource.

<h2 class="pdoc-module-header" id="SharedVPCHostProjectArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sharedVPCHostProject.ts#L70">interface SharedVPCHostProjectArgs</a>
</h2>

The set of arguments for constructing a SharedVPCHostProject resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sharedVPCHostProject.ts#L74">property project</a>
</h3>

```typescript
project: pulumi.Input<string>;
```


The ID of the project that will serve as a Shared VPC host project

<h2 class="pdoc-module-header" id="SharedVPCHostProjectState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sharedVPCHostProject.ts#L60">interface SharedVPCHostProjectState</a>
</h2>

Input properties used for looking up and filtering SharedVPCHostProject resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sharedVPCHostProject.ts#L64">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project that will serve as a Shared VPC host project

<h2 class="pdoc-module-header" id="SharedVPCServiceProjectArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sharedVPCServiceProject.ts#L84">interface SharedVPCServiceProjectArgs</a>
</h2>

The set of arguments for constructing a SharedVPCServiceProject resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sharedVPCServiceProject.ts#L88">property hostProject</a>
</h3>

```typescript
hostProject: pulumi.Input<string>;
```


The ID of a host project to associate.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sharedVPCServiceProject.ts#L92">property serviceProject</a>
</h3>

```typescript
serviceProject: pulumi.Input<string>;
```


The ID of the project that will serve as a Shared VPC service project.

<h2 class="pdoc-module-header" id="SharedVPCServiceProjectState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sharedVPCServiceProject.ts#L70">interface SharedVPCServiceProjectState</a>
</h2>

Input properties used for looking up and filtering SharedVPCServiceProject resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sharedVPCServiceProject.ts#L74">property hostProject</a>
</h3>

```typescript
hostProject?: pulumi.Input<string>;
```


The ID of a host project to associate.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/sharedVPCServiceProject.ts#L78">property serviceProject</a>
</h3>

```typescript
serviceProject?: pulumi.Input<string>;
```


The ID of the project that will serve as a Shared VPC service project.

<h2 class="pdoc-module-header" id="SnapshotArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/snapshot.ts#L205">interface SnapshotArgs</a>
</h2>

The set of arguments for constructing a Snapshot resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/snapshot.ts#L209">property labels</a>
</h3>

```typescript
labels?: pulumi.Input<{ ... }>;
```


A set of key/value label pairs to assign to the snapshot.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/snapshot.ts#L214">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


A unique name for the resource, required by GCE.
Changing this forces a new resource to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/snapshot.ts#L219">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/snapshot.ts#L226">property snapshotEncryptionKeyRaw</a>
</h3>

```typescript
snapshotEncryptionKeyRaw?: pulumi.Input<string>;
```


A 256-bit [customer-supplied encryption key]
(https://cloud.google.com/compute/docs/disks/customer-supplied-encryption),
encoded in [RFC 4648 base64](https://tools.ietf.org/html/rfc4648#section-4)
to encrypt this snapshot.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/snapshot.ts#L230">property sourceDisk</a>
</h3>

```typescript
sourceDisk: pulumi.Input<string>;
```


The disk which will be used as the source of the snapshot.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/snapshot.ts#L237">property sourceDiskEncryptionKeyRaw</a>
</h3>

```typescript
sourceDiskEncryptionKeyRaw?: pulumi.Input<string>;
```


A 256-bit [customer-supplied encryption key]
(https://cloud.google.com/compute/docs/disks/customer-supplied-encryption),
encoded in [RFC 4648 base64](https://tools.ietf.org/html/rfc4648#section-4)
to decrypt the source disk.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/snapshot.ts#L241">property zone</a>
</h3>

```typescript
zone?: pulumi.Input<string>;
```


The zone where the source disk is located.

<h2 class="pdoc-module-header" id="SnapshotState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/snapshot.ts#L137">interface SnapshotState</a>
</h2>

Input properties used for looking up and filtering Snapshot resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/snapshot.ts#L141">property labelFingerprint</a>
</h3>

```typescript
labelFingerprint?: pulumi.Input<string>;
```


The unique fingerprint of the labels.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/snapshot.ts#L145">property labels</a>
</h3>

```typescript
labels?: pulumi.Input<{ ... }>;
```


A set of key/value label pairs to assign to the snapshot.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/snapshot.ts#L150">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


A unique name for the resource, required by GCE.
Changing this forces a new resource to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/snapshot.ts#L155">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/snapshot.ts#L159">property selfLink</a>
</h3>

```typescript
selfLink?: pulumi.Input<string>;
```


The URI of the created resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/snapshot.ts#L166">property snapshotEncryptionKeyRaw</a>
</h3>

```typescript
snapshotEncryptionKeyRaw?: pulumi.Input<string>;
```


A 256-bit [customer-supplied encryption key]
(https://cloud.google.com/compute/docs/disks/customer-supplied-encryption),
encoded in [RFC 4648 base64](https://tools.ietf.org/html/rfc4648#section-4)
to encrypt this snapshot.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/snapshot.ts#L173">property snapshotEncryptionKeySha256</a>
</h3>

```typescript
snapshotEncryptionKeySha256?: pulumi.Input<string>;
```


The [RFC 4648 base64]
(https://tools.ietf.org/html/rfc4648#section-4) encoded SHA-256 hash of the
[customer-supplied encryption key](https://cloud.google.com/compute/docs/disks/customer-supplied-encryption)
that protects this resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/snapshot.ts#L177">property sourceDisk</a>
</h3>

```typescript
sourceDisk?: pulumi.Input<string>;
```


The disk which will be used as the source of the snapshot.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/snapshot.ts#L184">property sourceDiskEncryptionKeyRaw</a>
</h3>

```typescript
sourceDiskEncryptionKeyRaw?: pulumi.Input<string>;
```


A 256-bit [customer-supplied encryption key]
(https://cloud.google.com/compute/docs/disks/customer-supplied-encryption),
encoded in [RFC 4648 base64](https://tools.ietf.org/html/rfc4648#section-4)
to decrypt the source disk.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/snapshot.ts#L191">property sourceDiskEncryptionKeySha256</a>
</h3>

```typescript
sourceDiskEncryptionKeySha256?: pulumi.Input<string>;
```


The [RFC 4648 base64]
(https://tools.ietf.org/html/rfc4648#section-4) encoded SHA-256 hash of the
[customer-supplied encryption key](https://cloud.google.com/compute/docs/disks/customer-supplied-encryption)
that protects the source disk.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/snapshot.ts#L195">property sourceDiskLink</a>
</h3>

```typescript
sourceDiskLink?: pulumi.Input<string>;
```


The URI of the source disk.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/snapshot.ts#L199">property zone</a>
</h3>

```typescript
zone?: pulumi.Input<string>;
```


The zone where the source disk is located.

<h2 class="pdoc-module-header" id="SubnetworkArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetwork.ts#L120">interface SubnetworkArgs</a>
</h2>

The set of arguments for constructing a Subnetwork resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetwork.ts#L121">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetwork.ts#L122">property enableFlowLogs</a>
</h3>

```typescript
enableFlowLogs?: pulumi.Input<boolean>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetwork.ts#L123">property ipCidrRange</a>
</h3>

```typescript
ipCidrRange: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetwork.ts#L124">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetwork.ts#L125">property network</a>
</h3>

```typescript
network: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetwork.ts#L126">property privateIpGoogleAccess</a>
</h3>

```typescript
privateIpGoogleAccess?: pulumi.Input<boolean>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetwork.ts#L131">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetwork.ts#L132">property region</a>
</h3>

```typescript
region?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetwork.ts#L133">property secondaryIpRanges</a>
</h3>

```typescript
secondaryIpRanges?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```

<h2 class="pdoc-module-header" id="SubnetworkIAMBindingArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetworkIAMBinding.ts#L132">interface SubnetworkIAMBindingArgs</a>
</h2>

The set of arguments for constructing a SubnetworkIAMBinding resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetworkIAMBinding.ts#L133">property members</a>
</h3>

```typescript
members: pulumi.Input<pulumi.Input<string>[]>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetworkIAMBinding.ts#L138">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetworkIAMBinding.ts#L143">property region</a>
</h3>

```typescript
region?: pulumi.Input<string>;
```


The region of the subnetwork. If
unspecified, this defaults to the region configured in the provider.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetworkIAMBinding.ts#L149">property role</a>
</h3>

```typescript
role: pulumi.Input<string>;
```


The role that should be applied. Only one
`google_compute_subnetwork_iam_binding` can be used per role. Note that custom roles must be of the format
`[projects|organizations]/{parent-name}/roles/{role-name}`.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetworkIAMBinding.ts#L153">property subnetwork</a>
</h3>

```typescript
subnetwork: pulumi.Input<string>;
```


The name of the subnetwork.

<h2 class="pdoc-module-header" id="SubnetworkIAMBindingState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetworkIAMBinding.ts#L101">interface SubnetworkIAMBindingState</a>
</h2>

Input properties used for looking up and filtering SubnetworkIAMBinding resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetworkIAMBinding.ts#L105">property etag</a>
</h3>

```typescript
etag?: pulumi.Input<string>;
```


(Computed) The etag of the subnetwork's IAM policy.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetworkIAMBinding.ts#L106">property members</a>
</h3>

```typescript
members?: pulumi.Input<pulumi.Input<string>[]>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetworkIAMBinding.ts#L111">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetworkIAMBinding.ts#L116">property region</a>
</h3>

```typescript
region?: pulumi.Input<string>;
```


The region of the subnetwork. If
unspecified, this defaults to the region configured in the provider.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetworkIAMBinding.ts#L122">property role</a>
</h3>

```typescript
role?: pulumi.Input<string>;
```


The role that should be applied. Only one
`google_compute_subnetwork_iam_binding` can be used per role. Note that custom roles must be of the format
`[projects|organizations]/{parent-name}/roles/{role-name}`.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetworkIAMBinding.ts#L126">property subnetwork</a>
</h3>

```typescript
subnetwork?: pulumi.Input<string>;
```


The name of the subnetwork.

<h2 class="pdoc-module-header" id="SubnetworkIAMMemberArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetworkIAMMember.ts#L132">interface SubnetworkIAMMemberArgs</a>
</h2>

The set of arguments for constructing a SubnetworkIAMMember resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetworkIAMMember.ts#L133">property member</a>
</h3>

```typescript
member: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetworkIAMMember.ts#L138">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetworkIAMMember.ts#L143">property region</a>
</h3>

```typescript
region?: pulumi.Input<string>;
```


The region of the subnetwork. If
unspecified, this defaults to the region configured in the provider.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetworkIAMMember.ts#L149">property role</a>
</h3>

```typescript
role: pulumi.Input<string>;
```


The role that should be applied. Only one
`google_compute_subnetwork_iam_binding` can be used per role. Note that custom roles must be of the format
`[projects|organizations]/{parent-name}/roles/{role-name}`.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetworkIAMMember.ts#L153">property subnetwork</a>
</h3>

```typescript
subnetwork: pulumi.Input<string>;
```


The name of the subnetwork.

<h2 class="pdoc-module-header" id="SubnetworkIAMMemberState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetworkIAMMember.ts#L101">interface SubnetworkIAMMemberState</a>
</h2>

Input properties used for looking up and filtering SubnetworkIAMMember resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetworkIAMMember.ts#L105">property etag</a>
</h3>

```typescript
etag?: pulumi.Input<string>;
```


(Computed) The etag of the subnetwork's IAM policy.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetworkIAMMember.ts#L106">property member</a>
</h3>

```typescript
member?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetworkIAMMember.ts#L111">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetworkIAMMember.ts#L116">property region</a>
</h3>

```typescript
region?: pulumi.Input<string>;
```


The region of the subnetwork. If
unspecified, this defaults to the region configured in the provider.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetworkIAMMember.ts#L122">property role</a>
</h3>

```typescript
role?: pulumi.Input<string>;
```


The role that should be applied. Only one
`google_compute_subnetwork_iam_binding` can be used per role. Note that custom roles must be of the format
`[projects|organizations]/{parent-name}/roles/{role-name}`.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetworkIAMMember.ts#L126">property subnetwork</a>
</h3>

```typescript
subnetwork?: pulumi.Input<string>;
```


The name of the subnetwork.

<h2 class="pdoc-module-header" id="SubnetworkIAMPolicyArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetworkIAMPolicy.ts#L123">interface SubnetworkIAMPolicyArgs</a>
</h2>

The set of arguments for constructing a SubnetworkIAMPolicy resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetworkIAMPolicy.ts#L128">property policyData</a>
</h3>

```typescript
policyData: pulumi.Input<string>;
```


The policy data generated by
a `google_iam_policy` data source.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetworkIAMPolicy.ts#L133">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetworkIAMPolicy.ts#L138">property region</a>
</h3>

```typescript
region?: pulumi.Input<string>;
```


The region of the subnetwork. If
unspecified, this defaults to the region configured in the provider.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetworkIAMPolicy.ts#L142">property subnetwork</a>
</h3>

```typescript
subnetwork: pulumi.Input<string>;
```


The name of the subnetwork.

<h2 class="pdoc-module-header" id="SubnetworkIAMPolicyState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetworkIAMPolicy.ts#L94">interface SubnetworkIAMPolicyState</a>
</h2>

Input properties used for looking up and filtering SubnetworkIAMPolicy resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetworkIAMPolicy.ts#L98">property etag</a>
</h3>

```typescript
etag?: pulumi.Input<string>;
```


(Computed) The etag of the subnetwork's IAM policy.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetworkIAMPolicy.ts#L103">property policyData</a>
</h3>

```typescript
policyData?: pulumi.Input<string>;
```


The policy data generated by
a `google_iam_policy` data source.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetworkIAMPolicy.ts#L108">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetworkIAMPolicy.ts#L113">property region</a>
</h3>

```typescript
region?: pulumi.Input<string>;
```


The region of the subnetwork. If
unspecified, this defaults to the region configured in the provider.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetworkIAMPolicy.ts#L117">property subnetwork</a>
</h3>

```typescript
subnetwork?: pulumi.Input<string>;
```


The name of the subnetwork.

<h2 class="pdoc-module-header" id="SubnetworkState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetwork.ts#L94">interface SubnetworkState</a>
</h2>

Input properties used for looking up and filtering Subnetwork resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetwork.ts#L95">property creationTimestamp</a>
</h3>

```typescript
creationTimestamp?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetwork.ts#L96">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetwork.ts#L97">property enableFlowLogs</a>
</h3>

```typescript
enableFlowLogs?: pulumi.Input<boolean>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetwork.ts#L98">property fingerprint</a>
</h3>

```typescript
fingerprint?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetwork.ts#L99">property gatewayAddress</a>
</h3>

```typescript
gatewayAddress?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetwork.ts#L100">property ipCidrRange</a>
</h3>

```typescript
ipCidrRange?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetwork.ts#L101">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetwork.ts#L102">property network</a>
</h3>

```typescript
network?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetwork.ts#L103">property privateIpGoogleAccess</a>
</h3>

```typescript
privateIpGoogleAccess?: pulumi.Input<boolean>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetwork.ts#L108">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetwork.ts#L109">property region</a>
</h3>

```typescript
region?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetwork.ts#L110">property secondaryIpRanges</a>
</h3>

```typescript
secondaryIpRanges?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/subnetwork.ts#L114">property selfLink</a>
</h3>

```typescript
selfLink?: pulumi.Input<string>;
```


The URI of the created resource.

<h2 class="pdoc-module-header" id="TargetHttpProxyArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetHttpProxy.ts#L93">interface TargetHttpProxyArgs</a>
</h2>

The set of arguments for constructing a TargetHttpProxy resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetHttpProxy.ts#L94">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetHttpProxy.ts#L95">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetHttpProxy.ts#L100">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetHttpProxy.ts#L101">property urlMap</a>
</h3>

```typescript
urlMap: pulumi.Input<string>;
```

<h2 class="pdoc-module-header" id="TargetHttpProxyState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetHttpProxy.ts#L73">interface TargetHttpProxyState</a>
</h2>

Input properties used for looking up and filtering TargetHttpProxy resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetHttpProxy.ts#L74">property creationTimestamp</a>
</h3>

```typescript
creationTimestamp?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetHttpProxy.ts#L75">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetHttpProxy.ts#L76">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetHttpProxy.ts#L81">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetHttpProxy.ts#L82">property proxyId</a>
</h3>

```typescript
proxyId?: pulumi.Input<number>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetHttpProxy.ts#L86">property selfLink</a>
</h3>

```typescript
selfLink?: pulumi.Input<string>;
```


The URI of the created resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetHttpProxy.ts#L87">property urlMap</a>
</h3>

```typescript
urlMap?: pulumi.Input<string>;
```

<h2 class="pdoc-module-header" id="TargetHttpsProxyArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetHttpsProxy.ts#L108">interface TargetHttpsProxyArgs</a>
</h2>

The set of arguments for constructing a TargetHttpsProxy resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetHttpsProxy.ts#L109">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetHttpsProxy.ts#L110">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetHttpsProxy.ts#L115">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetHttpsProxy.ts#L116">property quicOverride</a>
</h3>

```typescript
quicOverride?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetHttpsProxy.ts#L117">property sslCertificates</a>
</h3>

```typescript
sslCertificates: pulumi.Input<pulumi.Input<string>[]>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetHttpsProxy.ts#L118">property sslPolicy</a>
</h3>

```typescript
sslPolicy?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetHttpsProxy.ts#L119">property urlMap</a>
</h3>

```typescript
urlMap: pulumi.Input<string>;
```

<h2 class="pdoc-module-header" id="TargetHttpsProxyState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetHttpsProxy.ts#L85">interface TargetHttpsProxyState</a>
</h2>

Input properties used for looking up and filtering TargetHttpsProxy resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetHttpsProxy.ts#L86">property creationTimestamp</a>
</h3>

```typescript
creationTimestamp?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetHttpsProxy.ts#L87">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetHttpsProxy.ts#L88">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetHttpsProxy.ts#L93">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetHttpsProxy.ts#L94">property proxyId</a>
</h3>

```typescript
proxyId?: pulumi.Input<number>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetHttpsProxy.ts#L95">property quicOverride</a>
</h3>

```typescript
quicOverride?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetHttpsProxy.ts#L99">property selfLink</a>
</h3>

```typescript
selfLink?: pulumi.Input<string>;
```


The URI of the created resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetHttpsProxy.ts#L100">property sslCertificates</a>
</h3>

```typescript
sslCertificates?: pulumi.Input<pulumi.Input<string>[]>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetHttpsProxy.ts#L101">property sslPolicy</a>
</h3>

```typescript
sslPolicy?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetHttpsProxy.ts#L102">property urlMap</a>
</h3>

```typescript
urlMap?: pulumi.Input<string>;
```

<h2 class="pdoc-module-header" id="TargetPoolArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetPool.ts#L180">interface TargetPoolArgs</a>
</h2>

The set of arguments for constructing a TargetPool resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetPool.ts#L185">property backupPool</a>
</h3>

```typescript
backupPool?: pulumi.Input<string>;
```


URL to the backup target pool. Must also set
failover\_ratio.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetPool.ts#L189">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```


Textual description field.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetPool.ts#L194">property failoverRatio</a>
</h3>

```typescript
failoverRatio?: pulumi.Input<number>;
```


Ratio (0 to 1) of failed nodes before using the
backup pool (which must also be set).

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetPool.ts#L199">property healthChecks</a>
</h3>

```typescript
healthChecks?: pulumi.Input<string>;
```


List of zero or one health check name or self_link. Only
legacy `google_compute_http_health_check` is supported.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetPool.ts#L207">property instances</a>
</h3>

```typescript
instances?: pulumi.Input<pulumi.Input<string>[]>;
```


List of instances in the pool. They can be given as
URLs, or in the form of "zone/name". Note that the instances need not exist
at the time of target pool creation, so there is no need to use the
Terraform interpolators to create a dependency on the instances from the
target pool.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetPool.ts#L212">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


A unique name for the resource, required by GCE. Changing
this forces a new resource to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetPool.ts#L217">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetPool.ts#L222">property region</a>
</h3>

```typescript
region?: pulumi.Input<string>;
```


Where the target pool resides. Defaults to project
region.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetPool.ts#L228">property sessionAffinity</a>
</h3>

```typescript
sessionAffinity?: pulumi.Input<string>;
```


How to distribute load. Options are "NONE" (no
affinity). "CLIENT\_IP" (hash of the source/dest addresses / ports), and
"CLIENT\_IP\_PROTO" also includes the protocol (default "NONE").

<h2 class="pdoc-module-header" id="TargetPoolState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetPool.ts#L122">interface TargetPoolState</a>
</h2>

Input properties used for looking up and filtering TargetPool resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetPool.ts#L127">property backupPool</a>
</h3>

```typescript
backupPool?: pulumi.Input<string>;
```


URL to the backup target pool. Must also set
failover\_ratio.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetPool.ts#L131">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```


Textual description field.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetPool.ts#L136">property failoverRatio</a>
</h3>

```typescript
failoverRatio?: pulumi.Input<number>;
```


Ratio (0 to 1) of failed nodes before using the
backup pool (which must also be set).

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetPool.ts#L141">property healthChecks</a>
</h3>

```typescript
healthChecks?: pulumi.Input<string>;
```


List of zero or one health check name or self_link. Only
legacy `google_compute_http_health_check` is supported.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetPool.ts#L149">property instances</a>
</h3>

```typescript
instances?: pulumi.Input<pulumi.Input<string>[]>;
```


List of instances in the pool. They can be given as
URLs, or in the form of "zone/name". Note that the instances need not exist
at the time of target pool creation, so there is no need to use the
Terraform interpolators to create a dependency on the instances from the
target pool.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetPool.ts#L154">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


A unique name for the resource, required by GCE. Changing
this forces a new resource to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetPool.ts#L159">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetPool.ts#L164">property region</a>
</h3>

```typescript
region?: pulumi.Input<string>;
```


Where the target pool resides. Defaults to project
region.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetPool.ts#L168">property selfLink</a>
</h3>

```typescript
selfLink?: pulumi.Input<string>;
```


The URI of the created resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetPool.ts#L174">property sessionAffinity</a>
</h3>

```typescript
sessionAffinity?: pulumi.Input<string>;
```


How to distribute load. Options are "NONE" (no
affinity). "CLIENT\_IP" (hash of the source/dest addresses / ports), and
"CLIENT\_IP\_PROTO" also includes the protocol (default "NONE").

<h2 class="pdoc-module-header" id="TargetSSLProxyArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetSSLProxy.ts#L108">interface TargetSSLProxyArgs</a>
</h2>

The set of arguments for constructing a TargetSSLProxy resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetSSLProxy.ts#L109">property backendService</a>
</h3>

```typescript
backendService: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetSSLProxy.ts#L110">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetSSLProxy.ts#L111">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetSSLProxy.ts#L116">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetSSLProxy.ts#L117">property proxyHeader</a>
</h3>

```typescript
proxyHeader?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetSSLProxy.ts#L118">property sslCertificates</a>
</h3>

```typescript
sslCertificates: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetSSLProxy.ts#L119">property sslPolicy</a>
</h3>

```typescript
sslPolicy?: pulumi.Input<string>;
```

<h2 class="pdoc-module-header" id="TargetSSLProxyState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetSSLProxy.ts#L85">interface TargetSSLProxyState</a>
</h2>

Input properties used for looking up and filtering TargetSSLProxy resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetSSLProxy.ts#L86">property backendService</a>
</h3>

```typescript
backendService?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetSSLProxy.ts#L87">property creationTimestamp</a>
</h3>

```typescript
creationTimestamp?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetSSLProxy.ts#L88">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetSSLProxy.ts#L89">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetSSLProxy.ts#L94">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetSSLProxy.ts#L95">property proxyHeader</a>
</h3>

```typescript
proxyHeader?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetSSLProxy.ts#L96">property proxyId</a>
</h3>

```typescript
proxyId?: pulumi.Input<number>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetSSLProxy.ts#L100">property selfLink</a>
</h3>

```typescript
selfLink?: pulumi.Input<string>;
```


The URI of the created resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetSSLProxy.ts#L101">property sslCertificates</a>
</h3>

```typescript
sslCertificates?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetSSLProxy.ts#L102">property sslPolicy</a>
</h3>

```typescript
sslPolicy?: pulumi.Input<string>;
```

<h2 class="pdoc-module-header" id="TargetTCPProxyArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetTCPProxy.ts#L97">interface TargetTCPProxyArgs</a>
</h2>

The set of arguments for constructing a TargetTCPProxy resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetTCPProxy.ts#L98">property backendService</a>
</h3>

```typescript
backendService: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetTCPProxy.ts#L99">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetTCPProxy.ts#L100">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetTCPProxy.ts#L105">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetTCPProxy.ts#L106">property proxyHeader</a>
</h3>

```typescript
proxyHeader?: pulumi.Input<string>;
```

<h2 class="pdoc-module-header" id="TargetTCPProxyState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetTCPProxy.ts#L76">interface TargetTCPProxyState</a>
</h2>

Input properties used for looking up and filtering TargetTCPProxy resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetTCPProxy.ts#L77">property backendService</a>
</h3>

```typescript
backendService?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetTCPProxy.ts#L78">property creationTimestamp</a>
</h3>

```typescript
creationTimestamp?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetTCPProxy.ts#L79">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetTCPProxy.ts#L80">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetTCPProxy.ts#L85">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetTCPProxy.ts#L86">property proxyHeader</a>
</h3>

```typescript
proxyHeader?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetTCPProxy.ts#L87">property proxyId</a>
</h3>

```typescript
proxyId?: pulumi.Input<number>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/targetTCPProxy.ts#L91">property selfLink</a>
</h3>

```typescript
selfLink?: pulumi.Input<string>;
```


The URI of the created resource.

<h2 class="pdoc-module-header" id="URLMapArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/uRLMap.ts#L160">interface URLMapArgs</a>
</h2>

The set of arguments for constructing a URLMap resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/uRLMap.ts#L164">property defaultService</a>
</h3>

```typescript
defaultService: pulumi.Input<string>;
```


The backend service or backend bucket to use if none of the given paths match.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/uRLMap.ts#L168">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```


An optional description of this test.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/uRLMap.ts#L172">property hostRules</a>
</h3>

```typescript
hostRules?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```


A list of host rules. Multiple blocks of this type are permitted. Structure is documented below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/uRLMap.ts#L176">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


The name of the `path_matcher` resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/uRLMap.ts#L180">property pathMatchers</a>
</h3>

```typescript
pathMatchers?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```


The name of the `path_matcher` to apply this host rule to.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/uRLMap.ts#L185">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/uRLMap.ts#L189">property tests</a>
</h3>

```typescript
tests?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```


The test to perform.  Multiple blocks of this type are permitted. Structure is documented below.

<h2 class="pdoc-module-header" id="URLMapState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/uRLMap.ts#L113">interface URLMapState</a>
</h2>

Input properties used for looking up and filtering URLMap resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/uRLMap.ts#L117">property defaultService</a>
</h3>

```typescript
defaultService?: pulumi.Input<string>;
```


The backend service or backend bucket to use if none of the given paths match.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/uRLMap.ts#L121">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```


An optional description of this test.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/uRLMap.ts#L125">property fingerprint</a>
</h3>

```typescript
fingerprint?: pulumi.Input<string>;
```


The unique fingerprint for this resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/uRLMap.ts#L129">property hostRules</a>
</h3>

```typescript
hostRules?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```


A list of host rules. Multiple blocks of this type are permitted. Structure is documented below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/uRLMap.ts#L133">property mapId</a>
</h3>

```typescript
mapId?: pulumi.Input<string>;
```


The GCE assigned ID of the resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/uRLMap.ts#L137">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


The name of the `path_matcher` resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/uRLMap.ts#L141">property pathMatchers</a>
</h3>

```typescript
pathMatchers?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```


The name of the `path_matcher` to apply this host rule to.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/uRLMap.ts#L146">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs. If it
is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/uRLMap.ts#L150">property selfLink</a>
</h3>

```typescript
selfLink?: pulumi.Input<string>;
```


The URI of the created resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/uRLMap.ts#L154">property tests</a>
</h3>

```typescript
tests?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```


The test to perform.  Multiple blocks of this type are permitted. Structure is documented below.

<h2 class="pdoc-module-header" id="VPNGatewayArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNGateway.ts#L93">interface VPNGatewayArgs</a>
</h2>

The set of arguments for constructing a VPNGateway resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNGateway.ts#L94">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNGateway.ts#L95">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNGateway.ts#L96">property network</a>
</h3>

```typescript
network: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNGateway.ts#L101">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNGateway.ts#L102">property region</a>
</h3>

```typescript
region?: pulumi.Input<string>;
```

<h2 class="pdoc-module-header" id="VPNGatewayState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNGateway.ts#L73">interface VPNGatewayState</a>
</h2>

Input properties used for looking up and filtering VPNGateway resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNGateway.ts#L74">property creationTimestamp</a>
</h3>

```typescript
creationTimestamp?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNGateway.ts#L75">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNGateway.ts#L76">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNGateway.ts#L77">property network</a>
</h3>

```typescript
network?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNGateway.ts#L82">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNGateway.ts#L83">property region</a>
</h3>

```typescript
region?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNGateway.ts#L87">property selfLink</a>
</h3>

```typescript
selfLink?: pulumi.Input<string>;
```


The URI of the created resource.

<h2 class="pdoc-module-header" id="VPNTunnelArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNTunnel.ts#L139">interface VPNTunnelArgs</a>
</h2>

The set of arguments for constructing a VPNTunnel resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNTunnel.ts#L140">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNTunnel.ts#L141">property ikeVersion</a>
</h3>

```typescript
ikeVersion?: pulumi.Input<number>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNTunnel.ts#L142">property labels</a>
</h3>

```typescript
labels?: pulumi.Input<{ ... }>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNTunnel.ts#L143">property localTrafficSelectors</a>
</h3>

```typescript
localTrafficSelectors?: pulumi.Input<pulumi.Input<string>[]>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNTunnel.ts#L144">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNTunnel.ts#L145">property peerIp</a>
</h3>

```typescript
peerIp: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNTunnel.ts#L150">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNTunnel.ts#L151">property region</a>
</h3>

```typescript
region?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNTunnel.ts#L152">property remoteTrafficSelectors</a>
</h3>

```typescript
remoteTrafficSelectors?: pulumi.Input<pulumi.Input<string>[]>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNTunnel.ts#L153">property router</a>
</h3>

```typescript
router?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNTunnel.ts#L154">property sharedSecret</a>
</h3>

```typescript
sharedSecret: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNTunnel.ts#L155">property targetVpnGateway</a>
</h3>

```typescript
targetVpnGateway: pulumi.Input<string>;
```

<h2 class="pdoc-module-header" id="VPNTunnelState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNTunnel.ts#L109">interface VPNTunnelState</a>
</h2>

Input properties used for looking up and filtering VPNTunnel resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNTunnel.ts#L110">property creationTimestamp</a>
</h3>

```typescript
creationTimestamp?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNTunnel.ts#L111">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNTunnel.ts#L112">property detailedStatus</a>
</h3>

```typescript
detailedStatus?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNTunnel.ts#L113">property ikeVersion</a>
</h3>

```typescript
ikeVersion?: pulumi.Input<number>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNTunnel.ts#L114">property labelFingerprint</a>
</h3>

```typescript
labelFingerprint?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNTunnel.ts#L115">property labels</a>
</h3>

```typescript
labels?: pulumi.Input<{ ... }>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNTunnel.ts#L116">property localTrafficSelectors</a>
</h3>

```typescript
localTrafficSelectors?: pulumi.Input<pulumi.Input<string>[]>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNTunnel.ts#L117">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNTunnel.ts#L118">property peerIp</a>
</h3>

```typescript
peerIp?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNTunnel.ts#L123">property project</a>
</h3>

```typescript
project?: pulumi.Input<string>;
```


The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNTunnel.ts#L124">property region</a>
</h3>

```typescript
region?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNTunnel.ts#L125">property remoteTrafficSelectors</a>
</h3>

```typescript
remoteTrafficSelectors?: pulumi.Input<pulumi.Input<string>[]>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNTunnel.ts#L126">property router</a>
</h3>

```typescript
router?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNTunnel.ts#L130">property selfLink</a>
</h3>

```typescript
selfLink?: pulumi.Input<string>;
```


The URI of the created resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNTunnel.ts#L131">property sharedSecret</a>
</h3>

```typescript
sharedSecret?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNTunnel.ts#L132">property sharedSecretHash</a>
</h3>

```typescript
sharedSecretHash?: pulumi.Input<string>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/master/sdk/nodejs/compute/vPNTunnel.ts#L133">property targetVpnGateway</a>
</h3>

```typescript
targetVpnGateway?: pulumi.Input<string>;
```

