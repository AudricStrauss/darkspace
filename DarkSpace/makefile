# ----------------------------------------------------------------------
#
# This makefile has been automatically generated by WinGDB 2.3, build 1499
# Do not edit.
#
# Project: DarkSpace
#
# ----------------------------------------------------------------------

PLATFORM=unix

ifneq ("$(windir)","")
PLATFORM=windows
endif

ifneq ("$(WinDir)","")
PLATFORM=windows
endif

ifneq ("$(WINDIR)","")
PLATFORM=windows
endif

UNAME=$(shell uname -o)

ifeq ("$(UNAME)","Cygwin")
PLATFORM=cygwin
endif

ifeq ("$(BUILD_CONFIGURATION)","")
	BUILD_CONFIGURATION=ReleaseLinux
endif

ifeq ("$(BUILD_CONFIGURATION)","DebugLinux")
CC= gcc
CXX= g++
AR= ar
CFLAGS= -g -I ../ -I ../../Medusa/ -I ../../Medusa/ThirdParty/LuaJIT/src/ -D_DEBUG
CXXFLAGS= -g -I ../ -I ../../Medusa/ -I ../../Medusa/ThirdParty/LuaJIT/src/ -D_DEBUG
ARFLAGS= cru
LDFLAGS= -shared
RESULT=libDarkSpaceD.so
INTERMEDIATE_DIR=DebugLinux/obj
DESTINATION_DIR=../Bin
ifeq ("$(PLATFORM)","cygwin")
	RM=rm -f
	MKDIR=mkdir -p
	INTERMEDIATE_DIR_MK=$(INTERMEDIATE_DIR)
	DESTINATION_DIR_MK=$(DESTINATION_DIR)
else
	RM= rm -f
	MKDIR= mkdir -p
	INTERMEDIATE_DIR_MK=DebugLinux/obj
	DESTINATION_DIR_MK=../Bin
endif

endif

ifeq ("$(BUILD_CONFIGURATION)","ReleaseLinux")
CC= gcc
CXX= g++
AR= ar
CFLAGS= -g -O2 -I ../ -I ../../Medusa/ -I ../../Medusa/ThirdParty/LuaJIT/src/
CXXFLAGS= -g -O2 -I ../ -I ../../Medusa/ -I ../../Medusa/ThirdParty/LuaJIT/src/
ARFLAGS= cru
LDFLAGS= -shared
RESULT=libDarkSpace.so
INTERMEDIATE_DIR=ReleaseLinux/obj
DESTINATION_DIR=../Bin
ifeq ("$(PLATFORM)","cygwin")
	RM=rm -f
	MKDIR=mkdir -p
	INTERMEDIATE_DIR_MK=$(INTERMEDIATE_DIR)
	DESTINATION_DIR_MK=$(DESTINATION_DIR)
else
	RM= rm -f
	MKDIR= mkdir -p
	INTERMEDIATE_DIR_MK=ReleaseLinux/obj
	DESTINATION_DIR_MK=../Bin
endif

endif

