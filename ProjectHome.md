jqSelecta renders a scrollable tabular view of a `<select>` HTML element's `<option>`s.

Useful for large data sets (with an arbitrary number of columns, as well as optional _select all_, _select none_ and _invert selection_ buttons) and also where you'd like the form elements to conform to the UI (i.e. themeroller skin).

It's non-destructive, in that the underlying form element isn't destroyed - the plugin maintains the state of the underlying select-option, so plain form submission will work and other JS components can access the select-option's state without tight coupling to the jqSelecta plugin.

State optionally persisted using cookies, and, in multi-select mode the cancel button reverts to previous selection.

For a full list of features/options see the [wiki](http://code.google.com/p/jqselecta/w/list).

Notes:
  * This plugin is themeroller compatible as of jQueryUI 1.7
  * Currently this is quite a new project, i'll happily fix any bugs reported while it's still fresh =)
  * **Release 0.3 is now available**


<table>
<tr><td width='33%'>
<wiki:gadget url="http://www.ohloh.net/p/jqselecta/widgets/project_users.xml?style=green" height="100"  border="0" /><br>
<br>
</td><td width='33%'>
<a href='http://jqueryui.com/themeroller/'><img src='http://dl.getdropbox.com/u/2465717/jqselecta-0.3/img/themeroller_ready_white_200px.png' alt='Theme Roller ready' title='Theme Roller ready' /></a>
</td><td width='33%' align='right'>

<a href='https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=4X72JCN3E2PU2&lc=GB&item_name=earcam&item_number=jqselecta&currency_code=GBP&bn=PP%2dDonationsBF%3abtn_donateCC_LG%2egif%3aNonHosted'><img src='https://www.paypal.com/en_US/GB/i/btn/btn_donateCC_LG.gif' border='0' /></a>

</td></tr>
</table>