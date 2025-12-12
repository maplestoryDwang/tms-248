
## README_en.md 文件内容：


# MapleStory TMS Server Project

## Language Selection
* [繁體中文](README_zh-TW.md)
* [简体中文](../README.md)

---

## Description
### Acknowledgements
Thanks to all friends who are willing to share and love Maplestory. Original repository address: https://github.com/rage123450/TMS246-Server

### Project Description
1. TMS-248.1 server version, found online two years ago
2. TMS server based on swordie architecture
3. JDK 17 required
4. Database: MariaDB
5. Startup method can refer to other TMS server startup methods

### Why This Project
1. Although the TMS245 MoSen server is excellent, I prefer the swordie project architecture more. Refactoring the project is a major task. I happened to find this project and discovered it can start normally after testing.
2. Previously researching GMS214, although it's also excellent, the game resolution gave me headaches. It looks very uncomfortable on 4K screens, and I didn't want to modify memory through HOOK, so I wanted to choose a higher version for fixing.
3. Currently, there are many excellent server versions for reference. Static debugging alone is sufficient for fixing requirements.

### Additional Notes
1. Pay attention to the storage path and file names of dat data, otherwise crashes may occur easily
2. The project lacks many scripts that need to be fixed.
3. Currently focusing on GMS214. Fixed features will be merged here if applicable to this project.

### Quick Start
1. Ensure JDK 17 or higher is installed
2. Install and configure MariaDB database
3. Import required database files
4. Configure server settings
5. Start the server

### System Requirements
- JDK 17+
- MariaDB 10.3+
- Minimum 4GB RAM
- Windows operating system