SOURCES= AdminEnhancements.cpp BeamEnhancements.cpp CargoEnhancement.cpp CargoGadget.cpp CargoResource.cpp Constants.cpp DefaultLootTables.cpp DropData.cpp EnhancementModifier.cpp FieldDamage.cpp FieldEnhancement.cpp FieldInterdictor.cpp FieldSafeZone.cpp GadgetAreaReload.cpp GadgetAreaWeapon.cpp GadgetArmor.cpp GadgetAura.cpp GadgetAutoRepair.cpp GadgetBeacon.cpp GadgetBeamWeapon.cpp GadgetBuild.cpp GadgetCloak.cpp GadgetDrive.cpp GadgetDropPod.cpp GadgetECCM.cpp GadgetECM.cpp GadgetELF.cpp GadgetEMP.cpp GadgetFighterBay.cpp GadgetJD.cpp GadgetJumpDrive.cpp GadgetJumpGate.cpp GadgetMiningBeam.cpp GadgetModifierEW.cpp GadgetPulseShield.cpp GadgetReactor.cpp GadgetReload.cpp GadgetScanner.cpp GadgetScript.cpp GadgetShield.cpp GadgetSlot.cpp GadgetSpawn.cpp GadgetSpreadWeapon.cpp GadgetTECCM.cpp GadgetTECM.cpp GadgetTractorBeam.cpp GadgetWeapon.cpp GameClient.cpp GameClientCommand.cpp GameContext.cpp GameContextScript.cpp GameDll.cpp GameProfile.cpp GameServer.cpp GameServerCommand.cpp GameZone.cpp MonsterCrystal.cpp MonsterEnergy.cpp MonsterGafin.cpp MonsterTeros.cpp MonsterTerosScout.cpp NounAsteroid.cpp NounAsteroidBelt.cpp NounBeacon.cpp NounBody.cpp NounCargo.cpp NounComet.cpp NounDrone.cpp NounDropTarget.cpp NounEnhancement.cpp NounField.cpp NounFighter.cpp NounGadget.cpp NounGame.cpp NounJumpGate.cpp NounJumpTarget.cpp NounNebula.cpp NounPlanet.cpp NounPod.cpp NounProjectile.cpp NounQueue.cpp NounScenery.cpp NounShip.cpp NounShipCargo.cpp NounShipControl.cpp NounShipEnhancement.cpp NounShipLogic.cpp NounSmartProjectile.cpp NounSpawn.cpp NounSpawnShip.cpp NounStar.cpp NounStructure.cpp NounTrail.cpp NounUnit.cpp PathMapPlanet.cpp SceneryDebris.cpp SceneryEffect.cpp ShipEnhancements.cpp ShipPlatform.cpp SpecialEnhancements.cpp StructureBarracks.cpp StructureDefense.cpp StructureFactory.cpp StructureHub.cpp StructureMIHub.cpp StructureMine.cpp StructurePort.cpp StructureShipyard.cpp StructureSolar.cpp Structures.cpp TierInfo.cpp FactionInfo.cpp Trail.cpp TraitDisplayName.cpp TraitOrbit.cpp TraitSignature.cpp VerbApplyEnhancement.cpp VerbBreakOrbit.cpp VerbBuildPlatform.cpp VerbBuildStructure.cpp VerbBuildUnit.cpp VerbCapturePlanet.cpp VerbCaptureShip.cpp VerbCommandShip.cpp VerbDestroyGadget.cpp VerbDestroyShip.cpp VerbDestroyStructure.cpp VerbDestroyUnit.cpp VerbDisband.cpp VerbDistress.cpp VerbEnterOrbit.cpp VerbExplodeProjectiles.cpp VerbGadgetOff.cpp VerbImportExport.cpp VerbJump.cpp VerbJumpAbort.cpp VerbJumpBegin.cpp VerbLoad.cpp VerbLockPlanet.cpp VerbMoveUnit.cpp VerbOrderShip.cpp VerbOrderUnit.cpp VerbPlanetEvent.cpp VerbQueue.cpp VerbRefitGadget.cpp VerbRemoveEnhancement.cpp VerbRepairGadget.cpp VerbRevolt.cpp VerbScrap.cpp VerbSelfDestruct.cpp VerbSetDetectionFlags.cpp VerbSetFlags.cpp VerbSetGadgetGroup.cpp VerbSetStructureActive.cpp VerbSpawn.cpp VerbTradeRoute.cpp VerbTransferCredits.cpp VerbTransferResource.cpp VerbUnload.cpp VerbUseGadget.cpp VerbUseJumpGate.cpp VerbUseMode.cpp VerbUseSingleGadget.cpp VerbUseStructure.cpp WeaponEnhancements.cpp

