# ![LOGO](logo.png) YouTube Analytics **flow**ground Connector

## Description

A generated **flow**ground connector for the YouTube Analytics API (version v2).

Generated from: https://api.apis.guru/v2/specs/googleapis.com/youtubeAnalytics/v2/swagger.json<br/>
Generated at: 2019-05-23T12:13:50+03:00

## API Description

Retrieves your YouTube Analytics data.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Removes an item from a group.

*Tags:* `groupItems`

#### Input Parameters
* `id` - _optional_ - The `id` parameter specifies the YouTube group item ID of the group item
that is being deleted.
* `onBehalfOfContentOwner` - _optional_ - This parameter can only be used in a properly authorized request. **Note:**
This parameter is intended exclusively for YouTube content partners that
own and manage many different YouTube channels.

The `onBehalfOfContentOwner` parameter indicates that the request's
authorization credentials identify a YouTube user who is acting on behalf
of the content owner specified in the parameter value. It allows content
owners to authenticate once and get access to all their video and channel
data, without having to provide authentication credentials for each
individual channel. The account that the user authenticates with must be
linked to the specified YouTube content owner.
* `alt` - _optional_ - Data format for response.
    Possible values: json, media, proto.
* `callback` - _optional_ - JSONP
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - Available to use for quota purposes for server-side applications. Can be any arbitrary string assigned to a user, but should not exceed 40 characters.
* `uploadType` - _optional_ - Legacy upload protocol for media (e.g. "media", "multipart").
* `upload_protocol` - _optional_ - Upload protocol for media (e.g. "raw", "multipart").

### Returns a collection of group items that match the API request parameters.

*Tags:* `groupItems`

#### Input Parameters
* `groupId` - _optional_ - The `groupId` parameter specifies the unique ID of the group for which you
want to retrieve group items.
* `onBehalfOfContentOwner` - _optional_ - This parameter can only be used in a properly authorized request. **Note:**
This parameter is intended exclusively for YouTube content partners that
own and manage many different YouTube channels.

The `onBehalfOfContentOwner` parameter indicates that the request's
authorization credentials identify a YouTube user who is acting on behalf
of the content owner specified in the parameter value. It allows content
owners to authenticate once and get access to all their video and channel
data, without having to provide authentication credentials for each
individual channel. The account that the user authenticates with must be
linked to the specified YouTube content owner.
* `alt` - _optional_ - Data format for response.
    Possible values: json, media, proto.
* `callback` - _optional_ - JSONP
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - Available to use for quota purposes for server-side applications. Can be any arbitrary string assigned to a user, but should not exceed 40 characters.
* `uploadType` - _optional_ - Legacy upload protocol for media (e.g. "media", "multipart").
* `upload_protocol` - _optional_ - Upload protocol for media (e.g. "raw", "multipart").

### Creates a group item.

*Tags:* `groupItems`

#### Input Parameters
* `onBehalfOfContentOwner` - _optional_ - This parameter can only be used in a properly authorized request. **Note:**
This parameter is intended exclusively for YouTube content partners that
own and manage many different YouTube channels.

The `onBehalfOfContentOwner` parameter indicates that the request's
authorization credentials identify a YouTube user who is acting on behalf
of the content owner specified in the parameter value. It allows content
owners to authenticate once and get access to all their video and channel
data, without having to provide authentication credentials for each
individual channel. The account that the user authenticates with must be
linked to the specified YouTube content owner.
* `access_token` - _optional_ - OAuth access token.
* `alt` - _optional_ - Data format for response.
    Possible values: json, media, proto.
* `callback` - _optional_ - JSONP
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - Available to use for quota purposes for server-side applications. Can be any arbitrary string assigned to a user, but should not exceed 40 characters.
* `uploadType` - _optional_ - Legacy upload protocol for media (e.g. "media", "multipart").
* `upload_protocol` - _optional_ - Upload protocol for media (e.g. "raw", "multipart").

### Deletes a group.

*Tags:* `groups`

#### Input Parameters
* `id` - _optional_ - The `id` parameter specifies the YouTube group ID of the group that is
being deleted.
* `onBehalfOfContentOwner` - _optional_ - This parameter can only be used in a properly authorized request. **Note:**
This parameter is intended exclusively for YouTube content partners that
own and manage many different YouTube channels.

