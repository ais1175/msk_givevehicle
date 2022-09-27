# msk_vehicleItems
Give or Delete Vehicles with Command or Item

## Ingame Command Usage ##
```lua
--PLATE is OPTIONAL

/giveveh <playerID> <categorie> <carModel> <plate>
/giveveh <playerID> <categorie> <carModel> <plate>
/giveveh <playerID> <categorie> <carModel> <plate>
/giveveh <playerID> <categorie> <carModel> <plate>

> Example: /giveveh 1 car zentorno "LS 1234"
> Example: /giveveh 1 boat zentorno "LS 1234"
> Example: /giveveh 1 aircraft zentorno "LS 1234"
> Example: /giveveh 1 helicopter zentorno "LS 1234"
```
```lua
/delveh <plate>

> Example: /delveh "LS 1234"
```

## Console Command Usage ##
```lua
--PLATE is OPTIONAL

_giveveh <playerID> <categorie> <carModel> <plate>
_giveveh <playerID> <categorie> <carModel> <plate>
_giveveh <playerID> <categorie> <carModel> <plate>
_giveveh <playerID> <categorie> <carModel> <plate>

> Example: _giveveh 1 car zentorno LS 1234
> Example: _giveveh 1 boat zentorno LS 1234
> Example: _giveveh 1 aircraft zentorno LS 1234
> Example: _giveveh 1 helicopter zentorno LS 1234
```
```lua
_delveh <plate>

> Example: _delveh LS 1234
```
## Requirements ##
* ESX 1.2 and above
