---
title: Module wafregional
---

<a href="../index.html">@pulumi/aws</a> &gt; wafregional

<h2 class="pdoc-module-header">Index</h2>

* <a href="#ByteMatchSet">class ByteMatchSet</a>
* <a href="#GeoMatchSet">class GeoMatchSet</a>
* <a href="#IpSet">class IpSet</a>
* <a href="#RateBasedRule">class RateBasedRule</a>
* <a href="#RegexMatchSet">class RegexMatchSet</a>
* <a href="#RegexPatternSet">class RegexPatternSet</a>
* <a href="#Rule">class Rule</a>
* <a href="#RuleGroup">class RuleGroup</a>
* <a href="#SizeConstraintSet">class SizeConstraintSet</a>
* <a href="#SqlInjectionMatchSet">class SqlInjectionMatchSet</a>
* <a href="#WebAcl">class WebAcl</a>
* <a href="#WebAclAssociation">class WebAclAssociation</a>
* <a href="#XssMatchSet">class XssMatchSet</a>
* <a href="#ByteMatchSetArgs">interface ByteMatchSetArgs</a>
* <a href="#ByteMatchSetState">interface ByteMatchSetState</a>
* <a href="#GeoMatchSetArgs">interface GeoMatchSetArgs</a>
* <a href="#GeoMatchSetState">interface GeoMatchSetState</a>
* <a href="#IpSetArgs">interface IpSetArgs</a>
* <a href="#IpSetState">interface IpSetState</a>
* <a href="#RateBasedRuleArgs">interface RateBasedRuleArgs</a>
* <a href="#RateBasedRuleState">interface RateBasedRuleState</a>
* <a href="#RegexMatchSetArgs">interface RegexMatchSetArgs</a>
* <a href="#RegexMatchSetState">interface RegexMatchSetState</a>
* <a href="#RegexPatternSetArgs">interface RegexPatternSetArgs</a>
* <a href="#RegexPatternSetState">interface RegexPatternSetState</a>
* <a href="#RuleArgs">interface RuleArgs</a>
* <a href="#RuleGroupArgs">interface RuleGroupArgs</a>
* <a href="#RuleGroupState">interface RuleGroupState</a>
* <a href="#RuleState">interface RuleState</a>
* <a href="#SizeConstraintSetArgs">interface SizeConstraintSetArgs</a>
* <a href="#SizeConstraintSetState">interface SizeConstraintSetState</a>
* <a href="#SqlInjectionMatchSetArgs">interface SqlInjectionMatchSetArgs</a>
* <a href="#SqlInjectionMatchSetState">interface SqlInjectionMatchSetState</a>
* <a href="#WebAclArgs">interface WebAclArgs</a>
* <a href="#WebAclAssociationArgs">interface WebAclAssociationArgs</a>
* <a href="#WebAclAssociationState">interface WebAclAssociationState</a>
* <a href="#WebAclState">interface WebAclState</a>
* <a href="#XssMatchSetArgs">interface XssMatchSetArgs</a>
* <a href="#XssMatchSetState">interface XssMatchSetState</a>

<a href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/byteMatchSet.ts">wafregional/byteMatchSet.ts</a> <a href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/geoMatchSet.ts">wafregional/geoMatchSet.ts</a> <a href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/ipSet.ts">wafregional/ipSet.ts</a> <a href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/rateBasedRule.ts">wafregional/rateBasedRule.ts</a> <a href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/regexMatchSet.ts">wafregional/regexMatchSet.ts</a> <a href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/regexPatternSet.ts">wafregional/regexPatternSet.ts</a> <a href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/rule.ts">wafregional/rule.ts</a> <a href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/ruleGroup.ts">wafregional/ruleGroup.ts</a> <a href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/sizeConstraintSet.ts">wafregional/sizeConstraintSet.ts</a> <a href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/sqlInjectionMatchSet.ts">wafregional/sqlInjectionMatchSet.ts</a> <a href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/webAcl.ts">wafregional/webAcl.ts</a> <a href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/webAclAssociation.ts">wafregional/webAclAssociation.ts</a> <a href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/xssMatchSet.ts">wafregional/xssMatchSet.ts</a> 


<h2 class="pdoc-module-header" id="ByteMatchSet">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/byteMatchSet.ts#L9">class ByteMatchSet</a>
</h2>

Provides a WAF Regional Byte Match Set Resource for use with Application Load Balancer.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/byteMatchSet.ts#L33">constructor</a>
</h3>

