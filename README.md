### Autodl Irssi

Container for the autodl irssi plugin.

## Useage

```
docker run \
	-it \
	--name autodl-irssi \
	-v </path/to/watch/directory>:/home/user/watch:rw \
	-v </path/to/autodl/directory>:/home/user/.autodl:rw \
	zmiguel/autodl-irssi
```
