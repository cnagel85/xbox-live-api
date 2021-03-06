# Changelog

This project follows [Semantic Versioning](http://semver.org/)

## 0.3.0 - 2016-01-07
- Added optional user_id param to the following XboxLiveApi methods
	- get_profile
	- get_xbox_one_games
	- get_xbox_360_games
- Added `XboxLiveApi.get_xuid`
- Added `XboxLiveApi.get_title_history`
- Added `XboxLiveApi.session_expired?`
- Added XboxLiveApi::XBLAuthError
	- raised by HttpSessionGateway::transform_response methods
	- raised on http status code 401

## 0.2.0 - 2015-09-23
- Added documentation for all public objects and interfaces
- Added `XboxLiveApi.with_session_info`
- Added `XboxLiveApi.get_friends_ids`

## 0.1.0 - 2015-07-27

- Added login for a user into Xbox Live API
- Added getting profile information for the user
- Added getting a user's games list
- Added getting the user's achievements for a game