```typescript
new ByteMatchSet(name: string, args?: ByteMatchSetArgs, opts?: pulumi.CustomResourceOptions)
```


Create a ByteMatchSet resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/byteMatchSet.ts#L18">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: ByteMatchSetState): ByteMatchSet
```


Get an existing ByteMatchSet resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method getProvider</a>
</h3>

```typescript
getProvider(moduleMember: string): ProviderResource | undefined
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/byteMatchSet.ts#L29">property byteMatchTuples</a>
</h3>

```typescript
public byteMatchTuples: pulumi.Output<{ ... }[] | undefined>;
```


Settings for the ByteMatchSet, such as the bytes (typically a string that corresponds with ASCII characters) that you want AWS WAF to search for in web requests. ByteMatchTuple documented below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/byteMatchSet.ts#L25">property byte_match_tuple</a>
</h3>

```typescript
public byte_match_tuple: pulumi.Output<{ ... }[] | undefined>;
```


**Deprecated**, use `byte_match_tuples` instead.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/byteMatchSet.ts#L33">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```


The name or description of the ByteMatchSet.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h2 class="pdoc-module-header" id="GeoMatchSet">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/geoMatchSet.ts#L9">class GeoMatchSet</a>
</h2>

Provides a WAF Regional Geo Match Set Resource

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/geoMatchSet.ts#L29">constructor</a>
</h3>

```typescript
new GeoMatchSet(name: string, args?: GeoMatchSetArgs, opts?: pulumi.CustomResourceOptions)
```


Create a GeoMatchSet resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/geoMatchSet.ts#L18">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: GeoMatchSetState): GeoMatchSet
```


Get an existing GeoMatchSet resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method getProvider</a>
</h3>

```typescript
getProvider(moduleMember: string): ProviderResource | undefined
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/geoMatchSet.ts#L25">property geoMatchConstraints</a>
</h3>

```typescript
public geoMatchConstraints: pulumi.Output<{ ... }[] | undefined>;
```


The Geo Match Constraint objects which contain the country that you want AWS WAF to search for.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/geoMatchSet.ts#L29">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```


The name or description of the Geo Match Set.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h2 class="pdoc-module-header" id="IpSet">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/ipSet.ts#L9">class IpSet</a>
</h2>

Provides a WAF Regional IPSet Resource for use with Application Load Balancer.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/ipSet.ts#L33">constructor</a>
</h3>

```typescript
new IpSet(name: string, args?: IpSetArgs, opts?: pulumi.CustomResourceOptions)
```


Create a IpSet resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/ipSet.ts#L18">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: IpSetState): IpSet
```


Get an existing IpSet resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method getProvider</a>
</h3>

```typescript
getProvider(moduleMember: string): ProviderResource | undefined
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/ipSet.ts#L25">property arn</a>
</h3>

```typescript
public arn: pulumi.Output<string>;
```


The ARN of the WAF IPSet.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/ipSet.ts#L29">property ipSetDescriptors</a>
</h3>

```typescript
public ipSetDescriptors: pulumi.Output<{ ... }[] | undefined>;
```


One or more pairs specifying the IP address type (IPV4 or IPV6) and the IP address range (in CIDR notation) from which web requests originate.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/ipSet.ts#L33">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```


The name or description of the IPSet.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h2 class="pdoc-module-header" id="RateBasedRule">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/rateBasedRule.ts#L9">class RateBasedRule</a>
</h2>

Provides a WAF Rate Based Rule Resource

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/rateBasedRule.ts#L41">constructor</a>
</h3>

```typescript
new RateBasedRule(name: string, args: RateBasedRuleArgs, opts?: pulumi.CustomResourceOptions)
```


Create a RateBasedRule resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/rateBasedRule.ts#L18">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: RateBasedRuleState): RateBasedRule
```


Get an existing RateBasedRule resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method getProvider</a>
</h3>

```typescript
getProvider(moduleMember: string): ProviderResource | undefined
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/rateBasedRule.ts#L25">property metricName</a>
</h3>

```typescript
public metricName: pulumi.Output<string>;
```


The name or description for the Amazon CloudWatch metric of this rule.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/rateBasedRule.ts#L29">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```


The name or description of the rule.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/rateBasedRule.ts#L33">property predicates</a>
</h3>

```typescript
public predicates: pulumi.Output<{ ... }[] | undefined>;
```


One of ByteMatchSet, IPSet, SizeConstraintSet, SqlInjectionMatchSet, or XssMatchSet objects to include in a rule.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/rateBasedRule.ts#L37">property rateKey</a>
</h3>

