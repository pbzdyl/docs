---
title: Module redis
---

<a href="../index.html">@pulumi/azure</a> &gt; redis

<h2 class="pdoc-module-header">Index</h2>

* <a href="#Cache">class Cache</a>
* <a href="#FirewallRule">class FirewallRule</a>
* <a href="#CacheArgs">interface CacheArgs</a>
* <a href="#CacheState">interface CacheState</a>
* <a href="#FirewallRuleArgs">interface FirewallRuleArgs</a>
* <a href="#FirewallRuleState">interface FirewallRuleState</a>

<a href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/cache.ts">redis/cache.ts</a> <a href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/firewallRule.ts">redis/firewallRule.ts</a> 


<h2 class="pdoc-module-header" id="Cache">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/cache.ts#L9">class Cache</a>
</h2>

Manages a Redis Cache.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/cache.ts#L92">constructor</a>
</h3>

```typescript
new Cache(name: string, args: CacheArgs, opts?: pulumi.CustomResourceOptions)
```


Create a Cache resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/cache.ts#L18">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: CacheState): Cache
```


Get an existing Cache resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method getProvider</a>
</h3>

```typescript
getProvider(moduleMember: string): ProviderResource | undefined
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/cache.ts#L25">property capacity</a>
</h3>

```typescript
public capacity: pulumi.Output<number>;
```


The size of the Redis cache to deploy. Valid values for a SKU `family` of C (Basic/Standard) are `0, 1, 2, 3, 4, 5, 6`, and for P (Premium) `family` are `1, 2, 3, 4`.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/cache.ts#L29">property enableNonSslPort</a>
</h3>

```typescript
public enableNonSslPort: pulumi.Output<boolean | undefined>;
```


Enable the non-SSL port (6789) - disabled by default.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/cache.ts#L33">property family</a>
</h3>

```typescript
public family: pulumi.Output<string>;
```


The SKU family to use. Valid values are `C` and `P`, where C = Basic/Standard, P = Premium.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/cache.ts#L37">property hostname</a>
</h3>

```typescript
public hostname: pulumi.Output<string>;
```


The Hostname of the Redis Instance

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/cache.ts#L41">property location</a>
</h3>

```typescript
public location: pulumi.Output<string>;
```


The location of the resource group.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/cache.ts#L46">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```


The name of the Redis instance. Changing this forces a
new resource to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/cache.ts#L50">property patchSchedules</a>
</h3>

```typescript
public patchSchedules: pulumi.Output<{ ... }[] | undefined>;
```


A list of `patch_schedule` blocks as defined below - only available for Premium SKU's.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/cache.ts#L54">property port</a>
</h3>

```typescript
public port: pulumi.Output<number>;
```


The non-SSL Port of the Redis Instance

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/cache.ts#L58">property primaryAccessKey</a>
</h3>

```typescript
public primaryAccessKey: pulumi.Output<string>;
```


The Primary Access Key for the Redis Instance

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/cache.ts#L62">property privateStaticIpAddress</a>
</h3>

```typescript
public privateStaticIpAddress: pulumi.Output<string>;
```


The Static IP Address to assign to the Redis Cache when hosted inside the Virtual Network. Changing this forces a new resource to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/cache.ts#L66">property redisConfiguration</a>
</h3>

```typescript
public redisConfiguration: pulumi.Output<{ ... }>;
```


A `redis_configuration` as defined below - with some limitations by SKU - defaults/details are shown below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/cache.ts#L71">property resourceGroupName</a>
</h3>

```typescript
public resourceGroupName: pulumi.Output<string>;
```


The name of the resource group in which to
create the Redis instance.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/cache.ts#L75">property secondaryAccessKey</a>
</h3>

```typescript
public secondaryAccessKey: pulumi.Output<string>;
```


The Secondary Access Key for the Redis Instance

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/cache.ts#L79">property shardCount</a>
</h3>

```typescript
public shardCount: pulumi.Output<number | undefined>;
```


*Only available when using the Premium SKU* The number of Shards to create on the Redis Cluster.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/cache.ts#L83">property skuName</a>
</h3>

```typescript
public skuName: pulumi.Output<string>;
```


The SKU of Redis to use - can be either Basic, Standard or Premium.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/cache.ts#L87">property sslPort</a>
</h3>

```typescript
public sslPort: pulumi.Output<number>;
```


The SSL Port of the Redis Instance

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/cache.ts#L91">property subnetId</a>
</h3>

```typescript
public subnetId: pulumi.Output<string | undefined>;
```


The ID of the Subnet within which the Redis Cache should be deployed. Changing this forces a new resource to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/cache.ts#L92">property tags</a>
</h3>

