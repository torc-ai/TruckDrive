<div align="center">

# TruckDrive: Long-Range Autonomous Highway Driving Dataset

**Torc Robotics**

[![Paper](https://img.shields.io/badge/Paper-PDF-2ea44f?style=flat-square)](https://arxiv.org/pdf/2603.02413)
[![arXiv](https://img.shields.io/badge/arXiv-2603.02413-b31b1b?style=flat-square)](https://arxiv.org/abs/2603.02413)
[![Project Page](https://img.shields.io/badge/Project-Page-f0ad4e?style=flat-square)](http://torc-ai.github.io/TruckDrive)
[![Devkit](https://img.shields.io/badge/Code-Devkit-0366d6?style=flat-square)](https://github.com/torc-ai/TruckDrive)
[![Data](https://img.shields.io/badge/Data-Access_Portal-6f42c1?style=flat-square)](https://d3ehgyu1hepsur.cloudfront.net/?prefix=)

**Filippo Ghilotti, Edoardo Palladin, Samuel Brucker, Adam Sigal, Mario Bijelic, Felix Heide**

</div>

<div align="center">
TruckDrive is a long-range autonomous highway driving dataset designed for heavy-truck safety, perception, prediction, and planning research. It targets high-speed highway operation, where reliable scene understanding hundreds of meters ahead is required for anticipatory planning and safe braking.

This repository hosts the **TruckDrive project website** together with release documentation.
</div>

---
## License

This Dataset is released under the **Torc Robotics Non-Commercial License v1.0**.

> **Non-Commercial Use** — Free to use under the terms of the
> Torc Robotics Non-Commercial License v1.0.
> Full text: [`LICENSE-NONCOMMERCIAL.txt`](./LICENSE-NONCOMMERCIAL.txt)

> **Commercial Use** — Requires a separate written license agreement.
> See [`LICENSE-COMMERCIAL.txt`](./LICENSE-COMMERCIAL.txt) or contact
> licensing@torc.ai.

Read [`COMMERCIAL-USE-POLICY.txt`](./COMMERCIAL-USE-POLICY.txt) for a
plain-language guide to determining which tier applies to You. If You
are still uncertain, contact licensing@torc.ai before
proceeding.

---

## Quick Reference

| I am...                                   | My use is...   | License needed        |
| ----------------------------------------- | -------------- | --------------------- |
| A PhD student publishing a paper          | Non-Commercial | None beyond this repo |
| A government researcher                   | Non-Commercial | None beyond this repo |
| An AV company doing internal R&D          | Commercial     | Contact us            |
| Training a model for a commercial product | Commercial     | Contact us            |
| A consultant working for an AV company    | Commercial     | Contact us            |
| A hobbyist learning computer vision       | Non-Commercial | None beyond this repo |
| Anyone benchmarking models for a paper | Non-Commercial | None beyond this repo |
| Unsure                                    | Unknown        | Contact us first      |

---

## Highlights

- **475k** synchronized multimodal samples
- **165k** densely annotated frames
- up to **1,000 m** for 2D benchmark annotations
- up to **400 m** for 3D benchmark annotations
- **7** long-range FMCW LiDARs, **3** short-range LiDARs, **10** 4D radars, and **11-15** cameras
- supports perception, tracking, depth estimation, prediction, planning, and end-to-end driving

## Dataset Overview

TruckDrive targets long-range, highway-scale autonomous driving for semi-trucks and other heavy commercial vehicles. It is designed to stress perception and planning systems beyond the short-range assumptions common in urban autonomous-driving benchmarks.

| Item                           | Paper-reported description                        |
| ------------------------------ | ------------------------------------------------- |
| Domain                         | Long-range highway and commercial-vehicle driving |
| Platform                       | Semi-truck-mounted multimodal sensor suite        |
| Synchronized samples           | **475k**                                          |
| Densely annotated frames       | **165k**                                          |
| Unlabeled synchronized samples | **310k**                                          |
| Sequences                      | **3,828** sequences recorded over 2 years         |
| Sequence duration              | **15-25 seconds**                                 |
| Average ego trajectory         | **500 m** per sequence                            |
| 2D annotation range            | Up to **1,000 m**                                 |
| 3D annotation range            | Up to **400 m**                                   |
| Primary operating regime       | Highway-speed, long-range truck autonomy          |

**Collection geography**: Texas, New Mexico, Virginia, North Carolina, Tennessee, Arkansas, West Virginia, and Arizona (United States only; excludes Illinois and California)

---

## Data Content

This Dataset consists of annotated autonomous vehicle driving data collected on public roads in the United States, excluding Illinois and California, with a primary focus on highway driving, together with related extra-urban and urban segments. The dataset is a long-range, multimodal driving dataset for autonomous highway driving, with a focus on heavy-vehicle operation, and contains synchronized camera, LiDAR, radar, and localization data. Raw sensor streams are not included in this release.

You may not use any data in this Dataset to query motor vehicle records databases or attempt to identify any individual, vehicle owner, registrant, operator, or passenger. See LICENSE-NONCOMMERCIAL.txt Section 4(c) for the full restriction.

You are solely responsible for compliance with all applicable federal, state, and local laws governing your use of the Dataset. See NOTICE.txt for further details.

---

## Citation

```bibtex
@inproceedings{ghilotti2026truckdrive,
  title     = {TruckDrive: Long-Range Autonomous Highway Driving Dataset},
  author    = {Ghilotti, Filippo and Palladin, Edoardo and Brucker, Samuel and Sigal, Adam and Bijelic, Mario and Heide, Felix},
  booktitle = {Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},
  year      = {2026}
}
```