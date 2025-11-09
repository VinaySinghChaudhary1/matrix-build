# Multi-Platform Matrix Build (48115ed)

This repository demonstrates a GitHub Actions **matrix build** workflow running on multiple OS and Node.js versions.

Each job:
- Runs in **parallel** across multiple platforms.
- Generates a **non-empty artifact** with build info.
- Uploads it with prefix `build-48115ed-*`.
- Includes a step identifier `matrix-48115ed`.

## Example Matrix
| OS | Node.js Version |
|----|-----------------|
| ubuntu-latest | 16 |
| windows-latest | 18 |
| macos-latest | 20 |

📧 **Email:** 22f2001153@ds.study.iitm.ac.in  
👤 **Maintainer:** Vinay Singh Chaudhary  
📂 **Repository:** [matrix-build](https://github.com/VinaySinghChaudhary1/matrix-build)