```typescript
public tags: pulumi.Output<{ ... }>;
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h2 class="pdoc-module-header" id="FirewallRule">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/firewallRule.ts#L11">class FirewallRule</a>
</h2>

Manages a Firewall Rule associated with a Premium Redis Cache.

~> **Note:** Redis Firewall Rules can only be assigned to a Redis Cache with a `Premium` SKU.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/firewallRule.ts#L43">constructor</a>
</h3>

```typescript
new FirewallRule(name: string, args: FirewallRuleArgs, opts?: pulumi.CustomResourceOptions)
```


Create a FirewallRule resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/firewallRule.ts#L20">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: FirewallRuleState): FirewallRule
```


Get an existing FirewallRule resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method getProvider</a>
</h3>

```typescript
getProvider(moduleMember: string): ProviderResource | undefined
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/firewallRule.ts#L27">property endIp</a>
</h3>

```typescript
public endIp: pulumi.Output<string>;
```


The highest IP address included in the range.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/firewallRule.ts#L31">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```


The name of the Firewall Rule. Changing this forces a new resource to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/firewallRule.ts#L35">property redisCacheName</a>
</h3>

```typescript
public redisCacheName: pulumi.Output<string>;
```


The name of the Redis Cache. Changing this forces a new resource to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/firewallRule.ts#L39">property resourceGroupName</a>
</h3>

```typescript
public resourceGroupName: pulumi.Output<string>;
```


The name of the resource group in which this Redis Cache exists.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/firewallRule.ts#L43">property startIp</a>
</h3>

```typescript
public startIp: pulumi.Output<string>;
```


The lowest IP address included in the range

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h2 class="pdoc-module-header" id="CacheArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/cache.ts#L247">interface CacheArgs</a>
</h2>

The set of arguments for constructing a Cache resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/cache.ts#L251">property capacity</a>
</h3>

```typescript
capacity: pulumi.Input<number>;
```


The size of the Redis cache to deploy. Valid values for a SKU `family` of C (Basic/Standard) are `0, 1, 2, 3, 4, 5, 6`, and for P (Premium) `family` are `1, 2, 3, 4`.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/cache.ts#L255">property enableNonSslPort</a>
</h3>

```typescript
enableNonSslPort?: pulumi.Input<boolean>;
```


Enable the non-SSL port (6789) - disabled by default.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/cache.ts#L259">property family</a>
</h3>

```typescript
family: pulumi.Input<string>;
```


The SKU family to use. Valid values are `C` and `P`, where C = Basic/Standard, P = Premium.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/cache.ts#L263">property location</a>
</h3>

```typescript
location: pulumi.Input<string>;
```


The location of the resource group.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/cache.ts#L268">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


The name of the Redis instance. Changing this forces a
new resource to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/cache.ts#L272">property patchSchedules</a>
</h3>

```typescript
patchSchedules?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```


A list of `patch_schedule` blocks as defined below - only available for Premium SKU's.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/cache.ts#L276">property privateStaticIpAddress</a>
</h3>

```typescript
privateStaticIpAddress?: pulumi.Input<string>;
```


The Static IP Address to assign to the Redis Cache when hosted inside the Virtual Network. Changing this forces a new resource to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/cache.ts#L280">property redisConfiguration</a>
</h3>

```typescript
redisConfiguration: pulumi.Input<{ ... }>;
```


A `redis_configuration` as defined below - with some limitations by SKU - defaults/details are shown below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/cache.ts#L285">property resourceGroupName</a>
</h3>

```typescript
resourceGroupName: pulumi.Input<string>;
```


The name of the resource group in which to
create the Redis instance.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/cache.ts#L289">property shardCount</a>
</h3>

```typescript
shardCount?: pulumi.Input<number>;
```


*Only available when using the Premium SKU* The number of Shards to create on the Redis Cluster.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/cache.ts#L293">property skuName</a>
</h3>

```typescript
skuName: pulumi.Input<string>;
```


The SKU of Redis to use - can be either Basic, Standard or Premium.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/cache.ts#L297">property subnetId</a>
</h3>

```typescript
subnetId?: pulumi.Input<string>;
```


The ID of the Subnet within which the Redis Cache should be deployed. Changing this forces a new resource to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/cache.ts#L298">property tags</a>
</h3>

```typescript
tags?: pulumi.Input<{ ... }>;
```

<h2 class="pdoc-module-header" id="CacheState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/cache.ts#L170">interface CacheState</a>
</h2>

Input properties used for looking up and filtering Cache resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/cache.ts#L174">property capacity</a>
</h3>

```typescript
capacity?: pulumi.Input<number>;
```


The size of the Redis cache to deploy. Valid values for a SKU `family` of C (Basic/Standard) are `0, 1, 2, 3, 4, 5, 6`, and for P (Premium) `family` are `1, 2, 3, 4`.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/cache.ts#L178">property enableNonSslPort</a>
</h3>

```typescript
enableNonSslPort?: pulumi.Input<boolean>;
```


Enable the non-SSL port (6789) - disabled by default.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/cache.ts#L182">property family</a>
</h3>

