# aetheria-models

3D creature models (GLB) for the Aetheria game, served with GitHub Pages.

- `models/creature-NNN.glb`: one model per AetherDex number, generated locally with
  [Hunyuan3D-2](https://github.com/Tencent-Hunyuan/Hunyuan3D-2) from renders of the game's own designs.
  Textures are WebP and geometry is quantized (KHR_mesh_quantization), so three.js's GLTFLoader reads them directly.
- `models/manifest.json`: which models exist, plus a version stamp for cache-busting.

Generated with Tencent Hunyuan3D-2 under the Tencent Hunyuan 3D 2.0 Community License.