```typescript
public rateKey: pulumi.Output<string>;
```


Valid value is IP.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/rateBasedRule.ts#L41">property rateLimit</a>
</h3>

```typescript
public rateLimit: pulumi.Output<number>;
```


The maximum number of requests, which have an identical value in the field specified by the RateKey, allowed in a five-minute period. Minimum value is 2000.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h2 class="pdoc-module-header" id="RegexMatchSet">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/regexMatchSet.ts#L9">class RegexMatchSet</a>
</h2>

Provides a WAF Regional Regex Match Set Resource

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/regexMatchSet.ts#L30">constructor</a>
</h3>

```typescript
new RegexMatchSet(name: string, args?: RegexMatchSetArgs, opts?: pulumi.CustomResourceOptions)
```


Create a RegexMatchSet resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/regexMatchSet.ts#L18">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: RegexMatchSetState): RegexMatchSet
```


Get an existing RegexMatchSet resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method getProvider</a>
</h3>

```typescript
getProvider(moduleMember: string): ProviderResource | undefined
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/regexMatchSet.ts#L25">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```


The name or description of the Regex Match Set.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/regexMatchSet.ts#L30">property regexMatchTuples</a>
</h3>

```typescript
public regexMatchTuples: pulumi.Output<{ ... }[] | undefined>;
```


The regular expression pattern that you want AWS WAF to search for in web requests,
the location in requests that you want AWS WAF to search, and other settings. See below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h2 class="pdoc-module-header" id="RegexPatternSet">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/regexPatternSet.ts#L9">class RegexPatternSet</a>
</h2>

Provides a WAF Regional Regex Pattern Set Resource

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/regexPatternSet.ts#L29">constructor</a>
</h3>

```typescript
new RegexPatternSet(name: string, args?: RegexPatternSetArgs, opts?: pulumi.CustomResourceOptions)
```


Create a RegexPatternSet resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/regexPatternSet.ts#L18">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: RegexPatternSetState): RegexPatternSet
```


Get an existing RegexPatternSet resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method getProvider</a>
</h3>

```typescript
getProvider(moduleMember: string): ProviderResource | undefined
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/regexPatternSet.ts#L25">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```


The name or description of the Regex Pattern Set.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/regexPatternSet.ts#L29">property regexPatternStrings</a>
</h3>

```typescript
public regexPatternStrings: pulumi.Output<string[] | undefined>;
```


A list of regular expression (regex) patterns that you want AWS WAF to search for, such as `B[a@]dB[o0]t`.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h2 class="pdoc-module-header" id="Rule">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/rule.ts#L9">class Rule</a>
</h2>

Provides an WAF Regional Rule Resource for use with Application Load Balancer.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/rule.ts#L33">constructor</a>
</h3>

```typescript
new Rule(name: string, args: RuleArgs, opts?: pulumi.CustomResourceOptions)
```


Create a Rule resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/rule.ts#L18">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: RuleState): Rule
```


Get an existing Rule resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method getProvider</a>
</h3>

```typescript
getProvider(moduleMember: string): ProviderResource | undefined
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/rule.ts#L25">property metricName</a>
</h3>

```typescript
public metricName: pulumi.Output<string>;
```


The name or description for the Amazon CloudWatch metric of this rule.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/rule.ts#L29">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```


The name or description of the rule.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/rule.ts#L33">property predicates</a>
</h3>

```typescript
public predicates: pulumi.Output<{ ... }[] | undefined>;
```


The objects to include in a rule.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h2 class="pdoc-module-header" id="RuleGroup">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/ruleGroup.ts#L9">class RuleGroup</a>
</h2>

Provides a WAF Regional Rule Group Resource

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/ruleGroup.ts#L33">constructor</a>
</h3>

```typescript
new RuleGroup(name: string, args: RuleGroupArgs, opts?: pulumi.CustomResourceOptions)
```


Create a RuleGroup resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/ruleGroup.ts#L18">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: RuleGroupState): RuleGroup
```


Get an existing RuleGroup resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method getProvider</a>
</h3>

```typescript
getProvider(moduleMember: string): ProviderResource | undefined
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/ruleGroup.ts#L25">property activatedRules</a>
</h3>

```typescript
public activatedRules: pulumi.Output<{ ... }[] | undefined>;
```


A list of activated rules, see below

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/ruleGroup.ts#L29">property metricName</a>
</h3>

```typescript
public metricName: pulumi.Output<string>;
```


A friendly name for the metrics from the rule group

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/ruleGroup.ts#L33">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```


