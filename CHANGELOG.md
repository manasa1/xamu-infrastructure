## [1.6.0]
### Breaking changes
- Refined namespaces - might need to change some `using` statements.
- Removed `BindablePicker` as the support is now included in Xamarin.Forms. The source is still in the repo if anyone needs it.

### Other changes
- Simplified and cleaned up some code 
- Added a few new converters
- Added `WrapLayout` from Xamarin docs
- Added support to `ItemsControl` to replace the panel

## [1.5.0]
- Replaced PCL support with .NET Standard 1.0 and 2.0
- Added `Orientation` and `Spacing` properties to `ItemsControl`
- Fixed bug in `ItemsControl` when the `DataTemplate` is applied _after_ the `ItemsSource`

## [1.1.0]
- Added support for PCL and .NET Standard
- Added ability to reset navigation  stack

## [1.0.161128]
- Add class constraint to Register method of IDependencyService
        
## [1.0.161104]
- Unify versions

## [1.0.160930]
- Added new `Register` method to `IDependencyService` to allow instance registration.

## [1.0.160916]
- Initial release of Core - broken out from **XamU.Infrastructure.dll** with no dependencies on Xamarin.Forms.