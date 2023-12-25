# YouTube Clone Project

## Overview

This project is a YouTube clone built using React, Tailwind CSS, Rapid API, React Icons, Axios, Moment, and React Player. The main goal of this project is to replicate the essential features of YouTube, including fetching data from the YouTube API, providing a search functionality, displaying suggested videos, and allowing users to watch live videos using the YouTube API from Rapid API.

## Technologies Used

- React: A JavaScript library for building user interfaces.
- Tailwind CSS: A utility-first CSS framework for rapidly building custom designs.
- Rapid API: A platform that enables developers to access various APIs, including the YouTube API for fetching video data.
- React Icons: A library that provides popular icons as React components.
- Axios: A promise-based HTTP client for making requests to APIs.
- Moment: A JavaScript library for parsing, validating, manipulating, and formatting dates.
- React Player: A React component for playing various media types, including YouTube videos.

## Features

### 1. Data from API

- Utilizes the YouTube API from Rapid API to fetch video data.
- Displays video thumbnails, titles, and other relevant information.

### 2. Search

- Implements a search functionality to allow users to search for videos.
- Updates the displayed videos dynamically based on the search query.

### 3. Suggested Videos

- Provides a list of suggested videos to enhance user engagement.
- Recommends videos based on the currently viewed video or user preferences.

### 4. Live Video Playing

- Utilizes the YouTube API from Rapid API to play live videos.
- Allows users to watch live videos seamlessly within the application.


## Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/youtube-clone.git
cd youtube-clone
```

2. Install dependencies:

```bash
npm install
```

3. Create a Rapid API account and obtain the YouTube API key.

4. Set up environment variables:

Create a `.env` file in the project root and add your YouTube API key:

```env
REACT_APP_YOUTUBE_API_KEY=your-api-key
```

## Usage

1. Start the development server:

```bash
npm start
```

2. Open your browser and navigate to `http://localhost:3000` to view the YouTube clone.

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvements, please open an issue or submit a pull request.
