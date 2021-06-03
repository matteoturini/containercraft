# Containercraft

Download your desired JAR in server.jar and set the variables PORT and RAM!

Example:

```bash
# Build the image
docker build --pull --rm -f "Dockerfile" -t containercraft:latest "."
# Run it!
docker run -e "RAM=1G" -e "PORT=25565" containercraft:latest "."
```

If you need Java 8 for Minecraft 1.8, get [NachoSpigot](https://github.com/CobbleSword/NachoSpigot)!

(or change the 16 in the Dockerfile to 8)
