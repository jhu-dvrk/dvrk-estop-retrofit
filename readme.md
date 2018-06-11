# dVRK E-stop Retrofit Kit

This retrofit kit converts the 4-pin and 5-pin E-stop connectors on old dVRK boxes to the newer 4-and-5-pin connectors.

![](docs/20180611_0010.jpg)

![](docs/20180611_0012.jpg)

**Why do I want the new 4-and-5-pin connectors?** The new connectors allow you to use the [JHU-style configurable serial connection](), so you can quickly reconfigure the dVRK into two or more systems (e.g. one workstation for the MTMs, and another workstation for the PSMs) for different research needs. 

![](docs/20180611_0001.jpg)
dVRK with retrofit applied at JHU. Top three boxes are connected to one safety chain, and the bottom one is connected to another. PSM3 is used as an one-arm-only dVRK.

# Which "type" do I need?

Look at the back side (connector side) of the dVRK boxes. If you only see a green four-pin safety chain connector, you need `type iv`. If you only see a green five-pin connector, you need `type v`.

The "types" are silkscreened on the retrofit kit PCB. `type iv` has a four-pin plug. `type v` has a five-pin plug.

![](docs/20180611_0007.jpg)
This is a four-pin green connector. You need `type iv`.

![](docs/20180611_0002.jpg)
This is a five-pin green connector. You need `type v`.

![](docs/20180611_0009.jpg)
If your boxes have these four-pin and five-pin connectors, you have the latest connector and you do not need this retrofit kit.

# How to use

You should receive an assembled PCB with one screw terminal plug connector for each box. You will reuse the screw terminal plug connectors and the e-stop button that came with your boxes. The retrofit process at JHU took about half an hour for six boxes. 

## Making the cables

Please use the following diagram as reference to make the cables.

![](docs/dvrk-estop.png)

You can use any 3-wire (or more) cables to make the daisy-chain cables. The cable normally carries no more than a few milliamps of current. However, in fault conditions such as shorting caused by broken insulation, the 12V pin can provide enough energy to start a fire. Please use caution and good practices when wiring. We recommend using stranded wires and wire ferrules.

## Plugging it in

If you are using the `type v`, you can directly plug the PCB assembly into the green connector behind the box, then plug the e-stop, cables, and termination plugs into the PCB assembly. 

If you are using the `type iv`, you have to make sure all boxes are sharing the same ground. Usually they are because their ground pin in the IEC connectors are connected at the power strip. If the 