A friendly name of the rule group

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h2 class="pdoc-module-header" id="SizeConstraintSet">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/sizeConstraintSet.ts#L9">class SizeConstraintSet</a>
</h2>

Provides a WAF Regional Size Constraint Set Resource for use with Application Load Balancer.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/sizeConstraintSet.ts#L29">constructor</a>
</h3>

```typescript
new SizeConstraintSet(name: string, args?: SizeConstraintSetArgs, opts?: pulumi.CustomResourceOptions)
```


Create a SizeConstraintSet resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/sizeConstraintSet.ts#L18">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: SizeConstraintSetState): SizeConstraintSet
```


Get an existing SizeConstraintSet resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method getProvider</a>
</h3>

```typescript
getProvider(moduleMember: string): ProviderResource | undefined
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/sizeConstraintSet.ts#L25">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```


The name or description of the Size Constraint Set.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/sizeConstraintSet.ts#L29">property sizeConstraints</a>
</h3>

```typescript
public sizeConstraints: pulumi.Output<{ ... }[] | undefined>;
```


Specifies the parts of web requests that you want to inspect the size of.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h2 class="pdoc-module-header" id="SqlInjectionMatchSet">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/sqlInjectionMatchSet.ts#L9">class SqlInjectionMatchSet</a>
</h2>

Provides a WAF Regional SQL Injection Match Set Resource for use with Application Load Balancer.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/sqlInjectionMatchSet.ts#L29">constructor</a>
</h3>

```typescript
new SqlInjectionMatchSet(name: string, args?: SqlInjectionMatchSetArgs, opts?: pulumi.CustomResourceOptions)
```


Create a SqlInjectionMatchSet resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/sqlInjectionMatchSet.ts#L18">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: SqlInjectionMatchSetState): SqlInjectionMatchSet
```


Get an existing SqlInjectionMatchSet resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method getProvider</a>
</h3>

```typescript
getProvider(moduleMember: string): ProviderResource | undefined
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/sqlInjectionMatchSet.ts#L25">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```


The name or description of the SizeConstraintSet.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/sqlInjectionMatchSet.ts#L29">property sqlInjectionMatchTuples</a>
</h3>

```typescript
public sqlInjectionMatchTuples: pulumi.Output<{ ... }[] | undefined>;
```


The parts of web requests that you want AWS WAF to inspect for malicious SQL code and, if you want AWS WAF to inspect a header, the name of the header.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h2 class="pdoc-module-header" id="WebAcl">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/webAcl.ts#L9">class WebAcl</a>
</h2>

Provides a WAF Regional Web ACL Resource for use with Application Load Balancer.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/webAcl.ts#L37">constructor</a>
</h3>

```typescript
new WebAcl(name: string, args: WebAclArgs, opts?: pulumi.CustomResourceOptions)
```


Create a WebAcl resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/webAcl.ts#L18">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: WebAclState): WebAcl
```


Get an existing WebAcl resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method getProvider</a>
</h3>

```typescript
getProvider(moduleMember: string): ProviderResource | undefined
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/webAcl.ts#L25">property defaultAction</a>
</h3>

```typescript
public defaultAction: pulumi.Output<{ ... }>;
```


The action that you want AWS WAF Regional to take when a request doesn't match the criteria in any of the rules that are associated with the web ACL.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/webAcl.ts#L29">property metricName</a>
</h3>

```typescript
public metricName: pulumi.Output<string>;
```


The name or description for the Amazon CloudWatch metric of this web ACL.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/webAcl.ts#L33">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```


The name or description of the web ACL.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/webAcl.ts#L37">property rules</a>
</h3>

```typescript
public rules: pulumi.Output<{ ... }[] | undefined>;
```


The rules to associate with the web ACL and the settings for each rule.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h2 class="pdoc-module-header" id="WebAclAssociation">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/webAclAssociation.ts#L11">class WebAclAssociation</a>
</h2>

Provides a resource to create an association between a WAF Regional WebACL and Application Load Balancer.

-> **Note:** An Application Load Balancer can only be associated with one WAF Regional WebACL.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/webAclAssociation.ts#L31">constructor</a>
</h3>

```typescript
new WebAclAssociation(name: string, args: WebAclAssociationArgs, opts?: pulumi.CustomResourceOptions)
```


Create a WebAclAssociation resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/webAclAssociation.ts#L20">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: WebAclAssociationState): WebAclAssociation
```


Get an existing WebAclAssociation resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method getProvider</a>
</h3>

```typescript
getProvider(moduleMember: string): ProviderResource | undefined
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/webAclAssociation.ts#L27">property resourceArn</a>
</h3>

