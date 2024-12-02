The RLBot framework support the Hoops game mode. This page contains useful values specifically about Hoops.

To make RLBot start a Hoops game you have to set the following values in `rlbot.cfg`:

```
game_mode = Hoops
game_map = Hoops_DunkHouse
```

## Arena

Hoops is always played on the maps Dunk House or The Block. The dimensions for the arena are:

- Floor: z=0.0
- Side wall: x=2966.67
- Back wall: y=3581.0
- Ceiling: z=1820.0

## Goals

In Hoops the goals are two rings. The rings are placed ??? uu above the ground. Their radius is 753 uu but they are connected to the wall with straight lines.

Center of goals: y=2936.0
Distance from back wall: y=2286.0
Goal height: z=350.0

## Boost Pads

Locations of all boost pads:

```
[-2176.0, -2944.0, 8.0] (0)
[2176.0, -2944.0, 8.0] (1)
[0.0, -2816.0, 0.0] (2)
[-1280.0, -2304.0, 0.0] (3)
[1280.0, -2304.0, 0.0] (4)
[-1536.0, -1024.0, 0.0] (5)
[1536.0, -1024.0, 0.0] (6)
[-512.0, -512.0, 0.0] (7)
[512.0, -512.0, 0.0] (8)
[-2432.0, 0.0, 8.0] (9)
[2432.0, 0.0, 8.0] (10)
[-512.0, 512.0, 0.0] (11)
[512.0, 512.0, 0.0] (12)
[-1536.0, 1024.0, 0.0] (13)
[1536.0, 1024.0, 0.0] (14)
[-1280.0, 2304.0, -0.0] (15)
[1280.0, 2304.0, 0.0] (16)
[0.0, 2816.0, 0.0] (17)
[-2176.0, 2944.0, 8.0] (18)
[2175.99, 2944.0, 8.0] (19)
```

## Ball

The radius of the ball is 96.38 uu. But other than that, the physics of the ball is similar to soccer.

## Spawning

| Kickoff         | Blue                                   | Orange                                |
|-----------------|----------------------------------------|---------------------------------------|
| Right corner    | loc: (-1536.0, -3072.0), yaw: 0.25 pi  | loc: (1536.0, 3072.0), yaw: -0.75 pi  |
| Left corner     | loc: (1536.0, -3072.0), yaw: 0.75 pi   | loc: (-1536.0, 3072.0), yaw: -0.25 pi |
| Back right      | loc: (-256.0, -2816.0), yaw: 0.5 pi    | loc: (256.0, 2816.0), yaw: -0.5 pi    |
| Back left       | loc: (256.0, -2816.0), yaw: 0.5 pi     | loc: (-256.0, 2816.0), yaw: -0.5 pi   |
| Far back center | loc: (0.0, -3200.0), yaw: 0.5 pi       | loc: (0.0, 3200.0), yaw: -0.5 pi      |

| Demolished      | Blue                                   | Orange                                |
|-----------------|----------------------------------------|---------------------------------------|
| Right corner    | loc: (-1920.0, -3071.8), yaw: 0.5 pi   | loc: (1920.0, 3071.8), yaw: -0.5 pi   |
| Left corner     | loc: (1920.0, -3071.8), yaw: 0.5 pi    | loc: (-1920.0, 3071.8), yaw: -0.5 pi  |
