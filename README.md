

# Nbt Tooltips 2.0    <img src="https://camo.githubusercontent.com/49b29197e2b4b615ec3fc9719a7898ef399be5df19ff35d0a430f417ed51fa4e/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f6c616e6775616765732f746f702f4b6f70616d65642f526176656e2d62504c5553" alt="Youtube Badge"/>
  </a>

[![curseforge downloads](http://cf.way2muchnoise.eu/full_nbt-crafting_downloads.svg)](https://minecraft.curseforge.om/projects/nbt-crafting)
[![modrinth downloads](https://img.shields.io/badge/dynamic/json?color=5da545&label=modrinth&prefix=downloads%20&query=downloads&url=https://api.modrinth.com/api/v1/mod/18ztUZP5&style=flat&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAxMSAxMSIgd2lkdGg9IjE0LjY2NyIgaGVpZ2h0PSIxNC42NjciICB4bWxuczp2PSJodHRwczovL3ZlY3RhLmlvL25hbm8iPjxkZWZzPjxjbGlwUGF0aCBpZD0iQSI+PHBhdGggZD0iTTAgMGgxMXYxMUgweiIvPjwvY2xpcFBhdGg+PC9kZWZzPjxnIGNsaXAtcGF0aD0idXJsKCNBKSI+PHBhdGggZD0iTTEuMzA5IDcuODU3YTQuNjQgNC42NCAwIDAgMS0uNDYxLTEuMDYzSDBDLjU5MSA5LjIwNiAyLjc5NiAxMSA1LjQyMiAxMWMxLjk4MSAwIDMuNzIyLTEuMDIgNC43MTEtMi41NTZoMGwtLjc1LS4zNDVjLS44NTQgMS4yNjEtMi4zMSAyLjA5Mi0zLjk2MSAyLjA5MmE0Ljc4IDQuNzggMCAwIDEtMy4wMDUtMS4wNTVsMS44MDktMS40NzQuOTg0Ljg0NyAxLjkwNS0xLjAwM0w4LjE3NCA1LjgybC0uMzg0LS43ODYtMS4xMTYuNjM1LS41MTYuNjk0LS42MjYuMjM2LS44NzMtLjM4N2gwbC0uMjEzLS45MS4zNTUtLjU2Ljc4Ny0uMzcuODQ1LS45NTktLjcwMi0uNTEtMS44NzQuNzEzLTEuMzYyIDEuNjUxLjY0NSAxLjA5OC0xLjgzMSAxLjQ5MnptOS42MTQtMS40NEE1LjQ0IDUuNDQgMCAwIDAgMTEgNS41QzExIDIuNDY0IDguNTAxIDAgNS40MjIgMCAyLjc5NiAwIC41OTEgMS43OTQgMCA0LjIwNmguODQ4QzEuNDE5IDIuMjQ1IDMuMjUyLjgwOSA1LjQyMi44MDljMi42MjYgMCA0Ljc1OCAyLjEwMiA0Ljc1OCA0LjY5MSAwIC4xOS0uMDEyLjM3Ni0uMDM0LjU2bC43NzcuMzU3aDB6IiBmaWxsLXJ1bGU9ImV2ZW5vZGQiIGZpbGw9IiM1ZGE0MjYiLz48L2c+PC9zdmc+)](https://modrinth.com/mod/nbt-crafting)
[![latest maven release](https://img.shields.io/maven-metadata/v?label=latest%20maven%20release&metadataUrl=https%3A%2F%2Fmaven.siphalor.de%2Fde%2Fsiphalor%2Fnbtcrafting-1.15%2Fmaven-metadata.xml)](https://maven.siphalor.de/de/siphalor/nbtcrafting-1.15/)

![logo](images/logo_2.0_big.png?raw=true)

## About
A forge mod which allows you to see an items nbt.

Everything is kept nicely visualized in the vanilla gui.

This can be achieved through the reintroduced /nbt attribute. 

**You can find more information in the [wiki](https://mcwor.de/nbt-crafting/v2).**

## Examples

You can find a datapack with some examples here: [Example Datapack](https://github.com/Siphalor/nbt-craftisuites/7385455218/artifacts/300475995)

A sample of some of the nicely writen code in this mod.

```json
{
  "type": "crafting_shapeless",
  "ingredients": [
    {
      "item": "minecraft:diamond_sword",
      "data": {
        "require": {
          "Damage": 2
        }
      }
    }
  ],
  "result": {
    "item": "minecraft:wooden_sword",
    "data": {
      "Damage": 2
       "nbt = 34678"
    }
  }
}
```

## Extra
Due to some additions made with this mod the nbt might some times not work - yay!

## License
This mod is available under the Apache 2.0 License.



 