```typescript
public resourceArn: pulumi.Output<string>;
```


Application Load Balancer ARN to associate with.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/webAclAssociation.ts#L31">property webAclId</a>
</h3>

```typescript
public webAclId: pulumi.Output<string>;
```


The ID of the WAF Regional WebACL to create an association.

<h2 class="pdoc-module-header" id="XssMatchSet">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/xssMatchSet.ts#L9">class XssMatchSet</a>
</h2>

Provides a WAF Regional XSS Match Set Resource for use with Application Load Balancer.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/xssMatchSet.ts#L29">constructor</a>
</h3>

```typescript
new XssMatchSet(name: string, args?: XssMatchSetArgs, opts?: pulumi.CustomResourceOptions)
```


Create a XssMatchSet resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/xssMatchSet.ts#L18">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: XssMatchSetState): XssMatchSet
```


Get an existing XssMatchSet resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method getProvider</a>
</h3>

```typescript
getProvider(moduleMember: string): ProviderResource | undefined
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/xssMatchSet.ts#L25">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```


The name of the set

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/xssMatchSet.ts#L29">property xssMatchTuples</a>
</h3>

```typescript
public xssMatchTuples: pulumi.Output<{ ... }[] | undefined>;
```


The parts of web requests that you want to inspect for cross-site scripting attacks.

<h2 class="pdoc-module-header" id="ByteMatchSetArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/byteMatchSet.ts#L81">interface ByteMatchSetArgs</a>
</h2>

The set of arguments for constructing a ByteMatchSet resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/byteMatchSet.ts#L89">property byteMatchTuples</a>
</h3>

```typescript
byteMatchTuples?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```


Settings for the ByteMatchSet, such as the bytes (typically a string that corresponds with ASCII characters) that you want AWS WAF to search for in web requests. ByteMatchTuple documented below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/byteMatchSet.ts#L85">property byte_match_tuple</a>
</h3>

```typescript
byte_match_tuple?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```


**Deprecated**, use `byte_match_tuples` instead.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/byteMatchSet.ts#L93">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


The name or description of the ByteMatchSet.

<h2 class="pdoc-module-header" id="ByteMatchSetState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/byteMatchSet.ts#L63">interface ByteMatchSetState</a>
</h2>

Input properties used for looking up and filtering ByteMatchSet resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/byteMatchSet.ts#L71">property byteMatchTuples</a>
</h3>

```typescript
byteMatchTuples?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```


Settings for the ByteMatchSet, such as the bytes (typically a string that corresponds with ASCII characters) that you want AWS WAF to search for in web requests. ByteMatchTuple documented below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/byteMatchSet.ts#L67">property byte_match_tuple</a>
</h3>

```typescript
byte_match_tuple?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```


**Deprecated**, use `byte_match_tuples` instead.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/byteMatchSet.ts#L75">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


The name or description of the ByteMatchSet.

<h2 class="pdoc-module-header" id="GeoMatchSetArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/geoMatchSet.ts#L71">interface GeoMatchSetArgs</a>
</h2>

The set of arguments for constructing a GeoMatchSet resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/geoMatchSet.ts#L75">property geoMatchConstraints</a>
</h3>

```typescript
geoMatchConstraints?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```


The Geo Match Constraint objects which contain the country that you want AWS WAF to search for.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/geoMatchSet.ts#L79">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


The name or description of the Geo Match Set.

<h2 class="pdoc-module-header" id="GeoMatchSetState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/geoMatchSet.ts#L57">interface GeoMatchSetState</a>
</h2>

Input properties used for looking up and filtering GeoMatchSet resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/geoMatchSet.ts#L61">property geoMatchConstraints</a>
</h3>

```typescript
geoMatchConstraints?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```


The Geo Match Constraint objects which contain the country that you want AWS WAF to search for.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/geoMatchSet.ts#L65">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


The name or description of the Geo Match Set.

<h2 class="pdoc-module-header" id="IpSetArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/ipSet.ts#L81">interface IpSetArgs</a>
</h2>

The set of arguments for constructing a IpSet resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/ipSet.ts#L85">property ipSetDescriptors</a>
</h3>

```typescript
ipSetDescriptors?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```


One or more pairs specifying the IP address type (IPV4 or IPV6) and the IP address range (in CIDR notation) from which web requests originate.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/ipSet.ts#L89">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


The name or description of the IPSet.

