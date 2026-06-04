---
license: cc-by-4.0
pretty_name: Habitat YCB Objects Dataset
---

![YCB](https://www.ycbbenchmarks.com/wp-content/uploads/2015/08/cropped-banner4.jpg)

# Habitat YCB Objects Dataset
Post-processed simulation assets for use in [habitat-sim](https://github.com/facebookresearch/habitat-sim).

Original sourced from [Official YCB Dataset](https://www.ycbbenchmarks.com/).

> YCB Object and Model Set is designed for facilitating benchmarking in robotic manipulation... The set is associated with a [model database](http://www.ycbbenchmarks.com/object-models/) which provides mesh models and high-resolution RGB-D scans of the objects for easy incorporation into manipulation and planning software platforms.

## Contents

```
├── configs
|   ├── *.object_config.json
├── meshes
|   ├── */*.glb      - BASIS compressed and optimized for simulation 
|   ├── */*.glb.orig - uncompressed raw assets
├── collison_meshes
|   ├── *.glb        - convex decomposition collision proxies
├── ycb.scene_dataset_config.json
```

- ycb.scene_dataset_config.json - SceneDataset file for easy import of the full dataset in habitat-sim. See [the docs](https://aihabitat.org/docs/habitat-sim/attributesJSON.html) for details.
