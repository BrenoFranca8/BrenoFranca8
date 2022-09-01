-- Head --
Thread: Render thread
Stacktrace:
	at net.minecraftforge.fml.network.PacketDistributor.lambda$playerConsumer$1(PacketDistributor.java:203) ~[forge:?] {re:mixin,re:classloading}
	at net.minecraftforge.fml.network.PacketDistributor$PacketTarget.send(PacketDistributor.java:165) ~[forge:?] {re:mixin,re:classloading}
	at net.minecraftforge.fml.network.simple.SimpleChannel.send(SimpleChannel.java:110) ~[forge:?] {re:mixin,re:classloading}
	at net.yezon.theabyss.TheabyssModVariables$PlayerVariables.syncPlayerVariables(TheabyssModVariables.java:507) ~[theabyss:?] {re:classloading}
	at net.yezon.theabyss.procedures.SaveHomeLocationProcedure.lambda$executeProcedure$0(SaveHomeLocationProcedure.java:48) ~[theabyss:?] {re:classloading}
	at net.minecraftforge.common.util.LazyOptional.ifPresent(LazyOptional.java:151) ~[forge:?] {re:mixin,re:classloading}
	at net.yezon.theabyss.procedures.SaveHomeLocationProcedure.executeProcedure(SaveHomeLocationProcedure.java:46) ~[theabyss:?] {re:classloading}
	at net.yezon.theabyss.procedures.SaveHomeLocationProcedure$GlobalTrigger.onEntityEndSleep(SaveHomeLocationProcedure.java:33) ~[theabyss:?] {re:classloading,pl:eventbus:A}
	at net.minecraftforge.eventbus.ASMEventHandler_1367_GlobalTrigger_onEntityEndSleep_PlayerWakeUpEvent.invoke(.dynamic) ~[?:?] {}
	at net.minecraftforge.eventbus.ASMEventHandler.invoke(ASMEventHandler.java:85) ~[eventbus-4.0.0.jar:?] {}
	at net.minecraftforge.eventbus.EventBus.post(EventBus.java:302) ~[eventbus-4.0.0.jar:?] {}
	at net.minecraftforge.eventbus.EventBus.post(EventBus.java:283) ~[eventbus-4.0.0.jar:?] {}
	at net.minecraftforge.event.ForgeEventFactory.onPlayerWakeup(ForgeEventFactory.java:467) ~[forge:?] {re:mixin,re:classloading}
	at net.minecraft.entity.player.PlayerEntity.func_225652_a_(PlayerEntity.java:1259) ~[?:?] {re:computing_frames,pl:accesstransformer:B,xf:fml:xaerominimap:xaero_playerentity_iswearing,xf:fml:xaeroworldmap:xaero_wm_playerentity_iswearing,re:mixin,pl:accesstransformer:B,xf:fml:xaerominimap:xaero_playerentity_iswearing,xf:fml:xaeroworldmap:xaero_wm_playerentity_iswearing,re:classloading,pl:accesstransformer:B,xf:fml:xaerominimap:xaero_playerentity_iswearing,xf:fml:xaeroworldmap:xaero_wm_playerentity_iswearing,pl:mixin:APP:dynamiclightsreforged.mixins.json:PlayerEntityMixin,pl:mixin:APP:betterendforge.mixins.json:PlayerEntityMixin,pl:mixin:APP:mixins.adorn.json:PlayerEntityMixin,pl:mixin:APP:caelus.mixins.json:PlayerEntityMixin,pl:mixin:APP:blue_skies.mixins.json:PlayerEntityMixin,pl:mixin:APP:environmental.mixins.json:PlayerEntityMixin,pl:mixin:APP:endergetic.mixins.json:PlayerEntityMixin,pl:mixin:APP:personality.mixins.json:PlayerEntityMixin,pl:mixin:APP:3dskinlayers.mixins.json:PlayerMixin,pl:mixin:A}
	at net.minecraft.entity.player.ServerPlayerEntity.func_225652_a_(ServerPlayerEntity.java:820) ~[?:?] {re:computing_frames,pl:accesstransformer:B,re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:betterendforge.mixins.json:ServerPlayerEntityMixin,pl:mixin:APP:endergetic.mixins.json:ServerPlayerEntityMixin,pl:mixin:A}
	at net.minecraft.entity.player.PlayerEntity.func_213366_dy(PlayerEntity.java:1269) ~[?:?] {re:computing_frames,pl:accesstransformer:B,xf:fml:xaerominimap:xaero_playerentity_iswearing,xf:fml:xaeroworldmap:xaero_wm_playerentity_iswearing,re:mixin,pl:accesstransformer:B,xf:fml:xaerominimap:xaero_playerentity_iswearing,xf:fml:xaeroworldmap:xaero_wm_playerentity_iswearing,re:classloading,pl:accesstransformer:B,xf:fml:xaerominimap:xaero_playerentity_iswearing,xf:fml:xaeroworldmap:xaero_wm_playerentity_iswearing,pl:mixin:APP:dynamiclightsreforged.mixins.json:PlayerEntityMixin,pl:mixin:APP:betterendforge.mixins.json:PlayerEntityMixin,pl:mixin:APP:mixins.adorn.json:PlayerEntityMixin,pl:mixin:APP:caelus.mixins.json:PlayerEntityMixin,pl:mixin:APP:blue_skies.mixins.json:PlayerEntityMixin,pl:mixin:APP:environmental.mixins.json:PlayerEntityMixin,pl:mixin:APP:endergetic.mixins.json:PlayerEntityMixin,pl:mixin:APP:personality.mixins.json:PlayerEntityMixin,pl:mixin:APP:3dskinlayers.mixins.json:PlayerMixin,pl:mixin:A}
	at net.minecraft.entity.player.ServerPlayerEntity.func_70037_a(ServerPlayerEntity.java:256) ~[?:?] {re:computing_frames,pl:accesstransformer:B,re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:betterendforge.mixins.json:ServerPlayerEntityMixin,pl:mixin:APP:endergetic.mixins.json:ServerPlayerEntityMixin,pl:mixin:A}
-- Entity being loaded --
Details:
	Entity Type: minecraft:player (net.minecraft.entity.player.ServerPlayerEntity)
	Entity ID: 58
	Entity Name: Droga_eo_breno
	Entity's Exact location: 185.50, 76.69, -100.50
	Entity's Block location: World: (185,76,-101), Chunk: (at 9,4,11 in 11,-7; contains blocks 176,0,-112 to 191,255,-97), Region: (0,-1; contains chunks 0,-32 to 31,-1, blocks 0,0,-512 to 511,255,-1)
	Entity's Momentum: 0.00, 0.01, 0.00
	Entity's Passengers: []
	Entity's Vehicle: ~~ERROR~~ NullPointerException: Cannot invoke "net.minecraft.entity.Entity.toString()" because the return value of "net.minecraft.entity.Entity.func_184187_bx()" is null
