# yt-video-downloader
# YouTube Video & Playlist Downloader

This repository contains a Python-based tool for downloading YouTube videos and playlists. With an intuitive command-line interface, this tool leverages the `pytube` library to make downloading your favorite videos and playlists easy and efficient.

---

## Features

- Download individual YouTube videos.
- Download entire YouTube playlists.
- Save videos in high quality.
- Simple and user-friendly CLI interface.

---

## Prerequisites

Before using this tool, ensure you have the following:

1. **Python Installed**: This project requires Python 3.7 or higher. Download Python [here](https://www.python.org/downloads/).
2. **Required Libraries**: Install the dependencies using the following command:

```bash
pip install pytube
```

---

## Installation

1. Clone this repository to your local machine:

```bash
git clone https://github.com/jaivishwaj/youtube-downloader.git
```

2. Navigate to the project directory:

```bash
cd youtube-downloader
```

3. Ensure dependencies are installed:

```bash
pip install -r requirements.txt
```

---

## Usage

### Download a Single YouTube Video

Run the following command to download a single video:

```bash
python downloader.py --video <VIDEO_URL>
```

Replace `<VIDEO_URL>` with the URL of the video you want to download.

### Download an Entire YouTube Playlist

Run the following command to download all videos in a playlist:

```bash
python downloader.py --playlist <PLAYLIST_URL>
```

Replace `<PLAYLIST_URL>` with the URL of the playlist you want to download.

---

## Example Commands

- Downloading a single video:

```bash
python downloader.py --video https://www.youtube.com/watch?v=example123
```

- Downloading a playlist:

```bash
python downloader.py --playlist https://www.youtube.com/playlist?list=example456
```

---

## Error Handling

- If a download fails due to network issues, ensure your internet connection is stable and retry.
- If a video or playlist URL is invalid, the tool will prompt you with an error message.

---

## Contributing

Contributions are welcome! If you have suggestions or improvements, feel free to open an issue or create a pull request.

1. Fork the repository.
2. Create a feature branch:

```bash
git checkout -b feature-name
```

3. Commit your changes:

```bash
git commit -m "Add new feature"
```

4. Push to the branch:

```bash
git push origin feature-name
```

5. Open a pull request.

---

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## Author

- **Jai Vishwa J**
- [GitHub](https://github.com/jaivishwaj)
- [LinkedIn](https://www.linkedin.com/in/jaivishwa-j/)

---

## Acknowledgments

- Special thanks to the developers of the `pytube` library for their amazing work.

---

Happy downloading! 🚀
