<!-- default file list -->
*Files to look at*:

* [Window1.xaml](./CS/Window1.xaml) (VB: [Window1.xaml](./VB/Window1.xaml))
<!-- default file list end -->
# How to bind a chart to an XML data source using the XPath property


<p>The following example demonstrates how to bind a chart to an XML data source using the XPath property.</p><p>To accomplish this task, it is necessary to add an <strong>XmlDataProvider</strong> object to a collection of the window's static resources, then assign this resource to a series' <strong>DataSource</strong> property using the <strong>XPath</strong> key to define the path to a specific XML node, and then set the <strong>ArgumentDataMember</strong> and <strong>ValueDataMember</strong> properties to the names of XML elements that should provide data for arguments and values.</p><p>Note that this approach to data binding is done completely in XAML, and no code-behind file is required.</p>

<br/>