SOURCEPATHS= AdminEnhancements.cpp BeamEnhancements.cpp CargoEnhancement.cpp CargoGadget.cpp CargoResource.cpp Constants.cpp DefaultLootTables.cpp DropData.cpp EnhancementModifier.cpp FieldDamage.cpp FieldEnhancement.cpp FieldInterdictor.cpp FieldSafeZone.cpp GadgetAreaReload.cpp GadgetAreaWeapon.cpp GadgetArmor.cpp GadgetAura.cpp GadgetAutoRepair.cpp GadgetBeacon.cpp GadgetBeamWeapon.cpp GadgetBuild.cpp GadgetCloak.cpp GadgetDrive.cpp GadgetDropPod.cpp GadgetECCM.cpp GadgetECM.cpp GadgetELF.cpp GadgetEMP.cpp GadgetFighterBay.cpp GadgetJD.cpp GadgetJumpDrive.cpp GadgetJumpGate.cpp GadgetMiningBeam.cpp GadgetModifierEW.cpp GadgetPulseShield.cpp GadgetReactor.cpp GadgetReload.cpp GadgetScanner.cpp GadgetScript.cpp GadgetShield.cpp GadgetSlot.cpp GadgetSpawn.cpp GadgetSpreadWeapon.cpp GadgetTECCM.cpp GadgetTECM.cpp GadgetTractorBeam.cpp GadgetWeapon.cpp GameClient.cpp GameClientCommand.cpp GameContext.cpp GameContextScript.cpp GameDll.cpp GameProfile.cpp GameServer.cpp GameServerCommand.cpp GameZone.cpp MonsterCrystal.cpp MonsterEnergy.cpp MonsterGafin.cpp MonsterTeros.cpp MonsterTerosScout.cpp NounAsteroid.cpp NounAsteroidBelt.cpp NounBeacon.cpp NounBody.cpp NounCargo.cpp NounComet.cpp NounDrone.cpp NounDropTarget.cpp NounEnhancement.cpp NounField.cpp NounFighter.cpp NounGadget.cpp NounGame.cpp NounJumpGate.cpp NounJumpTarget.cpp NounNebula.cpp NounPlanet.cpp NounPod.cpp NounProjectile.cpp NounQueue.cpp NounScenery.cpp NounShip.cpp NounShipCargo.cpp NounShipControl.cpp NounShipEnhancement.cpp NounShipLogic.cpp NounSmartProjectile.cpp NounSpawn.cpp NounSpawnShip.cpp NounStar.cpp NounStructure.cpp NounTrail.cpp NounUnit.cpp PathMapPlanet.cpp SceneryDebris.cpp SceneryEffect.cpp ShipEnhancements.cpp ShipPlatform.cpp SpecialEnhancements.cpp StructureBarracks.cpp StructureDefense.cpp StructureFactory.cpp StructureHub.cpp StructureMIHub.cpp StructureMine.cpp StructurePort.cpp StructureShipyard.cpp StructureSolar.cpp Structures.cpp TierInfo.cpp FactionInfo.cpp Trail.cpp TraitDisplayName.cpp TraitOrbit.cpp TraitSignature.cpp VerbApplyEnhancement.cpp VerbBreakOrbit.cpp VerbBuildPlatform.cpp VerbBuildStructure.cpp VerbBuildUnit.cpp VerbCapturePlanet.cpp VerbCaptureShip.cpp VerbCommandShip.cpp VerbDestroyGadget.cpp VerbDestroyShip.cpp VerbDestroyStructure.cpp VerbDestroyUnit.cpp VerbDisband.cpp VerbDistress.cpp VerbEnterOrbit.cpp VerbExplodeProjectiles.cpp VerbGadgetOff.cpp VerbImportExport.cpp VerbJump.cpp VerbJumpAbort.cpp VerbJumpBegin.cpp VerbLoad.cpp VerbLockPlanet.cpp VerbMoveUnit.cpp VerbOrderShip.cpp VerbOrderUnit.cpp VerbPlanetEvent.cpp VerbQueue.cpp VerbRefitGadget.cpp VerbRemoveEnhancement.cpp VerbRepairGadget.cpp VerbRevolt.cpp VerbScrap.cpp VerbSelfDestruct.cpp VerbSetDetectionFlags.cpp VerbSetFlags.cpp VerbSetGadgetGroup.cpp VerbSetStructureActive.cpp VerbSpawn.cpp VerbTradeRoute.cpp VerbTransferCredits.cpp VerbTransferResource.cpp VerbUnload.cpp VerbUseGadget.cpp VerbUseJumpGate.cpp VerbUseMode.cpp VerbUseSingleGadget.cpp VerbUseStructure.cpp WeaponEnhancements.cpp

