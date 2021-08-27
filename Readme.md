<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128533300/13.2.6%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/E5057)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* [Default.aspx](./CS/WebSite/Default.aspx) (VB: [Default.aspx](./VB/WebSite/Default.aspx))
* [Default.aspx.cs](./CS/WebSite/Default.aspx.cs) (VB: [Default.aspx.vb](./VB/WebSite/Default.aspx.vb))
<!-- default file list end -->
# ASPxGridView - How to allow end-users to resize the grid
<!-- run online -->
**[[Run Online]](https://codecentral.devexpress.com/e5057/)**
<!-- run online end -->


<p>The scenario is the following:<br />
- Set the ASPxGridView.SettingsPager.Mode property to 'ShowAllRecords';</p><p>- Set the ASPxGridView.Settings.ShowStatusBar to 'Visible' and the ASPxGridView.Settings.VerticalScrollBarMode property to 'Auto';</p><p>- Change the ASPxGridView's height and width in the mouse move event handler.</p><p><br />
The example supports both postponed (when the control's frame is rendered and resized on mouse move, and the control is actually resized after the mouse button is released) and real time resizing (when the control is resized on mouse move). Set the 'postpone' JavaScript variable to 'false', to allow real time resizing.</p><p><strong>See also</strong><strong></strong></p><p><strong></strong><a href="https://www.devexpress.com/Support/Center/p/E5152">GridView - How to allow end-users to resize the grid(MVC)</a></p>

<br/>


