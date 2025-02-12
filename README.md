> **🚧 Development Notice**
> 
> This project is currently under active development. Documentation and features are incomplete and subject to change. Check back regularly for updates!

# HeinSight Core

HeinSight is an open-source project that leverages the Hailo AI processor on Raspberry Pi 5 for advanced computer vision applications. Built on top of the Hailo platform, it provides a streamlined approach to implementing AI-powered vision solutions.

## Overview

This repository contains the core functionality for HeinSight, providing:
- Simplified pipeline management for AI inference
- Utilities for object detection and image processing
- Easy integration with Hailo AI processors
- Flexible model management

## Installation

1. Clone the repository:
```bash
git clone https://github.com/GDSwain/HeinSight-Core.git
cd HeinSight-Core
```

2. Set up your environment (instructions for the setup process)

3. Download required models:
```bash
./download_resources.sh
```

## Model Management

### Demo Model
This repository includes a demo .hef model for proof of concept testing.

### Additional Models
- Run `./download_resources.sh` to download standard models from Hailo's model zoo
- Custom .hef files should be placed in the `resources` directory after installation
- For a collection of compatible models, check out our [HeinSight-Models](link-to-future-repo) repository

## Contributing

Contributions are welcome! Feel free to:
- Fork the repository
- Create feature branches
- Submit pull requests
- Report issues
- Suggest improvements

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

This project builds upon the excellent work of:
- [Hailo Technologies](https://hailo.ai/)
- (Any other acknowledgments????)

## Disclaimer

This software is provided "as is" and "with all faults." The developers make no representations or warranties of any kind concerning the safety, suitability, lack of viruses, inaccuracies, typographical errors, or other harmful components of this software. There are inherent dangers in the use of any software, and you are solely responsible for determining whether this software is compatible with your equipment and other software installed on your equipment. You are also solely responsible for the protection of your equipment and backup of your data, and the developers will not be liable for any damages you may suffer in connection with using, modifying, or distributing this software.

---
Built with ❤️ by the good people at Hein Labs