```typescript
family?: pulumi.Input<string>;
```


The SKU family to use. Valid values are `C` and `P`, where C = Basic/Standard, P = Premium.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/cache.ts#L186">property hostname</a>
</h3>

```typescript
hostname?: pulumi.Input<string>;
```


The Hostname of the Redis Instance

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/cache.ts#L190">property location</a>
</h3>

```typescript
location?: pulumi.Input<string>;
```


The location of the resource group.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/cache.ts#L195">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


The name of the Redis instance. Changing this forces a
new resource to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/cache.ts#L199">property patchSchedules</a>
</h3>

```typescript
patchSchedules?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```


A list of `patch_schedule` blocks as defined below - only available for Premium SKU's.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/cache.ts#L203">property port</a>
</h3>

```typescript
port?: pulumi.Input<number>;
```


The non-SSL Port of the Redis Instance

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/cache.ts#L207">property primaryAccessKey</a>
</h3>

```typescript
primaryAccessKey?: pulumi.Input<string>;
```


The Primary Access Key for the Redis Instance

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/cache.ts#L211">property privateStaticIpAddress</a>
</h3>

```typescript
privateStaticIpAddress?: pulumi.Input<string>;
```


The Static IP Address to assign to the Redis Cache when hosted inside the Virtual Network. Changing this forces a new resource to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/cache.ts#L215">property redisConfiguration</a>
</h3>

```typescript
redisConfiguration?: pulumi.Input<{ ... }>;
```


A `redis_configuration` as defined below - with some limitations by SKU - defaults/details are shown below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/cache.ts#L220">property resourceGroupName</a>
</h3>

```typescript
resourceGroupName?: pulumi.Input<string>;
```


The name of the resource group in which to
create the Redis instance.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/cache.ts#L224">property secondaryAccessKey</a>
</h3>

```typescript
secondaryAccessKey?: pulumi.Input<string>;
```


The Secondary Access Key for the Redis Instance

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/cache.ts#L228">property shardCount</a>
</h3>

```typescript
shardCount?: pulumi.Input<number>;
```


*Only available when using the Premium SKU* The number of Shards to create on the Redis Cluster.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/cache.ts#L232">property skuName</a>
</h3>

```typescript
skuName?: pulumi.Input<string>;
```


The SKU of Redis to use - can be either Basic, Standard or Premium.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/cache.ts#L236">property sslPort</a>
</h3>

```typescript
sslPort?: pulumi.Input<number>;
```


The SSL Port of the Redis Instance

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/cache.ts#L240">property subnetId</a>
</h3>

```typescript
subnetId?: pulumi.Input<string>;
```


The ID of the Subnet within which the Redis Cache should be deployed. Changing this forces a new resource to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/cache.ts#L241">property tags</a>
</h3>

```typescript
tags?: pulumi.Input<{ ... }>;
```

<h2 class="pdoc-module-header" id="FirewallRuleArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/firewallRule.ts#L115">interface FirewallRuleArgs</a>
</h2>

The set of arguments for constructing a FirewallRule resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/firewallRule.ts#L119">property endIp</a>
</h3>

```typescript
endIp: pulumi.Input<string>;
```


The highest IP address included in the range.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/firewallRule.ts#L123">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


The name of the Firewall Rule. Changing this forces a new resource to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/firewallRule.ts#L127">property redisCacheName</a>
</h3>

```typescript
redisCacheName: pulumi.Input<string>;
```


The name of the Redis Cache. Changing this forces a new resource to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/firewallRule.ts#L131">property resourceGroupName</a>
</h3>

```typescript
resourceGroupName: pulumi.Input<string>;
```


The name of the resource group in which this Redis Cache exists.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/firewallRule.ts#L135">property startIp</a>
</h3>

```typescript
startIp: pulumi.Input<string>;
```


The lowest IP address included in the range

<h2 class="pdoc-module-header" id="FirewallRuleState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/firewallRule.ts#L89">interface FirewallRuleState</a>
</h2>

Input properties used for looking up and filtering FirewallRule resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/firewallRule.ts#L93">property endIp</a>
</h3>

```typescript
endIp?: pulumi.Input<string>;
```


The highest IP address included in the range.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/firewallRule.ts#L97">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


The name of the Firewall Rule. Changing this forces a new resource to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/firewallRule.ts#L101">property redisCacheName</a>
</h3>

```typescript
redisCacheName?: pulumi.Input<string>;
```


The name of the Redis Cache. Changing this forces a new resource to be created.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/firewallRule.ts#L105">property resourceGroupName</a>
</h3>

```typescript
resourceGroupName?: pulumi.Input<string>;
```


The name of the resource group in which this Redis Cache exists.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/master/sdk/nodejs/redis/firewallRule.ts#L109">property startIp</a>
</h3>

```typescript
startIp?: pulumi.Input<string>;
```


The lowest IP address included in the range

