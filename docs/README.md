# Wokwi sn54ls51 Chip

This is a custom chip for [Wokwi](https://wokwi.com/). It implements the sn54ls51 IC.

## Usage

To use this chip in your project, include it as a dependency in your `diagram.json` file:

```json
  "dependencies": {
    "chip-sn54ls51": "github:wokwi-custom-chips/sn54ls51@0.1.0"
  }
```

Then, add the chip to your circuit by adding a `chip-sn54ls51` item to the `parts` section of diagram.json:

```json
  "parts": {
    ...,
    { "type": "chip-sn54ls51", "id": "chip1" }
  },
```

For a complete example, see [The sn54ls51 chip test project](https://wokwi.com/projects/399519875293538305).
