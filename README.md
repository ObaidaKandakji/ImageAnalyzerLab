# ImageAnalyzerLab

## Youtube

- https://youtu.be/_eAnZhQ5DDA

## Local Run

1. Start Azurite in VS Code.
2. Create a blob container named `images` in the local emulator.
3. Activate the virtual environment:
   - Windows: `.\.venv\Scripts\activate`
4. Install dependencies:
   - `python -m pip install -r requirements.txt`
5. Start the Functions host:
   - `func start`
6. Upload images to `images` and query:
   - `http://localhost:7071/api/results`


