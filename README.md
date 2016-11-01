# Visio JavaScript APIs 1.1
**Applies to**: Visio Online
Welcome to the Visio JavaScript API documentation. Here you can find everything you need to know about Visio Online extensibility. Enabling Visio JavaScript APIs is the first step in making Visio Online extensible.
**Note:** The Visio JavaScript APIs are currently in preview and are subject to change. The Visio JavaScript APIs are not currently supported for use in production environments.
## Using Visio JavaScript APIs with embedded Visio diagrams
An embedded Microsoft Visio diagram is a diagram that is stored in a Microsoft SharePoint document library and displayed inside a SharePoint web page. One way to embed is to display the Visio diagram in an HTML &lt;iframe&gt; element. Then you can use Visio JavaScript APIs to programmatically work with the embedded diagram.

![A web page wtih embedded Visio diagram in an iframe followed by JavaScript code](/images/visio-embedded-diagram.jpg)

## Give us your feedback
The following links describe a subset of the Visio JavaScript APIs that are being planned as part of the first release. Please review and provide your feedback. One of the best ways of providing your input is by opening new issue in GitHub using the links available below.

   **Note:** The following features are still in a design and review phase, and hence not yet available as part of the product. The final design is subject to change. Once the feature is made available, the final specification will be published as part of the master repository.

