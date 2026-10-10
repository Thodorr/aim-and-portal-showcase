# Aim and Portal

![Unity](https://img.shields.io/badge/Unity-6000.3.14f1-black?logo=unity)
![C%23](https://img.shields.io/badge/C%23-512BD4?logo=csharp&logoColor=white)
![XR](https://img.shields.io/badge/XR-Meta%20Quest%203-0467DF?logo=meta&logoColor=white)
![Status](https://img.shields.io/badge/Status-Playable%20Prototype-success)

**Aim and Portal** is a Unity VR prototype in which a player places free-flying portals, aims through portal connections and retrieves distant objects without leaving a central hub world.

It was created as a three-person university project. Its gameplay turns portal-based interaction into a series of small spatial tasks: observe a target world through a gate, place and adjust a portal, reach through it and bring a quest object back to the hub.

## Showcase video

[Watch the interaction case study](media/showcase.mp4)

The video follows one quest object from portal placement to retrieval. It focuses on the interaction work rather than presenting a general gameplay trailer.

## Interaction concept

The player starts in a hub world with gates into three separate environments: an office, a space environment and a dungeon. Each gate shows a live view into its target world.

Using the portal gun, the player can aim, fire and stop a portal at any position in the scene. A placed portal can then be rotated and moved for finer alignment. This makes it possible to look around obstacles, aim through existing connections and reach distant objects through the portal surface.

Quest objects are retrieved through portal interactions and placed on matching sockets in the hub. The prototype uses this loop to demonstrate remote interaction through and with portals.

## Technical context

- Unity 6000.3.14f1
- C#
- OpenXR
- XR Interaction Toolkit 3.3.1
- Visual Effect Graph
- Standalone build for Meta Quest 3

## Project report

[Read the public project report in German](docs/Projektbericht.pdf)

The report documents the overall group project, including the interaction concept, technical architecture, requirements and the informal usability test.

## Repository scope

This repository intentionally contains showcase material only. The full Unity project and its source files are not published because the project was developed collaboratively and includes licensed Synty assets as well as a THM-provided portal framework.

## Team

Stefan Ganswint, Tom Kertels and Rico Marco Libesch
