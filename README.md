# servo-paint

Narrow Servo 0.8 paint crate patches used by VisualBits runtime integrations.

The source tracks Servo's `v0.8.0` release. `SERVO_WEBRENDER_LOW_MEMORY=1`
selects smaller, demand-grown WebRender GPU caches for embedded single-viewport
workloads. The default remains byte-for-byte equivalent to upstream behavior.
