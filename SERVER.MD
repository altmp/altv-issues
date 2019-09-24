# Functions/methods
- [ ] player.putInVehicle (vehicle, seat)
- [ ] player.ejectFromVehicle
- [ ] player.addWeapon (weaponHash, ammoCount)
- [ ] player.removeWeapon params: (weaponHash)
- [ ] player.removeAllWeapons
- [ ] player.setWeaponAmmo (weaponHash, ammoCount)
- [ ] player.getWeaponAmmo (weaponHash)
- [ ] player.giveWeaponComponent (weaponHash, componentHash)
- [ ] player.hasWeaponComponent (weaponHash, componentHash)
- [ ] player.getWeaponComponents(weaponHash)
- [ ] player.removeWeaponComponent(weaponHash, componentHash)
- [ ] player.removeAllWeaponComponents(weaponHash)
- [ ] player.resetAllWeaponComponents
- [ ] player.setWeaponTint(weaponHash, tintIndex)
- [ ] player.getWeaponTint(weaponHash)
- [ ] player.getAllWeaponTints()
- [ ] player.resetAllWeaponTints()
- [ ] player.setDecoration(collection, overlay)
- [ ] player.toggleFreeze(state: boolean)
- [ ] player.setComponentVariation (componentId, drawableId, textureId, paletteId)

# Properties
- [ ] player.ip
- [ ] player.discordInfo
- [ ] player.licenseHash
- [ ] player.currentWeapon
- [ ] player.eyeColor
- [ ] player.faceFeatures
- [ ] player.hairColor
- [ ] player.hairSecondColor
- [ ] player.headBlendData

- [ ] vehicle.category
- [ ] vehicle.model
- [ ] vehicle.velocity
- [ ] vehicle.rot/rotation

# Events
- [ ] Add `OnVehicleDeath` event
- [ ] Add `OnWeaponChange` event
- [ ] Add `OnResourceLoaded`, `OnResourceUnloaded` and `OnAllResourcesLoaded` events
- [ ] Add `OnVehicleDamageStateChanged` event
- [ ] Add `OnVehicleHealthStateChanged` event
