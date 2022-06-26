# Plotters Frame Buffer Example

This is a simple example project demonstrate how Plotters works with frame buffer devices. 
In our example, we use the [minifb](https://github.com/emoon/minifb) crates as the frame buffer implementation. 
You can also use any frame buffer devices, such as `/dev/fb0` etc.

This example also demonstrate how to use Plotters for realtime plot rendering.

This project is a simple simulation of an oscilloscope showing [Lissajous curve](https://en.wikipedia.org/wiki/Lissajous_curve). 

For more details about plotters, check the [main repository](https://github.com/plotters-rs/plotters)

![animation](https://plotters-rs.github.io/images/minifb-demo.gif)

To build and run the project:

```
cargo run
```
