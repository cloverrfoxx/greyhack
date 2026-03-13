# greyhackscripts
i no longer play grey hack, but so long as people find my scripts for the game useful i will keep this up, archival notice

collection of clovers's open source grey hack scripts

if you're a developer, check out the [foxlib](https://github.com/cloverrfoxx/foxlib-gh) repo for some useful libraries

## lunar

if you're here for lunar the files you will need IN ORDER are:
foxlib.src (compile to /root/Fox.so)
lunarcmd.src (compile to /root/lunarcmd)
lunar.src (compile as anything as long as those previous 2 are compiled properly)

do make sure that you modify your copy of lunar such that you don't accidentally wreck anything
(see lunar.src lines 42-56, 104-105, 133-139, 141-155, 157-174, 544-549)

## foxtrot

if you're here for foxtrot, um, i'm not sure i even remember how to set it up
foxtrot is my old hacktool-as-a-service doohickey and it kind of takes a lot to set up
and that setup isn't exactly feasible to do in recent versions of the game
(also some of its major features are broken)

so, sorry! can't help you with this one, i can tell you what you might need tho so you can figure something out:

a server to route through
a server to store user data on
a server to store user emails on
a server to store user exploit data + automating scans on
a crypto coin that exposes an api
to replace calls to BTC/Bytes api with the aforementioned crypto coin api
minifoxos.src
minifoxoscmds.src
foxlib.src
foxtrot.src
probably a custom src for the server backends that i don't seem to have anymore

## etc

if you're here for most anything else in here then those setups should be pretty easy, some might expect a /root/Fox.so (foxlib.src)
cloudsafe, sandboxy, and spark are services but iirc i made them rather simple to set up, you just might need to skim their code a little and make some changes
(spark might rely on a custom script i no longer have for moderator users to process file uploads)

## misc

if you've got questions or comments or nonsense come make it known on my [discord server](https://discord.gg/7QXz5JYZeX)

other projects i recommend!

- [Unclovered Lunarium](https://github.com/h4cktoria/unclovered-lunarium)
- [5hell](https://github.com/jhook777/5hell-for-Grey-Hack-the-Game)
- [Crowsploit](https://github.com/JessaTehCrow/crowsploit)
- [Unity](https://github.com/MachaCeleste/CelestialCorp-Unity)
- [Finko42's Scripts](https://github.com/Finko42/GreyHack)
