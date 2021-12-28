---- Minecraft Crash Report ----
// Surprise! Haha. Well, this is awkward.

Time: 12/27/21, 10:34 PM
Description: Unexpected error

java.util.NoSuchElementException
	at java.base/java.util.ArrayDeque.getLast(ArrayDeque.java:413)
	at net.minecraft.class_4587.method_23760(class_4587.java:65)
	at net.minecraft.class_757.redirect$bbc000$iris$saveBobbing(class_757.java:4041)
	at net.minecraft.class_757.method_3188(class_757.java:1025)
	at net.minecraft.class_757.method_3192(class_757.java:811)
	at net.minecraft.class_310.method_1523(class_310.java:1117)
	at net.minecraft.class_310.method_1514(class_310.java:733)
	at net.minecraft.client.main.Main.main(Main.java:238)
	at java.base/jdk.internal.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at java.base/jdk.internal.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:77)
	at java.base/jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.base/java.lang.reflect.Method.invoke(Method.java:568)
	at net.fabricmc.loader.impl.game.minecraft.MinecraftGameProvider.launch(MinecraftGameProvider.java:602)
	at net.fabricmc.loader.impl.launch.knot.Knot.launch(Knot.java:77)
	at net.fabricmc.loader.impl.launch.knot.KnotClient.main(KnotClient.java:23)


A detailed walkthrough of the error, its code path and all known details is as follows:
---------------------------------------------------------------------------------------

-- Head --
Thread: Render thread
Stacktrace:
	at java.base/java.util.ArrayDeque.getLast(ArrayDeque.java:413)
	at net.minecraft.class_4587.method_23760(class_4587.java:65)
	at net.minecraft.class_757.redirect$bbc000$iris$saveBobbing(class_757.java:4041)
	at net.minecraft.class_757.method_3188(class_757.java:1025)

-- Affected level --
Details:
	All players: 1 total; [class_746['Magnus27k'/116, l='ClientLevel', x=-38.50, y=72.00, z=-24.50]]
	Chunk stats: 4096, 443
	Level dimension: minecraft:overworld
	Level spawn location: World: (-32,65,-32), Section: (at 0,1,0 in -2,4,-2; chunk contains blocks -32,-64,-32 to -17,319,-17), Region: (-1,-1; contains chunks -32,-32 to -1,-1, blocks -512,-64,-512 to -1,319,-1)
	Level time: 5 game time, 5 day time
	Server brand: fabric
	Server type: Integrated singleplayer server
Stacktrace:
	at net.minecraft.class_638.method_8538(class_638.java:408)
	at net.minecraft.class_310.method_1587(class_310.java:2402)
	at net.minecraft.class_310.method_1514(class_310.java:757)
	at net.minecraft.client.main.Main.main(Main.java:238)
	at java.base/jdk.internal.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at java.base/jdk.internal.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:77)
	at java.base/jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.base/java.lang.reflect.Method.invoke(Method.java:568)
	at net.fabricmc.loader.impl.game.minecraft.MinecraftGameProvider.launch(MinecraftGameProvider.java:602)
	at net.fabricmc.loader.impl.launch.knot.Knot.launch(Knot.java:77)
	at net.fabricmc.loader.impl.launch.knot.KnotClient.main(KnotClient.java:23)

-- Last reload --
Details:
	Reload number: 1
	Reload reason: initial
	Finished: Yes
	Packs: Default, Fabric Mods

