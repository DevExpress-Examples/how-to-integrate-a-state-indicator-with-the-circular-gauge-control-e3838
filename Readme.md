<!-- default file list -->
*Files to look at*:

* [MainPage.xaml](./CS/SilverlightApplication1/MainPage.xaml) (VB: [MainPage.xaml](./VB/SilverlightApplication1/MainPage.xaml))
<!-- default file list end -->
# How to integrate a State Indicator with the Circular Gauge control  
<!-- run online -->
**[[Run Online]](https://codecentral.devexpress.com/e3838)**
<!-- run online end -->


<p>The following sample shows how a State Indicator control can be integrated with the Circular Gauge control. This integration forces the State Indicator control to automatically change its state every time when a Value Indicator enters into a new range on a Circular Gauge.</p><br />



<h3>Description</h3>

<p>For this, it is necessary to bind a State Indicator control to any value indicator of the Circular Gauge control (e.g., to a needle element) using the  <a href="http://help.devexpress.com/#WPF/DevExpressXpfGaugesAnalogGaugeControl_ValueIndicatortopic"><u>AnalogGaugeControl.ValueIndicator</u></a> attached property.  </p><p>You also need to add range elements to the scale of the Circular Gauge and specify<strong> </strong>states of the State Indicator control that correspond to these elements.</p><br />


<br/>