<h2 class="pdoc-module-header" id="IpSetState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/ipSet.ts#L63">interface IpSetState</a>
</h2>

Input properties used for looking up and filtering IpSet resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/ipSet.ts#L67">property arn</a>
</h3>

```typescript
arn?: pulumi.Input<string>;
```


The ARN of the WAF IPSet.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/ipSet.ts#L71">property ipSetDescriptors</a>
</h3>

```typescript
ipSetDescriptors?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```


One or more pairs specifying the IP address type (IPV4 or IPV6) and the IP address range (in CIDR notation) from which web requests originate.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/ipSet.ts#L75">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


The name or description of the IPSet.

<h2 class="pdoc-module-header" id="RateBasedRuleArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/rateBasedRule.ts#L110">interface RateBasedRuleArgs</a>
</h2>

The set of arguments for constructing a RateBasedRule resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/rateBasedRule.ts#L114">property metricName</a>
</h3>

```typescript
metricName: pulumi.Input<string>;
```


The name or description for the Amazon CloudWatch metric of this rule.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/rateBasedRule.ts#L118">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


The name or description of the rule.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/rateBasedRule.ts#L122">property predicates</a>
</h3>

```typescript
predicates?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```


One of ByteMatchSet, IPSet, SizeConstraintSet, SqlInjectionMatchSet, or XssMatchSet objects to include in a rule.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/rateBasedRule.ts#L126">property rateKey</a>
</h3>

```typescript
rateKey: pulumi.Input<string>;
```


Valid value is IP.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/rateBasedRule.ts#L130">property rateLimit</a>
</h3>

```typescript
rateLimit: pulumi.Input<number>;
```


The maximum number of requests, which have an identical value in the field specified by the RateKey, allowed in a five-minute period. Minimum value is 2000.

<h2 class="pdoc-module-header" id="RateBasedRuleState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/rateBasedRule.ts#L84">interface RateBasedRuleState</a>
</h2>

Input properties used for looking up and filtering RateBasedRule resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/rateBasedRule.ts#L88">property metricName</a>
</h3>

```typescript
metricName?: pulumi.Input<string>;
```


The name or description for the Amazon CloudWatch metric of this rule.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/rateBasedRule.ts#L92">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


The name or description of the rule.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/rateBasedRule.ts#L96">property predicates</a>
</h3>

```typescript
predicates?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```


One of ByteMatchSet, IPSet, SizeConstraintSet, SqlInjectionMatchSet, or XssMatchSet objects to include in a rule.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/rateBasedRule.ts#L100">property rateKey</a>
</h3>

```typescript
rateKey?: pulumi.Input<string>;
```


Valid value is IP.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/rateBasedRule.ts#L104">property rateLimit</a>
</h3>

```typescript
rateLimit?: pulumi.Input<number>;
```


The maximum number of requests, which have an identical value in the field specified by the RateKey, allowed in a five-minute period. Minimum value is 2000.

<h2 class="pdoc-module-header" id="RegexMatchSetArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/regexMatchSet.ts#L73">interface RegexMatchSetArgs</a>
</h2>

The set of arguments for constructing a RegexMatchSet resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/regexMatchSet.ts#L77">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


The name or description of the Regex Match Set.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/regexMatchSet.ts#L82">property regexMatchTuples</a>
</h3>

```typescript
regexMatchTuples?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```


The regular expression pattern that you want AWS WAF to search for in web requests,
the location in requests that you want AWS WAF to search, and other settings. See below.

<h2 class="pdoc-module-header" id="RegexMatchSetState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/regexMatchSet.ts#L58">interface RegexMatchSetState</a>
</h2>

Input properties used for looking up and filtering RegexMatchSet resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/regexMatchSet.ts#L62">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


The name or description of the Regex Match Set.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/regexMatchSet.ts#L67">property regexMatchTuples</a>
</h3>

```typescript
regexMatchTuples?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```


The regular expression pattern that you want AWS WAF to search for in web requests,
the location in requests that you want AWS WAF to search, and other settings. See below.

<h2 class="pdoc-module-header" id="RegexPatternSetArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/regexPatternSet.ts#L71">interface RegexPatternSetArgs</a>
</h2>

The set of arguments for constructing a RegexPatternSet resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/regexPatternSet.ts#L75">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


The name or description of the Regex Pattern Set.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/regexPatternSet.ts#L79">property regexPatternStrings</a>
</h3>

```typescript
regexPatternStrings?: pulumi.Input<pulumi.Input<string>[]>;
```


