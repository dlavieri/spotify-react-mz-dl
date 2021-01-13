# SPOTIFY API ENDPOINTS
Endpoint documentation: https://developer.spotify.com/documentation/web-api/reference-beta/

# GET an album
GET https://api.spotify.com/v1/albums/{id}
## GET album's tracks
GET https://api.spotify.com/v1/albums/{id}/tracks

# GET an artist
GET https://api.spotify.com/v1/artists/{id}
## GET artist's top tracks
GET https://api.spotify.com/v1/artists/{id}/top-tracks
## GET artist's albums
GET https://api.spotify.com/v1/artists/{id}/albums

# GET recommendations
GET https://api.spotify.com/v1/recommendations

# GET user's top artists and tracks
GET https://api.spotify.com/v1/me/top/{'artists' or 'tracks'}