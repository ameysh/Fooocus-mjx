# Fooocus-MJX

**Fooocus-MJX** is a personal and experimental fork of the original [Fooocus](https://github.com/lllyasviel/Fooocus) image generation tool. This fork focuses on enhancing compatibility and performance for AMD GPUs using [DirectML](https://github.com/microsoft/DirectML), along with several user interface and usability improvements.

> ⚠️ **Note**: This is not an official Fooocus release. It is intended for personal use and experimentation.

---

## About the Original Project

Fooocus is an image generating software (based on [Gradio](https://www.gradio.app/) <a href='https://github.com/gradio-app/gradio'><img src='https://img.shields.io/github/stars/gradio-app/gradio'></a>).

Fooocus presents a rethinking of image generator designs. The software is offline, open source, and free, while at the same time, similar to many online image generators like Midjourney, the manual tweaking is not needed, and users only need to focus on the prompts and images.

Read the full [original README](https://github.com/lllyasviel/Fooocus#readme) for in-depth details, installation instructions, model architecture, and more.

---

## Why This Fork?

This fork aims to refine DirectML integration for more stable and efficient execution on non-CUDA GPU systems.

---

## Overview of Key Modifications

Notable updates in this fork include, but are not limited to:

### AMD GPU Enhancements (via DirectML)
- Optimized memory handling for DirectML backends
- Improved performance and stability on AMD GPUs

### New Sampling Defaults
- Default sampler changed to `dpmpp_2m_sde` for better results with DirectML

### Additional Presets
- `Balanced` (45 steps)
- `High Speed` (25 steps)
- `Ultra Speed` (16 steps)

and some minor UI improvements.

---

## Project Structure

This fork preserves the core structure of Fooocus.

---

## Disclaimers

- This fork is experimental and provided **“as is”**, without any warranty, express or implied, including but not limited to merchantability or fitness for a particular purpose.  
- Use this software at your own risk. The maintainer is not liable for any damages or data loss resulting from its use.  
- This fork attempts to optimize performance for AMD GPUs using DirectML but may not function optimally on AMD or other hardware configurations.

---

## License

This project remains under the [GNU General Public License v3.0](LICENSE), in line with the original Fooocus repository.

---

## Credits

This fork builds upon [Fooocus](https://github.com/lllyasviel/Fooocus) by [lllyasviel](https://github.com/lllyasviel) and [contributors](https://github.com/lllyasviel/Fooocus/graphs/contributors). Many thanks to the upstream maintainers for their work.
