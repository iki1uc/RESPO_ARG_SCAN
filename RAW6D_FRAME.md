# RAW6D – Frame Layout Specification

{
  "frame": {
    "index": null,

    "pixel_block": {
      "format": "RGB/YUV",
      "data": "raw"
    },

    "depth_block": {
      "enabled": true,
      "data": "raw-depth"
    },

    "motion_block": {
      "enabled": true,
      "vectors": "mv-data"
    },

    "mystery_block": {
      "enabled": true,
      "pattern": "mystery-map"
    },

    "axes": {
      "in": null,
      "out": null
    },

    "timing": {
      "pts": null,
      "dts": null,
      "duration": null
    }
  }
}