-- System Details --
Details:
	Minecraft Version: 1.18.1
	Minecraft Version ID: 1.18.1
	Operating System: Windows 10 (amd64) version 10.0
	Java Version: 17.0.1, Microsoft
	Java VM Version: OpenJDK 64-Bit Server VM (mixed mode), Microsoft
	Memory: 940783016 bytes (897 MiB) / 2147483648 bytes (2048 MiB) up to 2147483648 bytes (2048 MiB)
	CPUs: 4
	Processor Vendor: GenuineIntel
	Processor Name: Intel(R) Core(TM) i3-8100 CPU @ 3.60GHz
	Identifier: Intel64 Family 6 Model 158 Stepping 11
	Microarchitecture: Coffee Lake
	Frequency (GHz): 3.60
	Number of physical packages: 1
	Number of physical CPUs: 4
	Number of logical CPUs: 4
	Graphics card #0 name: NVIDIA GeForce GTX 1660 SUPER
	Graphics card #0 vendor: NVIDIA (0x10de)
	Graphics card #0 VRAM (MB): 4095.00
	Graphics card #0 deviceId: 0x21c4
	Graphics card #0 versionInfo: DriverVersion=30.0.14.7212
	Memory slot #0 capacity (MB): 8192.00
	Memory slot #0 clockSpeed (GHz): 2.40
	Memory slot #0 type: DDR4
	Memory slot #1 capacity (MB): 8192.00
	Memory slot #1 clockSpeed (GHz): 2.40
	Memory slot #1 type: DDR4
	Virtual memory max (MB): 34318.83
	Virtual memory used (MB): 17698.01
	Swap memory total (MB): 17993.38
	Swap memory used (MB): 457.26
	JVM Flags: 9 total; -XX:HeapDumpPath=MojangTricksIntelDriversForPerformance_javaw.exe_minecraft.exe.heapdump -Xss1M -Xmx2G -XX:+UnlockExperimentalVMOptions -XX:+UseG1GC -XX:G1NewSizePercent=20 -XX:G1ReservePercent=20 -XX:MaxGCPauseMillis=50 -XX:G1HeapRegionSize=32M
	Fabric Mods: 
		apoli: Apoli 2.2.2
		architectury: Architectury 3.1.45
		awesomedungeon: Awesome Dungeon 1.1.4
		blue_endless_jankson: jankson 1.2.1
		calio: Calio 1.4.2
		cardinal-components-base: Cardinal Components API (base) 4.0.0-alpha.1+21w37a
		cardinal-components-entity: Cardinal Components API (entities) 4.0.0-alpha.1+21w37a
		cloth-basic-math: cloth-basic-math 0.6.0
		cloth-config: Cloth Config v6 6.0.42
		copperequipment: Copper Equipment 1.8.1
		diggusmaximus: Diggus Maximus 1.5.2-1.18
		dungeonvanilla: Dungeon vanilla 1.0.0
		enchant_giver: Enchant Giver 1.1.0
		expandedstorage: Expanded Storage 7.3.0
		fabric: Fabric API 0.43.1+1.18
		fabric-api-base: Fabric API Base 0.4.1+b4f4f6cd14
		fabric-api-lookup-api-v1: Fabric API Lookup API (v1) 1.3.5+3ac43d9514
		fabric-biome-api-v1: Fabric Biome API (v1) 6.0.1+3ac43d9514
		fabric-blockrenderlayer-v1: Fabric BlockRenderLayer Registration (v1) 1.1.9+3ac43d9514
		fabric-command-api-v1: Fabric Command API (v1) 1.1.6+3ac43d9514
		fabric-commands-v0: Fabric Commands (v0) 0.2.5+b4f4f6cd14
		fabric-containers-v0: Fabric Containers (v0) 0.1.18+d154e2c614
		fabric-content-registries-v0: Fabric Content Registries (v0) 0.4.5+6f53a73d14
		fabric-crash-report-info-v1: Fabric Crash Report Info (v1) 0.1.8+3ac43d9514
		fabric-dimensions-v1: Fabric Dimensions API (v1) 2.1.7+43d2957114
		fabric-entity-events-v1: Fabric Entity Events (v1) 1.4.5+6b21378a14
		fabric-events-interaction-v0: Fabric Events Interaction (v0) 0.4.15+3ac43d9514
		fabric-events-lifecycle-v0: Fabric Events Lifecycle (v0) 0.2.5+b4f4f6cd14
		fabric-game-rule-api-v1: Fabric Game Rule API (v1) 1.0.10+3ac43d9514
		fabric-item-api-v1: Fabric Item API (v1) 1.2.7+3ac43d9514
		fabric-item-groups-v0: Fabric Item Groups (v0) 0.3.3+3ac43d9514
		fabric-key-binding-api-v1: Fabric Key Binding API (v1) 1.0.8+c8aba2f314
		fabric-keybindings-v0: Fabric Key Bindings (v0) 0.2.6+b4f4f6cd14
		fabric-lifecycle-events-v1: Fabric Lifecycle Events (v1) 1.4.10+c15ca33514
		fabric-loot-tables-v1: Fabric Loot Tables (v1) 1.0.8+3ac43d9514
		fabric-mining-level-api-v1: Fabric Mining Level API (v1) 1.0.3+3ac43d9514
		fabric-mining-levels-v0: Fabric Mining Levels (v0) 0.1.7+b4f4f6cd14
		fabric-models-v0: Fabric Models (v0) 0.3.3+3ac43d9514
		fabric-networking-api-v1: Fabric Networking API (v1) 1.0.18+3ac43d9514
		fabric-networking-v0: Fabric Networking (v0) 0.3.5+b4f4f6cd14
		fabric-object-builder-api-v1: Fabric Object Builder API (v1) 1.10.13+3ac43d9514
		fabric-object-builders-v0: Fabric Object Builders (v0) 0.7.7+3ac43d9514
		fabric-particles-v1: Fabric Particles (v1) 0.2.9+526dc1ac14
		fabric-registry-sync-v0: Fabric Registry Sync (v0) 0.8.5+3ac43d9514
		fabric-renderer-api-v1: Fabric Renderer API (v1) 0.4.9+3ac43d9514
		fabric-renderer-indigo: Fabric Renderer - Indigo 0.4.12+3ac43d9514
		fabric-renderer-registries-v1: Fabric Renderer Registries (v1) 3.2.7+b4f4f6cd14
		fabric-rendering-data-attachment-v1: Fabric Rendering Data Attachment (v1) 0.3.3+d154e2c614
		fabric-rendering-fluids-v1: Fabric Rendering Fluids (v1) 0.1.18+3ac43d9514
		fabric-rendering-v0: Fabric Rendering (v0) 1.1.9+b4f4f6cd14
		fabric-rendering-v1: Fabric Rendering (v1) 1.10.3+6b21378a14
		fabric-resource-loader-v0: Fabric Resource Loader (v0) 0.4.11+3ac43d9514
		fabric-screen-api-v1: Fabric Screen API (v1) 1.0.7+3ac43d9514
		fabric-screen-handler-api-v1: Fabric Screen Handler API (v1) 1.1.11+3ac43d9514
		fabric-structure-api-v1: Fabric Structure API (v1) 2.0.8+295197a714
		fabric-tag-extensions-v0: Fabric Tag Extensions (v0) 1.2.5+3ac43d9514
		fabric-textures-v0: Fabric Textures (v0) 1.0.9+3ac43d9514
		fabric-tool-attribute-api-v1: Fabric Tool Attribute API (v1) 1.3.4+7de09f5514
		fabric-transfer-api-v1: Fabric Transfer API (v1) 1.5.4+b4f4f6cd14
		fabricloader: Fabric Loader 0.12.11
		flytre-lib-base: Flytre Lib - Base Module 1.3.0
		flytre-lib-compat: Flytre Lib - Compat Module 1.0.0
		flytre-lib-config: Flytre Lib - Config Module 1.1.0
		flytre-lib-event: Flytre Lib - Event Module 1.0.1
		flytre-lib-gui: Flytre Lib - GUI Module 1.0.0
		flytre-lib-storage: Flytre Lib - Storage Module 2.3.2
		flytre_lib: Flytre Lib 1.4.4
		iris: Iris 1.1.3
		java: OpenJDK 64-Bit Server VM 17
		kanos_config: Kanos Config 0.1.4+1.14.4-1.17.1
		kyrptconfig: Kyrpt Config 1.2.4-1.18
		lambdynlights: LambDynamicLights 2.1.0+1.17
		mcda: MC Dungeons Armors 1.8.6
		mcdw: MC Dungeons Weapons 3.6.0-1.18
		minecraft: Minecraft 1.18.1
		modmenu: Mod Menu 3.0.0
		more_gems: More Gems 1.3.50
		ninjaphenix_container_lib: NinjaPhenix's Container Library 1.2.5
		org_anarres_jcpp: jcpp 1.4.14
		org_aperlambda_lambdajcommon: lambdajcommon 1.8.1
		org_joml_joml: joml 1.10.2
		org_slf4j_slf4j-api: slf4j-api 1.7.12
		origins: Origins 1.3.1
		origins-classes: Origins: Classes 1.2.4
		pehkui: Pehkui 2.5.1+1.14.4-1.18
		playerabilitylib: Pal 1.3.0
		pride: Pride Lib 1.1.0+1.17
		pugh_tools: Pugh Tools 1.1.13
		rangers_haven: Ranger's Haven 2.3.1
		reach-entity-attributes: Reach Entity Attributes 2.1.1
		roughlyenoughitems: Roughly Enough Items 7.0.343
		sodium: Sodium 0.4.0-alpha5+build.9
		spruceui: SpruceUI 3.3.0+1.17
		treeaxe: The TreeAxe 1.1.24
		xaerominimap: Xaero's Minimap 21.22.6
		yigd: You're in Grave Danger 1.2.5
	Launched Version: fabric-loader-0.12.11-1.18.1
	Backend library: LWJGL version 3.2.2 build 10
	Backend API: NVIDIA GeForce GTX 1660 SUPER/PCIe/SSE2 GL version 3.2.0 NVIDIA 472.12, NVIDIA Corporation
	Window size: 1920x1080
	GL Caps: Using framebuffer using OpenGL 3.2
	GL debug messages: 
	Using VBOs: Yes
	Is Modded: Definitely; Client brand changed to 'fabric'; Server brand changed to 'fabric'
	Type: Integrated Server (map_client.txt)
	Graphics mode: fancy
	Resource Packs: Fabric Mods
	Current Language: English (US)
	CPU: 4x Intel(R) Core(TM) i3-8100 CPU @ 3.60GHz
	Server Running: true
	Player Count: 1 / 8; [class_3222['Magnus27k'/116, l='ServerLevel[New World]', x=-38.50, y=72.00, z=-24.50]]
	Data Packs: vanilla, Fabric Mods
