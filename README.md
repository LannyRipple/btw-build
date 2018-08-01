Helpers for building BTW client and server on new releases.

1. Eyeball bin/build-btw.  Change anything needed at the top of the
script.
2. Download and install any desired prereqs.  See share/Useful-urls.txt
   for what I think that involves.
3. Download latest BTW release and run bin/build-btw.
4. I like to start the server with

```
cd servers/btw-latest && screen -S mc-server -dm bash ./start
```

When you run Minecraft you'll want to edit the mc-patcher profile and
update the version to the BTW-\* you just built.
