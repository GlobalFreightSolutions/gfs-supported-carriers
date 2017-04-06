

# &lt;gfs-supported-carriers&gt;

The `gfs-supported-carrier` element renders a banner showing a configured set of carrier icons.

## Install

```bash
# via bower
$ bower install --save gfs-supported-carrier
```

## Usage

1. Import Web Components' polyfill:

```html
<script src="bower_components/webcomponentsjs/webcomponents-lite.js"></script>
```

2. Import Custom Element:

```html
<link rel="import" href="bower_components/gfs-supported-carrier/gfs-supported-carrier.html">
```

3. Start using it!

<!---
```
<custom-element-demo>
    <template>
        <script src="../webcomponentsjs/webcomponents-lite.js"></script>
        <link rel="import" href="gfs-supported-carrier.html">
        <next-code-block></next-code-block>
    </template>
</custom-element-demo>
```
-->

```html
<gfs-supported-carriers
	carriers="dpd inpost doddle hermes yodel anpost arrowxl correos dhlexpress"
	title="Our carriers"
    country-code="GB">
</gfs-supported-carriers>
```

More info and all the available properties can be found at [GFS widget portal](http://gfsdeveloperportal.azurewebsites.net/documentation/gfs-checkout/the-gfs-checkout-widgets/supported-carriers-widget/ "The Supported Carriers Widget")


## License

[Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0.html)