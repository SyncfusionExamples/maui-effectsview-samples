## Create a simple Effects View

This section explains how to create a Effects View and configure it. The control can be configured entirely in C# code or by the XAML markup.

### Adding a SfEffectsView control

Step 1: Add the NuGet to the project as discussed in the above reference section. 

Step 2: Add the namespace as shown in the following code sample.

{% tabs %}

{% highlight xaml %}

    xmlns:effectsView="clr-namespace:Syncfusion.Maui.Core;assembly=Syncfusion.Maui.Core"
	
{% endhighlight %}

{% highlight C# %}

    using Syncfusion.Maui.Core;

{% endhighlight %}

{% endtabs %}

Step 3: Set the control to content in `ContentPage`.

{% tabs %}

{% highlight xaml %}

<ContentPage.Content> 
	 <effectsView:SfEffectsView /> 
</ContentPage.Content>  


{% endhighlight %}

{% highlight c# %}

using Syncfusion.Maui.Core;

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

{% endhighlight %}

{% endtabs %}
