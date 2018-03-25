# HttpRequest #
[https://docs.djangoproject.com/en/2.0/ref/request-response/#django.http.HttpRequest](https://docs.djangoproject.com/en/2.0/ref/request-response/#django.http.HttpRequest)

## Attributes ##

<table>
<tr>
<th>Attribute</th>
<th>Description</th>
<th>From</th>
</tr>

<tr><td colspan='3'>Attributes set by middleware</td></tr>
<tr>
<td>user</td>
<td>An instance of AUTH_USER_MODEL representing the currently logged-in user. If the user isn’t currently logged in, user will be set to an instance of AnonymousUser.</td>
<td>AuthenticationMiddleware</td>
</tr>

<tr>
<td>session</td>
<td>A readable and writable, dictionary-like object that represents the current session.</td>
<td>SessionMiddleware</td>
</tr>

<tr>
<td>site</td>
<td>An instance of Site or RequestSite as returned by get_current_site() representing the current site.</td>
<td>CurrentSiteMiddleware</td>
</tr>

<tr>
<td></td>
<td></td>
<td></td>
</tr>

<tr>
<td></td>
<td></td>
<td></td>
</tr>

<tr>
<td></td>
<td></td>
<td></td>
</tr>

</table>