The `onBehalfOfContentOwner` parameter indicates that the request's
authorization credentials identify a YouTube user who is acting on behalf
of the content owner specified in the parameter value. It allows content
owners to authenticate once and get access to all their video and channel
data, without having to provide authentication credentials for each
individual channel. The account that the user authenticates with must be
linked to the specified YouTube content owner.
* `alt` - _optional_ - Data format for response.
    Possible values: json, media, proto.
* `callback` - _optional_ - JSONP
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - Available to use for quota purposes for server-side applications. Can be any arbitrary string assigned to a user, but should not exceed 40 characters.
* `uploadType` - _optional_ - Legacy upload protocol for media (e.g. "media", "multipart").
* `upload_protocol` - _optional_ - Upload protocol for media (e.g. "raw", "multipart").

### Returns a collection of groups that match the API request parameters. For<br/>
> example, you can retrieve all groups that the authenticated user owns,<br/>
> or you can retrieve one or more groups by their unique IDs.

*Tags:* `groups`

#### Input Parameters
* `id` - _optional_ - The `id` parameter specifies a comma-separated list of the YouTube group
ID(s) for the resource(s) that are being retrieved. Each group must be
owned by the authenticated user. In a `group` resource, the `id` property
specifies the group's YouTube group ID.

Note that if you do not specify a value for the `id` parameter, then you
must set the `mine` parameter to `true`.
* `mine` - _optional_ - This parameter can only be used in a properly authorized request. Set this
parameter's value to true to retrieve all groups owned by the authenticated
user.
* `onBehalfOfContentOwner` - _optional_ - This parameter can only be used in a properly authorized request. **Note:**
This parameter is intended exclusively for YouTube content partners that
own and manage many different YouTube channels.

The `onBehalfOfContentOwner` parameter indicates that the request's
authorization credentials identify a YouTube user who is acting on behalf
of the content owner specified in the parameter value. It allows content
owners to authenticate once and get access to all their video and channel
data, without having to provide authentication credentials for each
individual channel. The account that the user authenticates with must be
linked to the specified YouTube content owner.
* `pageToken` - _optional_ - The `pageToken` parameter identifies a specific page in the result set that
should be returned. In an API response, the `nextPageToken` property
identifies the next page that can be retrieved.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - Available to use for quota purposes for server-side applications. Can be any arbitrary string assigned to a user, but should not exceed 40 characters.
* `uploadType` - _optional_ - Legacy upload protocol for media (e.g. "media", "multipart").
* `upload_protocol` - _optional_ - Upload protocol for media (e.g. "raw", "multipart").

### Creates a group.

*Tags:* `groups`

#### Input Parameters
* `onBehalfOfContentOwner` - _optional_ - This parameter can only be used in a properly authorized request. **Note:**
This parameter is intended exclusively for YouTube content partners that
own and manage many different YouTube channels.

The `onBehalfOfContentOwner` parameter indicates that the request's
authorization credentials identify a YouTube user who is acting on behalf
of the content owner specified in the parameter value. It allows content
owners to authenticate once and get access to all their video and channel
data, without having to provide authentication credentials for each
individual channel. The account that the user authenticates with must be
linked to the specified YouTube content owner.
* `access_token` - _optional_ - OAuth access token.
* `alt` - _optional_ - Data format for response.
    Possible values: json, media, proto.
* `callback` - _optional_ - JSONP
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - Available to use for quota purposes for server-side applications. Can be any arbitrary string assigned to a user, but should not exceed 40 characters.
* `uploadType` - _optional_ - Legacy upload protocol for media (e.g. "media", "multipart").
* `upload_protocol` - _optional_ - Upload protocol for media (e.g. "raw", "multipart").

### Modifies a group. For example, you could change a group's title.

*Tags:* `groups`

#### Input Parameters
* `onBehalfOfContentOwner` - _optional_ - This parameter can only be used in a properly authorized request. **Note:**
This parameter is intended exclusively for YouTube content partners that
own and manage many different YouTube channels.