A list of regular expression (regex) patterns that you want AWS WAF to search for, such as `B[a@]dB[o0]t`.

<h2 class="pdoc-module-header" id="RegexPatternSetState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/regexPatternSet.ts#L57">interface RegexPatternSetState</a>
</h2>

Input properties used for looking up and filtering RegexPatternSet resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/regexPatternSet.ts#L61">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


The name or description of the Regex Pattern Set.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/regexPatternSet.ts#L65">property regexPatternStrings</a>
</h3>

```typescript
regexPatternStrings?: pulumi.Input<pulumi.Input<string>[]>;
```


A list of regular expression (regex) patterns that you want AWS WAF to search for, such as `B[a@]dB[o0]t`.

<h2 class="pdoc-module-header" id="RuleArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/rule.ts#L84">interface RuleArgs</a>
</h2>

The set of arguments for constructing a Rule resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/rule.ts#L88">property metricName</a>
</h3>

```typescript
metricName: pulumi.Input<string>;
```


The name or description for the Amazon CloudWatch metric of this rule.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/rule.ts#L92">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


The name or description of the rule.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/rule.ts#L96">property predicates</a>
</h3>

```typescript
predicates?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```


The objects to include in a rule.

<h2 class="pdoc-module-header" id="RuleGroupArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/ruleGroup.ts#L84">interface RuleGroupArgs</a>
</h2>

The set of arguments for constructing a RuleGroup resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/ruleGroup.ts#L88">property activatedRules</a>
</h3>

```typescript
activatedRules?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```


A list of activated rules, see below

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/ruleGroup.ts#L92">property metricName</a>
</h3>

```typescript
metricName: pulumi.Input<string>;
```


A friendly name for the metrics from the rule group

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/ruleGroup.ts#L96">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


A friendly name of the rule group

<h2 class="pdoc-module-header" id="RuleGroupState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/ruleGroup.ts#L66">interface RuleGroupState</a>
</h2>

Input properties used for looking up and filtering RuleGroup resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/ruleGroup.ts#L70">property activatedRules</a>
</h3>

```typescript
activatedRules?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```


A list of activated rules, see below

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/ruleGroup.ts#L74">property metricName</a>
</h3>

```typescript
metricName?: pulumi.Input<string>;
```


A friendly name for the metrics from the rule group

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/ruleGroup.ts#L78">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


A friendly name of the rule group

<h2 class="pdoc-module-header" id="RuleState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/rule.ts#L66">interface RuleState</a>
</h2>

Input properties used for looking up and filtering Rule resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/rule.ts#L70">property metricName</a>
</h3>

```typescript
metricName?: pulumi.Input<string>;
```


The name or description for the Amazon CloudWatch metric of this rule.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/rule.ts#L74">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


The name or description of the rule.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/rule.ts#L78">property predicates</a>
</h3>

```typescript
predicates?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```


The objects to include in a rule.

<h2 class="pdoc-module-header" id="SizeConstraintSetArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/sizeConstraintSet.ts#L71">interface SizeConstraintSetArgs</a>
</h2>

The set of arguments for constructing a SizeConstraintSet resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/sizeConstraintSet.ts#L75">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


The name or description of the Size Constraint Set.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/sizeConstraintSet.ts#L79">property sizeConstraints</a>
</h3>

```typescript
sizeConstraints?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```


Specifies the parts of web requests that you want to inspect the size of.

<h2 class="pdoc-module-header" id="SizeConstraintSetState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/sizeConstraintSet.ts#L57">interface SizeConstraintSetState</a>
</h2>

Input properties used for looking up and filtering SizeConstraintSet resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/sizeConstraintSet.ts#L61">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


The name or description of the Size Constraint Set.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/sizeConstraintSet.ts#L65">property sizeConstraints</a>
</h3>

```typescript
sizeConstraints?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```


Specifies the parts of web requests that you want to inspect the size of.

<h2 class="pdoc-module-header" id="SqlInjectionMatchSetArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/sqlInjectionMatchSet.ts#L71">interface SqlInjectionMatchSetArgs</a>
</h2>

The set of arguments for constructing a SqlInjectionMatchSet resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/sqlInjectionMatchSet.ts#L75">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


The name or description of the SizeConstraintSet.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/sqlInjectionMatchSet.ts#L79">property sqlInjectionMatchTuples</a>
</h3>

```typescript
sqlInjectionMatchTuples?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```


The parts of web requests that you want AWS WAF to inspect for malicious SQL code and, if you want AWS WAF to inspect a header, the name of the header.

