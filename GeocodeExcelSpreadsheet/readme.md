## Geocode Microsoft Excel (.xlsx) Spreadsheet Workflow Example

This Geocortex Workflow demonstrates how to:

1. Accept a Microsoft Excel (.xlsx) file
2. Parse the columns
3. Prompt the user to select the geocoding fields (address, city, state, zip)
4. Execute a Web Request directly to Bing's Geocoder
5. Parse the Bing Response
6. Add X and Y columns onto the table
7. Convert the datatable to a featureset with all attributes and creating geometries.

A live demonstration of this workflow in action available on the [DDS Demonstration Viewer](https://maperture.digitaldataservices.com/gvh_custom/). The workflow is available for Desktop applications under the Toolbar => Workflow Examples => Geocode XLXS.

*WARNING: This workflow was put together in only a couple hours and it is pretty messy. Some day we will refactor the code and put in better descriptions. But it should be helpful in the meantime.*

#### Requirements

You must get your own [Bing Maps API Key](https://msdn.microsoft.com/en-us/library/ff428642.aspx) to run this workflow.

### History

2016-08-17 - Initial upload.


### Credits

[Digital Data Services, Inc.](http://www.digitaldataservices.com/geocortex), is a Geocortex Implementation Solution Provider and Esri Silver Business Partner that specializes in the creation, conversion, management, integration, and presentation of geospatial information. Our expertise focuses on providing simple solutions to complex business challenges and allowing our clients to leverage and explore their data in new and unique ways. As experts in research, data processing, data storage/management, data analysis, and presentation, we serve our clients by making complex analytical decisions available to everyone. Our vision is that access to geospatial information should not be a barrier to making business decisions.

[Geocortex](http://www.geocortex.com/) and Latitude Geographics are registered trademarks of [Latitude Geographics Group Ltd.](http://www.latitudegeo.com/) in the United States and Canada, and are trademarks in other jurisdictions around the world.

### License

Copyright &copy; 2016 [Digital Data Services, Inc.](http://www.digitaldataservices.com/geocortex) All Rights Reserved.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
