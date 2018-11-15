<!-- default file list -->
*Files to look at*:

* [Default.aspx](./CS/WebSite/Default.aspx) (VB: [Default.aspx.vb](./VB/WebSite/Default.aspx.vb))
* [Default.aspx.cs](./CS/WebSite/Default.aspx.cs) (VB: [Default.aspx.vb](./VB/WebSite/Default.aspx.vb))
<!-- default file list end -->
# ASPxGridView - How to allow end-users to resize the grid


<p>The scenario is the following:<br />
- Set the ASPxGridView.SettingsPager.Mode property to 'ShowAllRecords';</p><p>- Set the ASPxGridView.Settings.ShowStatusBar to 'Visible' and the ASPxGridView.Settings.VerticalScrollBarMode property to 'Auto';</p><p>- Change the ASPxGridView's height and width in the mouse move event handler.</p><p><br />
The example supports both postponed (when the control's frame is rendered and resized on mouse move, and the control is actually resized after the mouse button is released) and real time resizing (when the control is resized on mouse move). Set the 'postpone' JavaScript variable to 'false', to allow real time resizing.</p><p><strong>See also</strong><strong></strong></p><p><strong></strong><a href="https://www.devexpress.com/Support/Center/p/E5152">GridView - How to allow end-users to resize the grid(MVC)</a></p>

<br/>


