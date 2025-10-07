# PrenivApp Downloader Console (Windows)

A small, fast console tool to download media from popular platforms with automatic backup endpoint support for maximum reliability.

## Supported Platforms
- **TikTok** - Videos and images
- **Facebook** - Videos, photos, and reels
- **Instagram** - Posts, reels, and stories
- **Twitter/X** - Videos and images
- **Spotify** - Audio tracks
- **Apple Music** - Audio tracks
- **Douyin** - Videos
- **MediaFire** - Files
- **YouTube** - MP3 audio (320kbps) and MP4 video (multiple qualities)
- **AIO DL** - All in One Downloader Support (Tiktok, Instagram, Facebook, Capcut, Douyin, Spotify, Twitter)

## Download
- Pick the file that matches your PC:
  - **win-x64**: Most Windows 10/11 PCs (Intel/AMD)
  - **win-arm64**: ARM-based Windows devices (Surface/Qualcomm)
- No installation required - self-contained executable with Native AOT compilation.

## Installation
1. Download the appropriate version for your system
2. Extract the file to your preferred location
3. No additional installation needed!

## Run
Double-click the EXE, or start from PowerShell/CMD:
```powershell
# Example
cd "C:\Path\To\App\"
."\PrenivApp Downloader Console.exe"
```

## Usage

### Basic Commands
- **Paste URL + Enter**: Download media from the URL
- **path [folder]**: Change download location
  ```
  path C:\Users\You\Downloads\Out
  path "D:\Media Out"
  ```
- **help**: Show available commands
- **exit**: Close the application

### Example Session
```
prenivapp » https://www.tiktok.com/@user/video/12345

prenivapp » path "D:\Media\Out"
Output folder set to: D:\Media\Out

prenivapp » exit
```

### Download Experience
- Real-time progress bar with percentage, size, and speed
- Files named with timestamp: `name_yyyyMMdd_HHmmss_random6.ext`
- Default folder: `%USERPROFILE%\Downloads\PrenivApp` (customizable)
- 35 MB file size limit for safety

## Troubleshooting

### Common Issues
- **SmartScreen warning**: Click "More info" → "Run anyway" (Windows security for unsigned apps)
- **"Enter a valid URL"**: Ensure URL starts with `http://` or `https://`
- **"File exceeds 100 MB"**: File size limit protection - download will stop
- **Permission denied**: Choose a writable folder (e.g., your Downloads folder)

## System Requirements
- **OS**: Windows 10 (1809+) or Windows 11
- **CPU**: x64 (Intel/AMD) or ARM64 (Qualcomm)
- **RAM**: 100 MB minimum
- **Storage**: 20 MB for app + space for downloads
- **Internet**: Active connection required

## Download Files

### Windows x64 (Intel/AMD)
- **File**: `PrenivApp Downloader Console.exe`
- **Platform**: `win-x64`
- **For**: Most Windows PCs

### Windows ARM64 (Qualcomm/Surface)
- **File**: `PrenivApp Downloader Console.exe`
- **Size**: ~15.29 MB
- **Platform**: `win-arm64`
- **For**: ARM-based Windows devices

## Security & Privacy
- No data collection or telemetry
- Downloads are direct from source platforms
- Self-contained - no external dependencies
