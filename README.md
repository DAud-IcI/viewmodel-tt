# viewmodel-tt
XML &amp; T4 Template based generor for .Net ViewModels that implement INotifyPropertyChanged. With this template you can make a lot of dumb yet extensible (all are `partial`) ViewModel classes for WPF and other projects that rely on `System.Componentmodel` and manage them all from a central position.

## Installation and usage

1. Download the [ViewModel.tt](ViewModel.tt) file into your project.
2. Create a [ViewModel.xml](ViewModel.xml) file in the same directory or download the example in this repository.
3. (Optional) Download the [ViewModel.xsd](ViewModel.xsd) file as well and [reference it](https://msdn.microsoft.com/en-us/library/ms757863(v=vs.85).aspx) in the XML file to get IntelliSense completion and tooltips.
4. Edit the XML file, then save the TT file to generate your classes.
5. Add the generated C# files to the project.

## Future plans

* Figure out how to automatically add generated files to the project.
* Create a Visual Studio extension for this.