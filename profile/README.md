![EPFL Center for Imaging logo](https://imaging.epfl.ch/resources/logo-for-gitlab.svg)
# 👋 Welcome!

Turn Python-based image processing workflows into **algorithms** that gain extra functionalities.

- [**Turn your algorithms into web servers**](https://imaging-server-kit.github.io/imaging-server-kit/sections/07_server.html) and run computations from [QuPath](https://github.com/Imaging-Server-Kit/qupath-extension-serverkit), [Napari](https://github.com/Imaging-Server-Kit/napari-serverkit), or [Python](./sections/08_python) via HTTP requests.

https://github.com/user-attachments/assets/36bda69d-996e-4240-9a53-7e76d9ea3894

- [**Generate dock widgets**](https://imaging-server-kit.github.io/imaging-server-kit/sections/01_algorithm.html) to run your algorithms interactively in Napari.

https://github.com/user-attachments/assets/1ff572f7-f159-4f5a-afd4-7a157de3d9f8

- Run your algorithms [**tile-by-tile**](https://imaging-server-kit.github.io/imaging-server-kit/sections/06_tiled.html) on the input data.

https://github.com/user-attachments/assets/47c2f734-5683-49d9-8aea-388c3a2bc16d

- [**Stream results**](https://imaging-server-kit.github.io/imaging-server-kit/sections/05_streams.html) to inspect them in real-time.

https://github.com/user-attachments/assets/a3f69a9f-fb68-4580-a804-6c57d5807b9a

## Getting started

The documentation is available on [this page](https://imaging-server-kit.github.io/imaging-server-kit/index.html).

## Supported image analysis tasks

| Task              | Examples                        | Napari | QuPath |
|-------------------|---------------------------------| ------ | ------ |
| Image segmentation | [CellPose](./examples/serverkit-cellpose/), [StarDist](./examples/serverkit-stardist/), [Instanseg](./examples/serverkit-instanseg/), [SAM-2](./examples/serverkit-sam2/), [Rembg](./examples/serverkit-rembg/), [CellPose4 (GPU)](./examples/serverkit-cellpose4_gpu/) | ✅ | ✅ |
| Points detection | [Spotiflow](./examples/serverkit-spotiflow/) | ✅ | ✅ |
| Boxes detection | [Ultralytics YOLO](./examples/serverkit-yolo/) | ✅ | ✅ |
| Vectors detection | [OrientationPy](./examples/serverkit-orientationpy/) | ✅ | ✅ |
| Image registration | [StackReg](./examples/serverkit-stackreg/), [Spam](./examples/serverkit-spam/) | ✅ |  |
| Image denoising | [Noise2Void](./examples/serverkit-n2v/) | ✅ |  |
| Paths detection | [SplineBox](./examples/serverkit-splinebox/) | ✅ |  |
| Tracking | [Trackpy](./examples/serverkit-trackpy/), [Trackastra](./examples/serverkit-trackastra/) | ✅ |  |
| Image generation | [Stable Diffusion](./examples/serverkit-stable-diffusion/) | ✅ |  |
| Image-to-text | [ResNet50](./examples/serverkit-resnet50/), [BLIP captioning](./examples/serverkit-blip-captioning/) | ✅ |  |
| Live updates | [Webcam stream](./examples/serverkit-webcam/) | ✅ |  |

## Roadmap

**November 2025**

The *Imaging Server Kit* is being actively developed! Here is what we're up to:

- [X] Improving robustness and user experience
- [ ] Developing the tiled inference concept
- [ ] Enhancing computations with gRPC
- [ ] Easy containerization and packaging
- [ ] Making a Fiji plugin

## Contributors

- Mallory Wittwer, EPFL Center for Imaging (mallory.wittwer@epfl.ch)
- Dr. Edward Andò, EPFL Center for Imaging
- Dr. Maud Barthélémy, EPFL Center for Imaging
- Dr. Florian Aymanns, EPFL Center for Imaging

## Acknowledgements

We acknowledge the [Personalized Health and Related Technologies (PHRT)](https://www.sfa-phrt.ch/) initiative for supporting this project.