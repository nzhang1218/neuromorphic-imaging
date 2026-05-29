# Supplementary videos

Four supplementary videos accompany the manuscript. They are stored using **[Git LFS](https://git-lfs.com)** because of their size — make sure Git LFS is installed before cloning so the actual `.mp4` files are pulled rather than text pointers:

```bash
git lfs install
git clone https://github.com/nzhang1218/neuromorphic-imaging.git
```

| File | Description |
|:--|:--|
| [`M1_MNIST.mp4`](M1_MNIST.mp4) | A randomly moving **MNIST digit** behind a solid silicone–SiO₂ phantom (transmission, OT ≈ 3.3). Shows the raw DVS spikes, ground-truth position, and the SNN tracking and reconstruction evolving over time steps. |
| [`M2_KMNIST.mp4`](M2_KMNIST.mp4) | **Kanji (KMNIST) characters** as spatially fixed but time-varying-contrast targets imaged in **reflection** (double-pass) geometry through the solid phantom (OT ≈ 6.6). |
| [`M3_Birds.mp4`](M3_Birds.mp4) | **Bird silhouettes** executing naturalistic flight trajectories, imaged in transmission through a **turbid-water** tank (diluted intralipid, OT ≈ 3.5). |
| [`M4_Fog_Chamber.mp4`](M4_Fog_Chamber.mp4) | The **dynamic fog chamber**: how object visibility changes as fog builds from thin to thick, with labeled objects at increasing distances from the chamber front. |

> If you cloned without Git LFS installed, run `git lfs install && git lfs pull` to fetch the videos.