Stacktrace:
	at net.minecraft.entity.Entity.func_70020_e(Entity.java:1494) ~[?:?] {re:mixin,pl:accesstransformer:B,re:computing_frames,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:dynamiclightsreforged.mixins.json:EntityMixin,pl:mixin:APP:infernal-expansion.mixins.json:common.MixinEntity,pl:mixin:APP:randompatches.mixins.json:EntityMixin,pl:mixin:APP:betterendforge.mixins.json:EntityMixin,pl:mixin:APP:structure_gel.mixins.json:EntityMixin,pl:mixin:APP:cavesandcliffs.mixins.json:core.accessor.EntityAccessor,pl:mixin:APP:entityculling.mixins.json:CullableMixin,pl:mixin:APP:abnormals_core.mixins.json:EntityMixin,pl:mixin:APP:upgrade_aquatic.mixins.json:EntityMixin,pl:mixin:APP:endergetic.mixins.json:EntityMixin,pl:mixin:APP:extraboats.mixins.json:EntityMixin,pl:mixin:APP:roadrunner.mixins.json:entity.collisions.EntityMixin,pl:mixin:APP:roadrunner.mixins.json:entity.fast_fluid_check.EntityMixin,pl:mixin:APP:roadrunner.mixins.json:entity.fast_suffocation_check.EntityMixin,pl:mixin:APP:roadrunner.mixins.json:entity.skip_fire_check.EntityMixin,pl:mixin:APP:roadrunner.mixins.json:entity.stream_entity_collisions_lazily.EntityMixin,pl:mixin:APP:iceberg.mixins.json:EntityMixin,pl:mixin:APP:quark.mixins.json:EntityMixin,pl:mixin:A}
	at net.minecraft.server.management.PlayerList.func_72380_a(PlayerList.java:291) ~[?:?] {re:mixin,xf:fml:xaerominimap:xaero_playerlist_sendworldinfo,xf:fml:xaeroworldmap:xaero_wm_playerlist_sendworldinfo,re:classloading,xf:fml:xaerominimap:xaero_playerlist_sendworldinfo,xf:fml:xaeroworldmap:xaero_wm_playerlist_sendworldinfo,pl:mixin:APP:betterendforge.mixins.json:PlayerListMixin,pl:mixin:APP:blue_skies.mixins.json:PlayerListMixin,pl:mixin:APP:endergetic.mixins.json:PlayerListMixin,pl:mixin:APP:enhancedcelestials.mixins.json:MixinPlayerList,pl:mixin:A}
	at net.minecraft.server.management.PlayerList.func_72355_a(PlayerList.java:128) ~[?:?] {re:mixin,xf:fml:xaerominimap:xaero_playerlist_sendworldinfo,xf:fml:xaeroworldmap:xaero_wm_playerlist_sendworldinfo,re:classloading,xf:fml:xaerominimap:xaero_playerlist_sendworldinfo,xf:fml:xaeroworldmap:xaero_wm_playerlist_sendworldinfo,pl:mixin:APP:betterendforge.mixins.json:PlayerListMixin,pl:mixin:APP:blue_skies.mixins.json:PlayerListMixin,pl:mixin:APP:endergetic.mixins.json:PlayerListMixin,pl:mixin:APP:enhancedcelestials.mixins.json:MixinPlayerList,pl:mixin:A}
	at net.minecraft.network.login.ServerLoginNetHandler.func_147326_c(ServerLoginNetHandler.java:118) ~[?:?] {re:mixin,re:classloading,pl:mixin:APP:randompatches.mixins.json:timeouts.ServerLoginNetHandlerMixin,pl:mixin:APP:kryptonreforged.mixins.json:network.shared.pipeline.encryption.ServerLoginNetworkHandlerMixin,pl:mixin:A}
	at net.minecraft.network.login.ServerLoginNetHandler.func_73660_a(ServerLoginNetHandler.java:65) ~[?:?] {re:mixin,re:classloading,pl:mixin:APP:randompatches.mixins.json:timeouts.ServerLoginNetHandlerMixin,pl:mixin:APP:kryptonreforged.mixins.json:network.shared.pipeline.encryption.ServerLoginNetworkHandlerMixin,pl:mixin:A}
	at net.minecraft.network.NetworkManager.func_74428_b(NetworkManager.java:222) ~[?:?] {re:mixin,re:classloading,pl:mixin:APP:kryptonreforged.mixins.json:network.shared.flushconsolidation.ClientConnectionMixin,pl:mixin:APP:kryptonreforged.mixins.json:network.shared.pipeline.compression.ClientConnectionMixin,pl:mixin:APP:kryptonreforged.mixins.json:network.shared.pipeline.encryption.ClientConnectionMixin,pl:mixin:A}
	at net.minecraft.network.NetworkSystem.func_151269_c(NetworkSystem.java:134) ~[?:?] {re:classloading}
	at net.minecraft.server.MinecraftServer.func_71190_q(MinecraftServer.java:865) ~[?:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:betterendforge.mixins.json:MinecraftServerMixin,pl:mixin:APP:structure_gel.mixins.json:MinecraftServerMixin,pl:mixin:APP:paxi.mixins.json:MixinMinecraftServer,pl:mixin:APP:byg.mixins.json:server.MixinMinecraftServer,pl:mixin:APP:roadrunner.mixins.json:world.light_batching.MinecraftServerMixin,pl:mixin:A}
	at net.minecraft.server.MinecraftServer.func_71217_p(MinecraftServer.java:787) ~[?:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:betterendforge.mixins.json:MinecraftServerMixin,pl:mixin:APP:structure_gel.mixins.json:MinecraftServerMixin,pl:mixin:APP:paxi.mixins.json:MixinMinecraftServer,pl:mixin:APP:byg.mixins.json:server.MixinMinecraftServer,pl:mixin:APP:roadrunner.mixins.json:world.light_batching.MinecraftServerMixin,pl:mixin:A}
	at net.minecraft.server.integrated.IntegratedServer.func_71217_p(IntegratedServer.java:78) ~[?:?] {re:classloading,pl:runtimedistcleaner:A}
	at net.minecraft.server.MinecraftServer.func_240802_v_(MinecraftServer.java:642) ~[?:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:betterendforge.mixins.json:MinecraftServerMixin,pl:mixin:APP:structure_gel.mixins.json:MinecraftServerMixin,pl:mixin:APP:paxi.mixins.json:MixinMinecraftServer,pl:mixin:APP:byg.mixins.json:server.MixinMinecraftServer,pl:mixin:APP:roadrunner.mixins.json:world.light_batching.MinecraftServerMixin,pl:mixin:A}
	at net.minecraft.server.MinecraftServer.func_240783_a_(MinecraftServer.java:232) ~[?:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:betterendforge.mixins.json:MinecraftServerMixin,pl:mixin:APP:structure_gel.mixins.json:MinecraftServerMixin,pl:mixin:APP:paxi.mixins.json:MixinMinecraftServer,pl:mixin:APP:byg.mixins.json:server.MixinMinecraftServer,pl:mixin:APP:roadrunner.mixins.json:world.light_batching.MinecraftServerMixin,pl:mixin:A}
	at java.lang.Thread.run(Thread.java:833) ~[?:?] {}


