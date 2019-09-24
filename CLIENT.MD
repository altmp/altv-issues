# Functions/methods
- [ ] player.setDefaultComponentVariation
- [ ] player.setComponentVariation (componentId, drawableId, textureId, paletteId)
- [ ] player.getComponentVariation (componentId)
- [ ] player.setHeadOverlay (overlayId, index, opacity)
- [ ] player.setHeadOverlayColor (overlayId, colorType, colorId, secondColorId)
- [ ] player.setEyeColor (index)
- [ ] player.setFaceFeature (index, scale) -> or/and one function for all face features
- [ ] player.setHeadBlendData (shapeFirstID, shapeSecondID, shapeThirdID, skinFirstID, skinSecondID, skinThirdID, shapeMix, skinMix, thirdMix, isParent)
- [ ] player.playAnimation
- [ ] player.stopAnimation
- [ ] player.setDecoration
- [ ] player.clearDecorations
- [ ] player.getDecorationsState

# Properties
- [ ] player.discordInfo
- [ ] player.licenseHash
- [ ] player.currentWeapon
- [ ] player.allWeapons -> [[weaponHash, ammoCount]]?
- [ ] player.eyeColor
- [ ] player.faceFeatures
- [ ] player.hairColor
- [ ] player.hairSecondColor
- [ ] player.headBlendData

# Events
- [ ] Add `OnWeaponFired` event
- [ ] Add `OnWeaponAmmoChanged` event
- [ ] Add `bone` param to `OnPlayerDamage` event
- [ ] Add `OnWeaponChange` event
- [ ] Add `OnEntityStreamedIn`/`OnEntityStreamedOut`
- [ ] Add `PlayerEnteredVehicle`/`PlayerLeftVehicle`

# Features
- [ ] Add canvas API powered by `cairo`
- [ ] Replace textures on fragments (.yft) in runtime