HEADERS= AdminEnhancements.h BeamEnhancements.h CargoEnhancement.h CargoGadget.h CargoResource.h Constants.h DefaultLootTables.h DropData.h EnhancementModifier.h FieldDamage.h FieldEnhancement.h FieldInterdictor.h FieldSafeZone.h GadgetAreaReload.h GadgetAreaWeapon.h GadgetArmor.h GadgetAura.h GadgetAutoRepair.h GadgetBeacon.h GadgetBeamWeapon.h GadgetBuild.h GadgetCloak.h GadgetDrive.h GadgetDropPod.h GadgetECCM.h GadgetECM.h GadgetELF.h GadgetEMP.h GadgetFighterBay.h GadgetJD.h GadgetJumpDrive.h GadgetJumpGate.h GadgetMiningBeam.h GadgetModifierEW.h GadgetPulseShield.h GadgetReactor.h GadgetReload.h GadgetScanner.h GadgetScript.h GadgetShield.h GadgetSlot.h GadgetSpawn.h GadgetSpreadWeapon.h GadgetTECCM.h GadgetTECM.h GadgetTractorBeam.h GadgetWeapon.h GameClient.h GameContext.h GameDll.h GameProfile.h GameServer.h GameZone.h MonsterCrystal.h MonsterEnergy.h MonsterGafin.h MonsterTeros.h MonsterTerosScout.h NounAsteroid.h NounAsteroidBelt.h NounBeacon.h NounBody.h NounCargo.h NounComet.h NounDrone.h NounDropTarget.h NounEnhancement.h NounField.h NounFighter.h NounGadget.h NounGame.h NounJumpGate.h NounJumpTarget.h NounNebula.h NounPlanet.h NounPod.h NounProjectile.h NounQueue.h NounScenery.h NounShip.h NounSmartProjectile.h NounSpawn.h NounSpawnShip.h NounStar.h NounStructure.h NounTrail.h NounUnit.h PathMapPlanet.h ProxyShip.h SceneryDebris.h SceneryEffect.h ShipEnhancements.h ShipFighter.h ShipPlatform.h SpecialEnhancements.h StructureBarracks.h StructureDefense.h StructureDefenseMix1.h StructureDefenseMix2.h StructureDefensePD1.h StructureDefensePD2.h StructureDefenseShip1.h StructureDefenseShip2.h StructureDepot.h StructureDome.h StructureFactory.h StructureFarm.h StructureFarm2.h StructureFarm3.h StructureHub.h StructureMIHub.h StructureInterdictor.h StructureLab.h StructureLab2.h StructureLab3.h StructureMine.h StructureMine2.h StructureMine3.h StructurePort.h StructurePower.h StructurePower2.h StructurePower3.h StructureSensor.h StructureShield.h StructureShipyard.h StructureSolar.h TierInfo.h FactionInfo.h Trail.h TraitBuildable.h TraitCargo.h TraitCargoHold.h TraitDamageable.h TraitDisplayName.h TraitEnergyBank.h TraitFleetId.h TraitOrbit.h TraitOrbitable.h TraitRepairable.h TraitSignature.h TraitUserId.h VerbApplyEnhancement.h VerbBreakOrbit.h VerbBuildPlatform.h VerbBuildStructure.h VerbBuildUnit.h VerbCapturePlanet.h VerbCaptureShip.h VerbCommandShip.h VerbDestroyGadget.h VerbDestroyShip.h VerbDestroyStructure.h VerbDestroyUnit.h VerbDisband.h VerbDistress.h VerbEnterOrbit.h VerbExplodeProjectiles.h VerbGadgetOff.h VerbImportExport.h VerbJump.h VerbJumpAbort.h VerbJumpBegin.h VerbLoad.h VerbLockPlanet.h VerbMoveUnit.h VerbOrderShip.h VerbOrderUnit.h VerbPlanetEvent.h VerbQueue.h VerbRefitGadget.h VerbRemoveEnhancement.h VerbRepairGadget.h VerbRevolt.h VerbScrap.h VerbSelfDestruct.h VerbSetDetectionFlags.h VerbSetFlags.h VerbSetGadgetGroup.h VerbSetStructureActive.h VerbSpawn.h VerbTradeRoute.h VerbTransferCredits.h VerbTransferResource.h VerbUnload.h VerbUseGadget.h VerbUseJumpGate.h VerbUseMode.h VerbUseSingleGadget.h VerbUseStructure.h WeaponEnhancements.h resource.h

VPATH= $(INTERMEDIATE_DIR)

OBJECTNAMES=$(patsubst %.c,%.o,$(patsubst %.cpp,%.o,$(SOURCES)))
OBJECTPATHS=$(addprefix $(INTERMEDIATE_DIR)/,$(OBJECTNAMES))

$(DESTINATION_DIR)/$(RESULT): $(OBJECTNAMES)
ifeq ("$(wildcard $(DESTINATION_DIR) )","")
	-$(MKDIR) $(DESTINATION_DIR_MK)
endif
	$(CXX) -shared $(CXXFLAGS) $(SYSROOTFLAGS) $(OBJECTPATHS) -o $@ $(LDFLAGS)

$(INTERMEDIATE_DIR)/DarkSpace.d: $(SOURCES) $(HEADERS)
ifeq ("$(wildcard $(DESTINATION_DIR) )","")
	-$(MKDIR) $(DESTINATION_DIR_MK)
endif
ifeq ("$(wildcard $(INTERMEDIATE_DIR) )","")
	-$(MKDIR) $(INTERMEDIATE_DIR_MK)
endif
	$(CXX) $(CXXFLAGS) -MM $(SOURCEPATHS) > $@

-include $(INTERMEDIATE_DIR)/DarkSpace.d

clean:
	$(RM) $(DESTINATION_DIR)/$(RESULT)
	$(RM) $(INTERMEDIATE_DIR)/DarkSpace.d
	$(RM) $(OBJECTPATHS)

%.o: %.cpp
	$(CXX) -fPIC $(CXXFLAGS) -c -o $(INTERMEDIATE_DIR)/$@ $<

%.o: %.c
	$(CC) -fPIC $(CFLAGS) -c -o $(INTERMEDIATE_DIR)/$@ $<