|Object| What is new| Description|Feedback|
|:----|:----|:----|:----|
|[application](reference/visio/application.md)|_Property_ > showToolbars|Show or Hide the standard toolbars.|[Go](https://github.com/OfficeDev/office-js-docs/issues/new?title=application-showToolbars)|
|[application](resources/application.md)|_Method_ > [load(param: object)](resources/application.md#loadparam-object)|Fills the proxy object created in JavaScript layer with property and object values specified in the parameter.|[Go](https://github.com/OfficeDev/office-js-docs/issues/new?title=OpenSpec-application-load)|
|[document](resources/document.md)|_Relationship_ > application|Represents a Visio application instance that contains this document. Read-only.|[Go](https://github.com/OfficeDev/office-js-docs/issues/new?title=document-application)|
|[document](resources/document.md)|_Relationship_ > pages|Represents a collection of pages associated with the document. Read-only.|[Go](https://github.com/OfficeDev/office-js-docs/issues/new?title=document-pages)|
|[document](resources/document.md)|_Relationship_ > view|Returns the DocumentView object. Read-only.|[Go](https://github.com/OfficeDev/office-js-docs/issues/new?title=document-view)|
|[document](resources/document.md)|_Method_ > [getActivePage()](resources/document.md#getactivepage)|Returns the Active Page of the document.|[Go](https://github.com/OfficeDev/office-js-docs/issues/new?title=OpenSpec-document-getActivePage)|
|[document](resources/document.md)|_Method_ > [load(param: object)](resources/document.md#loadparam-object)|Fills the proxy object created in JavaScript layer with property and object values specified in the parameter.|[Go](https://github.com/OfficeDev/office-js-docs/issues/new?title=OpenSpec-document-load)|
|[document](resources/document.md)|_Method_ > [setActivePage(PageName: string)](resources/document.md#setactivepagepagename-string)|Set the Active Page of the document.|[Go](https://github.com/OfficeDev/office-js-docs/issues/new?title=OpenSpec-document-setActivePage)|
|[document](resources/document.md)|_Method_ > [startDataRefresh()](resources/document.md#startdatarefresh)|Triggers the refresh of the data in the Diagram, for all pages.|[Go](https://github.com/OfficeDev/office-js-docs/issues/new?title=OpenSpec-document-startDataRefresh)|
|[documentView](resources/documentview.md)|_Property_ > disableHyperlinks|Disable Hyperlinks.|[Go](https://github.com/OfficeDev/office-js-docs/issues/new?title=documentView-disableHyperlinks)|
|[documentView](resources/documentview.md)|_Method_ > [load(param: object)](resources/documentview.md#loadparam-object)|Fills the proxy object created in JavaScript layer with property and object values specified in the parameter.|[Go](https://github.com/OfficeDev/office-js-docs/issues/new?title=OpenSpec-documentView-load)|
|[highlightData](resources/highlightdata.md)|_Property_ > color|A string that specifies the color of the highlight. It must have the form "#RRGGBB", where each letter represents a hexadecimal digit between 0 and F, and where RR is the red value between 0 and 0xFF (255), GG the green value between 0 and 0xFF (255), and BB is the blue value between 0 and 0xFF (255).|[Go](https://github.com/OfficeDev/office-js-docs/issues/new?title=highlightData-color)|
|[highlightData](resources/highlightdata.md)|_Property_ > width|A positive integer that specifies the width of the highlight's stroke in pixels.|[Go](https://github.com/OfficeDev/office-js-docs/issues/new?title=highlightData-width)|
|[highlightData](resources/highlightdata.md)|_Method_ > [load(param: object)](resources/highlightdata.md#loadparam-object)|Fills the proxy object created in JavaScript layer with property and object values specified in the parameter.|[Go](https://github.com/OfficeDev/office-js-docs/issues/new?title=OpenSpec-highlightData-load)|
|[hyperlink](resources/hyperlink.md)|_Property_ > address|Gets the address for a shape's Hyperlink object, the address to which the hyperlink navigates. Read-only.|[Go](https://github.com/OfficeDev/office-js-docs/issues/new?title=hyperlink-address)|
|[hyperlink](resources/hyperlink.md)|_Property_ > description|Gets the description of a hyperlink. Read-only.|[Go](https://github.com/OfficeDev/office-js-docs/issues/new?title=hyperlink-description)|
|[hyperlink](resources/hyperlink.md)|_Property_ > name|Hyperlink name. Read-only.|[Go](https://github.com/OfficeDev/office-js-docs/issues/new?title=hyperlink-name)|
|[hyperlink](resources/hyperlink.md)|_Method_ > [load(param: object)](resources/hyperlink.md#loadparam-object)|Fills the proxy object created in JavaScript layer with property and object values specified in the parameter.|[Go](https://github.com/OfficeDev/office-js-docs/issues/new?title=OpenSpec-hyperlink-load)|
|[hyperlinkCollection](resources/hyperlinkcollection.md)|_Property_ > items|A collection of hyperlink objects. Read-only.|[Go](https://github.com/OfficeDev/office-js-docs/issues/new?title=hyperlinkCollection-items)|
|[hyperlinkCollection](resources/hyperlinkcollection.md)|_Method_ > [getCount()](resources/hyperlinkcollection.md#getcount)|Gets the number of hyperlinks.|[Go](https://github.com/OfficeDev/office-js-docs/issues/new?title=OpenSpec-hyperlinkCollection-getCount)|
|[hyperlinkCollection](resources/hyperlinkcollection.md)|_Method_ > [getItem(Key: number or string)](resources/hyperlinkcollection.md#getitemkey-number-or-string)|Gets a Hyperlink using its key (name or Id).|[Go](https://github.com/OfficeDev/office-js-docs/issues/new?title=OpenSpec-hyperlinkCollection-getItem)|
|[hyperlinkCollection](resources/hyperlinkcollection.md)|_Method_ > [load(param: object)](resources/hyperlinkcollection.md#loadparam-object)|Fills the proxy object created in JavaScript layer with property and object values specified in the parameter.|[Go](https://github.com/OfficeDev/office-js-docs/issues/new?title=OpenSpec-hyperlinkCollection-load)|
|[page](resources/page.md)|_Property_ > index|Index of the Page. Read-only.|[Go](https://github.com/OfficeDev/office-js-docs/issues/new?title=page-index)|
|[page](resources/page.md)|_Property_ > isBackground|Whether the page is a background page or not. Read-only.|[Go](https://github.com/OfficeDev/office-js-docs/issues/new?title=page-isBackground)|
|[page](resources/page.md)|_Property_ > name|Page name. Read-only.|[Go](https://github.com/OfficeDev/office-js-docs/issues/new?title=page-name)|
|[page](resources/page.md)|_Relationship_ > shapes|Shapes in the Page. Read-only.|[Go](https://github.com/OfficeDev/office-js-docs/issues/new?title=page-shapes)|
|[page](resources/page.md)|_Relationship_ > view|Returns the view of the page. Read-only.|[Go](https://github.com/OfficeDev/office-js-docs/issues/new?title=page-view)|
|[page](resources/page.md)|_Method_ > [activate()](resources/page.md#activate)|Set the page as Active Page of the document.|[Go](https://github.com/OfficeDev/office-js-docs/issues/new?title=OpenSpec-page-activate)|
|[page](resources/page.md)|_Method_ > [load(param: object)](resources/page.md#loadparam-object)|Fills the proxy object created in JavaScript layer with property and object values specified in the parameter.|[Go](https://github.com/OfficeDev/office-js-docs/issues/new?title=OpenSpec-page-load)|
|[pageCollection](resources/pagecollection.md)|_Property_ > items|A collection of page objects. Read-only.|[Go](https://github.com/OfficeDev/office-js-docs/issues/new?title=pageCollection-items)|
|[pageCollection](resources/pagecollection.md)|_Method_ > [getCount()](resources/pagecollection.md#getcount)|Gets the number of pages in the collection.|[Go](https://github.com/OfficeDev/office-js-docs/issues/new?title=OpenSpec-pageCollection-getCount)|
|[pageCollection](resources/pagecollection.md)|_Method_ > [getItem(key: number or string)](resources/pagecollection.md#getitemkey-number-or-string)|Gets a page using its key (name or Id).|[Go](https://github.com/OfficeDev/office-js-docs/issues/new?title=OpenSpec-pageCollection-getItem)|
|[pageCollection](resources/pagecollection.md)|_Method_ > [load(param: object)](resources/pagecollection.md#loadparam-object)|Fills the proxy object created in JavaScript layer with property and object values specified in the parameter.|[Go](https://github.com/OfficeDev/office-js-docs/issues/new?title=OpenSpec-pageCollection-load)|
|[pageView](resources/pageview.md)|_Relationship_ > zoom|GetSet Page's Zoom level.|[Go](https://github.com/OfficeDev/office-js-docs/issues/new?title=pageView-zoom)|
|[pageView](resources/pageview.md)|_Method_ > [centerViewportOnShape(ShapeId: number)](resources/pageview.md#centerviewportonshapeshapeid-number)|Pans the Visio drawing to place the specified shape in the center of the view.|[Go](https://github.com/OfficeDev/office-js-docs/issues/new?title=OpenSpec-pageView-centerViewportOnShape)|
|[pageView](resources/pageview.md)|_Method_ > [isShapeInViewport(Shape: Shape)](resources/pageview.md#isshapeinviewportshape-shape)|To check if the shape is in view of the page or not.|[Go](https://github.com/OfficeDev/office-js-docs/issues/new?title=OpenSpec-pageView-isShapeInViewport)|
|[pageView](resources/pageview.md)|_Method_ > [load(param: object)](resources/pageview.md#loadparam-object)|Fills the proxy object created in JavaScript layer with property and object values specified in the parameter.|[Go](https://github.com/OfficeDev/office-js-docs/issues/new?title=OpenSpec-pageView-load)|
|[shape](resources/shape.md)|_Property_ > name|Shape's name. Read-only.|[Go](https://github.com/OfficeDev/office-js-docs/issues/new?title=shape-name)|
|[shape](resources/shape.md)|_Property_ > text|Shape's Text. Read-only.|[Go](https://github.com/OfficeDev/office-js-docs/issues/new?title=shape-text)|
|[shape](resources/shape.md)|_Relationship_ > hyperlinks|Returns the Hyperlinks collection for a Shape object. Read-only.|[Go](https://github.com/OfficeDev/office-js-docs/issues/new?title=shape-hyperlinks)|
|[shape](resources/shape.md)|_Relationship_ > shapeDataItems|Returns the Shape's Data Section. Read-only.|[Go](https://github.com/OfficeDev/office-js-docs/issues/new?title=shape-shapeDataItems)|
|[shape](resources/shape.md)|_Relationship_ > view|Returns the view of the shape. Read-only.|[Go](https://github.com/OfficeDev/office-js-docs/issues/new?title=shape-view)|
|[shape](resources/shape.md)|_Method_ > [load(param: object)](resources/shape.md#loadparam-object)|Fills the proxy object created in JavaScript layer with property and object values specified in the parameter.|[Go](https://github.com/OfficeDev/office-js-docs/issues/new?title=OpenSpec-shape-load)|
|[shapeCollection](resources/shapecollection.md)|_Property_ > items|A collection of shape objects. Read-only.|[Go](https://github.com/OfficeDev/office-js-docs/issues/new?title=shapeCollection-items)|
|[shapeCollection](resources/shapecollection.md)|_Method_ > [getCount()](resources/shapecollection.md#getcount)|Gets the number of Shapes in the collection.|[Go](https://github.com/OfficeDev/office-js-docs/issues/new?title=OpenSpec-shapeCollection-getCount)|
|[shapeCollection](resources/shapecollection.md)|_Method_ > [getItem(key: number or string)](resources/shapecollection.md#getitemkey-number-or-string)|Gets a Shape using its key (name or Index).|[Go](https://github.com/OfficeDev/office-js-docs/issues/new?title=OpenSpec-shapeCollection-getItem)|
|[shapeCollection](resources/shapecollection.md)|_Method_ > [load(param: object)](resources/shapecollection.md#loadparam-object)|Fills the proxy object created in JavaScript layer with property and object values specified in the parameter.|[Go](https://github.com/OfficeDev/office-js-docs/issues/new?title=OpenSpec-shapeCollection-load)|
|[shapeDataItem](resources/shapedataitem.md)|_Property_ > label|Label. Read-only.|[Go](https://github.com/OfficeDev/office-js-docs/issues/new?title=shapeDataItem-label)|
|[shapeDataItem](resources/shapedataitem.md)|_Property_ > name|Name. Read-only.|[Go](https://github.com/OfficeDev/office-js-docs/issues/new?title=shapeDataItem-name)|
|[shapeDataItem](resources/shapedataitem.md)|_Property_ > value|Value. Read-only.|[Go](https://github.com/OfficeDev/office-js-docs/issues/new?title=shapeDataItem-value)|
|[shapeDataItem](resources/shapedataitem.md)|_Method_ > [load(param: object)](resources/shapedataitem.md#loadparam-object)|Fills the proxy object created in JavaScript layer with property and object values specified in the parameter.|[Go](https://github.com/OfficeDev/office-js-docs/issues/new?title=OpenSpec-shapeDataItem-load)|
|[shapeDataItemCollection](resources/shapedataitemcollection.md)|_Property_ > items|A collection of shapeDataItem objects. Read-only.|[Go](https://github.com/OfficeDev/office-js-docs/issues/new?title=shapeDataItemCollection-items)|
|[shapeDataItemCollection](resources/shapedataitemcollection.md)|_Method_ > [getCount()](resources/shapedataitemcollection.md#getcount)|Gets the number of Shape Data Items.|[Go](https://github.com/OfficeDev/office-js-docs/issues/new?title=OpenSpec-shapeDataItemCollection-getCount)|
|[shapeDataItemCollection](resources/shapedataitemcollection.md)|_Method_ > [getItem(key: string)](resources/shapedataitemcollection.md#getitemkey-string)|Gets the ShapeDataItem using its name.|[Go](https://github.com/OfficeDev/office-js-docs/issues/new?title=OpenSpec-shapeDataItemCollection-getItem)|
|[shapeDataItemCollection](resources/shapedataitemcollection.md)|_Method_ > [load(param: object)](resources/shapedataitemcollection.md#loadparam-object)|Fills the proxy object created in JavaScript layer with property and object values specified in the parameter.|[Go](https://github.com/OfficeDev/office-js-docs/issues/new?title=OpenSpec-shapeDataItemCollection-load)|
|[shapeView](resources/shapeview.md)|_Relationship_ > highlight|Represents the highlight around the shape.|[Go](https://github.com/OfficeDev/office-js-docs/issues/new?title=shapeView-highlight)|
|[shapeView](resources/shapeview.md)|_Method_ > [load(param: object)](resources/shapeview.md#loadparam-object)|Fills the proxy object created in JavaScript layer with property and object values specified in the parameter.|[Go](https://github.com/OfficeDev/office-js-docs/issues/new?title=OpenSpec-shapeView-load)|
## Copyright
Copyright (c) 2016 Microsoft Corporation. All rights reserved.