-- System Details --
Details:
	Minecraft Version: 1.16.5
	Minecraft Version ID: 1.16.5
	Operating System: Windows 10 (amd64) version 10.0
	Java Version: 17.0.4.1, Oracle Corporation
	Java VM Version: Java HotSpot(TM) 64-Bit Server VM (mixed mode, sharing), Oracle Corporation
	Memory: 2021098856 bytes (1927 MB) / 3791650816 bytes (3616 MB) up to 8556380160 bytes (8160 MB)
	CPUs: 4
	JVM Flags: 10 total; -XX:HeapDumpPath=MojangTricksIntelDriversForPerformance_javaw.exe_minecraft.exe.heapdump -Xss1M -XX:+IgnoreUnrecognizedVMOptions -Xmx8132M -XX:+UnlockExperimentalVMOptions -XX:+UseG1GC -XX:G1NewSizePercent=20 -XX:G1ReservePercent=20 -XX:MaxGCPauseMillis=50 -XX:G1HeapRegionSize=32M
	ModLauncher: 8.1.3+8.1.3+main-8.1.x.c94d18ec
	ModLauncher launch target: fmlclient
	ModLauncher naming: srg
	ModLauncher services: 
		/mixin-0.8.4.jar mixin PLUGINSERVICE 
		/eventbus-4.0.0.jar eventbus PLUGINSERVICE 
		/forge-1.16.5-36.2.35.jar object_holder_definalize PLUGINSERVICE 
		/forge-1.16.5-36.2.35.jar runtime_enum_extender PLUGINSERVICE 
		/forge-1.16.5-36.2.35.jar capability_inject_definalize PLUGINSERVICE 
		/accesstransformers-3.0.1.jar accesstransformer PLUGINSERVICE 
		/forge-1.16.5-36.2.35.jar runtimedistcleaner PLUGINSERVICE 
		/mixin-0.8.4.jar mixin TRANSFORMATIONSERVICE 
		/forge-1.16.5-36.2.35.jar fml TRANSFORMATIONSERVICE 
	FML: 36.2
	Forge: net.minecraftforge:36.2.35
	FML Language Providers: 
		javafml@36.2
		minecraft@1
		kotlinforforge@1.17.0
	Mod List: 
		dynamiclightsreforged-mc1.16.5_v1.0.1.jar         |Dynamic Lights Reforged       |dynamiclightsreforged         |mc1.16.5_v1.0.1     |DONE      |Manifest: NOSIGNATURE
		BetterDungeons-1.16.4-1.2.1.jar                   |YUNG's Better Dungeons        |betterdungeons                |1.16.4-1.2.1        |DONE      |Manifest: NOSIGNATURE
		immersivecooking-1.2.0.jar                        |Immersive Cooking             |immersivecooking              |1.2.0               |DONE      |Manifest: NOSIGNATURE
		auudio_forge_1.0.3-1_MC_1.16.2-1.16.5.jar         |Auudio                        |auudio                        |1.0.3               |DONE      |Manifest: NOSIGNATURE
		infernal-expansion-1.16.5-2.5.0.jar               |Infernal Expansion            |infernalexp                   |2.5.0               |DONE      |Manifest: NOSIGNATURE
		stalwart-dungeons-1.16.5-1.1.7.jar                |Stalwart Dungeons             |stalwart_dungeons             |1.1.7               |DONE      |Manifest: NOSIGNATURE
		strawgolem-1.16-1.9.jar                           |Straw Golem                   |strawgolem                    |1.16-1.9            |DONE      |Manifest: NOSIGNATURE
		rubidium-0.2.7.jar                                |Rubidium                      |rubidium                      |0.2.7               |DONE      |Manifest: NOSIGNATURE
		farmersdelightintegrations-1.16.5-1.2.jar         |Farmer's Delight Compats      |farmersdelightintegrations    |1.16.5-1.2          |DONE      |Manifest: NOSIGNATURE
		YungsApi-1.16.4-Forge-13.jar                      |YUNG's API                    |yungsapi                      |1.16.4-Forge-13     |DONE      |Manifest: NOSIGNATURE
		upgradednetherite_items-1.16.5-1.0.0.4-release.jar|Upgraded Netherite : Items    |upgradednetherite_items       |1.16.5-1.0.0.4-relea|DONE      |Manifest: NOSIGNATURE
		guardvillagers-1.16.5.1.2.6.jar                   |Guard Villagers               |guardvillagers                |1.2.6               |DONE      |Manifest: NOSIGNATURE
		randompatches-2.4.4-forge.jar                     |RandomPatches                 |randompatches                 |2.4.4-forge         |DONE      |Manifest: 92:f6:29:d4:09:89:f5:f5:98:5e:20:34:31:d0:7b:58:22:06:bd:a5:d1:6a:92:6e:ac:3d:8d:18:c5:b2:5b:d7
		PickUpNotifier-v1.2-1.16.3.jar                    |Pick Up Notifier              |pickupnotifier                |1.2                 |DONE      |Manifest: d3:cc:6f:1b:30:87:fa:d9:8f:91:15:20:27:63:95:aa:d5:cb:1b:5b:e6:36:cc:57:20:a9:b3:d4:d5:1a:5d:b8
		SnowRealMagic-1.16.4-2.9.0.jar                    |Snow! Real Magic!             |snowrealmagic                 |2.9.0               |DONE      |Manifest: NOSIGNATURE
		what_did_you_vote_for-1.16.5-1.0.5.jar            |What Did You Vote For?        |whatareyouvotingfor           |1.0                 |DONE      |Manifest: NOSIGNATURE
		JustEnoughResources-1.16.5-0.12.1.133.jar         |Just Enough Resources         |jeresources                   |0.12.1.133          |DONE      |Manifest: NOSIGNATURE
		RevampedWolf-1.16.4-0.7.1.jar                     |RevampedWolf                  |revampedwolf                  |1.16.4-0.7.1        |DONE      |Manifest: NOSIGNATURE
		supplementaries-1.16.5-0.18.4.jar                 |Supplementaries               |supplementaries               |0.18.2              |DONE      |Manifest: NOSIGNATURE
		betterendforge-1.16.5-2.5.jar                     |BetterEnd Forge               |betterendforge                |1.16.5-2.5          |DONE      |Manifest: NOSIGNATURE
		upgradednetherite-1.16.5-2.0.0.8-release.jar      |Upgraded Netherite            |upgradednetherite             |1.16.5-2.0.0.8-relea|DONE      |Manifest: NOSIGNATURE
		structure_gel-1.16.5-1.7.8.jar                    |Structure Gel API             |structure_gel                 |1.7.8               |DONE      |Manifest: NOSIGNATURE
		corpse-1.16.5-1.0.6.jar                           |Corpse                        |corpse                        |1.16.5-1.0.6        |DONE      |Manifest: NOSIGNATURE
		TinySkeletons-v1.0.1-1.16.5-Forge.jar             |Tiny Skeletons                |tinyskeletons                 |1.0.1               |DONE      |Manifest: 9a:09:85:98:65:c4:8c:11:c5:49:f6:d6:33:23:39:df:8d:b4:ff:92:84:b8:bd:a5:83:9f:ac:7f:2a:d1:4b:6a
		cleancut-mc1.16-2.2-forge.jar                     |Clean Cut                     |cleancut                      |2.2                 |DONE      |Manifest: NOSIGNATURE
		torchmaster-2.3.8.jar                             |Torchmaster                   |torchmaster                   |2.3.8               |DONE      |Manifest: NOSIGNATURE
		repurposed_structures_forge-3.4.7+1.16.5.jar      |Repurposed Structures         |repurposed_structures         |3.4.7+1.16.5        |DONE      |Manifest: NOSIGNATURE
		morevillagers-FORGE-1.16.5-1.5.5.jar              |More Villagers                |morevillagers                 |1.5.5               |DONE      |Manifest: NOSIGNATURE
		BetterCompatibilityChecker-1.0.7-build.22+mc1.16.5|Better Compatibility Checker  |bcc                           |1.0.7-build.22+mc1.1|DONE      |Manifest: NOSIGNATURE
		MorePaths-1.16.1-1.3.2.jar                        |MorePaths                     |morepaths                     |1.16-1.3.2          |DONE      |Manifest: NOSIGNATURE
		toughnessbar-6.1.jar                              |Toughness Bar                 |toughnessbar                  |6.1                 |DONE      |Manifest: NOSIGNATURE
		dungeons_plus-1.16.5-1.1.5.jar                    |Dungeons Plus                 |dungeons_plus                 |1.1.5               |DONE      |Manifest: NOSIGNATURE
		cavesandcliffs-1.16.5-7.2.0.jar                   |Caves and Cliffs Backport     |cavesandcliffs                |1.16.5-7.2.0        |DONE      |Manifest: NOSIGNATURE
		darkerdepths-1.16.5-1.1.4.jar                     |Darker Depths                 |darkerdepths                  |1.1.4               |DONE      |Manifest: NOSIGNATURE
		Highlighter-1.16.5-1.1.1.jar                      |Highlighter                   |highlighter                   |1.1.1               |DONE      |Manifest: NOSIGNATURE
		spark-1.9.1-forge.jar                             |spark                         |spark                         |1.9.1               |DONE      |Manifest: NOSIGNATURE
		curios-forge-1.16.5-4.0.5.3.jar                   |Curios API                    |curios                        |1.16.5-4.0.5.3      |DONE      |Manifest: NOSIGNATURE
		oculus-1.2.5.jar                                  |Oculus                        |oculus                        |1.2.5               |DONE      |Manifest: NOSIGNATURE
		extendedmushrooms-1.16.5-1.7.0.2.jar              |Extended Mushrooms            |extendedmushrooms             |1.16.5-1.7.0.2      |DONE      |Manifest: NOSIGNATURE
		obfuscate-0.6.3-1.16.5.jar                        |Obfuscate                     |obfuscate                     |0.6.3               |DONE      |Manifest: NOSIGNATURE
		TheAbyss2 2.2.3-4 1.16.5.jar                      |TheAbyss                      |theabyss                      |2.2.3-4             |DONE      |Manifest: NOSIGNATURE
		Adorn-1.14.3+1.16.5-forge.jar                     |Adorn                         |adorn                         |1.14.3+1.16.5-forge |DONE      |Manifest: NOSIGNATURE
		cloth-config-4.14.64-forge.jar                    |Cloth Config v4 API           |cloth-config                  |4.14.64             |DONE      |Manifest: NOSIGNATURE
		BetterShieldsMC1.16.3-1.2.1.jar                   |Better Shields                |bettershields                 |1.2.1               |DONE      |Manifest: NOSIGNATURE
		FallingTree-1.16.5-2.11.5.jar                     |FallingTree                   |fallingtree                   |2.11.5              |DONE      |Manifest: 3c:8e:df:6c:df:a6:2a:9f:af:64:ea:04:9a:cf:65:92:3b:54:93:0e:96:50:b4:52:e1:13:42:18:2b:ae:40:29
		CustomStartingGear-1.16.5-2.0.3-universal.jar     |Custom Starter Gear           |customstartinggear            |2.0.3.1             |DONE      |Manifest: 53:bb:a0:11:bd:61:e2:1a:e2:cb:fd:f8:4f:e4:cd:a5:cc:12:f4:43:f0:78:68:3b:e1:62:c6:78:3b:27:ff:fe
		FastLeafDecay-v25.2.jar                           |FastLeafDecay                 |fastleafdecay                 |v25.2               |DONE      |Manifest: NOSIGNATURE
		Babel-1.0.5.jar                                   |Babel                         |babel                         |1.0.5               |DONE      |Manifest: NOSIGNATURE
		JEPB-1.0.0.jar                                    |Just Enough Piglin Bartering  |jepb                          |1.0.0               |DONE      |Manifest: NOSIGNATURE
		BetterMineshafts-Forge-1.16.4-2.0.4.jar           |YUNG's Better Mineshafts      |bettermineshafts              |1.16.4-2.0.4        |DONE      |Manifest: NOSIGNATURE
		veinmining-forge-1.16.5-0.16.jar                  |Vein Mining                   |veinmining                    |1.16.5-0.16         |DONE      |Manifest: NOSIGNATURE
		SimpleDiscordRichPresence-1.4.0-build.3+mc1.16.5.j|Simple Discord Rich Presence  |sdrp                          |1.4.0-build.3+mc1.16|DONE      |Manifest: NOSIGNATURE
		BetterModsButton-v1.0.5-1.16.5-Forge.jar          |Better Mods Button            |bettermodsbutton              |1.0.5               |DONE      |Manifest: 9a:09:85:98:65:c4:8c:11:c5:49:f6:d6:33:23:39:df:8d:b4:ff:92:84:b8:bd:a5:83:9f:ac:7f:2a:d1:4b:6a
		NekosEnchantedBooks-1.16-1.7.0.jar                |NekoвЂ™s Enchanted Books        |nebs                          |1.7.0               |DONE      |Manifest: NOSIGNATURE
		DarkPaintings-1.16.5-6.0.11.jar                   |DarkPaintings                 |darkpaintings                 |6.0.11              |DONE      |Manifest: eb:c4:b1:67:8b:f9:0c:db:dc:4f:01:b1:8e:61:64:39:4c:10:85:0b:a6:c4:c7:48:f0:fa:95:f2:cb:08:3a:e5
		Kiwi-1.16.5-3.6.1.jar                             |Kiwi                          |kiwi                          |3.6.1               |DONE      |Manifest: NOSIGNATURE
		ClientTweaks_1.16.3-5.3.0.jar                     |Client Tweaks                 |clienttweaks                  |5.3.0               |DONE      |Manifest: NOSIGNATURE
		mowziesmobs-1.5.25.jar                            |Mowzie's Mobs                 |mowziesmobs                   |1.5.25              |DONE      |Manifest: NOSIGNATURE
		ConfigMenusForge-v1.2.0-1.16.5-Forge.jar          |Config Menus for Forge        |configmenusforge              |1.2.0               |DONE      |Manifest: 9a:09:85:98:65:c4:8c:11:c5:49:f6:d6:33:23:39:df:8d:b4:ff:92:84:b8:bd:a5:83:9f:ac:7f:2a:d1:4b:6a
		jei-1.16.5-7.7.1.152.jar                          |Just Enough Items             |jei                           |7.7.1.152           |DONE      |Manifest: NOSIGNATURE
		jei-professions-1.0.0-1.16.4.jar                  |JEI Professions               |jeiprofessions                |1.0.0               |DONE      |Manifest: NOSIGNATURE
		VisualWorkbench-v1.1.0-1.16.5.jar                 |Visual Workbench              |visualworkbench               |1.1.0               |DONE      |Manifest: 9a:09:85:98:65:c4:8c:11:c5:49:f6:d6:33:23:39:df:8d:b4:ff:92:84:b8:bd:a5:83:9f:ac:7f:2a:d1:4b:6a
		AttributeFix-1.16.5-10.1.4.jar                    |AttributeFix                  |attributefix                  |10.1.4              |DONE      |Manifest: eb:c4:b1:67:8b:f9:0c:db:dc:4f:01:b1:8e:61:64:39:4c:10:85:0b:a6:c4:c7:48:f0:fa:95:f2:cb:08:3a:e5
		differentiate-1.16.5-0.5.3.jar                    |Differentiate                 |differentiate                 |0.5.3               |DONE      |Manifest: NOSIGNATURE
		goblintraders-1.7.3-1.16.5.jar                    |Goblin Traders                |goblintraders                 |1.7.3               |DONE      |Manifest: NOSIGNATURE
		caelus-forge-1.16.5-2.1.3.2.jar                   |Caelus API                    |caelus                        |1.16.5-2.1.3.2      |DONE      |Manifest: NOSIGNATURE
		Paxi-Forge-1.16.4-1.0.jar                         |Paxi                          |paxi                          |1.16.4-1.0          |DONE      |Manifest: NOSIGNATURE
		Fallingleaves-1.16.3-1.2.4.jar                    |Falling Leaves                |fallingleaves                 |1.2.4-alpha+20220121|DONE      |Manifest: NOSIGNATURE
		NaturesCompass-1.16.5-1.9.1-forge.jar             |Nature's Compass              |naturescompass                |1.16.5-1.9.1-forge  |DONE      |Manifest: NOSIGNATURE
		SereneSeasons-1.16.5-4.0.1.125-universal.jar      |Serene Seasons                |sereneseasons                 |1.16.5-4.0.1.125    |DONE      |Manifest: NOSIGNATURE
		stoneholm-1.2.2.jar                               |Stoneholm                     |stoneholm                     |1.2                 |DONE      |Manifest: NOSIGNATURE
		curioofundying-forge-1.16.5-5.2.0.0.jar           |Curio of Undying              |curioofundying                |1.16.5-5.2.0.0      |DONE      |Manifest: NOSIGNATURE
		snowundertrees-1.16.5-v1.3.jar                    |Snow Under Trees              |snowundertrees                |v1.3                |DONE      |Manifest: NOSIGNATURE
		sulfuric-1.1.jar                                  |Sulfuric                      |sulfuric                      |1.0                 |DONE      |Manifest: NOSIGNATURE
		outvoted-1.16.5-1.2.4.jar                         |Outvoted                      |outvoted                      |1.2.4               |DONE      |Manifest: NOSIGNATURE
		JEITweaker-1.16.5-1.1.0.49.jar                    |JEI Tweaker                   |jeitweaker                    |1.1.0.49            |DONE      |Manifest: NOSIGNATURE
		CraftTweaker-1.16.5-7.1.2.511.jar                 |CraftTweaker                  |crafttweaker                  |7.1.2.511           |DONE      |Manifest: NOSIGNATURE
		forge-1.16.5-36.2.35-universal.jar                |Forge                         |forge                         |36.2.35             |DONE      |Manifest: 22:af:21:d8:19:82:7f:93:94:fe:2b:ac:b7:e4:41:57:68:39:87:b1:a7:5c:c6:44:f9:25:74:21:14:f5:0d:90
		DynamicSurroundings-1.16.5-4.0.5.0.jar            |В§3Dynamic Surroundings        |dsurround                     |4.0.5.0             |DONE      |Manifest: NOSIGNATURE
		DungeonsArise-1.16.5-2.1.49-beta.jar              |When Dungeons Arise           |dungeons_arise                |2.1.49              |DONE      |Manifest: NOSIGNATURE
		forge-1.16.5-36.2.35-client.jar                   |Minecraft                     |minecraft                     |1.16.5              |DONE      |Manifest: NOSIGNATURE
		MouseTweaks-2.14-mc1.16.2.jar                     |Mouse Tweaks                  |mousetweaks                   |2.14                |DONE      |Manifest: NOSIGNATURE
		CavesCliffsBackportAdditions-3.3.jar              |CavesandCliffsbackportaddition|cavesandcliffsbackportaddition|3.1                 |DONE      |Manifest: NOSIGNATURE
		paintings-1.16.4-7.0.0.1.jar                      |Paintings ++                  |paintings                     |1.16.4-6.0.1.5      |DONE      |Manifest: NOSIGNATURE
		Xaeros_Minimap_22.10.0_Forge_1.16.5.jar           |Xaero's Minimap               |xaerominimap                  |22.10.0             |DONE      |Manifest: NOSIGNATURE
		ftb-backups-2.1.2.2.jar                           |FTB Backups                   |ftbbackups                    |2.1.2.2             |DONE      |Manifest: NOSIGNATURE
		polymorph-forge-1.16.5-0.40.jar                   |Polymorph                     |polymorph                     |1.16.5-0.40         |DONE      |Manifest: NOSIGNATURE
		JustEnoughProfessions-1.16.5-1.2.2.jar            |Just Enough Professions (JEP) |justenoughprofessions         |1.2.2               |DONE      |Manifest: NOSIGNATURE
		AutoRegLib-1.6-49.jar                             |AutoRegLib                    |autoreglib                    |1.6-49              |DONE      |Manifest: NOSIGNATURE
		earthmobsmod-1.16.4-0.4.2.jar                     |Earth Mobs Mod                |earthmobsmod                  |1.16.4-0.4.2        |DONE      |Manifest: NOSIGNATURE
		entityculling-forge-mc1.16.5-1.5.2.jar            |EntityCulling                 |entityculling                 |1.5.2               |DONE      |Manifest: NOSIGNATURE
		upgradednetherite_ultimate-1.16.5-1.0.0.4-release.|Upgraded Netherite : Ultimerit|upgradednetherite_ultimate    |1.16.5-1.0.0.4-relea|DONE      |Manifest: NOSIGNATURE
		PuzzlesLib-v1.0.15-1.16.5-Forge.jar               |Puzzles Lib                   |puzzleslib                    |1.0.15              |DONE      |Manifest: 9a:09:85:98:65:c4:8c:11:c5:49:f6:d6:33:23:39:df:8d:b4:ff:92:84:b8:bd:a5:83:9f:ac:7f:2a:d1:4b:6a
		byg-1.3.5.jar                                     |Oh The Biomes You'll Go       |byg                           |1.3.4               |DONE      |Manifest: NOSIGNATURE
		Aquaculture-1.16.5-2.1.22.jar                     |Aquaculture 2                 |aquaculture                   |1.16.5-2.1.22       |DONE      |Manifest: NOSIGNATURE
		xptome-1.16.5-v2.1.5.jar                          |XP Tome                       |xpbook                        |v2.1.5              |DONE      |Manifest: NOSIGNATURE
		blue_skies-1.16.5-1.1.3.jar                       |Blue Skies                    |blue_skies                    |1.1.3               |DONE      |Manifest: NOSIGNATURE
		BetterF3-1.1.3-forge-1.16.5.jar                   |BetterF3 Forge                |betterf3forge                 |1.1.3               |DONE      |Manifest: NOSIGNATURE
		Architects-Palette-1.16.4-1.1.5.jar               |Architect's Palette           |architects_palette            |1.1.2               |DONE      |Manifest: NOSIGNATURE
		KleeSlabs_1.16.5-9.2.1.jar                        |KleeSlabs                     |kleeslabs                     |9.2.1               |DONE      |Manifest: NOSIGNATURE
		villagernames_1.16.5-3.4.jar                      |Villager Names                |villagernames                 |3.4                 |DONE      |Manifest: NOSIGNATURE
		XaerosWorldMap_1.24.0_Forge_1.16.5.jar            |Xaero's World Map             |xaeroworldmap                 |1.24.0              |DONE      |Manifest: NOSIGNATURE
		Controlling-7.0.0.28.jar                          |Controlling                   |controlling                   |7.0.0.28            |DONE      |Manifest: NOSIGNATURE
		citadel-1.8.1-1.16.5.jar                          |Citadel                       |citadel                       |1.8.1               |DONE      |Manifest: NOSIGNATURE
		alexsmobs-1.12.1.jar                              |Alex's Mobs                   |alexsmobs                     |1.12.1              |DONE      |Manifest: NOSIGNATURE
		ImprovedBackpacks-1.6.2.1.jar                     |Improved Backpacks            |improvedbackpacks             |1.6.2.1             |DONE      |Manifest: NOSIGNATURE
		Bookshelf-Forge-1.16.5-10.4.32.jar                |Bookshelf                     |bookshelf                     |10.4.32             |DONE      |Manifest: eb:c4:b1:67:8b:f9:0c:db:dc:4f:01:b1:8e:61:64:39:4c:10:85:0b:a6:c4:c7:48:f0:fa:95:f2:cb:08:3a:e5
		Tips-1.16.5-4.0.18.jar                            |Tips                          |tips                          |4.0.18              |DONE      |Manifest: eb:c4:b1:67:8b:f9:0c:db:dc:4f:01:b1:8e:61:64:39:4c:10:85:0b:a6:c4:c7:48:f0:fa:95:f2:cb:08:3a:e5
		bygonenether-1.1.2-1.16.5.jar                     |Bygone Nether                 |bygonenether                  |1.1.2               |DONE      |Manifest: NOSIGNATURE
		carryon-1.16.5-1.15.5.22.jar                      |Carry On                      |carryon                       |1.15.5.22           |DONE      |Manifest: NOSIGNATURE
		omnis-1.16.5-1.1.2.3.jar                          |Omnis                         |omnis                         |1.16.5-1.0          |DONE      |Manifest: NOSIGNATURE
		[1.16.X-1.0.10]+Dragon+Mounts+Legacy.jar          |Dragon Mounts: Legacy         |dragonmounts                  |1.0.10              |DONE      |Manifest: NOSIGNATURE
		twilightforest-1.16.5-4.0.870-universal.jar       |The Twilight Forest           |twilightforest                |NONE                |DONE      |Manifest: NOSIGNATURE
		konkrete_forge_1.3.3-1_MC_1.16.2-1.16.5.jar       |Konkrete                      |konkrete                      |1.3.3               |DONE      |Manifest: NOSIGNATURE
		cuneiform-1.16.3-1.2.5.jar                        |Cuneiform                     |cuneiform                     |1.16.3-1.2.5        |DONE      |Manifest: NOSIGNATURE
		JEIEnchantmentInfo-1.16.5-1.3.0.jar               |JEI Enchantment Info          |jeienchantmentinfo            |1.16.5-1.3.0        |DONE      |Manifest: NOSIGNATURE
		EquipmentCompare-1.16.5-1.2.7.jar                 |Equipment Compare             |equipmentcompare              |1.2.7               |DONE      |Manifest: NOSIGNATURE
		chocolate-1.3.0-1.16.4.jar                        |Chocolate                     |chocolate                     |1.3.0-1.16.4        |DONE      |Manifest: NOSIGNATURE
		FarmersDelight-1.16.5-0.6.0.jar                   |Farmer's Delight              |farmersdelight                |1.16.5-0.6.0        |DONE      |Manifest: NOSIGNATURE
		fd_cookbook-2.0.jar                               |Farmers Delight Cookbook      |fd_cookbook                   |2.0                 |DONE      |Manifest: NOSIGNATURE
		culturaldelights-1.16.5-0.9.2.jar                 |Cultural Delights             |culturaldelights              |0.9.2               |DONE      |Manifest: NOSIGNATURE
		farmersdelightintegration-1.16.5-1.0.3.jar        |Farmer's Delight Integration  |farmersdelightintegration     |1.16.5-1.0.3        |DONE      |Manifest: NOSIGNATURE
		simpleshops-1.1.3.jar                             |Simple Shops                  |simpleshops                   |1.1.3               |DONE      |Manifest: NOSIGNATURE
		Talpm 1.0.0 1.16.5.jar                            |TheAbyss LPM Integration      |talpm                         |1.0.0               |DONE      |Manifest: NOSIGNATURE
		Bountiful-1.16.4-3.3.1.jar                        |Bountiful                     |bountiful                     |1.16.4-3.3.1        |DONE      |Manifest: NOSIGNATURE
		CNB-1.16.3_5-1.2.11.jar                           |Creatures and Beasts          |cnb                           |1.2.11              |DONE      |Manifest: NOSIGNATURE
		geckolib-forge-1.16.5-3.0.81.jar                  |GeckoLib                      |geckolib3                     |3.0.81              |DONE      |Manifest: NOSIGNATURE
		Cataclysm-0.19.jar                                |Cataclysm Mod                 |cataclysm                     |1.0                 |DONE      |Manifest: NOSIGNATURE
		Patchouli-1.16.4-53.3.jar                         |Patchouli                     |patchouli                     |1.16.4-53.3         |DONE      |Manifest: NOSIGNATURE
		collective-1.16.5-4.28.jar                        |Collective                    |collective                    |4.28                |DONE      |Manifest: NOSIGNATURE
		villagertools-1.16.5-1.0.2.jar                    |villagertools                 |villagertools                 |1.16.5-1.0.2        |DONE      |Manifest: 1f:47:ac:b1:61:82:96:b8:47:19:16:d2:61:81:11:60:3a:06:4b:61:31:56:7d:44:31:1e:0c:6f:22:5b:4c:ed
		elevatorid-1.16.5-1.7.13.jar                      |Elevator Mod                  |elevatorid                    |1.16.5-1.7.13       |DONE      |Manifest: NOSIGNATURE
		BetterStrongholds-1.16.4-1.2.1.jar                |YUNG's Better Strongholds     |betterstrongholds             |1.16.4-1.2.1        |DONE      |Manifest: NOSIGNATURE
		travelers_index-1.16.4-1.0.2.jar                  |Traveler's Index              |travelers_index               |1.16.4-1.0.2        |DONE      |Manifest: NOSIGNATURE
		cavebiomeapi-1.16.5-1.4.2.jar                     |CaveBiomeAPI                  |cavebiomeapi                  |1.16.5-1.4.2        |DONE      |Manifest: NOSIGNATURE
		architectury-1.32.66.jar                          |Architectury                  |architectury                  |1.32.66             |DONE      |Manifest: NOSIGNATURE
		ftb-library-forge-1605.3.4-build.90.jar           |FTB Library                   |ftblibrary                    |1605.3.4-build.90   |DONE      |Manifest: NOSIGNATURE
		ftb-teams-forge-1605.2.3-build.40.jar             |FTB Teams                     |ftbteams                      |1605.2.3-build.40   |DONE      |Manifest: NOSIGNATURE
		curiouselytra-forge-1.16.5-4.0.2.4.jar            |Curious Elytra                |curiouselytra                 |1.16.5-4.0.2.4      |DONE      |Manifest: NOSIGNATURE
		AI-Improvements-1.16.5-0.5.0.jar                  |AI-Improvements               |aiimprovements                |0.4.0               |DONE      |Manifest: NOSIGNATURE
		enchantwithmob-1.16.5-1.5.2.jar                   |Enchant With Mob              |enchantwithmob                |1.16.5-1.5.2        |DONE      |Manifest: NOSIGNATURE
		voidtotem-1.16.5-1.4.0.jar                        |Void Totem                    |voidtotem                     |1.16.5-1.4.0        |DONE      |Manifest: NOSIGNATURE
		TradingPost-v1.0.2-1.16.5.jar                     |Trading Post                  |tradingpost                   |1.0.2               |DONE      |Manifest: 9a:09:85:98:65:c4:8c:11:c5:49:f6:d6:33:23:39:df:8d:b4:ff:92:84:b8:bd:a5:83:9f:ac:7f:2a:d1:4b:6a
		BetterAdvancements-1.16.5-0.1.1.115.jar           |Better Advancements           |betteradvancements            |0.1.1.115           |DONE      |Manifest: NOSIGNATURE
		BH-Menu-1.16.5-1.3.jar                            |Bisect Hosting Menu           |bhmenu                        |1.16.5-1.3          |DONE      |Manifest: NOSIGNATURE
		NourishedNetherV12-1.16.5Backport.jar             |Nourished Nether              |nourished_nether              |1.1.3               |DONE      |Manifest: NOSIGNATURE
		item-filters-forge-1605.2.5-build.9.jar           |Item Filters                  |itemfilters                   |1605.2.5-build.9    |DONE      |Manifest: NOSIGNATURE
		ftb-quests-forge-1605.3.6-build.98.jar            |FTB Quests                    |ftbquests                     |1605.3.6-build.98   |DONE      |Manifest: NOSIGNATURE
		EasyMagic-v1.0.4-1.16.5.jar                       |Easy Magic                    |easymagic                     |1.0.4               |DONE      |Manifest: 9a:09:85:98:65:c4:8c:11:c5:49:f6:d6:33:23:39:df:8d:b4:ff:92:84:b8:bd:a5:83:9f:ac:7f:2a:d1:4b:6a
		NourishedEndV9-1.16.5Backport.jar                 |Nourished End                 |nourished_end                 |1.0.8               |DONE      |Manifest: NOSIGNATURE
		xlpackets-1.16.4-1.2.jar                          |XL Packets                    |xlpackets                     |1.16.4-1.2          |DONE      |Manifest: NOSIGNATURE
		the-conjurer-1.16.4-1.0.13.jar                    |The Conjurer                  |conjurer_illager              |1.0.13              |DONE      |Manifest: NOSIGNATURE
		dungeons_mobs-1.16.5-1.0.10.jar                   |Dungeons Mobs                 |dungeons_mobs                 |1.0.10              |DONE      |Manifest: NOSIGNATURE
		abnormals_core-1.16.5-3.3.1.jar                   |Abnormals Core                |abnormals_core                |3.3.1               |DONE      |Manifest: NOSIGNATURE
		environmental-1.16.5-1.1.1.jar                    |Environmental                 |environmental                 |1.1.1               |DONE      |Manifest: NOSIGNATURE
		bamboo_blocks-1.16.5-3.0.1.jar                    |Bamboo Blocks                 |bamboo_blocks                 |3.0.1               |DONE      |Manifest: NOSIGNATURE
		copperpot-1.16.5-1.2.0.jar                        |Copper Pot                    |copperpot                     |1.16.5-1.2.0        |DONE      |Manifest: NOSIGNATURE
		Bayou-Blues-1.16.5-1.0.5.jar                      |Bayou Blues                   |bayou_blues                   |1.16.5-1.0.5        |DONE      |Manifest: NOSIGNATURE
		upgrade_aquatic-1.16.5-3.1.2.jar                  |Upgrade Aquatic               |upgrade_aquatic               |3.1.2               |DONE      |Manifest: NOSIGNATURE
		Better-Badlands-1.16.5-2.0.3.jar                  |Better Badlands               |better_badlands               |1.16.5-2.0.3        |DONE      |Manifest: NOSIGNATURE
		irregularchef-1.16.5-1.0.1.jar                    |The Irregular Chef            |irregularchef                 |1.16.5-1.0.1        |DONE      |Manifest: NOSIGNATURE
		endergetic-1.16.5-3.0.2.jar                       |The Endergetic Expansion      |endergetic                    |3.0.2               |DONE      |Manifest: NOSIGNATURE
		neapolitan-1.16.5-2.2.1.jar                       |Neapolitan                    |neapolitan                    |2.2.1               |DONE      |Manifest: NOSIGNATURE
		personality-1.16.5-1.0.3.jar                      |Personality                   |personality                   |1.0.3               |DONE      |Manifest: NOSIGNATURE
		savageandravage-1.16.5-3.2.0.jar                  |Savage & Ravage               |savageandravage               |3.2.0               |DONE      |Manifest: NOSIGNATURE
		autumnity-1.16.5-2.1.2.jar                        |Autumnity                     |autumnity                     |2.1.2               |DONE      |Manifest: NOSIGNATURE
		nethers_delight-2.1.jar                           |Nethers Delight               |nethers_delight               |2.1                 |DONE      |Manifest: NOSIGNATURE
		buzzier_bees-1.16.5-3.0.3.jar                     |Buzzier Bees                  |buzzier_bees                  |3.0.3               |DONE      |Manifest: NOSIGNATURE
		Enhanced-Mushrooms-1.16.5-3.0.9.jar               |Enhanced Mushrooms            |enhanced_mushrooms            |1.16.5-3.0.9        |DONE      |Manifest: NOSIGNATURE
		extraboats-1.16.5-2.1.1.jar                       |Extra Boats                   |extraboats                    |2.1.1               |DONE      |Manifest: NOSIGNATURE
		Waystones_1.16.5-7.6.4.jar                        |Waystones                     |waystones                     |7.6.4               |DONE      |Manifest: NOSIGNATURE
		goldenhopper-1.2.1-1.16.3.jar                     |Golden Hopper                 |goldenhopper                  |1.2.1               |DONE      |Manifest: NOSIGNATURE
		Clumps-6.0.0.28.jar                               |Clumps                        |clumps                        |6.0.0.28            |DONE      |Manifest: NOSIGNATURE
		village-employment-1.16.5-1.4.1.jar               |Village Employment            |village_employment            |1.4.1               |DONE      |Manifest: NOSIGNATURE
		RoadRunner-mc1.16.5-1.4.1.jar                     |Meep Meep! (Road Runner)      |roadrunner                    |1.4.1               |DONE      |Manifest: NOSIGNATURE
		comforts-forge-1.16.5-4.0.1.5.jar                 |Comforts                      |comforts                      |1.16.5-4.0.1.5      |DONE      |Manifest: NOSIGNATURE
		tumbleweed-1.16-0.4.9.jar                         |Tumbleweed                    |tumbleweed                    |1.16-0.4.9          |DONE      |Manifest: NOSIGNATURE
		campful-1.16.5-3.1.0.jar                          |Campful                       |campful                       |2.0                 |DONE      |Manifest: NOSIGNATURE
		SimpleStorageNetwork-1.16.5-1.5.2.jar             |Simple Storage Network        |storagenetwork                |1.16.5-1.5.2        |DONE      |Manifest: 1f:47:ac:b1:61:82:96:b8:47:19:16:d2:61:81:11:60:3a:06:4b:61:31:56:7d:44:31:1e:0c:6f:22:5b:4c:ed
		OuterEnd-0.2.14.jar                               |The Outer End                 |outer_end                     |0.2.9               |DONE      |Manifest: NOSIGNATURE
		BadMobs-1.16.5-9.1.8.jar                          |BadMobs                       |badmobs                       |9.1.8               |DONE      |Manifest: eb:c4:b1:67:8b:f9:0c:db:dc:4f:01:b1:8e:61:64:39:4c:10:85:0b:a6:c4:c7:48:f0:fa:95:f2:cb:08:3a:e5
		deepdark_4.2.jar                                  |Dead Guy's Untitled Deep Dark |dead_guys_untitled_deep_dark_ |Frist Version!      |DONE      |Manifest: NOSIGNATURE
		lazydfu-0.1.3.jar                                 |LazyDFU                       |lazydfu                       |0.1.3               |DONE      |Manifest: NOSIGNATURE
		magnesium_extras-mc1.16.5_v1.3.1.jar              |Magnesium Extras              |magnesium_extras              |mc1.16.5_v1.3.1     |DONE      |Manifest: NOSIGNATURE
		ftb-chunks-forge-1605.3.2-build.115.jar           |FTB Chunks                    |ftbchunks                     |1605.3.2-build.115  |DONE      |Manifest: NOSIGNATURE
		frozenup-1.0.1.jar                                |Frozen Up                     |frozenup                      |1.0.1               |DONE      |Manifest: NOSIGNATURE
		3dSkinLayers-forge-1.1.0.jar                      |3dSkinLayers                  |skinlayers3d                  |1.1.0               |DONE      |Manifest: NOSIGNATURE
		TravelersTitles-1.16.4-1.5.jar                    |Traveler's Titles             |travelerstitles               |1.16.4-1.5          |DONE      |Manifest: NOSIGNATURE
		selene-1.16.5-1.9.0.jar                           |Selene                        |selene                        |1.16.5-1.0          |DONE      |Manifest: NOSIGNATURE
		EnchantmentDescriptions-1.16.5-7.1.20.jar         |EnchantmentDescriptions       |enchdesc                      |7.1.20              |DONE      |Manifest: eb:c4:b1:67:8b:f9:0c:db:dc:4f:01:b1:8e:61:64:39:4c:10:85:0b:a6:c4:c7:48:f0:fa:95:f2:cb:08:3a:e5
		Jade-1.16.4-2.8.1.jar                             |Jade                          |jade                          |2.8.1               |DONE      |Manifest: NOSIGNATURE
		atmospheric-1.16.5-3.1.1.jar                      |Atmospheric                   |atmospheric                   |3.1.1               |DONE      |Manifest: NOSIGNATURE
		Iceberg-1.16.5-1.0.41.jar                         |Iceberg                       |iceberg                       |1.0.41              |DONE      |Manifest: NOSIGNATURE
		Quark-r2.4-322.jar                                |Quark                         |quark                         |r2.4-322            |DONE      |Manifest: NOSIGNATURE
		terraincognita-1.16.3-1.7.3.jar                   |Terra Incognita               |terraincognita                |1.16.3-1.7.3        |DONE      |Manifest: NOSIGNATURE
		kryptonreforged-mc1.16.5_v1.0.0.jar               |Krypton Reforged              |kryptonreforged               |mc1.16.5_v1.0.0     |DONE      |Manifest: NOSIGNATURE
		abnormals_delight-1.16.5-1.2.1.jar                |Abnormals Delight             |abnormals_delight             |1.2.1               |DONE      |Manifest: NOSIGNATURE
		InventoryHud_[1.16.2-1.16.5].forge-3.4.1.jar      |Inventory HUD+(Forge edition) |inventoryhud                  |3.4.1               |DONE      |Manifest: NOSIGNATURE
		illagersweararmor-1.0.5.jar                       |Illagers Wear Armor           |illagersweararmor             |1.0.5               |DONE      |Manifest: NOSIGNATURE
		muchmoremodcompat-1.0.0.jar                       |Much More Mod Compat          |muchmoremodcompat             |NONE                |DONE      |Manifest: NOSIGNATURE
		decorative_blocks-1.16.4-1.7.2.jar                |Decorative Blocks             |decorative_blocks             |1.7.2               |DONE      |Manifest: NOSIGNATURE
		decorative_blocks_abnormals-1.2.jar               |Decorative Blocks Abnormals   |decorative_blocks_abnormals   |1.2                 |DONE      |Manifest: NOSIGNATURE
		combustivefishing-forge-1.16.3-4.0.0.1.jar        |Combustive Fishing            |combustivefishing             |1.16.3-4.0.0.1      |DONE      |Manifest: NOSIGNATURE
		fancymenu_forge_2.9.1_MC_1.16.2-1.16.5.jar        |FancyMenu                     |fancymenu                     |2.9.1               |DONE      |Manifest: NOSIGNATURE
		drippyloadingscreen_forge_1.6.4_MC_1.16.2-1.16.5.j|Drippy Loading Screen         |drippyloadingscreen           |1.6.4               |DONE      |Manifest: NOSIGNATURE
		Blocks+-1.16.5-1.2.jar                            |Blocks +                      |blocksplus                    |1.2                 |DONE      |Manifest: NOSIGNATURE
		upgradedcore-1.16.5-1.0.0.3-release.jar           |Upgraded Core                 |upgradedcore                  |1.16.5-1.0.0.3-relea|DONE      |Manifest: NOSIGNATURE
		ferritecore-2.1.0-forge.jar                       |Ferrite Core                  |ferritecore                   |2.1.0               |DONE      |Manifest: 41:ce:50:66:d1:a0:05:ce:a1:0e:02:85:9b:46:64:e0:bf:2e:cf:60:30:9a:fe:0c:27:e0:63:66:9a:84:ce:8a
		enhancedcelestials-2.0.9-1.16.5.jar               |Enhanced Celestials           |enhancedcelestials            |2.0.9-1.16.5        |DONE      |Manifest: NOSIGNATURE
		overloadedarmorbar-5.1.0.jar                      |Overloaded Armor Bar          |overloadedarmorbar            |5.1.0               |DONE      |Manifest: NOSIGNATURE
		NatureExpansion1.5.jar                            |Nature Expansion              |nature_expansion              |1.3.0               |DONE      |Manifest: NOSIGNATURE
	Crash Report UUID: c779ce14-1e91-4c05-9459-00646767d303
	RoadRunner != Lithium: This instance was launched using RoadRunner, which is an *unofficial* Lithium fork! Please **do not** report bugs to them!
	Kiwi Modules: 
		
	Patchouli open book context: n/a
	Loaded Shaderpack: (off)
	Player Count: 0 / 8; []
	Data Packs: vanilla, mod:dynamiclightsreforged, mod:betterdungeons, mod:immersivecooking, mod:auudio (incompatible), mod:infernalexp (incompatible), mod:stalwart_dungeons, mod:strawgolem, mod:rubidium (incompatible), mod:farmersdelightintegrations, mod:yungsapi, mod:upgradednetherite_items, mod:guardvillagers, mod:randompatches, mod:pickupnotifier (incompatible), mod:snowrealmagic, mod:whatareyouvotingfor, mod:jeresources, mod:revampedwolf, mod:supplementaries, mod:betterendforge, mod:upgradednetherite, mod:structure_gel, mod:corpse, mod:tinyskeletons, mod:cleancut (incompatible), mod:torchmaster (incompatible), mod:repurposed_structures, mod:morevillagers, mod:bcc (incompatible), mod:morepaths (incompatible), mod:toughnessbar (incompatible), mod:dungeons_plus, mod:cavesandcliffs, mod:darkerdepths, mod:highlighter, mod:spark, mod:curios, mod:oculus, mod:extendedmushrooms, mod:obfuscate, mod:theabyss, mod:adorn, mod:cloth-config (incompatible), mod:bettershields, mod:fallingtree, mod:customstartinggear (incompatible), mod:fastleafdecay, mod:babel, mod:jepb, mod:bettermineshafts, mod:veinmining, mod:sdrp (incompatible), mod:bettermodsbutton, mod:nebs, mod:darkpaintings, mod:kiwi, mod:clienttweaks (incompatible), mod:mowziesmobs, mod:configmenusforge, mod:jei, mod:jeiprofessions (incompatible), mod:visualworkbench, mod:attributefix, mod:differentiate, mod:goblintraders, mod:caelus, mod:paxi, mod:fallingleaves, mod:naturescompass (incompatible), mod:sereneseasons, mod:stoneholm, mod:curioofundying, mod:snowundertrees, mod:sulfuric, mod:outvoted, mod:jeitweaker, mod:crafttweaker, mod:forge, mod:dsurround, mod:dungeons_arise, mod:mousetweaks, mod:cavesandcliffsbackportadditions, mod:paintings (incompatible), mod:xaerominimap, mod:ftbbackups (incompatible), mod:polymorph, mod:justenoughprofessions, mod:autoreglib (incompatible), mod:earthmobsmod (incompatible), mod:entityculling, mod:upgradednetherite_ultimate, mod:puzzleslib, mod:byg, mod:aquaculture (incompatible), mod:xpbook, mod:blue_skies (incompatible), mod:betterf3forge, mod:architects_palette (incompatible), mod:kleeslabs (incompatible), mod:villagernames, mod:xaeroworldmap, mod:controlling, mod:citadel (incompatible), mod:alexsmobs, mod:improvedbackpacks, mod:bookshelf, mod:tips, mod:bygonenether (incompatible), mod:carryon, mod:omnis, mod:dragonmounts, mod:twilightforest, mod:konkrete, mod:cuneiform, mod:jeienchantmentinfo, mod:equipmentcompare, mod:chocolate, mod:farmersdelight, mod:fd_cookbook, mod:culturaldelights, mod:farmersdelightintegration, mod:simpleshops, mod:talpm, mod:bountiful (incompatible), mod:cnb, mod:geckolib3 (incompatible), mod:cataclysm (incompatible), mod:patchouli (incompatible), mod:collective, mod:villagertools, mod:elevatorid, mod:betterstrongholds, mod:travelers_index (incompatible), mod:cavebiomeapi, mod:architectury, mod:ftblibrary, mod:ftbteams, mod:curiouselytra, mod:aiimprovements, mod:enchantwithmob, mod:voidtotem, mod:tradingpost, mod:betteradvancements, mod:bhmenu, mod:nourished_nether, mod:itemfilters, mod:ftbquests, mod:easymagic, mod:nourished_end, mod:xlpackets, mod:conjurer_illager (incompatible), mod:dungeons_mobs (incompatible), mod:abnormals_core, mod:environmental, mod:bamboo_blocks, mod:copperpot, mod:bayou_blues, mod:upgrade_aquatic, mod:better_badlands, mod:irregularchef, mod:endergetic, mod:neapolitan, mod:personality, mod:savageandravage, mod:autumnity, mod:nethers_delight, mod:buzzier_bees, mod:enhanced_mushrooms, mod:extraboats, mod:waystones (incompatible), mod:goldenhopper (incompatible), mod:clumps, mod:village_employment, mod:roadrunner (incompatible), mod:comforts, mod:tumbleweed (incompatible), mod:campful, mod:storagenetwork, mod:outer_end, mod:badmobs (incompatible), mod:dead_guys_untitled_deep_dark_, mod:lazydfu, mod:magnesium_extras, mod:ftbchunks, mod:frozenup, mod:skinlayers3d, mod:travelerstitles, mod:selene, mod:enchdesc, mod:jade, mod:atmospheric, mod:iceberg, mod:quark (incompatible), mod:terraincognita, mod:kryptonreforged (incompatible), mod:abnormals_delight, mod:inventoryhud, mod:illagersweararmor (incompatible), mod:muchmoremodcompat, mod:decorative_blocks, mod:decorative_blocks_abnormals, mod:combustivefishing (incompatible), mod:fancymenu (incompatible), mod:drippyloadingscreen, mod:blocksplus, mod:upgradedcore, mod:ferritecore (incompatible), mod:enhancedcelestials, mod:overloadedarmorbar (incompatible), mod:nature_expansion, Repurposed_Structures-Better_Dungeons_Forge.zip, Repurposed_Structures-Better_Strongholds_Forge.zip, Repurposed_Structures-Buzzier_Bees.zip, Repurposed_Structures-Caves_And_Cliffs_Backport-v2.zip, Repurposed_Structures-Environmental.zip, Repurposed_Structures-Farmers_Delight_Forge.zip, Repurposed_Structures-More_Villagers_Forge_v2.zip, Repurposed_Structures-Savage_And_Ravage.zip, ichphilipp-s-endcity-v1-1-1-16-2-forge.zip (incompatible), the-forbidden-castle-v1-1.zip
	Type: Integrated Server (map_client.txt)
	Is Modded: Definitely; Client brand changed to 'forge'
[17:09:31] [Render thread/INFO]: [net.minecraft.util.registry.Bootstrap:func_179870_a:123]: #@!@# Game crashed! Crash report saved to: #@!@# C:\Users\kaio-\AppData\Roaming\.minecraft\versions\Better MC [FORGE] 1.16.5 Better MC [FORGE] v57.5\crash-reports\crash-2022-09-01_17.09.38-server.txt
[17:09:35] [DiscordRP Stop/INFO]: Shutting down Discord Rich Presence client
[17:09:35] [DiscordRP Stop/INFO]: Discord client closed.
2022-09-01 17:09:39,865 Netty Local Client IO #0 WARN Error parsing URI C:\Users\kaio-\AppData\Roaming\.minecraft\assets\log_configs\client-1.12.xml
2022-09-01 17:09:39,916 Netty Local Client IO #0 WARN Unable to register Log4j shutdown hook because JVM is shutting down. Using SimpleLogger
AL lib: (EE) alc_cleanup: 1 device not closed
Here I am!
[VersionManager] Refreshing versions locally...
[VersionManager] Versions has been refreshed (97 ms)
[Launcher] Minecraft closed with exit code: -1
[Launcher] Launcher exited.
flush now