The `onBehalfOfContentOwner` parameter indicates that the request's
authorization credentials identify a YouTube user who is acting on behalf
of the content owner specified in the parameter value. It allows content
owners to authenticate once and get access to all their video and channel
data, without having to provide authentication credentials for each
individual channel. The account that the user authenticates with must be
linked to the specified YouTube content owner.
* `access_token` - _optional_ - OAuth access token.
* `alt` - _optional_ - Data format for response.
    Possible values: json, media, proto.
* `callback` - _optional_ - JSONP
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - Available to use for quota purposes for server-side applications. Can be any arbitrary string assigned to a user, but should not exceed 40 characters.
* `uploadType` - _optional_ - Legacy upload protocol for media (e.g. "media", "multipart").
* `upload_protocol` - _optional_ - Upload protocol for media (e.g. "raw", "multipart").

### Retrieve your YouTube Analytics reports.

*Tags:* `reports`

#### Input Parameters
* `currency` - _optional_ - The currency to which financial metrics should be converted. The default is
US Dollar (USD). If the result contains no financial metrics, this flag
will be ignored. Responds with an error if the specified currency is not
recognized.",
pattern: [A-Z]{3}
* `dimensions` - _optional_ - A comma-separated list of YouTube Analytics dimensions, such as `views` or
`ageGroup,gender`. See the [Available
Reports](/youtube/analytics/v2/available_reports) document for a list of
the reports that you can retrieve and the dimensions used for those
reports. Also see the [Dimensions](/youtube/analytics/v2/dimsmets/dims)
document for definitions of those dimensions."
pattern: [0-9a-zA-Z,]+
* `endDate` - _optional_ - The end date for fetching YouTube Analytics data. The value should be in
`YYYY-MM-DD` format.
required: true, pattern: [0-9]{4}-[0-9]{2}-[0-9]{2}
* `filters` - _optional_ - A list of filters that should be applied when retrieving YouTube Analytics
data. The [Available Reports](/youtube/analytics/v2/available_reports)
document identifies the dimensions that can be used to filter each report,
and the [Dimensions](/youtube/analytics/v2/dimsmets/dims)  document defines
those dimensions. If a request uses multiple filters, join them together
with a semicolon (`;`), and the returned result table will satisfy both
filters. For example, a filters parameter value of
`video==dMH0bHeiRNg;country==IT` restricts the result set to include data
for the given video in Italy.",
* `ids` - _optional_ - Identifies the YouTube channel or content owner for which you are
retrieving YouTube Analytics data.

- To request data for a YouTube user, set the `ids` parameter value to
  `channel==CHANNEL_ID`, where `CHANNEL_ID` specifies the unique YouTube
  channel ID.
- To request data for a YouTube CMS content owner, set the `ids` parameter
  value to `contentOwner==OWNER_NAME`, where `OWNER_NAME` is the CMS name
  of the content owner.
required: true, pattern: [a-zA-Z]+==[a-zA-Z0-9_+-]+
* `includeHistoricalChannelData` - _optional_ - If set to true historical data (i.e. channel data from before the linking
of the channel to the content owner) will be retrieved.",
* `maxResults` - _optional_ - The maximum number of rows to include in the response.",
minValue: 1
* `metrics` - _optional_ - A comma-separated list of YouTube Analytics metrics, such as `views` or
`likes,dislikes`. See the
[Available Reports](/youtube/analytics/v2/available_reports)  document for
a list of the reports that you can retrieve and the metrics
available in each report, and see the
[Metrics](/youtube/analytics/v2/dimsmets/mets) document for definitions of
those metrics.
required: true, pattern: [0-9a-zA-Z,]+
* `sort` - _optional_ - A comma-separated list of dimensions or metrics that determine the sort
order for YouTube Analytics data. By default the sort order is ascending.
The '`-`' prefix causes descending sort order.",
pattern: [-0-9a-zA-Z,]+
* `startDate` - _optional_ - The start date for fetching YouTube Analytics data. The value should be in
`YYYY-MM-DD` format.
required: true, pattern: "[0-9]{4}-[0-9]{2}-[0-9]{2}
* `startIndex` - _optional_ - An index of the first entity to retrieve. Use this parameter as a
pagination mechanism along with the max-results parameter (one-based,
inclusive).",
minValue: 1

## License

**flow**ground :- Telekom iPaaS / googleapis-com-youtube-analytics-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