<h2 class="pdoc-module-header" id="SqlInjectionMatchSetState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/sqlInjectionMatchSet.ts#L57">interface SqlInjectionMatchSetState</a>
</h2>

Input properties used for looking up and filtering SqlInjectionMatchSet resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/sqlInjectionMatchSet.ts#L61">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


The name or description of the SizeConstraintSet.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/sqlInjectionMatchSet.ts#L65">property sqlInjectionMatchTuples</a>
</h3>

```typescript
sqlInjectionMatchTuples?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```


The parts of web requests that you want AWS WAF to inspect for malicious SQL code and, if you want AWS WAF to inspect a header, the name of the header.

<h2 class="pdoc-module-header" id="WebAclArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/webAcl.ts#L97">interface WebAclArgs</a>
</h2>

The set of arguments for constructing a WebAcl resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/webAcl.ts#L101">property defaultAction</a>
</h3>

```typescript
defaultAction: pulumi.Input<{ ... }>;
```


The action that you want AWS WAF Regional to take when a request doesn't match the criteria in any of the rules that are associated with the web ACL.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/webAcl.ts#L105">property metricName</a>
</h3>

```typescript
metricName: pulumi.Input<string>;
```


The name or description for the Amazon CloudWatch metric of this web ACL.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/webAcl.ts#L109">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


The name or description of the web ACL.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/webAcl.ts#L113">property rules</a>
</h3>

```typescript
rules?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```


The rules to associate with the web ACL and the settings for each rule.

<h2 class="pdoc-module-header" id="WebAclAssociationArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/webAclAssociation.ts#L79">interface WebAclAssociationArgs</a>
</h2>

The set of arguments for constructing a WebAclAssociation resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/webAclAssociation.ts#L83">property resourceArn</a>
</h3>

```typescript
resourceArn: pulumi.Input<string>;
```


Application Load Balancer ARN to associate with.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/webAclAssociation.ts#L87">property webAclId</a>
</h3>

```typescript
webAclId: pulumi.Input<string>;
```


The ID of the WAF Regional WebACL to create an association.

<h2 class="pdoc-module-header" id="WebAclAssociationState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/webAclAssociation.ts#L65">interface WebAclAssociationState</a>
</h2>

Input properties used for looking up and filtering WebAclAssociation resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/webAclAssociation.ts#L69">property resourceArn</a>
</h3>

```typescript
resourceArn?: pulumi.Input<string>;
```


Application Load Balancer ARN to associate with.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/webAclAssociation.ts#L73">property webAclId</a>
</h3>

```typescript
webAclId?: pulumi.Input<string>;
```


The ID of the WAF Regional WebACL to create an association.

<h2 class="pdoc-module-header" id="WebAclState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/webAcl.ts#L75">interface WebAclState</a>
</h2>

Input properties used for looking up and filtering WebAcl resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/webAcl.ts#L79">property defaultAction</a>
</h3>

```typescript
defaultAction?: pulumi.Input<{ ... }>;
```


The action that you want AWS WAF Regional to take when a request doesn't match the criteria in any of the rules that are associated with the web ACL.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/webAcl.ts#L83">property metricName</a>
</h3>

```typescript
metricName?: pulumi.Input<string>;
```


The name or description for the Amazon CloudWatch metric of this web ACL.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/webAcl.ts#L87">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


The name or description of the web ACL.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/webAcl.ts#L91">property rules</a>
</h3>

```typescript
rules?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```


The rules to associate with the web ACL and the settings for each rule.

<h2 class="pdoc-module-header" id="XssMatchSetArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/xssMatchSet.ts#L71">interface XssMatchSetArgs</a>
</h2>

The set of arguments for constructing a XssMatchSet resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/xssMatchSet.ts#L75">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


The name of the set

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/xssMatchSet.ts#L79">property xssMatchTuples</a>
</h3>

```typescript
xssMatchTuples?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```


The parts of web requests that you want to inspect for cross-site scripting attacks.

<h2 class="pdoc-module-header" id="XssMatchSetState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/xssMatchSet.ts#L57">interface XssMatchSetState</a>
</h2>

Input properties used for looking up and filtering XssMatchSet resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/xssMatchSet.ts#L61">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


The name of the set

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/wafregional/xssMatchSet.ts#L65">property xssMatchTuples</a>
</h3>

```typescript
xssMatchTuples?: pulumi.Input<pulumi.Input<{ ... }>[]>;
```


The parts of web requests that you want to inspect for cross-site scripting attacks.

