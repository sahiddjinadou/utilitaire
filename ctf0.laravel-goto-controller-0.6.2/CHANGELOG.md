# Change Log

## 0.0.1

- init

## 0.0.2

- refactors
- more methods for route

## 0.0.3

- smaller size

## 0.0.4

- add route completion

## 0.0.5

- can now copy method name if not found in the controller ex."used through a trait"

## 0.0.6

- better route completion

## 0.0.7

- fix showing copy method notif when no method is in link

## 0.0.9

- search for required files in workspace root only instead of everywhere
- better api

## 0.1.0

- add config to show/hide the route name suggestions

## 0.1.1

- fix package settings name

## 0.1.4

- fix showing links to controllers with partially matched names
- fix scrolling to methods with partially matched names

## 0.1.5

- things should be quicker now

## 0.2.0

- remove `route name suggestions` use `https://marketplace.visualstudio.com/items?itemName=amiralizadeh9480.laravel-extra-intellisense` instead

## 0.2.2

- better regex to support something like [`tenant_route($domain, 'home')`](https://tenancyforlaravel.com/docs/v3/features/cross-domain-redirect/)

## 0.2.3

- fix wrong path seperator for windows

## 0.2.5

- fix not working with controllers that have namespace in the name ex.`API\SomeController@action`

## 0.2.6

- use the correct file opening command

## 0.2.7

- make sure path separators are normalized

## 0.2.8

- support docker
- support new laravel 9 routes list cmnd (check [readme](https://github.com/ctf0/laravel-goto-controller/blob/HEAD/README.md))

## 0.3.0

- fix link popup not being clickable
- use a cmnd instead of the uri handler

## 0.4.1

- remove `waitB4Scroll` config
- use symbol provider to correctly navigate to action

## 0.4.5

- update `laravelGotoController.routeListCommand` & `laravelGotoController.phpCommand`, plz update ur config
- add new config `laravelGotoController.dockerVolumePath`
- better api
- update rdme

## 0.4.7

- fix error

## 0.4.8

- fix error 'Activating extension 'ctf0.laravel-goto-controller' failed: Cannot read properties of undefined (reading 'path').'

## 0.5.1

- fix not working correctly with `PhotoController@index`

## 0.5.3

- fix `ur is not a function or its return value is not iterable`

## 0.5.4

- show output panel when phpcommand fails

## 0.6.0

- better support for routes actions
- update rdme

## 0.6.1

- allow the extension to work regardless of parsing errors

## 0.6.2

- fix https://github.com/ctf0/laravel-goto-controller/issues/7
