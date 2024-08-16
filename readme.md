# Voice Memo Transcription README

This Jupyter Notebook contains code for processing voice memos and generating reports based on the transcribed text.

## File Structure

- `main.ipynb`: The main Jupyter Notebook file containing the code.
- `completed/`: Directory to store completed voice memo files.

## Dependencies

- `mlx_whisper`: A module for transcribing voice memos.
- `os`: A module for interacting with the operating system.
- `pathlib`: A module for working with file paths.
- `datetime`: A module for working with dates and times.
- `openai`: A module for interacting with the OpenAI API.
- `shutil`: A module for file operations.
- `dotenv`: A module for loading environment variables from a .env file.

## Usage

1. Place the voice memo files in the `voice_memo_dir` directory.
2. Run the code in the Jupyter Notebook.
3. The transcribed text will be processed and reports will be generated in the `transcription_folder` directory.
4. The completed voice memo files will be moved to the `completed` directory.