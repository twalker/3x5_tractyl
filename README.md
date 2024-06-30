# 3x5_tractyl

A 3x5 Dactyl keyboard with a trackball on the top left.

# Parts list

- [PMW3389 Motion Sensor](https://www.tindie.com/products/citizenjoe/pmw3389-motion-sensor)
- [Elite-C](https://keeb.io/products/elite-c-low-profile-version-usb-c-pro-micro-replacement-atmega32u4)
- [Cosmos keyboard configurator](https://ryanis.cool/cosmos/beta#cf:ChYIBBAFWAAYBSAEKNcBMM0BUAJAAEgBEhAIwgMYxgogowU4AChaMIgOMhAIAxAAOAAYACAAKMgBMMgB)
  v3: https://ryanis.cool/cosmos/beta#cf:ChYIBBAFWAAYACAFKM0BMMMBUABAAEgBEhAIwgMYxgogowU4AChaMIgOMhAIAxAAOAAYACAAKMgBMMgBQlMIA+ABAXgG2AEBEAFIAEgASABIAEgASABIAGAAaABwARgBIAEoAZgB9AOoAegHoAHIAbABAJABiA64AQCAAQAwADgoWAGIAQHAAQDIAdgE0AGEBw==
  v4: https://ryanis.cool/cosmos/beta#cf:ChYIBBAFWAAYACAFKNcBMM0BUABAAEgBEhAIwgMYxgogowU4AChaMIgOMhAIAxAAOAAYACAAKMgBMMgBQlQIA+ABAXgG2AEBEAFIAEgASABIAEgASABIAGAAaABwARgBIAEoAZgB2ASoAegHoAGQA7AByAGQAYQHuAEAgAEAMAA4KFgBiAEBwAEAyAHYBNABhAc=
  https://ryanis.cool/cosmos/beta#cf:ChYIBBAFWAAYBSAEKMMBMLkBUAJAAEgBEhAIwgMYiA4gowU4AChaMIgOMhAIAxAAOAAYACAAKMgBMMgBUhkwAAiAUBCAkIb4BBiA3ofAByCAeCjQxsECQlMIA+ABAngG2AEBEAFIAEgASABIAEgASABIAGAAaABwARgBIAEoAZgB2ASoAegHoAHIAbABAJABhAe4AQCAAQAwADgeWAGIAQHAAQDIAdgE0AGEBw==
  Low pro, adjusted stagger, and key spacing:
  https://ryanis.cool/cosmos/beta#cf:ChYIBBAFWAAYBSAEKLkBMK8BUAJAAEgBEhAIwgMYiA4gowU4AChaMIgOMg8IAzgAGAAgiA4ouQEwuQFSGDAACIBQEIDovQIYgN6HwAcggHgo0MbBAkJRCAPgAQJ4BtgBARABSABIAEgASABIAEgAYABoAHABGAEgASgAmAH0A6gB6AegAcgBsAEAkAGEB7gBAIABADAAOB5YAYgBAcABAMgB2ATQAYQH
  Lowpro v2:
  https://ryanis.cool/cosmos/beta#cf:ChYIBBAFWAAYBSAEKMMBMLkBUAJAAEgBEhAIwgMYiA4gowU4AChaMIgOMhAIAxAAOAAYACAAKMMBMLkBUhkwAAiAUBCAkIb4BBiA3ofAByCAeCjQxsECQlMIA+ABAngG2AEBEAFIAEgASABIAEgASABIAGAAaABwARgBIAEoAZgB2ASoAegHoAHIAbABAJABhAe4AQCAASgwADgoWAGIAQHAAQDIAdgE0AGEBw==
  v2 no web:

https://ryanis.cool/cosmos/beta#cf:ChYIBBAFWAAYBSAEKMMBMLkBUAJAAEgBEhAIwgMYiA4gowU4AChaMIgOMhAIAxAAOAAYACAAKMMBMLkBUhkwAAiAUBCAkIb4BBiA3ofAByCAeCjQxsECQlMIA+ABAngG2AEBEAFIAEgASABIAEgASABIAGAAaABwARgBIAEoAZgB2ASoAegHoAHIAbABAJABhAe4AQCAAQAwADgoWAGIAQHAAQDIAdgE0AGEBw==

Updated wrist wrests:
https://ryanis.cool/cosmos/beta#cf:ChYIBBAFWAAYBSAEKMMBMLkBUAJAAEgBEhAIwgMYiA4gowU4AChaMIgOMhAIAxAAOAAYACAAKMMBMLkBUhkwAAiAUBCAkIb4BBiA3ofAByCAeCjQxsECQlQIA+ABAngG2AEBEAFIAEgASABIAEgASABIAGAAaABwARgBIAEoAZgBoAaoAcwIoAHIAbABAJABwgO4AcIDgAEAMAA4KFgBiAEBwAEAyAHYBNABhAc=

# Dactyl build guides

- https://klotzandrew.com/blog/building-a-dactyl-keyboard-from-scratch
- https://www.reddit.com/r/olkb/comments/c8hjn1/help_me_correctly_programming_my_new_born_dactyl/
- https://github.com/aleung/mini-thumb-dactyl-keyboard
- https://github.com/dereknheiley/compactyl/tree/master
- https://github.com/ArtiomSu/qmk_firmware/tree/artiom_dactyl/keyboards/artiomsu_dactyl
- https://medium.com/swlh/complete-idiot-guide-for-building-a-dactyl-manuform-keyboard-53454845b065
- https://github.com/noahprince22/tractyl-manuform-keyboard

## Issues

- Could not configure dactyl generator with trackball holder. No response to github issue.
- No model for a 38mm trackball. Needed to model a trackball holder in Fusion 360.
- Diode in the wrong direction.
- 3-4 Switch wires disconnected.
- Trackball sensor too far from trackball to register movement.
- Case model had corrupted geometry on thumb cluster bottom.
- Case printing had layer shifts.
- MCU holder was too tight.
- Trackball wiring misconfigured (B2 and B3 in wrong order).
