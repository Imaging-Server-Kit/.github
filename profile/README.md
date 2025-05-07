![EPFL Center for Imaging logo](https://imaging.epfl.ch/resources/logo-for-gitlab.svg)
# 👋 Welcome!

The **Imaging Server Kit** is an open-source Python package for deploying image analysis algorithms as web services.

- Run computations remotely, while client applications remain focused on visualization.
- Connect to an algorithm server and run algorithms from [QuPath](https://github.com/Imaging-Server-Kit/qupath-extension-serverkit), [Napari](https://github.com/Imaging-Server-Kit/napari-serverkit), and Python.
- Easily [create algorithm servers](https://imaging-server-kit.github.io/imaging-server-kit/sections/algorithm_server.html) for Python-based algorithms

![serverkit-schema](./serverkit-schema.png)

## Getting started

The documentation is available on [this page](https://imaging-server-kit.github.io/imaging-server-kit).

## Supported image analysis tasks

| Task              | Examples                        | Napari | QuPath |
|-------------------|---------------------------------| ------ | ------ |
| Segmentation     | [StarDist](https://github.com/Imaging-Server-Kit/imaging-server-kit/tree/main/examples/servers/serverkit-stardist), [CellPose](https://github.com/Imaging-Server-Kit/imaging-server-kit/tree/main/examples/servers/serverkit-cellpose), [Rembg](https://github.com/Imaging-Server-Kit/imaging-server-kit/tree/main/examples/servers/serverkit-rembg), [SAM-2](https://github.com/Imaging-Server-Kit/extra-examples/tree/main/examples/serverkit-sam2), [InstanSeg](https://github.com/Imaging-Server-Kit/extra-examples/tree/main/examples/serverkit-instanseg)               | ✅ | ✅ |
| Object detection | [Spotiflow](https://github.com/Imaging-Server-Kit/extra-examples/tree/main/examples/serverkit-spotiflow), [LoG detector](https://github.com/Imaging-Server-Kit/imaging-server-kit/tree/main/examples/servers/serverkit-skimage-log)    | ✅ | ✅ |
| Vector fields    | [Orientationpy](https://github.com/Imaging-Server-Kit/imaging-server-kit/tree/main/examples/servers/serverkit-orientationpy)                   | ✅ | ✅ |
| Object tracking  | [Trackpy](https://github.com/Imaging-Server-Kit/imaging-server-kit/tree/main/examples/servers/serverkit-trackpy), [Trackastra]()         | ✅ |  |
| Image-to-Image   | [SPAM](https://github.com/Imaging-Server-Kit/extra-examples/tree/main/examples/serverkit-spam), [Noise2Void](https://github.com/Imaging-Server-Kit/extra-examples/tree/main/examples/serverkit-n2v)         | ✅ |  |
| Text-to-Image    | [Stable Diffusion](https://github.com/Imaging-Server-Kit/extra-examples/tree/main/examples/serverkit-stable-diffusion)         | ✅ |  |
| Image-to-Text    | [Image captioning](https://github.com/Imaging-Server-Kit/extra-examples/tree/main/examples/serverkit-blip-captioning)         | ✅ |  |
| Classification   | [ResNet50](https://github.com/Imaging-Server-Kit/extra-examples/tree/main/examples/serverkit-resnet50)         | ✅ |  |

## Roadmap

**April 2025**

The *Imaging Server Kit* is under construction! Here is what we're up to:

- [X] Make the `/info` route look nice
- [ ] Handle streaming/tiling for processing whole-slide images
- [ ] Add a sample image button in the QuPath extension
- [ ] Add a server-side timeout to the `/process` endpoint
- [ ] Make a Fiji plugin

## Contributors

- Mallory Wittwer, EPFL Center for Imaging (mallory.wittwer@epfl.ch)
- Edward Andò, EPFL Center for Imaging
- Maud Barthélémy, EPFL Center for Imaging
- Florian Aymanns, EPFL Center for Imaging

## Acknowledgements

We acknowledge the [Personalized Health and Related Technologies (PHRT)](https://www.sfa-phrt.ch/) initiative for supporting this project.