## Create a simple Effects View

This section explains how to create a Effects View and configure it. The control can be configured entirely in C# code or by the XAML markup.

### Adding a SfEffectsView control

Step 1: Add the NuGet to the project as discussed in the above reference section. 

Step 2: Add the namespace as shown in the following code sample.

**XAML**

```
    xmlns:effectsView="clr-namespace:Syncfusion.Maui.Core;assembly=Syncfusion.Maui.Core"	
```

**C#**

```
    using Syncfusion.Maui.Core;
```

Step 3: Set the control to content in `ContentPage`.

**XAML**

```
<ContentPage.Content> 
	 <effectsView:SfEffectsView /> 
</ContentPage.Content>  

```

**C#**

```

namespace EffectsViewMauiSample   
{  
	public partial class MainPage : ContentPage                  
	{ 
	    SfEffectsView effectsView;

		public MainPage()   
		{   
			InitializeComponent();       
			effectsView = new SfEffectsView(); 
			this.Content = effectsView;  
		}  
	}  
}  

```
