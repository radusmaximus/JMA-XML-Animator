# Usage

The general workflow is:

1. Load a jaw-motion XML file exported from a supported workflow.
2. Select the desired movement.
3. Select the mandibular object in Blender.
4. Use the add-on to reconstruct the rigid-body motion and set keyframes.
5. Inspect the reconstructed animation in Blender/Blender4Dental.
6. Use threshold-frame tools for frame-level inspection and quantitative analysis.

## Supported workflow concepts

The add-on was developed for frame-level analysis of XML motion exports from Zebris JMA and Medit i700 workflows. It supports:

- XML import
- movement selection
- SVD-based rigid-body reconstruction
- timeline keyframe generation
- threshold-based frame selection
- displacement component analysis
- occlusal contact-area computation

## Clinical caution

The generated outputs require expert interpretation. The add-on does not independently validate the absolute accuracy of any acquisition hardware and should not be used as a standalone clinical decision-support system.
