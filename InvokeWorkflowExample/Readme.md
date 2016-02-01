# Invoke Workflow Example

Demonstrates how to pass a variable from one Geocortex Workflow to another and receive a result.

This example illustrates how to request a string from a user. Pass that string to another workflow using the `Invoke Workflow` module where the string is converted to uppercase and returned. The result is then displayed to the user.

## Installation

Copy both the `CallWorkflowsExample.xaml` and `ToUpper.xaml` to a location where you can open them with Geocortex Workflow Designer. You **must** set the `Workflow Xaml Uri` path to the absolute path of the `ToUpper.xaml`. Sorry still haven't figured out a workaround to use relative pathing in WPF. 

## History

2016-02-01 - Initial upload

## Credits

Copyright &copy; 2016 [Digital Data Services, Inc.](http://www.digitaldataservices.com/geocortex)

## License

No License. You are free to use this code however you wish.