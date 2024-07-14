# Live Cricket Score Display for Streamlabs OBS

This project provides a simple HTML file (`scoreboard.html`) to display live cricket scores during live streaming using Streamlabs OBS.

## Usage

To use this in your live stream:

1. **Clone or Download**:
   - Clone this repository or download the `scoreboard.html` file directly.

2. **Configure `scoreboard.html`**:
   - Open `scoreboard.html` in a text editor.
   - Replace `YOUR_API_KEY_HERE` with your actual API key obtained from CricAPI.
   - Replace `MATCH_ID_HERE` with the match ID of the cricket match you want to display.

3. **Host the HTML File**:
   - Host the modified `scoreboard.html` file on GitHub Pages or any web hosting service.

4. **Integrate with Streamlabs OBS**:
   - Open Streamlabs OBS.
   - Create a new Scene or use an existing Scene where you want to display the live cricket score.
   - Add a Browser Source to the Scene and paste the URL of your hosted `scoreboard.html` file.

### Notes

- **API Key**: Keep your API key secure and do not expose it publicly in the `scoreboard.html` file.
- **Refresh Interval**: The example code fetches the score every 60 seconds (`60000` milliseconds). You can adjust this interval as needed in your `fetchScore` function.
- **License**: This project is licensed under [MIT License](LICENSE).
